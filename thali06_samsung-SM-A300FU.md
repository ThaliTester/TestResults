#### Test 60124347d4f5b03_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
--------- beginning of system
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
D/SSRM:n  ( 1019): SIOP:: AP = 300
,D/AndroidRuntime( 5405): 
D/AndroidRuntime( 5405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5405): CheckJNI is OFF
D/AndroidRuntime( 5405): readGMSProperty: start
D/AndroidRuntime( 5405): readGMSProperty: already setted!!
D/AndroidRuntime( 5405): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5405): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5405): readGMSProperty: end
D/AndroidRuntime( 5405): addProductProperty: start
E/AffinityControl( 5405): AffinityControl: registerfunction enter
D/AndroidRuntime( 5405): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/Launcher.HomeView( 1476): onPause
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1476
D/AndroidRuntime( 5405): Shutting down VM
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : -2122120936
V/TaskCloserActivity( 4905): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 5417): MountEmulatedStorage()
E/Zygote  ( 5417): v2
I/libpersona( 5417): KNOX_SDCARD checking this for 10338
I/libpersona( 5417): KNOX_SDCARD not a persona
I/SELinux ( 5417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5417 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5417): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1476): updateVisibility : ActivityRecord{1b0b953d token=android.os.BinderProxy@e00bb99 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 5417): TimaSignature is unavailable
D/ActivityThread( 5417): Added TimaKeyStore provider
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/Launcher.HomeView( 1476): onStop
V/ActivityThread( 1476): updateVisibility : ActivityRecord{1b0b953d token=android.os.BinderProxy@e00bb99 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Launcher( 1476): onTrimMemory. Level: 20
D/SensorManager( 1019): unregisterListener ::   
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 5405): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 5417): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5417): Time to load native libraries: 2 ms (timestamps 7266-7268)
I/LibraryLoader( 5417): Expected native library version number "",actual native library version number ""
,D/SensorService( 1019): [SO] -0.326 -0.019 9.922
,D/SensorService( 1019): [SO] [100 -> 255]
,E/SMD     (  292): DCD OFF
,V/WebViewChromiumFactoryProvider( 5417): Binding Chromium to main looper Looper (main, tid 1) {3d1d6021}
,I/LibraryLoader( 5417): Expected native library version number "",actual native library version number ""
,I/chromium( 5417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5417): Initializing chromium process, singleProcess=true
,W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5417): ApplicationContext is null in ApplicationStatus
,W/chromium( 5417): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5417): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5417): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5417): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5417): Local Branch: 
I/Adreno-EGL( 5417): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5417): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5417):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5417): 1052300195: getState() :  mService = null. Returning STATE_OFF
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
,W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5417): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5417): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5417): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 5417): CordovaWebView is running on device made by: samsung
,W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5417): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!,
W/chromium( 5417): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5417): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 5417): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5417
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5417): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5417): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5417): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5417): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +811ms
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{e3ab63b u0 com.test.thalitest/.MainActivity t22} time:97843
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 5417): Timeline: Activity_idle id: android.os.BinderProxy@290e47d0 time:97852
,I/SamsungIME( 1789): getCurrentCandidateView
,D/SamsungIME( 1789): Dismiss ExpandCandiate
,I/SamsungIME( 1789): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1789): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1789): KeybaordView init() : load resources
,W/BindingManager( 5417): Cannot call determinedVisibility() - never saw a connection for the pid: 5417
,I/SamsungIME( 1789): getCurrentKeyboard
I/SamsungIME( 1789): getTextKeyboard
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/8)
D/SamsungIME( 1789): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/JsMessageQueue( 5417): Set native->JS mode to OnlineEventsBridgeMode
,D/SensorService( 1019): [SO] -0.326 -0.019 9.922
,D/jxcore_app_log( 5417): JniHelper::setJavaVM(0xb8e4b448), pthread_self() = -1187373472
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5417): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2687f0df added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5417): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5417): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24bbfb added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5417): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5417): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5417): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5417): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5417): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5417): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5417): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5417): Initializing JXcore engine
W/jxcore-log( 5417): JXcore engine is ready
,E/audit   ( 1788): type=1400 msg=audit(1457399575.820:203): avc:  denied  { ioctl } for  pid=5470 comm="Thread-946" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1788):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1788): type=1300 msg=audit(1457399575.820:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9caf98f8 items=0 ppid=316 ppcomm=main pid=5470 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-946" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1788): type=1320 msg=audit(1457399575.820:203): 
,W/jxcore-log( 5417): Starting JXcore engine
,W/jxcore-log( 5417): Platform android
W/jxcore-log( 5417): 
W/jxcore-log( 5417): Process ARCH arm
W/jxcore-log( 5417): 
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 5417): JXcore Cordova bridge is ready!
I/jxcore-log( 5417): 
,W/jxcore-log( 5417): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5417): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5417): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5417): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5417): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 5417
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,V/AlarmManager( 1019): waitForAlarm result :4
,W/PluginManager( 5417): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1476): onRestart, Launcher: 651091293
,D/Launcher( 1476): onStart, Launcher: 651091293
D/Launcher.HomeView( 1476): onStart
,D/Launcher( 1476): onResume, Launcher: 651091293
D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1476): onResume
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1476): onResume
,D/SensorManager( 1019): unregisterListener ::   
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10011
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1019): Focus entered window: 1476
,D/GalleryCacheReady( 4350): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1476): log_dcs ThreadedRenderer::initialize entered! 
D/Mms/UIEventReceiver( 4987): ui event
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2395): onReceive by home
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
W/IInputConnectionWrapper( 5417): showStatusIcon on inactive InputConnection
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/SamsungIME( 1789): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,V/TaskCloserActivity( 4905): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,I/splitIntent( 1019): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@e00bb99 time:100520
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,E/Zygote  ( 5478): MountEmulatedStorage(),
,I/libpersona( 5478): KNOX_SDCARD checking this for 10102
E/Zygote  ( 5478): v2
I/libpersona( 5478): KNOX_SDCARD not a persona
I/SELinux ( 5478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5478 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5478): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Displayed Component not be shown by security: +144ms (total +14s560ms)
,D/TimaKeyStoreProvider( 5478): TimaSignature is unavailable
,D/ActivityThread( 5478): Added TimaKeyStore provider
,W/ResourcesManager( 5478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel_SMS( 5478): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5478): MmsConfig.loadMmsSettings
I/Babel_SMS( 5478): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 5478): MmsConfig.loadFromDatabase
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 4724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4724): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4724): [1] 5.onFinished: Scheduling replication attempt 2.
D/SensorService( 1019): [SO] currT = 100841086000, prevT = 100361162000, diff = 479924000, [-0.326 -0.038 9.922]
D/SensorService( 1019): [SO] -0.326 -0.038 9.922
D/SensorService( 1019): [SO] [100 -> 255]
,E/Babel_SMS( 5478): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5478): MmsConfig.loadFromResources
,E/Babel_SMS( 5478): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5478): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  287): getCameraInfo: X
,W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  287): getCameraInfo: X
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5478): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5478): startup - clean
,I/Babel   ( 5478): deleted: false for 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{2bbd3da0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:100971
,I/ActivityManager( 1019): Killing 4760:com.google.android.gms:car/u0a11 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,W/VideoCapabilities( 5478): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5478): Unsupported mime audio/evrc
,W/AudioCapabilities( 5478): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5478): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5478): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5478): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5478): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5478): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5478): Unsupported mime audio/evrc
,W/VideoCapabilities( 5478): Unsupported mime video/wvc1
,W/VideoCapabilities( 5478): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5478): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5478): Unsupported mime video/wvc1
,W/VideoCapabilities( 5478): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5478): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 5478): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5478): Unsupported mime video/mp43
,W/libprocessgroup( 1019): failed to open /acct/uid_10011/pid_4760/cgroup.procs: No such file or directory
,W/VideoCapabilities( 5478): Unsupported mime video/sorenson
,W/VideoCapabilities( 5478): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5478): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5478): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5478): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5478): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5478): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1019): Killing 3932:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/vclib   ( 5478): onServiceConnected
W/Babel   ( 5478): Attempted to change video mute state without an active call.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_3932/cgroup.procs: No such file or directory
,E/SQLiteLog( 1653): (10) POSIX Error : 11 SQLite Error : 3850,
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,V/AlarmManager( 1019): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1019): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1019): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1568): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1568): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1568): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1568): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,E/accuweather( 1568): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 02 13
,W/OpenGLRenderer( 1476): SFEffectCache::get: create texture(0xa1f19724): name, size, mSize = 35, 85680, 293260
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1173 (0x0)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 310
,D/FactoryTest( 4623): Not factory mode
D/FactoryTest( 4623): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4623): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4623): still no open session command from host, so toast
,W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4623): Timeline: Activity_launch_request id:com.android.settings time:107073,
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
,I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire(),
,D/FocusedStackFrame( 1019): Set to : 0
,D/Launcher.HomeView( 1476): onPause,
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 1476
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 4623): started activity for popup
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 4905): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=0)
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1019): [SO] changed settle time [1]
,D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=1)
,D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/ResourcesManager( 4623): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4623): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4623): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4623): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 4623): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4623): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/SettingsReceiverActivity( 4623): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus entered window: 1476
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1019): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1851391d attribute=null, token = android.os.BinderProxy@436b2b
,E/ActivityManager( 1019): Invalid thumbnail dimensions: 488x488
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,D/SettingsReceiverActivity( 4623): dev.kiessupport is : TRUE
,D/PhoneWindow( 4623): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4623): *FMB* installDecor flags : 8388610
,D/Launcher( 1476): onResume, Launcher: 651091293
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1476): onResume
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1476): onResume
,D/ActivityManager( 1019): handle home activity for 0
,I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4350): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@e00bb99 time:107290
,D/SensorService( 1019): [SO] -0.326 -0.019 9.922
,D/SensorService( 1019): [SO] [100 -> 255]
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/Recents_RecreateReceiver( 2395): onReceive by home
,V/TaskCloserActivity( 4905): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 4987): ui event
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,I/splitIntent( 1019): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=0)
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1019): [SO] changed settle time [0]
,D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=1)
D/SensorService( 1019): [SO] AR_init
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,D/SensorService( 1019): [SO] currT = 108031238000, prevT = 107570978000, diff = 460260000, [-0.326 -0.019 9.922]
,D/SensorService( 1019): [SO] -0.326 -0.019 9.922
D/SensorService( 1019): [SO] [100 -> 255]
,E/Watchdog( 1019): !@Sync 3
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/PowerManagerService( 1019): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1019): lcd : 138 +
,D/lights  ( 1019): lcd : 138 -
,D/lights  ( 1019): lcd : 104 +
,D/lights  ( 1019): lcd : 104 -
,D/lights  ( 1019): lcd : 71 +
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1019): lcd : 71 -
D/lights  ( 1019): lcd : 15 +
,D/lights  ( 1019): lcd : 15 -
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,V/WindowOrientationListener( 1019): WindowOrientationListener disabled,
D/PowerManagerService( 1019): [s] UserActivityState : 2 -> 4
D/SensorService( 1019): [SO] activate (ident=0xb992ba88, enabled=0)
I/PowerManagerService( 1019): Nap time (uid 1000)...,
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1019): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/SurfaceFlinger(  258): id=14 createSurf (540x960),-1 flag=20004, DolorFade
I/PowerManagerService( 1019): !@[ps] Screen__Off - 1 :  dream(timeout) (2),
I/PowerManagerService( 1019): Going to sleep due to screen timeout (uid 1000)...,
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1019): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1019): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1019): handleSandman : startDream(true)
,E/PowerManagerService( 1019): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1019): Sleeping (uid 1000)...,
D/PowerManagerService( 1019): [s] UserActivityState : 4 -> 0,
D/PowerManagerService( 1019): Excessive delay in ColorFade : createSurface: 13ms
,D/SensorManager( 1019): unregisterListener ::   
D/KeyguardViewMediator( 1173): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1173): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1173): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1173): notifyScreenOffLocked
D/Launcher.HomeView( 1476): onPause
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/KeyguardViewMediator( 1173): timeout : 5000
,D/PowerManagerService( 1019): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/DisplayPowerController( 1019): ColorFade: onAnimationStart
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 160 -> 160
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
,D/KeyguardViewMediator( 1173): setting alarm to turn off keyguard, seq = 2
V/TaskCloserActivity( 4905): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/KeyguardViewMediator( 1173): handleNotifyScreenOff
D/VolumePanel( 1173): onScreenTurnedOff()
D/VolumePanel( 1173): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1173): onScreenTurnedOff
,V/ActivityThread( 1476): updateVisibility : ActivityRecord{1b0b953d token=android.os.BinderProxy@e00bb99 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1476): onStop
,D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1019) 
,D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/BatteryService( 1019): turn on LED for fully charged
E/lights  ( 1019): write_int failed to open -1
,D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SmartFaceService( 1019): fail to set sysfs 0
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1019):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9d88f7fc
I/WifiNative-HAL( 1019): Could not start hal
,D/SamsungIME( 1789): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/NotificationService( 1019): ACTION_SCREEN_OFF
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1019): write_int failed to open -1
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off,
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1019): Bridge Server is not available
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1398): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1019): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1438): call the applyRouting
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,D/accuweather( 1568): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF,
D/accuweather( 1568): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1568): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1616): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1568): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1568): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1568): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1568): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1616): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1808): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1616): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1019): SIOP:: AP = 310
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1568): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1568): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1568): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1019): !@ ColorFade entry
,D/DisplayPowerController( 1019): ColorFade: onAnimationEnd
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1019): lcd : 0 +
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/lights  ( 1019): lcd : 0 -
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService-JNI( 1019): Excessive delay in MISC setInteractive(false) while turning screen off: 53ms
I/QCOM PowerHAL( 1019): Got set_interactive hint
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb8f7d690
D/PowerManagerService( 1019): Excessive delay in nativeSetInteractive(false): 55ms
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
D/DisplayManagerService( 1019): !@display_state: ON -> OFF
I/DisplayManagerService( 1019): Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,V/ActivityManager( 1019): Display changed displayId=0
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1173): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a227c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1197333192)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1197333192) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8a227c8
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0,
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2,
D/PowerManagerService( 1019): Excessive delay in !@display_state: OFF: 240ms
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node,
D/PowerManagerService( 1019): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 295ms
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,I/PowerManagerService( 1019): [PWL] Off : 0s ago
D/SurfaceControl( 1019): Excessive delay in setPowerMode(): 239ms
I/libsuspend( 1019): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1019): !@autosuspend_wakeup_count_enable done
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1,
,V/AlarmManager( 1019): waitForAlarm result :4
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardViewMediator( 1173): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1173): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1173): *** Keyguard wallpaper service already unbounded
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4724): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4724): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 5s ago
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 15s ago,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/BatteryService( 1019): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 4,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PowerManagerService( 1019): [PWL] Off : 30s ago
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 50162(3MB) AllocSpace objects, 42(1586KB) LOS objects, 33% free, 24MB/36MB, paused 2.228ms total 144.801ms
,D/Finsky  ( 4724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4724): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4724): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1019): [PWL] Off : 50s ago,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4724): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4724): [1] 5.onFinished: Scheduling replication attempt 5.
,E/Watchdog( 1019): !@Sync 5
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4724): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4724): [1] 5.onFinished: Giving up after 6 failures.
,I/PowerManagerService( 1019): [PWL] Off : 75s ago,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 6,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1019): waitForAlarm result :4
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 8,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1019): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1019): [PWL] Off : 225s ago,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1019): stay LED for fully charged
,I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 11,
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1653): Explicit concurrent mark sweep GC freed 20437(1159KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 938us total 43.988ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1653): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1653): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1653): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1653): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4724): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4724): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4724): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4724): Ignoring header User-Agent because its value was null.
I/System.out( 4724): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
,I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10026
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 12,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=403947 batch.start=422736
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 13,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1019): !@Sync 14
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 15
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 16
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 390s ago,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 17,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 18
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/Atfwd_Daemon(  328): Stop the daemon....,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 19
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 20
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 21,
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1653): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1653): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1653): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1653): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 4724): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4724): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4724): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4724): Ignoring header User-Agent because its value was null.
I/System.out( 4724): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10026
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 22,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 23
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 24
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 25,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 680s ago,
,E/Watchdog( 1019): !@Sync 26,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 27
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 28,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1019): !@Sync 29
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,E/SMD     (  292): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 30,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1019): !@Sync 31,
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
W/GLSActivity( 1653): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1653): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1653): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1653): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
E/PlayEventLogger( 4724): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4724): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4724): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4724): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4724): Ignoring header User-Agent because its value was null.
I/System.out( 4724): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10026
,I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 32
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 33,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 34,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 950s ago,
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1019): !@Sync 35,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 36
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 37,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 38,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/BatteryService( 1019): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1050s ago,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 39
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1457400691948
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1457400691957
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 40
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 41,
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1653): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1653): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1653): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1653): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1653): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1653): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1653): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1653): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1653): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
,I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4724): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4724): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4724): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4724): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4724): Ignoring header User-Agent because its value was null.
I/System.out( 4724): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  282): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  282): getNetworkForDns: using netid 0 for uid 10026
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1155s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1019): !@Sync 42
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6020): 
D/AndroidRuntime( 6020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6020): CheckJNI is OFF
D/AndroidRuntime( 6020): readGMSProperty: start
D/AndroidRuntime( 6020): readGMSProperty: already setted!!
D/AndroidRuntime( 6020): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6020): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6020): readGMSProperty: end
D/AndroidRuntime( 6020): addProductProperty: start
E/AffinityControl( 6020): AffinityControl: registerfunction enter
D/AndroidRuntime( 6020): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1019): START PACKAGE DELETE: observer{406499040}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5417:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{164b6d2c com.example.hello/10346} due to missing metadata
W/ActivityManager( 1019): Spurious death for ProcessRecord{1384e599 5417:com.test.thalitest/u0a338}, curProc for 5417: null
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3700): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 814us total 38.225ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5320): Explicit concurrent mark sweep GC freed 52(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 1.099ms total 59.777ms
E/SamsungIME( 1789): mOCRHelper is null
W/GeofencerStateMachine( 1635): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3485): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 08 02:33:04 GMT+01:00 2016
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3485): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6033): MountEmulatedStorage()
E/Zygote  ( 6033): v2
I/libpersona( 6033): KNOX_SDCARD checking this for 10090
I/libpersona( 6033): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): onCreate()
I/SELinux ( 6033): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3485): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6033 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6033): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6033): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3485): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/TimaKeyStoreProvider( 6033): TimaSignature is unavailable
D/ActivityThread( 6033): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): listeningToPackageRemoved().START
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1019): Explicit concurrent mark sweep GC freed 28517(3MB) AllocSpace objects, 118(1897KB) LOS objects, 33% free, 24MB/36MB, paused 2.774ms total 241.462ms
I/art     ( 1019): WaitForGcToComplete blocked for 161.230ms for cause Explicit
D/RegisteredServicesCache( 1438): empty dynamic service
D/RCPManagerService( 1019): PackageReceiver onReceive()
D/elm:15121( 6033): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 6033): ELMEngine.ELMEngine( context ).
D/elm:15121( 6033): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6033): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6033): ElmAgentService : onCreate()
D/elm:15121( 6033): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6033): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6033): MDMBridge.getInstance()
D/elm:15121( 6033): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6033): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3485): KLMSIntentService(): onDestroy()
D/elm:15121( 6033): ElmAgentService : onDestroy().
E/Watchdog( 1019): !@Sync 43
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1019): removeObsoleteFile: deleting file=22_task.xml
D/TaskPersister( 1019): removeObsoleteFile: deleting file=22_task_thumbnail.png
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 5055): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5055): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5055): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5055): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5139): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5139): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/art     ( 1019): Explicit concurrent mark sweep GC freed 15257(845KB) AllocSpace objects, 5(994KB) LOS objects, 33% free, 23MB/35MB, paused 13.445ms total 218.073ms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4350): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 4987): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/Mms/FreeMessageReceiverService( 4987): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4987): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1019): List of disabled apps :
W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/Compatibility( 5220): onReceive() it will make start service
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5220): onHandleIntent()
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Compatibility( 5220): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6053): MountEmulatedStorage()
E/Zygote  ( 6053): v2
I/libpersona( 6053): KNOX_SDCARD checking this for 10055
I/libpersona( 6053): KNOX_SDCARD not a persona
I/SELinux ( 6053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6053 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5220): found: 2
D/Compatibility( 5220): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5220): skipping ResolveInfo{279e5e07 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5220): considering ResolveInfo{1f7e5b34 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5220): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/SELinux ( 6053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Compatibility( 5220): enabling receiver ResolveInfo{26cedd5d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/SELinux ( 6053): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5220): enabling receiver ResolveInfo{2074c6d2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5220): enabling receiver ResolveInfo{3eb8d3a3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/PackageManager( 1019): delete codoeFile: 
D/Compatibility( 5220): enabling receiver ResolveInfo{183ff6a0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10338 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{406499040}
D/Compatibility( 5220): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6053): TimaSignature is unavailable
D/ActivityThread( 6053): Added TimaKeyStore provider
D/AndroidRuntime( 6020): Shutting down VM
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1019): onPackageRemoved : com.test.thalitest
D/UserAnalysis.PlaceProvider( 6053): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6053): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6053): SecurePlaceDbHelper() 
D/UserAnalysis( 6053): Create SecureDbHelper
D/IntelligenceServiceApplication( 6053): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6053): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/IntelligenceServiceApplication( 6053): no applications having user consent for prediction
W/ContextImpl( 5243): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 1000
I/libpersona( 6070): KNOX_SDCARD not a persona
I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 4591:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 6053): 901635276: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 6053): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
I/art     (  316): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 969us total 23.369ms
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6053): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
D/ActivityThread( 6070): Added TimaKeyStore provider
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 679us total 18.320ms
W/ResourcesManager( 6070): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.620ms
D/RCPManager( 6070):  in createShortcut() for packageName: com.test.thalitest userId0
W/art     ( 6020): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/RCPManagerService( 1019):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
W/ContextImpl( 5261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
D/FilterInstaller( 5261): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5261): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5261): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5261): before removeFromFS
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4591/cgroup.procs: No such file or directory
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6087): MountEmulatedStorage()
E/Zygote  ( 6087): v2
I/libpersona( 6087): KNOX_SDCARD checking this for 1000
I/libpersona( 6087): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6087): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 6099): MountEmulatedStorage()
E/Zygote  ( 6099): v2
I/libpersona( 6099): KNOX_SDCARD checking this for 10095
I/libpersona( 6099): KNOX_SDCARD not a persona
I/SELinux ( 6099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6099 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 6087): TimaSignature is unavailable
D/ActivityThread( 6087): Added TimaKeyStore provider
E/SELinux ( 6099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6099): TimaSignature is unavailable
D/ActivityThread( 6099): Added TimaKeyStore provider
W/ContextImpl( 6087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6120): MountEmulatedStorage()
E/Zygote  ( 6120): v2
I/libpersona( 6120): KNOX_SDCARD checking this for 1000
I/libpersona( 6120): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 6087): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6087): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6087): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6087): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6087): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6087): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6087): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6087): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6087): Process: com.android.keychain, PID: 6087
E/AndroidRuntime( 6087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6087): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6087): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6087): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6087): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6087): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PreloadFilterInstaller( 6099): uses FILTER_DB_VER_1
E/SQLiteLog( 6099): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 6120): TimaSignature is unavailable
E/SQLiteDatabase( 6099): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6099): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6099): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6099): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6099): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6099): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6099): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6099): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6099): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6099): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6099): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6099): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6099): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6099): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6099): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6099): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6099): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6099): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6099): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6099): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6099): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6099): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6099): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6099): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6099): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6099): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6099): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6099): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6099): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6099): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6099): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6099): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityThread( 6120): Added TimaKeyStore provider
W/SQLiteOpenHelper( 6099): Opened filter.db in read-only mode
E/SQLiteLog( 6099): (284) automatic index on titles(filter_id)
E/SQLiteLog( 6099): (284) automatic index on titles(filter_id)

```
