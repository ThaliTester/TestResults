#### Test 6122644500803c8_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
,E/SMD     (  306): DCD ON
D/AndroidRuntime( 6506): 
D/AndroidRuntime( 6506): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6506): CheckJNI is OFF
D/AndroidRuntime( 6506): readGMSProperty: start
D/AndroidRuntime( 6506): readGMSProperty: already setted!!
D/AndroidRuntime( 6506): readGMSProperty: end
D/AndroidRuntime( 6506): addProductProperty: start
--------- beginning of system
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl( 6506): AffinityControl: registerfunction enter
D/AndroidRuntime( 6506): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  909): inState():  stateMachine is null !!
I/PersonaManagerService(  909): PersonaId don't exist
I/ActivityManager(  909): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  909): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ResourcesManager(  909): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  909): mDVFSHelper.acquire()
D/FocusedStackFrame(  909): Set to : 0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6521 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6521): MountEmulatedStorage()
E/Zygote  ( 6521): v2
I/libpersona( 6521): KNOX_SDCARD checking this for 10079
I/libpersona( 6521): KNOX_SDCARD not a persona
D/PointerIcon(  909): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  909): setMouseCustomIcon IconType is same.101
D/PointerIcon(  909): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  909): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6506): Shutting down VM
I/SELinux ( 6521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6521): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6521): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6521): TimaSignature is unavailable
D/ActivityThread( 6521): Added TimaKeyStore provider
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  909): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1465): destroyHardwareResources():327400354
D/ConnectivityService(  909): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6521): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  266): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger(  266): id=8 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1834): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1465): updateVisibility : ActivityRecord{1b69606c token=android.os.BinderProxy@20d19873 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1465): onTrimMemory. Level: 20
,I/WebViewFactory( 6521): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 6521): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6521): Time to load native libraries: 2 ms (timestamps 4049-4051)
I/LibraryLoader( 6521): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6521): Binding Chromium to main looper Looper (main, tid 1) {d596bb5}
I/LibraryLoader( 6521): Expected native library version number "",actual native library version number ""
I/chromium( 6521): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6521): Initializing chromium process, singleProcess=true
W/art     ( 6521): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6521): ApplicationContext is null in ApplicationStatus
W/chromium( 6521): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 6521): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6521): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6521): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 6521): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6521): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6521): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6521): Local Branch: mybranch5813579
I/Adreno-EGL( 6521): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6521): Local Patches: NONE
I/Adreno-EGL( 6521): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 6521): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
D/BluetoothAdapter( 6521): 541024919: getState() :  mService = null. Returning STATE_OFF
W/art     ( 6521): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6521): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6521): CordovaWebView is running on device made by: samsung
W/art     ( 6521): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6521): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  909): Activity pause timeout for ActivityRecord{24938aab u0 com.test.thalitest/.MainActivity t9}
D/Activity( 6521): performCreate Call secproduct feature valuefalse
D/Activity( 6521): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6521): Render dirty regions requested: true
D/ActivityManager(  909): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  909): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  909): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  909): handleActiveUserChange for user 0
D/PersonaManagerService(  909): getPersonasForUser(): returning null!
V/ActivityThread( 6521): updateVisibility : ActivityRecord{1c9abeb4 token=android.os.BinderProxy@4c03c6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  266): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/OpenGLRenderer( 6521): Initialized EGL, version 1.4
D/PointerIcon(  909): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  909): setMouseCustomIcon IconType is same.101
D/PointerIcon(  909): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  909): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6521): HWUI protection enabled for context ,  &this =0xb3ae7fb0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6521): Enabling debug mode 0
D/InputMethodManagerService(  909): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1738): getCurrentCandidateView
W/ActivityManager(  909): mDVFSHelper.release()
I/Timeline(  909): Timeline: Activity_windows_visible id: ActivityRecord{24938aab u0 com.test.thalitest/.MainActivity t9} time:134583
W/IInputConnectionWrapper( 6521): showStatusIcon on inactive InputConnection
I/Timeline( 6521): Timeline: Activity_idle id: android.os.BinderProxy@4c03c6 time:134593
W/BindingManager( 6521): Cannot call determinedVisibility() - never saw a connection for the pid: 6521
D/SamsungIME( 1738): Dismiss ExpandCandiate
I/SamsungIME( 1738): getDebugLevel  : 0x4f4c
I/SamsungIME( 1738): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6521): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1738): KeybaordView init() : load resources
I/SamsungIME( 1738): getCurrentKeyboard
I/SamsungIME( 1738): getTextKeyboard
D/SamsungIME( 1738): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6521): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357923200
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32e0954d added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6521): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340b4350 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6521): addListener: New listener added - the number of listeners is now 1
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6521): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6521): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6521): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6521): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6521): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 6521): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/SamsungIME( 1738): [SwiftkeyWrapper] currentLangauge : 1701729619
D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): stay LED for fully charged
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,W/jxcore-log( 6521): Initializing JXcore engine
,W/jxcore-log( 6521): JXcore engine is ready
,E/SMD     (  306): DCD ON
,E/auditd  ( 1870): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  909): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  909): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
,E/audit   ( 1870): type=1400 msg=audit(1456845401.782:201): avc:  denied  { ioctl } for  pid=6587 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
,E/audit   ( 1870):  SEPF_SM-N9005_5.0-1_0032
E/audit   ( 1870): 
,E/audit   ( 1870): type=1300 msg=audit(1456845401.782:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9b2fb8d8 items=0 ppid=332 ppcomm=main pid=6587 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1870): type=1320 msg=audit(1456845401.782:201): 
,W/jxcore-log( 6521): Starting JXcore engine
,I/ActivityManager(  909): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/Zygote  ( 6592): MountEmulatedStorage()
,E/Zygote  ( 6592): v2
I/libpersona( 6592): KNOX_SDCARD checking this for 1000
I/libpersona( 6592): KNOX_SDCARD not a persona
,I/SELinux ( 6592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6592): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6592): TimaSignature is unavailable
,D/ActivityThread( 6592): Added TimaKeyStore provider
,W/jxcore-log( 6521): Platform android
W/jxcore-log( 6521): 
W/jxcore-log( 6521): Process ARCH arm
W/jxcore-log( 6521): 
,D/ResourcesManager( 6592): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6592):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6592):  SeDenialReceiver : File path = null
,I/ActivityManager(  909): Killing 5033:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/jxcore-log( 6521): JXcore Cordova bridge is ready!
I/jxcore-log( 6521): 
,W/jxcore-log( 6521): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 6521): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/Watchdog(  909): !@Sync 4
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6521): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 6521): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 6521): BLE multiple advertisement supported
I/jxcore-log( 6521): 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/jxcore-log( 6521): My device name is: samsung-SM-N9005
I/jxcore-log( 6521): 
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 350, PST = 342, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/PackageManager(  909): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6521): 
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6521): 
,I/io.jxcore.node.ConnectivityInfo( 6521): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6521):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6521):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6521):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 6521):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6521):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 6521):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 6521):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 6521):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 6521): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 6521): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6521): 
,E/SMD     (  306): DCD ON
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6521): 
,I/jxcore-log( 6521): Unit Test app is loaded
I/jxcore-log( 6521): 
,I/chromium( 6521): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log( 6521): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 6521): 
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 350, PST = 336, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :8
,I/PowerManagerService(  909): [PWL] Off : 105s ago
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1780): disconnect managed GoogleApiClient
,D/SSRM:n  (  909): SIOP:: AP = 310, PST = 332, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,V/AlarmManager(  909): waitForAlarm result :4
,D/NtpTrustedTime(  909): forceRefresh() from cache miss
,D/NtpTrustedTime(  909): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): stay LED for fully charged
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 5
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 310, PST = 330, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 300, PST = 324, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  909): [PWL] Off : 140s ago
,D/SSRM:n  (  909): SIOP:: AP = 300, PST = 316, CUR = 450
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  909): waitForAlarm result :4
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/VacuumService( 1780): Vacuum at: now=1456845460457 tag=VacuumService
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 6
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :4
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): stay LED for fully charged
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 300, PST = 313, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :8
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 311, CUR = 450
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :8
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/Watchdog(  909): !@Sync 7
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PowerManagerService(  909): [PWL] Off : 180s ago
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 310, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 304, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 8
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate,
E/SMD     (  306): DCD ON
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  909): [PWL] Off : 225s ago
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 9
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 292, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  909): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  909): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  909): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  909): initializing...
,I/TLC_TIMA_PKM_initialize(  909): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  909): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  909): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  909): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  909): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  909): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  909): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  909): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  909): App is not loaded in QSEE
,D/QSEECOMAPI: (  909): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  909): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  909): Trustlet response is completed
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  909): [PWL] Off : 275s ago
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/NtpTrustedTime(  909): forceRefresh() from cache miss
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/NtpTrustedTime(  909): forceRefresh Fail.
,E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): stay LED for fully charged
,I/ActivityManager(  909): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6692 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 6692): MountEmulatedStorage()
,E/Zygote  ( 6692): v2
I/libpersona( 6692): KNOX_SDCARD checking this for 10096
,I/libpersona( 6692): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,I/SELinux ( 6692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6692): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6692): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/TimaKeyStoreProvider( 6692): TimaSignature is unavailable
,D/ActivityThread( 6692): Added TimaKeyStore provider
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 6692): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  909): Killing 5305:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 11
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5627): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 12
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 330s ago
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :8
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 13
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:n  (  909): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/Watchdog(  909): !@Sync 14
,E/SMD     (  306): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  909): [PWL] Off : 390s ago
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 285, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 15
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 284, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,I/bootchecker(  335): bootchecker wake up!!
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  909): !@Sync 16
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  909): [PWL] Off : 455s ago
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 17
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  306): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  909): !@Sync 18
,E/SMD     (  306): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 525s ago
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,I/Atfwd_Daemon(  347): Stop the daemon....
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 19
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  909): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  909): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  909): TimaServiceHandler.handleMessage what =1
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/Watchdog(  909): !@Sync 21
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 600s ago
,E/SMD     (  306): DCD ON
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5627): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  909): setPowerConnected  = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/Watchdog(  909): !@Sync 22
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  909): !@Sync 23
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 680s ago
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  909): !@Sync 24
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  909): !@Sync 25
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 26
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,V/AlarmManager(  909): waitForAlarm result :8
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  909): [PWL] Off : 765s ago
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 27
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 28
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 29
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  909): [PWL] Off : 855s ago
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/TimaService(  909): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  909): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  909): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): stay LED for fully charged
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 31
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5627): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/Watchdog(  909): !@Sync 32
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): stay LED for fully charged
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 950s ago
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 33
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true,
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 34
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 35
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 36
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  909): [PWL] Off : 1050s ago
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  909): stay LED for fully charged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 37
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  909): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 38
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 39
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 1155s ago
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,D/TimaService(  909): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  909): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  909): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  909): User[0] Flushing usage stats to disk
,E/SMD     (  306): DCD ON
,I/ApplicationUsage(  909): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  909): Updating Usage Statistics in DB @ 1456846482083
,I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
,W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  909): ::getAppControlDB: Exception to create DB
W/System.err(  909): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  909): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  909): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  909): Done Updating Usage Statistics in DB @ 1456846482258
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  909): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  909): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  909): !@Sync 40
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 41
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1780): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5627): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  909): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 42
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  909): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 43
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): Plugged
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,I/PowerManagerService(  909): [PWL] Off : 1265s ago
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  909): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryService(  909): stay LED for fully charged
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  909): !@Sync 44
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  909): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  909): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  909): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  909): Plugged
,I/MotionRecognitionService(  909): setPowerConnected  = true
,D/BatteryService(  909): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  306): DCD ON
,E/SMD     (  306): DCD ON
,D/BatteryService(  909): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  306): DCD ON
D/AndroidRuntime( 6799): 
D/AndroidRuntime( 6799): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6799): CheckJNI is OFF
D/AndroidRuntime( 6799): readGMSProperty: start
D/AndroidRuntime( 6799): readGMSProperty: already setted!!
D/AndroidRuntime( 6799): readGMSProperty: end
D/AndroidRuntime( 6799): addProductProperty: start
E/AffinityControl( 6799): AffinityControl: registerfunction enter
D/AndroidRuntime( 6799): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  909): START PACKAGE DELETE: observer{731850916}
D/PackageManager(  909): pkg{<packageName>}
D/PackageManager(  909): user{0}
D/PackageManager(  909): caller{2000}
D/PackageManager(  909): flags{3}
D/PersonaManagerService(  909): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  909): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  909): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  909): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  909): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  909): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  909): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  909): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  909): getApplicationUninstallationEnabled
D/ApplicationPolicy(  909): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  909): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  909): Killing 6521:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  909): Skipping PackageSetting{92c6a94 com.example.hello/10078} due to missing metadata
E/SMD     (  306): DCD ON
I/WindowState(  909): WIN DEATH: Window{2acdc849 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=11 Removed NainActivit (6/8)
I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
E/libprocessgroup(  909): failed to kill 1 processes for processgroup 6521
D/PointerIcon(  909): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  909): setMouseCustomIcon IconType is same.101
D/PointerIcon(  909): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
I/ActivityManager(  909):   Force finishing activity ActivityRecord{24938aab u0 com.test.thalitest/.MainActivity t9}
D/PointerIcon(  909): setHoveringSpenCustomIcon IconType is same.1
D/FocusedStackFrame(  909): Set to : 0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  909):   Force finishing activity ActivityRecord{24938aab u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  909): Duplicate finish request for ActivityRecord{24938aab u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 1501): Explicit concurrent mark sweep GC freed 1207(60KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/32MB, paused 392us total 23.619ms
I/art     ( 6346): Explicit concurrent mark sweep GC freed 9632(549KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 321us total 33.591ms
W/ActivityManager(  909): Spurious death for ProcessRecord{23fe760d 6521:com.test.thalitest/u0a79}, curProc for 6521: null
D/ConnectivityService(  909): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  909): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1738): mOCRHelper is null
W/GeofencerStateMachine( 1780): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 1465): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1465): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/art     ( 5785): Explicit concurrent mark sweep GC freed 7148(325KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 302us total 45.470ms
W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/InputReader(  909): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1465): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/art     ( 5280): Explicit concurrent mark sweep GC freed 34701(1898KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 544us total 50.161ms
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/art     ( 2057): Explicit concurrent mark sweep GC freed 3094(127KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 21MB/29MB, paused 491us total 48.904ms
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/Zygote  ( 6829): MountEmulatedStorage()
E/Zygote  ( 6829): v2
I/libpersona( 6829): KNOX_SDCARD checking this for 10023
I/libpersona( 6829): KNOX_SDCARD not a persona
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/ActivityManager(  909): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6829 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/SELinux ( 6829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6829): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/RegisteredServicesCache( 1428): empty dynamic service
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/TimaKeyStoreProvider( 6829): TimaSignature is unavailable
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ActivityThread( 6829): Added TimaKeyStore provider
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/SecContentProvider2(  909): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  909): mCursor = null
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/SurfaceWidgetView( 1465): destroyHardwareResources():327400354
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  909): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  909): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager( 6829): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/Launcher( 1465): onRestart, Launcher: 431438552
D/Launcher( 1465): onStart, Launcher: 431438552
D/Launcher.HomeView( 1465): onStart
D/RCPManagerService(  909): PackageReceiver onReceive()
V/ActivityThread( 1465): updateVisibility : ActivityRecord{1b69606c token=android.os.BinderProxy@20d19873 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/HarmonyEASService(  909): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1834): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1834): [237392/8] SurfaceWidget drawing first frame
D/KnoxMUMContainerPolicy(  909): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/accuweather( 1834): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/BackupManagerService(  909): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  909): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  909): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  909): uID is 10079
V/EnterpriseBillingPolicy(  909): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  909): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  909): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  909): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  909): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  909): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  909): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT(  909): com.test.thalitest(10079) is removed.
D/TaskPersister(  909): removeObsoleteFile: deleting file=9_task.xml
D/SSRM:aV (  909): MSG_TYPE_APP_REMOVED::
I/SurfaceFlinger(  266): id=12 createSurf (1080x1920),1 flag=4, Mauncher
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  909): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  909): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  909): setMouseCustomIcon IconType is same.101
D/PointerIcon(  909): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  909): setHoveringSpenCustomIcon IconType is same.1
D/InputMethodManagerService(  909): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 6521 uid 10079
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/KLMS-2.4.511: ( 6829): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6829): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456846623486
I/KLMS-2.4.511: ( 6829): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6829): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/EnterpriseDeviceManagerService(  909): Package has changed for user 0
D/EnterpriseDeviceManagerService(  909): Admin package name: com.google.android.gms
I/Timeline(  909): Timeline: Activity_windows_visible id: ActivityRecord{820f7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:1357954
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     (  909): Explicit concurrent mark sweep GC freed 26939(1855KB) AllocSpace objects, 10(160KB) LOS objects, 30% free, 36MB/52MB, paused 1.873ms total 215.752ms
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
E/Zygote  ( 6848): MountEmulatedStorage()
E/Zygote  ( 6848): v2
I/libpersona( 6848): KNOX_SDCARD checking this for 10116
I/libpersona( 6848): KNOX_SDCARD not a persona
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
I/ActivityManager(  909): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6848 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  909): Killing 5343:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/SELinux ( 6848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6848): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/TimaKeyStoreProvider( 6848): TimaSignature is unavailable
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ActivityThread( 6848): Added TimaKeyStore provider
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PackageManager(  909): delete codoeFile: 
D/AASAuninstall(  909): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  909): UID=10079 Target=com.test.thalitest
D/PackageManager(  909): result of delete: 1{731850916}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/AndroidRuntime( 6799): Shutting down VM
D/ResourcesManager( 6848): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  909): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  909): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  909): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/elm:14491( 6848): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/elm:14491( 6848): ELMEngine.ELMEngine( context ).
D/elm:14491( 6848): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  909): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/elm:14491( 6848): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/AASAservice-UpdateReceiver( 3371): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3371): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3371): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3371): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3371): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3371): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3371): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3371): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6058): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6058): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6058): onReceive() : package name is not s health. Return !!!
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6848): ElmAgentService : onCreate()
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6848): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/elm:14491( 6848): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6848): MDMBridge.getInstance()
D/elm:14491( 6848): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6848): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/SSRM:n  (  909): SIOP:: AP = 280, PST = 280, CUR = 450
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
I/PCWCLIENTTRACE_PushUtil( 6076): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6076): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6076): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6076): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
D/elm:14491( 6848): ElmAgentService : onDestroy().
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  909): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  909): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  909): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  909): onPackageRemoved : com.test.thalitest
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6866): MountEmulatedStorage()
E/Zygote  ( 6866): v2
I/libpersona( 6866): KNOX_SDCARD checking this for 10043
I/libpersona( 6866): KNOX_SDCARD not a persona
I/ActivityManager(  909): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6866 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  909): Killing 5706:flipboard.app/u0a125 (adj 15): bgCount ##41
I/SELinux ( 6866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6866): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6866): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6866): TimaSignature is unavailable
D/ActivityThread( 6866): Added TimaKeyStore provider
D/ResourcesManager( 6866): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 6866): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6866): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 6866): PushLog.txt file is not deleted.
D/SPPClientService( 6866): PushLog.txt file is not deleted.
D/SPPClientService( 6866): ============PushLog. stop!
I/SA      ( 6140): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6140): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  909): Killing 5754:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  909): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6886): MountEmulatedStorage()
E/Zygote  ( 6886): v2
I/libpersona( 6886): KNOX_SDCARD checking this for 10024
I/libpersona( 6886): KNOX_SDCARD not a persona
I/ActivityManager(  909): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=6886 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 6886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6886): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6886): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiver( 6160): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 6886): TimaSignature is unavailable
D/ActivityThread( 6886): Added TimaKeyStore provider
I/TactileAssist(  909): enable value -1
I/TactileAssist(  909): internal enable value -1
I/TactileAssist(  909): intensity value -1
I/TactileAssist(  909): saveAppList value true
D/Mms/FreeMessageReceiverService( 6160): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 6160): onHandleIntent: ACTION_PACKAGE_REMOVED
D/ResourcesManager( 6886): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
I/TactileAssist(  909): List of disabled apps :
D/SettingsProvider(  909): name = reading_mode_app_list
D/Compatibility( 6204): onReceive() it will make start service
I/EventHub(  909): Removing device '/dev/input/event6' due to inotify event
D/Compatibility( 6204): onHandleIntent()
D/Compatibility( 6204): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 6204): found: 2
D/Compatibility( 6204): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6204): skipping ResolveInfo{2ade25bb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6204): considering ResolveInfo{19b73ad8 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6204): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6204): enabling receiver ResolveInfo{22020e31 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 1501): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 6204): enabling receiver ResolveInfo{6192916 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SQLiteLog( 5785): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 5785): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5785): (14) cannot open file at line 32509 of [b3bb660af9]
E/SQLiteLog( 5785): (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sm/databases/history.db) - 
E/SQLiteDatabase( 5785): Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
E/SQLiteDatabase( 5785): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5785): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/SQLiteDatabase( 5785): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/SQLiteDatabase( 5785): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/SQLiteDatabase( 5785): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/SQLiteDatabase( 5785): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/SQLiteDatabase( 5785): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 5785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 5785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5785): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5785): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 5785): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5785): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 5785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/AndroidRuntime( 5785): Shutting down VM
E/AndroidRuntime( 5785): FATAL EXCEPTION: main
E/AndroidRuntime( 5785): Process: com.samsung.android.sm, PID: 5785
E/AndroidRuntime( 5785): java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 5785): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
E/AndroidRuntime( 5785): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 5785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 5785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5785): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5785): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 5785): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5785): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 5785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 5785): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 5785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 5785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5785): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/AndroidRuntime( 5785): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/AndroidRuntime( 5785): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/AndroidRuntime( 5785): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/AndroidRuntime( 5785): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/AndroidRuntime( 5785): 	... 9 more

```
