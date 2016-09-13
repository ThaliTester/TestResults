#### Test 85067679198230b_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system,
09-14 01:05:16.700  1020  3818 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-14 01:05:16.700  1020  3818 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4310, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-14 01:05:16.700  1020  3818 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-14 01:05:16.700  1020  3818 D BatteryService: stay LED for charging
09-14 01:05:16.700  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-14 01:05:16.700  1020  1020 I MotionRecognitionService: Plugged
09-14 01:05:16.700  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
09-14 01:05:16.700  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-14 01:05:16.700  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
09-14 01:05:16.710  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-14 01:05:16.710  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-14 01:05:16.710  3220  3220 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-14 01:05:16.710  3220  3374 D HeadsetStateMachine: Disconnected process message: 10
09-14 01:05:16.730  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-14 01:05:16.730  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-14 01:05:16.730  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-14 01:05:16.980  7306  7306 D AndroidRuntime: 
09-14 01:05:16.980  7306  7306 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-14 01:05:16.980  7306  7306 D AndroidRuntime: CheckJNI is OFF
09-14 01:05:16.980  7306  7306 D AndroidRuntime: readGMSProperty: start
09-14 01:05:16.980  7306  7306 D AndroidRuntime: readGMSProperty: already setted!!
09-14 01:05:16.980  7306  7306 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-14 01:05:16.980  7306  7306 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-14 01:05:16.980  7306  7306 D AndroidRuntime: readGMSProperty: end
09-14 01:05:16.980  7306  7306 D AndroidRuntime: addProductProperty: start
09-14 01:05:17.120  7306  7306 E AffinityControl: AffinityControl: registerfunction enter
09-14 01:05:17.140  7306  7306 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-14 01:05:17.150  1020  1339 E PersonaManagerService: inState():  stateMachine is null !!
09-14 01:05:17.150  1020  1339 I PersonaManagerService: PersonaId don't exist
09-14 01:05:17.150  1020  1339 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-14 01:05:17.160  1020  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-14 01:05:17.180  1020  1339 W ActivityManager: mDVFSHelper.acquire()
09-14 01:05:17.180  1020  1339 D FocusedStackFrame: Set to : 0
09-14 01:05:17.190  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:17.190  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:17.190  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:17.190  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:17.190  1020  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-14 01:05:17.190  1020  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-14 01:05:17.200  1020  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-14 01:05:17.200  1020  1339 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7319 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-14 01:05:17.200  1020  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-14 01:05:17.200  1020  1339 D InputDispatcher: Focused application set to: xxxx
09-14 01:05:17.200  1020  1339 D InputDispatcher: Focus left window: 1493
09-14 01:05:17.200  7319  7319 E Zygote  : MountEmulatedStorage()
09-14 01:05:17.200  7319  7319 I libpersona: KNOX_SDCARD checking this for 10170
09-14 01:05:17.200  7319  7319 E Zygote  : v2
09-14 01:05:17.200  7319  7319 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:17.200  7306  7306 D AndroidRuntime: Shutting down VM
09-14 01:05:17.200  7319  7319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:17.210  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-14 01:05:17.210  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-14 01:05:17.210   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-14 01:05:17.210  7319  7319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:17.210  7319  7319 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-14 01:05:17.220  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-14 01:05:17.220  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
09-14 01:05:17.230  7319  7319 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:17.240  7319  7319 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:17.240  1020  1222 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-14 01:05:17.240  1020  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-14 01:05:17.260  1020  1222 D PersonaManager: isKioskContainerExistOnDevice
09-14 01:05:17.270  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-14 01:05:17.270   258   453 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
09-14 01:05:17.270   258  1165 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
09-14 01:05:17.280  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{2082c6fc token=android.os.BinderProxy@3b3c40f1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-14 01:05:17.280  1493  1493 D Launcher: onTrimMemory. Level: 20
09-14 01:05:17.370  7319  7319 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-14 01:05:17.390  7319  7319 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7253-7255)
09-14 01:05:17.390  7319  7319 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-14 01:05:17.410  7306  7306 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-14 01:05:17.430  7319  7319 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60a1f27}
,09-14 01:05:17.430  7319  7319 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-14 01:05:17.440  7319  7319 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-14 01:05:17.480  7319  7319 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-14 01:05:17.480  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 01:05:17.490  7319  7319 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-14 01:05:17.540  7319  7319 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-14 01:05:17.540  7319  7319 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-14 01:05:17.540  7319  7319 I Adreno-EGL: Build Date: 04/06/15 Mon
09-14 01:05:17.540  7319  7319 I Adreno-EGL: Local Branch: 
09-14 01:05:17.540  7319  7319 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-14 01:05:17.540  7319  7319 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-14 01:05:17.540  7319  7319 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-14 01:05:17.620  7319  7319 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-14 01:05:17.630  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-14 01:05:17.630  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-14 01:05:17.640  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-14 01:05:17.640  7319  7319 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-14 01:05:17.760  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 01:05:17.760  1020  1047 W ActivityManager: Activity pause timeout for ActivityRecord{6231851 u0 com.test.thalitest/.MainActivity t164}
,09-14 01:05:17.770  7319  7319 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 01:05:17.780  7319  7319 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-14 01:05:17.780  7319  7319 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-14 01:05:17.790  7319  7319 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-14 01:05:17.790  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 01:05:17.800  7319  7319 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-14 01:05:17.840  7319  7360 D OpenGLRenderer: Render dirty regions requested: true
,09-14 01:05:17.850  1020  1032 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-14 01:05:17.850  1020  1032 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-14 01:05:17.850  1020  1032 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-14 01:05:17.850  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-14 01:05:17.850  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-14 01:05:17.850  7319  7347 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-14 01:05:17.860  7319  7319 V ActivityThread: updateVisibility : ActivityRecord{3fb63d07 token=android.os.BinderProxy@1458a188 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-14 01:05:17.860  7319  7319 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-14 01:05:17.860  7319  7319 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-14 01:05:17.870   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-14 01:05:17.880  1020  1477 D InputDispatcher: Focus entered window: 7319
,09-14 01:05:17.890  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-14 01:05:17.890  7319  7319 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-14 01:05:17.890  7319  7360 I OpenGLRenderer: Initialized EGL, version 1.4
09-14 01:05:17.890  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
09-14 01:05:17.890  7319  7360 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-14 01:05:17.890  7319  7360 D OpenGLRenderer: Enabling debug mode 0
,09-14 01:05:17.920  1020  1143 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,09-14 01:05:17.930  1184  1184 D PanelView: There is/are notification(s) 
,09-14 01:05:17.930  1020  7364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-14 01:05:17.940  1020  1052 I ActivityManager: Displayed Component not be shown by security: +676ms (total +1m38s954ms)
,09-14 01:05:17.940  1020  1052 W ActivityManager: mDVFSHelper.release()
,09-14 01:05:17.940  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6231851 u0 com.test.thalitest/.MainActivity t164} time:217804
,09-14 01:05:17.940  7319  7319 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-14 01:05:17.950  7319  7319 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1458a188 time:217810
09-14 01:05:17.950   258  1100 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-14 01:05:17.950   258   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-14 01:05:18.000  1869  1869 I SamsungIME: getCurrentCandidateView
,09-14 01:05:18.060  7319  7319 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7319
,09-14 01:05:18.090  1869  1869 D SamsungIME: Dismiss ExpandCandiate
,09-14 01:05:18.240   288   288 E SMD     : DCD OFF
,09-14 01:05:18.240  7319  7319 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 01:05:18.250  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,09-14 01:05:18.290  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,09-14 01:05:18.300  1869  1869 I SamsungIME: KeybaordView init() : load resources
,09-14 01:05:18.320  1869  1869 I SamsungIME: getCurrentKeyboard
09-14 01:05:18.320  1869  1869 I SamsungIME: getTextKeyboard
,09-14 01:05:18.330  7319  7366 D jxcore_app_log: JniHelper::setJavaVM(0xb805a2b0), pthread_self() = -1201768232
,09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-14 01:05:18.340  7319  7366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198db215 added. We now have 1 listener(s)
,09-14 01:05:18.340  1869  1869 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-14 01:05:18.350  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-14 01:05:18.350  7319  7366 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-14 01:05:18.350  7319  7366 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:05:18.350  7319  7366 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-14 01:05:18.360  7319  7366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b3b7cb8 added. We now have 1 listener(s)
,09-14 01:05:18.360  7319  7366 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-14 01:05:18.360  7319  7366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:05:18.370  7319  7366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-14 01:05:18.370  7319  7366 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:05:18.370  7319  7366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:05:18.370  7319  7366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 01:05:18.370  7319  7366 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 01:05:18.370  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:05:18.380  7319  7366 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 01:05:18.380  7319  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:05:18.410  7319  7319 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 01:05:19.180  7319  7373 W jxcore-log: Initializing JXcore engine
09-14 01:05:19.180  7319  7373 W jxcore-log: JXcore engine is ready
,09-14 01:05:19.240  1939  1939 E audit   : type=1400 msg=audit(1473807919.240:205): avc:  denied  { ioctl } for  pid=7373 comm="Thread-1381" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-14 01:05:19.240  1939  1939 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:19.240  1939  1939 E audit   : type=1300 msg=audit(1473807919.240:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9f3fb8f8 items=0 ppid=312 ppcomm=main pid=7373 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1381" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-14 01:05:19.240  1939  1939 E audit   : type=1320 msg=audit(1473807919.240:205): 
,09-14 01:05:19.250  7319  7373 W jxcore-log: Starting JXcore engine
,09-14 01:05:19.360  7319  7373 W jxcore-log: Platform android
09-14 01:05:19.360  7319  7373 W jxcore-log: 
09-14 01:05:19.360  7319  7373 W jxcore-log: Process ARCH arm
09-14 01:05:19.360  7319  7373 W jxcore-log: 
,09-14 01:05:19.630  7319  7373 I jxcore-log: JXcore Cordova bridge is ready!
09-14 01:05:19.630  7319  7373 I jxcore-log: 
,09-14 01:05:19.630  7319  7373 W jxcore-log: JXcore engine is started
,09-14 01:05:19.630  7319  7366 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 01:05:19.630  7319  7319 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 01:05:19.640  7319  7373 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-14 01:05:19.640  7319  7373 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-14 01:05:19.650  7319  7319 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,09-14 01:05:19.650  7319  7319 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-14 01:05:19.650  1020  4371 D FocusedStackFrame: Set to : 0
09-14 01:05:19.650  1020  4371 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-14 01:05:19.650  1020  4371 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-14 01:05:19.650  1020  4371 D InputDispatcher: Focused application set to: xxxx
09-14 01:05:19.650  1020  4371 D InputDispatcher: Focus left window: 7319
09-14 01:05:19.660  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-14 01:05:19.660  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
09-14 01:05:19.660  1020  4371 I ActivityManager: Killing 6853:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-14 01:05:19.660  7319  7319 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-14 01:05:19.670  7319  7319 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-14 01:05:19.670  7319  7319 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:05:19.670  7319  7319 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:05:19.670  7319  7319 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:05:19.670  7319  7319 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:05:19.670  7319  7319 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198db215 removed from the list
09-14 01:05:19.670  7319  7319 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:05:19.670  7319  7319 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b3b7cb8 removed from the list
09-14 01:05:19.670  7319  7319 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:05:19.670  7319  7319 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
09-14 01:05:19.670  7319  7319 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-14 01:05:19.680   258   450 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-14 01:05:19.680   258  1165 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-14 01:05:19.690  1020  1033 W ActivityManager: mDVFSHelper.acquire()
,09-14 01:05:19.690  1020  1033 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-14 01:05:19.710  1493  1493 D Launcher: onRestart, Launcher: 286773874
,09-14 01:05:19.720  1493  1493 D Launcher: onStart, Launcher: 286773874
,09-14 01:05:19.720  1493  1493 D Launcher.HomeView: onStart
,09-14 01:05:19.720  1493  1493 D Launcher: onResume, Launcher: 286773874
,09-14 01:05:19.720  1020  1032 D SettingsProvider: name = kids_home_mode
,09-14 01:05:19.720  1020  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-14 01:05:19.720  1020  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-14 01:05:19.720  1020  1032 D SettingsProvider: selectionArgs: false
,09-14 01:05:19.720  1020  1032 D SettingsProvider: selectionArgs: 10006
09-14 01:05:19.720  1020  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-14 01:05:19.720  1020  1032 D SettingsProvider: ret = -1
09-14 01:05:19.720  1493  1493 D Launcher.HomeView: onResume
,09-14 01:05:19.730  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-14 01:05:19.740  1493  1493 D MenuAppsGridFragment: onResume
,09-14 01:05:19.740  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-14 01:05:19.740  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-14 01:05:19.750  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-14 01:05:19.750  1020  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-14 01:05:19.750  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,09-14 01:05:19.750  1020  1222 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,09-14 01:05:19.750  1020  1222 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,09-14 01:05:19.750  1020  1222 W ActivityManager: userId = 0, bbcId = -10000
,09-14 01:05:19.750  1020  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-14 01:05:19.750  1020  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,09-14 01:05:19.760  1020  1222 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-14 01:05:19.760  1020  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.760  1020  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.760  1020  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.760  1020  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.780  7377  7377 E Zygote  : MountEmulatedStorage()
09-14 01:05:19.780  7377  7377 E Zygote  : v2
09-14 01:05:19.780  7377  7377 I libpersona: KNOX_SDCARD checking this for 10039
09-14 01:05:19.780  7377  7377 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:19.780  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:19.780  1020  1222 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7377 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-14 01:05:19.780  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:19.780  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:19.780  1020  1339 D ActivityManager: handle home activity for 0
09-14 01:05:19.780  1020  1339 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-14 01:05:19.780  1020  1339 D KnoxTimeoutHandler: post home show event for user 0
09-14 01:05:19.780  1020  1339 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-14 01:05:19.780  1020  1339 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-14 01:05:19.780  1020  1339 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-14 01:05:19.780  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-14 01:05:19.780  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-14 01:05:19.780  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-14 01:05:19.780  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-14 01:05:19.780  1493  1493 D Launcher.HomeView: onPause
09-14 01:05:19.790  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-14 01:05:19.790  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.790  1020  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.790  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-14 01:05:19.790  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.790  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
09-14 01:05:19.790  1020  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.790  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,09-14 01:05:19.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.810  7391  7391 E Zygote  : MountEmulatedStorage()
09-14 01:05:19.810  7391  7391 E Zygote  : v2
09-14 01:05:19.810  7391  7391 I libpersona: KNOX_SDCARD checking this for 10089
09-14 01:05:19.810  7391  7391 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:19.810  1020  1047 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7391 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,09-14 01:05:19.820  7391  7391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:19.820  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:19.820  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.820  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
09-14 01:05:19.820  1020  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.820  7377  7377 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:19.820  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,09-14 01:05:19.820  7391  7391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:19.820  7391  7391 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-14 01:05:19.820  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.820  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.820  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.820  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.830  7401  7401 E Zygote  : MountEmulatedStorage()
,09-14 01:05:19.830  7401  7401 I libpersona: KNOX_SDCARD checking this for 10139
09-14 01:05:19.830  7401  7401 E Zygote  : v2
09-14 01:05:19.830  7401  7401 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:19.830  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:19.840  1020  1047 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7401 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,09-14 01:05:19.840  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:19.840  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:19.860   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
09-14 01:05:19.860  7391  7391 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:19.860  7391  7391 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:19.870  1020  1222 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.870  1020  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.870  1020  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
09-14 01:05:19.870  1020  1222 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1493, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
09-14 01:05:19.870  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:19.870  7401  7401 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:19.870  1020  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-14 01:05:19.870  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.870  1020  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.870  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,09-14 01:05:19.870  2581  2581 D Recents_RecreateReceiver: onReceive by home
,09-14 01:05:19.870  1020  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-14 01:05:19.880  1020  1033 D InputDispatcher: Focus entered window: 1493
,09-14 01:05:19.880  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-14 01:05:19.880  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-14 01:05:19.880  1493  1493 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-14 01:05:19.880  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-14 01:05:19.880  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.880  1020  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
09-14 01:05:19.880  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-14 01:05:19.880  7377  7377 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-14 01:05:19.880  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.880  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.880  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:19.880  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:19.890  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{2082c6fc token=android.os.BinderProxy@3b3c40f1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-14 01:05:19.890  1493  1493 D Launcher.HomeView: onStop
,09-14 01:05:19.890  1020  1508 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-14 01:05:19.890  7319  7319 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
09-14 01:05:19.890  1020  7423 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-14 01:05:19.900  1869  1869 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-14 01:05:19.900  7425  7425 I libpersona: KNOX_SDCARD checking this for 10084
09-14 01:05:19.900  7425  7425 E Zygote  : MountEmulatedStorage()
09-14 01:05:19.900  7425  7425 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:19.900  7425  7425 E Zygote  : v2
09-14 01:05:19.900  1020  1492 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7425 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,09-14 01:05:19.900  7425  7425 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:19.910  7425  7425 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:19.910  1184  1184 D PanelView: There is/are notification(s) 
,09-14 01:05:19.910  7425  7425 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-14 01:05:19.910  7391  7391 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-14 01:05:19.910  7391  7391 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-14 01:05:19.930  1493  1493 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b3c40f1 time:219796
,09-14 01:05:19.940  7425  7425 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:19.940  7425  7425 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:19.940  7401  7401 V TaskCloserActivity: TaskCloserActivity enter()
,09-14 01:05:19.940  7375  7375 D AndroidRuntime: 
09-14 01:05:19.940  7375  7375 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-14 01:05:19.950  7375  7375 D AndroidRuntime: CheckJNI is OFF
,09-14 01:05:19.950  7375  7375 D AndroidRuntime: readGMSProperty: start
09-14 01:05:19.950  7375  7375 D AndroidRuntime: readGMSProperty: already setted!!
09-14 01:05:19.950  7375  7375 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-14 01:05:19.950  7375  7375 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-14 01:05:19.950  7375  7375 D AndroidRuntime: readGMSProperty: end
09-14 01:05:19.950  7375  7375 D AndroidRuntime: addProductProperty: start
,09-14 01:05:19.950  7401  7401 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,09-14 01:05:19.950  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.950  1020  1508 I ActivityManager: Killing 6929:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-14 01:05:19.950  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.950  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,09-14 01:05:19.960  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{219e77e1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:219828
09-14 01:05:19.960  1020  1052 W ActivityManager: mDVFSHelper.release()
,09-14 01:05:19.970  7425  7425 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-14 01:05:19.970  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-14 01:05:19.980  1020  4371 D PersonaManager: isKioskContainerExistOnDevice
,09-14 01:05:19.990  1020  1032 I ActivityManager: Killing 6969:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-14 01:05:19.990  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:19.990  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
09-14 01:05:19.990  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:19.990  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,09-14 01:05:20.000  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-14 01:05:20.000  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.000  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.000  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.020  7449  7449 E Zygote  : MountEmulatedStorage(),
09-14 01:05:20.020  7449  7449 E Zygote  : v2,
09-14 01:05:20.020  7449  7449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:20.020  7449  7449 I libpersona: KNOX_SDCARD checking this for 10135
09-14 01:05:20.020  7449  7449 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:20.030  7449  7449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-14 01:05:20.030  1020  1032 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7449 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
09-14 01:05:20.030  7449  7449 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:20.030  1020  1032 I ActivityManager: Killing 6951:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-14 01:05:20.050  7449  7449 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:20.050  7449  7449 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:20.050   312   312 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 27.810ms
,09-14 01:05:20.070  7449  7449 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-14 01:05:20.070  7449  7449 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-14 01:05:20.070  7449  7449 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-14 01:05:20.070  7449  7449 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
09-14 01:05:20.070  7449  7449 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-14 01:05:20.070   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.719ms
,09-14 01:05:20.090  7375  7375 E AffinityControl: AffinityControl: registerfunction enter
09-14 01:05:20.090   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 16.699ms
,09-14 01:05:20.110  7375  7375 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-14 01:05:20.120  1020  1508 I ActivityManager: Killing 6994:com.sec.pcw.device/1000 (adj 15): empty #21
,09-14 01:05:20.120  7377  7377 D NearbySource: Nearby Source Create!
,09-14 01:05:20.120  7377  7377 D NearbyContext: Nearby Context Create!
,09-14 01:05:20.130  1020  1143 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-14 01:05:20.130  1020  1143 D PackageManager: START PACKAGE DELETE: observer{891186311}
09-14 01:05:20.130  1020  1143 D PackageManager: pkg{<packageName>}
09-14 01:05:20.130  1020  1143 D PackageManager: user{0}
09-14 01:05:20.130  1020  1143 D PackageManager: caller{2000}
09-14 01:05:20.130  1020  1143 D PackageManager: flags{2}
09-14 01:05:20.130  1020  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-14 01:05:20.130  1020  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-14 01:05:20.130  1020  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-14 01:05:20.130  1020  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-14 01:05:20.130  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-14 01:05:20.130  1020  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-14 01:05:20.130  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-14 01:05:20.130  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
09-14 01:05:20.130  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-14 01:05:20.130  1020  1060 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-14 01:05:20.150  1020  1047 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-14 01:05:20.150  1020  1047 I ActivityManager: Killing 7319:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,09-14 01:05:20.170   257   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-14 01:05:20.170   257   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-14 01:05:20.170  7377  7377 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-14 01:05:20.170  7377  7377 D SLinkSource: Samsung link source created
,09-14 01:05:20.250  1020  4371 W ActivityManager: Spurious death for ProcessRecord{1a6f87b4 7319:com.test.thalitest/u0a170}, curProc for 7319: null
,09-14 01:05:20.250  1020  1060 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-14 01:05:20.280  6383  6383 I art     : Explicit concurrent mark sweep GC freed 653(37KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 618us total 22.111ms
,09-14 01:05:20.290  1020  1492 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-14 01:05:20.290  1020  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-14 01:05:20.290  6704  6704 I art     : Explicit concurrent mark sweep GC freed 97(15KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 955us total 32.299ms
,09-14 01:05:20.300  2879  2879 I art     : Explicit concurrent mark sweep GC freed 18883(1087KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 789us total 32.516ms
,09-14 01:05:20.320  1869  1869 E SamsungIME: mOCRHelper is null
,09-14 01:05:20.330  1020  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-14 01:05:20.380  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-14 01:05:20.380  1020  1128 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-14 01:05:20.380  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-14 01:05:20.380  1020  1128 V NetworkStats: performPollLocked(flags=0x3)
,09-14 01:05:20.390  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-14 01:05:20.390  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-14 01:05:20.390  1020  1128 V NetworkStats: performPollLocked() took 10ms
09-14 01:05:20.390  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-14 01:05:20.400  1442  1442 D RegisteredServicesCache: empty dynamic service
,09-14 01:05:20.410  7377  7468 D ContactProvider: getAllContactInfoList Start
,09-14 01:05:20.410  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,09-14 01:05:20.410  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-14 01:05:20.440  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-14 01:05:20.440  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-14 01:05:20.470  1020  1020 I art     : Explicit concurrent mark sweep GC freed 67780(4MB) AllocSpace objects, 44(704KB) LOS objects, 33% free, 23MB/35MB, paused 2.606ms total 187.586ms
09-14 01:05:20.470  1020  4371 I art     : WaitForGcToComplete blocked for 154.302ms for cause Explicit
,09-14 01:05:20.510  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,09-14 01:05:20.510  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-14 01:05:20.510  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-14 01:05:20.510  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-14 01:05:20.510  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-14 01:05:20.520  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
,09-14 01:05:20.520  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-14 01:05:20.590  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-14 01:05:20.590  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: uID is 10170
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-14 01:05:20.590  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-14 01:05:20.590  1020  1166 D TaskPersister: removeObsoleteFile: deleting file=164_task.xml
,09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: uID is 10170
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-14 01:05:20.590  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-14 01:05:20.600  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-14 01:05:20.600  1020  3382 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-14 01:05:20.600  1020  1020 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-14 01:05:20.630  1020  4371 I art     : Explicit concurrent mark sweep GC freed 14730(839KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.226ms total 156.515ms
09-14 01:05:20.630  1020  1060 I art     : WaitForGcToComplete blocked for 265.020ms for cause Explicit
,09-14 01:05:20.630  1782  2124 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-14 01:05:20.640  1020  1032 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-14 01:05:20.640  1020  1032 D SecContentProvider2: mCursor = null
,09-14 01:05:20.640  1020  1046 D EnterpriseDeviceManagerService: Package has changed for user 0
09-14 01:05:20.640  1020  1046 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-14 01:05:20.640  1020  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-14 01:05:20.650  1020  1046 W TextServicesManagerService: no available spell checker services found
09-14 01:05:20.650  7377  7377 D GalleryCacheReady: Receive : home resume
09-14 01:05:20.660  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.660  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:20.660  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
09-14 01:05:20.660  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.670  7058  7058 D Mms/UIEventReceiver: ui event
09-14 01:05:20.670  1020  1492 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
09-14 01:05:20.670  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.670  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.670  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:20.670  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,09-14 01:05:20.680  7401  7401 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,09-14 01:05:20.690  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.690  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.690  2863  2863 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 14 01:05:20 GMT+02:00 2016
,09-14 01:05:20.690  1020  1143 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-14 01:05:20.690  1020  1143 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-14 01:05:20.690  1020  1143 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.690  1020  1143 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:20.690  1020  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-14 01:05:20.700  2863  2863 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-14 01:05:20.700  1020  1508 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-14 01:05:20.700  1020  1508 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
09-14 01:05:20.700  1020  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
09-14 01:05:20.700  2863  2863 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-14 01:05:20.700  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.700  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.700  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.700  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.700  2863  2863 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-14 01:05:20.710  2863  2863 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-14 01:05:20.710  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-14 01:05:20.710  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-14 01:05:20.710  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-14 01:05:20.720  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-14 01:05:20.720  7471  7471 E Zygote  : MountEmulatedStorage()
09-14 01:05:20.720  7471  7471 I libpersona: KNOX_SDCARD checking this for 10090
09-14 01:05:20.720  7471  7471 E Zygote  : v2
09-14 01:05:20.720  7471  7471 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:20.720  7471  7471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:20.730  1020  1508 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7471 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-14 01:05:20.720  7471  7471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:20.730  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-14 01:05:20.730  7471  7471 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:20.730  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.730  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.730  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.730  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.750  7484  7484 E Zygote  : MountEmulatedStorage()
09-14 01:05:20.750  7484  7484 E Zygote  : v2
09-14 01:05:20.750  7484  7484 I libpersona: KNOX_SDCARD checking this for 10032
09-14 01:05:20.750  7484  7484 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:20.750  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:20.750  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:20.750  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-14 01:05:20.760  1020  1047 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7484 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-14 01:05:20.760  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
09-14 01:05:20.760  7471  7471 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:20.760  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.760  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.760  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.760  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.760  7471  7471 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:20.780  7496  7496 E Zygote  : MountEmulatedStorage()
09-14 01:05:20.780  7496  7496 I libpersona: KNOX_SDCARD checking this for 10052
09-14 01:05:20.780  7496  7496 E Zygote  : v2
09-14 01:05:20.780  7496  7496 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:20.780  7496  7496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:20.780  7496  7496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:20.780  7496  7496 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-14 01:05:20.780  1020  1047 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7496 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-14 01:05:20.790  1020  1046 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-14 01:05:20.800  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.,
09-14 01:05:20.800  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-14 01:05:20.800  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.800  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.810  1020  1060 I art     : Explicit concurrent mark sweep GC freed 6248(361KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.066ms total 173.535ms
,09-14 01:05:20.810  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.810  7496  7496 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:20.810  7516  7516 I libpersona: KNOX_SDCARD checking this for 10098
09-14 01:05:20.810  7516  7516 E Zygote  : MountEmulatedStorage()
09-14 01:05:20.810  7516  7516 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:20.810  7516  7516 E Zygote  : v2
,09-14 01:05:20.820  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:20.820  7496  7496 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:20.820  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:20.820  7484  7484 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:20.820  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:20.820  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:20.820  1020  1047 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7516 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-14 01:05:20.830  2863  7470 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-14 01:05:20.830  2863  7470 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-14 01:05:20.840  7377  7468 D ContactProvider: getAllContactInfoList End
,09-14 01:05:20.840  7377  7468 I syncContacts: thread: 1363, sync time = 567
,09-14 01:05:20.840  2863  2863 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-14 01:05:20.850  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:20.850  7516  7516 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:20.860  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.870  1020  1046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-14 01:05:20.870  1020  1046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-14 01:05:20.870  1020  1046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-14 01:05:20.870  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.870  7471  7471 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-14 01:05:20.870  7471  7471 D elm:15121: ELMEngine.ELMEngine( context ).
,09-14 01:05:20.880  1020  1060 D PackageManager: delete codoeFile: 
,09-14 01:05:20.880  7471  7471 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-14 01:05:20.880  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.880  1020  1033 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-14 01:05:20.880  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-14 01:05:20.880  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.880  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-14 01:05:20.880  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-14 01:05:20.890  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-14 01:05:20.890  7471  7471 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-14 01:05:20.890  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.890  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-14 01:05:20.890  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.890  1020  1060 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-14 01:05:20.890  1020  1060 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-14 01:05:20.890  1020  1060 D PackageManager: result of delete: 1{891186311}
,09-14 01:05:20.900  7471  7471 D elm:15121: ElmAgentService : onCreate()
,09-14 01:05:20.900  7471  7531 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-14 01:05:20.900  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.900  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-14 01:05:20.900  7471  7531 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-14 01:05:20.900  7471  7531 D elm:15121: MDMBridge.getInstance()
09-14 01:05:20.900  7471  7531 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-14 01:05:20.900  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-14 01:05:20.900  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-14 01:05:20.900  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-14 01:05:20.910  7375  7375 D AndroidRuntime: Shutting down VM
,09-14 01:05:20.910  1020  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-14 01:05:20.910  1020  1060 D PackageManager: userId{-1}
09-14 01:05:20.910  1020  1060 D PackageManager: andCode{true}
,09-14 01:05:20.910  7471  7531 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-14 01:05:20.910  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-14 01:05:20.910  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.910  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.910  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.910  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.930  7534  7534 E Zygote  : MountEmulatedStorage()
,09-14 01:05:20.930  7534  7534 E Zygote  : v2
09-14 01:05:20.930  7484  7535 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-14 01:05:20.930  7534  7534 I libpersona: KNOX_SDCARD checking this for 1000
09-14 01:05:20.930  7534  7534 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:20.930  7484  7535 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-14 01:05:20.930  7534  7534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-14 01:05:20.940  1020  1481 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7534 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-14 01:05:20.940  1020  1481 I ActivityManager: Killing 6888:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-14 01:05:20.940  7534  7534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:20.940  7534  7534 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:20.940  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-14 01:05:20.940  7484  7535 D SPPClientService: PushLog.txt file is not deleted.
09-14 01:05:20.950  7471  7471 D elm:15121: ElmAgentService : onDestroy().
09-14 01:05:20.950  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.950  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.950  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:20.950  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:20.950  7484  7535 D SPPClientService: PushLog.txt file is not deleted.
09-14 01:05:20.950  7484  7535 D SPPClientService: ============PushLog. stop!
,09-14 01:05:20.960  2648  2648 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-14 01:05:20.960  2648  2648 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-14 01:05:20.960  7550  7550 E Zygote  : MountEmulatedStorage()
,09-14 01:05:20.960  7550  7550 E Zygote  : v2
09-14 01:05:20.960  7550  7550 I libpersona: KNOX_SDCARD checking this for 10032
09-14 01:05:20.960  7550  7550 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:20.960  7550  7550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:20.970  1020  1033 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7550 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-14 01:05:20.970  1020  1033 I ActivityManager: Killing 7040:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-14 01:05:20.970  7550  7550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:20.970  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-14 01:05:20.970  7534  7534 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:20.970  7550  7550 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-14 01:05:20.970  7534  7534 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:20.970  1020  1046 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-14 01:05:20.980  1020  1046 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-14 01:05:20.980  1020  1481 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-14 01:05:20.990  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-14 01:05:20.990  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.990  1020  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:20.990  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-14 01:05:20.990  1020  1339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:20.990  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-14 01:05:20.990  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:20.990  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:20.990  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:20.990  1020  1222 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-14 01:05:21.000  1020  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-14 01:05:21.000  1020  1222 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.000  1020  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.000  1020  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-14 01:05:21.000  3858  7566 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-14 01:05:21.010  3858  7566 D AccountUtils: Clearing selected account for com.test.thalitest
09-14 01:05:21.010  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-14 01:05:21.010  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.010  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.010  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.010  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.010  7550  7550 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:21.010  7550  7550 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:21.030  7573  7573 E Zygote  : MountEmulatedStorage()
09-14 01:05:21.030  7573  7573 I libpersona: KNOX_SDCARD checking this for 10055
09-14 01:05:21.030  7573  7573 E Zygote  : v2
09-14 01:05:21.030  7573  7573 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:21.040  7573  7573 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:21.040  1020  1481 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7573 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-14 01:05:21.040  7573  7573 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:21.040  7573  7573 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:21.040  1020  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-14 01:05:21.050  1020  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-14 01:05:21.050  1020  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.050  1020  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.050  1020  3818 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-14 01:05:21.060  1020  3818 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.060  1020  3818 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.060  1020  3818 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.060  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-14 01:05:21.060  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.060  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.060  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.060  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.070  7573  7573 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:21.070  7573  7573 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:21.080  7589  7589 E Zygote  : MountEmulatedStorage()
,09-14 01:05:21.090  7589  7589 E Zygote  : v2
09-14 01:05:21.090  7589  7589 I libpersona: KNOX_SDCARD checking this for 1000
09-14 01:05:21.090  7589  7589 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:21.090  7589  7589 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:21.090  1020  1033 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7589 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-14 01:05:21.090  1020  1033 I ActivityManager: Killing 7079:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
09-14 01:05:21.090  7589  7589 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:21.090  7589  7589 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:21.100  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-14 01:05:21.100  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.100  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.100  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.100  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.110  3858  7566 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-14 01:05:21.120  7375  7375 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-14 01:05:21.120  1020  1339 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-14 01:05:21.120  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.120  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.120  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.120  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.130  3858  3858 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-14 01:05:21.130  3858  3858 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-14 01:05:21.130  1020  1222 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-14 01:05:21.130  1020  1222 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.130  1020  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.130  1020  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.130  7589  7589 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:21.140  7589  7589 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:21.140  7573  7573 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-14 01:05:21.140  3858  3858 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-14 01:05:21.140  1020  4371 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-14 01:05:21.140  3858  3858 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-14 01:05:21.140  7550  7604 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-14 01:05:21.140  1020  4371 W ActivityManager: userId = 0, bbcId = -10000
,09-14 01:05:21.140  7550  7604 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-14 01:05:21.140  1020  4371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.140  1020  4371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.150  1020  3818 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-14 01:05:21.150  1020  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.150  1020  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.150  1020  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.150  1020  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.160  3858  7599 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
09-14 01:05:21.160  3858  7599 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,09-14 01:05:21.160  7550  7604 D SPPClientService: PushLog.txt file is not deleted.
09-14 01:05:21.160  7550  7604 D SPPClientService: PushLog.txt file is not deleted.
09-14 01:05:21.160  7550  7604 D SPPClientService: ============PushLog. stop!
,09-14 01:05:21.170  7609  7609 E Zygote  : MountEmulatedStorage(),
,09-14 01:05:21.170  7609  7609 I libpersona: KNOX_SDCARD checking this for 1000
09-14 01:05:21.170  7609  7609 E Zygote  : v2
,09-14 01:05:21.170  7609  7609 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:21.170  7609  7609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:21.170  7609  7609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:21.170  1020  3818 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7609 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-14 01:05:21.170  7609  7609 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:21.180  7573  7573 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
09-14 01:05:21.180  7573  7573 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-14 01:05:21.180  7573  7573 D UserAnalysis: Create SecureDbHelper,
,09-14 01:05:21.180  1020  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:21.180  1020  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.180  1020  1222 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.180  1020  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.180  1020  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.190  3858  7599 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
09-14 01:05:21.190  3858  7599 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,09-14 01:05:21.200  7609  7609 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:21.200  1020  1477 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-14 01:05:21.200  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.200  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
09-14 01:05:21.200  1020  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:21.200  7609  7609 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:21.200  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-14 01:05:21.200  7573  7573 D IntelligenceServiceApplication: onCreate()
,09-14 01:05:21.210  7573  7573 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-14 01:05:21.220  7573  7573 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-14 01:05:21.220  7377  7377 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-14 01:05:21.230  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-14 01:05:21.230  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-14 01:05:21.240   288   288 E SMD     : DCD OFF
,09-14 01:05:21.240  3858  7599 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
09-14 01:05:21.240  3858  7599 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,09-14 01:05:21.240  3858  7599 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,09-14 01:05:21.250  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-14 01:05:21.260  7609  7609 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-14 01:05:21.260  7609  7609 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-14 01:05:21.260  7609  7609 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-14 01:05:21.270  7589  7589 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
09-14 01:05:21.270  3858  7599 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
09-14 01:05:21.270  3858  7599 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,09-14 01:05:21.270  1020  1339 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,09-14 01:05:21.270  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.280  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.280  1020  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:21.280  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-14 01:05:21.280  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-14 01:05:21.280  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.280  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.280  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.280  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.290  7609  7609 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-14 01:05:21.290  7609  7609 I PCWCLIENTTRACE_PushUtil: sales region : global
09-14 01:05:21.290  7609  7609 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-14 01:05:21.290  7609  7609 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-14 01:05:21.300  7635  7635 E Zygote  : MountEmulatedStorage()
09-14 01:05:21.300  7635  7635 I libpersona: KNOX_SDCARD checking this for 1000
09-14 01:05:21.300  7635  7635 E Zygote  : v2
09-14 01:05:21.300  7635  7635 I libpersona: KNOX_SDCARD not a persona
,09-14 01:05:21.300  1020  1032 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-14 01:05:21.300  6383  7632 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-14 01:05:21.320  1020  1481 I ActivityManager: Killing 7096:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-14 01:05:21.320  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-14 01:05:21.320  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.320  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.320  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.320  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.320  1020  1508 D LocationManagerService: getProviders()=[passive, gps]
,09-14 01:05:21.330  7635  7635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:21.330  3858  7599 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
,09-14 01:05:21.330  3858  7599 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,09-14 01:05:21.330  3858  7599 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
09-14 01:05:21.330  3858  7599 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,09-14 01:05:21.340  7635  7635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:21.340  7642  7642 E Zygote  : MountEmulatedStorage()
09-14 01:05:21.340  7642  7642 E Zygote  : v2
09-14 01:05:21.340  7642  7642 I libpersona: KNOX_SDCARD checking this for 10029
09-14 01:05:21.340  7642  7642 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:21.340  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:21.340  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:21.350  7635  7635 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:21.350  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-14 01:05:21.350  1020  1481 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7642 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
09-14 01:05:21.350  1020  1481 I ActivityManager: Killing 7113:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-14 01:05:21.350  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-14 01:05:21.360  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-14 01:05:21.370  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,09-14 01:05:21.370  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,09-14 01:05:21.370  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-14 01:05:21.380  1020  4371 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-14 01:05:21.380   312   312 I art     : Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 29.065ms
,09-14 01:05:21.380  1020  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.380  1020  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.380  1020  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.380  1020  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-14 01:05:21.390  7635  7635 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:21.390  7635  7635 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:21.400   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.679ms
,09-14 01:05:21.400  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-14 01:05:21.400  7642  7642 D ActivityThread: Added TimaKeyStore provider
09-14 01:05:21.410  7573  7573 D BluetoothAdapter: cancelDiscovery
,09-14 01:05:21.410  6383  6383 I art     : Explicit concurrent mark sweep GC freed 628(36KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 710us total 146.655ms
,09-14 01:05:21.420   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.521ms
,09-14 01:05:21.430  1493  1493 D Launcher.Model: reloadBadges entered.
09-14 01:05:21.430  7143  7157 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-14 01:05:21.430  7143  7157 D BadgeProvider: sendNotify, [notify] : null
09-14 01:05:21.430  7143  7157 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-14 01:05:21.430  7143  7157 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-14 01:05:21.430  7143  7157 D BadgeProvider: update, [UpdateCount] : 1
,09-14 01:05:21.430  7668  7668 E Zygote  : MountEmulatedStorage(),
09-14 01:05:21.430  7668  7668 I libpersona: KNOX_SDCARD checking this for 10014
09-14 01:05:21.430  7668  7668 E Zygote  : v2
09-14 01:05:21.430  7668  7668 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:21.430  7668  7668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-14 01:05:21.440  7668  7668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-14 01:05:21.440  7668  7668 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-14 01:05:21.440  1020  4371 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7668 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-14 01:05:21.450  7058  7058 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,09-14 01:05:21.460  3220  3242 D BluetoothAdapterProperties: mDiscovering is false
09-14 01:05:21.460  3220  3242 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-14 01:05:21.460  7573  7573 D BluetoothAdapter: cancelDiscovery = true
09-14 01:05:21.460  7573  7573 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-14 01:05:21.470  1020  3818 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-14 01:05:21.470  1020  3818 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.470  1020  3818 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.470  1020  3818 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:21.470  1020  3818 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-14 01:05:21.470  3858  7680 I GMPM-SVC: App measurement is starting up
09-14 01:05:21.480  7496  7568 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-14 01:05:21.480  7058  7685 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-14 01:05:21.480  7058  7685 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,09-14 01:05:21.480  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-14 01:05:21.480  1020  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:21.480  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,09-14 01:05:21.480  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.480  1020  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.480  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.490  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-14 01:05:21.490  7573  7573 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-14 01:05:21.490  1020  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-14 01:05:21.490  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.490  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.490  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.490  7668  7668 D TimaKeyStoreProvider: TimaSignature is unavailable
09-14 01:05:21.490  7668  7668 D ActivityThread: Added TimaKeyStore provider
,09-14 01:05:21.490  1020  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:21.490  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,09-14 01:05:21.500  2648  2648 I ConfigService: onCreate
,09-14 01:05:21.500  3858  3858 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-14 01:05:21.500  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.500  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.500  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-14 01:05:21.500  7573  7573 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,09-14 01:05:21.500  7573  7573 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-14 01:05:21.500  7573  7573 E UserAnalysis: It failed to get the database for dump_log
09-14 01:05:21.500  7573  7573 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,09-14 01:05:21.500  3858  4299 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-14 01:05:21.500  7573  7573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-14 01:05:21.500  7573  7573 E UserAnalysis: It failed to get the database for dump_log
09-14 01:05:21.510  3858  7680 E GMPM-SVC: AppMeasurementService not registered/enabled
09-14 01:05:21.510  3858  7680 E GMPM-SVC: Uploading is not possible. App measurement disabled
09-14 01:05:21.510  2648  7687 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/config.db" with flag (131138) and mode_t (0) due to error (30)
09-14 01:05:21.510  1020  3818 I TactileAssist: enable value -1
09-14 01:05:21.510  1020  3818 I TactileAssist: internal enable value -1
09-14 01:05:21.510  1020  3818 I TactileAssist: intensity value -1
09-14 01:05:21.510  1020  3818 I TactileAssist: saveAppList value true
09-14 01:05:21.520  1020  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:21.520  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-14 01:05:21.520  2648  7687 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-14 01:05:21.520  2648  7687 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:05:21.520  1020  3818 I TactileAssist: List of disabled apps :
09-14 01:05:21.520  1020  1490 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.520  1020  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.520  1020  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.520  3858  7623 W BaseAppContext: Using Auth Proxy for data requests.
09-14 01:05:21.530  1020  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-14 01:05:21.530  2648  7687 W SQLiteOpenHelper: Opened config.db in read-only mode
09-14 01:05:21.530  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.530  1020  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.530  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.530  3858  7689 I PeopleContactsSync: CP2 sync disabled
09-14 01:05:21.530  7496  7568 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
09-14 01:05:21.530  1020  1033 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
09-14 01:05:21.530  7635  7688 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
09-14 01:05:21.530  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-14 01:05:21.540  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.e.Jx(UpdateIcingCorporaService.java:408)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.g.bdp(UpdateIcingCorporaService.java:347)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-14 01:05:21.540  7496  7568 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:05:21.540  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.540  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.540  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-14 01:05:21.540  3858  7680 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/google_app_measurement.db" with flag (131138) and mode_t (0) due to error (30)
09-14 01:05:21.540  7635  7688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-14 01:05:21.550  7690  7690 E Zygote  : MountEmulatedStorage()
09-14 01:05:21.550  7690  7690 E Zygote  : v2
09-14 01:05:21.550  7690  7690 I libpersona: KNOX_SDCARD checking this for 1000
09-14 01:05:21.550  7690  7690 I libpersona: KNOX_SDCARD not a persona
09-14 01:05:21.550  7690  7690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-14 01:05:21.560  7690  7690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-14 01:05:21.560  1020  1481 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-14 01:05:21.560  1020  1481 I ActivityManager: Killing 7161:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
09-14 01:05:21.560  7690  7690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-14 01:05:21.560  1020  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-14 01:05:21.560  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0
09-14 01:05:21.560  1020  1490 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.560  1020  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-14 01:05:21.560  1020  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:05:21.560  3858  7680 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
09-14 01:05:21.570  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-14 01:05:21.570  1020  1477 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-14 01:05:21.570  1020  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-14 01:05:21.570  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-14 01:05:21.570  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-14 01:05:21.570  3858  7680 E GMPM-SVC: Opening the database failed, dropping and recreating it

```
