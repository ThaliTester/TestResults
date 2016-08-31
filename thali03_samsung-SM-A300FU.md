#### Test 832760823d6df89_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-31 11:16:38.453   288   288 E SMD     : DCD OFF
08-31 11:16:38.733  7220  7220 D AndroidRuntime: 
08-31 11:16:38.733  7220  7220 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:16:38.733  7220  7220 D AndroidRuntime: CheckJNI is OFF
08-31 11:16:38.733  7220  7220 D AndroidRuntime: readGMSProperty: start
08-31 11:16:38.733  7220  7220 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:16:38.733  7220  7220 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 11:16:38.733  7220  7220 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:16:38.733  7220  7220 D AndroidRuntime: readGMSProperty: end
08-31 11:16:38.733  7220  7220 D AndroidRuntime: addProductProperty: start
08-31 11:16:38.863  7220  7220 E AffinityControl: AffinityControl: registerfunction enter
08-31 11:16:38.883  7220  7220 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:16:38.893  1017  3801 E PersonaManagerService: inState():  stateMachine is null !!
08-31 11:16:38.893  1017  3801 I PersonaManagerService: PersonaId don't exist
08-31 11:16:38.893  1017  3801 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 11:16:38.893  1017  3801 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-31 11:16:38.913  1017  3801 W ActivityManager: mDVFSHelper.acquire()
08-31 11:16:38.913  1017  3801 D FocusedStackFrame: Set to : 0
08-31 11:16:38.913  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 11:16:38.913  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 11:16:38.923  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:38.923  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:38.923  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:38.923  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:38.933  1017  3801 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 11:16:38.933  1017  3801 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7231 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:16:38.933  1017  3801 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:16:38.933  7231  7231 I libpersona: KNOX_SDCARD checking this for 10170
08-31 11:16:38.933  1017  3801 D InputDispatcher: Focused application set to: xxxx
08-31 11:16:38.933  7231  7231 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:38.933  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 11:16:38.933  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 11:16:38.933  1017  3801 D InputDispatcher: Focus left window: 1489
08-31 11:16:38.933  7231  7231 E Zygote  : MountEmulatedStorage()
08-31 11:16:38.933  7231  7231 E Zygote  : v2
08-31 11:16:38.933  7220  7220 D AndroidRuntime: Shutting down VM
08-31 11:16:38.933   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-31 11:16:38.933  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:38.943  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:16:38.943  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 11:16:38.953  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:16:38.953  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 11:16:38.963  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:16:38.963  7231  7231 D ActivityThread: Added TimaKeyStore provider
08-31 11:16:38.963  1017  3751 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 11:16:38.973  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 11:16:38.983  1017  3751 D PersonaManager: isKioskContainerExistOnDevice
08-31 11:16:38.983  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 11:16:39.023   258  1039 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-31 11:16:39.023   258   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-31 11:16:39.023  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{11e2681a token=android.os.BinderProxy@180e26d8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 11:16:39.023  1489  1489 D Launcher: onTrimMemory. Level: 20
08-31 11:16:39.103  7231  7231 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 11:16:39.143  7220  7220 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 11:16:39.153  7231  7231 I cr.library_loader: Time to load native libraries: 8 ms (timestamps 5660-5668)
,08-31 11:16:39.153  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:16:39.173  7231  7231 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19765014}
,08-31 11:16:39.173  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:16:39.183  7231  7231 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
,08-31 11:16:39.223  7231  7231 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 11:16:39.223  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:16:39.233  7231  7231 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:16:39.283  7231  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:16:39.283  7231  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:16:39.283  7231  7231 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:16:39.283  7231  7231 I Adreno-EGL: Local Branch: 
08-31 11:16:39.283  7231  7231 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:16:39.283  7231  7231 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:16:39.283  7231  7231 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:16:39.383  7231  7231 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:16:39.393  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:16:39.393  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:16:39.403  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 11:16:39.403  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 11:16:39.483  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2504dd72 u0 com.test.thalitest/.MainActivity t164}
08-31 11:16:39.513  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:16:39.523  7231  7231 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 11:16:39.543  7231  7231 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 11:16:39.543  7231  7231 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-31 11:16:39.543  7231  7231 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-31 11:16:39.553  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:16:39.553  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:16:39.673  7231  7271 D OpenGLRenderer: Render dirty regions requested: true
08-31 11:16:39.673  1017  1496 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 11:16:39.673  1017  1496 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:16:39.673  1017  1496 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 11:16:39.673  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 11:16:39.673  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 11:16:39.683  7231  7258 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-31 11:16:39.683  7231  7231 V ActivityThread: updateVisibility : ActivityRecord{36a36874 token=android.os.BinderProxy@3387c061 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 11:16:39.693  7231  7231 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 11:16:39.693  7231  7231 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 11:16:39.703  1017  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:16:39.703  1017  3816 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:16:39.703  1017  3816 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:16:39.703  1017  3816 D BatteryService: stay LED for charging
08-31 11:16:39.703  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 11:16:39.703  1017  1017 I MotionRecognitionService: Plugged
08-31 11:16:39.703  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-31 11:16:39.703   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-31 11:16:39.703  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 11:16:39.703  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 11:16:39.713  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:16:39.713  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-31 11:16:39.713  1017  1548 D InputDispatcher: Focus entered window: 7231
08-31 11:16:39.723  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:16:39.723  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 11:16:39.723  7231  7231 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 11:16:39.723  7231  7271 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 11:16:39.723  3218  3218 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:16:39.723  3218  3357 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:16:39.723  7231  7271 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 11:16:39.723  7231  7271 D OpenGLRenderer: Enabling debug mode 0
08-31 11:16:39.733  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:16:39.743  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:16:39.743  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:16:39.743  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:16:39.743  1178  1178 D SViewCoverView: level :100 plugged : 2
08-31 11:16:39.753  1017  1547 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-31 11:16:39.763  1178  1178 D PanelView: There is/are notification(s) 
08-31 11:16:39.763  1017  7277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 11:16:39.773  1017  1048 I ActivityManager: Displayed Component not be shown by security: +792ms (total +38s530ms)
08-31 11:16:39.773  1017  1048 W ActivityManager: mDVFSHelper.release()
08-31 11:16:39.773  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2504dd72 u0 com.test.thalitest/.MainActivity t164} time:156288
08-31 11:16:39.783   258  1039 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-31 11:16:39.783  1998  1998 I SamsungIME: getCurrentCandidateView
08-31 11:16:39.793  7231  7231 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-31 11:16:39.793  7231  7231 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3387c061 time:156305
08-31 11:16:39.813  7231  7231 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7231
08-31 11:16:39.893  1998  1998 D SamsungIME: Dismiss ExpandCandiate
08-31 11:16:39.993  7231  7231 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-31 11:16:40.053  1998  1998 I SamsungIME: getDebugLevel  : 0x4f4c
08-31 11:16:40.073  7231  7275 D jxcore_app_log: JniHelper::setJavaVM(0xb7b982b0), pthread_self() = -1206755032
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 11:16:40.083  7231  7275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1757f56a added. We now have 1 listener(s)
08-31 11:16:40.093  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-31 11:16:40.093  1998  1998 I SamsungIME: getDebugLevel  : 0x4f4c
08-31 11:16:40.093  7231  7275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:16:40.093  7231  7275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:40.093  7231  7275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:16:40.103  7231  7275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@153083d1 added. We now have 1 listener(s)
08-31 11:16:40.103  7231  7275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:40.103  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:40.103  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 11:16:40.103  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:16:40.103  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:16:40.103  7231  7275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 11:16:40.103  1998  1998 I SamsungIME: KeybaordView init() : load resources
08-31 11:16:40.113  7231  7275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:40.113  7231  7275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-31 11:16:40.113  7231  7275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:40.123  7231  7275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:40.123  7231  7275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:16:40.123  7231  7275 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:40.123  7231  7275 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:16:40.123  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:40.123  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:40.133  1998  1998 I SamsungIME: getCurrentKeyboard
08-31 11:16:40.133  1998  1998 I SamsungIME: getTextKeyboard
,08-31 11:16:40.153  7231  7231 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:16:40.153  1998  1998 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 11:16:40.703  7231  7286 W jxcore-log: Initializing JXcore engine
08-31 11:16:40.703  7231  7286 W jxcore-log: JXcore engine is ready
,08-31 11:16:40.753  1996  1996 E audit   : type=1400 msg=audit(1472635000.753:205): avc:  denied  { ioctl } for  pid=7286 comm="Thread-1375" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 11:16:40.763  1996  1996 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:16:40.763  1996  1996 E audit   : type=1300 msg=audit(1472635000.753:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9f9c78f8 items=0 ppid=305 ppcomm=main pid=7286 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1375" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 11:16:40.763  1996  1996 E audit   : type=1320 msg=audit(1472635000.753:205): 
,08-31 11:16:40.773  7231  7286 W jxcore-log: Starting JXcore engine
,08-31 11:16:40.873  7231  7286 W jxcore-log: Platform android
08-31 11:16:40.873  7231  7286 W jxcore-log: 
08-31 11:16:40.873  7231  7286 W jxcore-log: Process ARCH arm
08-31 11:16:40.873  7231  7286 W jxcore-log: 
,08-31 11:16:41.083  7231  7286 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:16:41.083  7231  7286 I jxcore-log: 
,08-31 11:16:41.083  7231  7286 W jxcore-log: JXcore engine is started
,08-31 11:16:41.083  7231  7275 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:16:41.083  7231  7231 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:16:41.453   288   288 E SMD     : DCD OFF,
,08-31 11:16:42.483   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:16:43.483   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:16:44.463   288   288 E SMD     : DCD OFF
,08-31 11:16:44.483   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:16:45.033  1017  3358 D SSRM:n  : SIOP:: AP = 310
,08-31 11:16:45.483   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:16:46.293  1017  3382 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 11:16:46.483   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:16:47.463   288   288 E SMD     : DCD OFF,
,08-31 11:16:47.483   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-31 11:16:48.973  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-31 11:16:49.743  1017  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:16:49.743  1017  1547 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:16:49.743  1017  1547 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 11:16:49.743  1017  1547 D BatteryService: stay LED for charging
08-31 11:16:49.743  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:16:49.743  1017  1017 I MotionRecognitionService: Plugged
,08-31 11:16:49.753  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:16:49.753  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:16:49.753  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:16:49.753  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 11:16:49.753  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:16:49.763  3218  3218 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 11:16:49.763  3218  3357 D HeadsetStateMachine: Disconnected process message: 10
,08-31 11:16:49.773  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:16:49.773  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:16:49.773  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:16:49.773  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 11:16:49.783  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-31 11:16:50.073  1017  1050 I PowerManagerService: [PWL] Off : 105s ago,
,08-31 11:16:50.463   288   288 E SMD     : DCD OFF,
,08-31 11:16:51.553  1017  1309 E Watchdog: !@Sync 5
,08-31 11:16:53.243  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 11:16:53.243  7231  7286 I jxcore-log: 
,08-31 11:16:53.243  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 11:16:53.243  7231  7286 I jxcore-log: 
,08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:53.253  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:53.253  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:53.253  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:16:53.253  7231  7286 I jxcore-log: 
,08-31 11:16:53.253  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:16:53.253  7231  7286 I jxcore-log: 
,08-31 11:16:53.463   288   288 E SMD     : DCD OFF,
,08-31 11:16:53.813  1691  3113 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-31 11:16:53.933  7231  7286 I jxcore-log: Unit Test app is loaded
08-31 11:16:53.933  7231  7286 I jxcore-log: 
,08-31 11:16:53.943  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:53.943  7231  7286 I jxcore-log: 
,08-31 11:16:53.943  7231  7231 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:16:53.943  7231  7286 D executeNativeTests: Running unit tests
,08-31 11:16:54.033  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:54.033  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba added. We now have 2 listener(s)
,08-31 11:16:54.033  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:16:54.033  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:54.033  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:54.033  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:54.033  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b added. We now have 2 listener(s)
08-31 11:16:54.033  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:54.033  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:16:54.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.043  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.043  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:54.043  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:16:54.053  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:16:54.053  7231  7286 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 11:16:54.053  7231  7286 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:16:54.053  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.053  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.053  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.053  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba removed from the list
08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.053  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b removed from the list
,08-31 11:16:54.053  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.053  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.053  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:54.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:54.063  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.063  7231  7286 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 11:16:54.063  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.063  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.063  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.063  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.063  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.063  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.063  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.063  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.063  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.063  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.063  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:16:54.073  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.073  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.073  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.073  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.073  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.073  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.073  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.073  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.073  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.073  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.073  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.073  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.073  7231  7286 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:54.073  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.073  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:54.073  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:54.073  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:54.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:54.083  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:54.083  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:54.083  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:54.093  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:16:54.093  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:16:54.093  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 11:16:54.103  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 11:16:54.103  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:16:54.103  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:16:54.103  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:16:54.103  3218  3378 D BtGatt.GattService: registerClient() - UUID=497ce813-e498-4417-ab60-95e818b91968
,08-31 11:16:54.153  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=497ce813-e498-4417-ab60-95e818b91968, clientIf=6
,08-31 11:16:54.153  7231  7242 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:16:54.153  3218  3354 D BtGatt.GattService: start scan with filters,
08-31 11:16:54.153  3218  3356 D BtGatt.ScanManager: handling starting scan
08-31 11:16:54.153  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:16:54.153  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:16:54.153  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:54.153  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:16:54.153  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:54.163  3218  3356 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:16:54.163  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:54.163  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:16:54.163  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:16:54.173  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:16:54.173  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.173  3218  3356 D BtGatt.ScanManager: allow scan with filters
,08-31 11:16:54.173  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:16:54.173  3218  3356 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-31 11:16:54.173  7231  7286 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:16:54.173  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:16:54.173  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.173  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:16:54.173  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:16:54.183  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.183  7231  7286 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:16:54.183  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.183  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:16:54.183  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.183  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:16:54.183  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:16:54.183  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:54.183  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:16:54.183  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:16:54.183  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:16:54.183  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.183  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:16:54.183  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-31 11:16:54.183  3218  3229 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:16:54.183  3218  3354 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:16:54.193  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:16:54.193  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:54.193  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:16:54.193  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:16:54.193  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:54.193  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:16:54.193  3218  3356 D BtGatt.ScanManager: filter size is 1
,08-31 11:16:54.203  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:16:54.203  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 11:16:54.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.203  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.203  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:54.203  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.203  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.203  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.203  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.203  7231  7286 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:16:54.203  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.203  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:16:54.203  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:54.203  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:16:54.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:54.203  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.203  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.213  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.213  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:16:54.213  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.213  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:16:54.213  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:16:54.213  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.223  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:54.223  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:54.223  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:54.223  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:54.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:54.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:54.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:16:54.223  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.223  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:16:54.223  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:16:54.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:16:54.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-31 11:16:54.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:16:54.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:16:54.233  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:16:54.233  3218  3354 D BtGatt.GattService: registerClient() - UUID=87bc5f1a-3391-4e15-92a3-2da5db788044
,08-31 11:16:54.283  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=87bc5f1a-3391-4e15-92a3-2da5db788044, clientIf=6
08-31 11:16:54.283  7231  7244 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 11:16:54.283  3218  3233 D BtGatt.GattService: start scan with filters
,08-31 11:16:54.283  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:16:54.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:16:54.283  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:54.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:16:54.283  3218  3356 D BtGatt.ScanManager: handling starting scan
,08-31 11:16:54.283  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:54.283  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:16:54.283  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.283  3218  3356 D BtGatt.ScanManager: allow scan with filters
08-31 11:16:54.293  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:16:54.293  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:16:54.293  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:16:54.293  3218  3356 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 11:16:54.293  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:16:54.293  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.293  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:16:54.293  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:16:54.293  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:16:54.303  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:16:54.303  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.303  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:16:54.303  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.303  7231  7286 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:16:54.313  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:16:54.313  7231  7286 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:16:54.313  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.313  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:16:54.313  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.313  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:16:54.313  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:16:54.313  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:54.313  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:16:54.313  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:16:54.313  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:16:54.313  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:16:54.323  3218  3229 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:16:54.323  3218  3356 D BtGatt.ScanManager: filter size is 1
,08-31 11:16:54.323  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 11:16:54.323  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:16:54.323  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:16:54.323  3218  3354 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:16:54.323  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:16:54.323  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:16:54.323  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:16:54.323  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:54.323  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:16:54.333  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:16:54.333  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:16:54.333  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.333  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:54.333  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.333  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.333  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:54.333  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.333  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:54.333  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.333  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:54.333  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.333  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.333  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.333  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.333  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.333  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.333  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.333  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:16:54.333  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:16:54.333  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:16:54.333  7231  7286 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:16:54.343  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:54.343  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:16:54.343  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.343  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.343  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:54.353  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:16:54.353  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.353  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:54.353  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:54.353  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:54.353  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:54.353  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:54.353  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:16:54.363  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:16:54.363  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:16:54.363  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:16:54.363  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:16:54.373  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:16:54.373  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:16:54.373  3218  3233 D BtGatt.GattService: registerClient() - UUID=0bf6ce6c-6d70-4e80-a1b7-aee55b73386a
,08-31 11:16:54.413  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=0bf6ce6c-6d70-4e80-a1b7-aee55b73386a, clientIf=6
,08-31 11:16:54.413  7231  7242 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:16:54.413  3218  3378 D BtGatt.GattService: start scan with filters
,08-31 11:16:54.413  3218  3356 D BtGatt.ScanManager: handling starting scan
,08-31 11:16:54.423  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:16:54.423  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:16:54.423  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:16:54.423  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:16:54.423  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:16:54.423  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:16:54.423  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:16:54.423  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:16:54.423  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:16:54.423  3218  3356 D BtGatt.ScanManager: allow scan with filters
,08-31 11:16:54.423  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:16:54.423  3218  3356 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 11:16:54.433  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:16:54.433  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:16:54.433  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.433  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:16:54.433  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:16:54.433  7231  7286 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:16:54.433  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:16:54.433  7231  7286 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:16:54.433  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.433  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:16:54.433  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.433  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:16:54.433  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:16:54.433  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:16:54.433  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:16:54.433  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:16:54.443  3218  3233 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:16:54.443  3218  3378 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:54.443  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.443  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.443  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:54.443  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.443  7231  7286 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:16:54.443  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.443  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.443  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:54.443  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list,
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.443  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.443  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.443  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.443  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.443  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:16:54.443  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.443  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:16:54.443  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.453  7231  7286 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:16:54.453  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.453  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.453  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 11:16:54.453  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.453  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.453  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 11:16:54.453  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.453  7231  7286 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
,08-31 11:16:54.453  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-31 11:16:54.453  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.453  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.453  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.453  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.453  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.453  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:54.463  3218  3356 D BtGatt.ScanManager: filter size is 1
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.463  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 5
08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.463  7231  7286 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:16:54.463  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.463  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.463  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.463  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.463  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:16:54.463  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.463  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.463  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:16:54.463  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:16:54.463  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:16:54.463  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:16:54.463  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:16:54.463  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:16:54.463  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:16:54.463  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:16:54.463  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.463  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.463  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.463  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:54.463  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.463  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.463  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.463  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.473  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:54.473  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.473  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.473  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.473  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:16:54.473  7231  7286 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:16:54.473  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:16:54.473  7231  7286 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:16:54.473  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:16:54.473  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:16:54.473  7231  7286 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:16:54.473  7231  7286 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:16:54.473  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 11:16:54.473  7231  7286 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:16:54.473  7231  7286 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:16:54.473  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:16:54.473  7231  7286 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:16:54.473  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:16:54.483  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:16:54.483  7231  7286 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:16:54.483  7231  7286 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:16:54.483  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.483  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.483  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 11:16:54.483  7231  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1439)
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.483  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.483  7231  7286 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-31 11:16:54.483  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.483  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.483  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.483  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.483  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.483  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.483  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.483  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1439
,08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString,
08-31 11:16:54.493  7231  7286 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:16:54.493  7231  7286 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection,
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-31 11:16:54.493  7231  7286 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:16:54.493  7231  7286 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.493  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.493  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.493  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.493  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.493  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.493  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.493  7231  7294 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:16:54.503  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:16:54.503  7231  7294 D BluetoothSocket: connect(): myUserId = 0
,08-31 11:16:54.503  7231  7294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:16:54.503  7231  7231 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:16:54.503  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.503  7231  7231 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:16:54.503  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:16:54.503  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.503  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.503  7231  7296 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:16:54.503  7231  7296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:54.503  3218  3378 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:16:54.513  7231  7296 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.513  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.513  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.513  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:16:54.513  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.513  7231  7296 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.513  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7296 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:16:54.513  7231  7294 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,08-31 11:16:54.513  7231  7296 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14480b55
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.513  7231  7286 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-31 11:16:54.513  7231  7286 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:16:54.513  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:16:54.513  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.513  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.513  7231  7296 D BluetoothSocket: channel: 6
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.513  7231  7296 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2edee96a, channel: 6, state: LISTENING
08-31 11:16:54.513  7231  7296 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2edee96a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14480b55, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1203de5bmSocket: android.net.LocalSocket@2ec796f8 impl:android.net.LocalSocketImpl@36cb07d1 fd:FileDescriptor[106]
08-31 11:16:54.513  7231  7296 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ec796f8 impl:android.net.LocalSocketImpl@36cb07d1 fd:FileDescriptor[106]
08-31 11:16:54.513  7231  7296 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:16:54.513  7231  7296 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-31 11:16:54.513  7231  7296 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:16:54.513  7231  7231 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 11:16:54.513  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.513  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.513  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.513  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.513  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.513  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.513  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.523  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
,08-31 11:16:54.523  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:54.523  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:54.523  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:54.523  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.523  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.523  7231  7286 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14839dba not in the list
08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.523  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:54.523  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.523  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:54.523  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:54.523  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:54.523  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:54.523  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5046b not in the list
08-31 11:16:54.523  7231  7286 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:16:54.523  7231  7286 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:16:54.523  7231  7286 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:16:54.523  7231  7286 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:16:54.523  7231  7286 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:16:54.523  7231  7286 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:16:54.523  7231  7286 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:16:54.523  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:54.523  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7a3236 added. We now have 2 listener(s)
,08-31 11:16:54.523  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:54.523  7231  7286 D BluetoothAdapter: enable()
,08-31 11:16:54.533  7231  7286 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 11:16:54.533  1017  1506 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:16:54.533  1017  1506 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:16:54.533  1017  1506 D SecContentProvider2: mCursor = null
,08-31 11:16:54.533  1017  1506 D WifiService: setWifiEnabled: true pid=7231, uid=10170
,08-31 11:16:54.533  1017  1506 W ActivityManager: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:16:54.543  1017  1506 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:16:54.543  1017  1506 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:16:54.543  1017  1506 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:16:54.543  1017  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:16:54.543  1017  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:16:54.543  1017  1506 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:16:54.543  1017  1506 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:16:54.543  1017  1506 D SettingsProvider: name = wifi_on
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4180537 added. We now have 3 listener(s)
08-31 11:16:54.543  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5b2aa4 added. We now have 4 listener(s)
,08-31 11:16:54.543  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:54.543  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa7500d added. We now have 5 listener(s)
,08-31 11:16:54.553  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:54.553  1017  1547 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:16:54.553  1017  1547 D WifiService: setWifiEnabled: false pid=7231, uid=10170
08-31 11:16:54.553  1017  1547 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:16:54.553  1017  1547 D SecContentProvider2: mCursor = null
08-31 11:16:54.553  1017  1547 D SettingsProvider: name = wifi_on
,08-31 11:16:54.563  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 11:16:54.563  7231  7286 D BluetoothAdapter: disable()
08-31 11:16:54.563  1357  1357 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:16:54.563  1357  1357 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 11:16:54.563  1357  1357 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-31 11:16:54.563  1357  1357 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:16:54.573  1017  1548 D SettingsProvider: name = bluetooth_on
08-31 11:16:54.573  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:16:54.573  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:54.573  3218  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 11:16:54.573  3218  3290 D BluetoothAdapterProperties: Setting state to 13
08-31 11:16:54.573  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:16:54.573  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:16:54.573  3218  3290 D BluetoothAdapterService: updateAdapterState state is 13
08-31 11:16:54.573  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.573  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.573  1017  3801 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:16:54.573  1017  3801 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,08-31 11:16:54.583  1017  3801 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.583  1017  3801 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.583  1017  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:16:54.583  3218  3218 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 11:16:54.583  3218  3290 D BluetoothAdapterService: Autoconnection is available 
08-31 11:16:54.583  1017  3751 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 11:16:54.583  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 11:16:54.583  3218  3290 D BluetoothAdapterService: terminating service from this receiver
08-31 11:16:54.583  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.583  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.583  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:16:54.583  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.583  1017  3751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.583  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.583  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fa58627, channel: 19, state: LISTENING
08-31 11:16:54.583  3218  3290 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:16:54.583  3218  3290 D BluetoothAdapterProperties: mDiscovering is false,
08-31 11:16:54.583  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fa58627, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a51563c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@318430d4mSocket: android.net.LocalSocket@3421927d impl:android.net.LocalSocketImpl@369ba572 fd:FileDescriptor[82]
08-31 11:16:54.583  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3421927d impl:android.net.LocalSocketImpl@369ba572 fd:FileDescriptor[82]
08-31 11:16:54.583  1017  1496 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 11:16:54.583  3218  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:16:54.583  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.583  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:54.593  1357  1357 I wpa_supplicant: Scan aborted because the firmware maybe busy.
,08-31 11:16:54.593  1357  1357 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-31 11:16:54.593  1357  1357 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-31 11:16:54.593  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 11:16:54.593  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.593  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:54.593  4788  4788 D BluetoothPbap: Proxy object disconnected
,08-31 11:16:54.593  4788  4788 D PbapServerProfile: Bluetooth service disconnected
,08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:54.603  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:16:54.603  3218  3293 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:54.603  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:16:54.603  3218  3290 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 11:16:54.603  3218  3290 E bt-btif : cmd socket is not created
08-31 11:16:54.603  3218  5273 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:54.603  3218  3294 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 11:16:54.603  7231  7294 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7ddbdd3, channel: -1, state: INIT,
08-31 11:16:54.603  3218  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:16:54.603  7231  7294 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7ddbdd3, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d724d10, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3785e009mSocket: android.net.LocalSocket@3e39520e impl:android.net.LocalSocketImpl@3a3c642f fd:FileDescriptor[107]
08-31 11:16:54.603  7231  7294 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e39520e impl:android.net.LocalSocketImpl@3a3c642f fd:FileDescriptor[107]
08-31 11:16:54.603  7231  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1439)
,08-31 11:16:54.603  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:54.603  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.613  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:16:54.613  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:16:54.613  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.613  3218  3294 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-31 11:16:54.613  3218  3294 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
,08-31 11:16:54.613  3218  3294 W bt-btif : invalid rfc slot id: 4
,08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:54.623  3218  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:16:54.633  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:54.633  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-31 11:16:54.633  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:16:54.633  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:16:54.643  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:16:54.643  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:54.643  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 11:16:54.643  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-31 11:16:54.643  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:16:54.643  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:16:54.643  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:16:54.643  1998  1998 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:16:54.643  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@315d8640, channel: 5, state: LISTENING
08-31 11:16:54.643  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@315d8640, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1213c02f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1939d979mSocket: android.net.LocalSocket@a7aa6be impl:android.net.LocalSocketImpl@9fb131f fd:FileDescriptor[80]
08-31 11:16:54.643  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a7aa6be impl:android.net.LocalSocketImpl@9fb131f fd:FileDescriptor[80]
,08-31 11:16:54.643  1017  1449 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:16:54.643  1017  1548 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:16:54.643  3218  3218 I BtOppRfcommListener: stopping Accept Thread
08-31 11:16:54.653  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28b4c66c, channel: 12, state: LISTENING
08-31 11:16:54.653  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28b4c66c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f1a60e6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@cf59435mSocket: android.net.LocalSocket@2db670ca impl:android.net.LocalSocketImpl@1347c23b fd:FileDescriptor[87]
08-31 11:16:54.653  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2db670ca impl:android.net.LocalSocketImpl@1347c23b fd:FileDescriptor[87]
,08-31 11:16:54.653  3218  5273 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:16:54.653  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:54.653  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:16:54.653  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.663  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:54.663   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:16:54.663  1698  2525 V NativeCrypto: Read error: ssl=0xb8108020: I/O error during system call, Connection timed out
,08-31 11:16:54.673  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 11:16:54.673  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:16:54.673  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.673  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:16:54.673  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.673  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:16:54.673  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:16:54.673  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:16:54.673  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:16:54.673  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-31 11:16:54.683  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:16:54.693  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
,08-31 11:16:54.693  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 11:16:54.703  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1,
08-31 11:16:54.703  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:54.703  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 11:16:54.703  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-31 11:16:54.703  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:16:54.703  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:16:54.713  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:54.713  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:16:54.713  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.713  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.713  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:16:54.713  1017  1125 D WifiP2pService: P2pDisablingState
,08-31 11:16:54.723  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:16:54.723  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:16:54.723  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-31 11:16:54.723  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-31 11:16:54.723  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:16:54.723  1017  1125 D WifiP2pService: p2p socket connection lost
08-31 11:16:54.723  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:16:54.723  1017  1048 D WifiDisplayController: disconnect
08-31 11:16:54.723  1017  1048 D WifiDisplayController: updateConnection
08-31 11:16:54.723  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:16:54.723  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:16:54.723  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 11:16:54.723  1017  1125 D WifiP2pService: P2pDisabledState
,08-31 11:16:54.723  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 11:16:54.723  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:16:54.723  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:16:54.723  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:16:54.733  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 11:16:54.733  1017  1496 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:16:54.733  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:16:54.753  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 11:16:54.753  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:16:54.763  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.763  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.763   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:16:54.773  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.773  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 11:16:54.773  1017  1128 V NetworkStats: updateIfacesLocked(),
08-31 11:16:54.773  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:16:54.773  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:16:54.773  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:16:54.773  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:16:54.773  1017  1128 V NetworkStats: performPollLocked() took 5ms
,08-31 11:16:54.773  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:54.773  1357  1357 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:16:54.783  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-31 11:16:54.783  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:16:54.783  1178  1663 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:16:54.783  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.783  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:16:54.783  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
,08-31 11:16:54.783  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:54.783  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} },
08-31 11:16:54.783  1466  1466 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:16:54.783  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-31 11:16:54.783  1466  1466 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:54.783  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:16:54.793  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:16:54.793  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:16:54.793  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.793  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:54.793  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.793  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:54.793  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 11:16:54.793  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:16:54.793  1178  1178 D HotspotTile: onReceive : 0, 0
,08-31 11:16:54.803  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 11:16:54.803  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 11:16:54.803  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-31 11:16:54.803  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-19ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:16:54.803  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:54.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:54.803  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:54.803  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.803  1017  1123 V NetworkStats: updateIfacesLocked()
08-31 11:16:54.803  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:16:54.803  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:54.803  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:16:54.803  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:16:54.813  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:16:54.813  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:16:54.813  3218  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:16:54.813  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:16:54.813  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:16:54.813  3218  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 11:16:54.813  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-31 11:16:54.813  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-31 11:16:54.813  3218  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-31 11:16:54.813  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:16:54.813  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:16:54.823  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:16:54.823  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 11:16:54.823  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:16:54.823  1017  1123 V NetworkStats: performPollLocked() took 19ms
,08-31 11:16:54.823  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 11:16:54.823  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:54.823  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:54.823  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:16:54.833  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:54.833  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:16:54.833  1017  1264 I art     : Explicit concurrent mark sweep GC freed 57664(3MB) AllocSpace objects, 33(528KB) LOS objects, 33% free, 23MB/35MB, paused 8.110ms total 197.287ms
,08-31 11:16:54.843  1017  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:16:54.843  1698  2525 V NativeCrypto: SSL shutdown failed: ssl=0xb8108020: I/O error during system call, Broken pipe
08-31 11:16:54.843  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:16:54.843  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:16:54.843  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.843  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.843  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.843  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 11:16:54.843  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:16:54.843  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 11:16:54.843  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:16:54.843  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:16:54.843  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:16:54.843  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:16:54.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.843  1017  1449 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:16:54.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.843  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 11:16:54.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:54.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:16:54.843  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:16:54.843  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:16:54.843  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:16:54.853  1017  1449 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:16:54.853  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.853  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 11:16:54.853  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 11:16:54.853  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:54.853  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:54.853  3218  3218 V BluetoothOppManager: cleanUp...
08-31 11:16:54.853  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:16:54.853  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:16:54.853  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.853  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.853  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.853  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-31 11:16:54.853  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:54.853  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:16:54.853  3218  3218 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:16:54.853  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:16:54.863  1017  3816 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:16:54.863  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:54.863  1017  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:16:54.863  1017  3816 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.863  1017  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.863  1017  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.863  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.863  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:16:54.863  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 11:16:54.873  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:16:54.873  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:16:54.873  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:16:54.873  4788  4788 D DockEventReceiver: finishStartingService: stopping service
08-31 11:16:54.873  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 11:16:54.873  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.873  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.873  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:16:54.873  3218  3218 D A2dpService: Received stop request...Stopping profile...
,08-31 11:16:54.873  3218  3360 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:16:54.873  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:16:54.873  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 11:16:54.873  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:16:54.883  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:16:54.883  1017  1264 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:16:54.883  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:16:54.883  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.883  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.883  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.883  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.883  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.883  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.883  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:16:54.893  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-31 11:16:54.893  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:16:54.893  1017  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:16:54.893  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:16:54.893  4788  4788 D HeadsetProfile: Bluetooth service disconnected
08-31 11:16:54.893  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.893  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
08-31 11:16:54.893  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.893  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:16:54.893  4788  4788 D BluetoothA2dp: Proxy object disconnected
08-31 11:16:54.893  4788  4788 D A2dpProfile: Bluetooth service disconnected
,08-31 11:16:54.893  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:16:54.893  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:16:54.893  3218  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:16:54.893  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:16:54.893  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:16:54.903  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:54.903  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:54.903  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:16:54.903  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:16:54.903  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:16:54.903  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:16:54.903  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 11:16:54.903  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 11:16:54.903  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-31 11:16:54.903  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 11:16:54.903  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:16:54.903  3218  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-31 11:16:54.903  3218  3218 D HidService: Received stop request...Stopping profile...
,08-31 11:16:54.903  3218  3218 D HidService: Stopping Bluetooth HidService
,08-31 11:16:54.913  3218  3218 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:16:54.913  3218  3218 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:16:54.913  3218  3218 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:16:54.913  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.913  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:54.913  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:16:54.923  4788  4788 D BluetoothInputDevice: Proxy object disconnected
,08-31 11:16:54.923  4788  4788 D HidProfile: Bluetooth service disconnected
,08-31 11:16:54.923  1357  1357 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 11:16:54.923  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 11:16:54.923  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 11:16:54.923  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:16:54.923  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:16:54.923  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:54.923  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:54.923  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:54.923  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:54.933  7307  7307 E Zygote  : MountEmulatedStorage(),
08-31 11:16:54.933  7307  7307 I libpersona: KNOX_SDCARD checking this for 10055
08-31 11:16:54.933  7307  7307 E Zygote  : v2
,08-31 11:16:54.933  7307  7307 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:54.933  7307  7307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:54.943  1017  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7307 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 11:16:54.943  7307  7307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:16:54.943  7307  7307 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:54.943  3218  3218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:16:54.943  3218  3218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
08-31 11:16:54.943  1357  1357 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 11:16:54.943  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:54.943  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:16:54.943  1017  1131 D Tethering: InitialState.processMessage what=4
,08-31 11:16:54.943  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:16:54.943  3218  3218 D HealthService: Received stop request...Stopping profile...
08-31 11:16:54.943  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:16:54.943  1017  1131 E Tethering: No numeric data
08-31 11:16:54.953  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:16:54.953  1357  1357 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 11:16:54.953  1357  1357 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 11:16:54.953  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:54.953  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:16:54.953  1357  1357 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:16:54.953  1357  1357 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:16:54.953  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:54.953  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:16:54.953  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:16:54.953  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:16:54.953  1017  1131 D Tethering: clearTetheredNotification()
,08-31 11:16:54.953  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.953  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:16:54.953  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:16:54.953  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:16:54.953  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:54.953  3218  3218 D PanService: Received stop request...Stopping profile...
08-31 11:16:54.953  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.953  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 11:16:54.963  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.963  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 11:16:54.963  4788  4788 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:16:54.963  4788  4788 D PanProfile: Bluetooth service disconnected
08-31 11:16:54.963  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 11:16:54.963  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:16:54.963  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:16:54.963  3218  3218 D BluetoothA2dp: Proxy object disconnected
08-31 11:16:54.963  3218  3218 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 11:16:54.963  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:16:54.963  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.963  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:54.963  3218  3361 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:16:54.963  3218  3218 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:16:54.963  3218  3218 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 11:16:54.963  3218  3218 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 11:16:54.963  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.963  4788  4788 D BluetoothMap: Proxy object disconnected
08-31 11:16:54.963  4788  4788 D MapProfile: Bluetooth service disconnected
,08-31 11:16:54.963  3218  3218 D SapService: Received stop request...Stopping profile...
08-31 11:16:54.963  3218  3218 D SapService: Stopping Bluetooth SapService
08-31 11:16:54.963  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:16:54.973  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:16:54.973  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:16:54.973  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:16:54.973  3218  3218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:16:54.973  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:16:54.973  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:16:54.973  3218  3218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:16:54.973  3218  3218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 11:16:54.973  4788  4788 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:16:54.973  4788  4788 D SapProfile: Bluetooth service disconnected
,08-31 11:16:54.973  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:16:54.973  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 11:16:54.973  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 11:16:54.973  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:16:54.973  3218  3218 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 11:16:54.973  3218  3218 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 11:16:54.973  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:16:54.973  3218  3290 D BluetoothAdapterProperties: Setting state to 10
08-31 11:16:54.973  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:16:54.973  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:16:54.973  3218  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 11:16:54.973  3218  3290 D BluetoothAdapterService: Autoconnection is available 
08-31 11:16:54.973  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 11:16:54.973  3218  3290 I BluetoothAdapterState: Entering OffState
08-31 11:16:54.973  4788  4796 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:16:54.973  4788  7321 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:54.973  4788  7321 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:16:54.983  4788  4796 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:16:54.983  7307  7307 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:16:54.983  7231  7244 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:54.983  7231  7244 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:54.983  7231  7244 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 11:16:54.983  7231  7244 D BluetoothLeAdvertiser: Exit stop advertising
08-31 11:16:54.983  7231  7244 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 11:16:54.983  7231  7244 D BluetoothLeScanner: Exiting stopAllScan
,08-31 11:16:54.983  7307  7307 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:54.983  1698  1728 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:16:54.983  1698  1728 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:54.983  4788  4799 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:16:54.983  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:54.983  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:16:55.003  4788  4799 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 11:16:55.003  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.003  4788  4799 D Bluetoothsap: Unbinding service...
,08-31 11:16:55.003  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.003  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.003  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:16:55.003  1466  1686 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:55.003  1466  1686 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:16:55.003  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:16:55.013  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:16:55.013  1178  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:16:55.013  7231  7231 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 11:16:55.013  1178  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:55.013  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:16:55.013  3218  3354 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:16:55.013  1438  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:55.013  1438  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:55.013  4788  7321 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:16:55.013  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:16:55.013  1691  1709 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:55.013  1691  1709 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:55.013  3218  3378 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:55.013  3218  3378 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:16:55.013  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:16:55.013  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:16:55.013  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:16:55.013  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.013  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:55.013  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-31 11:16:55.013  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:16:55.013  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:16:55.023  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:16:55.023  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.023  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.023  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:55.023  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:16:55.023  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-31 11:16:55.023  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.023  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.023  1998  1998 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:16:55.023  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:55.023  7307  7307 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:16:55.033  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.033  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.033  1017  1544 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:16:55.033  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.033  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:16:55.033  1017  1547 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:16:55.033  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:16:55.033  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:16:55.033  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.033  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:55.033  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:55.043  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.043  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:55.043  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.043  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-31 11:16:55.043  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.043  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.043  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:16:55.043  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:16:55.043  1017  3358 D SSRM:n  : SIOP:: AP = 320
08-31 11:16:55.053  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.053  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-31 11:16:55.053  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:16:55.063  7307  7307 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-31 11:16:55.063  7307  7307 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 11:16:55.063  7307  7307 D UserAnalysis: Create SecureDbHelper
,08-31 11:16:55.063  7307  7307 D IntelligenceServiceApplication: onCreate(),
,08-31 11:16:55.073  1017  1264 I ActivityManager: Killing 6835:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-31 11:16:55.083  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-31 11:16:55.083  7307  7307 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:16:55.083  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.083  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.083  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.083  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.093  7338  7338 E Zygote  : MountEmulatedStorage()
,08-31 11:16:55.093  1017  1488 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7338 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 11:16:55.093  7338  7338 E Zygote  : v2
08-31 11:16:55.093  7338  7338 I libpersona: KNOX_SDCARD checking this for 10105
08-31 11:16:55.093  7338  7338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:55.093  7338  7338 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:55.093  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 11:16:55.093  7338  7338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:16:55.093  7307  7307 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:16:55.093  7338  7338 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:16:55.103  7307  7307 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-31 11:16:55.113  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:16:55.113  7338  7338 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:55.123  7338  7338 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:55.173  1357  1357 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:16:55.183  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:55.183  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:16:55.183  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:16:55.253   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:16:55.253   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:55.253  7338  7356 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:16:55.263   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:16:55.263   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:55.263  7338  7356 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:16:55.283  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 11:16:55.283  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:16:55.303  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:16:55.303  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:55.303  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:55.303  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:55.303  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 11:16:55.313  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:55.313  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:16:55.313  1178  1178 D HotspotTile: onReceive : 1, 0
,08-31 11:16:55.313  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:55.323  1691  2174 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:55.323  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:55.323  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:55.323  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-31 11:16:55.333  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:55.333  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:55.343  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  7338  7338 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:16:55.443  7338  7338 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:16:55.443  1017  3801 I ActivityManager: Killing 6851:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-31 11:16:55.463  1017  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:16:55.463  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:16:55.463  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:55.463  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:55.463  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:16:55.463  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:16:55.463  1609  1609 I Hs20UtilService: Starting #8
08-31 11:16:55.463  1609  1643 I Hs20UtilService: Message received 5007
08-31 11:16:55.473  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:16:55.473  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:16:55.473  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:16:55.473  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:16:55.473  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:16:55.473  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:16:55.483  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:16:55.483  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:16:55.493  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:16:55.493  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:16:55.493  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:16:55.493  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:16:55.493  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 11:16:55.493  1017  1548 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-31 11:16:55.493  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.493  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.493  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.493  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.503  7368  7368 E Zygote  : MountEmulatedStorage()
08-31 11:16:55.503  7368  7368 E Zygote  : v2
08-31 11:16:55.503  7368  7368 I libpersona: KNOX_SDCARD checking this for 10064
08-31 11:16:55.503  7368  7368 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:55.503  7368  7368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:55.503  7338  7357 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 11:16:55.513  7368  7368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:16:55.513  1017  1548 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7368 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:16:55.513  7368  7368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:55.523  1017  3751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:16:55.523  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:55.533  1017  3751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:16:55.533  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:16:55.543  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:55.543  7368  7368 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:55.553  7368  7368 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 11:16:55.563  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:16:55.573  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 11:16:55.593  7368  7368 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:16:55.603  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 11:16:55.603  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.603  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.603  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.603  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.613  7386  7386 E Zygote  : MountEmulatedStorage()
08-31 11:16:55.613  1017  1136 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7386 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:16:55.613  7386  7386 E Zygote  : v2
08-31 11:16:55.613  7386  7386 I libpersona: KNOX_SDCARD checking this for 10065
08-31 11:16:55.613  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:55.613  7386  7386 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:55.613  1017  1136 I ActivityManager: Killing 6876:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-31 11:16:55.613  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:55.623  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:55.633  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 11:16:55.633  7386  7386 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:55.653  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:16:55.653  1017  1496 I ActivityManager: Killing 6898:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 11:16:55.663  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:16:55.663  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:16:55.663  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:55.663  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:55.663  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:16:55.663  1609  1609 I Hs20UtilService: Starting #9
,08-31 11:16:55.663  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:16:55.663  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:16:55.663  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:16:55.663  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:16:55.663  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:16:55.663  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:16:55.663  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:16:55.673  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:16:55.673  1017  1547 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:16:55.673  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:16:55.673  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:55.673  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:55.673  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:16:55.673  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-31 11:16:55.683  1609  1609 I Hs20UtilService: Starting #10
08-31 11:16:55.683  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:16:55.683  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.683  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:55.683  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.683  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.693  7401  7401 E Zygote  : MountEmulatedStorage(),
,08-31 11:16:55.693  7401  7401 E Zygote  : v2,
08-31 11:16:55.693  1017  1029 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:16:55.693  7401  7401 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:16:55.693  7401  7401 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:55.693  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:55.703  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:55.703  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:55.723  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:55.723  7401  7401 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:55.753  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:16:55.753  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:16:55.753  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 11:16:55.763  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:16:55.763  1017  3751 I ActivityManager: Killing 6813:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 11:16:55.773  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:55.773  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:16:55.773  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:55.773  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:55.773  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:16:55.773  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:55.783  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:55.783  1017  1017 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:16:55.783  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:16:55.783  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 11:16:55.783  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.783  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.783  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.783  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:55.803  7417  7417 E Zygote  : MountEmulatedStorage()
,08-31 11:16:55.803  7417  7417 I libpersona: KNOX_SDCARD checking this for 10102
08-31 11:16:55.803  7417  7417 E Zygote  : v2
08-31 11:16:55.803  7417  7417 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:55.803  7417  7417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:55.813  7417  7417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:55.813  7417  7417 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:16:55.823  1017  1017 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7417 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 11:16:55.853   305   305 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 969us total 38.363ms
08-31 11:16:55.853  7417  7417 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:55.853  1017  1045 D Tethering: interfaceRemoved wlan0,
08-31 11:16:55.853  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:16:55.853  7417  7417 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:55.883   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 26.160ms
,08-31 11:16:55.883  7417  7417 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:16:55.903   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 19.867ms
,08-31 11:16:56.053  1017  1045 D Tethering: interfaceRemoved p2p0
,08-31 11:16:56.053  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:16:56.073  7417  7437 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 11:16:56.073  7417  7437 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 11:16:56.073  7417  7437 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 11:16:56.073  7417  7437 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 11:16:56.083  7417  7437 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 11:16:56.083  7417  7437 I Babel_SMS: MmsConfig.loadFromResources
,08-31 11:16:56.083  7417  7437 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 11:16:56.083  7417  7437 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 11:16:56.113  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 11:16:56.113  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 11:16:56.113  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.113  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:56.113  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:16:56.133  7417  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:56.133  7417  7417 I Babel_Crash: startup - clean
,08-31 11:16:56.163  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.163  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.163  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.173  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.173  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.173  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.173  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.173  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.173  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.183  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.183  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.183  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.183  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.193  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.193  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.193  7417  7417 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:56.193  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.193  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.193  7417  7417 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.193  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.203  7417  7417 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:16:56.203  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.203  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.203  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.203  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:16:56.203  7417  7417 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 11:16:56.203  7417  7417 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 11:16:56.213  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:16:56.213  1017  1547 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:16:56.213  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:16:56.213  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:56.213  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.213  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:16:56.213  7417  7417 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 11:16:56.213  7417  7417 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 11:16:56.213  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:16:56.213  7417  7417 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:16:56.223  4788  4788 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:56.223  7417  7417 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:16:56.223  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:16:56.223  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:56.223  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:16:56.233  7417  7417 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 11:16:56.233  7417  7417 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:16:56.243  7417  7417 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 11:16:56.243  1017  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:16:56.243  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:16:56.243  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.243  7417  7417 W VideoCapabilities: Unsupported mime video/wvc1
08-31 11:16:56.243  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:16:56.243  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:16:56.253  7417  7417 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 11:16:56.253  1609  1609 I Hs20UtilService: Starting #11
08-31 11:16:56.253  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:16:56.253  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:16:56.253  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:16:56.253  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:16:56.253  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:16:56.253  7417  7417 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 11:16:56.253  7417  7417 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 11:16:56.263  7417  7417 W VideoCapabilities: Unsupported mime video/mp43
,08-31 11:16:56.263  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:16:56.263  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.263  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.263  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.263  7417  7417 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 11:16:56.263  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.273  7417  7417 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 11:16:56.273  7442  7442 E Zygote  : MountEmulatedStorage(),
,08-31 11:16:56.273  7442  7442 E Zygote  : v2
,08-31 11:16:56.273  7442  7442 I libpersona: KNOX_SDCARD checking this for 1000,
08-31 11:16:56.273  7442  7442 I libpersona: KNOX_SDCARD not a persona,
,08-31 11:16:56.283  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:56.283  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:56.283  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:16:56.283  1017  1546 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:16:56.293  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:56.293  7442  7442 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:56.303  7417  7417 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:16:56.323  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 11:16:56.323  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-31 11:16:56.323  7442  7442 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:16:56.323  7417  7417 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:56.323  7417  7417 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:56.333  7417  7417 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:56.333  7417  7417 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:56.333  1017  1449 I ActivityManager: Killing 6998:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-31 11:16:56.343  7442  7442 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 11:16:56.343  7442  7442 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 11:16:56.343  7442  7442 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 11:16:56.343  7442  7442 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:56.343  7417  7417 I vclib   : onServiceConnected
,08-31 11:16:56.343  1017  1136 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-31 11:16:56.343  1017  1136 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-31 11:16:56.343  1017  1136 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 11:16:56.343  1017  1136 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-31 11:16:56.343  1017  1136 I ActivityManager: Killing 7015:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-31 11:16:56.353  7442  7458 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 11:16:56.353  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 11:16:56.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.363  7460  7460 E Zygote  : MountEmulatedStorage()
08-31 11:16:56.363  7460  7460 E Zygote  : v2
,08-31 11:16:56.373  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7460 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:16:56.373  7460  7460 I libpersona: KNOX_SDCARD checking this for 10001
08-31 11:16:56.373  7460  7460 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:56.373  7460  7460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:56.373  7460  7460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:16:56.373  7460  7460 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:56.383  7460  7460 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:56.383  7460  7460 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:56.463  1017  3816 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 11:16:56.463  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.463  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.463  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.463  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.463   288   288 E SMD     : DCD OFF,
,08-31 11:16:56.473  7477  7477 E Zygote  : MountEmulatedStorage(),
08-31 11:16:56.473  1017  3816 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:16:56.473  7477  7477 E Zygote  : v2
08-31 11:16:56.473  7477  7477 I libpersona: KNOX_SDCARD checking this for 1000
,08-31 11:16:56.473  7477  7477 I libpersona: KNOX_SDCARD not a persona,
08-31 11:16:56.483  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:56.483  1017  3816 I ActivityManager: Killing 7034:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-31 11:16:56.483  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:56.483  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:56.513  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:16:56.513  7477  7477 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:56.553  7477  7477 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 11:16:56.623  1017  1096 V AlarmManager: waitForAlarm result :4
,08-31 11:16:56.633  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-31 11:16:56.633  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-31 11:16:56.633  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-31 11:16:56.633  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 11:16:56.633  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 11:16:56.643  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 11:16:56.643  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 11:16:56.643  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:16:56.643  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-31 11:16:56.643  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 11:16:56.663  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:16:56.663  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:16:56.683  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:16:56.683  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-31 11:16:56.693  7477  7477 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 11:16:56.693  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:16:56.703  7477  7477 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 11:16:56.703  7477  7477 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:56.703  7477  7477 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 11:16:56.703  7477  7477 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-31 11:16:56.703  7477  7477 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 11:16:56.713  1017  3816 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 11:16:56.713  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.713  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.713  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.713  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.723  7494  7494 E Zygote  : MountEmulatedStorage(),
08-31 11:16:56.723  7494  7494 E Zygote  : v2
08-31 11:16:56.723  7494  7494 I libpersona: KNOX_SDCARD checking this for 10008
08-31 11:16:56.723  7494  7494 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:56.723  7494  7494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:56.733  1017  3816 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7494 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 11:16:56.733  1017  3816 I ActivityManager: Killing 7057:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-31 11:16:56.733  7494  7494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:56.733  7494  7494 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 11:16:56.753  7494  7494 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:56.753  7494  7494 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:56.793  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 11:16:56.823  1017  1546 I ActivityManager: Killing 6955:com.android.mms/u0a41 (adj 15): empty #21
,08-31 11:16:56.833  1017  1547 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:16:56.833  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 11:16:56.833  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.833  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:56.833  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:16:56.853  1876  1876 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:16:56.853  1876  2792 I iu.UploadsManager: num queued entries: 0
08-31 11:16:56.853  1876  2792 I iu.UploadsManager: num updated entries: 0
,08-31 11:16:56.863  1876  2792 I iu.SyncManager: NEXT; no task
,08-31 11:16:56.863  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:16:56.863  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-31 11:16:56.863  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.863  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:16:56.863  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:16:56.873  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:16:56.873  1876  1876 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-31 11:16:56.873  2796  2796 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 11:16:56 GMT+02:00 2016
,08-31 11:16:56.873  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 11:16:56.873  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:16:56.873  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:56.873  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:56.873  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:16:56.883  2796  2796 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 11:16:56.883  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 11:16:56.893  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.893  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.893  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.893  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.893  2796  2796 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 11:16:56.903  7511  7511 E Zygote  : MountEmulatedStorage(),
08-31 11:16:56.903  7511  7511 E Zygote  : v2
08-31 11:16:56.903  7511  7511 I libpersona: KNOX_SDCARD checking this for 10031
,08-31 11:16:56.903  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:56.903  7511  7511 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:56.903  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:16:56.903  1017  1136 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7511 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-31 11:16:56.903  2796  2796 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 11:16:56.903  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:16:56.903  2796  2796 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 11:16:56.913  2796  7510 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 11:16:56.913  1017  1030 D CountryDetector: No listener is left
,08-31 11:16:56.923  2796  7510 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION,
08-31 11:16:56.923  2796  7510 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 11:16:56.923  2796  7510 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 11:16:56.923  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:56.923  7511  7511 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:56.923  2796  2796 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 11:16:56.953  7511  7511 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 11:16:56.953  1017  1030 I ActivityManager: Killing 7079:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-31 11:16:56.973  1017  3816 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 11:16:56.973  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.973  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:56.973  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.973  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:56.973  2734  7526 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-31 11:16:56.983  2734  7526 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 11:16:56.983  2734  7526 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 11:16:56.983  2734  7526 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 11:16:56.983  2734  7526 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,08-31 11:16:56.983  1017  3816 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7527 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:16:56.993  7527  7527 E Zygote  : MountEmulatedStorage()
08-31 11:16:56.993  7527  7527 E Zygote  : v2
08-31 11:16:56.993  7527  7527 I libpersona: KNOX_SDCARD checking this for 10032
,08-31 11:16:56.993  7527  7527 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:56.993  7527  7527 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:56.993  7527  7527 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:56.993  7527  7527 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:16:57.013  7527  7527 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:57.013  7527  7527 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:57.063  7527  7542 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-31 11:16:57.063  7527  7542 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 11:16:57.063  7527  7527 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 11:16:57.073  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 11:16:57.073  7527  7542 D SPPClientService: PushLog.txt file is not deleted.
08-31 11:16:57.073  7527  7542 D SPPClientService: PushLog.txt file is not deleted.
08-31 11:16:57.073  7527  7542 D SPPClientService: ============PushLog. stop!
,08-31 11:16:57.073  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.073  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:57.073  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:57.073  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.093  7544  7544 E Zygote  : MountEmulatedStorage()
,08-31 11:16:57.093  7544  7544 E Zygote  : v2
08-31 11:16:57.093  7544  7544 I libpersona: KNOX_SDCARD checking this for 10036
08-31 11:16:57.093  7544  7544 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:57.093  7544  7544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:57.093  1017  1029 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7544 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 11:16:57.093  1017  1029 I ActivityManager: Killing 7090:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 11:16:57.093  7544  7544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:16:57.093  1017  1506 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-31 11:16:57.093  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-31 11:16:57.093  7544  7544 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-31 11:16:57.103  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:57.103  1017  1506 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 11:16:57.103  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 11:16:57.123  7544  7544 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:57.123  7544  7544 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:57.133  7527  7552 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 11:16:57.163  7544  7544 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@29d3cd7c
,08-31 11:16:57.183  7544  7544 I SA      : [SSP] onCreated
,08-31 11:16:57.193  7544  7544 I SA      : [TPM] There is no property file
,08-31 11:16:57.193  7544  7544 I SA      : [SCU] isHaveSA() - false
,08-31 11:16:57.193  7544  7544 I SA      : [TPM] getModelProperty : null
,08-31 11:16:57.193  7544  7544 I SA      : [TPM] getCSCProperty : null
,08-31 11:16:57.203  7544  7544 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-31 11:16:57.203  7544  7544 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 11:16:57.203  7544  7544 I SA      : [DM] TFT FEATURE: false
,08-31 11:16:57.203  7544  7544 I SA      : [DM] init START
,08-31 11:16:57.203  7544  7544 I SA      : [DM] This device is not a Vodafone
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 11:16:57.213  7544  7544 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 11:16:57.213  7544  7544 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75),
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-31 11:16:57.223  7544  7544 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 11:16:57.233  7544  7544 I SA      : [SCU] isHaveSA() - false
,08-31 11:16:57.233  7544  7544 I SA      : support phone number id : false
08-31 11:16:57.233  7544  7544 I SA      : [DM] Supports Ref Jpn : true
,08-31 11:16:57.233  7544  7544 I SA      : [DM] init END
08-31 11:16:57.233  7544  7544 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 11:16:57.233  7544  7544 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
08-31 11:16:57.233  7544  7544 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 11:16:57.233  7544  7544 I SA      : [SLFUCHKMGR] constructor called,
,08-31 11:16:57.243  7544  7544 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 11:16:57.243  7544  7544 I SA      : [OR] == isSIMCardReady false ==
,08-31 11:16:57.243  7544  7544 I SA      : [SCU] == networkStateCheck == false
08-31 11:16:57.243  7544  7544 I SA      : [OR] onReceive END
,08-31 11:16:57.243  1017  1264 I ActivityManager: Killing 7112:com.wsomacp/u0a23 (adj 15): empty #21
,08-31 11:16:57.253  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:57.253  1828  1828 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:16:57.263  2667  2672 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-31 11:16:57.263  1828  1828 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-31 11:16:57.263  1828  1828 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 11:16:57.263  1828  1828 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-31 11:16:57.263  1828  1828 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 11:16:57.273  1828  1828 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:16:57.273  1828  1828 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 11:16:57.273  1017  3801 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 11:16:57.273  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.273  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.273  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.273  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.293  7566  7566 E Zygote  : MountEmulatedStorage()
,08-31 11:16:57.293  7566  7566 E Zygote  : v2
08-31 11:16:57.293  7566  7566 I libpersona: KNOX_SDCARD checking this for 10077
,08-31 11:16:57.293  7566  7566 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:57.293  7566  7566 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:57.293  1017  3801 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7566 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 11:16:57.293  7566  7566 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:16:57.293  7566  7566 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-31 11:16:57.313  7566  7566 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 11:16:57.313  7566  7566 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:57.463  1017  3751 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-31 11:16:57.463  1017  3751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 11:16:57.463  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:57.463  1017  3751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:57.463  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:16:57.473  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast,
,08-31 11:16:57.473  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:57.473  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:57.473  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:57.473  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:57.493  1017  1029 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7584 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:16:57.493  1017  1547 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-31 11:16:57.493  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 11:16:57.493  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:57.493  7584  7584 I libpersona: KNOX_SDCARD checking this for 10110
,08-31 11:16:57.493  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:57.493  7584  7584 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:57.493  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-31 11:16:57.493  7584  7584 E Zygote  : MountEmulatedStorage()
,08-31 11:16:57.493  7584  7584 E Zygote  : v2
,08-31 11:16:57.493  7584  7584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:57.503  7417  7583 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-31 11:16:57.503  7584  7584 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:57.503  7584  7584 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:16:57.513  1017  1136 I ActivityManager: Killing 7148:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-31 11:16:57.523  7584  7584 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:57.523  7584  7584 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:57.583  1017  3751 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:16:57.583  1017  3751 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:16:57.583  1017  3751 D SecContentProvider2: mCursor = null
,08-31 11:16:57.583  1017  3751 D WifiService: setWifiEnabled: true pid=7231, uid=10170
,08-31 11:16:57.583  1017  3751 W ActivityManager: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:16:57.593  1017  3751 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:16:57.593  1017  3751 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:16:57.593  1017  3751 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:16:57.593  1017  3751 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:16:57.593  1017  3751 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:16:57.593  1017  3751 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:16:57.593  1017  3751 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:16:57.593  1017  3751 D SettingsProvider: name = wifi_on
,08-31 11:16:57.603  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:16:57.643  1017  1506 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:16:57.653  1017  1096 V AlarmManager: waitForAlarm result :4,
,08-31 11:16:57.793   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:16:57.793   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:57.793  7584  7603 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:16:57.793   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:16:57.793   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:57.793  7584  7603 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:16:57.813   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:16:57.813   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:57.813  7584  7604 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:16:57.813   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:16:57.813   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:16:57.813  7584  7604 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:16:57.833  7584  7584 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:16:57.833  7584  7584 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:16:57.833  7584  7584 I GAv4    :   adb logcat -s GAv4
,08-31 11:16:57.863  7584  7584 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:57.863  1017  1136 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:16:57.873  7584  7584 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:57.893  7584  7612 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:16:57.983  1017  1045 D Tethering: interfaceAdded wlan0
,08-31 11:16:57.993  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:57.993  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:16:57.993  1017  1131 E Tethering: No numeric data
08-31 11:16:57.993  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:16:57.993  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:16:57.993  1017  1131 D Tethering: clearTetheredNotification()
08-31 11:16:57.993  1017  1131 D Tethering: InitialState.processMessage what=4
,08-31 11:16:57.993  1017  1131 E Tethering: No numeric data,
,08-31 11:16:58.003  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:16:58.003  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:58.003  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:16:58.003  1017  1045 D Tethering: interfaceAdded p2p0,
,08-31 11:16:58.003  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:58.003  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
08-31 11:16:58.003  1178  1178 D HotspotTile: updateTetherState():false, false
08-31 11:16:58.003  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:16:58.003  1017  1123 V NetworkStats: performPollLocked() took 7ms
08-31 11:16:58.003  1017  1131 D Tethering: clearTetheredNotification()
08-31 11:16:58.003  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:16:58.003  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:58.003   278   982 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 11:16:58.013   278   982 D SoftapController: Softap fwReload - Ok
08-31 11:16:58.013  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:16:58.013  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:58.013  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:16:58.013  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 11:16:58.013  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:16:58.013  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:58.013  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:16:58.013   278   982 D CommandListener: Setting iface cfg
08-31 11:16:58.013   278   982 D CommandListener: Trying to bring down wlan0
,08-31 11:16:58.013  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:58.013  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:16:58.013  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:16:58.013  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:16:58.013   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:16:58.013  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 11:16:58.013  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:58.013  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:58.013  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:16:58.023  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-31 11:16:58.023  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:16:58.023  1017  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:16:58.033  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:58.033  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:58.033  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:58.033  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:58.033  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 11:16:58.033  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:16:58.033  1178  1178 D HotspotTile: onReceive : 2, 0
,08-31 11:16:58.033  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:58.033  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:58.043  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:58.083  7615  7615 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 11:16:58.083  7615  7615 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:16:58.083  7615  7615 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:16:58.103  7615  7615 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 11:16:58.103   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7615,
,08-31 11:16:58.103   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 11:16:58.103  7615  7615 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 11:16:58.103  7615  7615 I wpa_supplicant: ssSupport state is = 1
08-31 11:16:58.103  7615  7615 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 11:16:58.103  7615  7615 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 11:16:58.103   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7615
08-31 11:16:58.103   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-31 11:16:58.183  1017  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:16:58.183  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:58.183  1017  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:58.183  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 11:16:58.213  7584  7584 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 11:16:58.233  7584  7584 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4737-4739)
08-31 11:16:58.233  7584  7584 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:16:58.243  7584  7584 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fa58627},
08-31 11:16:58.243  7584  7584 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 11:16:58.243  7584  7584 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:16:58.263  7584  7584 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 11:16:58.263  7584  7584 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:16:58.273  7584  7584 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:16:58.283  7584  7584 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:16:58.283  7584  7584 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:16:58.283  7584  7584 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:16:58.283  7584  7584 I Adreno-EGL: Local Branch: 
08-31 11:16:58.283  7584  7584 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:16:58.283  7584  7584 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:16:58.283  7584  7584 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:16:58.303   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-31 11:16:58.303  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-31 11:16:58.343  7584  7584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:16:58.353  7584  7643 W cr.media: Requires BLUETOOTH permission
,08-31 11:16:58.353  7584  7584 I NSApplication: Starting up...
,08-31 11:16:58.353  1017  1546 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:16:58.353  7615  7615 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:16:58.353  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:16:58.363  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 11:16:58.363   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7615
08-31 11:16:58.363   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:16:58.363  1017  3801 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-31 11:16:58.363  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:16:58.363  7615  7615 I wpa_supplicant: ssSupport state is = 1
,08-31 11:16:58.363  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:16:58.373  7615  7615 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 11:16:58.373  7615  7615 E wpa_supplicant: SIM READ ERROR,
08-31 11:16:58.373  1017  1548 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-31 11:16:58.373  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 11:16:58.373  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.373  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:58.373  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.373  1017  1548 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:58.373  7615  7615 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:16:58.373  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:16:58.373  7615  7615 E wpa_supplicant: SIM READ ERROR
08-31 11:16:58.373  7615  7615 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:16:58.373  7615  7615 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:16:58.373  7615  7615 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:16:58.373  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:16:58.373  7615  7615 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 11:16:58.373  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:16:58.373  7615  7615 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:16:58.373  7615  7615 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:16:58.373  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:16:58.373  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:16:58.383  7649  7649 E Zygote  : MountEmulatedStorage()
,08-31 11:16:58.383  7649  7649 E Zygote  : v2
08-31 11:16:58.383  7649  7649 I libpersona: KNOX_SDCARD checking this for 10117
08-31 11:16:58.383  7649  7649 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:58.383  1017  1548 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7649 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:16:58.393  1017  1548 I ActivityManager: Killing 6749:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-31 11:16:58.393  7649  7649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:58.393  7649  7649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:58.393  7649  7649 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:16:58.413  7649  7649 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:58.413  7649  7649 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:58.433  7649  7649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:16:58.463  7615  7615 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 11:16:58.593  7615  7615 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:16:58.593  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:16:58.603  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 11:16:58.613   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7615
08-31 11:16:58.613   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:16:58.613  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:16:58.613  7615  7615 I wpa_supplicant: ssSupport state is = 1
,08-31 11:16:58.613  7615  7615 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 11:16:58.613  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:16:58.623  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 11:16:58.623   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7615
08-31 11:16:58.623   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 11:16:58.623  7615  7615 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:16:58.623  7615  7615 I wpa_supplicant: ssSupport state is = 1
08-31 11:16:58.623  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:16:58.623  7615  7615 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:16:58.623  7615  7615 E wpa_supplicant: SIM READ ERROR
08-31 11:16:58.623  7615  7615 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:16:58.623  7615  7615 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:16:58.623  7615  7615 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:16:58.623  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:16:58.623  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:16:58.623  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:16:58.633  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:16:58.633  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:16:58.633  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:16:58.763  1017  3801 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 11:16:58.773  7615  7615 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 11:16:58.773  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:16:58.773  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.773  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:58.773  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.773  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:58.783  7672  7672 E Zygote  : MountEmulatedStorage(),
08-31 11:16:58.783  7672  7672 E Zygote  : v2
,08-31 11:16:58.783  7672  7672 I libpersona: KNOX_SDCARD checking this for 10121
08-31 11:16:58.783  7672  7672 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:58.793  7672  7672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:58.793  7672  7672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:58.793  7672  7672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:16:58.793  1017  3801 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7672 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-31 11:16:58.793  1017  3801 I ActivityManager: Killing 7168:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-31 11:16:58.823   305   305 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.646ms total 25.526ms
,08-31 11:16:58.823  7672  7672 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:58.823  7672  7672 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:58.833   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.729ms
08-31 11:16:58.833  7672  7672 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:58.833  7672  7672 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 11:16:58.843  7672  7672 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:16:58.853  7672  7672 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:58.853  7672  7672 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 11:16:58.853   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.425ms
,08-31 11:16:58.853  7672  7672 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 11:16:58.853  1017  1547 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-31 11:16:58.863  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.863  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.863  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:58.863  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:58.873  1017  1547 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7689 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 11:16:58.873  7689  7689 E Zygote  : MountEmulatedStorage()
08-31 11:16:58.873  7689  7689 I libpersona: KNOX_SDCARD checking this for 10141
08-31 11:16:58.873  7689  7689 E Zygote  : v2
08-31 11:16:58.873  7689  7689 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:58.873  7689  7689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:58.873  1017  1547 I ActivityManager: Killing 7127:com.android.defcontainer/u0a3 (adj 15): empty #21
08-31 11:16:58.873  7615  7615 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-31 11:16:58.873  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 11:16:58.873  7615  7615 I wpa_supplicant: Skip scan - bUseNetwork false
08-31 11:16:58.873  7689  7689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:16:58.873  7689  7689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:16:58.893  7689  7689 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:58.893  7689  7689 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:58.913  7689  7689 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-31 11:16:58.913  7689  7689 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:58.913  7689  7689 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:16:58.913  7689  7689 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 11:16:58.963  1017  3816 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:58.973  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:58.993  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 11:16:58.993  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:16:58.993  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:16:59.003  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:59.013  1017  1548 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:59.023  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 11:16:59.033  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:16:59.033  7615  7615 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 11:16:59.033  7615  7615 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:16:59.033  7615  7615 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:16:59.033  7615  7615 E wpa_supplicant: SIM READ ERROR
08-31 11:16:59.033  7615  7615 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:16:59.053  7615  7615 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 11:16:59.063  1017  3816 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 11:16:59.063  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.063  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 11:16:59.073  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:59.073  1017  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.073  7615  7615 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:16:59.073  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:59.073  1017  3801 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:59.083  7713  7713 E Zygote  : MountEmulatedStorage()
08-31 11:16:59.083  7713  7713 E Zygote  : v2
08-31 11:16:59.083  7713  7713 I libpersona: KNOX_SDCARD checking this for 10068
08-31 11:16:59.083  7713  7713 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:59.083  7713  7713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:16:59.083  7713  7713 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:59.083  7713  7713 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-31 11:16:59.093  1017  3816 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7713 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-31 11:16:59.093  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:16:59.103  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:16:59.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:59.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:16:59.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:59.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 11:16:59.113  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:59.113  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:16:59.113  1178  1178 D HotspotTile: onReceive : 3, 0
08-31 11:16:59.113  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:59.113  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:59.113  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:59.113  1017  1126 E WifiConfigStore: Not a HS20
,08-31 11:16:59.113  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:59.113  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:59.123  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:59.123  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:59.123  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 11:16:59.123  7713  7713 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:59.123  7713  7713 D ActivityThread: Added TimaKeyStore provider
08-31 11:16:59.123  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:16:59.123  7615  7615 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:16:59.123  7615  7615 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:16:59.123  7615  7615 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:16:59.123  7615  7615 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:16:59.123  7615  7615 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 11:16:59.123  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:16:59.123  7615  7615 I wpa_supplicant: First Scan Start
08-31 11:16:59.123  7615  7615 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:16:59.133  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-31 11:16:59.133  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:16:59.133  1017  1126 I WifiNative-HAL: startHal
08-31 11:16:59.133  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ed7188c
08-31 11:16:59.133  1017  1126 I WifiNative-HAL: Could not start hal
,08-31 11:16:59.133  7417  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:59.133  1017  1136 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:16:59.133  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 11:16:59.133  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 11:16:59.133  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 11:16:59.143   278   982 D CommandListener: Setting iface cfg,
08-31 11:16:59.143   278   982 D CommandListener: Trying to bring up p2p0
,08-31 11:16:59.143  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.143  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:16:59.143  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.143  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:59.143  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.143  1017  1125 D WifiP2pService: P2pEnablingState
,08-31 11:16:59.143  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 11:16:59.143  1017  1125 D WifiP2pService: P2p socket connection successful
08-31 11:16:59.143  1017  1125 D WifiP2pService: P2pEnabledState
,08-31 11:16:59.153  7730  7730 E Zygote  : MountEmulatedStorage()
08-31 11:16:59.153  7730  7730 I libpersona: KNOX_SDCARD checking this for 10009
08-31 11:16:59.153  7730  7730 E Zygote  : v2
08-31 11:16:59.153  7730  7730 I libpersona: KNOX_SDCARD not a persona
08-31 11:16:59.153  1017  1488 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7730 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-31 11:16:59.153  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:16:59.153  1017  1488 I ActivityManager: Killing 6204:com.samsung.android.sm/1000 (adj 15): empty #21
,08-31 11:16:59.153  1017  1488 I ActivityManager: Killing 6938:com.android.vending/u0a26 (adj 15): empty #22
08-31 11:16:59.153  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:59.153  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:16:59.153  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:16:59.163  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:16:59.163  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:16:59.163  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 11:16:59.163  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:16:59.163  1017  1048 D WifiDisplayController: disconnect
08-31 11:16:59.163  1017  1048 D WifiDisplayController: updateConnection
08-31 11:16:59.163  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:16:59.163  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 11:16:59.163  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:16:59.163  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:16:59.163  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:16:59.163  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-31 11:16:59.163  7615  7615 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:16:59.173  7615  7615 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:16:59.173  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3,
08-31 11:16:59.173  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:59.173  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:16:59.173  1017  1151 I WifiNative-HAL: startHal
08-31 11:16:59.173  1017  3801 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:16:59.173  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dc339bc
08-31 11:16:59.173  1017  1151 I WifiNative-HAL: Could not start hal
08-31 11:16:59.173  1017  1151 E WifiScanningService: could not start HAL
08-31 11:16:59.173  7615  7615 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 11:16:59.173  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,08-31 11:16:59.173  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:16:59.173  1017  1126 D SecContentProvider2: mCursor = null
08-31 11:16:59.173  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 11:16:59.173  7713  7713 D BadgeProvider: onCreate
,08-31 11:16:59.173  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:59.173  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:16:59.173  7713  7713 D BadgeProvider: DatabaseHelper
08-31 11:16:59.173  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:16:59.173  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:16:59.193  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 11:16:59.193  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-31 11:16:59.193  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-31 11:16:59.203  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:59.203  7730  7730 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:59.213  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 11:16:59.213  1017  1125 D WifiP2pService: InactiveState
08-31 11:16:59.213  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:16:59.213  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:16:59.213  7615  7615 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:16:59.213  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 11:16:59.213  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:16:59.273  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:16:59.273  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:16:59.273  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:16:59.273  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:16:59.273  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  secondary type: null
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  wps: 0
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  grpcapab: 0
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  devcapab: 0
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  status: 3
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  wfdInfo: null
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-31 11:16:59.273  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-31 11:16:59.373  1017  1544 I art     : Explicit concurrent mark sweep GC freed 52786(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.408ms total 160.902ms
,08-31 11:16:59.373  7713  7722 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 11:16:59.383  7713  7722 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 11:16:59.383  7713  7722 D BadgeProvider: sendNotify, [notify] : null
08-31 11:16:59.383  7713  7722 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 11:16:59.383  7713  7722 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 11:16:59.383  7713  7722 D BadgeProvider: update, [UpdateCount] : 1
,08-31 11:16:59.383  1489  1489 D Launcher.Model: reloadBadges entered.
,08-31 11:16:59.413  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 11:16:59.413  1017  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 11:16:59.413  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 11:16:59.423  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 11:16:59.433  1017  3751 I ActivityManager: Killing 7368:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-31 11:16:59.463  1017  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:16:59.463  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:16:59.463  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:59.463  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:16:59.463  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:16:59.463   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:16:59.463   278   978 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-31 11:16:59.463  1609  1609 I Hs20UtilService: Starting #12
,08-31 11:16:59.463   288   288 E SMD     : DCD OFF
,08-31 11:16:59.463  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:16:59.473  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:16:59.473  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:16:59.473  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:16:59.473  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:16:59.483  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:16:59.483  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:16:59.483  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:16:59.483  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:16:59.483  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:16:59.483  1609  1609 I Hs20UtilService: Starting #13
,08-31 11:16:59.493  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:16:59.493  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:16:59.493  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:16:59.493  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:16:59.493  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:16:59.493  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:16:59.493  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:16:59.493  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-31 11:16:59.493  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:16:59.493  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:16:59.493  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:16:59.503  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:16:59.503  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:16:59.503  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:16:59.503  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:16:59.503  1017  3801 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 11:16:59.503  1017  3801 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-31 11:16:59.503  1017  3801 W BroadcastQueue: android.os.TransactionTooLargeException
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-31 11:16:59.503  1017  3801 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:16:59.503  1017  3801 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 11:16:59.513  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.513  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:59.513  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:16:59.513  1017  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:16:59.523  7750  7750 E Zygote  : MountEmulatedStorage()
08-31 11:16:59.523  1017  3801 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7750 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:16:59.523  7750  7750 E Zygote  : v2
08-31 11:16:59.523  7750  7750 I libpersona: KNOX_SDCARD checking this for 10064
08-31 11:16:59.523  7750  7750 I libpersona: KNOX_SDCARD not a persona
,08-31 11:16:59.523  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:16:59.533  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:16:59.533  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:16:59.543  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:16:59.543  7750  7750 D ActivityThread: Added TimaKeyStore provider
,08-31 11:16:59.563  7750  7750 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 11:16:59.573  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:16:59.573  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 11:16:59.603  7750  7750 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:16:59.603  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:16:59.613  1017  3816 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:16:59.613  1017  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:16:59.613  1017  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:16:59.613  1017  1496 I ActivityManager: Killing 7307:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 11:16:59.643  1017  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7368/cgroup.procs: No such file or directory
,08-31 11:16:59.803  1017  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 11:16:59.803  1017  1547 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:16:59.803  1017  1547 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:16:59.803  1017  1547 D BatteryService: stay LED for charging
08-31 11:16:59.803  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:16:59.803  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-31 11:16:59.803  1017  1017 I MotionRecognitionService: Plugged
08-31 11:16:59.803  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 11:16:59.803  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-31 11:16:59.803  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:16:59.803  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:16:59.833  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:16:59.833  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:16:59.833  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:16:59.833  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 11:16:59.833  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-31 11:16:59.993  1017  1096 V AlarmManager: waitForAlarm result :8
,08-31 11:17:00.293  7615  7615 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-31 11:17:00.303  7615  7615 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 11:17:00.303  1017  7709 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:17:00.303  7615  7615 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 11:17:00.303  7615  7615 I wpa_supplicant: Trying to associate with  'G700',
08-31 11:17:00.303  7615  7615 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-31 11:17:00.303  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 11:17:00.323  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:00.323  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:00.433  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:00.433  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:17:00.433  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:00.433  7615  7615 E wpa_supplicant: Cmd 35605 not handled,
08-31 11:17:00.433  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:00.433  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 11:17:00.433  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:00.433  7615  7615 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:17:00.433  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 11:17:00.433  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:17:00.433  7615  7615 I wpa_supplicant: Associated with F4.99.3E
08-31 11:17:00.433  7615  7615 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:17:00.433  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-31 11:17:00.433  7615  7615 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-31 11:17:00.433  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 11:17:00.433  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:17:00.433  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:17:00.433  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true,
,08-31 11:17:00.433  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:17:00.443  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:00.433  1017  1131 E Tethering: No numeric data
08-31 11:17:00.443  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 11:17:00.443  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:17:00.443  1178  1178 D HotspotTile: updateTetherState():false, false
08-31 11:17:00.443  1017  1131 D Tethering: clearTetheredNotification()
08-31 11:17:00.443  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:00.443  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:00.443  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:17:00.443  7615  7615 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:17:00.443  7615  7615 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 11:17:00.443  7615  7615 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-31 11:17:00.453  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:17:00.453  7615  7615 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-31 11:17:00.453  7615  7615 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-31 11:17:00.453  1017  1123 V NetworkStats: performPollLocked() took 10ms
08-31 11:17:00.453  7615  7615 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 11:17:00.453  7615  7615 I wpa_supplicant: Blacklist: Clear (temp) 
,08-31 11:17:00.453  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 11:17:00.453  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:00.453  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:00.453  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:00.453  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:00.453  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:17:00.453  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:17:00.453  1017  1126 D SecContentProvider2: mCursor = null
08-31 11:17:00.453  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:17:00.463  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 11:17:00.463  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 11:17:00.473  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:17:00.473  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:17:00.473  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:00.473  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:00.483  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.483  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:17:00.483  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:17:00.483  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-31 11:17:00.483  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:17:00.483  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:00.483  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:00.483  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:00.493  1609  1609 I Hs20UtilService: Starting #14
08-31 11:17:00.493  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:00.493  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:17:00.493  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:00.493  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:17:00.503  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:17:00.503  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:17:00.503  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 11:17:00.503  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:17:00.503  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-31 11:17:00.513   278   982 D CommandListener: Setting iface cfg
,08-31 11:17:00.523  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2,
,08-31 11:17:00.523  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:00.523  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:00.533  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 11:17:00.533  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:00.543  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.543  1017  1126 E WifiNative-wlan0: do suspend false
,08-31 11:17:00.543  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:17:00.543  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:17:00.543  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:00.543  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:00.603  1017  3801 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:17:00.603  1017  3801 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:17:00.603  1017  3801 D SecContentProvider2: mCursor = null
,08-31 11:17:00.603  1017  3801 D WifiService: setWifiEnabled: false pid=7231, uid=10170
,08-31 11:17:00.603  1017  3801 D SettingsProvider: name = wifi_on
,08-31 11:17:00.613  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:17:00.633  1017  1126 E WifiNative-wlan0: do suspend true,
,08-31 11:17:00.653  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
,08-31 11:17:00.653  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:17:00.663   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:00.663  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.663  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:00.663  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:17:00.663  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-31 11:17:00.663   278   982 E Netd    : no such netId 503
,08-31 11:17:00.673  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:17:00.683  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-31 11:17:00.683  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-31 11:17:00.683  1017  1128 V NetworkStats: updateIfacesLocked()
,08-31 11:17:00.683  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:17:00.683  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:00.683  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:17:00.683  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:00.693  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
,08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:00.693  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:17:00.693  1017  1128 V NetworkStats: performPollLocked() took 9ms
08-31 11:17:00.693  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:00.693  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:17:00.693  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
,08-31 11:17:00.693  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:17:00.693  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 11:17:00.693  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-31 11:17:00.693  1017  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.693  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.693  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 11:17:00.693  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:00.693  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:17:00.693  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:00.693  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:00.703  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:00.703  1609  1609 I Hs20UtilService: Starting #15
,08-31 11:17:00.703  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:00.703  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-31 11:17:00.703  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:17:00.703  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-31 11:17:00.703  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:17:00.703  1017  7767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-31 11:17:00.703  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-31 11:17:00.703  1017  7767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:17:00.703  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:17:00.703  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:17:00.703  1017  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 11:17:00.703  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 11:17:00.703  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:00.713  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:00.713  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:00.713  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-31 11:17:00.713  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:17:00.713  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:17:00.713  1017  1125 D WifiP2pService: P2pDisablingState
,08-31 11:17:00.713  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:17:00.713  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 11:17:00.713  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:00.713  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:17:00.713  1017  1048 D WifiDisplayController: disconnect
,08-31 11:17:00.713  1017  1048 D WifiDisplayController: updateConnection
08-31 11:17:00.723  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:17:00.713  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:17:00.713  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:17:00.713  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:17:00.723  1017  1125 D WifiP2pService: p2p socket connection lost
,08-31 11:17:00.723  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:17:00.723  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:17:00.723  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:17:00.723  1017  1126 E WifiNative-wlan0: do suspend true
08-31 11:17:00.723  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:17:00.723  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:17:00.723  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:17:00.723  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:17:00.723  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 11:17:00.723  1017  1125 D WifiP2pService: P2pDisabledState
,08-31 11:17:00.733  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:17:00.733  1017  1264 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:17:00.733  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:17:00.743  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:17:00.743  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:00.743  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:17:00.743  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:17:00.743  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:17:00.743  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:17:00.743  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:17:00.743  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:17:00.753  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:17:00.753  7750  7750 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:17:00.753  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-31 11:17:00.753  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-31 11:17:00.763   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:17:00.763  7770  7770 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 11:17:00.763  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 11:17:00.763  7615  7615 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:17:00.773  7770  7770 I dhcpcd  : version 5.5.6 starting
,08-31 11:17:00.773  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:00.773  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,08-31 11:17:00.773  7770  7770 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.773  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:17:00.783  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:00.783  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:00.783  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.783  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.793  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:00.793  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:00.793  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:17:00.793  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:00.793  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:17:00.803  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.803  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:00.803  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.803  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:00.803  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:00.803  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 11:17:00.803  1017  1449 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:00.803  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:17:00.803  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:00.803  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:00.803  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:00.803  1178  1178 D HotspotTile: onReceive : 0, 0
08-31 11:17:00.803  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:17:00.803  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:00.803  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:17:00.813  1609  1609 I Hs20UtilService: Starting #16
08-31 11:17:00.813  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:17:00.813  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:00.813  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:00.813  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:17:00.813  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:00.813  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:17:00.813  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:00.813  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:00.823  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:17:00.823  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:00.823  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-31 11:17:00.823  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:17:00.823  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:17:00.823  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:17:00.833  1017  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:17:00.833  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:00.833  1017  1546 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:17:00.833  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:00.833  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:17:00.843  1609  1609 I Hs20UtilService: Starting #17
,08-31 11:17:00.843  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:17:00.843  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:17:00.843  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 11:17:00.843  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:17:00.843  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:17:00.853  7770  7770 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 11:17:00.853  7770  7770 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:17:00.853  7770  7770 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 11:17:00.853  7770  7770 I dhcpcd  : bssid match
,08-31 11:17:00.853  7770  7770 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,08-31 11:17:00.913  7770  7770 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-31 11:17:01.003  7615  7615 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:17:01.043  7770  7770 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-31 11:17:01.123  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:17:01.123  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:17:01.123  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:17:01.123  7615  7615 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:17:01.153  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.153  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:01.153  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.153  1017  1131 D Tethering: InitialState.processMessage what=4
08-31 11:17:01.153  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.153  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:01.153  1017  1131 E Tethering: No numeric data,
08-31 11:17:01.153  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.153  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:17:01.153  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:01.153  1017  1131 D Tethering: clearTetheredNotification()
08-31 11:17:01.153  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:17:01.153  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:01.153  1178  1178 D HotspotTile: updateTetherState():false, false
08-31 11:17:01.153  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:01.153  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:17:01.163  7615  7615 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-31 11:17:01.163  7615  7615 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-31 11:17:01.163  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 11:17:01.163  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:01.163  7615  7615 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 11:17:01.163  7615  7615 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:17:01.163  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.163  7615  7615 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:17:01.163  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:17:01.163  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:17:01.163  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:01.163  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:01.423  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:17:01.423  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:01.423  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:17:01.523  7615  7615 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:17:01.603  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:17:01.603  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:01.603  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:01.603  7615  7615 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 11:17:01.713  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-31 11:17:01.713  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:17:01.723  7417  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:01.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:01.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:01.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:01.723  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:01.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 11:17:01.733  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:17:01.733  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:17:01.733  1178  1178 D HotspotTile: onReceive : 1, 0
08-31 11:17:01.733  1691  2174 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:17:01.733  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:01.743  1017  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:17:01.743  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:17:01.743  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:01.743  1017  1496 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 11:17:01.743  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:01.743  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:01.743  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:17:01.743  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:17:01.743  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:17:01.743  1609  1609 I Hs20UtilService: Starting #18
08-31 11:17:01.743  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:17:01.753  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:17:02.443   278   976 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-31 11:17:02.443  1017  1045 D Tethering: interfaceRemoved wlan0
,08-31 11:17:02.443  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:17:02.463   288   288 E SMD     : DCD OFF,
,08-31 11:17:02.613  1017  1045 D Tethering: interfaceRemoved p2p0
,08-31 11:17:02.613  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:17:03.423  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 11:17:03.613  7231  7286 D BluetoothAdapter: enable()
,08-31 11:17:03.613  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:17:03.623  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 11:17:03.623  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:17:03.623  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:17:03.623  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:03.623  1017  1029 D SettingsProvider: name = bluetooth_on,
,08-31 11:17:03.623  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:03.623  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:03.633  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-31 11:17:03.633  3218  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 11:17:03.633  3218  3290 D BluetoothAdapterProperties: Setting state to 11
08-31 11:17:03.633  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:17:03.633  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:03.633  3218  3290 D BluetoothAdapterService: updateAdapterState state is 11
08-31 11:17:03.633  3218  3290 D BluetoothAdapterService: Autoconnection is available 
08-31 11:17:03.633  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-31 11:17:03.633  3218  3290 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:17:03.633  1017  1548 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 11:17:03.633  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:03.643  1017  1548 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:03.643  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
,08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:17:03.633  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:17:03.633  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 11:17:03.633  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.633  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.633  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:17:03.643  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-31 11:17:03.643  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:17:03.643  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 11:17:03.643  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.643  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.643  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.643  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:17:03.643  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 11:17:03.643  3218  3218 D HeadsetService: Received start request. Starting profile...
08-31 11:17:03.643  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 11:17:03.643  3218  3218 D HeadsetService: start()
08-31 11:17:03.643  3218  3218 D HeadsetStateMachine: make
,08-31 11:17:03.643  1017  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.643  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.653  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.653  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.653  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.653  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:17:03.653  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:17:03.653  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:17:03.653  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:03.653  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 11:17:03.653  3218  3218 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 11:17:03.673  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:17:03.673  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:03.673  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-31 11:17:03.673  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null,
,08-31 11:17:03.673  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
,08-31 11:17:03.673  1017  1547 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:03.673  1998  1998 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:03.683  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:17:03.683  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:03.683  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:17:03.683  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:17:03.683  1017  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.683  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.683  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.683  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.683  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.683  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:03.683  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:17:03.683  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.683  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:17:03.683  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:17:03.683  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:17:03.683  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.683  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.683  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:17:03.693  1017  1548 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.693  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.693  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.693  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.693  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.693  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:17:03.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:03.693  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:03.693  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.703  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.693  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 11:17:03.703  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.703  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:17:03.703  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:17:03.703  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:17:03.703  1017  1547 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 11:17:03.703  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:17:03.703  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-31 11:17:03.703  3218  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:17:03.703  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.703  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.703  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:17:03.703  3218  3218 I bluedroid: get_profile_interface handsfree
08-31 11:17:03.703  1017  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.703  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.703  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.703  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.703  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:03.713  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:03.713  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:17:03.713  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:17:03.713  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:17:03.713  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:17:03.713  3218  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 11:17:03.713  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:03.723  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:03.723  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:17:03.723  3218  3218 E DualScoManager: Dual Sco Manager already instantiated
08-31 11:17:03.723  3218  3218 I DualScoManager: Set HeadsetServiceHelper
08-31 11:17:03.723  3218  3218 D BluetoothAtMessage: createCMTIContentObservers
08-31 11:17:03.723  1017  3816 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 11:17:03.723  1017  3816 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:17:03.723  1017  3816 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:17:03.723  1017  3816 D SettingsProvider: selectionArgs: false
08-31 11:17:03.723  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-31 11:17:03.723  1017  3816 D SettingsProvider: selectionArgs: 1002
,08-31 11:17:03.723  1017  3816 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:17:03.723  1017  3816 D SettingsProvider: ret = -1,
08-31 11:17:03.723  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:03.723  3218  7799 D HeadsetStateMachine: Enter Disconnected: -2
08-31 11:17:03.723  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:03.733  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:03.733  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:03.743  7800  7800 E Zygote  : MountEmulatedStorage(),
08-31 11:17:03.743  7800  7800 E Zygote  : v2
08-31 11:17:03.743  7800  7800 I libpersona: KNOX_SDCARD checking this for 10055
08-31 11:17:03.743  7800  7800 I libpersona: KNOX_SDCARD not a persona
,08-31 11:17:03.743  1017  1136 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7800 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 11:17:03.743  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:17:03.743  3218  3218 D HeadsetService: mStartError = false
08-31 11:17:03.743  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:03.753  3218  3218 D A2dpService: Received start request. Starting profile...
08-31 11:17:03.753  3218  3218 D A2dpService: start()
08-31 11:17:03.753  3218  3218 I bluedroid: get_profile_interface avrcp
,08-31 11:17:03.753  3218  7799 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 11:17:03.753  3218  7799 D HeadsetStateMachine: map size, before remove : 0
08-31 11:17:03.753  3218  7799 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:17:03.753  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:17:03.753  3218  3218 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:17:03.753  3218  3218 D Avrcp   : Initialize Media Controller
08-31 11:17:03.753  3218  3218 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-31 11:17:03.753  3218  3218 E Avrcp   : getActiveSessions
08-31 11:17:03.753  3218  3218 D Avrcp   : pick active media Controller
08-31 11:17:03.753  3218  3218 D Avrcp   : Get the active Media Controller 
,08-31 11:17:03.753  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:17:03.763  3218  3218 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 11:17:03.763  3218  3218 D A2dpStateMachine: make
08-31 11:17:03.763  3218  7806 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 11:17:03.763  3218  3218 I bluedroid: get_profile_interface a2dp
08-31 11:17:03.763  3218  7810 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:17:03.763  3218  3218 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:17:03.763  3218  3218 D A2dpService: mStartError = false
08-31 11:17:03.763  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:03.763  3218  3218 D HidService: Received start request. Starting profile...
08-31 11:17:03.763  3218  3218 D HidService: start()
08-31 11:17:03.763  3218  3218 I bluedroid: get_profile_interface hidhost
08-31 11:17:03.763  3218  3218 D HidService: setHidService(): set to: null
08-31 11:17:03.763  3218  3218 D HidService: mStartError = false
08-31 11:17:03.763  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:03.773  3218  7809 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:17:03.773  3218  3218 D HealthService: Received start request. Starting profile...
,08-31 11:17:03.773  3218  3218 D HealthService: start()
08-31 11:17:03.773  3218  3218 I bluedroid: get_profile_interface health
08-31 11:17:03.773  3218  3218 D HealthService: mStartError = false
08-31 11:17:03.773  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:03.773  3218  3218 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 11:17:03.773  1438  1448 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 11:17:03.773  1438  1438 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 11:17:03.773  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 11:17:03.773  1438  1448 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 11:17:03.783  3218  3218 D PanService: Received start request. Starting profile...
08-31 11:17:03.783  3218  3218 D PanService: start()
08-31 11:17:03.783  3218  3218 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:17:03.783  3218  3218 I bluedroid: get_profile_interface pan
08-31 11:17:03.783  3218  3218 D PanService: mStartError = false
08-31 11:17:03.783  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:03.783  3218  3218 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:17:03.783  3218  3218 D BluetoothMapService: start()
,08-31 11:17:03.783  3218  3218 D BluetoothMapService: mStartError = false
08-31 11:17:03.783  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:03.783  3218  3218 D HeadsetStateMachine: Proxy object connected
08-31 11:17:03.783  3218  3218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 11:17:03.783  3218  7799 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:17:03.783  3218  3218 D SapService: Received start request. Starting profile...
08-31 11:17:03.783  3218  3218 D SapService: start()
08-31 11:17:03.783  3218  3218 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:17:03.783  3218  3218 I bluedroid: get_profile_interface sap
08-31 11:17:03.783  3218  3218 D SapService: mStartError = false
08-31 11:17:03.783  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:03.783  3218  3218 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 11:17:03.783  3218  3218 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 11:17:03.783  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:17:03.783  3218  3218 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:17:03.783  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:17:03.783  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 11:17:03.783  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 11:17:03.783  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 11:17:03.783  3218  7799 D HeadsetStateMachine: Disconnected process message: 18
08-31 11:17:03.783  3218  7799 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:17:03.783  3218  7799 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:17:03.783  3218  7799 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:17:03.793  3218  7806 D BluetoothMediaBrowser: no now playing list
08-31 11:17:03.793  3218  7806 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 11:17:03.803  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 11:17:03.803  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:17:03.803  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:17:03.803  3218  3290 I bluedroid: enable
08-31 11:17:03.803  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:17:03.813  7800  7800 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:03.813  3218  3293 E bt-btif : BTM_SEC_REG[4  : sec: 0x3092, service name [] (up to 21 chars saved)
08-31 11:17:03.813  3218  3293 E bt-btif :                : sec: 0x80, service name [ion && *sectio, chan_id 2
08-31 11:17:03.813  3218  3293 E bt-btif : BTM_SEC_REG[5]: id 39, is_orig 1, psm 0x0017n && *section && key && *key && name && *name && bytes && type
08-31 11:17:03.813  3218  3293 E bt-btif : btif_storage_]: id 39, is_orig 0, psm 0x0017, proto_id 0
08-31 11:17:03.813  3218  3293 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 11:17:03.813  3218  3293 E BluetoothServiceJni: populateRssiValuesNative
08-31 11:17:03.813  3218  3293 I bluedroid: getModelRssiValues
08-31 11:17:03.813  3218  3293 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 11:17:03.813  3218  3293 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:17:03.823  3218  3293 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 11:17:03.823  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 11:17:03.823  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:17:03.823  3218  3293 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:17:03.823  3218  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:17:03.823  3218  3293 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-31 11:17:03.823  3218  3293 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-31 11:17:03.823  3218  3293 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-31 11:17:03.823  3218  3293 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 11:17:03.823  3218  3293 E bt-btif : JVenable fails
,08-31 11:17:03.823  3218  3293 D bte_conf: Device ID record 1 : primary
,08-31 11:17:03.823  3218  3293 D bte_conf:   vendorId            = 0075
08-31 11:17:03.823  3218  3293 D bte_conf:   vendorIdSource      = 0001
08-31 11:17:03.823  3218  3293 D bte_conf:   product             = 0100
,08-31 11:17:03.833  3218  3293 D bte_conf:   version             = 0200
08-31 11:17:03.833  3218  3293 D bte_conf:   clientExecutableURL = 
08-31 11:17:03.833  3218  3293 D bte_conf:   serviceDescription  = 
08-31 11:17:03.833  3218  3293 D bte_conf:   documentationURL    = 
,08-31 11:17:03.833  3218  3293 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:17:03.833  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:03.833  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:17:03.833  3218  3290 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:17:03.833  3218  3290 D BluetoothAdapterProperties: State =  11
08-31 11:17:03.833  1017  1264 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 11:17:03.843  3218  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:17:03.843  3218  3293 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:17:03.843  3218  3290 D BluetoothAdapterProperties: Setting state to 12
08-31 11:17:03.843  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:17:03.843  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:17:03.843  3218  3293 D BluetoothAdapterProperties: Scan Mode:21
,08-31 11:17:03.843  3218  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:17:03.843  1017  3816 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 11:17:03.843  1017  3816 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:17:03.843  1017  3816 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:17:03.843  1017  3816 D SettingsProvider: selectionArgs: false
08-31 11:17:03.843  1017  3816 D SettingsProvider: selectionArgs: 1002
08-31 11:17:03.843  1017  3816 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:17:03.843  1017  3816 D SettingsProvider: ret = -1
,08-31 11:17:03.843  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:03.843  3218  3290 D BluetoothAdapterService: updateAdapterState state is 12
08-31 11:17:03.843  1017  1548 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.843  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.843  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.843  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.843  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.853  4788  4799 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:17:03.853  3218  3290 D BluetoothAdapterService: Autoconnection is available 
08-31 11:17:03.853  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 11:17:03.853  3218  3290 D BluetoothAdapterService: starting service from this receiver
,08-31 11:17:03.853  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:03.853  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.853  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.853  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.853  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.853  3218  3290 I BluetoothAdapterState: Entering On State from state = 11
08-31 11:17:03.853  3218  3218 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 11:17:03.853  3218  3218 I BluetoothPbapService: Handler(): got msg=1
,08-31 11:17:03.863  1017  1264 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:03.863  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:03.863  7800  7800 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:17:03.863  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 11:17:03.863  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.863  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.863  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.863  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.863  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:03.863  4788  7321 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:03.863  4788  7321 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.873  4788  4796 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:03.873  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:03.873  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 11:17:03.873  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.883  3218  7822 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:17:03.883  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.883  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.883  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.883  7231  7242 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.883  7231  7242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.883  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:03.883  4788  4788 D BluetoothPbap: Proxy object connected
,08-31 11:17:03.883  3218  7822 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:17:03.883  3218  7822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:03.883  1438  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:17:03.883  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:17:03.883  4788  4788 D PbapServerProfile: Bluetooth service connected
,08-31 11:17:03.883  4788  4788 D BluetoothInputDevice: Proxy object connected
08-31 11:17:03.883  4788  4788 D HidProfile: Bluetooth service connected
08-31 11:17:03.883  3218  7822 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 11:17:03.883  3218  7822 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:03.883  3218  7822 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:03.883  3218  7822 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6bef5d0
,08-31 11:17:03.883  3218  7822 D BluetoothSocket: channel: 19
08-31 11:17:03.883  3218  7822 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 11:17:03.883  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:17:03.883  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:03.893  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.893  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.893  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.893  1438  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:03.893  1698  2162 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.893  1698  2162 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:03.893  4788  4796 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:17:03.893  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 11:17:03.893  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.893  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.893  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:03.893  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 11:17:03.893  7800  7800 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 11:17:03.893  7800  7800 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 11:17:03.893  7800  7800 D UserAnalysis: Create SecureDbHelper
,08-31 11:17:03.903  4788  4788 D BluetoothMap: Proxy object connected
08-31 11:17:03.903  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.903  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.903  4788  4799 D BluetoothPan: Binding service...
08-31 11:17:03.903  4788  4788 D MapProfile: Bluetooth service connected
08-31 11:17:03.903  4788  4788 D BluetoothMap: getConnectedDevices()
,08-31 11:17:03.903  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 11:17:03.903  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.903  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.903  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.903  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.903  7800  7800 D IntelligenceServiceApplication: onCreate()
08-31 11:17:03.903  4788  4788 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:17:03.903  4788  4788 D PanProfile: Bluetooth service connected
,08-31 11:17:03.903  1438  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.913  1017  1506 I ActivityManager: Killing 7338:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-31 11:17:03.913  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:03.913  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:03.913  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.913  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.913  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.913  1438  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:03.913  7800  7800 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:17:03.923  4788  7321 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.923  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 11:17:03.923  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:03.923  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:03.923  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.923  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.923  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 11:17:03.923  7800  7800 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:17:03.923  4788  7321 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:17:03.923  4788  4788 D HeadsetProfile: Bluetooth service connected
08-31 11:17:03.923  1466  1686 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.923  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:03.923  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:17:03.923  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.923  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.923  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-31 11:17:03.923  1466  1686 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:17:03.923  4788  4799 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 11:17:03.923  4788  4799 D Bluetoothsap: Binding service...
,08-31 11:17:03.933  4788  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-31 11:17:03.933  7800  7800 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 11:17:03.933  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 11:17:03.933  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.933  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.933  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.933  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.933  4788  4799 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-31 11:17:03.933  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:17:03.933  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.933  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:17:03.943  4788  4788 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 11:17:03.943  4788  4788 D SapProfile: Bluetooth service connected
08-31 11:17:03.943  4788  4788 D Bluetoothsap: getConnectedDevices()
,08-31 11:17:03.943  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.943  1466  4718 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.943  1466  4718 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.943  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 11:17:03.943  1438  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.943  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:03.943  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:03.943  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:03.943  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.943  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.943  1438  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:03.943  1178  1773 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.943  1178  1773 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.943  3218  3229 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:17:03.943  3218  3229 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.943  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:17:03.943  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.943  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.953  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.953  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.953  3218  3218 D BluetoothA2dp: Proxy object connected
08-31 11:17:03.953  3218  3218 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 11:17:03.953  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.953  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:03.953  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:17:03.953  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:03.953  1438  7823 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:03.953  1438  7823 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.953  4788  4796 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:17:03.953  4788  4796 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:03.953  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:17:03.953  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.953  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:03.953  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:03.953  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:03.963  4788  4788 D BluetoothA2dp: Proxy object connected
08-31 11:17:03.963  4788  4788 D A2dpProfile: Bluetooth service connected
,08-31 11:17:03.963  1691  1709 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:03.963  1691  1709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.963  3218  3233 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:03.963  3218  3233 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:03.963  1456  6358 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:03.963  1456  6358 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:03.963  1017  1047 D BluetoothPan: Binding service...
,08-31 11:17:03.963  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:17:03.963  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:03.963  1017  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-31 11:17:03.963  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:17:03.973  1017  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #25
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: android.os.TransactionTooLargeException
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:17:03.973  1017  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 11:17:03.973  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 11:17:03.973  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:17:03.973  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:03.973  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 11:17:03.973  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:17:03.983  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:17:03.983  1438  1438 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1757f56a, true
,08-31 11:17:03.983  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:17:03.983  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:03.983  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-31 11:17:03.983  1438  1438 D BluetoothHeadset: registerMessageListener
,08-31 11:17:03.983  1998  1998 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:03.983  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:03.983  3218  3354 D HeadsetService: registerMessageListener
,08-31 11:17:03.983  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:03.983  1017  1546 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:03.993  1017  1136 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 11:17:03.993  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:17:03.993  3218  3354 D HeadsetService: registerMessageListener
08-31 11:17:03.993  3218  7799 D HeadsetStateMachine: Disconnected process message: 70
,08-31 11:17:03.993  1438  1438 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 11:17:03.993  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 11:17:03.993  3218  7799 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3d1439c9
,08-31 11:17:03.993  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:03.993  3218  7825 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 11:17:03.993  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:03.993  1438  1438 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 11:17:03.993  1438  1438 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 11:17:03.993  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 11:17:03.993  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:17:03.993  4788  4788 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 11:17:03.993  4788  4788 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 11:17:03.993  4788  4788 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:17:03.993  4788  4788 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:17:04.003  3218  7799 D HeadsetStateMachine: Disconnected process message: 9
08-31 11:17:04.003  3218  7799 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:17:04.003  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:04.003  3218  7825 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:17:04.003  3218  7825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:04.003   283   701 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 11:17:04.003   283   701 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 11:17:04.003   283   701 V voice   : voice_set_parameters: exit with code(-2)
08-31 11:17:04.003   283   701 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:17:04.003   283   701 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:17:04.003   283   701 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:17:04.003   283   701 V audio_hw_primary: adev_set_parameters: exit
08-31 11:17:04.003  3218  7799 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:17:04.003  3218  7825 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-31 11:17:04.003  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:17:04.003  3218  7825 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:04.003  3218  7825 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:04.003  3218  7825 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ae08ce
08-31 11:17:04.003  3218  7825 D BluetoothSocket: channel: 5
,08-31 11:17:04.003  1017  1264 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:17:04.003  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:17:04.013  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:04.013  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:04.013  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:17:04.013  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:17:04.023  4788  4788 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:17:04.023  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:04.023  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:04.023  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:17:04.033  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:04.033  3218  3218 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:17:04.033  1017  1264 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:04.033  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:17:04.033  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:04.033  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:04.033  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:04.043  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 11:17:04.043  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:04.043  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:04.043  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:04.043  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:04.053  7830  7830 E Zygote  : MountEmulatedStorage()
,08-31 11:17:04.053  7830  7830 E Zygote  : v2
08-31 11:17:04.053  7830  7830 I libpersona: KNOX_SDCARD checking this for 10105
08-31 11:17:04.053  7830  7830 I libpersona: KNOX_SDCARD not a persona
,08-31 11:17:04.053  7830  7830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:17:04.053  1017  1029 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7830 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 11:17:04.063  1017  1496 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:17:04.063  7830  7830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:17:04.063  7830  7830 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:17:04.073  3218  7840 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:17:04.073  3218  7840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:04.073  3218  7840 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
,08-31 11:17:04.073  3218  7840 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:04.073  3218  7840 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:04.073  3218  7840 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2625e3da
08-31 11:17:04.073  3218  7840 D BluetoothSocket: channel: 12
08-31 11:17:04.073  3218  7840 I BtOppRfcommListener: Accept thread started.
,08-31 11:17:04.083  7830  7830 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:17:04.083  7830  7830 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:04.183   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:17:04.183   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:17:04.183  7830  7851 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:17:04.193   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:17:04.193   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:17:04.193  7830  7851 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.343  7830  7830 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:04.343  7830  7830 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:04.353  1017  1548 I ActivityManager: Killing 7442:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 11:17:04.403  7830  7852 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:17:04.433  1017  3816 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:04.433  1017  3816 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:04.433  1017  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:04.433  1017  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:05.073  1017  3358 D SSRM:n  : SIOP:: AP = 330
,08-31 11:17:05.083  1017  1096 V AlarmManager: waitForAlarm result :4
,08-31 11:17:05.083  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 11:17:05.083  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 11:17:05.103   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:17:05.103   278   978 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 11:17:05.103  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 11:17:05.103  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 11:17:05.113  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:17:05.113  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-31 11:17:05.113  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 11:17:05.123  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:05.123  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:17:05.133  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:17:05.153  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:17:05.153  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:17:05.153  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:17:05.163  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-31 11:17:05.173  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:17:05.473   288   288 E SMD     : DCD OFF,
,08-31 11:17:06.293  1017  3382 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:17:06.633  7231  7286 D BluetoothAdapter: disable()
,08-31 11:17:06.633  1017  1506 D SettingsProvider: name = bluetooth_on
,08-31 11:17:06.643  3218  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 11:17:06.643  3218  3290 D BluetoothAdapterProperties: Setting state to 13,
,08-31 11:17:06.643  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:17:06.643  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:06.643  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:06.643  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.643  3218  3290 D BluetoothAdapterService: updateAdapterState state is 13
08-31 11:17:06.643  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:06.643  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.643  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.653  3218  3218 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 11:17:06.653  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e2aa00b, channel: 19, state: LISTENING
08-31 11:17:06.653  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e2aa00b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6bef5d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@286baee8mSocket: android.net.LocalSocket@34945901 impl:android.net.LocalSocketImpl@2e0e63a6 fd:FileDescriptor[80]
,08-31 11:17:06.653  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@34945901 impl:android.net.LocalSocketImpl@2e0e63a6 fd:FileDescriptor[80]
,08-31 11:17:06.653  3218  3290 D BluetoothAdapterService: Autoconnection is available 
,08-31 11:17:06.653  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-31 11:17:06.653  3218  3290 D BluetoothAdapterService: terminating service from this receiver
,08-31 11:17:06.653  4788  4788 D BluetoothPbap: Proxy object disconnected
08-31 11:17:06.653  4788  4788 D PbapServerProfile: Bluetooth service disconnected
,08-31 11:17:06.653  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:06.663  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-31 11:17:06.663  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:17:06.663  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:17:06.673  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:06.673  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:06.673  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:06.673  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-31 11:17:06.673  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:17:06.673  1017  1449 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:06.683  1017  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:17:06.683  1998  1998 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:06.683  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:17:06.683  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:06.683  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ac0d194, channel: 5, state: LISTENING
,08-31 11:17:06.683  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ac0d194, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ae08ce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@306c843dmSocket: android.net.LocalSocket@32ad1432 impl:android.net.LocalSocketImpl@20850583 fd:FileDescriptor[82],
08-31 11:17:06.683  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32ad1432 impl:android.net.LocalSocketImpl@20850583 fd:FileDescriptor[82]
,08-31 11:17:06.693  3218  3218 I BtOppRfcommListener: stopping Accept Thread
08-31 11:17:06.693  3218  3218 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26a37300, channel: 12, state: LISTENING
08-31 11:17:06.693  3218  3218 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26a37300, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2625e3da, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32a22739mSocket: android.net.LocalSocket@614417e impl:android.net.LocalSocketImpl@280876df fd:FileDescriptor[87]
08-31 11:17:06.693  3218  3218 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@614417e impl:android.net.LocalSocketImpl@280876df fd:FileDescriptor[87]
,08-31 11:17:06.693  3218  7840 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:17:06.693  3218  7840 I BtOppRfcommListener: BluetoothSocket listen thread finished,
08-31 11:17:06.693  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:17:06.693  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 11:17:06.693  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:06.693  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:06.693  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:17:06.693  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.693  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:06.693  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.693  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.693  3218  3290 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:17:06.693  3218  3290 D BluetoothAdapterProperties: mDiscovering is false
,08-31 11:17:06.703  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:17:06.703  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:06.703  1017  3751 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:17:06.703  3218  3218 V BluetoothOppManager: cleanUp...
,08-31 11:17:06.703  3218  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 11:17:06.713  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:06.713  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:06.713  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:17:06.713  3218  3293 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:17:06.713  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:17:06.723  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 11:17:06.723  1017  1547 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:17:06.723  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.723  3218  3290 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 11:17:06.723  3218  3290 E bt-btif : cmd socket is not created
,08-31 11:17:06.723  3218  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 11:17:06.723  3218  3294 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 11:17:06.723  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:06.723  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.723  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:17:06.733  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:17:06.733  3218  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:17:06.743  4788  4788 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:17:06.743  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:06.743  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:06.743  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:17:06.923  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 11:17:06.923  3218  3290 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:17:06.923  3218  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-31 11:17:06.923  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-31 11:17:06.923  3218  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,08-31 11:17:06.923  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:06.923  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:06.923  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:06.933  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:06.933  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.933  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 11:17:06.933  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:06.933  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.933  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,08-31 11:17:06.933  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:17:06.933  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:17:06.933  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:06.933  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.943  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:06.943  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.943  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:17:06.943  3218  3218 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:17:06.943  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:17:06.943  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:06.943  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:17:06.943  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:06.943  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.943  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:06.943  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:06.943  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.943  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:17:06.943  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:17:06.943  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:17:06.953  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.953  1017  1264 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:06.953  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.953  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:06.953  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:06.953  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.953  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:17:06.953  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:17:06.953  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:17:06.953  1017  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:06.953  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.963  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:17:06.963  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:06.963  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.963  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:17:06.963  4788  4788 D HeadsetProfile: Bluetooth service disconnected
,08-31 11:17:06.963  3218  3218 D A2dpService: Received stop request...Stopping profile...
08-31 11:17:06.963  3218  7809 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:17:06.963  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.963  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.963  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:06.963  1017  3751 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:06.963  1017  3751 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.963  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:06.963  1017  3751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.963  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:06.963  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:17:06.963  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:17:06.963  3218  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 11:17:06.963  1017  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:06.963  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:17:06.973  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.973  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:06.973  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:06.973  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:06.973  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:06.973  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:17:06.973  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:17:06.973  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:17:06.973  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:17:06.973  3218  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-31 11:17:06.973  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-31 11:17:06.973  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 11:17:06.973  4788  4788 D BluetoothA2dp: Proxy object disconnected
08-31 11:17:06.973  4788  4788 D A2dpProfile: Bluetooth service disconnected
,08-31 11:17:06.973  3218  3218 D HidService: Received stop request...Stopping profile...
,08-31 11:17:06.973  3218  3218 D HidService: Stopping Bluetooth HidService
,08-31 11:17:06.973  3218  3218 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 11:17:06.973  3218  3218 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:17:06.973  3218  3218 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:17:06.973  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.983  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-31 11:17:06.983  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:06.983  4788  4788 D BluetoothInputDevice: Proxy object disconnected
08-31 11:17:06.983  4788  4788 D HidProfile: Bluetooth service disconnected
,08-31 11:17:06.983  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:17:06.983  3218  3218 D HealthService: Received stop request...Stopping profile...
08-31 11:17:06.983  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.983  3218  3218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 11:17:06.983  3218  3218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:17:06.983  3218  3218 D PanService: Received stop request...Stopping profile...
,08-31 11:17:06.983  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.983  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:17:06.983  3218  3218 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 11:17:06.983  4788  4788 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:17:06.993  4788  4788 D PanProfile: Bluetooth service disconnected
,08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:06.993  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 11:17:06.993  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:17:06.993  3218  3218 D SapService: Received stop request...Stopping profile...
,08-31 11:17:06.993  3218  3218 D SapService: Stopping Bluetooth SapService
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:06.993  4788  4788 D BluetoothMap: Proxy object disconnected
,08-31 11:17:06.993  4788  4788 D MapProfile: Bluetooth service disconnected
,08-31 11:17:06.993  3218  3218 D BluetoothA2dp: Proxy object disconnected
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 11:17:06.993  3218  7810 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 11:17:06.993  3218  3218 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:17:06.993  3218  3218 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 11:17:06.993  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:17:06.993  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:06.993  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:17:06.993  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.993  3218  3218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:17:06.993  3218  3218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 11:17:06.993  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:17:06.993  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:06.993  3218  3218 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:07.003  4788  4788 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:17:07.003  4788  4788 D SapProfile: Bluetooth service disconnected
08-31 11:17:07.003  3218  3218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:17:07.003  3218  3218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 11:17:07.003  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-31 11:17:07.003  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 11:17:07.003  3218  3218 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:17:07.003  3218  3218 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 11:17:07.003  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-31 11:17:07.003  3218  3218 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 11:17:07.003  3218  3218 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-31 11:17:07.003  3218  3218 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 11:17:07.003  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-31 11:17:07.003  3218  3290 D BluetoothAdapterProperties: Setting state to 10
,08-31 11:17:07.003  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-31 11:17:07.003  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:07.003  3218  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 11:17:07.013  3218  3290 D BluetoothAdapterService: Autoconnection is available 
,08-31 11:17:07.013  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 11:17:07.013  3218  3290 I BluetoothAdapterState: Entering OffState
,08-31 11:17:07.013  4788  4796 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:17:07.013  4788  4799 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.013  4788  4799 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.013  4788  7321 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:17:07.013  7231  7244 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.013  7231  7244 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.013  7231  7244 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 11:17:07.013  7231  7244 D BluetoothLeAdvertiser: Exit stop advertising
08-31 11:17:07.013  7231  7244 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-31 11:17:07.013  7231  7244 D BluetoothLeScanner: Exiting stopAllScan
,08-31 11:17:07.013  1698  4401 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.013  1698  4401 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.013  4788  4796 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:17:07.013  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.023  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.023  7830  7842 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.023  7830  7842 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.023  4788  4796 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 11:17:07.023  4788  4796 D Bluetoothsap: Unbinding service...
,08-31 11:17:07.023  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:17:07.023  1466  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.023  1466  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.023  1178  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.023  1178  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.033  3218  7827 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:17:07.033  1438  7872 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.033  1438  7872 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.033  4788  4799 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:17:07.033  1691  1894 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.033  1691  1894 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.033  3218  3378 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.033  3218  3378 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.033  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:17:07.033  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:17:07.033  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:07.033  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,08-31 11:17:07.033  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:17:07.043  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:17:07.043  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:07.043  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-31 11:17:07.043  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:07.043  1017  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:17:07.043  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:17:07.053  1998  1998 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:07.053  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:07.053  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:07.053  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:07.063  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:17:07.063  1017  1544 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:17:07.063  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:17:07.063  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:07.063  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:07.063  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:17:07.063  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:17:07.073  4788  4788 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:17:07.073  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:07.073  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:07.073  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:17:07.493   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:17:08.473   288   288 E SMD     : DCD OFF
,08-31 11:17:08.493   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:17:09.493   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:17:09.643  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:17:09.643  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:09.853  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:17:09.853  1017  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:17:09.853  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:17:09.853  1017  1030 D BatteryService: stay LED for charging
,08-31 11:17:09.853  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:17:09.863  1017  1017 I MotionRecognitionService: Plugged
,08-31 11:17:09.863  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:17:09.863  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:17:09.863  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:17:09.863  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 11:17:09.863  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:17:09.893  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:17:09.893  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:17:09.893  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:17:09.893  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 11:17:09.893  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-31 11:17:10.493   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:17:11.473   288   288 E SMD     : DCD OFF,
,08-31 11:17:11.493   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:17:12.493   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-31 11:17:12.653  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:17:12.653  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d972a3c added. We now have 6 listener(s),
08-31 11:17:12.653  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:12.653  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:12.653  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea373c5 added. We now have 7 listener(s)
08-31 11:17:12.653  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:12.653  7231  7286 I System.out: IsBluetoothEnabled
08-31 11:17:12.653  7231  7286 D BluetoothAdapter: disable(),
,08-31 11:17:12.663  1017  1029 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-31 11:17:12.663  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:12.663  7231  7286 D BluetoothAdapter: enable()
,08-31 11:17:12.663  1017  1449 W ActivityManager: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:17:12.663  1017  1449 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 11:17:12.663  1017  1449 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:17:12.673  1017  1449 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:12.673  1017  1449 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:12.673  1017  1449 D SettingsProvider: name = bluetooth_on
,08-31 11:17:12.683  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:17:12.683  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:17:12.683  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,08-31 11:17:12.683  3218  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 11:17:12.683  3218  3290 D BluetoothAdapterProperties: Setting state to 11
08-31 11:17:12.683  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:17:12.683  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:12.683  3218  3290 D BluetoothAdapterService: updateAdapterState state is 11,
08-31 11:17:12.693  3218  3290 D BluetoothAdapterService: Autoconnection is available 
08-31 11:17:12.693  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-31 11:17:12.693  3218  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:12.693  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-31 11:17:12.693  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
,08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:17:12.693  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:17:12.693  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:17:12.703  1998  1998 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:12.703  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:17:12.703  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:12.703  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-31 11:17:12.703  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:12.713  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:12.713  1017  1264 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:12.713  1017  3816 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:17:12.713  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:17:12.713  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:12.713  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:17:12.723  1017  1548 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:12.723  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.723  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.723  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.723  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.723  3218  3218 D HeadsetService: Received start request. Starting profile...
,08-31 11:17:12.723  3218  3218 D HeadsetService: start()
08-31 11:17:12.733  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:17:12.733  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:17:12.733  3218  3218 D HeadsetStateMachine: make
08-31 11:17:12.733  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:17:12.733  3218  3218 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 11:17:12.733  1017  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:12.733  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.743  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:17:12.743  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.743  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.743  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.743  1017  1544 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:17:12.743  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.743  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:17:12.743  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:17:12.743  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:17:12.743  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.743  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.743  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 11:17:12.743  1017  3751 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:12.743  1017  3751 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.743  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:12.743  1017  3751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.743  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.753  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-31 11:17:12.753  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:17:12.753  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:17:12.753  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:12.753  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.753  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.753  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:12.753  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.753  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 11:17:12.753  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:17:12.753  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:17:12.753  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:17:12.753  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-31 11:17:12.763  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:12.763  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.763  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:17:12.763  3218  3218 I bluedroid: get_profile_interface handsfree
,08-31 11:17:12.763  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:12.763  1017  3816 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:12.763  1017  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.763  1017  3816 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:12.763  1017  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.763  1017  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.773  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:12.773  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:12.773  3218  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:17:12.773  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:12.773  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 11:17:12.773  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.773  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.773  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.773  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-31 11:17:12.773  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:17:12.773  3218  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 11:17:12.783  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:12.783  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.783  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.783  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.783  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:17:12.783  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:12.783  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:17:12.783  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:17:12.783  3218  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 11:17:12.783  3218  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:17:12.783  3218  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 11:17:12.793  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-31 11:17:12.793  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:17:12.793  3218  3218 E DualScoManager: Dual Sco Manager already instantiated
,08-31 11:17:12.793  3218  3218 I DualScoManager: Set HeadsetServiceHelper
08-31 11:17:12.793  3218  3218 D BluetoothAtMessage: createCMTIContentObservers
08-31 11:17:12.793  1017  1547 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 11:17:12.793  1017  1547 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:17:12.793  1017  1547 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:17:12.793  1017  1547 D SettingsProvider: selectionArgs: false
08-31 11:17:12.793  1017  1547 D SettingsProvider: selectionArgs: 1002
08-31 11:17:12.793  1017  1547 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:17:12.793  1017  1547 D SettingsProvider: ret = -1
,08-31 11:17:12.793  3218  7880 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 11:17:12.793  3218  3218 D HeadsetService: mStartError = false
08-31 11:17:12.793  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:12.803  3218  3218 D A2dpService: Received start request. Starting profile...
08-31 11:17:12.803  3218  3218 D A2dpService: start()
08-31 11:17:12.803  3218  3218 I bluedroid: get_profile_interface avrcp
,08-31 11:17:12.803  3218  7880 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 11:17:12.803  3218  7880 D HeadsetStateMachine: map size, before remove : 0
08-31 11:17:12.803  3218  7880 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:17:12.803  3218  3218 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:17:12.803  3218  3218 D Avrcp   : Initialize Media Controller
08-31 11:17:12.803  3218  3218 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 11:17:12.803  3218  3218 E Avrcp   : getActiveSessions
08-31 11:17:12.803  3218  3218 D Avrcp   : pick active media Controller
08-31 11:17:12.803  3218  3218 D Avrcp   : Get the active Media Controller 
,08-31 11:17:12.813  3218  3218 I Avrcp   :  Updating now playing list upon AVRCP Start,
,08-31 11:17:12.813  3218  3218 D A2dpStateMachine: make
08-31 11:17:12.813  3218  7881 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 11:17:12.823  3218  3218 I bluedroid: get_profile_interface a2dp
,08-31 11:17:12.823  3218  7883 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:17:12.823  3218  3218 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:17:12.823  3218  3218 D A2dpService: mStartError = false
08-31 11:17:12.823  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:12.823  3218  3218 D HeadsetStateMachine: Try to query the phonestate on bind
08-31 11:17:12.823  1438  1470 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:17:12.823  1438  1438 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 11:17:12.823  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 11:17:12.823  1438  1470 I Telecom : BluetoothPhoneService: Result of Message : true
08-31 11:17:12.823  3218  7882 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:17:12.823  3218  3218 D HidService: Received start request. Starting profile...
08-31 11:17:12.823  3218  3218 D HidService: start()
08-31 11:17:12.823  3218  3218 I bluedroid: get_profile_interface hidhost
08-31 11:17:12.823  3218  3218 D HidService: setHidService(): set to: null
08-31 11:17:12.823  3218  3218 D HidService: mStartError = false
08-31 11:17:12.823  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:12.823  3218  3218 D HealthService: Received start request. Starting profile...
08-31 11:17:12.823  3218  3218 D HealthService: start()
,08-31 11:17:12.823  3218  3218 I bluedroid: get_profile_interface health
08-31 11:17:12.823  3218  3218 D HealthService: mStartError = false
08-31 11:17:12.823  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:12.823  3218  3218 D HeadsetStateMachine: Proxy object connected
08-31 11:17:12.823  3218  3218 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 11:17:12.823  3218  3218 D PanService: Received start request. Starting profile...
08-31 11:17:12.823  3218  3218 D PanService: start()
08-31 11:17:12.823  3218  3218 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:17:12.823  3218  3218 I bluedroid: get_profile_interface pan
08-31 11:17:12.823  3218  3218 D PanService: mStartError = false
08-31 11:17:12.823  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:12.833  3218  7880 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:17:12.833  3218  3218 D BluetoothMapService: Received start request. Starting profile...
08-31 11:17:12.833  3218  3218 D BluetoothMapService: start()
,08-31 11:17:12.833  3218  3218 D BluetoothMapService: mStartError = false
,08-31 11:17:12.833  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:12.833  3218  3218 D SapService: Received start request. Starting profile...
08-31 11:17:12.833  3218  3218 D SapService: start()
08-31 11:17:12.833  3218  3218 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:17:12.833  3218  3218 I bluedroid: get_profile_interface sap
08-31 11:17:12.833  3218  3218 D SapService: mStartError = false
08-31 11:17:12.833  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
08-31 11:17:12.833  3218  3218 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 11:17:12.833  3218  3218 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 11:17:12.833  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:17:12.833  3218  3218 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:17:12.833  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:17:12.833  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 11:17:12.833  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 11:17:12.833  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 11:17:12.833  3218  7880 D HeadsetStateMachine: Disconnected process message: 18
08-31 11:17:12.833  3218  7880 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:17:12.833  3218  7880 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:17:12.833  3218  7880 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:17:12.843  3218  7881 D BluetoothMediaBrowser: no now playing list
08-31 11:17:12.843  3218  7881 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 11:17:12.853  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 11:17:12.853  3218  3218 E BluetoothAdapterService(438016615): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:17:12.853  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 11:17:12.853  3218  3290 I bluedroid: enable
,08-31 11:17:12.863  3218  3293 E bt-btif : Calling BTA_HhEnable
,08-31 11:17:12.863  3218  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:17:12.863  3218  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-31 11:17:12.863  3218  3293 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 11:17:12.863  3218  3293 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 11:17:12.863  3218  3293 E BluetoothServiceJni: populateRssiValuesNative
08-31 11:17:12.863  3218  3293 I bluedroid: getModelRssiValues
,08-31 11:17:12.863  3218  3293 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 11:17:12.863  3218  3293 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:17:12.863  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 11:17:12.863  3218  3293 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 11:17:12.873  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:12.873  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:17:12.873  3218  3293 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:17:12.873  3218  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:17:12.873  3218  3293 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-31 11:17:12.873  3218  3293 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-31 11:17:12.873  3218  3293 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-31 11:17:12.873  3218  3293 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 11:17:12.873  3218  3293 E bt-btif : JVenable fails
,08-31 11:17:12.873  3218  3293 D bte_conf: Device ID record 1 : primary
08-31 11:17:12.873  3218  3293 D bte_conf:   vendorId            = 0075
08-31 11:17:12.873  3218  3293 D bte_conf:   vendorIdSource      = 0001
08-31 11:17:12.873  3218  3293 D bte_conf:   product             = 0100
08-31 11:17:12.873  3218  3293 D bte_conf:   version             = 0200
08-31 11:17:12.873  3218  3293 D bte_conf:   clientExecutableURL = 
08-31 11:17:12.873  3218  3293 D bte_conf:   serviceDescription  = 
08-31 11:17:12.873  3218  3293 D bte_conf:   documentationURL    = 
08-31 11:17:12.873  3218  3293 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:17:12.873  3218  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-31 11:17:12.873  3218  3293 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:17:12.873  3218  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:17:12.873  3218  3290 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:17:12.873  3218  3290 D BluetoothAdapterProperties: State =  11
,08-31 11:17:12.873  1017  3816 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:17:12.873  3218  3290 D BluetoothAdapterProperties: Setting state to 12
08-31 11:17:12.873  3218  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:17:12.883  3218  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:17:12.883  3218  3293 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:17:12.883  3218  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:17:12.883  1017  1264 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 11:17:12.883  1017  1264 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:17:12.883  1017  1264 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:17:12.883  1017  1264 D SettingsProvider: selectionArgs: false
08-31 11:17:12.883  1017  1264 D SettingsProvider: selectionArgs: 1002
08-31 11:17:12.883  1017  1264 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:17:12.883  1017  1264 D SettingsProvider: ret = -1
08-31 11:17:12.883  3218  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:17:12.883  3218  3290 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 11:17:12.883  1017  1264 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:12.883  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-31 11:17:12.883  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:12.883  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.883  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.883  3218  3290 D BluetoothAdapterService: Autoconnection is available 
,08-31 11:17:12.883  4788  7321 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:17:12.883  3218  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 11:17:12.883  3218  3290 D BluetoothAdapterService: starting service from this receiver
08-31 11:17:12.883  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:17:12.883  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:17:12.893  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:12.893  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:12.893  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:12.893  3218  3290 I BluetoothAdapterState: Entering On State from state = 11
,08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:12.903  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:12.903  3218  3218 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 11:17:12.903  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:13.033  1017  1047 I art     : Explicit concurrent mark sweep GC freed 50373(2MB) AllocSpace objects, 5(81KB) LOS objects, 33% free, 23MB/34MB, paused 2.401ms total 146.092ms
08-31 11:17:13.033  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 11:17:13.033  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.033  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.033  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.033  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.043  4788  4799 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:13.043  4788  4799 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:13.043  4788  7321 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:17:13.043  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 11:17:13.043  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.043  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.043  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.043  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.043  7231  7242 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:13.043  7231  7242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.043  1438  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.043  3218  3218 I BluetoothPbapService: Handler(): got msg=1
,08-31 11:17:13.043  1017  3801 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
08-31 11:17:13.043  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:13.043  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.043  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.043  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.043  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.053  1438  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:13.053  1698  4401 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.053  1698  4401 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:13.053  4788  4788 D BluetoothPbap: Proxy object connected
08-31 11:17:13.053  4788  4788 D PbapServerProfile: Bluetooth service connected
,08-31 11:17:13.053  4788  7321 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:17:13.053  3218  7890 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:17:13.053  4788  4788 D BluetoothInputDevice: Proxy object connected
08-31 11:17:13.053  4788  4788 D HidProfile: Bluetooth service connected
,08-31 11:17:13.053  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 11:17:13.053  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.053  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.053  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.053  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.063  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.063  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:13.063  4788  4796 D BluetoothPan: Binding service...
,08-31 11:17:13.063  4788  4788 D BluetoothMap: Proxy object connected
08-31 11:17:13.063  4788  4788 D MapProfile: Bluetooth service connected
08-31 11:17:13.063  4788  4788 D BluetoothMap: getConnectedDevices()
,08-31 11:17:13.063  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:17:13.063  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.063  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 11:17:13.063  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.063  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.063  7830  7841 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:17:13.063  7830  7841 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.063  3218  7890 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:17:13.063  3218  7890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:13.063  4788  4788 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:17:13.063  4788  4788 D PanProfile: Bluetooth service connected
08-31 11:17:13.063  1438  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.063  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:13.063  3218  7890 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 11:17:13.063  3218  7890 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:13.063  3218  7890 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:13.063  3218  7890 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22fc18b7
08-31 11:17:13.063  3218  7890 D BluetoothSocket: channel: 19
08-31 11:17:13.063  3218  7890 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 11:17:13.063  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.063  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.063  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.063  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.073  1438  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:13.073  4788  7321 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.073  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:17:13.073  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.073  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.073  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.073  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.073  4788  7321 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:13.073  1466  4718 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.073  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:13.073  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.073  4788  4788 D HeadsetProfile: Bluetooth service connected
08-31 11:17:13.073  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.073  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.073  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-31 11:17:13.073  1466  4718 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:13.073  4788  4799 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 11:17:13.073  4788  4799 D Bluetoothsap: Binding service...
,08-31 11:17:13.083  4788  4799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 11:17:13.083  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 11:17:13.083  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.083  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.083  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.083  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.083  4788  4799 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 11:17:13.083  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:17:13.083  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 11:17:13.083  4788  4788 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 11:17:13.083  4788  4788 D SapProfile: Bluetooth service connected
08-31 11:17:13.083  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:17:13.083  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:17:13.083  4788  4788 D Bluetoothsap: getConnectedDevices()
,08-31 11:17:13.083  1466  1686 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.083  1466  1686 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.083  1017  1017 D BluetoothA2dp: Proxy object connected
08-31 11:17:13.083  1438  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.083  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:13.083  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.083  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.083  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.083  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 11:17:13.083  1438  1470 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:17:13.083  1178  1192 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.083  1178  1192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.093  3218  3354 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:17:13.093  3218  3354 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-31 11:17:13.093  1017  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:17:13.093  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.093  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:13.093  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.093  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.093  3218  3218 D BluetoothA2dp: Proxy object connected
08-31 11:17:13.093  3218  3218 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 11:17:13.093  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.093  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:17:13.093  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:17:13.093  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:17:13.093  1438  7872 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.093  1438  7872 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.103  4788  4796 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:17:13.103  4788  4796 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:17:13.103  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:17:13.103  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.103  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.103  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:13.103  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.103  4788  4788 D BluetoothA2dp: Proxy object connected
,08-31 11:17:13.103  4788  4788 D A2dpProfile: Bluetooth service connected
08-31 11:17:13.103  1691  1709 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.103  1691  1709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.103  3218  3233 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.103  3218  3233 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:17:13.103  1456  1487 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:17:13.103  1456  1487 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:17:13.103  1017  1047 D BluetoothPan: Binding service...
08-31 11:17:13.103  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:17:13.103  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.103  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:17:13.103  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-31 11:17:13.103  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:17:13.103  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:13.103  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 11:17:13.103  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:17:13.113  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:17:13.113  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:17:13.113  1438  1438 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3735fa5b, true
,08-31 11:17:13.113  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:17:13.113  1178  1178 D BluetoothTile:  getBluetoothState : 12
08-31 11:17:13.113  1438  1438 D BluetoothHeadset: registerMessageListener
,08-31 11:17:13.113  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:13.123  1998  1998 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:17:13.123  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:13.123  4788  4788 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:13.123  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:13.123  1178  1678 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:17:13.123  3218  7826 D HeadsetService: registerMessageListener
08-31 11:17:13.123  3218  7826 D HeadsetService: registerMessageListener
,08-31 11:17:13.133  3218  7880 D HeadsetStateMachine: Disconnected process message: 70
08-31 11:17:13.133  3218  7880 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@9687824
08-31 11:17:13.133  1438  1438 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 11:17:13.133  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:17:13.133  1017  1136 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:17:13.133  1017  1449 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 11:17:13.133  1438  1438 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 11:17:13.133  3218  7891 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 11:17:13.133  1438  1438 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 11:17:13.133  1438  1438 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 11:17:13.133  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:17:13.133  4788  4788 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-31 11:17:13.133  4788  4788 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-31 11:17:13.133  4788  4788 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:17:13.133  4788  4788 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:17:13.143  3218  7880 D HeadsetStateMachine: Disconnected process message: 9
08-31 11:17:13.143  3218  7880 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:17:13.143  3218  7891 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:17:13.143  3218  7891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:13.143  3218  7891 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-31 11:17:13.143  3218  7891 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:13.143  3218  7891 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:13.143  3218  7891 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ee4f8d
08-31 11:17:13.143  3218  7891 D BluetoothSocket: channel: 5
08-31 11:17:13.143   283   686 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 11:17:13.143   283   686 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 11:17:13.143   283   686 V voice   : voice_set_parameters: exit with code(-2)
08-31 11:17:13.143   283   686 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:17:13.143   283   686 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:17:13.143   283   686 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:17:13.143   283   686 V audio_hw_primary: adev_set_parameters: exit
08-31 11:17:13.143  3218  7880 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:17:13.143  4788  4788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:17:13.143  1017  1449 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:17:13.143  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.143  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.143  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:13.143  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:17:13.153  1698  1698 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:17:13.153  4788  4788 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:17:13.163  4788  4788 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:17:13.163  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:17:13.163  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:17:13.173  3218  3218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a1b9a67
,08-31 11:17:13.173  3218  3218 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:17:13.183  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:17:13.183  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:17:13.183  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:13.183  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:13.183  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:17:13.183  1017  1546 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:17:13.203  3218  7896 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:17:13.203  3218  7896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:17:13.203  3218  7896 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-31 11:17:13.203  3218  7896 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:17:13.203  3218  7896 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:17:13.203  3218  7896 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7fd5789
,08-31 11:17:13.203  3218  7896 D BluetoothSocket: channel: 12
08-31 11:17:13.203  3218  7896 I BtOppRfcommListener: Accept thread started.
,08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:13.693  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:13.693  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:13.693  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:17:13.693  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@183c811a added. We now have 8 listener(s)
,08-31 11:17:13.703  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:17:13.703  1017  3751 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:17:13.703  1017  3751 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:17:13.703  1017  3751 D SecContentProvider2: mCursor = null
,08-31 11:17:13.703  1017  3751 D WifiService: setWifiEnabled: false pid=7231, uid=10170
,08-31 11:17:13.703  1017  3751 D SettingsProvider: name = wifi_on
,08-31 11:17:13.713  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:13.713  1017  1264 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:17:13.713  1017  1264 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:17:13.713  1017  1264 D SecContentProvider2: mCursor = null
,08-31 11:17:13.713  1017  1264 D WifiService: setWifiEnabled: true pid=7231, uid=10170
,08-31 11:17:13.713  1017  1264 W ActivityManager: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:17:13.713  1017  1264 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:17:13.713  1017  1264 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:17:13.713  1017  1264 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:17:13.713  1017  1264 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:17:13.713  1017  1264 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:17:13.713  1017  1264 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:17:13.713  1017  1264 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:17:13.723  1017  1264 D SettingsProvider: name = wifi_on
,08-31 11:17:13.723  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:17:14.043  1017  1045 D Tethering: interfaceAdded wlan0
,08-31 11:17:14.053  1017  1131 E Tethering: No numeric data
,08-31 11:17:14.053  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 11:17:14.053  1017  1131 D Tethering: clearTetheredNotification()
,08-31 11:17:14.053  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:14.053  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:14.053  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:14.053  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:14.063  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 11:17:14.063  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:14.063  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:17:14.063  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 11:17:14.063  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:14.063  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:14.063  1017  1131 D Tethering: InitialState.processMessage what=4
08-31 11:17:14.063  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:17:14.073  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:14.073  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:14.073  1017  1131 E Tethering: No numeric data
,08-31 11:17:14.073  1017  1045 D Tethering: interfaceAdded p2p0
08-31 11:17:14.073  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:17:14.073  1017  1131 D Tethering: clearTetheredNotification()
,08-31 11:17:14.073  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:17:14.073  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:14.073  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:14.073  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:14.083  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:17:14.083  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 11:17:14.083  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 11:17:14.083  1017  1123 V NetworkStats: performPollLocked() took 10ms
08-31 11:17:14.083  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:14.093  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:14.093  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:14.093  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:17:14.093  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:17:14.093   278   982 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-31 11:17:14.093   278   982 D SoftapController: Softap fwReload - Ok
08-31 11:17:14.093  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:17:14.093   278   982 D CommandListener: Setting iface cfg,
08-31 11:17:14.093   278   982 D CommandListener: Trying to bring down wlan0
08-31 11:17:14.093   278   982 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:17:14.093  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 11:17:14.103  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 11:17:14.113  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:17:14.123  1017  1548 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:17:14.123  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:14.123  1017  1548 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:14.123  1017  1548 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:14.133  1017  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:17:14.133  1017  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:14.133  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.133  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:14.133  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.133  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:14.133  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 11:17:14.133  1178  1178 D HotspotTile: onReceive : 2, 0
,08-31 11:17:14.133  1609  1609 I Hs20UtilService: Starting #19
,08-31 11:17:14.133  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:17:14.143  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:17:14.143  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-31 11:17:14.143  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:17:14.143  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:17:14.143  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:17:14.173  7907  7907 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-31 11:17:14.173  7907  7907 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:17:14.173  7907  7907 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:17:14.183  7907  7907 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-31 11:17:14.183   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7907
08-31 11:17:14.183   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:17:14.183  7907  7907 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 11:17:14.183  7907  7907 I wpa_supplicant: ssSupport state is = 1
08-31 11:17:14.183  7907  7907 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 11:17:14.183  7907  7907 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 11:17:14.183   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7907
08-31 11:17:14.183   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 11:17:14.343   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-31 11:17:14.343  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-31 11:17:14.393  7907  7907 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:17:14.393  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:17:14.403  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:17:14.403   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7907
,08-31 11:17:14.403   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:17:14.403  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:17:14.403  7907  7907 I wpa_supplicant: ssSupport state is = 1
08-31 11:17:14.403  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:17:14.403  7907  7907 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:17:14.403  7907  7907 E wpa_supplicant: SIM READ ERROR
08-31 11:17:14.403  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:17:14.403  7907  7907 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:17:14.403  7907  7907 E wpa_supplicant: SIM READ ERROR,
08-31 11:17:14.403  7907  7907 I wpa_supplicant: Blacklist: Clear (all) 
08-31 11:17:14.403  7907  7907 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:17:14.403  7907  7907 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:17:14.403  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 11:17:14.403  7907  7907 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 11:17:14.403  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:17:14.403  7907  7907 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 11:17:14.403  7907  7907 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 11:17:14.403  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:17:14.403  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:17:14.403  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:17:14.473   288   288 E SMD     : DCD OFF,
,08-31 11:17:14.523  7907  7907 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 11:17:14.653  7907  7907 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 11:17:14.653  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 11:17:14.663  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:17:14.663   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7907
08-31 11:17:14.663   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 11:17:14.673  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:17:14.673  7907  7907 I wpa_supplicant: ssSupport state is = 1
08-31 11:17:14.673  7907  7907 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-31 11:17:14.673  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:17:14.683  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:17:14.683   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7907
08-31 11:17:14.683   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:17:14.683  7907  7907 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-31 11:17:14.683  7907  7907 I wpa_supplicant: ssSupport state is = 1
08-31 11:17:14.683  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:17:14.683  7907  7907 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:17:14.683  7907  7907 E wpa_supplicant: SIM READ ERROR,
08-31 11:17:14.683  7907  7907 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:17:14.683  7907  7907 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:17:14.683  7907  7907 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:17:14.683  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 11:17:14.683  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:17:14.683  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:17:14.693  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:17:14.693  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:17:14.693  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:17:14.733  7907  7907 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 11:17:14.733  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:17:14.793  7907  7907 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 11:17:14.793  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-31 11:17:14.793  7907  7907 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:17:14.803  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-31 11:17:14.803  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:17:14.813  7907  7907 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-31 11:17:14.813  7907  7907 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:17:14.813  7907  7907 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:17:14.813  7907  7907 E wpa_supplicant: SIM READ ERROR
08-31 11:17:14.813  7907  7907 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:17:14.823  7907  7907 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 11:17:14.833  7907  7907 I wpa_supplicant: Skip scan - bUseNetwork false,
08-31 11:17:14.833  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:17:14.843  4788  4788 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:14.843  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.843  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:14.843  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:14.843  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 11:17:14.843  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:17:14.843  1178  1678 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:17:14.843  1017  1126 E WifiConfigStore: Not a HS20
,08-31 11:17:14.843  1178  1178 D HotspotTile: onReceive : 3, 0
,08-31 11:17:14.843  1017  1264 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:14.843  1017  1264 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:14.843  1017  1264 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:14.853  1017  1264 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:14.853  1017  1264 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:14.853  7231  7231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:14.853  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 11:17:14.853  1609  1609 I Hs20UtilService: Starting #20
08-31 11:17:14.853  1609  1643 I Hs20UtilService: Message received 5011
,08-31 11:17:14.853  7231  7231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:17:14.853  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:17:14.853  7907  7907 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:17:14.853  7907  7907 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 11:17:14.853  7907  7907 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:17:14.853  7907  7907 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:17:14.853  7907  7907 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-31 11:17:14.853  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:17:14.853  7907  7907 I wpa_supplicant: First Scan Start
08-31 11:17:14.853  7907  7907 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:17:14.863  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:17:14.863  7401  7401 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:17:14.863  7401  7401 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:17:14.863  7401  7401 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:17:14.863  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-31 11:17:14.863  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:17:14.863  1017  1126 I WifiNative-HAL: startHal
08-31 11:17:14.863  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ed7188c
08-31 11:17:14.863  1017  1126 I WifiNative-HAL: Could not start hal
,08-31 11:17:14.863  7417  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:17:14.863  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 11:17:14.863  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 11:17:14.873   278   982 D CommandListener: Setting iface cfg
08-31 11:17:14.873   278   982 D CommandListener: Trying to bring up p2p0
,08-31 11:17:14.873  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:17:14.873  1017  1125 D WifiP2pService: P2pEnablingState
,08-31 11:17:14.873  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 11:17:14.873  1017  1125 D WifiP2pService: P2p socket connection successful
,08-31 11:17:14.873  1017  1125 D WifiP2pService: P2pEnabledState
,08-31 11:17:14.873  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 11:17:14.873  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3,
08-31 11:17:14.873  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:17:14.873  1017  1151 I WifiNative-HAL: startHal
08-31 11:17:14.873  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9dc339bc
08-31 11:17:14.873  1017  1151 I WifiNative-HAL: Could not start hal,
08-31 11:17:14.873  1017  1151 E WifiScanningService: could not start HAL
08-31 11:17:14.873  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 11:17:14.873  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:17:14.873  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 11:17:14.883  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 11:17:14.883  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:17:14.883  1017  1048 D WifiDisplayController: disconnect,
08-31 11:17:14.883  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:14.883  1017  1048 D WifiDisplayController: updateConnection
08-31 11:17:14.883  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:17:14.883  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:17:14.883  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:17:14.883  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-31 11:17:14.883  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 11:17:14.883  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-31 11:17:14.883  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-31 11:17:14.883  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 11:17:14.883  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:17:14.883  1017  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:17:14.883  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 11:17:14.883  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 11:17:14.883  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:17:14.883  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-31 11:17:14.883  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:17:14.883  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:17:14.883  7907  7907 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:17:14.883  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-31 11:17:14.883  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:17:14.883  7907  7907 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 11:17:14.883  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:17:14.893  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-31 11:17:14.893  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:17:14.893  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:17:14.893  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:17:14.893  7907  7907 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 11:17:14.893  1017  1126 E WifiStateMachine: Failed to set frequency band 0
08-31 11:17:14.893  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 11:17:14.893  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-31 11:17:14.893  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 11:17:14.893  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:14.893  7750  7750 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:17:14.893  1017  1126 D SecContentProvider2: mCursor = null
08-31 11:17:14.893  7750  7750 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:17:14.893  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-31 11:17:14.893  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
,08-31 11:17:14.893  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  secondary type: null
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  wps: 0
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  grpcapab: 0
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  devcapab: 0
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  status: 3
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  wfdInfo: null
,08-31 11:17:14.893  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-31 11:17:14.893  1017  1048 D WifiDisplayController:  SConnectInfo : null
08-31 11:17:14.893  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:14.893  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:14.903  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:17:14.923  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-31 11:17:14.923  1017  1125 D WifiP2pService: InactiveState,
08-31 11:17:14.923  7907  7907 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 11:17:14.923  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 11:17:14.923  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:17:14.923  1017  1125 D WifiP2pService: InactiveState{ what=143376 },
08-31 11:17:14.923  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:17:15.063  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:17:15.063  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:17:15.063  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:17:15.093  1017  3358 D SSRM:n  : SIOP:: AP = 310
,08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:15.733  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:15.743  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 11:17:15.743  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 11:17:15.743  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
08-31 11:17:15.743  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1adf32d Bundle[{}]
,08-31 11:17:15.753  7231  7286 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:17:15.753  7231  7286 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 11:17:15.753  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:17:15.753  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:17:15.753  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 11:17:15.753  7231  7286 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:17:15.753  7231  7286 I System.out: Running OutgoingSocketThread
,08-31 11:17:15.753  7231  7918 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1469)
,08-31 11:17:15.763  7231  7918 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56645
,08-31 11:17:15.763  7231  7918 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:17:16.063  7907  7907 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-31 11:17:16.063  7907  7907 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:17:16.063  7907  7907 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 11:17:16.063  7907  7907 I wpa_supplicant: Trying to associate with  'G700'
08-31 11:17:16.063  7907  7907 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 11:17:16.063  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 11:17:16.063  1017  7913 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:17:16.083  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:16.083  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:16.183  7907  7907 E wpa_supplicant: Cmd 35605 not handled
08-31 11:17:16.183  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:16.183  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:16.183  7907  7907 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:17:16.183  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:17:16.183  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 11:17:16.183  7907  7907 I wpa_supplicant: Associated with F4.99.3E
08-31 11:17:16.183  7907  7907 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 11:17:16.183  7907  7907 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 11:17:16.183  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:17:16.183  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:17:16.183  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:16.183  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:17:16.183  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:17:16.183  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:17:16.183  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-31 11:17:16.193  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:17:16.193  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 11:17:16.193  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:17:16.193  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:16.193  1017  1131 E Tethering: No numeric data
08-31 11:17:16.193  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 11:17:16.193  1017  1131 D Tethering: clearTetheredNotification()
,08-31 11:17:16.193  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:16.203  1017  1123 V NetworkStats: performPollLocked() took 5ms
,08-31 11:17:16.193  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:16.203  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:17:16.193  1017  1126 D SecContentProvider2: mCursor = null
08-31 11:17:16.203  1178  1178 D HotspotTile: updateTetherState():false, false
08-31 11:17:16.193  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 11:17:16.193  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:17:16.203  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:16.203  7907  7907 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:17:16.203  7907  7907 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 11:17:16.203  7907  7907 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-31 11:17:16.203  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 11:17:16.203  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:16.203  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:16.203  7907  7907 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:17:16.203  7907  7907 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 11:17:16.203  7907  7907 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 11:17:16.203  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:17:16.203  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:16.213  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:17:16.213  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:17:16.213  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 11:17:16.213  7907  7907 I wpa_supplicant: Blacklist: Clear (temp) 
,08-31 11:17:16.213  7907  7907 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:17:16.213  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 11:17:16.223  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 11:17:16.223  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:17:16.223  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:17:16.223  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:17:16.223  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:17:16.223  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:17:16.223  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:16.223  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:16.223  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:16.223  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:16.223  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:16.223  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:17:16.223  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:16.223  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:17:16.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.233  1609  1609 I Hs20UtilService: Starting #21
08-31 11:17:16.233  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:16.233  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:17:16.233  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:17:16.233  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:16.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:17:16.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:17:16.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:17:16.243  4788  4788 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:17:16.243  4788  4830 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:17:16.243   278   982 D CommandListener: Setting iface cfg
,08-31 11:17:16.243  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:17:16.253  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 11:17:16.253  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:16.253  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:16.253  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:16.253  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:16.253  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.263  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.263  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:16.263  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:16.263  1017  1126 E WifiNative-wlan0: do suspend false
,08-31 11:17:16.263  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
08-31 11:17:16.263  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:17:16.263  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 11:17:16.263  1017  1126 D SecContentProvider2: mCursor = null
,08-31 11:17:16.323  1017  1096 V AlarmManager: waitForAlarm result :4
,08-31 11:17:16.333   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:17:16.333   278   978 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 11:17:16.333  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:16.343  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:16.343  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:17:16.473  7923  7923 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 11:17:16.483  7923  7923 I dhcpcd  : version 5.5.6 starting
,08-31 11:17:16.483  7923  7923 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 11:17:16.533  7923  7923 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 11:17:16.533  7923  7923 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:17:16.533  7923  7923 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 11:17:16.533  7923  7923 I dhcpcd  : bssid match
08-31 11:17:16.533  7923  7923 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 11:17:16.653  7923  7923 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 11:17:16.713  7923  7923 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-31 11:17:16.753  7231  7286 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1470)
08-31 11:17:16.753  7231  7286 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1470)
,08-31 11:17:16.763  7231  7286 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1475),
08-31 11:17:16.763  7231  7286 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-31 11:17:16.763  7231  7286 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1476)
,08-31 11:17:16.763  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-31 11:17:16.763  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535144b added. We now have 2 listener(s),
08-31 11:17:16.763  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:16.763  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-31 11:17:16.763  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:16.763  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:17:16.763  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10caae28 added. We now have 9 listener(s)
08-31 11:17:16.763  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:16.773  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-31 11:17:16.773  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:16.783  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:16.783  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:16.783  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291194e6 added. We now have 3 listener(s)
08-31 11:17:16.783  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27beaa27 added. We now have 10 listener(s)
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-31 11:17:16.783  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:17:16.783  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:17:16.783  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:16.783  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3535144b removed from the list,
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10caae28 removed from the list
08-31 11:17:16.783  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:16.783  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:16.783  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:16.783  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10caae28 not in the list,
08-31 11:17:16.783  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27beaa27 removed from the list
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:17:16.783  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.783  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:16.783  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:17:16.783  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291194e6 removed from the list
08-31 11:17:16.793  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:16.793  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53084d4 added. We now have 2 listener(s)
,08-31 11:17:16.793  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:16.793  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:16.793  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:17:16.793  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:16.793  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19567d added. We now have 9 listener(s)
08-31 11:17:16.793  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:17:16.793  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-31 11:17:16.803  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:16.803  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:16.803  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:17:16.803  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:17:16.803  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:16.803  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f61c1c3 added. We now have 3 listener(s)
,08-31 11:17:16.803  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:17:16.813  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:16.813  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:16.813  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:16.813  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:16.813  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:16.813  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@357b1a40 added. We now have 10 listener(s)
08-31 11:17:16.813  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:16.813  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:17:16.813  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:17:16.813  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:17:16.813  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:17:16.813  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:17:16.813  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:17:16.813  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:17:16.823  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-31 11:17:16.823  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:17:16.823  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:17:16.823  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-31 11:17:16.833  3218  7826 D BtGatt.GattService: registerClient() - UUID=fa94f7ac-8340-4e9e-9075-82666af49924
,08-31 11:17:16.873  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=fa94f7ac-8340-4e9e-9075-82666af49924, clientIf=6,
,08-31 11:17:16.873  7231  7242 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 11:17:16.873  3218  3229 D BtGatt.GattService: start scan with filters
08-31 11:17:16.873  3218  3356 D BtGatt.ScanManager: handling starting scan
08-31 11:17:16.873  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:17:16.873  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:17:16.873  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:17:16.873  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:17:16.883  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:17:16.883  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:16.883  3218  3356 D BtGatt.ScanManager: allow scan with filters
08-31 11:17:16.883  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:17:16.883  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:17:16.883  3218  3356 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-31 11:17:16.883  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:17:16.883  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:17:16.883  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:17:16.883  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:16.883  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:17:16.883  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 11:17:16.883  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-31 11:17:16.883  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:17:16.883  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:16.883  7231  7286 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-31 11:17:16.883  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:17:16.883  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:17:16.883  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.883  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-31 11:17:16.883  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:16.883  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:17:16.883  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:17:16.883  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:17:16.883  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-31 11:17:16.883  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:17:16.893  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:17:16.893  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:17:16.893  3218  3354 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:17:16.893  3218  3378 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:17:16.893  3218  3356 D BtGatt.ScanManager: filter size is 1
,08-31 11:17:16.893  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 6
,08-31 11:17:16.893  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:17:16.893  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:16.893  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:17:16.893  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:17:16.893  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:17:16.893  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:17:16.893  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:17:16.893  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:17:16.903  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:17:16.903  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:16.903  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:17:16.903  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:17:16.903  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:17:16.903  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:16.903  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:17:16.903  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:17:16.903  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:17:16.903  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:17:16.913  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:16.913  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:16.913  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:17:16.913  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:17:16.923  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:17:16.923  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:16.923  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.923  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-31 11:17:16.923  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53084d4 removed from the list
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:16.923  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19567d removed from the list
08-31 11:17:16.923  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:17:16.923  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:16.923  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.923  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:17:16.923  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19567d not in the list
08-31 11:17:16.923  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.923  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:16.923  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@357b1a40 removed from the list
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 11:17:16.923  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:16.923  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:16.923  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:16.923  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f61c1c3 removed from the list,
08-31 11:17:16.933  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:16.933  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13179a6c added. We now have 2 listener(s)
,08-31 11:17:16.933  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:17:16.933  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:16.933  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:16.943  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:16.943  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da1d835 added. We now have 9 listener(s)
,08-31 11:17:16.943  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:16.943  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:17:16.943  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:16.953  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:16.953  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:16.953  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:17:16.953  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:16.953  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:16.953  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:17:16.953  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22d7a63b added. We now have 3 listener(s)
,08-31 11:17:16.953  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:17:16.963  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:17:16.963  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:17:16.963  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:17:16.963  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1719f158 added. We now have 10 listener(s)
08-31 11:17:16.963  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:17:16.963  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:17:16.963  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:17:16.963  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:17:16.963  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 11:17:16.963  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:17:16.963  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:17:16.963  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:17:16.973  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:17:16.973  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:17:16.973  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:17:16.973  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:17:16.973  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:17:16.973  3218  3378 D BtGatt.GattService: registerClient() - UUID=1e067cd1-f09e-40fe-8c01-322db16b6efe
,08-31 11:17:17.013  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=1e067cd1-f09e-40fe-8c01-322db16b6efe, clientIf=6
,08-31 11:17:17.023  7231  7244 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 11:17:17.023  3218  7827 D BtGatt.GattService: start scan with filters
,08-31 11:17:17.023  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:17:17.023  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:17:17.023  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:17:17.023  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: handling starting scan
,08-31 11:17:17.023  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-31 11:17:17.023  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: allow scan with filters
,08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-31 11:17:17.023  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:17:17.023  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:17:17.023  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-31 11:17:17.023  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:17:17.023  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:17:17.023  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:17:17.033  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:17:17.033  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:17:17.033  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.033  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:17:17.033  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:17:17.033  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:17.033  7231  7286 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,08-31 11:17:17.033  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:17:17.033  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:17:17.033  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:17:17.033  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.033  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.033  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:17:17.033  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.033  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13179a6c removed from the list
,08-31 11:17:17.033  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.043  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da1d835 removed from the list
,08-31 11:17:17.043  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:17:17.043  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-31 11:17:17.043  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.043  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da1d835 not in the list
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:17:17.043  3218  3229 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:17:17.043  3218  3356 D BtGatt.ScanManager: filter size is 1
08-31 11:17:17.043  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 7
08-31 11:17:17.043  3218  3233 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 11:17:17.043  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:17:17.043  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:17.043  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:17:17.043  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:17:17.043  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:17:17.053  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:17:17.053  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.053  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:17:17.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:17:17.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:17:17.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:17:17.053  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:17:17.053  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:17.053  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:17:17.053  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1719f158 removed from the list
08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.063  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22d7a63b removed from the list
,08-31 11:17:17.063  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e8cb04 added. We now have 2 listener(s)
08-31 11:17:17.063  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:17.063  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:17:17.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:17:17.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:17:17.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:17.063  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b11d8ed added. We now have 9 listener(s)
08-31 11:17:17.063  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:17:17.063  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:17:17.073  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:17:17.073  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:17:17.073  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:17:17.073  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:17:17.073  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:17.073  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aa6a1b3 added. We now have 3 listener(s)
,08-31 11:17:17.073  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:17.083  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:17.083  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:17.083  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:17.083  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:17.083  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:17.083  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a99370 added. We now have 10 listener(s)
08-31 11:17:17.083  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:17.083  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:17:17.083  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:17:17.083  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:17:17.083  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:17:17.083  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:17:17.083  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 11:17:17.083  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:17:17.093  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:17:17.093  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:17:17.093  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:17:17.093  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:17:17.093  7231  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:17:17.093  3218  3378 D BtGatt.GattService: registerClient() - UUID=ab7fdd4c-bf07-4b85-9ae8-ae2bdc49e3bd
,08-31 11:17:17.103  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:17:17.103  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:17.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.113  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 11:17:17.123  1017  1126 E WifiStateMachine: VerifyingLinkState enter
,08-31 11:17:17.123  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 11:17:17.123  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 11:17:17.123  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 11:17:17.143  3218  3293 D BtGatt.GattService: onClientRegistered() - UUID=ab7fdd4c-bf07-4b85-9ae8-ae2bdc49e3bd, clientIf=6,
08-31 11:17:17.143  7231  7244 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,08-31 11:17:17.143  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-31 11:17:17.143  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:17:17.143  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:17:17.143  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:17:17.143  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:17:17.143  3218  3354 D BtGatt.GattService: start scan with filters
,08-31 11:17:17.143  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-31 11:17:17.143  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:17:17.143  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:17:17.143  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:17:17.143  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:17:17.143  3218  3356 D BtGatt.ScanManager: handling starting scan
,08-31 11:17:17.153  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-31 11:17:17.153  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:17.153  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:17.153  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:17.153  3218  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:17:17.153  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.153  1017  1506 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:17:17.153  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 11:17:17.153  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:17.153  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-31 11:17:17.153  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:17.153  1017  1128 D ConnectivityService: LTETest block dns file not exists
08-31 11:17:17.153  3218  3356 D BtGatt.ScanManager: allow scan with filters
08-31 11:17:17.153  3218  3356 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:17:17.153  3218  3356 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:17:17.153  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.153  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:17:17.163  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 11:17:17.163  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 11:17:17.163  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.163  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:17:17.163  1609  1609 I Hs20UtilService: Starting #22
,08-31 11:17:17.163  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:17.163  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:17:17.163  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:17.163  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:17:17.163  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.163  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.163  1017  1128 V NetworkStats: performPollLocked() took 6ms
,08-31 11:17:17.163  3218  3356 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:17:17.163  3218  3356 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:17:17.173  3218  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:17:17.173  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.173  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:17:17.173  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:17:17.173  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:17:17.183  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:17:17.183  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-31 11:17:17.183  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:17.183  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.183  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 11:17:17.183  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.183  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:17.183  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 11:17:17.183  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:17:17.183  4788  4788 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:17:17.183  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 11:17:17.183  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.183  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:17:17.183  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:17:17.183  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:17:17.183  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:17.183  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.183  1017  1128 V NetworkStats: performPollLocked() took 3ms
08-31 11:17:17.183  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:17:17.193  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:17:17.193  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:17.193  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.193  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.193  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:17:17.193  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 11:17:17.193  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-31 11:17:17.203  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-31 11:17:17.203  1017  7919 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:17:17.203  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 11:17:17.203  1017  7919 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 11:17:17.203  1017  7919 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:17:17.203  1017  7919 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-31 11:17:17.203  1017  7919 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:17:17.203  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:17:17.203  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:17:17.203  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:17:17.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.203  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.203  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:17:17.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.203  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e8cb04 removed from the list
08-31 11:17:17.203  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.203  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b11d8ed removed from the list
08-31 11:17:17.203  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:17:17.203  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:17:17.203  1017  1128 D ConnectivityService:    accepting network in place of null
08-31 11:17:17.203  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 11:17:17.213  1466  1466 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-31 11:17:17.213  1466  1466 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:17:17.213  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:17:17.213  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-31 11:17:17.213  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:17.213  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:17:17.213  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:17:17.213  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.213  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.213  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:17.213  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 11:17:17.213   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:17:17.213   278   978 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-31 11:17:17.213  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.213  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.213  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.213  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 11:17:17.223  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 11:17:17.223  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 11:17:17.223  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:17:17.223  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 11:17:17.223  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.223  1017  1123 V NetworkStats: updateIfacesLocked()
08-31 11:17:17.223  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:17:17.223  1178  1663 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:17:17.223  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:17:17.223  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:17.223  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:17:17.223  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:17:17.223  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.223  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.223  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b11d8ed not in the list
08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:17:17.223  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:17:17.223  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:17:17.223  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:17:17.223  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.223  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.223  1017  1123 V NetworkStats: performPollLocked() took 5ms
,08-31 11:17:17.223  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.223  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 11:17:17.223  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.223  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:17.223  3218  7827 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:17:17.223  3218  7826 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:17:17.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:17:17.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:17:17.233  3218  3356 D BtGatt.ScanManager: filter size is 1
08-31 11:17:17.233  3218  3356 D BtGatt.ScanManager: delete FilterIndex - 8
08-31 11:17:17.233  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:17.233  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:17.233  3218  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:17:17.233  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:17:17.233  3218  3356 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:17:17.233  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:17:17.233  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:17:17.233  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:17:17.233  1178  1178 D StatusBar.NetworkController: updateDataNetType()
,08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:17:17.233  7231  7286 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:17:17.233  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:17:17.233  3218  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:17:17.233  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.233  1017  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:17:17.233  3218  3356 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:17:17.233  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:17:17.233  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:17.233  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:17.233  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:17.243  1609  1609 I Hs20UtilService: Starting #23
,08-31 11:17:17.243  3218  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:17:17.243  3218  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:17:17.243  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.243  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:17.243  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a99370 removed from the list
08-31 11:17:17.243  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.243  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:17.243  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aa6a1b3 removed from the list
08-31 11:17:17.243  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:17.243  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:17:17.243  7231  7231 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:17:17.243  1609  1643 I Hs20UtilService: Message received 5007
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76c769c added. We now have 2 listener(s)
,08-31 11:17:17.243  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:17:17.243  4788  4788 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:17:17.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:17.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:17:17.243  4788  4788 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 11:17:17.243  4788  4788 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:17.243  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa38a5 added. We now have 9 listener(s)
08-31 11:17:17.243  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:17:17.253  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:17:17.253  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:17:17.253  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:17:17.253  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:17:17.253  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:17:17.263  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:17:17.263  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:17:17.263  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:17.263  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:17:17.263  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:17:17.263  1609  1609 I Hs20UtilService: Starting #24
,08-31 11:17:17.263  1609  1643 I Hs20UtilService: Message received 5007
,08-31 11:17:17.263  4788  4788 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:17:17.263  7231  7286 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:17:17.263  4788  4788 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 11:17:17.263  7231  7286 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:17:17.263  7231  7286 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:17:17.263  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:17:17.263  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fa942b added. We now have 3 listener(s)
,08-31 11:17:17.273  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:17.273  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:17:17.273  1017  1544 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:17:17.273  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:17:17.273  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33186088 added. We now have 10 listener(s)
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:17:17.273  7231  7286 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:17:17.273  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:17:17.273  7231  7286 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.273  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.273  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76c769c removed from the list
08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.273  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa38a5 removed from the list
08-31 11:17:17.273  7231  7286 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:17.273  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.273  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.273  7231  7286 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfa38a5 not in the list
08-31 11:17:17.273  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.273  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:17.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:17:17.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:17:17.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:17:17.283  7231  7286 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33186088 removed from the list
08-31 11:17:17.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:17:17.283  7231  7286 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:17:17.283  7231  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:17:17.283  7231  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:17:17.283  7231  7286 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fa942b removed from the list
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:17:17.283  7231  7286 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:17:17.283  1017  1548 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
,08-31 11:17:17.283  1017  1548 D SecContentProvider2: mCursor = null,
08-31 11:17:17.283  1017  3801 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 11:17:17.283  1017  3801 D SecContentProvider2: mCursor = null
,08-31 11:17:17.283  1017  1546 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 11:17:17.283  1017  1546 D SecContentProvider2: mCursor = null
,08-31 11:17:17.293  1017  3816 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 11:17:17.293  1017  3816 D SecContentProvider2: mCursor = null
08-31 11:17:17.293  7231  7959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1483, name: My test thread name)
08-31 11:17:17.293  7231  7959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1483, thread name: My test thread name)
08-31 11:17:17.293  7231  7959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1483, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:17:17.293  1017  1488 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 11:17:17.293  1017  1488 D SecContentProvider2: mCursor = null
,08-31 11:17:17.293  1017  1506 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-31 11:17:17.293  1017  1506 D SecContentProvider2: mCursor = null
,08-31 11:17:17.293  7231  7960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1485, name: My test thread name)
08-31 11:17:17.303  7231  7960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1485, thread name: My test thread name)
,08-31 11:17:17.303  7231  7960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1485, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:17:17.303  7231  7286 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:17:17.303  7231  7286 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:17:17.303  7231  7286 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:17:17.303  7231  7286 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:17:17.303  7231  7286 D com.test.thalitest.ThaliTestRunner: Total duration: 23271 ms
,08-31 11:17:17.303  7231  7286 I jxcore-log: Total number of executed tests:  80,
08-31 11:17:17.303  7231  7286 I jxcore-log: 
08-31 11:17:17.303  7231  7286 I jxcore-log: Number of passed tests:  80
08-31 11:17:17.303  7231  7286 I jxcore-log: 
08-31 11:17:17.303  7231  7286 I jxcore-log: Number of failed tests:  0
08-31 11:17:17.303  7231  7286 I jxcore-log: 
,08-31 11:17:17.303  7231  7286 I jxcore-log: Number of ignored tests:  0
08-31 11:17:17.303  7231  7286 I jxcore-log: 
08-31 11:17:17.303  7231  7286 I jxcore-log: Total duration:  23271
08-31 11:17:17.303  7231  7286 I jxcore-log: 
,08-31 11:17:17.303  7231  7286 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-31 11:17:17.303  7231  7286 I jxcore-log: 
08-31 11:17:17.303  7231  7286 I jxcore-log: My device name is: samsung-SM-A300FU
08-31 11:17:17.303  7231  7286 I jxcore-log: 
08-31 11:17:17.313  7231  7286 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:17:17.313  7231  7286 I jxcore-log: 
08-31 11:17:17.313  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.313  7231  7286 I jxcore-log: 
08-31 11:17:17.313  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.313  7231  7286 I jxcore-log: 
08-31 11:17:17.313  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.313  7231  7286 I jxcore-log: 
08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
,08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
,08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
,08-31 11:17:17.323  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.323  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
,08-31 11:17:17.333  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.333  7231  7286 I jxcore-log: 
08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.343   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-31 11:17:17.343  7231  7286 I jxcore-log: 
08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.343  7231  7286 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:17:17.343  7231  7286 I jxcore-log: 
,08-31 11:17:17.353  1017  1030 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-31 11:17:17.363  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 11:17:17.413  7231  7231 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:17:17.473   288   288 E SMD     : DCD OFF,
,08-31 11:17:17.563  7231  7231 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-31 11:17:17.573  7962  7962 D AndroidRuntime: ,
08-31 11:17:17.573  7962  7962 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 11:17:17.583  7962  7962 D AndroidRuntime: CheckJNI is OFF,
08-31 11:17:17.583  7962  7962 D AndroidRuntime: readGMSProperty: start
08-31 11:17:17.583  7962  7962 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:17:17.583  7962  7962 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 11:17:17.583  7962  7962 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:17:17.583  7962  7962 D AndroidRuntime: readGMSProperty: end
08-31 11:17:17.583  7962  7962 D AndroidRuntime: addProductProperty: start,
,08-31 11:17:17.703  7962  7962 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 11:17:17.713  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:17:17.733  7962  7962 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:17:17.743  7231  7231 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:17:17.753  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-31 11:17:17.753  1017  1136 D PackageManager: START PACKAGE DELETE: observer{959276837}
08-31 11:17:17.753  1017  1136 D PackageManager: pkg{<packageName>}
08-31 11:17:17.753  1017  1136 D PackageManager: user{0}
08-31 11:17:17.753  1017  1136 D PackageManager: caller{2000}
08-31 11:17:17.753  1017  1136 D PackageManager: flags{2}
08-31 11:17:17.753  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 11:17:17.753  1017  1136 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 11:17:17.753  1017  1136 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 11:17:17.753  1017  1136 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 11:17:17.753  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-31 11:17:17.753  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 11:17:17.753  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 11:17:17.753  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 11:17:17.753  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 11:17:17.753  1017  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-31 11:17:17.763  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,08-31 11:17:17.873  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:17:17.883  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:17.883  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:17.883  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:17.883  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:17.883  7231  7231 D AndroidRuntime: Shutting down VM
,08-31 11:17:17.883  7231  7231 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:17:17.883  7231  7231 E AndroidRuntime: Process: com.test.thalitest, PID: 7231
08-31 11:17:17.883  7231  7231 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } in io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1277fe36
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:943)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: Caused by: java.lang.SecurityException: ConnectivityService: Neither user 10170 nor current process has android.permission.ACCESS_NETWORK_STATE.
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1540)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.net.IConnectivityManager$Stub$Proxy.getActiveNetworkInfo(IConnectivityManager.java:1297)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.net.ConnectivityManager.getActiveNetworkInfo(ConnectivityManager.java:748)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor.updateConnectivityInfo(ConnectivityMonitor.java:152)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver.onReceive(ConnectivityMonitor.java:225)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-31 11:17:17.883  7231  7231 E AndroidRuntime: 	... 8 more
,08-31 11:17:17.903  7972  7972 E Zygote  : MountEmulatedStorage()
,08-31 11:17:17.903  7972  7972 E Zygote  : v2,
08-31 11:17:17.903  7972  7972 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:17:17.903  7972  7972 I libpersona: KNOX_SDCARD not a persona
08-31 11:17:17.903  1017  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:17:17.903  7972  7972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:17:17.903  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-31 11:17:17.913  7972  7972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:17:17.913  7972  7972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:17:17.913  1017  1043 I ActivityManager: Killing 7231:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
08-31 11:17:17.913  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{2504dd72 u0 com.test.thalitest/.MainActivity t164}
08-31 11:17:17.923  1017  1544 W ActivityManager: Can't find mystery application for Crash from pid=7231 uid=10170: android.os.BinderProxy@196060fa
08-31 11:17:17.923  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
08-31 11:17:17.923  1017  1058 I ActivityManager:   Force finishing activity ActivityRecord{2504dd72 u0 com.test.thalitest/.MainActivity t164 f}
08-31 11:17:17.923  1017  1058 W ActivityManager: Duplicate finish request for ActivityRecord{2504dd72 u0 com.test.thalitest/.MainActivity t164 f}
,08-31 11:17:17.933  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 11:17:17.953  7972  7972 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:17:17.953  7972  7972 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:17.953  1017  1043 D InputDispatcher: Focus left window: 7231
,08-31 11:17:17.953   258   452 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-31 11:17:17.953   258  1039 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-31 11:17:17.963  1017  1043 D InputDispatcher: Focused application released
,08-31 11:17:17.963  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:17:17.963  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:17:17.973  2812  2812 I art     : Explicit concurrent mark sweep GC freed 16599(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 41.310ms
,08-31 11:17:17.993  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:17:18.003  1691  1902 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 11:17:18.003  1998  1998 E SamsungIME: mOCRHelper is null
,08-31 11:17:18.023  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:17:18.043  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-31 11:17:18.043  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
08-31 11:17:18.043  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:18.053  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:17:18.053  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:18.063  1017  1123 V NetworkStats: performPollLocked() took 17ms
08-31 11:17:18.063  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:18.063  1456  1456 D RegisteredServicesCache: empty dynamic service
,08-31 11:17:18.093  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:18.093  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:18.093  1456  1456 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 11:17:18.103  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:17:18.103  7972  7972 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 11:17:18.103  7972  7972 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 11:17:18.103  7972  7972 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:17:18.113  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-31 11:17:18.113  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 11:17:18.113  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 11:17:18.113  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 11:17:18.113  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-31 11:17:18.123  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:17:18.123  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 11:17:18.123  7972  7972 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 11:17:18.123  7972  7972 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 11:17:18.123  7972  7972 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 11:17:18.123  7972  7972 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:17:18.123  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:18.123  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.123  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.133  1017  1488 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 11:17:18.133  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 11:17:18.133  1017  1488 D SecContentProvider2: mCursor = null
,08-31 11:17:18.133  1017  3801 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-31 11:17:18.133  1017  3801 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-31 11:17:18.133  1017  3801 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 11:17:18.133  1017  3801 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-31 11:17:18.143  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 11:17:18.163  1017  1030 I ActivityManager: Killing 7460:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-31 11:17:18.223  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 11:17:18.243  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 11:17:18.243  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 11:17:18.243  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-31 11:17:18.243  1017  1546 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:17:18.243  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,08-31 11:17:18.253  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.253  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.253  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.263  1017  1058 I art     : Explicit concurrent mark sweep GC freed 70279(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 7.908ms total 255.744ms
,08-31 11:17:18.263  1017  1027 I art     : WaitForGcToComplete blocked for 224.780ms for cause HeapTrim
,08-31 11:17:18.273  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.273  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 11:17:18.273  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 11:17:18.273  1017  1058 D PackageManager: delete codoeFile: 
,08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 11:17:18.273  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 11:17:18.283  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 11:17:18.283  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.283  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:17:18.283  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 11:17:18.283  1017  1163 D TaskPersister: removeObsoleteFile: deleting file=164_task.xml
,08-31 11:17:18.283  1017  3358 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-31 11:17:18.283  1017  1017 V EnterpriseBillingPolicy: uID is 10170
,08-31 11:17:18.283  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:17:18.283  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:17:18.283  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.293  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-31 11:17:18.293  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 11:17:18.293  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 11:17:18.293  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 11:17:18.293  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 11:17:18.293  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-31 11:17:18.293  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-31 11:17:18.303  1017  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-31 11:17:18.303  1017  1058 D PackageManager: result of delete: 1{959276837}
,08-31 11:17:18.303  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.303  7962  7962 D AndroidRuntime: Shutting down VM
,08-31 11:17:18.313  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 11:17:18.313  1017  1058 D PackageManager: userId{-1}
08-31 11:17:18.313  1017  1058 D PackageManager: andCode{true}
,08-31 11:17:18.313  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 11:17:18.313  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.313  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.313  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.313  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:18.323  7990  7990 E Zygote  : MountEmulatedStorage()
08-31 11:17:18.323  7990  7990 E Zygote  : v2
08-31 11:17:18.323  7990  7990 I libpersona: KNOX_SDCARD checking this for 10003
08-31 11:17:18.323  7990  7990 I libpersona: KNOX_SDCARD not a persona
08-31 11:17:18.333  7990  7990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:17:18.333  1017  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7990 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 11:17:18.333  1017  3801 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:17:18.333  1017  3801 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-31 11:17:18.333  1017  3801 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.333  1017  3801 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.333  1017  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-31 11:17:18.333  7990  7990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:17:18.333  7990  7990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:17:18.363  7990  7990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:17:18.363  7990  7990 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:18.373  1017  1547 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.373  1698  8002 I VacuumService: Vacuum at: now=1472635038359 tag=VacuumService
,08-31 11:17:18.373  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.373  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.373  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.393  1017  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.393  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.393  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 11:17:18.393  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.393  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.403  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:17:18.403  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.403  1017  1136 I ActivityManager: Killing 7477:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-31 11:17:18.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.413  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 11:17:18.413  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:17:18.413  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:17:18.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.433  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.433  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.433  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.433  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:17:18.443  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.443  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:17:18.443  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:17:18.443  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 11:17:18.453  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:17:18.453  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:17:18.453  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.453  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.453  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.453  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:18.453  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:17:18.463  8010  8010 E Zygote  : MountEmulatedStorage()
08-31 11:17:18.463  8010  8010 E Zygote  : v2
,08-31 11:17:18.463  8010  8010 I libpersona: KNOX_SDCARD checking this for 10001
08-31 11:17:18.463  8010  8010 I libpersona: KNOX_SDCARD not a persona
,08-31 11:17:18.463  8010  8010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:17:18.463  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8010 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:17:18.473  8010  8010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:17:18.473  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 11:17:18.473  8010  8010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:17:18.473  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 11:17:18.483  8010  8010 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:17:18.493  8010  8010 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:18.493  1017  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.493  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.493  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.493  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.503  1017  3816 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.503  1017  3816 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:18.503  1017  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.503  1017  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.513  7962  7962 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-31 11:17:18.533  1017  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 11:17:18.543  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:18.543  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.543  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:17:18.543  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:17:18.543  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:17:18.543  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 11:17:18.543  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:18.543  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:17:18.543  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:17:18.543  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:17:18.553  1017  1128 V NetworkStats: performPollLocked() took 6ms
,08-31 11:17:18.553  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:17:18.553  1698  8003 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-31 11:17:18.553  8029  8029 E Zygote  : MountEmulatedStorage()
,08-31 11:17:18.553  8029  8029 E Zygote  : v2
08-31 11:17:18.553  8029  8029 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:17:18.553  8029  8029 I libpersona: KNOX_SDCARD not a persona
,08-31 11:17:18.563  8029  8029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:17:18.563  1017  1506 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=8029 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:17:18.563  1017  1506 I ActivityManager: Killing 7494:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-31 11:17:18.563  1698  8003 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 11:17:18.563  8029  8029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:17:18.563  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 11:17:18.563  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:18.563  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 11:17:18.563  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:17:18.563  8029  8029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:17:18.563  1178  1663 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 11:17:18.563  1178  1663 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 11:17:18.573  1017  3801 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.573  1017  3801 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.573  1017  3801 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.573  1017  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.593  8029  8029 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:17:18.593  8029  8029 D ActivityThread: Added TimaKeyStore provider
,08-31 11:17:18.613  1698  8003 W Uploader:  no longer exists, so no auth token.
,08-31 11:17:18.633  1017  3751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:17:18.633  1017  3751 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:17:18.633  1017  3751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.633  1017  3751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:17:18.633  8029  8029 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 11:17:18.633  1698  8009 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-31 11:17:18.643  1698  8009 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 11:17:18.643  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 11:17:18.653  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.653  8029  8029 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: disk I/O error (code 3850),
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	,at com.google.android.gms.phenotype.service.a.c.a(SourceFile:60)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at com.google.android.gms.phenotype.service.a.a.a(SourceFile:25)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-31 11:17:18.653  1698  8009 E PhenotypeIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:17:18.653  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-31 11:17:18.653  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318),
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: ,	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.653  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.653  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:17:18.653  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.653  1698  8003 E Uploader: Failed to get server token: Status{statusCode=INTERNAL_ERROR, resolution=null}
08-31 11:17:18.663  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 11:17:18.663  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.663  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.663  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.663  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:17:18.663  1017  1547 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
08-31 11:17:18.663  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:17:18.663  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-31 11:17:18.663  1017  1547 W Act,ivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-31 11:17:18.663  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.663  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:37,2)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.673  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673  1698  8003 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 11:17:18.673  1698  8003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:17:18.673  1698  8003 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 11:17:18.673  1698  8003 I System.out: (HTTPLog)-Thread-220-252649336: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 11:17:18.673  1698  8003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:17:18.673  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.673  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.673  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.673   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:17:18.673   278   978 D Netd    : getNetworkForDns: using netid 504 for uid 10011
08-31 11:17:18.683  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.683  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.683  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.683  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.683  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.683  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.683  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.693  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.693  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.693  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.693  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.693  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.693  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.693  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.703  8029  8029 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:17:18.703  8029  8029 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-31 11:17:18.703  8029  8029 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:17:18.703  8029  8029 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)

```
