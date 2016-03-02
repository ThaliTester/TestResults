#### Test 613623666a5dbc7_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6611): 
D/AndroidRuntime( 6611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6611): CheckJNI is OFF
D/AndroidRuntime( 6611): readGMSProperty: start
D/AndroidRuntime( 6611): readGMSProperty: already setted!!
D/AndroidRuntime( 6611): readGMSProperty: end
D/AndroidRuntime( 6611): addProductProperty: start
E/AffinityControl( 6611): AffinityControl: registerfunction enter
D/AndroidRuntime( 6611): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  886): inState():  stateMachine is null !!
I/PersonaManagerService(  886): PersonaId don't exist
I/ActivityManager(  886): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  886): mDVFSHelper.acquire()
D/FocusedStackFrame(  886): Set to : 0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  886): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6627 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  886): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  886): setMouseCustomIcon IconType is same.101
D/PointerIcon(  886): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  886): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6611): Shutting down VM
E/Zygote  ( 6627): MountEmulatedStorage()
E/Zygote  ( 6627): v2
I/libpersona( 6627): KNOX_SDCARD checking this for 10079
I/libpersona( 6627): KNOX_SDCARD not a persona
I/SELinux ( 6627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6627): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6627): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6627): TimaSignature is unavailable
D/ActivityThread( 6627): Added TimaKeyStore provider
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  886): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1444): destroyHardwareResources():59470974
I/SurfaceFlinger(  266): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger(  266): id=8 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1809): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6627): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2612f368 token=android.os.BinderProxy@3b36ca1f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1444): onTrimMemory. Level: 20
I/WebViewFactory( 6627): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 6627): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6627): Time to load native libraries: 3 ms (timestamps 1290-1293)
I/LibraryLoader( 6627): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6627): Binding Chromium to main looper Looper (main, tid 1) {3ac8b6e8}
I/LibraryLoader( 6627): Expected native library version number "",actual native library version number ""
I/chromium( 6627): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6627): Initializing chromium process, singleProcess=true
W/art     ( 6627): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6627): ApplicationContext is null in ApplicationStatus
W/chromium( 6627): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 6627): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6627): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6627): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 6627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6627): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6627): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6627): Local Branch: mybranch5813579
I/Adreno-EGL( 6627): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6627): Local Patches: NONE
I/Adreno-EGL( 6627): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
I/ServiceManager(  359): Waiting for service AtCmdFwd...
D/BluetoothAdapter( 6627): 47672381: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6627): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 6627): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6627): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6627): CordovaWebView is running on device made by: samsung
W/art     ( 6627): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6627): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  886): Activity pause timeout for ActivityRecord{3c44d68d u0 com.test.thalitest/.MainActivity t9}
D/Activity( 6627): performCreate Call secproduct feature valuefalse
D/Activity( 6627): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6627): Render dirty regions requested: true
D/ActivityManager(  886): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  886): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  886): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  886): handleActiveUserChange for user 0
D/PersonaManagerService(  886): getPersonasForUser(): returning null!
V/ActivityThread( 6627): updateVisibility : ActivityRecord{1e057d73 token=android.os.BinderProxy@3160dead {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  266): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  886): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  886): setMouseCustomIcon IconType is same.101
D/PointerIcon(  886): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  886): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6627): Initialized EGL, version 1.4
I/OpenGLRenderer( 6627): HWUI protection enabled for context ,  &this =0xa074b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6627): Enabling debug mode 0
D/InputMethodManagerService(  886): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  886): mDVFSHelper.release()
I/Timeline(  886): Timeline: Activity_windows_visible id: ActivityRecord{3c44d68d u0 com.test.thalitest/.MainActivity t9} time:251872
I/SamsungIME( 1743): getCurrentCandidateView
W/IInputConnectionWrapper( 6627): showStatusIcon on inactive InputConnection
I/Timeline( 6627): Timeline: Activity_idle id: android.os.BinderProxy@3160dead time:251886
W/BindingManager( 6627): Cannot call determinedVisibility() - never saw a connection for the pid: 6627
D/SamsungIME( 1743): Dismiss ExpandCandiate
D/JsMessageQueue( 6627): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1743): getDebugLevel  : 0x4f4c
I/SamsungIME( 1743): getDebugLevel  : 0x4f4c
I/SamsungIME( 1743): KeybaordView init() : load resources
I/SamsungIME( 1743): getCurrentKeyboard
I/SamsungIME( 1743): getTextKeyboard
D/SamsungIME( 1743): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6627): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359647616
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6627): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1e7960 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9278bf added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6627): addListener: New listener added - the number of listeners is now 1
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6627): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6627): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6627): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6627): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6627): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 6627): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ServiceManager(  359): Waiting for service AtCmdFwd...
D/SamsungIME( 1743): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SSRM:n  (  886): SIOP:: AP = 300, PST = 284, CUR = 450
,E/SMD     (  303): DCD ON
,W/jxcore-log( 6627): Initializing JXcore engine
W/jxcore-log( 6627): JXcore engine is ready
,E/auditd  ( 1858): In denial and Property audit_ondenial is set to 1 
E/audit   ( 1858): type=1400 msg=audit(1456906281.952:201): avc:  denied  { ioctl } for  pid=6700 comm="Thread-1082" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
E/audit   ( 1858):  SEPF_SM-N9005_5.0-1_0032
E/audit   ( 1858): 
D/SecurityLogAgent:SEDenialService(  886): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0,
,E/audit   ( 1858): type=1300 msg=audit(1456906281.952:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a3fb8d8 items=0 ppid=340 ppcomm=main pid=6700 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1082" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/audit   ( 1858): type=1320 msg=audit(1456906281.952:201): 
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0,
D/SecurityLogAgent:SEDenialService(  886): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/jxcore-log( 6627): Starting JXcore engine
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  886): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6704): MountEmulatedStorage()
,E/Zygote  ( 6704): v2
I/libpersona( 6704): KNOX_SDCARD checking this for 1000
I/libpersona( 6704): KNOX_SDCARD not a persona
,I/SELinux ( 6704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6704): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 6704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6704): TimaSignature is unavailable
,D/ActivityThread( 6704): Added TimaKeyStore provider
,D/ResourcesManager( 6704): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6704):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6704):  SeDenialReceiver : File path = null
,I/ActivityManager(  886): Killing 5095:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,W/jxcore-log( 6627): Platform android
W/jxcore-log( 6627): 
W/jxcore-log( 6627): Process ARCH arm
W/jxcore-log( 6627): 
,I/jxcore-log( 6627): JXcore Cordova bridge is ready!
I/jxcore-log( 6627): 
W/jxcore-log( 6627): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6627): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD ON
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6627): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 6627): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 6627): BLE multiple advertisement supported
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): My device name is: samsung-SM-N9005
I/jxcore-log( 6627): 
,E/Watchdog(  886): !@Sync 8
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6627): 
,E/SMD     (  303): DCD ON
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6627): 
,I/io.jxcore.node.ConnectivityInfo( 6627): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6627):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6627):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6627):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 6627):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6627):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 6627):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 6627):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 6627):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 6627): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 6627): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6627): 
,D/SSRM:n  (  886): SIOP:: AP = 330, PST = 288, CUR = 450
,E/SMD     (  303): DCD ON
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 6627): 
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService(  886): stay LED for fully charged
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6627): 
,I/jxcore-log( 6627): Unit Test app is loaded
I/jxcore-log( 6627): 
,I/chromium( 6627): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log( 6627): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 6627): 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  886): SIOP:: AP = 320, PST = 291, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  886): [PWL] Off : 225s ago
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 9
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 290, PST = 293, CUR = 450
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 293, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 293, CUR = 450
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  886): initializing...
,I/TLC_TIMA_PKM_initialize(  886): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  886): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  886): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  886): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  886): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  886): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  886): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  886): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  886): App is not loaded in QSEE
,D/QSEECOMAPI: (  886): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  886): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  886): Trustlet response is completed
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  303): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  886): [PWL] Off : 275s ago
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 294, CUR = 450
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/NtpTrustedTime(  886): forceRefresh() from cache miss
,D/NtpTrustedTime(  886): forceRefresh Fail.
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  886): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6735 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6735): MountEmulatedStorage()
E/Zygote  ( 6735): v2
I/libpersona( 6735): KNOX_SDCARD checking this for 10096
I/libpersona( 6735): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,I/SELinux ( 6735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6735): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6735): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 6735): TimaSignature is unavailable
,D/ActivityThread( 6735): Added TimaKeyStore provider
,D/ResourcesManager( 6735): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  886): Killing 5363:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 294, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 11
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5680): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 292, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 12
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 330s ago
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  886): stay LED for fully charged
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 13
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 281, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 14
,E/SMD     (  303): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  886): [PWL] Off : 390s ago
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 15
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 279, CUR = 450
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/bootchecker(  354): bootchecker wake up!!
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 278, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 16
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 277, CUR = 450
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  886): [PWL] Off : 455s ago
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 275, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 17
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  303): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 274, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  303): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 273, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 18
,E/SMD     (  303): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  886): stay LED for fully charged
,I/PowerManagerService(  886): [PWL] Off : 525s ago
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,I/Atfwd_Daemon(  359): Stop the daemon....
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  886): stay LED for fully charged
,E/Watchdog(  886): !@Sync 19
,E/SMD     (  303): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 280, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  886): !@Sync 21
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 600s ago
,E/SMD     (  303): DCD ON
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/System.out( 5680): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  886): !@Sync 22
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 23
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 680s ago
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 24
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  886): !@Sync 25
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 26
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/LightsService(  886): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,E/LightSensor(  886): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/SensorManager(  886): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 3888): Aggregate from 1456904967659 (log), 1456904967659 (data)
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  886): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  886): unregisterListener ::   
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,I/PowerManagerService(  886): [PWL] Off : 765s ago
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 27
,E/SMD     (  303): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 28
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/Watchdog(  886): !@Sync 29
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,I/PowerManagerService(  886): [PWL] Off : 855s ago
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  886): !@Sync 30
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 31
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5680): (HTTPLog)-Static: isSBSettingEnabled false
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 32
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 950s ago
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 33
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 34
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 35
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 36
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 1050s ago
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 37
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 38
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 39
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/PowerManagerService(  886): [PWL] Off : 1155s ago
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,I/UsageStatsService(  886): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  886): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  886): Updating Usage Statistics in DB @ 1456907245090
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  886): Done Updating Usage Statistics in DB @ 1456907245254
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  886): !@Sync 40
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 41
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5680): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 42
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true,
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 43
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  886): [PWL] Off : 1265s ago
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 44
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 45
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  886): !@Sync 46
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 47
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 1380s ago
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/Watchdog(  886): !@Sync 48
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  886): !@Sync 49
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  886): stay LED for fully charged
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  886): !@Sync 50
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  886): !@Sync 51
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 1500s ago
,E/SMD     (  303): DCD ON
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1870): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5680): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  886): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  886): setPowerConnected  = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  303): DCD ON
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
,D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,E/SMD     (  303): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService(  886): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  886): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  886): stay LED for fully charged
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
E/Watchdog(  886): !@Sync 52
D/SSRM:n  (  886): SIOP:: AP = 270, PST = 270, CUR = 450
E/SMD     (  303): DCD ON
D/AndroidRuntime( 6877): 
D/AndroidRuntime( 6877): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6877): CheckJNI is OFF
D/AndroidRuntime( 6877): readGMSProperty: start
D/AndroidRuntime( 6877): readGMSProperty: already setted!!
D/AndroidRuntime( 6877): readGMSProperty: end
D/AndroidRuntime( 6877): addProductProperty: start
E/AffinityControl( 6877): AffinityControl: registerfunction enter
D/AndroidRuntime( 6877): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  886): START PACKAGE DELETE: observer{574343511}
D/PackageManager(  886): pkg{<packageName>}
D/PackageManager(  886): user{0}
D/PackageManager(  886): caller{2000}
D/PackageManager(  886): flags{3}
D/PersonaManagerService(  886): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  886): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  886): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  886): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  886): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  886): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  886): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  886): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  886): getApplicationUninstallationEnabled
D/ApplicationPolicy(  886): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  886): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  886): Killing 6627:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  886): Skipping PackageSetting{281f950d com.example.hello/10078} due to missing metadata
I/WindowState(  886): WIN DEATH: Window{3bbb40bb u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=11 Removed NainActivit (6/8)
I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
E/libprocessgroup(  886): failed to kill 1 processes for processgroup 6627
I/ActivityManager(  886):   Force finishing activity ActivityRecord{3c44d68d u0 com.test.thalitest/.MainActivity t9}
D/FocusedStackFrame(  886): Set to : 0
D/PointerIcon(  886): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  886): setMouseCustomIcon IconType is same.101
D/PointerIcon(  886): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  886): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  886):   Force finishing activity ActivityRecord{3c44d68d u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  886): Duplicate finish request for ActivityRecord{3c44d68d u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 5841): Explicit concurrent mark sweep GC freed 10513(497KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 304us total 20.059ms
I/art     ( 3888): Explicit concurrent mark sweep GC freed 33865(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 22MB/29MB, paused 793us total 83.232ms
I/art     ( 1501): Explicit concurrent mark sweep GC freed 547(34KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 606us total 66.457ms
I/art     ( 5339): Explicit concurrent mark sweep GC freed 35490(1931KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 662us total 61.198ms
W/ActivityManager(  886): Spurious death for ProcessRecord{1b176c44 6627:com.test.thalitest/u0a79}, curProc for 6627: null
D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1743): mOCRHelper is null
W/GeofencerStateMachine( 1870): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 1444): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ResourcesManager( 1444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1444): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1444): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  886): Explicit concurrent mark sweep GC freed 30941(3MB) AllocSpace objects, 86(1377KB) LOS objects, 30% free, 36MB/52MB, paused 2.131ms total 106.073ms
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager( 1444): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/Zygote  ( 6905): MountEmulatedStorage()
E/Zygote  ( 6905): v2
I/libpersona( 6905): KNOX_SDCARD checking this for 10023
I/libpersona( 6905): KNOX_SDCARD not a persona
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/ActivityManager(  886): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6905 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6905): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RegisteredServicesCache( 1413): empty dynamic service
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/TimaKeyStoreProvider( 6905): TimaSignature is unavailable
D/ActivityThread( 6905): Added TimaKeyStore provider
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager( 6905): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SurfaceWidgetView( 1444): destroyHardwareResources():59470974
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  886): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1444): onRestart, Launcher: 166091156
D/Launcher( 1444): onStart, Launcher: 166091156
D/Launcher.HomeView( 1444): onStart
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2612f368 token=android.os.BinderProxy@3b36ca1f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1809): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1809): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1809): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/SurfaceFlinger(  266): id=12 createSurf (1080x1920),1 flag=4, Mauncher
D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/PointerIcon(  886): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  886): setMouseCustomIcon IconType is same.101
D/PointerIcon(  886): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  886): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/EnterpriseDeviceManagerService(  886): Package has changed for user 0
D/EnterpriseDeviceManagerService(  886): Admin package name: com.google.android.gms
D/InputMethodManagerService(  886): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  886): Got RemoteException sending setActive(false) notification to pid 6627 uid 10079
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.511: ( 6905): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.511: ( 6905): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456907610143
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.511: ( 6905): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6905): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/Timeline(  886): Timeline: Activity_windows_visible id: ActivityRecord{be4f86 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:1581700
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService(  886): PackageReceiver onReceive()
I/HarmonyEASService(  886): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  886): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  886): uID is 10079
V/EnterpriseBillingPolicy(  886): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  886): removeObsoleteFile: deleting file=9_task.xml
D/SSRM:aV (  886): MSG_TYPE_APP_REMOVED::
V/AlarmManagerEXT(  886): com.test.thalitest(10079) is removed.
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/art     (  886): Explicit concurrent mark sweep GC freed 16222(975KB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 36MB/52MB, paused 2.238ms total 242.810ms
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  ( 6925): MountEmulatedStorage()
I/libpersona( 6925): KNOX_SDCARD checking this for 10116
E/Zygote  ( 6925): v2
I/libpersona( 6925): KNOX_SDCARD not a persona
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
I/ActivityManager(  886): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6925 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  886): Killing 5399:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
W/ResourcesManager(  886): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux ( 6925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6925): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/TimaKeyStoreProvider( 6925): TimaSignature is unavailable
D/ActivityThread( 6925): Added TimaKeyStore provider
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/ResourcesManager( 6925): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6925): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6925): ELMEngine.ELMEngine( context ).
D/elm:14491( 6925): MDMBridge.setEnterpriseBridge()
D/PackageManager(  886): delete codoeFile: 
D/AASAuninstall(  886): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  886): UID=10079 Target=com.test.thalitest
D/PackageManager(  886): result of delete: 1{574343511}
D/AndroidRuntime( 6877): Shutting down VM
D/UsbSettingsManager(  886): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  886): onPackageRemoved : com.test.thalitest
D/elm:14491( 6925): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/AASAservice-UpdateReceiver( 3434): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3434): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3434): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3434): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3434): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3434): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3434): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3434): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3434): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3434): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/elm:14491( 6925): ElmAgentService : onCreate()
D/elm:14491( 6925): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6925): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6925): MDMBridge.getInstance()
D/elm:14491( 6925): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6925): MDMBridge.getAllLicenseInfoFromSDK()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6130): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6130): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6130): onReceive() : package name is not s health. Return !!!
I/PCWCLIENTTRACE_PushUtil( 6148): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6148): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6148): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6148): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/elm:14491( 6925): ElmAgentService : onDestroy().
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6943): MountEmulatedStorage()
E/Zygote  ( 6943): v2
I/libpersona( 6943): KNOX_SDCARD checking this for 10043
I/libpersona( 6943): KNOX_SDCARD not a persona
I/SELinux ( 6943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6943): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6943): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  886): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6943 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 5760:flipboard.app/u0a125 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 6943): TimaSignature is unavailable
D/ActivityThread( 6943): Added TimaKeyStore provider
D/ResourcesManager( 6943): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 6943): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6943): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 6943): PushLog.txt file is not deleted.
D/SPPClientService( 6943): PushLog.txt file is not deleted.
D/SPPClientService( 6943): ============PushLog. stop!
I/SA      ( 6210): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6210): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  886): Killing 5810:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
E/SharedPreferencesImpl( 5378): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/Mms/FreeMessageReceiver( 6230): onReceive, action : android.intent.action.PACKAGE_REMOVED
I/EventHub(  886): Removing device '/dev/input/event6' due to inotify event
I/TactileAssist(  886): enable value -1
I/TactileAssist(  886): internal enable value -1
I/TactileAssist(  886): intensity value -1
I/TactileAssist(  886): saveAppList value true
I/TactileAssist(  886): List of disabled apps :
E/SharedPreferencesImpl(  886): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
D/Mms/FreeMessageReceiverService( 6230): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 6230): onHandleIntent: ACTION_PACKAGE_REMOVED
D/SettingsProvider(  886): name = reading_mode_app_list
I/EventHub(  886): Removing device '/dev/input/event7' due to inotify event
D/Compatibility( 6271): onReceive() it will make start service
D/Compatibility( 6271): onHandleIntent()
D/Compatibility( 6271): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 6271): found: 2
D/Compatibility( 6271): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6271): skipping ResolveInfo{2c87d9e7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6271): considering ResolveInfo{9e65994 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6271): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6271): enabling receiver ResolveInfo{2d76c3d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6271): enabling receiver ResolveInfo{ce1dc32 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6271): enabling receiver ResolveInfo{dee2d83 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6271): enabling receiver ResolveInfo{36997b00 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SharedPreferencesImpl( 6271): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 6271): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 6271): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/UpdateIcingCorporaServi( 1501): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE

```
