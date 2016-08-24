#### Test 8251899684424f3_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-24 17:07:35.907  1015  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 17:07:35.907  1015  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:07:35.907  1015  1364 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 17:07:35.907  1015  1364 D BatteryService: stay LED for fully charged
08-24 17:07:35.907  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 17:07:35.907  1015  1015 I MotionRecognitionService: Plugged
08-24 17:07:35.907  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-24 17:07:35.917  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 17:07:35.917  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 17:07:35.917  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 17:07:35.917  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 17:07:35.927  3140  3140 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 17:07:35.927  3140  3243 D HeadsetStateMachine: Disconnected process message: 10
08-24 17:07:35.937  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 17:07:35.937  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 17:07:35.937  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:07:36.577  6763  6763 D AndroidRuntime: 
08-24 17:07:36.577  6763  6763 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 17:07:36.577  6763  6763 D AndroidRuntime: CheckJNI is OFF
08-24 17:07:36.577  6763  6763 D AndroidRuntime: readGMSProperty: start
08-24 17:07:36.577  6763  6763 D AndroidRuntime: readGMSProperty: already setted!!
08-24 17:07:36.577  6763  6763 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 17:07:36.577  6763  6763 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 17:07:36.577  6763  6763 D AndroidRuntime: readGMSProperty: end
08-24 17:07:36.577  6763  6763 D AndroidRuntime: addProductProperty: start
08-24 17:07:36.727  6763  6763 E AffinityControl: AffinityControl: registerfunction enter
08-24 17:07:36.757  6763  6763 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 17:07:36.767  1015  1474 E PersonaManagerService: inState():  stateMachine is null !!
08-24 17:07:36.767  1015  1474 I PersonaManagerService: PersonaId don't exist
08-24 17:07:36.767  1015  1474 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 17:07:36.767  1015  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:36.787  1015  1474 W ActivityManager: mDVFSHelper.acquire()
08-24 17:07:36.787   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-24 17:07:36.787   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-24 17:07:36.797  1015  1474 D FocusedStackFrame: Set to : 0
08-24 17:07:36.807  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 17:07:36.807  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 17:07:36.807  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:36.807  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:36.807  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:36.807  1015  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:36.817  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 17:07:36.817  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 17:07:36.817   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-24 17:07:36.817   287   287 E SMD     : DCD OFF
08-24 17:07:36.827  6774  6774 E Zygote  : MountEmulatedStorage()
08-24 17:07:36.827  6774  6774 E Zygote  : v2
08-24 17:07:36.827  6774  6774 I libpersona: KNOX_SDCARD checking this for 10171
08-24 17:07:36.827  6774  6774 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:36.827  1015  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 17:07:36.827  1015  1474 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6774 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 17:07:36.827  1015  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:36.827  1015  1474 D InputDispatcher: Focused application set to: xxxx
08-24 17:07:36.827  6774  6774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:36.827  1015  1474 D InputDispatcher: Focus left window: 1479
08-24 17:07:36.827  6763  6763 D AndroidRuntime: Shutting down VM
08-24 17:07:36.837  6774  6774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:36.837  6774  6774 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 17:07:36.847  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 17:07:36.847  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 17:07:36.867  6774  6774 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:36.867  6774  6774 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:36.867  1015  1028 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 17:07:36.867  1015  1015 V ActivityManager: Display changed displayId=0
08-24 17:07:36.877  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 17:07:36.887  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
08-24 17:07:36.907  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-24 17:07:36.917   257  2016 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-24 17:07:36.917   257   433 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-24 17:07:36.927  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{368cb6ec token=android.os.BinderProxy@38813b88 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 17:07:36.927  1479  1479 D Launcher: onTrimMemory. Level: 20
08-24 17:07:37.017  6774  6774 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-24 17:07:37.037  6763  6763 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 17:07:37.057  6774  6774 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 7309-7316)
,08-24 17:07:37.057  6774  6774 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 17:07:37.077  6774  6774 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1cbc23c4}
,08-24 17:07:37.077  6774  6774 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 17:07:37.077  6774  6774 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 17:07:37.117  6774  6774 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 17:07:37.117  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:37.127  6774  6774 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:07:37.157  6774  6774 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:37.157  6774  6774 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:37.157  6774  6774 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:37.157  6774  6774 I Adreno-EGL: Local Branch: 
08-24 17:07:37.157  6774  6774 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:37.157  6774  6774 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:37.157  6774  6774 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:37.237  6774  6774 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:37.247  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 17:07:37.247  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 17:07:37.257  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 17:07:37.257  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 17:07:37.367  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:37.377  6774  6774 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 17:07:37.387  6774  6774 D PhoneWindow: *FMB* installDecor mIsFloating : false,
08-24 17:07:37.387  6774  6774 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-24 17:07:37.397  6774  6774 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,08-24 17:07:37.397  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{22e8871 u0 com.test.thalitest/.MainActivity t2}
,08-24 17:07:37.397  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 17:07:37.397  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:37.527  6774  6815 D OpenGLRenderer: Render dirty regions requested: true
,08-24 17:07:37.527  1015  1334 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 17:07:37.527  1015  1334 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 17:07:37.527  1015  1334 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 17:07:37.537  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 17:07:37.537  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 17:07:37.537  6774  6802 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-24 17:07:37.537  6774  6774 V ActivityThread: updateVisibility : ActivityRecord{2afcd424 token=android.os.BinderProxy@10917b51 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 17:07:37.547  6774  6774 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-24 17:07:37.547  6774  6774 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-24 17:07:37.557   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-24 17:07:37.567  1015  1094 D InputDispatcher: Focus entered window: 6774
,08-24 17:07:37.577  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:07:37.577  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:07:37.577  6774  6774 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 17:07:37.577  6774  6815 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 17:07:37.577  6774  6815 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-24 17:07:37.587  6774  6815 D OpenGLRenderer: Enabling debug mode 0
,08-24 17:07:37.607  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 17:07:37.607  1176  1176 I StatusBar: Icon Only
,08-24 17:07:37.617  1176  1176 D PanelView: There is/are notification(s) 
,08-24 17:07:37.617  1015  6820 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:07:37.627  1015  1045 I ActivityManager: Displayed Component not be shown by security: +733ms (total +823ms),
,08-24 17:07:37.627  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22e8871 u0 com.test.thalitest/.MainActivity t2} time:107885,
,08-24 17:07:37.627  1015  1045 W ActivityManager: mDVFSHelper.release(),
,08-24 17:07:37.637  6774  6774 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 17:07:37.637  6774  6774 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10917b51 time:107891
08-24 17:07:37.637   257   646 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-24 17:07:37.637   257   432 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
,08-24 17:07:37.637  1870  1870 I SamsungIME: getCurrentCandidateView
,08-24 17:07:37.697  6774  6774 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6774
,08-24 17:07:37.737  1870  1870 D SamsungIME: Dismiss ExpandCandiate
,08-24 17:07:37.887  1870  1870 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 17:07:37.887  6774  6774 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 17:07:37.927  1870  1870 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 17:07:37.927  1015  1310 E Watchdog: !@Sync 3
,08-24 17:07:37.937  1870  1870 I SamsungIME: KeybaordView init() : load resources
,08-24 17:07:37.967  1870  1870 I SamsungIME: getCurrentKeyboard
08-24 17:07:37.967  1870  1870 I SamsungIME: getTextKeyboard
,08-24 17:07:37.977  6774  6819 D jxcore_app_log: JniHelper::setJavaVM(0xb756b2b0), pthread_self() = -1213180064
,08-24 17:07:37.977  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 17:07:37.977  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 17:07:37.977  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 17:07:37.977  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 17:07:37.977  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 17:07:37.987  6774  6819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fd369a added. We now have 1 listener(s)
08-24 17:07:37.987  1870  1870 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-24 17:07:37.987  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
08-24 17:07:37.987  6774  6819 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-24 17:07:37.987  6774  6819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:07:37.987  6774  6819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 17:07:37.997  6774  6819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a56dac1 added. We now have 1 listener(s)
08-24 17:07:37.997  6774  6819 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:38.007  6774  6819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-24 17:07:38.017  6774  6819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:38.017  6774  6819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:38.017  6774  6819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 17:07:38.017  6774  6819 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:38.017  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:38.027  6774  6819 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 17:07:38.027  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:38.067  6774  6774 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 17:07:38.527  6774  6828 W jxcore-log: Initializing JXcore engine
08-24 17:07:38.527  6774  6828 W jxcore-log: JXcore engine is ready
,08-24 17:07:38.587  2018  2018 E audit   : type=1400 msg=audit(1472051258.587:205): avc:  denied  { ioctl } for  pid=6828 comm="Thread-1260" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 17:07:38.587  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.587  2018  2018 E audit   : type=1300 msg=audit(1472051258.587:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9faa08f8 items=0 ppid=305 ppcomm=main pid=6828 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1260" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 17:07:38.587  2018  2018 E audit   : type=1320 msg=audit(1472051258.587:205): 
,08-24 17:07:38.597  6774  6828 W jxcore-log: Starting JXcore engine,
,08-24 17:07:38.707  6774  6828 W jxcore-log: Platform android,
08-24 17:07:38.707  6774  6828 W jxcore-log: 
08-24 17:07:38.707  6774  6828 W jxcore-log: Process ARCH arm
08-24 17:07:38.707  6774  6828 W jxcore-log: 
,08-24 17:07:38.847   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 17:07:38.847   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 17:07:38.907  6774  6828 I jxcore-log: JXcore Cordova bridge is ready!,
08-24 17:07:38.907  6774  6828 I jxcore-log: 
08-24 17:07:38.907  6774  6828 W jxcore-log: JXcore engine is started
,08-24 17:07:38.917  6774  6819 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 17:07:38.917  6774  6774 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 17:07:39.827   287   287 E SMD     : DCD OFF,
,08-24 17:07:42.177  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-24 17:07:42.377  1015  3343 D SSRM:n  : SIOP:: AP = 340
,08-24 17:07:42.827   287   287 E SMD     : DCD OFF,
,08-24 17:07:43.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:44.237  5639  5639 D FactoryTest: Not factory mode
,08-24 17:07:44.237  5639  5639 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-24 17:07:44.237  5639  5639 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 17:07:44.237  5639  5639 D MTPRx   : still no open session command from host, so toast
,08-24 17:07:44.247  5639  5639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-24 17:07:44.247  5639  5639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-24 17:07:44.247  5639  5639 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114506
,08-24 17:07:44.247  1015  1027 E PersonaManagerService: inState():  stateMachine is null !!
,08-24 17:07:44.247  1015  1027 I PersonaManagerService: PersonaId don't exist
08-24 17:07:44.247  1015  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-24 17:07:44.257  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:07:44.257  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:44.257  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:44.257  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-24 17:07:44.257  1015  1027 W ActivityManager: mDVFSHelper.acquire()
,08-24 17:07:44.277  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:07:44.287  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:44.287  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:07:44.287  1015  1027 D InputDispatcher: Focused application set to: xxxx
,08-24 17:07:44.287  1015  1027 D InputDispatcher: Focus left window: 6774
,08-24 17:07:44.287  5639  5639 E MTPRx   : started activity for popup
,08-24 17:07:44.287  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:07:44.287  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101,
,08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:07:44.317  5639  5639 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:07:44.337  5639  5639 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-24 17:07:44.337  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:07:44.337  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:44.337  1015  1477 D InputDispatcher: Focused application set to: xxxx
,08-24 17:07:44.337  1015  1477 D InputDispatcher: Focus entered window: 6774
,08-24 17:07:44.347  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:07:44.347  1015  1554 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 17:07:44.347  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:07:44.347  1015  1554 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1ea517a8 attribute=null, token = android.os.BinderProxy@2e8ca078
,08-24 17:07:44.387  5639  5639 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-24 17:07:44.397  5639  5639 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-24 17:07:44.397  5639  5639 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-24 17:07:44.417  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 17:07:44.417  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-24 17:07:44.417  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 17:07:44.417  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-24 17:07:44.417  1015  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 17:07:44.417  1015  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 17:07:44.417  1015  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 17:07:44.417  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 17:07:44.417  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 17:07:44.437  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:07:44.437  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 17:07:44.437  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34f5111d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3fa5873a, 16908290=android.view.AbsSavedState$1@3fa5873a}, android:focusedViewId=100}]}]
,08-24 17:07:44.447  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 17:07:44.447  6774  6774 V ActivityThread: updateVisibility : ActivityRecord{2afcd424 token=android.os.BinderProxy@10917b51 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 17:07:44.447  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 17:07:44.447  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 17:07:44.447  6774  6774 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10917b51 time:114703
,08-24 17:07:44.447  1015  1478 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:07:44.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:45.827   287   287 E SMD     : DCD OFF,
,08-24 17:07:45.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:45.957  1015  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:07:45.967  1015  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 17:07:45.967  1015  1553 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 17:07:45.967  1015  1553 D BatteryService: stay LED for fully charged
08-24 17:07:45.967  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:07:45.967  1015  1015 I MotionRecognitionService: Plugged
,08-24 17:07:45.967  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:07:45.967  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:07:45.967  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:07:45.977  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 17:07:45.977  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:07:45.987  3140  3140 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 17:07:45.987  3140  3243 D HeadsetStateMachine: Disconnected process message: 10
,08-24 17:07:45.997  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:07:45.997  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:07:45.997  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:07:46.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:46.857  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-24 17:07:47.257  1015  1040 W ActivityManager: mDVFSHelper.release(),
,08-24 17:07:47.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:48.827   287   287 E SMD     : DCD OFF
,08-24 17:07:48.847   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 17:07:49.747  1015  1093 V AlarmManager: waitForAlarm result :4
,08-24 17:07:49.747  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-24 17:07:49.767  2041  2041 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-24 17:07:49.817  1015  1334 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:49.817  1015  1334 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-24 17:07:49.827  1015  1334 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:49.827  1015  1334 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:49.827  1015  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:49.867  4792  4792 D ConnectivityManager: CallingUid : 10011, CallingPid : 4792
,08-24 17:07:49.877  1015  1476 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 17:07:49.877  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-24 17:07:49.877  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-24 17:07:49.877  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-24 17:07:49.887  4792  6836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 17:07:49.937  4792  6837 W DriveInitializer: Background init thread started
,08-24 17:07:49.967   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-24 17:07:49.967   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:49.967  4792  6837 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-24 17:07:50.007  2041  2041 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-24 17:07:50.047  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:50.057  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-24 17:07:50.057  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:50.057  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.057  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.077  1015  1476 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-24 17:07:50.077  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-24 17:07:50.077  4792  6837 W DriveInitializer: Background init thread ended
,08-24 17:07:50.097  1015  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:07:50.097  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-24 17:07:50.097  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:50.097  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.097  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.127  4792  6845 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-24 17:07:50.127  4792  6845 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-24 17:07:50.147  2041  2041 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 17:07:50.187  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:50.187  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.187  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.277  1015  1554 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:50.277  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-24 17:07:50.277  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:50.277  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.277  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.317  1015  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:50.317  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-24 17:07:50.317  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:50.317  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:50.317  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.377  1015  3992 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:50.377  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:50.377  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.377  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.387  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:50.397  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:50.397  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.397  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.477  1015  1553 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:50.477  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:50.477  1015  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:50.477  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:50.477  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:50.477  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:50.487  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:50.487  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:50.497  6850  6850 E Zygote  : MountEmulatedStorage(),
08-24 17:07:50.497  6850  6850 E Zygote  : v2
08-24 17:07:50.497  6850  6850 I libpersona: KNOX_SDCARD checking this for 10011
08-24 17:07:50.497  6850  6850 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:50.497  1015  1553 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6850 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-24 17:07:50.507  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:50.507  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:50.507  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:50.527  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:50.527  6850  6850 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:50.547  6850  6850 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 17:07:50.547  6850  6850 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 17:07:50.587  6850  6850 I MultiDex: VM with version 2.1.0 has multidex support
08-24 17:07:50.587  6850  6850 I MultiDex: install
08-24 17:07:50.587  6850  6850 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 17:07:50.617  6850  6850 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 17:07:50.677  6850  6850 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 17:07:50.677  6850  6850 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20413bc0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-24 17:07:50.677  6850  6850 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 17:07:50.697  6850  6850 D ChimeraCfgMgr: Reading stored module config
,08-24 17:07:50.797  6850  6867 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-24 17:07:50.807  2041  2225 I art     : Explicit concurrent mark sweep GC freed 58269(3MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 10MB/18MB, paused 1.400ms total 129.962ms
,08-24 17:07:50.807  6850  6850 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-24 17:07:50.807  6850  6850 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-24 17:07:50.987  1015  3992 I art     : Explicit concurrent mark sweep GC freed 37083(1989KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.435ms total 152.633ms
,08-24 17:07:50.997  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-24 17:07:51.017  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:51.017  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.017  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.017  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.027  1015  1364 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:51.037  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.037  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.037  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.057   282   708 D WVCdm   : Instantiating CDM.
,08-24 17:07:51.057   282   282 I WVCdm   : CdmEngine::OpenSession
,08-24 17:07:51.057   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-24 17:07:51.087   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-24 17:07:51.107   282   282 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-24 17:07:51.107  1015  1494 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-24 17:07:51.107  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-24 17:07:51.107  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.107  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.107  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.117  2041  2041 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=87a18bea-ec69-438d-885b-ed14f8150b54
,08-24 17:07:51.137  2041  2041 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 17:07:51.137  2041  2041 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 17:07:51.167   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-24 17:07:51.167  1015  1094 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:51.167   282   708 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-24 17:07:51.167   282   708 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-24 17:07:51.167   282   708 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-24 17:07:51.167  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.167  1015  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.167  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.167   282   708 D WVCdm   : PrepareKeyRequest: nonce=2580772513
,08-24 17:07:51.177  4244  4398 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 679us total 34.166ms
,08-24 17:07:51.267  6850  6859 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-24 17:07:51.267  6850  6859 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:51.267  6850  6859 I System.out: (HTTPLog)-Static: isShipBuild true
08-24 17:07:51.267  6850  6859 I System.out: (HTTPLog)-Thread-1240-587711597: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-24 17:07:51.267  6850  6859 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:07:51.267   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:07:51.267   274   979 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 17:07:51.307  1015  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:07:51.307  2041  2209 W GCoreFlp: No location to return for getLastLocation()
,08-24 17:07:51.317  6850  6859 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 17:07:51.317  6850  6859 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6850, getuid(): 10011
,08-24 17:07:51.337  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:51.347  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.347  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.347  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.347  1015  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:51.347  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.347  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:51.347  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.377  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-24 17:07:51.377  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.377  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:51.377  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.397  4792  6846 D UdcContextInitService: registered all accounts: true
,08-24 17:07:51.397  2041  2213 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 17:07:51.437  2041  2225 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-24 17:07:51.597  6850  6859 I qtaguid : Untagging socket 30
,08-24 17:07:51.607  1015  1364 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-24 17:07:51.607  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-24 17:07:51.617  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:51.617  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:51.617  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:51.627  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 17:07:51.627  6774  6828 I jxcore-log: 
,08-24 17:07:51.627  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 17:07:51.627  6774  6828 I jxcore-log: 
,08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:51.627  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:51.637  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:51.637  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 17:07:51.637  6774  6828 I jxcore-log: 
,08-24 17:07:51.637  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 17:07:51.637  6774  6828 I jxcore-log: 
,08-24 17:07:51.827   287   287 E SMD     : DCD OFF,
,08-24 17:07:51.997  6879  6879 I dex2oat : ----------------------------------------------------
,08-24 17:07:51.997  6879  6879 I dex2oat : <SS>: S T A R T I N G . . .
08-24 17:07:51.997  6879  6879 I dex2oat : <SS>: Zip is absent. Canceled.
08-24 17:07:51.997  6879  6879 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 17:07:52.047  6879  6879 I dex2oat : dex2oat took 46.303ms (threads: 4)
,08-24 17:07:52.057  6850  6859 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:52.057  6850  6859 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:52.057  6850  6859 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:52.057  6850  6859 I Adreno-EGL: Local Branch: 
08-24 17:07:52.057  6850  6859 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:52.057  6850  6859 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:52.057  6850  6859 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:52.317  6850  6859 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:52.317  6850  6859 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:52.317  6850  6859 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:52.317  6850  6859 I Adreno-EGL: Local Branch: 
08-24 17:07:52.317  6850  6859 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:52.317  6850  6859 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:52.317  6850  6859 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:52.347  6774  6828 D executeNativeTests: Running unit tests,
,08-24 17:07:52.367  6850  6859 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-24 17:07:52.367  6850  6859 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:52.367  6850  6859 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:52.367  6850  6859 I Adreno-EGL: Local Branch: 
08-24 17:07:52.367  6850  6859 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:52.367  6850  6859 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:52.367  6850  6859 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:52.397  1015  3343 D SSRM:n  : SIOP:: AP = 360
,08-24 17:07:52.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:07:52.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db added. We now have 2 listener(s)
,08-24 17:07:52.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:07:52.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:07:52.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:07:52.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:52.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 added. We now have 2 listener(s)
08-24 17:07:52.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:52.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:07:52.447  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:52.447  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:52.457  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:52.457  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:52.457  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:52.457  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:07:52.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:52.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 17:07:52.457  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:07:52.457  6774  6828 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 17:07:52.457  6774  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:07:52.457  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:52.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:52.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 17:07:52.457  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:52.457  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.457  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.467  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:07:52.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db removed from the list
08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 removed from the list
08-24 17:07:52.467  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.467  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.467  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.467  6774  6828 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-24 17:07:52.467  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:52.467  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.467  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:52.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:07:52.467  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:52.477  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.477  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.477  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.477  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.477  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.477  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.477  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.477  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.477  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.477  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.477  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.477  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:07:52.477  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:07:52.477  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.477  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.477  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.477  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.487  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.487  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.487  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.487  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.487  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.487  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.487  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.487  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.487  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.487  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.487  6774  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:07:52.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:52.487  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:07:52.497  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:52.497  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:07:52.497  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:07:52.497  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:52.497  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:52.497  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:52.497  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:07:52.497  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:07:52.497  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:07:52.497  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:52.507  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:07:52.507  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 17:07:52.527  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-24 17:07:52.527  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-24 17:07:52.527  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:07:52.527  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:07:52.527  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 17:07:52.537  3140  3338 D BtGatt.GattService: registerClient() - UUID=c152db3d-6410-4efe-bbc7-5eca29e7c0c9
,08-24 17:07:52.577  3140  3236 D BtGatt.GattService: onClientRegistered() - UUID=c152db3d-6410-4efe-bbc7-5eca29e7c0c9, clientIf=6
,08-24 17:07:52.587  6774  6786 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:07:52.587  3140  3156 D BtGatt.GattService: start scan with filters
,08-24 17:07:52.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:07:52.587  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 17:07:52.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:07:52.587  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:52.587  3140  3241 D BtGatt.ScanManager: handling starting scan
,08-24 17:07:52.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:52.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:07:52.597  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:52.597  3140  3241 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:52.597  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-24 17:07:52.597  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-24 17:07:52.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:52.597  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:52.597  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:52.597  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:52.607  3140  3236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:07:52.607  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.607  3140  3241 D BtGatt.ScanManager: allow scan with filters
08-24 17:07:52.607  3140  3241 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:07:52.607  3140  3241 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-24 17:07:52.607  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:07:52.607  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.607  3140  3241 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:52.617  3140  3241 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:52.617  6774  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:52.617  3140  3236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 17:07:52.617  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.617  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.617  6774  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 17:07:52.617  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.617  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 17:07:52.617  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.617  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:52.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:52.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:52.617  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:52.617  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:07:52.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:07:52.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:52.617  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 17:07:52.617  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.617  3140  3338 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:52.627  3140  3156 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:07:52.627  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:07:52.627  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:52.627  3140  3241 D BtGatt.ScanManager: filter size is 1
08-24 17:07:52.627  3140  3241 D BtGatt.ScanManager: delete FilterIndex - 3
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:07:52.627  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:52.627  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.627  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.627  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:52.627  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.627  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.627  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.627  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.627  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.627  6774  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 17:07:52.637  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.637  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:52.637  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:52.637  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:07:52.637  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.637  3140  3241 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:52.637  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:52.637  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:52.637  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:52.637  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 17:07:52.637  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:07:52.637  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:52.637  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:52.637  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:52.637  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:07:52.637  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.647  3140  3241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:07:52.647  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:52.647  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:52.647  2041  6848 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-24 17:07:52.647  2041  6848 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:52.647  2041  6848 I System.out: (HTTPLog)-Static: isShipBuild true
08-24 17:07:52.647  2041  6848 I System.out: (HTTPLog)-Thread-272-782967888: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-24 17:07:52.647  2041  6848 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:07:52.647  3140  3236 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 17:07:52.647   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:07:52.647   274   979 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 17:07:52.647  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.657  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:52.657  2041  6848 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 17:07:52.657  2041  6848 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:52.657  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:07:52.657  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:07:52.657  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:07:52.657  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:07:52.657  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:07:52.667  3140  3156 D BtGatt.GattService: registerClient() - UUID=5d8cb6ce-9c10-4bda-8955-e1bd2ff37463
,08-24 17:07:52.697  2041  6848 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:52.707  3140  3236 D BtGatt.GattService: onClientRegistered() - UUID=5d8cb6ce-9c10-4bda-8955-e1bd2ff37463, clientIf=6
,08-24 17:07:52.707  6774  6782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:07:52.707  3140  3151 D BtGatt.GattService: start scan with filters
,08-24 17:07:52.707  3140  3241 D BtGatt.ScanManager: handling starting scan
,08-24 17:07:52.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:07:52.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 17:07:52.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:07:52.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:52.707  3140  3236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:07:52.707  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.707  3140  3241 D BtGatt.ScanManager: allow scan with filters
08-24 17:07:52.707  3140  3241 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:07:52.707  3140  3241 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-24 17:07:52.717  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:07:52.717  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.717  3140  3241 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:52.717  3140  3241 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:52.717  3140  3236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:07:52.717  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:52.717  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:52.717  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-24 17:07:52.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:07:52.717  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.727  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:52.727  6774  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:52.727  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:52.727  6774  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 17:07:52.727  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.727  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:07:52.727  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.727  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:52.727  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:52.727  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:52.727  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:52.727  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:07:52.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:07:52.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:52.737  3140  3338 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:52.737  3140  3241 D BtGatt.ScanManager: filter size is 1
08-24 17:07:52.737  3140  3241 D BtGatt.ScanManager: delete FilterIndex - 4
08-24 17:07:52.737  3140  3156 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:07:52.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:07:52.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:52.737  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:07:52.737  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:52.737  3140  3241 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:07:52.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:07:52.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:07:52.747  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:07:52.747  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.747  3140  3241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:07:52.747   282   691 I WVCdm   : CdmEngine::CloseSession
,08-24 17:07:52.747  3140  3236 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 17:07:52.747  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.747   282   691 I WVCdm   : L3 Terminate.
08-24 17:07:52.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:52.747  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.747  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:52.747  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.747  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.747  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:52.747  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.747  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.747  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.747  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.747  6774  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 17:07:52.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:52.757  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:52.757  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:52.757  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:52.757  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:07:52.757  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:52.767  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:52.767  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:52.767  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:52.767  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:52.767  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:07:52.767  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:52.767  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:07:52.767  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:07:52.777  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:07:52.777  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:07:52.777  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:07:52.777  3140  3151 D BtGatt.GattService: registerClient() - UUID=d2690acb-3790-4b4a-ba18-96bd17e984c8
,08-24 17:07:52.817  3140  3236 D BtGatt.GattService: onClientRegistered() - UUID=d2690acb-3790-4b4a-ba18-96bd17e984c8, clientIf=6
,08-24 17:07:52.817  6774  6786 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 17:07:52.817  3140  3237 D BtGatt.GattService: start scan with filters
08-24 17:07:52.817  3140  3241 D BtGatt.ScanManager: handling starting scan
08-24 17:07:52.817  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:07:52.817  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 17:07:52.817  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:07:52.817  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:52.827  3140  3236 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-24 17:07:52.827  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.827  3140  3241 D BtGatt.ScanManager: allow scan with filters
08-24 17:07:52.827  3140  3241 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 17:07:52.827  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:07:52.827  3140  3241 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-24 17:07:52.827  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:07:52.827  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:52.827  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-24 17:07:52.827  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.827  3140  3241 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:52.827  3140  3241 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:52.837  3140  3236 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:07:52.837  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.837  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:52.837  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-24 17:07:52.837  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.837  6774  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:52.847  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:52.847  6774  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 17:07:52.847  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:52.847  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 17:07:52.847  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:52.847  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:52.847  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 17:07:52.847  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:52.847  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:52.847  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:07:52.847  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-24 17:07:52.847  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:52.847  3140  3151 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:52.847  3140  3241 D BtGatt.ScanManager: filter size is 1
,08-24 17:07:52.847  3140  3241 D BtGatt.ScanManager: delete FilterIndex - 5
,08-24 17:07:52.847  3140  3236 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 17:07:52.847  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:52.857  3140  3241 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:07:52.857  3140  3237 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:07:52.857  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:07:52.857  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 17:07:52.857  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-24 17:07:52.857  3140  3236 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:07:52.857  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:52.857  3140  3241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,08-24 17:07:52.857  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.857  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.857  6774  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-24 17:07:52.857  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.857  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.857  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:07:52.857  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.857  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.857  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:52.857  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
,08-24 17:07:52.857  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.857  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.857  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.857  3140  3236 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:07:52.857  3140  3236 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:52.857  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:52.857  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.867  6774  6828 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-24 17:07:52.867  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.867  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.867  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:07:52.867  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.867  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.867  6774  6828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-24 17:07:52.867  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.867  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.867  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:07:52.867  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.867  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.867  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.867  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.877  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list,
,08-24 17:07:52.877  6774  6828 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 17:07:52.877  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.877  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.877  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.877  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.877  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.877  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.877  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.877  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:52.877  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.877  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.877  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.877  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.877  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 17:07:52.877  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:52.877  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:52.877  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:07:52.877  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:52.877  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.877  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.887  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.887  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.887  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.887  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.887  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:52.887  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.887  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.887  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.887  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.887  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.887  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:52.887  6774  6828 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 17:07:52.887  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-24 17:07:52.887  6774  6828 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:07:52.887  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:07:52.887  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 17:07:52.887  6774  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:07:52.887  6774  6828 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 17:07:52.887  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:52.887  6774  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-24 17:07:52.887  6774  6828 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 17:07:52.887  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:52.887  6774  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:07:52.887  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:52.897  6774  6828 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1324)
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.897  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.897  6774  6828 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.897  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.897  6774  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1324
,08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 17:07:52.897  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.897  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.897  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.897  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.897  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.897  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.897  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
,08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 17:07:52.907  6774  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:07:52.907  6774  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:07:52.907  6774  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:52.907  6774  6828 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:07:52.907  6774  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:52.907  6774  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 17:07:52.907  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.907  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.907  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.907  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.907  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.907  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.907  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.907  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings,: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.907  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.907  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.907  6774  6891 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.917  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.917  6774  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:52.917  6774  6891 D BluetoothSocket: connect(): myUserId = 0
08-24 17:07:52.917  6774  6891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 17:07:52.917  6774  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 17:07:52.917  6774  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.917  6774  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 17:07:52.917  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 17:07:52.917  3140  3151 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:52.927  6774  6891 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:07:52.927  6774  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 17:07:52.927  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.927  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:52.927  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.927  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.927  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.927  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.927  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.927  6774  6828 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 17:07:52.927  6774  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:52.927  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:52.927  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.927  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.927  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.927  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.927  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.927  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.927  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.937  6774  6893 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:07:52.937  6774  6893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:07:52.937  6774  6893 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-24 17:07:52.937  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.937  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.937  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.937  6774  6893 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:07:52.937  6774  6893 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.937  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6893 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f912a9a
08-24 17:07:52.937  6774  6893 D BluetoothSocket: channel: 6
08-24 17:07:52.937  6774  6893 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8e63fcb, channel: 6, state: LISTENING
08-24 17:07:52.937  6774  6893 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8e63fcb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f912a9a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@137b33a8mSocket: android.net.LocalSocket@31225ec1 impl:android.net.LocalSocketImpl@2ec75666 fd:FileDescriptor[107]
08-24 17:07:52.937  6774  6893 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31225ec1 impl:android.net.LocalSocketImpl@2ec75666 fd:FileDescriptor[107]
08-24 17:07:52.937  6774  6893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 17:07:52.937  6774  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 17:07:52.937  6774  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 17:07:52.937  6774  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.937  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:52.937  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:52.937  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198b29db not in the list
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.937  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:52.937  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:52.937  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:52.937  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163bc78 not in the list
08-24 17:07:52.937  6774  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 17:07:52.937  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:07:52.937  6774  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 17:07:52.937  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:07:52.937  6774  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 17:07:52.937  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 17:07:52.947  6774  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:07:52.947  6774  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:07:52.947  6774  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 17:07:52.947  6774  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 17:07:52.947  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:52.947  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20170da7 added. We now have 2 listener(s)
08-24 17:07:52.947  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:52.947  6774  6828 D BluetoothAdapter: enable()
08-24 17:07:52.957  6774  6828 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 17:07:52.957  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 17:07:52.957  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:07:52.957  1015  1027 D SecContentProvider2: mCursor = null
08-24 17:07:52.957  1015  1027 D WifiService: setWifiEnabled: true pid=6774, uid=10171
08-24 17:07:52.967  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:07:52.967  2041  2225 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-24 17:07:52.967  1015  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-24 17:07:52.967  1015  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:07:52.967  1015  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:07:52.967  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:07:52.967  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:07:52.967  1015  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:07:52.967  1015  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:07:52.967  1015  1027 D SettingsProvider: name = wifi_on
08-24 17:07:52.967  2041  2225 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-24 17:07:52.967  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:52.967  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2623e254 added. We now have 3 listener(s)
08-24 17:07:52.967  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:07:52.977  2041  2225 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-24 17:07:51.529+0200, stopTime=2016-08-24 17:07:52.982+0200, duration=1453ms
08-24 17:07:52.977  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:52.977  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3525fd added. We now have 4 listener(s)
08-24 17:07:52.977  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:07:52.977  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:52.977  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe272f2 added. We now have 5 listener(s)
08-24 17:07:52.977  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:07:52.987  1015  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 17:07:52.987  1015  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:07:52.987  1015  1494 D SecContentProvider2: mCursor = null
08-24 17:07:52.987  1015  1494 D WifiService: setWifiEnabled: false pid=6774, uid=10171
08-24 17:07:52.987  1015  1494 D SettingsProvider: name = wifi_on
08-24 17:07:52.987  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:52.987   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:07:52.987   274   979 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 17:07:52.987  6774  6828 D BluetoothAdapter: disable()
,08-24 17:07:52.997  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:52.997  2041  6896 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:52.997  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 17:07:52.997  1362  1362 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:07:52.997  1362  1362 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-24 17:07:52.997  1362  1362 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-24 17:07:52.997  1362  1362 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 17:07:53.007  1015  1334 D SettingsProvider: name = bluetooth_on
,08-24 17:07:53.007  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:07:53.017  3140  3233 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-24 17:07:53.017  3140  3233 D BluetoothAdapterProperties: Setting state to 13
08-24 17:07:53.017  3140  3233 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:07:53.027  3140  3233 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:07:53.027  3140  3233 D BluetoothAdapterService: updateAdapterState state is 13
08-24 17:07:53.027  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:53.027  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.027  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-24 17:07:53.027  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.027  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.027  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.027  3140  3140 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
,08-24 17:07:53.027  3140  3233 D BluetoothAdapterService: Autoconnection is available 
08-24 17:07:53.027  3140  3233 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-24 17:07:53.027  3140  3233 D BluetoothAdapterService: terminating service from this receiver
,08-24 17:07:53.027  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.027  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.027  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.027  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:07:53.027  3140  3140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20b3f116, channel: 19, state: LISTENING
,08-24 17:07:53.027  3140  3140 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20b3f116, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c0f183e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d168a97mSocket: android.net.LocalSocket@389d3484 impl:android.net.LocalSocketImpl@2307c46d fd:FileDescriptor[74]
08-24 17:07:53.027  3140  3140 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@389d3484 impl:android.net.LocalSocketImpl@2307c46d fd:FileDescriptor[74]
08-24 17:07:53.027  3140  3233 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 17:07:53.027  3140  3233 D BluetoothAdapterProperties: mDiscovering is false
,08-24 17:07:53.037  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:07:53.037  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:53.037  1015  1364 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-24 17:07:53.037  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:53.037  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:07:53.037  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-24 17:07:53.037  3140  3233 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 17:07:53.037  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:53.037  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:53.037  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:53.047  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:07:53.047  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.047  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:07:53.047  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:53.047  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-24 17:07:53.047  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.047  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:07:53.047  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:07:53.057  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:07:53.057  1870  1870 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:07:53.057  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:53.057  1015  1334 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:07:53.057  1015  1364 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:07:53.057  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:07:53.067  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:53.067  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:53.067  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:53.067  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:53.067  1015  3992 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:53.067  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.077  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.077  1015  3992 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:53.077  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:53.077  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:53.077  3140  3236 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 17:07:53.087  3140  3236 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:07:53.087  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:07:53.087  1015  1094 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:07:53.087  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.087  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.097  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.097  3140  3233 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-24 17:07:53.097  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.097  3140  3233 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-24 17:07:53.097  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.097  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:07:53.097  3140  3233 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-24 17:07:53.097  3140  3233 E bt-btif : cmd socket is not created
08-24 17:07:53.097  3140  5151 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 17:07:53.097  3140  3233 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 17:07:53.097  6774  6891 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1206cfc0, channel: -1, state: INIT
08-24 17:07:53.097  6774  6891 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1206cfc0, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2eb324f9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@920cc3emSocket: android.net.LocalSocket@17260a9f impl:android.net.LocalSocketImpl@86927ec fd:FileDescriptor[105]
08-24 17:07:53.097  6774  6891 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17260a9f impl:android.net.LocalSocketImpl@86927ec fd:FileDescriptor[105]
08-24 17:07:53.097  3140  3259 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-24 17:07:53.097  3140  3259 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 17:07:53.097  6774  6891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1324)
,08-24 17:07:53.107  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:07:53.107  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:07:53.107  3140  3259 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 17:07:53.107  4063  4063 D BluetoothPbap: Proxy object disconnected
08-24 17:07:53.107  4063  4063 D PbapServerProfile: Bluetooth service disconnected
,08-24 17:07:53.117  3140  3140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@217608a2, channel: 5, state: LISTENING
08-24 17:07:53.117  3140  3140 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@217608a2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9c4669f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@52f3933mSocket: android.net.LocalSocket@8fb14f0 impl:android.net.LocalSocketImpl@34e93a69 fd:FileDescriptor[76]
08-24 17:07:53.117  3140  3140 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8fb14f0 impl:android.net.LocalSocketImpl@34e93a69 fd:FileDescriptor[76]
,08-24 17:07:53.117  3140  3140 I BtOppRfcommListener: stopping Accept Thread
08-24 17:07:53.117  3140  3140 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d500cee, channel: 12, state: LISTENING
08-24 17:07:53.117  3140  3140 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d500cee, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eaaf631, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d1a358fmSocket: android.net.LocalSocket@1c14901c impl:android.net.LocalSocketImpl@a521425 fd:FileDescriptor[80]
08-24 17:07:53.117  3140  3140 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c14901c impl:android.net.LocalSocketImpl@a521425 fd:FileDescriptor[80]
,08-24 17:07:53.117  3140  5151 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 17:07:53.117  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:07:53.117  3140  3140 V BluetoothOppManager: cleanUp...
,08-24 17:07:53.117  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:07:53.127  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:53.127  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 17:07:53.127  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 17:07:53.127  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.127  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.127  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.127  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.137  1015  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6906 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 17:07:53.147  6906  6906 E Zygote  : MountEmulatedStorage(),
08-24 17:07:53.147  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
08-24 17:07:53.147  6906  6906 E Zygote  : v2
08-24 17:07:53.147  6906  6906 I libpersona: KNOX_SDCARD checking this for 10055
08-24 17:07:53.147  6906  6906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:53.147  6906  6906 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:53.147  6906  6906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:53.147  6906  6906 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:53.177  6906  6906 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:53.177  6906  6906 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:53.207  6906  6906 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 17:07:53.247  6906  6906 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-24 17:07:53.247  6906  6906 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-24 17:07:53.247  6906  6906 D UserAnalysis: Create SecureDbHelper
,08-24 17:07:53.257  6906  6906 D IntelligenceServiceApplication: onCreate()
,08-24 17:07:53.267  1015  1553 I ActivityManager: Killing 6474:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-24 17:07:53.277  1015  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-24 17:07:53.277  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.277  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.277  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.277  6906  6906 D IntelligenceServiceApplication: no applications having user consent for prediction
08-24 17:07:53.277  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:53.297  1015  1477 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6924 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-24 17:07:53.297  6924  6924 E Zygote  : MountEmulatedStorage()
08-24 17:07:53.297  6924  6924 E Zygote  : v2,
08-24 17:07:53.297  6924  6924 I libpersona: KNOX_SDCARD checking this for 10105
08-24 17:07:53.297  6924  6924 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:53.297  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 17:07:53.297  6906  6906 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,08-24 17:07:53.297  6924  6924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:07:53.297  3140  3259 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-24 17:07:53.297  3140  3259 W bt-btif : ag scb idx 1 not allocated
08-24 17:07:53.297  3140  3259 W bt-btif : ag scb idx 2 not allocated
08-24 17:07:53.297  3140  3259 E bt-btif : BTA AG is already disabled, ignoring ...
,08-24 17:07:53.307  3140  3319 I bt_userial_mct: exiting userial_read_thread
08-24 17:07:53.307  3140  3319 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 17:07:53.307  3140  3236 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-24 17:07:53.307  3140  3261 I bt_vendor: hw_epilog_process
08-24 17:07:53.307  3140  3236 D bt_userial_mct: userial_close
08-24 17:07:53.307  3140  3236 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 17:07:53.307  6924  6924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:53.307  6924  6924 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:53.317  6906  6906 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 17:07:53.337  6924  6924 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:53.337  6924  6924 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:53.427  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:07:53.467   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:07:53.467   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:53.467  6924  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:07:53.487   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:07:53.487   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:53.487  6924  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:07:53.557  3140  3236 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 17:07:53.557  3140  3236 I bt_vendor: bluetooth satus is on
08-24 17:07:53.557  3140  3236 I bt_vendor: bt-vendor : resetting BT status
08-24 17:07:53.557  3140  3236 I bt_vendor: Starting hciattach daemon
08-24 17:07:53.557  3140  3236 I bt_vendor: try to set false
,08-24 17:07:53.557  3140  3236 I bt_vendor: Starting hciattach daemon,
,08-24 17:07:53.557  3140  3236 I bt_vendor: try to set false,
08-24 17:07:53.557  3140  3236 I bt_vendor: cleanup
08-24 17:07:53.567  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.557  3140  3259 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 17:07:53.567  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-24 17:07:53.557  3140  3236 I GKI_LINUX: GKI_exit_task 0 done
08-24 17:07:53.557  3140  3236 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 17:07:53.557  3140  3233 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 17:07:53.557  3140  3233 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:07:53.557  3140  3233 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-24 17:07:53.557  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-24 17:07:53.557  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 17:07:53.567  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-24 17:07:53.567  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.567  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.567  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.577  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-24 17:07:53.577  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:07:53.577  3140  3140 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:07:53.577  3140  3140 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 17:07:53.577  3140  3140 D BtGatt.GattService: stop()
08-24 17:07:53.577  3140  3140 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 17:07:53.577  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:07:53.577  1015  3992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.577  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.577  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.577  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.577  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.577  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.577  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 17:07:53.577  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-24 17:07:53.577  3140  3140 D HeadsetService: Received stop request...Stopping profile...
08-24 17:07:53.577  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:07:53.577  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.577  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.577  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.577  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.577  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.587  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.587  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-24 17:07:53.587  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:07:53.587  4063  4063 D HeadsetProfile: Bluetooth service disconnected
,08-24 17:07:53.587  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-24 17:07:53.587  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 17:07:53.587  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.587  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.587  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.587  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.587  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.587  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-24 17:07:53.587  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:07:53.587  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:07:53.587  1015  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.587  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.587  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-24 17:07:53.587  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.587  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.597  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-24 17:07:53.597  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 17:07:53.597  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:07:53.597  1015  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.597  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.597  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.597  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.597  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.597  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.597  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-24 17:07:53.597  3140  3233 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:07:53.597  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:07:53.597  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.597  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:53.597  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.597  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.597  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-24 17:07:53.597  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:07:53.607  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:53.607  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.607  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.607  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.607  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:07:53.607  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:53.607  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:07:53.607  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:07:53.607  3140  3233 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:07:53.607  3140  3233 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:07:53.607  3140  3233 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 17:07:53.607  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-24 17:07:53.607  3140  3140 D A2dpService: Received stop request...Stopping profile...
,08-24 17:07:53.607  3140  3250 D A2dpStateMachine: Exit Disconnected: -1
,08-24 17:07:53.617  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.617  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-24 17:07:53.617  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-24 17:07:53.617  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:07:53.617  3140  3140 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-24 17:07:53.617  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 17:07:53.617  4063  4063 D BluetoothA2dp: Proxy object disconnected
,08-24 17:07:53.617  4063  4063 D A2dpProfile: Bluetooth service disconnected
08-24 17:07:53.617  3140  3140 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 17:07:53.617  3140  3140 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:07:53.617  3140  3140 D HidService: Received stop request...Stopping profile...
08-24 17:07:53.617  3140  3140 D HidService: Stopping Bluetooth HidService
08-24 17:07:53.617  3140  3140 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:07:53.617  3140  3140 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-24 17:07:53.617  3140  3140 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:07:53.617  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.627  4063  4063 D BluetoothInputDevice: Proxy object disconnected
08-24 17:07:53.627  3140  3140 D HealthService: Received stop request...Stopping profile...
,08-24 17:07:53.627  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:07:53.627  4063  4063 D HidProfile: Bluetooth service disconnected
,08-24 17:07:53.627  3140  3140 D PanService: Received stop request...Stopping profile...
08-24 17:07:53.627  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.627  4063  4063 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:07:53.627  4063  4063 D PanProfile: Bluetooth service disconnected
08-24 17:07:53.627  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 17:07:53.627  3140  3140 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 17:07:53.627  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.627  4063  4063 D BluetoothMap: Proxy object disconnected
,08-24 17:07:53.627  3140  3140 D SapService: Received stop request...Stopping profile...
08-24 17:07:53.627  4063  4063 D MapProfile: Bluetooth service disconnected
08-24 17:07:53.627  3140  3140 D SapService: Stopping Bluetooth SapService
08-24 17:07:53.627  3140  3140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:07:53.627  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-24 17:07:53.627  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:07:53.627  3140  3140 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 17:07:53.627  3140  3140 D BluetoothA2dp: Proxy object disconnected
08-24 17:07:53.637  3140  3140 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-24 17:07:53.637  3140  3251 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 17:07:53.637  3140  3140 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:07:53.637  3140  3140 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:07:53.637  4063  4063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 17:07:53.637  4063  4063 D SapProfile: Bluetooth service disconnected
,08-24 17:07:53.637  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 17:07:53.637  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.637  3140  3140 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-24 17:07:53.637  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-24 17:07:53.637  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.637  3140  3140 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.637  3140  3140 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 17:07:53.637  3140  3140 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 17:07:53.637  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-24 17:07:53.637  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.637  3140  3140 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.637  3140  3140 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:07:53.637  3140  3140 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:07:53.637  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-24 17:07:53.637  3140  3140 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:07:53.637  3140  3140 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-24 17:07:53.637  3140  3140 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-24 17:07:53.637  3140  3140 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-24 17:07:53.637  3140  3140 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-24 17:07:53.637  3140  3233 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-24 17:07:53.637  3140  3233 D BluetoothAdapterProperties: Setting state to 10
08-24 17:07:53.637  3140  3233 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:07:53.637  3140  3233 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:07:53.637  3140  3233 D BluetoothAdapterService: updateAdapterState state is 10
08-24 17:07:53.637  3140  3233 D BluetoothAdapterService: Autoconnection is available 
,08-24 17:07:53.637  3140  3233 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 17:07:53.637  3140  3233 I BluetoothAdapterState: Entering OffState
08-24 17:07:53.637  4063  4077 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:07:53.637  4063  4074 D Bluetoothsap: onBluetoothStateChange: up=false
08-24 17:07:53.637  4063  4074 D Bluetoothsap: Unbinding service...
08-24 17:07:53.637  1438  1726 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:53.647  1438  1726 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:07:53.647  1176  1185 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  1176  1185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:07:53.647  6774  6782 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  6774  6782 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:07:53.647  6774  6782 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-24 17:07:53.647  6774  6782 D BluetoothLeAdvertiser: Exit stop advertising
08-24 17:07:53.647  6774  6782 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-24 17:07:53.647  6774  6782 D BluetoothLeScanner: Exiting stopAllScan
08-24 17:07:53.647  4063  4077 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 17:07:53.647  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:53.647  3140  3338 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:07:53.647  4063  4074 D BluetoothMap: onBluetoothStateChange: up=false
08-24 17:07:53.647  4063  4071 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 17:07:53.647  1421  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  1421  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:53.647  2041  2584 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  2041  2584 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:53.647  3140  3151 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  3140  3151 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:07:53.647  4063  4077 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:53.647  4063  4077 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:53.647  1427  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:53.657  1427  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:53.657  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:07:53.657  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 17:07:53.657  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-24 17:07:53.667  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:53.667  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,08-24 17:07:53.667  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:07:53.667  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:07:53.667  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:07:53.667  1176  1763 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
,08-24 17:07:53.667  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:53.667  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-24 17:07:53.667  1176  1763 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:07:53.677  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
,08-24 17:07:53.677  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:07:53.677  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:07:53.677  2041  2222 D BluetoothAdapter: 569280609: getState() :  mService = null. Returning STATE_OFF
08-24 17:07:53.677  2041  2222 D BluetoothAdapter: 569280609: getState() :  mService = null. Returning STATE_OFF
,08-24 17:07:53.677  1015  1474 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:07:53.677  1015  1554 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:53.677  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:53.687  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-24 17:07:53.687  1870  1870 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:07:53.687  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:53.687  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-24 17:07:53.687  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.687  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:53.687  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:07:53.687  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:07:53.697  3140  3236 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 17:07:53.697  3140  3140 I GKI_LINUX: GKI_exit_task 1 done
08-24 17:07:53.697  3140  3140 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-24 17:07:53.697  3140  3140 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 17:07:53.697  3140  3140 I art     : System.exit called, status: 0
,08-24 17:07:53.697  3140  3140 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=222 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=220 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=218 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.707  6924  6924 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:53.707  6924  6924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:53.717  1015  1474 I ActivityManager: Killing 6369:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-24 17:07:53.717  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-24 17:07:53.727  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-24 17:07:53.727  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 17:07:53.727  1015  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:07:53.727  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-24 17:07:53.727  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.727  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:53.727  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-24 17:07:53.737  4063  4063 D DockEventReceiver: finishStartingService: stopping service
08-24 17:07:53.737  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
08-24 17:07:53.737  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:53.747  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
08-24 17:07:53.747  1015  1028 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-24 17:07:53.747  1015  1028 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 17:07:53.747  1015  1028 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-24 17:07:53.747  1015  1028 W BroadcastQueue: android.os.TransactionTooLargeException
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-24 17:07:53.747  1015  1028 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:07:53.747  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
08-24 17:07:53.757  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.757  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.757  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.757  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:53.767  6961  6961 E Zygote  : MountEmulatedStorage()
08-24 17:07:53.767  6961  6961 E Zygote  : v2
08-24 17:07:53.767  6961  6961 I libpersona: KNOX_SDCARD checking this for 1002
08-24 17:07:53.767  6961  6961 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:53.767  1015  1028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6961 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-24 17:07:53.767  6961  6961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:53.767  6961  6961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:53.767  6961  6961 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:53.777  6924  6952 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 17:07:53.797  6961  6961 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:53.797  6961  6961 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:53.807  6961  6961 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 17:07:53.807  6961  6961 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:07:53.817  1015  3992 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:53.817  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.817  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:53.817  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 17:07:53.837  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-24 17:07:53.837  6961  6961 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
08-24 17:07:53.837  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:07:53.837   274   983 D CommandListener: Clearing all IP addresses on wlan0,
08-24 17:07:53.837  2041  3022 V NativeCrypto: Read error: ssl=0xb7a5b708: I/O error during system call, Connection timed out
08-24 17:07:53.837  2041  6896 I qtaguid : Untagging socket 66
08-24 17:07:53.837  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.837  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.837  2041  6896 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
08-24 17:07:53.837  2041  6896 I qtaguid : Untagging socket 65
08-24 17:07:53.837  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.847  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:53.847  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:07:53.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.847  2041  3022 V NativeCrypto: SSL shutdown failed: ssl=0xb7a5b708: I/O error during system call, Broken pipe
08-24 17:07:53.847  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.847  2041  6896 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
08-24 17:07:53.847  2041  3022 E GCM     : Wifi connection closed with errorCode 20
08-24 17:07:53.847  2041  6896 I qtaguid : Untagging socket 47
08-24 17:07:53.847  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.847  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.847  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:53.847  2041  6896 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:53.847  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3,
08-24 17:07:53.847  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:53.847  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:53.847  2041  6896 I qtaguid : Untagging socket 47
,08-24 17:07:53.847  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.847  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.847  2041  6896 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
08-24 17:07:53.847   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:53.847  2041  6896 I qtaguid : Untagging socket 47
08-24 17:07:53.847  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:07:53.847  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.857  2041  6896 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:53.857  2041  6896 I qtaguid : Untagging socket 47
08-24 17:07:53.857  2041  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-24 17:07:53.857  2041  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 17:07:53.857  2041  6896 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2041, getuid(): 10011
,08-24 17:07:53.857  1015  1474 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-24 17:07:53.857  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:07:53.867  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 17:07:53.867  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-24 17:07:53.867  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-24 17:07:53.867  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 17:07:53.867  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:07:53.867  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:07:53.867  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-24 17:07:53.867  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:53.867  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:07:53.867  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 17:07:53.877  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:53.867  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:53.867  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-24 17:07:53.867  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-24 17:07:53.867  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:53.867  1015  1738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.867  1015  1738 I qtaguid : Tagging socket 331 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-24 17:07:53.867  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:53.867  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:53.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.867  1015  1738 I qtaguid : Untagging socket 331
08-24 17:07:53.867  1015  1738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:53.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding GattService
,08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding HeadsetService
08-24 17:07:53.887  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding A2dpService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding HidService
,08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding HealthService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding PanService
,08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding SapService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding SapClientService
,08-24 17:07:53.887  6961  6961 D BtSettings.ProfileConfig: Adding HidDevService
08-24 17:07:53.887  6961  6961 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-24 17:07:53.887  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-24 17:07:53.887  1015  1334 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-24 17:07:53.887  1015  1334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.887  1015  1334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.887  1015  1334 D SettingsProvider: selectionArgs: false
08-24 17:07:53.887  1015  1334 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.887  1015  1334 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.887  1015  1334 D SettingsProvider: ret = -1
,08-24 17:07:53.887  1015  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-24 17:07:53.887  1015  1124 D WifiP2pService: P2pDisablingState
08-24 17:07:53.887  1015  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.887  1015  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.887  1015  1094 D SettingsProvider: selectionArgs: false
08-24 17:07:53.887  1015  1094 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.887  1015  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.887  1015  1094 D SettingsProvider: ret = -1
08-24 17:07:53.897  1015  1553 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-24 17:07:53.897  1015  1553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  1553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  1553 D SettingsProvider: selectionArgs: false
08-24 17:07:53.897  1015  1553 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.897  1015  1553 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  1553 D SettingsProvider: ret = -1
,08-24 17:07:53.897  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-24 17:07:53.897  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  1494 D SettingsProvider: selectionArgs: false
,08-24 17:07:53.897  1015  1494 D SettingsProvider: selectionArgs: 1002
,08-24 17:07:53.897  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  1494 D SettingsProvider: ret = -1
,08-24 17:07:53.897  1015  1364 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-24 17:07:53.897  1015  1364 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  1364 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  1364 D SettingsProvider: selectionArgs: false
08-24 17:07:53.897  1015  1364 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.897  1015  1364 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  1364 D SettingsProvider: ret = -1
,08-24 17:07:53.897  1015  3992 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-24 17:07:53.897  1015  3992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  3992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  3992 D SettingsProvider: selectionArgs: false
08-24 17:07:53.897  1015  3992 D SettingsProvider: selectionArgs: 1002
,08-24 17:07:53.897  1015  3992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  3992 D SettingsProvider: ret = -1
,08-24 17:07:53.897  1015  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-24 17:07:53.897  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-24 17:07:53.897  1015  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  1124 D WifiP2pService: p2p socket connection lost
08-24 17:07:53.897  1015  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  1474 D SettingsProvider: selectionArgs: false
08-24 17:07:53.897  1015  1474 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.897  1015  1124 D WifiP2pService: P2pDisabledState
08-24 17:07:53.897  1015  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  1474 D SettingsProvider: ret = -1
,08-24 17:07:53.897  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:07:53.897  1015  1028 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-24 17:07:53.897  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.897  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.897  1015  1028 D SettingsProvider: selectionArgs: false
08-24 17:07:53.897  1015  1028 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.897  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.897  1015  1028 D SettingsProvider: ret = -1
08-24 17:07:53.907  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:07:53.907  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.907  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.907  1015  1476 D SettingsProvider: selectionArgs: false,
08-24 17:07:53.907  1015  1476 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.907  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.907  1015  1476 D SettingsProvider: ret = -1
08-24 17:07:53.907  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:53.907  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.907  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.907  1015  1028 D SettingsProvider: selectionArgs: false
08-24 17:07:53.907  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-24 17:07:53.907  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.907  1015  1028 D SettingsProvider: ret = -1
,08-24 17:07:53.907  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:53.907  1015  1554 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-24 17:07:53.907  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:53.907  1015  1554 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.907  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-24 17:07:53.907  1015  1554 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.907  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:53.907  1015  1554 D SettingsProvider: selectionArgs: false
08-24 17:07:53.907  1015  1045 D WifiDisplayController: disconnect
08-24 17:07:53.907  1015  1554 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.907  1015  1045 D WifiDisplayController: updateConnection
08-24 17:07:53.907  1015  1554 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:53.907  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-24 17:07:53.907  1015  1554 D SettingsProvider: ret = -1
08-24 17:07:53.907  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 17:07:53.907  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:53.907  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:53.907  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:53.907  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:53.907  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-24 17:07:53.907  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 17:07:53.907  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:53.907  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:53.907  1015  1478 D SettingsProvider: selectionArgs: false
08-24 17:07:53.907  1015  1478 D SettingsProvider: selectionArgs: 1002
08-24 17:07:53.907  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:07:53.907  1015  1478 D SettingsProvider: ret = -1
,08-24 17:07:53.917  1015  1334 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 17:07:53.917  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 17:07:53.927  1015  1364 I ActivityManager: Killing 6505:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-24 17:07:53.937  1015  1094 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:53.937  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-24 17:07:53.937  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:53.937  1015  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:53.937  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:53.947  1362  1362 I wpa_supplicant: nl80211: Received scan results (11 BSSes)
,08-24 17:07:53.957  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-24 17:07:53.957  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-24 17:07:53.957  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:53.957   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-24 17:07:53.957   274   979 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-24 17:07:53.957  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-24 17:07:53.957   274   983 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:07:53.957  1015  1127 V NetworkStats: updateIfacesLocked()
08-24 17:07:53.957  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:53.957  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:53.957  2041  6896 I qtaguid : Untagging socket 47
08-24 17:07:53.957  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.957  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.957  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.957  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.957  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:53.957  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:53.957  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:53.967  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-24 17:07:53.967  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-24 17:07:53.967  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:07:53.967  1362  1362 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:53.967  1015  1127 V NetworkStats: performPollLocked() took 7ms
08-24 17:07:53.967  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:53.967  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:53.977  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:53.977  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:53.977  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:53.977  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:53.977  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:53.977  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-24 17:07:53.977  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:07:53.977  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:53.977  1176  1176 D HotspotTile: onReceive : 0, 0
,08-24 17:07:53.987  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:53.987  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:53.987  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:53.987  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:07:53.987  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-24 17:07:53.987  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:53.987  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:07:53.987  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:53.987  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:53.987  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:53.987  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:53.987  1015  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:53.987  1176  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-24 17:07:53.987  4792  6836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-24 17:07:53.987  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:07:53.987  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 17:07:53.987  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 17:07:53.997  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-24 17:07:53.997  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-24 17:07:53.997  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-24 17:07:53.997  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 17:07:53.997  1438  1438 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-24 17:07:53.997  1438  1438 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 17:07:53.997  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-24 17:07:53.997  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-24 17:07:53.997  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-24 17:07:53.997  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-24 17:07:53.997  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:53.997  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:53.997  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-24 17:07:54.007  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
08-24 17:07:54.007  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:54.007  1015  1122 V NetworkStats: updateIfacesLocked()
08-24 17:07:54.007  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:54.007  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:54.007  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-24 17:07:54.007  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-24 17:07:54.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.007  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-24 17:07:54.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-24 17:07:54.007  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-24 17:07:54.007  1015  1122 V NetworkStats: performPollLocked() took 8ms
08-24 17:07:54.017  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.017  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:54.017  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:54.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:54.017  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:07:54.017  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:54.057  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:07:54.057  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:54.057  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-24 17:07:54.057  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.057  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.057  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.067  2041  2041 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-24 17:07:54.067  2041  2041 E ctxmgr  : com.android.volley.NoConnectionError: java.net.ConnectException: failed to connect to www.googleapis.com/172.217.21.10 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:151)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at iss.performRequest(:com.google.android.gms:64)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.volley.NetworkDispatcher.run(:com.google.android.gms:113)
08-24 17:07:54.067  2041  2041 E ctxmgr  : Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/172.217.21.10 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at java.net.Socket.connect(Socket.java:882)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.volley.toolbox.HttpClientStack.performRequest(:com.google.android.gms:87)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at isr.performRequest(:com.google.android.gms:63)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:96)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	... 2 more
08-24 17:07:54.067  2041  2041 E ctxmgr  : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at libcore.io.Posix.connect(Native Method)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-24 17:07:54.067  2041  2041 E ctxmgr  : 	... 21 more
,08-24 17:07:54.077  2041  2225 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-24 17:07:54.077  2041  6986 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-24 17:07:54.077  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:07:54.077  1015  3992 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.087  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.087  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.087  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.097  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.097  1015  1334 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:54.097  1015  1334 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:54.097  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.107  1015  1334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.107  1015  1334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.107  1015  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:54.107  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.107  1015  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.107  1619  1619 I Hs20UtilService: Starting #8
08-24 17:07:54.107  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.107  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.107  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:07:54.107  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.107  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-24 17:07:54.107  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.107  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.107  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.117  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.117  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.117  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.117  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.117  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:07:54.117  2041  6986 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-24 17:07:54.127  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:54.127  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.127  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.127  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.127  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.127  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.127  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.127  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.137  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.137  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.137  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.137  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:54.137  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-24 17:07:54.137  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:54.137  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:54.137  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:54.137  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:54.137  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:54.137  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.137  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:54.137  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:54.137  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.147  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.147  1438  1438 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:54.147  1438  1438 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:54.147  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:07:54.147  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:54.157  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:07:54.157  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:07:54.157  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-24 17:07:54.157  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:54.157  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:54.157  1015  1334 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-24 17:07:54.157  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.157  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.157  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.157  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.167  7002  7002 E Zygote  : MountEmulatedStorage(),
08-24 17:07:54.167  1015  1334 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7002 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:54.167  7002  7002 E Zygote  : v2
08-24 17:07:54.167  7002  7002 I libpersona: KNOX_SDCARD checking this for 10064
,08-24 17:07:54.167  7002  7002 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:54.167  7002  7002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:54.177  7002  7002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:54.177  7002  7002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:54.197  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.197  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.197  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:54.197  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.197  7002  7002 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:54.197  7002  7002 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:54.207  1362  1362 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:54.217  7002  7002 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 17:07:54.237  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:54.237  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 17:07:54.267  1362  1362 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-24 17:07:54.267  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:54.267  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-24 17:07:54.267  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:54.267  7002  7002 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:07:54.267  1015  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-24 17:07:54.267  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.267  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.267  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.267  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.277  2041  6985 I art     : Explicit concurrent mark sweep GC freed 43921(2MB) AllocSpace objects, 6(237KB) LOS objects, 39% free, 11MB/18MB, paused 1.330ms total 69.023ms,
,08-24 17:07:54.287  7017  7017 E Zygote  : MountEmulatedStorage()
,08-24 17:07:54.287  7017  7017 E Zygote  : v2
08-24 17:07:54.287  7017  7017 I libpersona: KNOX_SDCARD checking this for 10065
08-24 17:07:54.287  7017  7017 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:54.287  7017  7017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:54.287  1362  1362 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-24 17:07:54.287  1015  1494 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7017 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:54.287  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.287  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.287  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:54.297  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.287  1362  1362 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-24 17:07:54.287  1015  1128 D Tethering: InitialState.processMessage what=4
08-24 17:07:54.287  1362  1362 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 17:07:54.287  1362  1362 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-24 17:07:54.287  1362  1362 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:54.297  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.297  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:54.297  1015  1128 E Tethering: No numeric data
08-24 17:07:54.297  7017  7017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:54.297  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:07:54.297  1015  1128 D Tethering: clearTetheredNotification()
,08-24 17:07:54.297  7017  7017 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:54.297  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.297  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:54.297  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:54.297  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:54.297  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.297  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.297  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:54.297  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:54.297  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:07:54.297  1015  1122 V NetworkStats: performPollLocked() took 4ms,
08-24 17:07:54.297  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:54.307  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:54.307  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:54.317  7017  7017 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:54.317  7017  7017 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:54.327  1015  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.327  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.327  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.327  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.347  7017  7017 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:54.347   267   267 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb86e37c8
08-24 17:07:54.347   267   267 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-24 17:07:54.347   267   267 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 17:07:54.347   267   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1200736120)
,08-24 17:07:54.357  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.357  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:54.357  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-24 17:07:54.357  1015  1554 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-24 17:07:54.357  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.357  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.357  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.367  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.377  1015  1554 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7035 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-24 17:07:54.377  1015  1554 I ActivityManager: Killing 6559:com.samsung.android.sm/1000 (adj 15): empty #21
,08-24 17:07:54.377  7035  7035 E Zygote  : MountEmulatedStorage()
08-24 17:07:54.377  7035  7035 E Zygote  : v2
08-24 17:07:54.377  7035  7035 I libpersona: KNOX_SDCARD checking this for 10102
08-24 17:07:54.377  7035  7035 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:54.387  7035  7035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:54.387  1015  1553 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.387  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.387  1015  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.387  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.387  2041  7034 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
08-24 17:07:54.387  2041  6985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 17:07:54.387  1015  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.387  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.387  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.387  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.387  7035  7035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:54.387  7035  7035 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:54.397   267   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-24 17:07:54.397   267   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-24 17:07:54.397   267   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1200736120) wakelock released: 1, error no: 0
08-24 17:07:54.397   267   358 I rmt_storage: 
,08-24 17:07:54.397   267   267 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb86e37c8
,08-24 17:07:54.407   305   305 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 30.725ms,
,08-24 17:07:54.417  7035  7035 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:54.417  7035  7035 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:54.427  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.427  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.427  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.427  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.427  2041  7034 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-24 17:07:54.427  2041  6985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-24 17:07:54.427  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.427  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.427  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.427  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:07:54.427   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 735us total 19.423ms
,08-24 17:07:54.437  7035  7035 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 17:07:54.447  1362  1362 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:54.447   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 18.244ms
,08-24 17:07:54.467  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:54.467  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.467  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.467  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:54.467  2041  7034 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 17:07:54.467  2041  6985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 17:07:54.467  2041  6985 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-24 17:07:54.477  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:07:54.477  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:54.477  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:54.477  1362  1362 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 17:07:54.497  2041  6985 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 17:07:54.497  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:54.507  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-24 17:07:54.517  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:54.517  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:54.517  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:07:54.527  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:54.527  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:07:54.577  1015  1476 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 17:07:54.577  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-24 17:07:54.577  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:07:54.587  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:54.587  2041  2222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:07:54.587  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-24 17:07:54.587  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.587  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:54.587  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.587  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.587  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:54.587  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:07:54.587  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:54.587  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 17:07:54.597  1176  1176 D HotspotTile: onReceive : 1, 0
,08-24 17:07:54.597  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.597  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.597  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:54.647  2041  6985 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:07:54.647   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:07:54.647   274   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 17:07:54.657  2041  6985 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-24 17:07:54.677  7035  7057 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-24 17:07:54.677  7035  7057 I Babel_SMS: MmsConfig.loadMmsSettings
,08-24 17:07:54.677  7035  7057 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-24 17:07:54.677  7035  7057 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 17:07:54.717  7035  7057 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-24 17:07:54.717  7035  7057 I Babel_SMS: MmsConfig.loadFromResources
,08-24 17:07:54.727  7035  7057 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-24 17:07:54.727  7035  7057 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-24 17:07:54.757  1015  1494 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-24 17:07:54.757  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-24 17:07:54.757  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.757  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:54.757  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 17:07:54.777  7035  7035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:07:54.777  7035  7035 I Babel_Crash: startup - clean
,08-24 17:07:54.817  1015  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:54.817  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:54.817  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.817  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.817  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:54.817  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:07:54.817  1619  1619 I Hs20UtilService: Starting #9
,08-24 17:07:54.817  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:07:54.817  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:54.827  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:54.827  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:07:54.827  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:54.827  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:07:54.827  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:54.827   287   287 E SMD     : DCD OFF
,08-24 17:07:54.837  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:54.837  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:54.837  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.837  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.837  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:54.847  1619  1619 I Hs20UtilService: Starting #10
,08-24 17:07:54.847  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:07:54.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:54.857  7035  7035 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:54.857  7035  7035 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 17:07:54.857  7035  7035 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 17:07:54.867  7035  7035 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-24 17:07:54.867  7035  7035 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-24 17:07:54.867  7035  7035 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-24 17:07:54.867  7035  7035 W AudioCapabilities: Unsupported mime audio/x-ima
,08-24 17:07:54.877  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:54.877  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:54.877  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 17:07:54.877  7035  7035 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 17:07:54.877  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:54.887  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:54.887  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:54.887  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.887  7035  7035 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 17:07:54.907  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.907  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.907  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.907  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.907  7035  7035 W VideoCapabilities: Unsupported mime video/wvc1
,08-24 17:07:54.917  7035  7035 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,08-24 17:07:54.917  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.917  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.917  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.917  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.917  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.927  7035  7035 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-24 17:07:54.927  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.927  7035  7035 W VideoCapabilities: Unsupported mime video/wvc1
,08-24 17:07:54.927  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.927  7035  7035 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 17:07:54.927  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.927  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.927  7035  7035 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-24 17:07:54.937  7035  7035 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-24 17:07:54.937  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.937  7035  7035 W VideoCapabilities: Unsupported mime video/mp43
,08-24 17:07:54.937  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.937  7035  7035 W VideoCapabilities: Unsupported mime video/sorenson
,08-24 17:07:54.937  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.937  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.947  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:54.947  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:54.947  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:54.947  7035  7035 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 17:07:54.947  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 17:07:54.947  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.947  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.947  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:54.947  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:54.957  7060  7060 E Zygote  : MountEmulatedStorage()
08-24 17:07:54.957  7060  7060 E Zygote  : v2
,08-24 17:07:54.967  7060  7060 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:54.967  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:54.967  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:54.967  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-24 17:07:54.967  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:54.967  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:54.977  7035  7035 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,08-24 17:07:54.987  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:54.987  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.007  7035  7035 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:55.007  7035  7035 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:55.007  7035  7035 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:55.017  7035  7035 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:55.017  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-24 17:07:55.017  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 17:07:55.017  7060  7060 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 17:07:55.017  1015  1334 I ActivityManager: Killing 6532:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-24 17:07:55.017  7035  7035 I vclib   : onServiceConnected
,08-24 17:07:55.037  7060  7060 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-24 17:07:55.037  7060  7060 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 17:07:55.037  7060  7060 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 17:07:55.037  7060  7060 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:55.037  1015  3992 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-24 17:07:55.037  7060  7075 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-24 17:07:55.037  1015  3992 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-24 17:07:55.037  1015  3992 I ActivityManager: Killing 6607:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-24 17:07:55.047  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-24 17:07:55.047  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.047  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.047  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.047  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.067  7077  7077 E Zygote  : MountEmulatedStorage(),
08-24 17:07:55.067  7077  7077 E Zygote  : v2
08-24 17:07:55.067  7077  7077 I libpersona: KNOX_SDCARD checking this for 10001,
08-24 17:07:55.067  7077  7077 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.067  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:55.067  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7077 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:55.067  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:55.067  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.067  1015  1554 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-24 17:07:55.077  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.077  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.077  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.077  1015  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.087  7092  7092 E Zygote  : MountEmulatedStorage()
,08-24 17:07:55.087  7092  7092 E Zygote  : v2
08-24 17:07:55.087  7092  7092 I libpersona: KNOX_SDCARD checking this for 10031
08-24 17:07:55.087  7092  7092 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.087  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:55.097  1015  1554 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7092 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-24 17:07:55.097  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.097  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.097  7077  7077 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.097  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.097  1793  1793 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-24 17:07:55.097  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-24 17:07:55.107  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.107  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.107  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.107  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.117  7103  7103 E Zygote  : MountEmulatedStorage()
,08-24 17:07:55.117  7103  7103 E Zygote  : v2
08-24 17:07:55.117  7103  7103 I libpersona: KNOX_SDCARD checking this for 10121
08-24 17:07:55.117  7103  7103 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.117  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.117  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.117  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7103 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-24 17:07:55.117  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.127  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.137  7092  7092 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:55.137  2602  2614 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-24 17:07:55.137  1793  1793 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-24 17:07:55.137  1793  1793 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-24 17:07:55.137  1793  1793 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-24 17:07:55.137  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-24 17:07:55.147  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.147  7103  7103 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.157  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 17:07:55.157  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-24 17:07:55.157  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-24 17:07:55.167  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.167  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.167  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.167  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.167  1015  1042 D Tethering: interfaceRemoved wlan0
08-24 17:07:55.167  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-24 17:07:55.167  7103  7103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:07:55.177  7103  7103 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 17:07:55.177  7103  7103 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:07:55.177  7122  7122 E Zygote  : MountEmulatedStorage(),
08-24 17:07:55.177  7122  7122 E Zygote  : v2
08-24 17:07:55.177  7122  7122 I libpersona: KNOX_SDCARD checking this for 10077
08-24 17:07:55.177  7122  7122 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.177  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.177  1015  1028 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7122 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:55.187  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.187  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.187  7103  7103 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:55.197  7092  7092 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-24 17:07:55.217  7103  7103 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-24 17:07:55.217  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.217  7122  7122 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.217  7103  7103 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-24 17:07:55.227  1015  1334 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-24 17:07:55.227  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.227  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.227  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.227  1015  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.237  7139  7139 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.237  7139  7139 E Zygote  : v2
08-24 17:07:55.237  7139  7139 I libpersona: KNOX_SDCARD checking this for 10141
08-24 17:07:55.237  7139  7139 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:55.237  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.247  1015  1334 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7139 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-24 17:07:55.247  1015  1334 I ActivityManager: Killing 6624:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-24 17:07:55.247  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 17:07:55.247  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.247  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.247  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.247  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.257  2781  7145 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-24 17:07:55.257  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.257  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.267  2781  7145 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-24 17:07:55.267  2781  7145 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
08-24 17:07:55.267  7147  7147 E Zygote  : MountEmulatedStorage(),
08-24 17:07:55.267  2781  7145 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-24 17:07:55.267  7147  7147 E Zygote  : v2
08-24 17:07:55.267  7147  7147 I libpersona: KNOX_SDCARD checking this for 10032,
08-24 17:07:55.267  7147  7147 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:55.267  2781  7145 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-24 17:07:55.267  7147  7147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.277  1015  1028 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7147 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:55.277  7147  7147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:55.277  7147  7147 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.287  1015  1042 D Tethering: interfaceRemoved p2p0
08-24 17:07:55.287  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 17:07:55.297  1015  1494 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-24 17:07:55.297  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.297  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.297  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.297  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.307  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.307  7139  7139 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.307  7168  7168 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.307  7168  7168 I libpersona: KNOX_SDCARD checking this for 1000,
08-24 17:07:55.307  7168  7168 E Zygote  : v2
08-24 17:07:55.307  7168  7168 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:55.307  7168  7168 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.317  7168  7168 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:55.317  7168  7168 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.317  1015  1494 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:07:55.317  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.317  1015  1494 I ActivityManager: Killing 6642:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-24 17:07:55.317  7147  7147 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.347  7139  7139 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-24 17:07:55.347  7139  7139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:07:55.347  7139  7139 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:07:55.347  7139  7139 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 17:07:55.357  7168  7168 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.357  7168  7168 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.367  1015  1094 I art     : Explicit concurrent mark sweep GC freed 51484(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.671ms total 179.609ms
,08-24 17:07:55.407  1015  1474 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.427  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.427  7147  7190 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-24 17:07:55.427  7147  7190 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-24 17:07:55.427  7147  7147 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-24 17:07:55.427  1015  1478 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-24 17:07:55.427  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.427  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.427  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.427  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.447  7147  7190 D SPPClientService: PushLog.txt file is not deleted.
08-24 17:07:55.447  7147  7190 D SPPClientService: PushLog.txt file is not deleted.
08-24 17:07:55.447  7147  7190 D SPPClientService: ============PushLog. stop!
,08-24 17:07:55.447  7194  7194 E Zygote  : MountEmulatedStorage()
,08-24 17:07:55.447  7194  7194 E Zygote  : v2
08-24 17:07:55.457  7194  7194 I libpersona: KNOX_SDCARD checking this for 10036
08-24 17:07:55.457  1015  1478 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7194 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:55.457  7194  7194 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.457  1015  1478 I ActivityManager: Killing 6571:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-24 17:07:55.457  7194  7194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.457  1015  1027 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-24 17:07:55.457  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.457  7194  7194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.457  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:55.457  7194  7194 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 17:07:55.457  1015  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-24 17:07:55.457  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-24 17:07:55.467  7168  7168 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-24 17:07:55.477  1015  1364 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.477  1015  1494 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.487  7194  7194 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.487  7194  7194 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.497  7147  7208 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-24 17:07:55.517  2041  2225 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-24 17:07:55.527  7194  7194 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@22039b2c
,08-24 17:07:55.527  2041  2225 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-24 17:07:55.537  1015  1553 I ActivityManager: Killing 6665:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-24 17:07:55.547  7194  7194 I SA      : [SSP] onCreated
,08-24 17:07:55.547  1015  1477 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-24 17:07:55.547  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.547  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.547  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.547  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.557  7217  7217 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.557  7217  7217 E Zygote  : v2
08-24 17:07:55.557  7217  7217 I libpersona: KNOX_SDCARD checking this for 10068
08-24 17:07:55.557  7217  7217 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.557  1015  1477 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7217 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-24 17:07:55.557  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.567  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:55.567  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.577  1015  3992 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.587  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.587  7217  7217 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.587  1015  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.607  7194  7194 I SA      : [TPM] There is no property file
,08-24 17:07:55.617  1015  1364 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-24 17:07:55.617  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.617  1015  3992 D RCPManagerService: exchangeData() failure , invalid userId,
08-24 17:07:55.617  7194  7194 I SA      : [SCU] isHaveSA() - false
,08-24 17:07:55.617  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.617  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:55.617  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
08-24 17:07:55.627  7194  7194 I SA      : [TPM] getModelProperty : null
08-24 17:07:55.627  7194  7194 I SA      : [TPM] getCSCProperty : null
,08-24 17:07:55.627  7194  7194 I SA      : [DM] FLOATING AMOLED FEATURE: true,
08-24 17:07:55.627  7194  7194 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-24 17:07:55.627  7194  7194 I SA      : [DM] TFT FEATURE: false
,08-24 17:07:55.637  7217  7217 D BadgeProvider: onCreate
08-24 17:07:55.637  1015  1553 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-24 17:07:55.637  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.637  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.637  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.637  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.637  7217  7217 D BadgeProvider: DatabaseHelper
,08-24 17:07:55.647  7194  7194 I SA      : [DM] init START,
,08-24 17:07:55.647  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:55.657  7237  7237 E Zygote  : MountEmulatedStorage()
,08-24 17:07:55.657  7237  7237 E Zygote  : v2
08-24 17:07:55.657  7237  7237 I libpersona: KNOX_SDCARD checking this for 10110
08-24 17:07:55.657  7237  7237 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.657  7237  7237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:55.657  7194  7194 I SA      : [DM] This device is not a Vodafone
,08-24 17:07:55.657  1015  1553 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7237 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-24 17:07:55.657  7237  7237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:07:55.667  1015  1474 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 17:07:55.667  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-24 17:07:55.667  7237  7237 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.667  7168  7168 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-24 17:07:55.667  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.667  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:55.667  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 17:07:55.677  1015  1553 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-24 17:07:55.677  7168  7168 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-24 17:07:55.677  7168  7168 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-24 17:07:55.687  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.687  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.687  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.687  1015  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.687  7168  7168 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-24 17:07:55.687  7168  7168 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-24 17:07:55.687  7168  7168 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-24 17:07:55.687  7035  7236 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-24 17:07:55.687  7217  7226 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-24 17:07:55.697  7237  7237 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.697   305   305 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 663us total 39.609ms
,08-24 17:07:55.707  7237  7237 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.717   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.524ms
,08-24 17:07:55.727   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.167ms,
,08-24 17:07:55.747  7252  7252 E Zygote  : MountEmulatedStorage(),
08-24 17:07:55.747  7252  7252 E Zygote  : v2
08-24 17:07:55.747  7252  7252 I libpersona: KNOX_SDCARD checking this for 10009
,08-24 17:07:55.747  7252  7252 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:55.747  1015  1553 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7252 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-24 17:07:55.747  7252  7252 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.747  1015  1553 I ActivityManager: Killing 6103:com.android.mms/u0a41 (adj 15): empty #21
08-24 17:07:55.747  7252  7252 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.747  1015  1476 I ActivityManager: Killing 6685:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-24 17:07:55.747  7252  7252 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.757  1015  1364 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-24 17:07:55.757  1015  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.757  1015  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.757  1015  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.757  1015  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.777  7252  7252 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.777  7252  7252 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.777  7267  7267 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.777  7267  7267 E Zygote  : v2
08-24 17:07:55.777  7267  7267 I libpersona: KNOX_SDCARD checking this for 10008
08-24 17:07:55.777  7267  7267 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.777  7267  7267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.787  7267  7267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.787  1015  1364 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7267 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:55.787  1015  1364 I ActivityManager: Killing 6702:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-24 17:07:55.787  7267  7267 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.787  1015  1364 I ActivityManager: Killing 6521:com.android.calendar/u0a131 (adj 15): empty #21
,08-24 17:07:55.797  7194  7194 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75),
08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-24 17:07:55.807  7194  7194 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-24 17:07:55.807  7194  7194 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-24 17:07:55.817  1015  1027 D CountryDetector: No listener is left
08-24 17:07:55.817  7217  7227 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-24 17:07:55.817  7217  7227 D BadgeProvider: sendNotify, [notify] : null
08-24 17:07:55.817  7217  7227 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-24 17:07:55.817  7217  7227 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-24 17:07:55.817  7217  7227 D BadgeProvider: update, [UpdateCount] : 1
,08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-24 17:07:55.817  1479  1479 D Launcher.Model: reloadBadges entered.
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-24 17:07:55.817  7194  7194 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-24 17:07:55.827  7194  7194 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-24 17:07:55.837  7194  7194 I SA      : [SCU] isHaveSA() - false
08-24 17:07:55.837  7194  7194 I SA      : support phone number id : false
08-24 17:07:55.837  7194  7194 I SA      : [DM] Supports Ref Jpn : true
,08-24 17:07:55.837  7194  7194 I SA      : [DM] init END
08-24 17:07:55.837  7194  7194 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-24 17:07:55.837  7267  7267 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.837  7267  7267 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.847  7194  7194 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-24 17:07:55.847  7194  7194 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-24 17:07:55.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:55.887  7194  7194 I SA      : [SLFUCHKMGR] constructor called
,08-24 17:07:55.897  7194  7194 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-24 17:07:55.897  7194  7194 I SA      : [OR] == isSIMCardReady false ==
,08-24 17:07:55.907  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-24 17:07:55.907  1015  1553 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-24 17:07:55.907  7194  7194 I SA      : [SCU] == networkStateCheck == false
,08-24 17:07:55.907  7194  7194 I SA      : [OR] onReceive END
08-24 17:07:55.907  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.917  1015  1494 I ActivityManager: Killing 6717:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-24 17:07:55.917  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.917  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:55.937  1015  1334 I ActivityManager: Killing 6061:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-24 17:07:55.937  2895  2895 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 17:07:55 GMT+02:00 2016
,08-24 17:07:55.937  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 17:07:55.937  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.937  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.937  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.937  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 17:07:55.937  2895  2895 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-24 17:07:55.947  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 17:07:55.947  2895  2895 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-24 17:07:55.947  2895  2895 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 17:07:55.947  2895  2895 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 17:07:55.947  1015  1334 I ActivityManager: Killing 5857:com.android.vending/u0a26 (adj 15): empty #21
,08-24 17:07:55.957  2895  7286 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-24 17:07:55.957  2895  7286 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-24 17:07:55.957  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:55.957  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.957  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.957  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:55.957  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:55.967  2895  7286 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-24 17:07:55.967  2895  7286 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-24 17:07:55.967  2895  2895 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-24 17:07:55.977  4792  7287 I iu.SyncManager: SYNC; picasa accounts
,08-24 17:07:55.997  4792  4792 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-24 17:07:56.027  1015  1478 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:07:56.027  1015  1478 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:07:56.027  1015  1478 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 17:07:56.027  1015  1478 D BatteryService: stay LED for fully charged
08-24 17:07:56.027  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:07:56.037  1015  1015 I MotionRecognitionService: Plugged
,08-24 17:07:56.037  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:07:56.037  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:56.037  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:07:56.037  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:07:56.037  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 17:07:56.037  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:07:56.047  1015  3992 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 17:07:56.047  1015  3992 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:07:56.047  1015  3992 D SecContentProvider2: mCursor = null
,08-24 17:07:56.047  1015  3992 D WifiService: setWifiEnabled: true pid=6774, uid=10171
08-24 17:07:56.047  1015  3992 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:07:56.047  1015  3992 W WifiService: Failed getting userId using ActivityManagerNative
08-24 17:07:56.047  1015  3992 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:07:56.047  1015  3992 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:07:56.047  1015  3992 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:07:56.047  1015  3992 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:07:56.047  1015  3992 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:07:56.047  1015  3992 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 17:07:56.047  1015  3992 D SettingsProvider: name = wifi_on
,08-24 17:07:56.057  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-24 17:07:56.067  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-24 17:07:56.067  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 17:07:56.067  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:07:56.207   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 17:07:56.207   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:56.207  7237  7293 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 17:07:56.217   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-24 17:07:56.217   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:56.217  7237  7237 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 17:07:56.217  7237  7237 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 17:07:56.217  7237  7237 I GAv4    :   adb logcat -s GAv4
,08-24 17:07:56.217  7237  7293 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-24 17:07:56.227   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 17:07:56.227   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:56.227  7237  7295 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 17:07:56.237   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-24 17:07:56.237   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:56.237  7237  7295 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-24 17:07:56.237  7237  7237 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:56.237  1015  3992 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:56.247  7237  7237 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:56.247  7237  7296 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:56.427  1015  1042 D Tethering: interfaceAdded wlan0
,08-24 17:07:56.437  1015  1128 E Tethering: No numeric data
,08-24 17:07:56.437  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 17:07:56.437  1015  1128 D Tethering: clearTetheredNotification()
,08-24 17:07:56.437  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:56.437  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:56.437  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:56.447  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:56.437  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:56.447  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:07:56.447  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:56.447  1015  1122 V NetworkStats: performPollLocked() took 4ms
,08-24 17:07:56.447  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:56.447  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:07:56.447  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:56.447  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:56.447  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:56.447  1015  1128 D Tethering: InitialState.processMessage what=4,
08-24 17:07:56.447  1015  1128 E Tethering: No numeric data,
08-24 17:07:56.447  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:07:56.457  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:56.447  1015  1128 D Tethering: clearTetheredNotification()
08-24 17:07:56.457  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:56.457  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:56.457  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:07:56.457  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:56.457  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:56.457  1015  1042 D Tethering: interfaceAdded p2p0
,08-24 17:07:56.457  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-24 17:07:56.457  1015  1122 V NetworkStats: performPollLocked() took 4ms
08-24 17:07:56.457  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:56.457  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:56.457  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:56.457  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:56.457  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:56.457  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:56.457   274   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-24 17:07:56.457   274   983 D SoftapController: Softap fwReload - Ok
,08-24 17:07:56.467   274   983 D CommandListener: Setting iface cfg
08-24 17:07:56.467   274   983 D CommandListener: Trying to bring down wlan0
,08-24 17:07:56.467   274   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:56.467  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-24 17:07:56.467  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 17:07:56.477  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-24 17:07:56.477  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:56.477  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:56.477  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.477  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.477  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.477  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:56.477  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:56.477  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-24 17:07:56.477  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:56.477  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 17:07:56.487  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:56.487  1176  1176 D HotspotTile: onReceive : 2, 0
,08-24 17:07:56.487  7237  7237 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-24 17:07:56.487  1015  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:56.487  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.487  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.487  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:56.487  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-24 17:07:56.487  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.507  7237  7237 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6765-6768)
,08-24 17:07:56.507  7237  7237 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 17:07:56.537  7237  7237 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d168a97},
08-24 17:07:56.537  7237  7237 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 17:07:56.537  7237  7237 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 17:07:56.537  7318  7318 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-24 17:07:56.537  7318  7318 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 17:07:56.537  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-24 17:07:56.547  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-24 17:07:56.557   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7318
08-24 17:07:56.557   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-24 17:07:56.557  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-24 17:07:56.557  7318  7318 I wpa_supplicant: ssSupport state is = 1
08-24 17:07:56.557  7318  7318 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 17:07:56.557  7318  7318 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-24 17:07:56.557   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7318
08-24 17:07:56.557   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-24 17:07:56.557  7237  7237 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 17:07:56.557  7237  7237 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:56.557  7237  7237 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:07:56.577  7237  7237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:56.577  7237  7237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:56.577  7237  7237 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:56.577  7237  7237 I Adreno-EGL: Local Branch: 
08-24 17:07:56.577  7237  7237 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:56.577  7237  7237 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:56.577  7237  7237 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:56.667  7237  7237 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:56.667  7237  7333 W cr.media: Requires BLUETOOTH permission
,08-24 17:07:56.687  7237  7237 I NSApplication: Starting up...
,08-24 17:07:56.687  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:56.687  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:56.697  1015  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-24 17:07:56.697  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.697  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.697  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.697  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.717  7338  7338 E Zygote  : MountEmulatedStorage()
,08-24 17:07:56.717  7338  7338 E Zygote  : v2
08-24 17:07:56.717  7338  7338 I libpersona: KNOX_SDCARD checking this for 10117
08-24 17:07:56.717  7338  7338 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:56.717  7338  7338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:56.717  1015  1494 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7338 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:56.717  1015  1494 I ActivityManager: Killing 6906:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21,
,08-24 17:07:56.727  7338  7338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:56.727  7338  7338 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.747  7338  7338 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:56.747  7338  7338 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.757   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-24 17:07:56.757  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-24 17:07:56.767  7338  7338 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:07:56.807  7318  7318 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-24 17:07:56.807  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:56.817  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-24 17:07:56.817   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
08-24 17:07:56.817   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:07:56.817  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:56.817  7318  7318 I wpa_supplicant: ssSupport state is = 1
08-24 17:07:56.817  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-24 17:07:56.827  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-24 17:07:56.827  7318  7318 E wpa_supplicant: SIM READ ERROR
08-24 17:07:56.827  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:56.827  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:56.827  7318  7318 E wpa_supplicant: SIM READ ERROR
08-24 17:07:56.827  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
08-24 17:07:56.827  7318  7318 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:07:56.827  7318  7318 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 17:07:56.827  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:56.827  7318  7318 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-24 17:07:56.827  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:56.827  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:56.827  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:07:56.827  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:56.827  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:56.827  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:56.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:56.927  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-24 17:07:57.067  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-24 17:07:57.067  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:57.087  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-24 17:07:57.087   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
08-24 17:07:57.087   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:07:57.087  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:57.087  7318  7318 I wpa_supplicant: ssSupport state is = 1
,08-24 17:07:57.097  7318  7318 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-24 17:07:57.097  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:57.107  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-24 17:07:57.107   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7318
08-24 17:07:57.107   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-24 17:07:57.107  7318  7318 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:57.107  7318  7318 I wpa_supplicant: ssSupport state is = 1
08-24 17:07:57.107  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:57.107  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-24 17:07:57.107  7318  7318 E wpa_supplicant: SIM READ ERROR
08-24 17:07:57.107  7318  7318 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:07:57.107  7318  7318 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-24 17:07:57.107  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:07:57.117  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:57.117  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:57.117  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:57.117  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:57.117  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:57.117  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:57.127  1015  1027 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-24 17:07:57.127  1015  1027 I ActivityManager: Killing 6961:com.android.bluetooth/1002 (adj 15): empty #21
,08-24 17:07:57.137  1015  1554 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:57.137  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:57.137  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:57.137  1015  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:57.137  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:57.147  1619  1619 I Hs20UtilService: Starting #11
,08-24 17:07:57.147  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:57.147  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:57.147  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:57.147  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:57.147  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:07:57.157  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:57.157  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:57.157  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:57.157  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:57.157  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:57.157  1619  1619 I Hs20UtilService: Starting #12
,08-24 17:07:57.157  1619  1635 I Hs20UtilService: Message received 5011,
08-24 17:07:57.157  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:57.157  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:57.157  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:57.157  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:57.217  7318  7318 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-24 17:07:57.217  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 17:07:57.307  7318  7318 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-24 17:07:57.307  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-24 17:07:57.307  7318  7318 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 17:07:57.447  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:07:57.447  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:57.447  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:57.477  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-24 17:07:57.487  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:07:57.487  7318  7318 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-24 17:07:57.487  7318  7318 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-24 17:07:57.487  7318  7318 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:57.487  7318  7318 E wpa_supplicant: SIM READ ERROR,
08-24 17:07:57.487  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:57.507  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-24 17:07:57.527  7318  7318 I wpa_supplicant: Skip scan - bUseNetwork false,
08-24 17:07:57.527  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:57.527  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
08-24 17:07:57.527  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-24 17:07:57.527  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:57.527  1176  1176 D HotspotTile: onReceive : 3, 0
08-24 17:07:57.527  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:57.527  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:57.527  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:57.527  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:57.527  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:57.527  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:57.527  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-24 17:07:57.537  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:57.537  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:07:57.537  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:57.537  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:57.537  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:57.537  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:07:57.537  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:57.537  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:57.537  1015  1553 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:57.537  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:07:57.537  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:57.537  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:57.537  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:07:57.547  1619  1619 I Hs20UtilService: Starting #13
08-24 17:07:57.547  1619  1635 I Hs20UtilService: Message received 5011
08-24 17:07:57.547  1015  1125 E WifiConfigStore: Not a HS20
08-24 17:07:57.547  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 17:07:57.547  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
08-24 17:07:57.547  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:57.547  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:57.547  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:57.547  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-24 17:07:57.547  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-24 17:07:57.547  7318  7318 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 17:07:57.547  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-24 17:07:57.557  7318  7318 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:07:57.557  7318  7318 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 17:07:57.557  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 17:07:57.557  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-24 17:07:57.557  7318  7318 I wpa_supplicant: First Scan Start
08-24 17:07:57.557  7318  7318 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-24 17:07:57.557  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
08-24 17:07:57.557  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:07:57.557  1015  1125 I WifiNative-HAL: startHal
08-24 17:07:57.557  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d33d88c
08-24 17:07:57.557  1015  1125 I WifiNative-HAL: Could not start hal
08-24 17:07:57.557  7035  7035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:07:57.567  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:07:57.567  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-24 17:07:57.567  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
08-24 17:07:57.567  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:07:57.567  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:57.567  1015  1147 I WifiNative-HAL: startHal
08-24 17:07:57.567  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e3e59bc
08-24 17:07:57.567  1015  1147 I WifiNative-HAL: Could not start hal
08-24 17:07:57.567  1015  1147 E WifiScanningService: could not start HAL
08-24 17:07:57.567  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-24 17:07:57.567  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:57.567  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:07:57.567  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:07:57.567  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-24 17:07:57.567   274   983 D CommandListener: Setting iface cfg
08-24 17:07:57.567   274   983 D CommandListener: Trying to bring up p2p0
08-24 17:07:57.577  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 17:07:57.577  1015  1124 D WifiP2pService: P2pEnablingState
08-24 17:07:57.577  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 17:07:57.577  1015  1124 D WifiP2pService: P2p socket connection successful
08-24 17:07:57.577  1015  1124 D WifiP2pService: P2pEnabledState
08-24 17:07:57.577  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:07:57.577  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:07:57.577  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-24 17:07:57.577  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 17:07:57.577  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 17:07:57.577  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:07:57.577  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:57.577  7318  7318 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-24 17:07:57.577  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-24 17:07:57.577  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-24 17:07:57.577  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-24 17:07:57.577  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:57.577  1015  1045 D WifiDisplayController: disconnect
08-24 17:07:57.577  1015  1045 D WifiDisplayController: updateConnection
08-24 17:07:57.577  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:57.577  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:57.577  1015  1125 D SecContentProvider2: mCursor = null
08-24 17:07:57.577  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 17:07:57.587  1015  1473 I ActivityManager: Killing 6924:com.google.android.apps.maps/u0a105 (adj 15): empty #21
08-24 17:07:57.587  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-24 17:07:57.587  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-24 17:07:57.587  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
08-24 17:07:57.587  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:07:57.587  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:57.587  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:57.587  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:57.587  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 17:07:57.587  1015  1364 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 17:07:57.587  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  secondary type: null
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  wps: 0
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  grpcapab: 0
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  devcapab: 0
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  status: 3
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  wfdInfo: null
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-24 17:07:57.587  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-24 17:07:57.587  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-24 17:07:57.597  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 17:07:57.597  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:07:57.597  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:57.597  1015  1125 D SecContentProvider2: mCursor = null
08-24 17:07:57.597  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:07:57.597  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:57.597  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:57.597  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:57.597  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-24 17:07:57.597  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-24 17:07:57.597  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-24 17:07:57.597  7002  7002 D FileShare-Client: Outbound.stopDelayTimer - 
08-24 17:07:57.607  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
08-24 17:07:57.607  1015  1124 D WifiP2pService: InactiveState
08-24 17:07:57.607  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:07:57.607  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
08-24 17:07:57.607  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 17:07:57.607  7017  7017 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:57.607  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:07:57.607  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:07:57.827   287   287 E SMD     : DCD OFF
,08-24 17:07:57.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:58.787  7318  7318 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
08-24 17:07:58.787  7318  7318 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-24 17:07:58.787  7318  7318 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-24 17:07:58.787  7318  7318 I wpa_supplicant: Trying to associate with  'G700',
08-24 17:07:58.787  7318  7318 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-24 17:07:58.787  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-24 17:07:58.787  1015  7365 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-24 17:07:58.807  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-24 17:07:58.807  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:58.857   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 17:07:58.907  7318  7318 E wpa_supplicant: Cmd 35605 not handled
,08-24 17:07:58.907  7318  7318 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-24 17:07:58.907  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:07:58.907  7318  7318 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-24 17:07:58.907  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:58.907  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-24 17:07:58.907  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:58.907  7318  7318 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-24 17:07:58.907  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-24 17:07:58.907  7318  7318 I wpa_supplicant: Associated with F4.99.3E
08-24 17:07:58.907  7318  7318 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-24 17:07:58.907  7318  7318 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-24 17:07:58.917  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:58.907  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-24 17:07:58.907  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 17:07:58.907  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-24 17:07:58.917  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:07:58.917  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-24 17:07:58.917  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:58.917  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
,08-24 17:07:58.917  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:07:58.927  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:58.917  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-24 17:07:58.927  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:07:58.917  1015  1128 E Tethering: No numeric data
08-24 17:07:58.927  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:07:58.917  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:07:58.927  1015  1122 V NetworkStats: performPollLocked() took 10ms
08-24 17:07:58.917  1015  1128 D Tethering: clearTetheredNotification()
08-24 17:07:58.917  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.917  7318  7318 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 17:07:58.917  7318  7318 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-24 17:07:58.917  7318  7318 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-24 17:07:58.917  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:07:58.917  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:58.917  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:58.927  7318  7318 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:07:58.927  7318  7318 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 17:07:58.927  7318  7318 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-24 17:07:58.927  7318  7318 I wpa_supplicant: Blacklist: Clear (temp) 
08-24 17:07:58.927  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-24 17:07:58.927  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:07:58.927  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-24 17:07:58.927  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:58.927  1015  1125 D SecContentProvider2: mCursor = null
08-24 17:07:58.927  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.927  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.927  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.927  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:58.927  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:58.937  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-24 17:07:58.937  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-24 17:07:58.947  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:58.947  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:58.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:58.947  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-24 17:07:58.947  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:07:58.947  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-24 17:07:58.947  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:58.947  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:58.947  1015  1334 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:58.947  1015  1334 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:58.947  1015  1334 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:58.947  1015  1334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:58.947  1015  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:58.947  1619  1619 I Hs20UtilService: Starting #14
,08-24 17:07:58.947  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:07:58.957  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:07:58.957  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:07:58.957  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:58.957  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:58.957  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:07:58.957  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:58.957  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:58.957  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:58.967   274   983 D CommandListener: Setting iface cfg
,08-24 17:07:58.977  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-24 17:07:58.977  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:07:58.977  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:58.987  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:58.987  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:58.987  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.987  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.987  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.987  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:58.987  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:07:58.997  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:58.997  1015  1125 E WifiNative-wlan0: do suspend false
,08-24 17:07:58.997  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-24 17:07:58.997  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:07:59.057  1015  1554 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:07:59.057  1015  1554 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:07:59.057  1015  1554 D SecContentProvider2: mCursor = null
,08-24 17:07:59.067  1015  1554 D WifiService: setWifiEnabled: false pid=6774, uid=10171
,08-24 17:07:59.067  1015  1554 D SettingsProvider: name = wifi_on
,08-24 17:07:59.067  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:07:59.087  1015  1125 E WifiNative-wlan0: do suspend true,
,08-24 17:07:59.107  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
,08-24 17:07:59.107  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:07:59.117   274   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:59.117  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:59.117  1015  1124 D WifiP2pService: InactiveState{ what=131204 },
08-24 17:07:59.117  1015  1127 E ConnectivityService: updateNetworkInfo(),
08-24 17:07:59.117  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 },
08-24 17:07:59.117  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:07:59.117  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:59.117  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:07:59.117  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-24 17:07:59.117   274   983 E Netd    : no such netId 503
08-24 17:07:59.127  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-24 17:07:59.127  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:59.127  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.127  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.127  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.127  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.127  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-24 17:07:59.127  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 17:07:59.127  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-24 17:07:59.127  1015  1127 V NetworkStats: updateIfacesLocked()
08-24 17:07:59.127  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:59.127  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:07:59.127  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 17:07:59.127  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:59.137  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 17:07:59.137  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:07:59.137  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:59.137  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:07:59.137  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-24 17:07:59.137  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:07:59.137  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.147  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.147  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.147  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.147  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:07:59.147  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:59.147  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:59.147  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 17:07:59.147  1015  1127 V NetworkStats: performPollLocked() took 21ms
08-24 17:07:59.147  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:59.147  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-24 17:07:59.147  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-24 17:07:59.157  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-24 17:07:59.157  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:59.157  1015  1045 D WifiDisplayController: disconnect
08-24 17:07:59.157  1015  1045 D WifiDisplayController: updateConnection
08-24 17:07:59.157  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:59.157  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:59.157  1015  7369 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
,08-24 17:07:59.157  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503],
,08-24 17:07:59.157  1015  7369 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 17:07:59.157  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
08-24 17:07:59.157  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit(),
08-24 17:07:59.157  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 17:07:59.157  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:59.157  1015  1334 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:59.157  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow(),
,08-24 17:07:59.157  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-24 17:07:59.157  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:59.157  1015  1494 I ActivityManager: Killing 7060:com.sec.pcw.device/1000 (adj 15): empty #21
08-24 17:07:59.157  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-24 17:07:59.167  1015  1124 D WifiP2pService: P2pDisablingState
08-24 17:07:59.157  1015  1127 E ConnectivityService: updateNetworkInfo(),
08-24 17:07:59.167  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-24 17:07:59.167  1015  1124 D WifiP2pService: p2p socket connection lost
08-24 17:07:59.167  1015  1124 D WifiP2pService: P2pDisabledState
,08-24 17:07:59.167  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:07:59.167  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-24 17:07:59.167  1015  1553 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:59.167  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:59.167  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:59.167  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:59.167  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.167  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:59.167  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:59.167  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:59.177  1619  1619 I Hs20UtilService: Starting #15
,08-24 17:07:59.177  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:07:59.177  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:07:59.177  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:59.177  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:59.177  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:59.177  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:59.177  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:07:59.177  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:59.187  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:07:59.187  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:07:59.187  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:07:59.187  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:59.187  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:59.187  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:59.187  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:59.197  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:59.197  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-24 17:07:59.197  7002  7002 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:07:59.197  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-24 17:07:59.197  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-24 17:07:59.207   274   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:59.207  7017  7017 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:59.207  7318  7318 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:59.207  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:59.207  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:59.207  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.207  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.207  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.207  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.217  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:07:59.217  7372  7372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-24 17:07:59.217  7372  7372 I dhcpcd  : version 5.5.6 starting
,08-24 17:07:59.227  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:59.227  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:59.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.227  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:59.227  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:07:59.227  7372  7372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-24 17:07:59.237  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:59.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:59.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:59.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-24 17:07:59.237  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 17:07:59.237  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-24 17:07:59.237  1176  1176 D HotspotTile: onReceive : 0, 0,
,08-24 17:07:59.247  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:59.247  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:07:59.247  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.247  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:59.247  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:59.247  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:07:59.247  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.247  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:07:59.257  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:59.257  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.257  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:59.257  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:59.257  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:07:59.257  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:07:59.257  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:07:59.257  1619  1619 I Hs20UtilService: Starting #16
,08-24 17:07:59.267  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:07:59.267  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:07:59.267  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:59.267  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:59.267  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:59.267  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:59.277  1015  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:59.277  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.277  1015  1473 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:59.277  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 17:07:59.277  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:07:59.277  1619  1619 I Hs20UtilService: Starting #17
08-24 17:07:59.277  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:59.277  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:59.277  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:59.277  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-24 17:07:59.277  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:07:59.297  7372  7372 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-24 17:07:59.297  7372  7372 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-24 17:07:59.297  7372  7372 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-24 17:07:59.297  7372  7372 I dhcpcd  : bssid match,
08-24 17:07:59.297  7372  7372 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-24 17:07:59.337  7318  7318 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:59.387  7372  7372 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-24 17:07:59.427  7372  7372 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-24 17:07:59.457  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-24 17:07:59.457  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:59.457  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:59.457  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:59.487  7318  7318 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-24 17:07:59.487  7318  7318 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-24 17:07:59.487  7318  7318 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 17:07:59.487  7318  7318 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-24 17:07:59.487  7318  7318 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:59.487  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 17:07:59.487  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.487  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:59.487  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:07:59.487  1015  1128 D Tethering: InitialState.processMessage what=4
08-24 17:07:59.487  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.487  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:59.497  1015  1128 E Tethering: No numeric data
08-24 17:07:59.497  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:07:59.497  1015  1128 D Tethering: clearTetheredNotification()
,08-24 17:07:59.497  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
08-24 17:07:59.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:59.507  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:59.507  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:59.507  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:59.507  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:07:59.507  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.507  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.507  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:59.507  1015  1122 V NetworkStats: performPollLocked() took 5ms
,08-24 17:07:59.507  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:59.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:07:59.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:59.837  7318  7318 I wpa_supplicant: Blacklist: Clear (all) ,
,08-24 17:07:59.907  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:07:59.907  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.907  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:59.977  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:07:59.977  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.977  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
,08-24 17:07:59.987  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 17:07:59.987  1015  1093 V AlarmManager: waitForAlarm result :8,
,08-24 17:08:00.087  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-24 17:08:00.087  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-24 17:08:00.087  7035  7035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:00.097  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:00.097  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:08:00.097  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.097  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:08:00.097  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.097  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.097  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:00.097  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-24 17:08:00.097  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 17:08:00.097  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-24 17:08:00.097  1176  1176 D HotspotTile: onReceive : 1, 0
,08-24 17:08:00.107  2041  2222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:00.107  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:00.107  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:00.107  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:00.117  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:08:00.117  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:00.117  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:00.117  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:00.117  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:00.127  1619  1619 I Hs20UtilService: Starting #18
,08-24 17:08:00.127  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:08:00.127  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:08:00.127  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:00.127  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:08:00.127  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:08:00.777   274   977 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-24 17:08:00.787  1015  1042 D Tethering: interfaceRemoved wlan0
08-24 17:08:00.787  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-24 17:08:00.837   287   287 E SMD     : DCD OFF
,08-24 17:08:00.977  1015  1042 D Tethering: interfaceRemoved p2p0
,08-24 17:08:00.977  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 17:08:01.787  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 17:08:02.067  6774  6828 D BluetoothAdapter: enable(),
,08-24 17:08:02.077  1015  1334 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:08:02.077  1015  1334 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688),
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 17:08:02.077  1015  1334 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 17:08:02.077  1015  1334 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-24 17:08:02.077  1015  1334 D SettingsProvider: name = bluetooth_on
08-24 17:08:02.077  1015  1334 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:02.087  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-24 17:08:02.087  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:02.087  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-24 17:08:02.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
08-24 17:08:02.087  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:02.087  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 17:08:02.087  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 17:08:02.087  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:02.107  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7403 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-24 17:08:02.107  7403  7403 E Zygote  : MountEmulatedStorage(),
08-24 17:08:02.107  7403  7403 E Zygote  : v2
08-24 17:08:02.107  7403  7403 I libpersona: KNOX_SDCARD checking this for 1002
08-24 17:08:02.107  7403  7403 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:02.107  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:02.117  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:08:02.117  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:02.137  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:02.137  7403  7403 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:02.157  7403  7403 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 17:08:02.157  7403  7403 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:08:02.177  7403  7403 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding GattService
,08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding HeadsetService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding A2dpService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding HidService
,08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding HealthService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding PanService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding SapService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding SapClientService,
08-24 17:08:02.207  7403  7403 D BtSettings.ProfileConfig: Adding HidDevService
08-24 17:08:02.207  7403  7403 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-24 17:08:02.217  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-24 17:08:02.217  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1478 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1478 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1478 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-24 17:08:02.217  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1494 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1494 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1494 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:02.217  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1477 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1477 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1477 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1364 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-24 17:08:02.217  1015  1364 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1364 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1364 D SettingsProvider: selectionArgs: false
,08-24 17:08:02.217  1015  1364 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1364 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1364 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1553 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-24 17:08:02.217  1015  1553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1553 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1553 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1553 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1553 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-24 17:08:02.217  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-24 17:08:02.217  1015  1027 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1027 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1027 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-24 17:08:02.217  1015  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1094 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1094 D SettingsProvider: selectionArgs: 1002
,08-24 17:08:02.217  1015  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1094 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-24 17:08:02.217  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.217  1015  1476 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  1476 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.217  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.217  1015  1476 D SettingsProvider: ret = -1
,08-24 17:08:02.217  1015  3992 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
08-24 17:08:02.217  1015  3992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.217  1015  3992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-24 17:08:02.217  1015  3992 D SettingsProvider: selectionArgs: false
08-24 17:08:02.217  1015  3992 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.227  1015  3992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.227  1015  3992 D SettingsProvider: ret = -1
,08-24 17:08:02.227  1015  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:02.227  1015  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.227  1015  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.227  1015  1473 D SettingsProvider: selectionArgs: false
08-24 17:08:02.227  1015  1473 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.227  1015  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:02.227  1015  1473 D SettingsProvider: ret = -1
08-24 17:08:02.227  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.227  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.227  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-24 17:08:02.227  1015  1028 D SettingsProvider: selectionArgs: false
08-24 17:08:02.227  1015  1028 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.227  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.227  1015  1028 D SettingsProvider: ret = -1
,08-24 17:08:02.227  1015  1334 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-24 17:08:02.227  1015  1334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.227  1015  1334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-24 17:08:02.227  1015  1334 D SettingsProvider: selectionArgs: false
08-24 17:08:02.227  1015  1334 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.227  1015  1334 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.227  1015  1334 D SettingsProvider: ret = -1
,08-24 17:08:02.247  7403  7403 D BluetoothAdapterState: make
,08-24 17:08:02.247  7403  7418 I BluetoothAdapterState: Entering OffState,
08-24 17:08:02.247  7403  7403 I bluedroid: init
,08-24 17:08:02.257  7403  7403 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-24 17:08:02.257  7403  7403 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 17:08:02.257  7403  7403 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 17:08:02.257  7403  7403 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
,08-24 17:08:02.257  7403  7403 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-24 17:08:02.257  7403  7403 I bluedroid: get_profile_interface socket
08-24 17:08:02.257  7403  7403 I bluedroid: get_profile_interface map_client
08-24 17:08:02.257  7403  7421 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-24 17:08:02.257  7403  7421 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-24 17:08:02.257  7403  7421 E BluetoothServiceJni: populateRssiValuesNative
08-24 17:08:02.257  7403  7421 I bluedroid: getModelRssiValues
08-24 17:08:02.257  7403  7421 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
08-24 17:08:02.257  7403  7421 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 17:08:02.257  7403  7403 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-24 17:08:02.257  7403  7421 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-24 17:08:02.267  1015  1015 D SettingsProvider: name = bluetooth_name
,08-24 17:08:02.267  7403  7403 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:02.267  1015  3992 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:02.267  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.267  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.267  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.267  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.277  7403  7411 I bluedroid: config_hci_snoop_log,
,08-24 17:08:02.277  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-24 17:08:02.277  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-24 17:08:02.277  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-24 17:08:02.287  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-24 17:08:02.287  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-24 17:08:02.287  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 17:08:02.287  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:02.287  7403  7403 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-24 17:08:02.287  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-24 17:08:02.297  7403  7418 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-24 17:08:02.297  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-24 17:08:02.297  7403  7418 D BluetoothAdapterProperties: Setting state to 11
,08-24 17:08:02.297  7403  7418 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 17:08:02.297  7403  7418 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:02.297  7403  7418 D BluetoothAdapterService: updateAdapterState state is 11
,08-24 17:08:02.297  7403  7418 D BluetoothAdapterService: Autoconnection is available 
,08-24 17:08:02.297  7403  7418 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-24 17:08:02.297  7403  7418 D BluetoothSecureManager: getInstant: null
,08-24 17:08:02.297  7403  7418 D BluetoothSecureManager: calling getMethod for getService
,08-24 17:08:02.307  7403  7418 D BluetoothSecureManager: calling getService
,08-24 17:08:02.307  7403  7418 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@ba275c
,08-24 17:08:02.307  1015  1477 D BluetoothSecureManagerService: isSecureModeEnabled
08-24 17:08:02.307  1015  1477 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-24 17:08:02.307  7403  7418 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:08:02.307  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-24 17:08:02.307  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:02.307  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-24 17:08:02.317  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:02.317  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-24 17:08:02.317  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:02.317  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-24 17:08:02.317  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:02.317  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:02.317  1176  1176 D BluetoothTile:  getBluetoothState : 11
08-24 17:08:02.317  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:02.317  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:08:02.327  1870  1870 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:02.327  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-24 17:08:02.327  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 17:08:02.327  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-24 17:08:02.327  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:02.327  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:02.327  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-24 17:08:02.327  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:02.327  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-24 17:08:02.327  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 17:08:02.327  1015  3992 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:02.337  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.337  1015  3992 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:08:02.337  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:02.337  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:08:02.337  7403  7418 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-24 17:08:02.337  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:02.337  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:02.337  7403  7418 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:02.337  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-24 17:08:02.337  7403  7418 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:02.337  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.337  7403  7418 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.337  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-24 17:08:02.337  7403  7418 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-24 17:08:02.337  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:08:02.337  1015  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-24 17:08:02.337  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
08-24 17:08:02.337  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-24 17:08:02.337  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:02.337  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:08:02.347  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:02.347  7403  7418 D BluetoothBondStateMachine: make
,08-24 17:08:02.357  7403  7424 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 17:08:02.357  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-24 17:08:02.357  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 17:08:02.357  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-24 17:08:02.357  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-24 17:08:02.357  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-24 17:08:02.357  1015  1554 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-24 17:08:02.357  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
08-24 17:08:02.367  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.367  1015  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.367  1015  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:02.367  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:02.367  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-24 17:08:02.367  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:02.367  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:02.367  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:02.367  7403  7403 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:08:02.367  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.367  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:02.367  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:02.367  7403  7403 D BtGatt.GattService: Received start request. Starting profile...
08-24 17:08:02.367  7403  7403 D BtGatt.GattService: start()
08-24 17:08:02.367  7403  7403 D BtGatt.GattService: start()
08-24 17:08:02.367  7403  7403 I bluedroid: get_profile_interface gatt
,08-24 17:08:02.367  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:02.367  7403  7403 D BtGatt.AdvertiseManager: advertise manager created
,08-24 17:08:02.367  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 17:08:02.367  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:02.367  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:02.367  1015  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 17:08:02.377  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:02.377  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:02.377  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:02.377  1015  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:02.387  7429  7429 E Zygote  : MountEmulatedStorage(),
,08-24 17:08:02.387  7429  7429 E Zygote  : v2
08-24 17:08:02.387  7429  7429 I libpersona: KNOX_SDCARD checking this for 10055
08-24 17:08:02.387  7429  7429 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:02.387  7429  7429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:08:02.397  1015  1494 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7429 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 17:08:02.397  7429  7429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:02.397  7429  7429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:02.397  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:02.397  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 17:08:02.397  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.397  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.397  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.407  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-24 17:08:02.407  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:02.407  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:08:02.407  1015  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:02.407  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.407  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.407  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.407  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.417  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-24 17:08:02.417  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:02.417  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:08:02.417  7403  7403 D BtGatt.GattService: mStartError = false
08-24 17:08:02.417  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:02.417  1015  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:02.417  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.417  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.417  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.417  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.417  7403  7403 D HeadsetService: Received start request. Starting profile...
08-24 17:08:02.417  7403  7403 D HeadsetService: start()
,08-24 17:08:02.427  7403  7403 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:08:02.427  7403  7403 D HeadsetStateMachine: make
,08-24 17:08:02.427  1015  3343 D SSRM:n  : SIOP:: AP = 360
,08-24 17:08:02.427  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-24 17:08:02.427  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:02.427  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:08:02.427  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:02.427  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.427  7403  7403 E HeadsetStateMachine: # of Max HF connection is 2
,08-24 17:08:02.437  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.437  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.437  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.437  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:02.437  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:02.437  7429  7429 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:08:02.437  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-24 17:08:02.437  7429  7429 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:02.437  1015  1474 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-24 17:08:02.437  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.437  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.437  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:02.437  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:02.447  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:02.447  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.447  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.447  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.447  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.447  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-24 17:08:02.457  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:02.457  7403  7418 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:08:02.457  1015  3992 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-24 17:08:02.457  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.457  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:02.457  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.457  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:02.457  7403  7403 I bluedroid: get_profile_interface handsfree
,08-24 17:08:02.457  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:02.457  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:02.457  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.457  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:02.457  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:02.467  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:02.477  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:02.477  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.477  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:02.477  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:02.477  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:02.477  7403  7418 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-24 17:08:02.477  7403  7403 I DualScoManager: Instantiating Dual Sco Manager
,08-24 17:08:02.477  7403  7403 I DualScoManager: Set HeadsetServiceHelper
,08-24 17:08:02.477  7403  7403 D BluetoothAtMessage: createCMTIContentObservers
,08-24 17:08:02.477  1015  1094 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-24 17:08:02.477  1015  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:02.477  1015  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:02.477  1015  1094 D SettingsProvider: selectionArgs: false
08-24 17:08:02.477  1015  1094 D SettingsProvider: selectionArgs: 1002
08-24 17:08:02.487  1015  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:02.487  1015  1094 D SettingsProvider: ret = -1
,08-24 17:08:02.487  7403  7445 D HeadsetStateMachine: Enter Disconnected: -2
,08-24 17:08:02.487  7403  7403 D HeadsetService: mStartError = false
,08-24 17:08:02.487  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:02.487  7403  7403 D A2dpService: Received start request. Starting profile...
08-24 17:08:02.487  7403  7403 D A2dpService: start()
08-24 17:08:02.487  7429  7429 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 17:08:02.487  7403  7445 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-24 17:08:02.487  7403  7403 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 17:08:02.487  7403  7445 D HeadsetStateMachine: map size, before remove : 0
08-24 17:08:02.487  7403  7445 D HeadsetStateMachine: map size, after remove: 0
,08-24 17:08:02.487  7403  7403 I bluedroid: get_profile_interface avrcp
,08-24 17:08:02.497  7403  7403 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:08:02.497  7403  7403 D Avrcp   : Initialize Media Controller
,08-24 17:08:02.497  7403  7403 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-24 17:08:02.497  7403  7403 E Avrcp   : getActiveSessions
08-24 17:08:02.497  7403  7403 D Avrcp   : pick active media Controller
08-24 17:08:02.497  7403  7403 D Avrcp   : Get the active Media Controller 
,08-24 17:08:02.517  7403  7403 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-24 17:08:02.517  7403  7446 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-24 17:08:02.517  7403  7403 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:08:02.517  7403  7403 D A2dpStateMachine: make
,08-24 17:08:02.517  7403  7403 I bluedroid: get_profile_interface a2dp
,08-24 17:08:02.517  7403  7448 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 17:08:02.517  7429  7429 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-24 17:08:02.517  7403  7403 E bt-btif : warning : media task started media_task_refcnt 1 
,08-24 17:08:02.517  7429  7429 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 17:08:02.517  7429  7429 D UserAnalysis: Create SecureDbHelper
,08-24 17:08:02.527  7403  7403 D A2dpService: mStartError = false
08-24 17:08:02.527  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:02.527  7403  7403 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 17:08:02.527  7403  7403 D HidService: Received start request. Starting profile...
08-24 17:08:02.527  7403  7403 D HidService: start()
08-24 17:08:02.527  7403  7403 I bluedroid: get_profile_interface hidhost
08-24 17:08:02.527  7403  7403 D HidService: setHidService(): set to: null
08-24 17:08:02.527  7403  7403 D HidService: mStartError = false
08-24 17:08:02.527  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:02.527  7403  7447 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:02.527  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-24 17:08:02.527  7403  7403 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 17:08:02.527  7429  7429 D IntelligenceServiceApplication: onCreate()
,08-24 17:08:02.527  7403  7403 D HealthService: Received start request. Starting profile...
08-24 17:08:02.527  7403  7403 D HealthService: start()
,08-24 17:08:02.537  1015  1494 I ActivityManager: Killing 7077:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-24 17:08:02.537  7403  7403 I bluedroid: get_profile_interface health
08-24 17:08:02.537  7403  7403 D HealthService: mStartError = false
08-24 17:08:02.537  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:02.537  7403  7403 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 17:08:02.537  7403  7403 D PanService: Received start request. Starting profile...
08-24 17:08:02.537  7403  7403 D PanService: start()
08-24 17:08:02.537  7403  7403 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:02.537  7403  7403 I bluedroid: get_profile_interface pan
08-24 17:08:02.537  7403  7403 D PanService: mStartError = false
08-24 17:08:02.537  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:02.537  7403  7403 D HeadsetStateMachine: Try to query the phonestate on bind
,08-24 17:08:02.537  7403  7446 D BluetoothMediaBrowser: no now playing list
08-24 17:08:02.537  7403  7446 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-24 17:08:02.537  1421  1443 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 17:08:02.537  1421  1421 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-24 17:08:02.537  7429  7429 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-24 17:08:02.537  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-24 17:08:02.537  1421  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 17:08:02.547  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 17:08:02.547  7403  7403 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:02.547  7403  7403 D BluetoothMapService: start()
08-24 17:08:02.547  7429  7429 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-24 17:08:02.547  7403  7403 D BluetoothMapService: mStartError = false
08-24 17:08:02.547  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:02.547  7403  7403 D HeadsetStateMachine: Proxy object connected
08-24 17:08:02.547  7403  7403 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-24 17:08:02.547  7403  7445 D HeadsetStateMachine: Disconnected process message: 11
,08-24 17:08:02.547  7403  7403 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-24 17:08:02.547  7403  7403 D SapService: Received start request. Starting profile...
08-24 17:08:02.547  7403  7403 D SapService: start()
08-24 17:08:02.547  7403  7403 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 17:08:02.547  7403  7403 I bluedroid: get_profile_interface sap
08-24 17:08:02.547  7403  7403 D SapService: mStartError = false
08-24 17:08:02.547  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:02.547  7403  7403 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 17:08:02.547  7403  7445 D HeadsetStateMachine: Disconnected process message: 18
08-24 17:08:02.547  7403  7403 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-24 17:08:02.547  7403  7403 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 17:08:02.547  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 17:08:02.547  7403  7445 D HeadsetStateMachine: Disconnected process message: 10
08-24 17:08:02.547  7403  7403 D BluetoothA2dp: Proxy object connected
08-24 17:08:02.547  7403  7403 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-24 17:08:02.547  7403  7445 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:08:02.547  7403  7445 D HeadsetStateMachine: Disconnected process message: 11
08-24 17:08:02.547  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 17:08:02.547  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-24 17:08:02.547  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-24 17:08:02.547  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-24 17:08:02.557  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-24 17:08:02.557  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:02.557  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:02.557  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:02.557  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:02.557  7429  7429 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 17:08:02.567  7453  7453 E Zygote  : MountEmulatedStorage(),
,08-24 17:08:02.567  7453  7453 E Zygote  : v2
08-24 17:08:02.567  7453  7453 I libpersona: KNOX_SDCARD checking this for 10105
08-24 17:08:02.567  7453  7453 I libpersona: KNOX_SDCARD not a persona,
,08-24 17:08:02.577  1015  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7453 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-24 17:08:02.577  7453  7453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:02.577  7453  7453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:08:02.577  7453  7453 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:08:02.607  7453  7453 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:02.607  7453  7453 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:02.607  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-24 17:08:02.607  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-24 17:08:02.617  7403  7418 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-24 17:08:02.617  7403  7418 I bluedroid: enable
,08-24 17:08:02.617  7403  7418 I bt_hci_bdroid: init
,08-24 17:08:02.617  7403  7470 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-24 17:08:02.617  7403  7418 I bt_vendor: bt-vendor : init
,08-24 17:08:02.617  7403  7418 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 17:08:02.617  7403  7418 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-24 17:08:02.617  7403  7418 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-24 17:08:02.617  7403  7418 D bt_userial_mct: userial_init
,08-24 17:08:02.627  7403  7418 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 17:08:02.627  7403  7418 I bt_vendor: Starting hciattach daemon
08-24 17:08:02.627  7403  7418 I bt_vendor: try to set false
,08-24 17:08:02.627  7403  7418 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-24 17:08:02.627  7403  7418 I bt_vendor: Starting hciattach daemon
08-24 17:08:02.627  7403  7418 I bt_vendor: try to set true
,08-24 17:08:02.657  7474  7474 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-24 17:08:02.697  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-24 17:08:02.707  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 17:08:02.727  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-24 17:08:02.737  7486  7486 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-24 17:08:02.737  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-24 17:08:02.747  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-24 17:08:02.817   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:08:02.817   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:08:02.817  7453  7493 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:08:02.817   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:08:02.817   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:08:02.827  7453  7493 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:08:02.927  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-24 17:08:02.937  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 17:08:02.977  7453  7453 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.977  7453  7453 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.977  7453  7453 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.977  7453  7453 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.977  7453  7453 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.977  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.987  7453  7453 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.987  7453  7453 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.987  7453  7453 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:02.987  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 17:08:02.987  1015  1478 I ActivityManager: Killing 7092:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-24 17:08:02.987  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:02.997  7403  7418 I bt_vendor: bluetooth satus is on
08-24 17:08:02.997  7403  7472 D bt_userial_mct: userial_open(port:0)
08-24 17:08:02.997  7403  7472 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 17:08:02.997  7403  7472 I bt_vendor: Done intiailizing UART
,08-24 17:08:02.997  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:02.997  7403  7472 I bt_vendor: Done intiailizing UART
,08-24 17:08:02.997  7403  7472 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-24 17:08:02.997  7403  7472 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-24 17:08:02.997  7403  7506 D bt_userial_mct: Entering userial_read_thread()
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_A2D
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_PAN
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_SAP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_BTIF
08-24 17:08:03.007  7403  7470 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-24 17:08:03.047  7453  7498 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 17:08:03.067  1015  1364 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:03.067  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.067  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:08:03.067  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 17:08:03.097  7403  7470 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-24 17:08:03.097  7403  7470 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42e2ed1 
,08-24 17:08:03.107  7403  7470 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42e2ed1 
,08-24 17:08:03.117  7403  7421 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-24 17:08:03.117  7403  7421 E bt-btif : Calling BTA_HhEnable
,08-24 17:08:03.117  7403  7421 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-24 17:08:03.117  7403  7421 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-24 17:08:03.117  7403  7421 E BluetoothServiceJni: populateRssiValuesNative
,08-24 17:08:03.127  7403  7421 I bluedroid: getModelRssiValues
08-24 17:08:03.127  7403  7421 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-24 17:08:03.127  7403  7421 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 17:08:03.127  1015  1015 D SettingsProvider: name = bluetooth_name
,08-24 17:08:03.127  7403  7421 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-24 17:08:03.137  7403  7421 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:03.137  7403  7421 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:08:03.137  7403  7421 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:03.137  7403  7421 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-24 17:08:03.137  7403  7421 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-24 17:08:03.137  7403  7421 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-24 17:08:03.137  7403  7421 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-24 17:08:03.137  7403  7421 E bt-btif : btif_sock_init: !vhci_init
08-24 17:08:03.137  7403  7421 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-24 17:08:03.137  7403  7421 D IOP_DB_BT: db_open: db_open : handle 3023953936l, read 13894 bytes onto local cache
08-24 17:08:03.137  7403  7421 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-24 17:08:03.137  7403  7421 D IOP_DB_BT: db_query: result 1
,08-24 17:08:03.137  7403  7421 I         : iop_db_open: iop_db_open status 0
08-24 17:08:03.137  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.137  7403  7421 D bte_conf: Device ID record 1 : primary
08-24 17:08:03.137  7403  7421 D bte_conf:   vendorId            = 0075
08-24 17:08:03.137  7403  7421 D bte_conf:   vendorIdSource      = 0001
08-24 17:08:03.137  7403  7421 D bte_conf:   product             = 0100
08-24 17:08:03.137  7403  7421 D bte_conf:   version             = 0200
08-24 17:08:03.137  7403  7421 D bte_conf:   clientExecutableURL = 
08-24 17:08:03.137  7403  7421 D bte_conf:   serviceDescription  = 
08-24 17:08:03.137  7403  7421 D bte_conf:   documentationURL    = 
08-24 17:08:03.137  7403  7421 D bte_conf: bte_load_did_conf no section named DID2.
,08-24 17:08:03.147  7403  7421 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:03.147  7403  7418 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 17:08:03.147  7403  7418 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:03.147  7403  7418 D BluetoothAdapterProperties: State =  11
,08-24 17:08:03.147  1015  3992 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 17:08:03.147  7403  7418 D BluetoothAdapterProperties: Setting state to 12
08-24 17:08:03.147  7403  7418 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:08:03.147  7403  7506 E bt_mct  : hci lib postload completed
,08-24 17:08:03.147  7403  7421 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:03.147  7403  7421 D BluetoothAdapterProperties: Scan Mode:21
08-24 17:08:03.147  7403  7421 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:03.157  1015  1554 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-24 17:08:03.157  1015  1554 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-24 17:08:03.157  1015  1554 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-24 17:08:03.157  1015  1554 D SettingsProvider: selectionArgs: false
,08-24 17:08:03.157  1015  1554 D SettingsProvider: selectionArgs: 1002
,08-24 17:08:03.157  1015  1554 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:03.157  1015  1554 D SettingsProvider: ret = -1
,08-24 17:08:03.157  7403  7418 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:03.157  7403  7418 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:03.167  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:03.167  1015  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:03.167  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.167  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.167  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.167  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.177  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:03.177  7403  7418 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:03.177  7403  7418 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 17:08:03.177  7403  7418 D BluetoothAdapterService: starting service from this receiver
,08-24 17:08:03.177  1015  1554 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:03.177  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.177  7403  7412 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:03.177  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.177  1015  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.177  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.177  7403  7418 I BluetoothAdapterState: Entering On State from state = 11
,08-24 17:08:03.187  4063  4071 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:03.187  4063  4071 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.187  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:03.187  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:03.187  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:03.187  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.187  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.187  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.187  4063  4063 D BluetoothA2dp: Proxy object connected
,08-24 17:08:03.187  4063  7186 D Bluetoothsap: onBluetoothStateChange: up=true
08-24 17:08:03.187  4063  7186 D Bluetoothsap: Binding service...
08-24 17:08:03.187  4063  4063 D A2dpProfile: Bluetooth service connected
,08-24 17:08:03.197  7403  7403 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-24 17:08:03.197  4063  7186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 17:08:03.197  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-24 17:08:03.197  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.197  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:03.197  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.197  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 17:08:03.197  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.197  4063  7186 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-24 17:08:03.207  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.207  1421  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.207  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:03.207  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:03.207  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.207  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.207  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.217  1421  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:03.217  1438  2015 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:03.217  1438  2015 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.217  1176  1185 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.217  1176  1185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.217  7403  7403 I BluetoothPbapService: Handler(): got msg=1
,08-24 17:08:03.217  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.217  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:03.217  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:03.217  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:03.217  1015  1478 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 17:08:03.227  4063  4077 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.227  7403  7512 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 17:08:03.227  7403  7512 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 17:08:03.237  7403  7512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:03.237  7403  7512 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-24 17:08:03.237  7403  7512 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:03.237  7403  7512 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-24 17:08:03.237  7403  7512 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@127b20f9
08-24 17:08:03.237  7403  7512 D BluetoothSocket: channel: 19
08-24 17:08:03.237  7403  7512 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 17:08:03.367  1015  1044 I art     : Explicit concurrent mark sweep GC freed 65983(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.385ms total 144.957ms
,08-24 17:08:03.367  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:03.367  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:03.367  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.367  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.367  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 17:08:03.367  4063  4077 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:03.377  6774  6786 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:03.377  6774  6786 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.377  4063  4063 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-24 17:08:03.377  4063  4063 D SapProfile: Bluetooth service connected
08-24 17:08:03.377  4063  7186 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 17:08:03.377  4063  4063 D Bluetoothsap: getConnectedDevices()
,08-24 17:08:03.377  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-24 17:08:03.377  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.377  4063  4063 D HeadsetProfile: Bluetooth service connected
08-24 17:08:03.377  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.377  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.377  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.377  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.377  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.377  4063  4077 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:03.377  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-24 17:08:03.377  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.377  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.377  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.377  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.377  4063  4063 D BluetoothInputDevice: Proxy object connected
,08-24 17:08:03.387  4063  4063 D HidProfile: Bluetooth service connected
,08-24 17:08:03.387  4063  4071 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 17:08:03.387  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-24 17:08:03.387  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.387  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.387  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.387  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.387  7403  7412 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.387  7403  7412 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.387  1421  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.387  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:03.387  1421  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.387  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:03.387  4063  4063 D BluetoothMap: Proxy object connected
08-24 17:08:03.387  1421  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 17:08:03.387  4063  4063 D MapProfile: Bluetooth service connected
08-24 17:08:03.387  4063  4063 D BluetoothMap: getConnectedDevices()
08-24 17:08:03.387  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.387  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:03.387  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-24 17:08:03.387  1421  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:03.387  2041  2583 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.387  2041  2583 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.387  4063  7186 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.387  4063  7186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.397  1438  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.397  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:03.397  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:03.397  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.397  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.397  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.397  1438  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:03.397  1015  1044 D BluetoothPan: Binding service...
08-24 17:08:03.397  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 17:08:03.397  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.397  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:03.397  4063  4063 D BluetoothPbap: Proxy object connected
08-24 17:08:03.397  4063  4063 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:03.397  1427  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:03.397  1427  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.397  7453  7469 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:03.397  7453  7469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:03.397  1421  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.397  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:03.397  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.397  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:03.397  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.397  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.397  1421  1443 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 17:08:03.397  4063  4077 D BluetoothPan: Binding service...
,08-24 17:08:03.397  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 17:08:03.397  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.397  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.407  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.407  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.407  4063  4063 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:03.407  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:03.407  4063  4063 D PanProfile: Bluetooth service connected
08-24 17:08:03.407  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:03.407  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:03.407  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.407  1015  1015 D BluetoothA2dp: Proxy object connected
,08-24 17:08:03.407  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 17:08:03.407  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-24 17:08:03.407  1421  1421 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@35c78f45, true
,08-24 17:08:03.417  1176  1176 D BluetoothTile:  onBluetoothStateChange:
08-24 17:08:03.417  1421  1421 D BluetoothHeadset: registerMessageListener
,08-24 17:08:03.417  1870  1870 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:03.417  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:03.417  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:03.417  1176  1176 D BluetoothTile:  getBluetoothState : 12
08-24 17:08:03.417  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:03.417  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:03.427  1015  1364 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:03.427  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.427  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:03.427  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-24 17:08:03.427  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:08:03.427  7403  7411 D HeadsetService: registerMessageListener
,08-24 17:08:03.427  7403  7411 D HeadsetService: registerMessageListener
,08-24 17:08:03.427  7403  7445 D HeadsetStateMachine: Disconnected process message: 70
08-24 17:08:03.427  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.427  7403  7445 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1c0f183e
,08-24 17:08:03.427  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.427  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:03.427  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:03.427  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.427  7403  7518 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-24 17:08:03.427  1421  1421 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-24 17:08:03.427  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 17:08:03.437  1421  1421 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 17:08:03.437  1421  1421 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-24 17:08:03.437  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-24 17:08:03.437  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:03.437  4063  4063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-24 17:08:03.437  7403  7518 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:03.437  7403  7518 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:03.437  4063  4063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-24 17:08:03.437  4063  4063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-24 17:08:03.437  4063  4063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-24 17:08:03.437  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:03.437  1015  1474 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-24 17:08:03.447  7403  7445 D HeadsetStateMachine: Disconnected process message: 9
08-24 17:08:03.447  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:08:03.447  7403  7445 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 17:08:03.447  7403  7518 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-24 17:08:03.447  7403  7518 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:03.447  7403  7518 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:03.447  7403  7518 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9c4669f
,08-24 17:08:03.447  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:03.447  7403  7518 D BluetoothSocket: channel: 5
,08-24 17:08:03.447   282   691 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-24 17:08:03.447   282   691 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 17:08:03.447   282   691 V voice   : voice_set_parameters: exit with code(-2)
,08-24 17:08:03.447   282   691 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 17:08:03.457   282   691 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 17:08:03.457   282   691 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 17:08:03.457   282   691 V audio_hw_primary: adev_set_parameters: exit
08-24 17:08:03.457  7403  7445 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-24 17:08:03.457  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:03.457  1015  1094 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 17:08:03.457  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.457  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.457  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:03.457  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:03.467  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:03.467  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:03.477  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:03.477  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 17:08:03.477  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:03.477  7403  7403 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 17:08:03.487  1015  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:03.487  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.487  1015  1364 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:08:03.487  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:03.487  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:03.507  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:03.507  1015  1364 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:03.507  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-24 17:08:03.517  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.517  1015  1364 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:03.517  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:03.517  1015  1477 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 17:08:03.527  7403  7527 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 17:08:03.527  7403  7527 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:03.527  2041  7528 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-24 17:08:03.527  7403  7527 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-24 17:08:03.527  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:03.527  7403  7527 D BluetoothSocket: bindListen(), new LocalSocket 
,08-24 17:08:03.527  7403  7527 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-24 17:08:03.527  7403  7527 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eaaf631
08-24 17:08:03.527  7403  7527 D BluetoothSocket: channel: 12
08-24 17:08:03.527  7403  7527 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:03.537  1015  1334 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:03.537  1015  1334 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.537  1015  1334 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:03.537  1015  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:03.547  1015  1094 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:03.557  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:03.557  1015  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:03.557  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:03.557  2041  7528 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-24 17:08:03.837   287   287 E SMD     : DCD OFF,
,08-24 17:08:05.087  6774  6828 D BluetoothAdapter: disable()
,08-24 17:08:05.087  1015  1476 D SettingsProvider: name = bluetooth_on
,08-24 17:08:05.097  7403  7418 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-24 17:08:05.097  7403  7418 D BluetoothAdapterProperties: Setting state to 13
08-24 17:08:05.097  7403  7418 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:08:05.097  7403  7418 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:05.097  7403  7418 D BluetoothAdapterService: updateAdapterState state is 13
,08-24 17:08:05.097  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:05.097  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:05.107  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:05.107  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:05.107  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:05.107  7403  7403 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-24 17:08:05.107  7403  7418 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:05.107  7403  7418 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-24 17:08:05.107  7403  7418 D BluetoothAdapterService: terminating service from this receiver
,08-24 17:08:05.107  7403  7403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20b3f116, channel: 19, state: LISTENING
,08-24 17:08:05.107  7403  7403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20b3f116, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@127b20f9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d168a97mSocket: android.net.LocalSocket@389d3484 impl:android.net.LocalSocketImpl@2307c46d fd:FileDescriptor[74]
08-24 17:08:05.107  7403  7403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@389d3484 impl:android.net.LocalSocketImpl@2307c46d fd:FileDescriptor[74]
,08-24 17:08:05.107  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:05.107  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-24 17:08:05.117  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:08:05.117  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:05.117  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:05.117  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:05.117  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-24 17:08:05.127  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
08-24 17:08:05.127  1870  1870 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:05.127  1015  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:05.127  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:08:05.127  1015  1334 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:05.127  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:08:05.137  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:05.137  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:05.137  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:05.137  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:05.137  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:05.147  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:05.147  7403  7403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@217608a2, channel: 5, state: LISTENING
,08-24 17:08:05.147  7403  7403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@217608a2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9c4669f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@52f3933mSocket: android.net.LocalSocket@8fb14f0 impl:android.net.LocalSocketImpl@34e93a69 fd:FileDescriptor[76]
,08-24 17:08:05.147  7403  7403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8fb14f0 impl:android.net.LocalSocketImpl@34e93a69 fd:FileDescriptor[76]
08-24 17:08:05.147  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:05.147  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:05.147  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-24 17:08:05.147  7403  7403 I BtOppRfcommListener: stopping Accept Thread
08-24 17:08:05.147  1015  3992 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:05.147  7403  7403 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d500cee, channel: 12, state: LISTENING
08-24 17:08:05.147  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-24 17:08:05.147  7403  7403 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d500cee, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eaaf631, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d1a358fmSocket: android.net.LocalSocket@1c14901c impl:android.net.LocalSocketImpl@a521425 fd:FileDescriptor[79]
08-24 17:08:05.147  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 17:08:05.147  7403  7403 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c14901c impl:android.net.LocalSocketImpl@a521425 fd:FileDescriptor[79]
08-24 17:08:05.147  7403  7527 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:08:05.147  7403  7527 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 17:08:05.147  7403  7418 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 17:08:05.147  7403  7418 D BluetoothAdapterProperties: mDiscovering is false
08-24 17:08:05.157  1015  1474 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-24 17:08:05.157  7403  7418 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 17:08:05.157  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:05.157  1015  3992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:05.157  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:05.157  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:05.157  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:05.167  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:05.167  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:05.167  1015  1478 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:08:05.167  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:05.167  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:05.167  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:05.167  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:05.177  4063  4063 D BluetoothPbap: Proxy object disconnected
,08-24 17:08:05.177  4063  4063 D PbapServerProfile: Bluetooth service disconnected
,08-24 17:08:05.177  7403  7421 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:05.177  7403  7421 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:05.177  7403  7418 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 17:08:05.177  7403  7418 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-24 17:08:05.177  7403  7418 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-24 17:08:05.187  7403  7418 E bt-btif : cmd socket is not created
,08-24 17:08:05.187  7403  7470 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-24 17:08:05.187  7403  7470 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 17:08:05.187  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:08:05.187  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:05.187  7403  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 17:08:05.187  7403  7418 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 17:08:05.187  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:05.197  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:05.207  7403  7403 V BluetoothOppManager: cleanUp...
,08-24 17:08:05.207  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:05.207  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:05.207  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:05.207  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 17:08:05.227  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:05.237  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:08:05.387  7403  7470 W bt-btif : ag scb idx 1 not allocated
08-24 17:08:05.387  7403  7470 W bt-btif : ag scb idx 2 not allocated
08-24 17:08:05.387  7403  7470 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 17:08:05.387  7403  7506 I bt_userial_mct: exiting userial_read_thread
08-24 17:08:05.387  7403  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 17:08:05.387  7403  7421 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 17:08:05.387  7403  7472 I bt_vendor: hw_epilog_process
08-24 17:08:05.387  7403  7421 D bt_userial_mct: userial_close
08-24 17:08:05.387  7403  7421 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-24 17:08:06.077  7403  7421 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-24 17:08:06.077  7403  7421 I bt_vendor: bluetooth satus is on
08-24 17:08:06.077  7403  7421 I bt_vendor: bt-vendor : resetting BT status
,08-24 17:08:06.077  7403  7421 I bt_vendor: Starting hciattach daemon
08-24 17:08:06.077  7403  7421 I bt_vendor: try to set false
,08-24 17:08:06.077  7403  7421 I bt_vendor: Starting hciattach daemon
08-24 17:08:06.077  7403  7421 I bt_vendor: try to set false
,08-24 17:08:06.077  7403  7421 I bt_vendor: cleanup
08-24 17:08:06.077  7403  7470 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-24 17:08:06.077  7403  7421 I GKI_LINUX: GKI_exit_task 0 done
08-24 17:08:06.077  7403  7421 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-24 17:08:06.087  7403  7418 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 17:08:06.087  7403  7418 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 17:08:06.087  7403  7418 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-24 17:08:06.087  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-24 17:08:06.087  1015  1554 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.087  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 17:08:06.087  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-24 17:08:06.087  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-24 17:08:06.087  1015  3992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.087  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.087  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-24 17:08:06.087  1015  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.087  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:06.087  7403  7403 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:08:06.087  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:06.087  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:06.087  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-24 17:08:06.087  7403  7403 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 17:08:06.087  7403  7403 D BtGatt.GattService: stop()
08-24 17:08:06.087  7403  7403 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 17:08:06.097  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.097  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.097  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:06.097  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
08-24 17:08:06.097  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 17:08:06.097  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:06.097  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-24 17:08:06.097  1015  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.097  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.097  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.097  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.097  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:06.097  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-24 17:08:06.097  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:06.097  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-24 17:08:06.097  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.097  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.107  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.107  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.107  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:06.107  1015  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 17:08:06.107  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-24 17:08:06.107  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:06.107  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:08:06.107  1015  1477 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:08:06.107  1015  1477 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 17:08:06.107  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:08:06.107  1015  1477 D BatteryService: stay LED for fully charged
,08-24 17:08:06.107  1015  1015 I MotionRecognitionService: Plugged
,08-24 17:08:06.107  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:08:06.117  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:08:06.117  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:08:06.117  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 17:08:06.117  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:08:06.127  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.127  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.127  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.127  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.127  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:06.127  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-24 17:08:06.127  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:06.127  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:08:06.137  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.137  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.137  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.137  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.137  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:06.137  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:06.137  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.137  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.137  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.137  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.137  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-24 17:08:06.137  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:06.137  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-24 17:08:06.137  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:08:06.137  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 17:08:06.137  1015  3992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:06.137  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.137  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.137  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.137  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:06.137  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:06.137  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:06.147  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:08:06.147  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:06.147  7403  7418 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:06.147  7403  7418 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:06.147  7403  7418 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 17:08:06.147  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-24 17:08:06.147  7403  7403 D HeadsetService: Received stop request...Stopping profile...
,08-24 17:08:06.147  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.147  7403  7403 D A2dpService: Received stop request...Stopping profile...
,08-24 17:08:06.147  7403  7447 D A2dpStateMachine: Exit Disconnected: -1
,08-24 17:08:06.147  4063  4063 D HeadsetProfile: Bluetooth service disconnected
08-24 17:08:06.147  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 17:08:06.147  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.157  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:06.157  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-24 17:08:06.157  4063  4063 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:06.157  7403  7403 D HidService: Received stop request...Stopping profile...
,08-24 17:08:06.157  4063  4063 D A2dpProfile: Bluetooth service disconnected
08-24 17:08:06.157  7403  7403 D HidService: Stopping Bluetooth HidService
08-24 17:08:06.157  7403  7403 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:08:06.157  7403  7403 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-24 17:08:06.157  7403  7403 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:08:06.157  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.157  7403  7403 D HealthService: Received stop request...Stopping profile...
,08-24 17:08:06.157  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.157  7403  7403 D PanService: Received stop request...Stopping profile...
08-24 17:08:06.157  4063  4063 D BluetoothInputDevice: Proxy object disconnected
08-24 17:08:06.157  4063  4063 D HidProfile: Bluetooth service disconnected
,08-24 17:08:06.157  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.157  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:08:06.157  4063  4063 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 17:08:06.157  4063  4063 D PanProfile: Bluetooth service disconnected
,08-24 17:08:06.167  7403  7403 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 17:08:06.167  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.167  7403  7403 D SapService: Received stop request...Stopping profile...
08-24 17:08:06.167  7403  7403 D SapService: Stopping Bluetooth SapService
08-24 17:08:06.167  7403  7403 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@182aaed7
,08-24 17:08:06.167  4063  4063 D BluetoothMap: Proxy object disconnected
08-24 17:08:06.167  4063  4063 D MapProfile: Bluetooth service disconnected
,08-24 17:08:06.167  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-24 17:08:06.167  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:06.167  4063  4063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 17:08:06.167  7403  7403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-24 17:08:06.167  4063  4063 D SapProfile: Bluetooth service disconnected
,08-24 17:08:06.177  7403  7403 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 17:08:06.177  7403  7403 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-24 17:08:06.177  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 17:08:06.177  7403  7403 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-24 17:08:06.177  7403  7448 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-24 17:08:06.177  7403  7403 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:08:06.177  7403  7403 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 17:08:06.177  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-24 17:08:06.177  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.177  7403  7403 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-24 17:08:06.177  7403  7403 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-24 17:08:06.177  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:06.177  7403  7403 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:08:06.177  7403  7403 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-24 17:08:06.177  7403  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 17:08:06.177  7403  7403 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-24 17:08:06.177  7403  7403 E BluetoothAdapterService(405450455): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-24 17:08:06.187  7403  7403 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-24 17:08:06.187  7403  7403 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-24 17:08:06.187  7403  7418 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-24 17:08:06.187  7403  7418 D BluetoothAdapterProperties: Setting state to 10
,08-24 17:08:06.187  7403  7418 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:08:06.187  7403  7418 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:06.187  7403  7418 D BluetoothAdapterService: updateAdapterState state is 10
,08-24 17:08:06.187  7403  7418 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:06.187  7403  7418 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 17:08:06.187  7403  7418 I BluetoothAdapterState: Entering OffState
,08-24 17:08:06.187  7403  7411 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:06.187  4063  4077 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:08:06.187  4063  4071 D Bluetoothsap: onBluetoothStateChange: up=false
,08-24 17:08:06.187  4063  4071 D Bluetoothsap: Unbinding service...
,08-24 17:08:06.187  1438  1849 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:06.187  1438  1849 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  1176  1193 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:06.197  1176  1193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  6774  6782 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:06.197  6774  6782 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:06.197  6774  6782 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-24 17:08:06.197  6774  6782 D BluetoothLeAdvertiser: Exit stop advertising
08-24 17:08:06.197  6774  6782 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-24 17:08:06.197  6774  6782 D BluetoothLeScanner: Exiting stopAllScan
08-24 17:08:06.197  4063  7186 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 17:08:06.197  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:06.197  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:06.197  4063  4077 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 17:08:06.197  4063  4071 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 17:08:06.197  7403  7514 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:06.197  7403  7514 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  1421  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:06.197  1421  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  2041  7188 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:06.197  2041  7188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  4063  4074 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:06.197  4063  4074 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  1427  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:06.197  1427  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.197  7453  7466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:06.197  7453  7466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:06.207  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:08:06.207  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 17:08:06.207  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-24 17:08:06.217  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:06.217  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-24 17:08:06.217  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:08:06.217  7403  7421 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 17:08:06.217  7403  7403 I GKI_LINUX: GKI_exit_task 1 done
08-24 17:08:06.217  7403  7403 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-24 17:08:06.217  7403  7403 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 17:08:06.217  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
,08-24 17:08:06.217  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:06.217  1870  1870 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:06.217  7403  7403 I art     : System.exit called, status: 0
08-24 17:08:06.217  7403  7403 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 17:08:06.217  1176  1763 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:08:06.217  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:06.217  1176  1176 D BluetoothTile:  getBluetoothState : 10
,08-24 17:08:06.217  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:08:06.217  1176  1176 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
08-24 17:08:06.217  1176  1763 D BluetoothAdapter: 50218743: getState() :  mService = null. Returning STATE_OFF
,08-24 17:08:06.217  1015  3992 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:08:06.217  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:06.227  2041  2222 D BluetoothAdapter: 569280609: getState() :  mService = null. Returning STATE_OFF
08-24 17:08:06.227  1015  1494 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-24 17:08:06.227  2041  2222 D BluetoothAdapter: 569280609: getState() :  mService = null. Returning STATE_OFF
,08-24 17:08:06.227  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:06.227  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:08:06.227  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:06.227  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:06.227  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.227  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.227  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:06.227  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 17:08:06.227  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:06.227  1015  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:08:06.227  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.227  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:06.227  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:06.227  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:06.237  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:06.237  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:06.247  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:06.247  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-24 17:08:06.247  1015  1028 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 17:08:06.257  1015  1028 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 17:08:06.257  1015  1028 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-24 17:08:06.257  1015  1028 W BroadcastQueue: android.os.TransactionTooLargeException
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-24 17:08:06.257  1015  1028 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 17:08:06.257  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-24 17:08:06.257  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:06.257  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:06.257  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:06.257  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:06.267  1015  1028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7544 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-24 17:08:06.267  7544  7544 E Zygote  : MountEmulatedStorage()
08-24 17:08:06.267  7544  7544 I libpersona: KNOX_SDCARD checking this for 1002
08-24 17:08:06.267  7544  7544 E Zygote  : v2
08-24 17:08:06.267  7544  7544 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:06.277  7544  7544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:06.277  7544  7544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:06.277  7544  7544 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:06.297  7544  7544 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:06.297  7544  7544 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:06.307  7544  7544 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 17:08:06.307  7544  7544 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:08:06.327  7544  7544 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding GattService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding HeadsetService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding A2dpService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding HidService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding HealthService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding PanService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding SapService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-24 17:08:06.367  7544  7544 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-24 17:08:06.377  7544  7544 D BtSettings.ProfileConfig: Adding SapClientService
,08-24 17:08:06.377  7544  7544 D BtSettings.ProfileConfig: Adding HidDevService
,08-24 17:08:06.377  7544  7544 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-24 17:08:06.377  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-24 17:08:06.377  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.377  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.377  1015  1477 D SettingsProvider: selectionArgs: false
08-24 17:08:06.377  1015  1477 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.377  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.377  1015  1477 D SettingsProvider: ret = -1
,08-24 17:08:06.377  1015  1553 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:06.377  1015  1553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.377  1015  1553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.377  1015  1553 D SettingsProvider: selectionArgs: false
,08-24 17:08:06.377  1015  1553 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.377  1015  1553 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:06.377  1015  1553 D SettingsProvider: ret = -1
,08-24 17:08:06.377  1015  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:06.377  1015  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.377  1015  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.377  1015  1094 D SettingsProvider: selectionArgs: false
08-24 17:08:06.377  1015  1094 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.377  1015  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.377  1015  1094 D SettingsProvider: ret = -1
,08-24 17:08:06.377  1015  1554 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-24 17:08:06.377  1015  1554 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.377  1015  1554 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.377  1015  1554 D SettingsProvider: selectionArgs: false
08-24 17:08:06.377  1015  1554 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.377  1015  1554 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.377  1015  1554 D SettingsProvider: ret = -1
,08-24 17:08:06.387  1015  3992 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-24 17:08:06.387  1015  3992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  3992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  3992 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  3992 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  3992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  3992 D SettingsProvider: ret = -1
,08-24 17:08:06.387  1015  1364 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-24 17:08:06.387  1015  1364 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-24 17:08:06.387  1015  1364 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1364 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1364 D SettingsProvider: selectionArgs: 1002
,08-24 17:08:06.387  1015  1364 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:06.387  1015  1364 D SettingsProvider: ret = -1
08-24 17:08:06.387  1015  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:06.387  1015  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1473 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1473 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:06.387  1015  1473 D SettingsProvider: ret = -1
,08-24 17:08:06.387  1015  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-24 17:08:06.387  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1476 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1476 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  1476 D SettingsProvider: ret = -1
08-24 17:08:06.387  1015  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:06.387  1015  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1474 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1474 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  1474 D SettingsProvider: ret = -1
08-24 17:08:06.387  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:06.387  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1027 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1027 D SettingsProvider: selectionArgs: 1002,
08-24 17:08:06.387  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  1027 D SettingsProvider: ret = -1
08-24 17:08:06.387  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-24 17:08:06.387  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-24 17:08:06.387  1015  1494 D SettingsProvider: selectionArgs: false
08-24 17:08:06.387  1015  1494 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  1494 D SettingsProvider: ret = -1
08-24 17:08:06.387  1015  1334 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-24 17:08:06.387  1015  1334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:06.387  1015  1334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:06.387  1015  1334 D SettingsProvider: selectionArgs: false
,08-24 17:08:06.387  1015  1334 D SettingsProvider: selectionArgs: 1002
08-24 17:08:06.387  1015  1334 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:06.387  1015  1334 D SettingsProvider: ret = -1
,08-24 17:08:06.397  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:06.397  1015  1554 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:06.397  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-24 17:08:06.397  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.397  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:06.397  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:06.407  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:06.407  2041  7560 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-24 17:08:06.417  1015  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:06.417  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:06.417  1015  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:06.417  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:06.427  2041  7560 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-24 17:08:06.837   287   287 E SMD     : DCD OFF
,08-24 17:08:07.177  1015  1047 I PowerManagerService: [PWL] Off : 75s ago,
08-24 17:08:07.177  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-24 17:08:07.177  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-24 17:08:07.177  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=13181)
,08-24 17:08:07.937  1015  1310 E Watchdog: !@Sync 4
,08-24 17:08:08.107  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:08.107  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:08.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:09.847   287   287 E SMD     : DCD OFF
,08-24 17:08:09.867   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:10.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:11.107  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-24 17:08:11.107  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7817b5 added. We now have 6 listener(s)
,08-24 17:08:11.107  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:11.107  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:11.107  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24596e4a added. We now have 7 listener(s)
08-24 17:08:11.107  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:11.117  6774  6828 I System.out: IsBluetoothEnabled
,08-24 17:08:11.117  6774  6828 D BluetoothAdapter: disable(),
,08-24 17:08:11.117  1015  1474 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
08-24 17:08:11.117  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:11.117  6774  6828 D BluetoothAdapter: enable()
,08-24 17:08:11.127  1015  1477 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 17:08:11.127  1015  1477 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:08:11.127  1015  1477 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:11.127  1015  1477 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 17:08:11.127  1015  1477 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:11.137  1015  1477 D SettingsProvider: name = bluetooth_on
,08-24 17:08:11.137  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 17:08:11.137  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:11.137  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-24 17:08:11.137  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-24 17:08:11.177  7544  7544 D BluetoothAdapterState: make
,08-24 17:08:11.187  7544  7544 I bluedroid: init
,08-24 17:08:11.187  7544  7566 I BluetoothAdapterState: Entering OffState,
,08-24 17:08:11.187  7544  7544 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-24 17:08:11.187  7544  7544 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 17:08:11.187  7544  7544 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 17:08:11.187  7544  7544 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-24 17:08:11.187  7544  7544 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-24 17:08:11.187  7544  7544 I bluedroid: get_profile_interface socket
08-24 17:08:11.187  7544  7544 I bluedroid: get_profile_interface map_client
08-24 17:08:11.187  7544  7569 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-24 17:08:11.197  7544  7569 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-24 17:08:11.197  7544  7569 E BluetoothServiceJni: populateRssiValuesNative
08-24 17:08:11.197  7544  7569 I bluedroid: getModelRssiValues
08-24 17:08:11.197  7544  7569 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 17:08:11.197  7544  7569 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-24 17:08:11.197  7544  7544 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-24 17:08:11.197  7544  7569 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3),
,08-24 17:08:11.197  1015  1015 D SettingsProvider: name = bluetooth_name
,08-24 17:08:11.207  7544  7544 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:11.207  1015  1553 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:11.207  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.207  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.207  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:11.207  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.207  7544  7555 I bluedroid: config_hci_snoop_log
,08-24 17:08:11.207  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 17:08:11.217  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
08-24 17:08:11.217  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 17:08:11.217  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
08-24 17:08:11.217  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-24 17:08:11.217  7544  7544 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-24 17:08:11.227  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 17:08:11.227  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:11.237  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-24 17:08:11.237  7544  7566 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-24 17:08:11.237  7544  7566 D BluetoothAdapterProperties: Setting state to 11
,08-24 17:08:11.237  7544  7566 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 17:08:11.237  7544  7566 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:11.237  7544  7566 D BluetoothAdapterService: updateAdapterState state is 11
,08-24 17:08:11.237  7544  7566 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:11.237  7544  7566 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-24 17:08:11.247  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-24 17:08:11.247  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:11.247  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-24 17:08:11.247  7544  7566 D BluetoothSecureManager: getInstant: null
08-24 17:08:11.247  7544  7566 D BluetoothSecureManager: calling getMethod for getService
08-24 17:08:11.247  7544  7566 D BluetoothSecureManager: calling getService
,08-24 17:08:11.247  7544  7566 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3c1b933a
,08-24 17:08:11.247  1015  1476 D BluetoothSecureManagerService: isSecureModeEnabled
08-24 17:08:11.247  1015  1476 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-24 17:08:11.247  7544  7566 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:08:11.247  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 17:08:11.257  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:11.257  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:11.257  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:11.257  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 17:08:11.257  7544  7566 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-24 17:08:11.257  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:11.267  7544  7566 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:11.267  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-24 17:08:11.267  1015  1364 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:11.267  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:11.267  7544  7566 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:11.267  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:11.267  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:11.267  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:11.267  7544  7566 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:11.267  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-24 17:08:11.267  7544  7566 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-24 17:08:11.267  7544  7566 D BluetoothBondStateMachine: make
,08-24 17:08:11.267  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
08-24 17:08:11.267  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-24 17:08:11.267  1870  1870 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:11.277  1015  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:11.277  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.277  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.277  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:11.277  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:11.277  7544  7571 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 17:08:11.277  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-24 17:08:11.277  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 17:08:11.277  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-24 17:08:11.287  1015  1334 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:11.287  1015  1334 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.287  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
08-24 17:08:11.287  1015  1334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.287  1015  1334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.287  1015  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.287  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:11.287  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:11.287  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:11.287  1015  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:11.287  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.287  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-24 17:08:11.287  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.287  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.287  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.287  7544  7544 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:08:11.287  7544  7544 D BtGatt.GattService: Received start request. Starting profile...
08-24 17:08:11.287  7544  7544 D BtGatt.GattService: start()
08-24 17:08:11.287  7544  7544 D BtGatt.GattService: start()
08-24 17:08:11.287  7544  7544 I bluedroid: get_profile_interface gatt
,08-24 17:08:11.287  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
08-24 17:08:11.287  7544  7544 D BtGatt.AdvertiseManager: advertise manager created
,08-24 17:08:11.287  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 17:08:11.287  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:11.287  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:11.297  1015  1554 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:11.297  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.297  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.297  1015  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.297  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.297  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-24 17:08:11.297  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:08:11.297  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:08:11.307  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:11.307  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.307  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:11.307  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.307  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.307  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-24 17:08:11.307  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.307  1015  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 17:08:11.307  7544  7544 D BtGatt.GattService: mStartError = false
08-24 17:08:11.307  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.307  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-24 17:08:11.307  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:11.307  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:08:11.307  7544  7544 D HeadsetService: Received start request. Starting profile...
,08-24 17:08:11.307  7544  7544 D HeadsetService: start()
,08-24 17:08:11.307  7544  7544 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 17:08:11.307  7544  7544 D HeadsetStateMachine: make
,08-24 17:08:11.307  1015  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:11.317  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.317  7544  7544 E HeadsetStateMachine: # of Max HF connection is 2
08-24 17:08:11.317  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.317  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.317  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.317  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-24 17:08:11.317  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 17:08:11.317  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:08:11.327  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:11.327  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.327  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.327  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:11.327  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.327  1015  1094 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-24 17:08:11.327  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.327  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.327  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 17:08:11.327  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:11.327  7544  7566 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:11.327  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.327  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:11.327  1015  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:11.327  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.337  1015  1094 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.337  1015  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.337  1015  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.337  1015  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-24 17:08:11.337  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.337  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.337  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.337  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:11.337  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-24 17:08:11.337  7544  7544 I bluedroid: get_profile_interface handsfree
,08-24 17:08:11.337  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:11.337  7544  7566 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:08:11.347  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:11.347  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.347  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:11.347  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.347  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:11.347  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:11.347  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:08:11.347  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:11.347  7544  7566 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:11.347  7544  7566 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:11.347  7544  7566 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-24 17:08:11.357  7544  7544 I DualScoManager: Instantiating Dual Sco Manager
08-24 17:08:11.357  7544  7544 I DualScoManager: Set HeadsetServiceHelper
08-24 17:08:11.357  7544  7544 D BluetoothAtMessage: createCMTIContentObservers
,08-24 17:08:11.357  1015  3992 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-24 17:08:11.357  1015  3992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:11.357  1015  3992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:11.357  1015  3992 D SettingsProvider: selectionArgs: false
08-24 17:08:11.357  1015  3992 D SettingsProvider: selectionArgs: 1002
08-24 17:08:11.357  1015  3992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:11.357  1015  3992 D SettingsProvider: ret = -1
,08-24 17:08:11.357  7544  7575 D HeadsetStateMachine: Enter Disconnected: -2
,08-24 17:08:11.367  7544  7544 D HeadsetService: mStartError = false
,08-24 17:08:11.367  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.367  7544  7544 D A2dpService: Received start request. Starting profile...
08-24 17:08:11.367  7544  7544 D A2dpService: start()
,08-24 17:08:11.367  7544  7575 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-24 17:08:11.367  7544  7575 D HeadsetStateMachine: map size, before remove : 0
08-24 17:08:11.367  7544  7575 D HeadsetStateMachine: map size, after remove: 0
,08-24 17:08:11.367  7544  7544 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 17:08:11.367  7544  7544 I bluedroid: get_profile_interface avrcp
,08-24 17:08:11.377  7544  7544 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:08:11.377  7544  7544 D Avrcp   : Initialize Media Controller
,08-24 17:08:11.377  7544  7544 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-24 17:08:11.377  7544  7544 E Avrcp   : getActiveSessions
,08-24 17:08:11.377  7544  7544 D Avrcp   : pick active media Controller
,08-24 17:08:11.377  7544  7544 D Avrcp   : Get the active Media Controller 
,08-24 17:08:11.387  7544  7544 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-24 17:08:11.397  7544  7579 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-24 17:08:11.397  7544  7544 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:08:11.397  7544  7544 D A2dpStateMachine: make
,08-24 17:08:11.397  7544  7544 I bluedroid: get_profile_interface a2dp
,08-24 17:08:11.397  7544  7581 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 17:08:11.397  7544  7544 E bt-btif : warning : media task started media_task_refcnt 1 
,08-24 17:08:11.397  7544  7544 D A2dpService: mStartError = false
08-24 17:08:11.397  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.397  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-24 17:08:11.397  7544  7580 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:11.397  7544  7544 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 17:08:11.407  7544  7544 D HidService: Received start request. Starting profile...
08-24 17:08:11.407  7544  7544 D HidService: start()
08-24 17:08:11.407  7544  7544 I bluedroid: get_profile_interface hidhost
08-24 17:08:11.407  7544  7544 D HidService: setHidService(): set to: null
08-24 17:08:11.407  7544  7544 D HidService: mStartError = false
08-24 17:08:11.407  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.407  7544  7544 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 17:08:11.407  7544  7544 D HealthService: Received start request. Starting profile...
08-24 17:08:11.407  7544  7544 D HealthService: start()
,08-24 17:08:11.407  7544  7544 I bluedroid: get_profile_interface health
08-24 17:08:11.407  7544  7579 D BluetoothMediaBrowser: no now playing list
08-24 17:08:11.407  7544  7544 D HealthService: mStartError = false
08-24 17:08:11.407  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.407  7544  7544 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 17:08:11.407  7544  7544 D PanService: Received start request. Starting profile...
08-24 17:08:11.407  7544  7544 D PanService: start()
08-24 17:08:11.407  7544  7544 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:11.407  7544  7544 I bluedroid: get_profile_interface pan
,08-24 17:08:11.417  7544  7579 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1,
,08-24 17:08:11.417  7544  7544 D PanService: mStartError = false
08-24 17:08:11.417  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
08-24 17:08:11.417  7544  7544 D HeadsetStateMachine: Try to query the phonestate on bind
,08-24 17:08:11.417  1421  7513 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 17:08:11.417  1421  1421 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-24 17:08:11.417  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 17:08:11.417  1421  7513 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 17:08:11.417  7544  7544 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:11.417  7544  7544 D BluetoothMapService: start()
,08-24 17:08:11.427  7544  7544 D BluetoothMapService: mStartError = false
08-24 17:08:11.427  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:11.427  7544  7544 D HeadsetStateMachine: Proxy object connected
08-24 17:08:11.427  7544  7544 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-24 17:08:11.427  7544  7544 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-24 17:08:11.427  7544  7575 D HeadsetStateMachine: Disconnected process message: 11
,08-24 17:08:11.427  7544  7544 D SapService: Received start request. Starting profile...
08-24 17:08:11.427  7544  7544 D SapService: start()
08-24 17:08:11.427  7544  7544 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 17:08:11.427  7544  7544 I bluedroid: get_profile_interface sap
08-24 17:08:11.427  7544  7544 D SapService: mStartError = false
08-24 17:08:11.427  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
08-24 17:08:11.427  7544  7544 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 17:08:11.427  7544  7544 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-24 17:08:11.427  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 17:08:11.427  7544  7544 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 17:08:11.427  7544  7544 D BluetoothA2dp: Proxy object connected
08-24 17:08:11.427  7544  7544 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-24 17:08:11.427  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 17:08:11.427  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-24 17:08:11.427  7544  7575 D HeadsetStateMachine: Disconnected process message: 18
08-24 17:08:11.427  7544  7575 D HeadsetStateMachine: Disconnected process message: 10
08-24 17:08:11.427  7544  7575 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:08:11.427  7544  7575 D HeadsetStateMachine: Disconnected process message: 11
,08-24 17:08:11.427  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:11.427  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-24 17:08:11.427  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-24 17:08:11.447  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:11.457  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-24 17:08:11.457  7544  7544 E BluetoothAdapterService(1016668845): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-24 17:08:11.457  7544  7566 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-24 17:08:11.457  7544  7566 I bluedroid: enable
,08-24 17:08:11.457  7544  7566 I bt_hci_bdroid: init
,08-24 17:08:11.457  7544  7566 I bt_vendor: bt-vendor : init
08-24 17:08:11.457  7544  7566 I bt_vendor: bt-vendor : get_bt_soc_type
,08-24 17:08:11.457  7544  7566 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-24 17:08:11.467  7544  7585 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 17:08:11.467  7544  7566 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-24 17:08:11.467  7544  7566 D bt_userial_mct: userial_init
,08-24 17:08:11.467  7544  7566 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 17:08:11.467  7544  7566 I bt_vendor: Starting hciattach daemon
08-24 17:08:11.467  7544  7566 I bt_vendor: try to set false
,08-24 17:08:11.467  7544  7566 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 17:08:11.467  7544  7566 I bt_vendor: Starting hciattach daemon
,08-24 17:08:11.467  7544  7566 I bt_vendor: try to set true
,08-24 17:08:11.477  7589  7589 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-24 17:08:11.527  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-24 17:08:11.527  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-24 17:08:11.547  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-24 17:08:11.557  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-24 17:08:11.567  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-24 17:08:11.567  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-24 17:08:11.757  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-24 17:08:11.767  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-24 17:08:11.827  7544  7566 I bt_vendor: bluetooth satus is on,
08-24 17:08:11.827  7544  7587 D bt_userial_mct: userial_open(port:0)
08-24 17:08:11.827  7544  7587 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,08-24 17:08:11.827  7544  7587 I bt_vendor: Done intiailizing UART
08-24 17:08:11.827  7544  7587 I bt_vendor: Done intiailizing UART,
08-24 17:08:11.827  7544  7587 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 17:08:11.827  7544  7587 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-24 17:08:11.837  7544  7608 D bt_userial_mct: Entering userial_read_thread()
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_HCI,
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_A2D,
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_PAN
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_SAP
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_SDP
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_SMP
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 17:08:11.837  7544  7585 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-24 17:08:11.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:08:11.927  7544  7585 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-24 17:08:11.927  7544  7585 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42e8ed1 
,08-24 17:08:11.927  7544  7585 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42e8ed1 
,08-24 17:08:11.947  7544  7569 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-24 17:08:11.947  7544  7569 E bt-btif : Calling BTA_HhEnable
,08-24 17:08:11.947  7544  7569 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-24 17:08:11.947  7544  7569 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-24 17:08:11.947  7544  7569 E BluetoothServiceJni: populateRssiValuesNative
08-24 17:08:11.947  7544  7569 I bluedroid: getModelRssiValues
,08-24 17:08:11.957  7544  7569 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 17:08:11.957  7544  7569 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 17:08:11.957  1015  1015 D SettingsProvider: name = bluetooth_name
,08-24 17:08:11.957  7544  7569 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-24 17:08:11.957  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:11.967  7544  7569 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 17:08:11.967  7544  7569 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:11.967  7544  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:11.967  7544  7569 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-24 17:08:11.967  7544  7569 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-24 17:08:11.967  7544  7569 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-24 17:08:11.967  7544  7569 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-24 17:08:11.967  7544  7569 E bt-btif : btif_sock_init: !vhci_init
,08-24 17:08:11.967  7544  7569 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-24 17:08:11.977  7544  7569 D IOP_DB_BT: db_open: db_open : handle 3028299792l, read 13894 bytes onto local cache
08-24 17:08:11.977  7544  7569 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-24 17:08:11.977  7544  7569 D IOP_DB_BT: db_query: result 1
08-24 17:08:11.977  7544  7569 I         : iop_db_open: iop_db_open status 0
,08-24 17:08:11.977  7544  7569 D bte_conf: Device ID record 1 : primary
08-24 17:08:11.977  7544  7569 D bte_conf:   vendorId            = 0075
08-24 17:08:11.977  7544  7569 D bte_conf:   vendorIdSource      = 0001
08-24 17:08:11.977  7544  7569 D bte_conf:   product             = 0100
08-24 17:08:11.977  7544  7569 D bte_conf:   version             = 0200
08-24 17:08:11.977  7544  7569 D bte_conf:   clientExecutableURL = 
08-24 17:08:11.977  7544  7569 D bte_conf:   serviceDescription  = 
08-24 17:08:11.977  7544  7569 D bte_conf:   documentationURL    = 
08-24 17:08:11.977  7544  7569 D bte_conf: bte_load_did_conf no section named DID2.
,08-24 17:08:11.977  7544  7566 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-24 17:08:11.977  7544  7566 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:11.977  7544  7566 D BluetoothAdapterProperties: State =  11
,08-24 17:08:11.977  7544  7608 E bt_mct  : hci lib postload completed
,08-24 17:08:11.977  1015  1364 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 17:08:11.977  7544  7566 D BluetoothAdapterProperties: Setting state to 12
,08-24 17:08:11.977  7544  7566 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:08:11.987  7544  7569 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:11.987  7544  7569 D BluetoothAdapterProperties: Scan Mode:21
08-24 17:08:11.987  7544  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:11.987  7544  7569 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:11.987  1015  1476 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-24 17:08:11.987  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:11.987  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:11.987  1015  1476 D SettingsProvider: selectionArgs: false
08-24 17:08:11.987  1015  1476 D SettingsProvider: selectionArgs: 1002
08-24 17:08:11.987  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:11.987  1015  1476 D SettingsProvider: ret = -1
,08-24 17:08:11.987  7544  7566 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:11.987  7544  7566 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 17:08:11.987  1015  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:11.987  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:11.997  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.997  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:11.997  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:11.997  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:11.997  4063  4077 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:11.997  7544  7566 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:11.997  7544  7566 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 17:08:11.997  7544  7566 D BluetoothAdapterService: starting service from this receiver
,08-24 17:08:11.997  4063  4077 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:11.997  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:12.007  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.007  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.007  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.007  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.007  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:12.007  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:12.007  7544  7566 I BluetoothAdapterState: Entering On State from state = 11
,08-24 17:08:12.007  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 17:08:12.017  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.017  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.017  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.017  4063  4071 D Bluetoothsap: onBluetoothStateChange: up=true
,08-24 17:08:12.017  4063  4071 D Bluetoothsap: Binding service...
,08-24 17:08:12.017  4063  4063 D BluetoothA2dp: Proxy object connected
,08-24 17:08:12.017  4063  4063 D A2dpProfile: Bluetooth service connected
,08-24 17:08:12.017  4063  4071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 17:08:12.027  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-24 17:08:12.027  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.027  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.027  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.027  7544  7544 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-24 17:08:12.027  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.027  4063  4071 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-24 17:08:12.027  7544  7558 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:12.037  1421  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.037  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:12.037  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.037  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.037  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:12.037  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.037  1421  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.037  1438  2015 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:12.037  1438  2015 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.037  1176  1185 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:12.037  1176  1185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:12.037  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.037  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:12.037  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.037  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.047  4063  4074 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.047  7544  7544 I BluetoothPbapService: Handler(): got msg=1
,08-24 17:08:12.047  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:12.047  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.047  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.047  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.047  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.047  1015  1334 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-24 17:08:12.047  4063  4074 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.047  6774  7187 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:12.047  6774  7187 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.047  4063  4077 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 17:08:12.047  4063  4063 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-24 17:08:12.057  4063  4063 D SapProfile: Bluetooth service connected
,08-24 17:08:12.057  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-24 17:08:12.057  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.057  4063  4063 D Bluetoothsap: getConnectedDevices()
08-24 17:08:12.057  7544  7612 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 17:08:12.057  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.057  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.057  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.057  7544  7570 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.057  7544  7570 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:12.057  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:12.057  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.057  4063  7186 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:12.057  4063  4063 D HeadsetProfile: Bluetooth service connected
,08-24 17:08:12.057  7544  7612 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 17:08:12.057  7544  7612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:12.057  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-24 17:08:12.057  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-24 17:08:12.057  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.057  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.057  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.067  4063  4071 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 17:08:12.067  4063  4063 D BluetoothInputDevice: Proxy object connected
08-24 17:08:12.067  7544  7612 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-24 17:08:12.067  7544  7612 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:12.067  7544  7612 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:12.067  7544  7612 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9c4669f
08-24 17:08:12.067  7544  7612 D BluetoothSocket: channel: 19
08-24 17:08:12.067  7544  7612 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 17:08:12.067  4063  4063 D HidProfile: Bluetooth service connected
,08-24 17:08:12.067  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-24 17:08:12.067  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.067  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.067  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.067  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.067  1421  7513 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.067  1421  7513 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.077  1421  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.077  4063  4063 D BluetoothMap: Proxy object connected
,08-24 17:08:12.077  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:12.077  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.077  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.077  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.077  4063  4063 D MapProfile: Bluetooth service connected
08-24 17:08:12.077  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.077  4063  4063 D BluetoothMap: getConnectedDevices()
,08-24 17:08:12.077  1421  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.077  2041  2584 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.077  2041  2584 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:12.077  4063  7186 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.077  4063  7186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.077  1438  1849 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.087  4063  4063 D BluetoothPbap: Proxy object connected
08-24 17:08:12.087  4063  4063 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:12.087  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:12.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.087  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.087  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.087  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.087  1438  1849 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.087  1015  1044 D BluetoothPan: Binding service...
,08-24 17:08:12.087  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-24 17:08:12.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.087  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:12.097  1427  1442 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.097  1427  1442 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:12.097  7453  7469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:12.097  7453  7469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:12.097  1421  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.097  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:12.097  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:12.097  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.097  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.097  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.097  1421  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:12.097  4063  4077 D BluetoothPan: Binding service...,
,08-24 17:08:12.097  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-24 17:08:12.097  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.107  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.107  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.107  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.107  4063  4063 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:12.107  4063  4063 D PanProfile: Bluetooth service connected
,08-24 17:08:12.107  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:12.107  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:12.107  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:12.107  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.107  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 17:08:12.107  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-24 17:08:12.107  1015  1015 D BluetoothA2dp: Proxy object connected
,08-24 17:08:12.117  1421  1421 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@7fd369a, true
,08-24 17:08:12.117  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:08:12.117  1421  1421 D BluetoothHeadset: registerMessageListener
08-24 17:08:12.117  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:12.117  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 17:08:12.117  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-24 17:08:12.117  1870  1870 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:12.127  1015  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:08:12.127  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.127  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:12.127  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.127  7544  7570 D HeadsetService: registerMessageListener
,08-24 17:08:12.127  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:12.127  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-24 17:08:12.127  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:12.127  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-24 17:08:12.137  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-24 17:08:12.137  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:08:12.137  7544  7570 D HeadsetService: registerMessageListener,
,08-24 17:08:12.137  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:08:12.137  1015  1494 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-24 17:08:12.137  7544  7575 D HeadsetStateMachine: Disconnected process message: 70
08-24 17:08:12.137  7544  7575 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3dde53ec
,08-24 17:08:12.137  1421  1421 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-24 17:08:12.137  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-24 17:08:12.137  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:12.137  4063  4063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:12.137  1421  1421 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 17:08:12.137  1421  1421 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-24 17:08:12.137  1421  1421 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-24 17:08:12.147  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:12.147  7544  7616 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-24 17:08:12.147  7544  7575 D HeadsetStateMachine: Disconnected process message: 9
,08-24 17:08:12.147  7544  7575 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 17:08:12.147  4063  4063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-24 17:08:12.147  4063  4063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-24 17:08:12.147  4063  4063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-24 17:08:12.147  4063  4063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-24 17:08:12.147  7544  7616 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:12.147  1176  1763 D BluetoothTile:  handleUpdatestate:false name:null
08-24 17:08:12.147  7544  7616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:12.147  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:12.157   282   691 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-24 17:08:12.157   282   691 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 17:08:12.157   282   691 V voice   : voice_set_parameters: exit with code(-2)
08-24 17:08:12.157   282   691 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 17:08:12.157   282   691 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 17:08:12.157   282   691 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 17:08:12.157   282   691 V audio_hw_primary: adev_set_parameters: exit
,08-24 17:08:12.157  7544  7575 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-24 17:08:12.157  7544  7616 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-24 17:08:12.157  7544  7616 D BluetoothSocket: bindListen(), new LocalSocket 
,08-24 17:08:12.157  7544  7616 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:12.157  7544  7616 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29c3d3b5
08-24 17:08:12.157  7544  7616 D BluetoothSocket: channel: 5
,08-24 17:08:12.157  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:12.157  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:12.157  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10eab1bb added. We now have 8 listener(s)
08-24 17:08:12.157  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:12.157  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:12.157  1015  1364 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 17:08:12.167  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.167  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.167  1015  3992 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:08:12.167  1015  3992 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 17:08:12.167  1015  3992 D SecContentProvider2: mCursor = null
,08-24 17:08:12.167  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.167  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:12.167  1015  3992 D WifiService: setWifiEnabled: false pid=6774, uid=10171
,08-24 17:08:12.167  1015  3992 D SettingsProvider: name = wifi_on,
,08-24 17:08:12.177  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:12.177  4063  4063 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:12.187  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:12.187  1015  1474 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:08:12.187  1015  1474 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:08:12.187  1015  1474 D SecContentProvider2: mCursor = null
,08-24 17:08:12.187  1015  1474 D WifiService: setWifiEnabled: true pid=6774, uid=10171
08-24 17:08:12.187  1015  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:12.187  1015  1474 W WifiService: Failed getting userId using ActivityManagerNative
08-24 17:08:12.187  1015  1474 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:12.187  1015  1474 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:12.187  1015  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:08:12.187  1015  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:08:12.187  1015  1474 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:08:12.187  1015  1474 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:08:12.187  1015  1474 D SettingsProvider: name = wifi_on
,08-24 17:08:12.187  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:12.187  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 17:08:12.197  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-24 17:08:12.197  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:12.197  7544  7544 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:08:12.197  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:12.197  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.197  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.197  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:12.197  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:12.217  2041  2041 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:12.217  1015  1554 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:08:12.217  1015  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-24 17:08:12.227  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.227  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:12.227  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:12.227  1015  1474 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 17:08:12.237  2041  7626 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-24 17:08:12.237  2041  2041 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-24 17:08:12.247  7544  7629 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 17:08:12.247  7544  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:12.247  7544  7629 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-24 17:08:12.247  7544  7629 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:12.247  7544  7629 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:12.247  7544  7629 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3eaaf631
,08-24 17:08:12.247  7544  7629 D BluetoothSocket: channel: 12
08-24 17:08:12.247  7544  7629 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:12.387  1015  1473 I art     : Explicit concurrent mark sweep GC freed 20183(1143KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.802ms total 146.805ms
,08-24 17:08:12.387  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:12.397  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:12.397  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:12.397  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:12.407  1015  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:12.407  1015  1554 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:12.407  1015  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:08:12.407  1015  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:08:12.417  2041  7626 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-24 17:08:12.457  1015  3343 D SSRM:n  : SIOP:: AP = 330
,08-24 17:08:12.507  1015  2095 V SAMP_SPCM_test: CSC File load.. 
,08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-24 17:08:12.527  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time,
,08-24 17:08:12.537  1015  1042 D Tethering: interfaceAdded wlan0
,08-24 17:08:12.547  1015  1128 E Tethering: No numeric data,
08-24 17:08:12.547  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:12.547  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:12.547  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:12.567  1015  1042 D Tethering: interfaceAdded p2p0
,08-24 17:08:12.567  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-24 17:08:12.577  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:12.577   274   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-24 17:08:12.577   274   983 D SoftapController: Softap fwReload - Ok
,08-24 17:08:12.587  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:12.587  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:08:12.587   274   983 D CommandListener: Setting iface cfg
08-24 17:08:12.587   274   983 D CommandListener: Trying to bring down wlan0
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-24 17:08:12.587   274   983 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location,
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email,
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,08-24 17:08:12.587  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-24 17:08:12.597  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-24 17:08:12.597  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-24 17:08:12.597  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-24 17:08:12.597  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control,
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-24 17:08:12.607  1015  2095 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-24 17:08:12.607  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:08:12.607  1015  1128 D Tethering: clearTetheredNotification()
08-24 17:08:12.607  1015  1128 D Tethering: InitialState.processMessage what=4
,08-24 17:08:12.607  1015  1128 E Tethering: No numeric data
,08-24 17:08:12.617  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:12.617  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:08:12.617  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:08:12.617  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:08:12.617  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:12.617  1015  2095 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-24 17:08:12.617  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:12.617  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-24 17:08:12.617  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:12.627  1015  2095 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:12.627  1015  2095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:12.627  1015  2095 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:12.627  1015  2095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:12.637  7638  7638 E Zygote  : MountEmulatedStorage(),
08-24 17:08:12.637  1015  2095 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7638 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:08:12.637  7638  7638 E Zygote  : v2
08-24 17:08:12.637  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:08:12.637  1015  1128 D Tethering: clearTetheredNotification()
08-24 17:08:12.637  7638  7638 I libpersona: KNOX_SDCARD checking this for 1000
,08-24 17:08:12.637  7638  7638 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:12.637  7638  7638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:12.647  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-24 17:08:12.647  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:08:12.647  7638  7638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:08:12.647  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:12.647  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:12.647  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:12.647  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:12.647  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:12.647  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:12.647  7638  7638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:08:12.657  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:12.657  1015  1122 V NetworkStats: performPollLocked() took 5ms
,08-24 17:08:12.657  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:12.657  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-24 17:08:12.657  7637  7637 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-24 17:08:12.657  7637  7637 I wpa_supplicant: Successfully initialized wpa_supplicant
08-24 17:08:12.657  7637  7637 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-24 17:08:12.677  7637  7637 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-24 17:08:12.677   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7637,
08-24 17:08:12.677   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:08:12.677  7637  7637 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-24 17:08:12.677  7637  7637 I wpa_supplicant: ssSupport state is = 1
,08-24 17:08:12.677  7637  7637 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 17:08:12.677  7637  7637 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-24 17:08:12.677   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7637
08-24 17:08:12.677   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-24 17:08:12.687  7638  7638 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:08:12.687  7638  7638 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:12.697  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 17:08:12.707  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:12.707  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:08:12.707  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:12.707  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:12.707  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:12.707  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:12.707  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:12.707  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-24 17:08:12.707  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:12.707  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:12.707  7638  7638 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 17:08:12.707  1176  1176 D HotspotTile: onReceive : 2, 0
,08-24 17:08:12.707  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:12.717  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:12.717  1015  3992 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:12.717  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:12.717  1015  3992 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:08:12.717  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:12.717  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:12.727  1619  1619 I Hs20UtilService: Starting #19,
,08-24 17:08:12.727  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:08:12.727  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:08:12.727  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-24 17:08:12.737  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1,
08-24 17:08:12.737  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:08:12.767  1015  2095 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-24 17:08:12.837   287   287 E SMD     : DCD OFF,
,08-24 17:08:12.857   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-24 17:08:12.857  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-24 17:08:12.857   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:08:12.907  7637  7637 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 17:08:12.907  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:12.917  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-24 17:08:12.917   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7637
08-24 17:08:12.917   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 17:08:12.917  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 17:08:12.917  7637  7637 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:12.917  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:12.917  7637  7637 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:12.917  7637  7637 E wpa_supplicant: SIM READ ERROR
08-24 17:08:12.917  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:12.917  7637  7637 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:12.917  7637  7637 E wpa_supplicant: SIM READ ERROR
08-24 17:08:12.917  7637  7637 I wpa_supplicant: Blacklist: Clear (all) 
08-24 17:08:12.917  7637  7637 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:08:12.917  7637  7637 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 17:08:12.917  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:12.917  7637  7637 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-24 17:08:12.917  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:12.917  7637  7637 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-24 17:08:12.917  7637  7637 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-24 17:08:12.927  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:08:12.927  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:12.927  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:13.057  7637  7637 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-24 17:08:13.187  7637  7637 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-24 17:08:13.187  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:13.197  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-24 17:08:13.197   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7637
08-24 17:08:13.197   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 17:08:13.197  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
,08-24 17:08:13.197  7637  7637 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:13.197  7637  7637 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 17:08:13.197  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:13.217  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-24 17:08:13.217   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7637
08-24 17:08:13.217   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 17:08:13.217  7637  7637 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-24 17:08:13.217  7637  7637 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:13.217  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-24 17:08:13.217  7637  7637 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:13.217  7637  7637 E wpa_supplicant: SIM READ ERROR
,08-24 17:08:13.217  7637  7637 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:08:13.217  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:13.217  7637  7637 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 17:08:13.217  7637  7637 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 17:08:13.217  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:13.217  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:13.217  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:08:13.217  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:13.217  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:08:13.297  7637  7637 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-24 17:08:13.297  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 17:08:13.337  7637  7637 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-24 17:08:13.337  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-24 17:08:13.337  7637  7637 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 17:08:13.347  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-24 17:08:13.347  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:08:13.347  7637  7637 I wpa_supplicant: HOTSPOT20_ENABLE called
08-24 17:08:13.347  7637  7637 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:13.347  7637  7637 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:13.347  7637  7637 E wpa_supplicant: SIM READ ERROR
08-24 17:08:13.347  7637  7637 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:08:13.367  7637  7637 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-24 17:08:13.377  7637  7637 I wpa_supplicant: Skip scan - bUseNetwork false
08-24 17:08:13.377  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:13.377  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-24 17:08:13.377  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:13.377  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:13.377  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:08:13.377  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:13.377  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:13.377  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-24 17:08:13.387  1176  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:13.377  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-24 17:08:13.387  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:13.387  1176  1176 D HotspotTile: onReceive : 3, 0
,08-24 17:08:13.387  4063  4063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:13.397  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:13.397  1015  1125 E WifiConfigStore: Not a HS20
,08-24 17:08:13.397  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:13.397  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 17:08:13.407  1015  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:08:13.407  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:08:13.407  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-24 17:08:13.407  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.407  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:13.407  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:13.407  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-24 17:08:13.407  7637  7637 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 17:08:13.407  7637  7637 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 17:08:13.407  7637  7637 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:08:13.407  7637  7637 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 17:08:13.407  7637  7637 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 17:08:13.407  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
08-24 17:08:13.417  7637  7637 I wpa_supplicant: First Scan Start
08-24 17:08:13.417  7637  7637 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 17:08:13.417  1619  1619 I Hs20UtilService: Starting #20
,08-24 17:08:13.417  1619  1635 I Hs20UtilService: Message received 5011
,08-24 17:08:13.417  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-24 17:08:13.417  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:08:13.417  6590  6590 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:13.417  6590  6590 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:08:13.417  6590  6590 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-24 17:08:13.417  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:08:13.417  1015  1125 I WifiNative-HAL: startHal
08-24 17:08:13.417  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d33d88c
08-24 17:08:13.417  1015  1125 I WifiNative-HAL: Could not start hal
,08-24 17:08:13.417  7035  7035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:13.427  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:08:13.427  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-24 17:08:13.427   274   983 D CommandListener: Setting iface cfg
08-24 17:08:13.427  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-24 17:08:13.427   274   983 D CommandListener: Trying to bring up p2p0
,08-24 17:08:13.427  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 17:08:13.427  1015  1124 D WifiP2pService: P2pEnablingState
,08-24 17:08:13.427  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 17:08:13.427  1015  1124 D WifiP2pService: P2p socket connection successful
08-24 17:08:13.427  1015  1124 D WifiP2pService: P2pEnabledState
,08-24 17:08:13.427  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:08:13.427  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:08:13.427  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-24 17:08:13.437  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:08:13.437  1015  1015 D RttService: SCAN_AVAILABLE : 3
,08-24 17:08:13.437  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:08:13.437  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-24 17:08:13.437  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:08:13.437  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-24 17:08:13.437  7637  7637 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 17:08:13.437  1015  1147 D WifiScanningService: DefaultState got{ when=-4ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:13.437  1015  1147 I WifiNative-HAL: startHal
,08-24 17:08:13.437  7637  7637 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-24 17:08:13.437  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e3e59bc
08-24 17:08:13.437  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:08:13.437  1015  1147 I WifiNative-HAL: Could not start hal
08-24 17:08:13.437  1015  1147 E WifiScanningService: could not start HAL
,08-24 17:08:13.437  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-24 17:08:13.437  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-24 17:08:13.437  7637  7637 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-24 17:08:13.437  1015  1125 E WifiStateMachine: Failed to set frequency band 0
,08-24 17:08:13.437  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-24 17:08:13.437  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:13.437  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:13.437  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:08:13.437  1015  1045 D WifiDisplayController: disconnect
08-24 17:08:13.437  1015  1045 D WifiDisplayController: updateConnection
08-24 17:08:13.437  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-24 17:08:13.437  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:13.447  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-24 17:08:13.447  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-24 17:08:13.447  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:13.447  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:13.447  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:08:13.447  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-24 17:08:13.457  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:08:13.457  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:08:13.457  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:08:13.457  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 17:08:13.457  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  secondary type: null
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  wps: 0
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  grpcapab: 0
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  devcapab: 0
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  status: 3
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  wfdInfo: null,
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-24 17:08:13.457  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-24 17:08:13.457  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:13.457  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 17:08:13.457  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:08:13.457  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:13.457  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-24 17:08:13.457  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:13.457  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:13.457  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:08:13.457  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:13.467  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:08:13.467  7002  7002 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 17:08:13.467  7002  7002 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:08:13.477  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-24 17:08:13.477  7017  7017 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-24 17:08:13.477  1015  1124 D WifiP2pService: InactiveState
,08-24 17:08:13.477  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:08:13.477  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:08:13.477  7637  7637 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 17:08:13.477  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:08:13.477  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:08:13.547  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:13.547  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:13.547  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:08:13.857   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:14.197  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:14.207  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:14.207  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 17:08:14.207  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 17:08:14.217  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34f5111d Bundle[{}]
,08-24 17:08:14.217  6774  6828 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 17:08:14.217  6774  6828 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 17:08:14.217  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 17:08:14.217  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 17:08:14.217  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 17:08:14.217  6774  6828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:08:14.227  6774  6828 I System.out: Running OutgoingSocketThread
,08-24 17:08:14.227  6774  7661 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1355)
,08-24 17:08:14.227  6774  7661 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45684
,08-24 17:08:14.227  6774  7661 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 17:08:14.677  7637  7637 I wpa_supplicant: nl80211: Received scan results (34 BSSes),
08-24 17:08:14.677  7637  7637 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 17:08:14.677  7637  7637 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-24 17:08:14.677  7637  7637 I wpa_supplicant: Trying to associate with  'G700'
08-24 17:08:14.677  7637  7637 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-24 17:08:14.677  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-24 17:08:14.677  1015  7659 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-24 17:08:14.697  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:14.697  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:14.797  7637  7637 E wpa_supplicant: Cmd 35605 not handled
,08-24 17:08:14.807  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.807  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.807  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:14.807  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 17:08:14.807  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.807  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:08:14.807  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:14.807  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.807  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:14.807  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:08:14.807  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:08:14.807  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-24 17:08:14.807  7637  7637 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-24 17:08:14.807  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-24 17:08:14.807  7637  7637 I wpa_supplicant: Associated with F4.99.3E
,08-24 17:08:14.807  7637  7637 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 17:08:14.807  7637  7637 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-24 17:08:14.807  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:14.807  1015  1128 E Tethering: No numeric data,
08-24 17:08:14.817  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:08:14.817  1015  1128 D Tethering: clearTetheredNotification()
,08-24 17:08:14.817  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:14.817  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.817  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 17:08:14.817  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:14.817  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:08:14.817  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-24 17:08:14.817  1015  1122 V NetworkStats: performPollLocked() took 5ms
,08-24 17:08:14.827  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.827  7637  7637 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 17:08:14.827  7637  7637 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-24 17:08:14.827  7637  7637 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-24 17:08:14.827  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-24 17:08:14.827  7637  7637 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:08:14.827  7637  7637 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 17:08:14.827  7637  7637 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-24 17:08:14.827  7637  7637 I wpa_supplicant: Blacklist: Clear (temp) 
08-24 17:08:14.827  7637  7637 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:14.827  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:14.827  1015  1125 D SecContentProvider2: mCursor = null
08-24 17:08:14.827  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-24 17:08:14.827  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:14.827  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:14.827  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:08:14.827  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-24 17:08:14.827  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:14.827  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:14.837  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-24 17:08:14.837  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-24 17:08:14.847  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-24 17:08:14.847  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:14.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.847  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-24 17:08:14.847  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-24 17:08:14.847  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:08:14.847  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
,08-24 17:08:14.847  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:14.847  1015  1364 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:14.847  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:14.847  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:14.847  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:14.857  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:14.857  1619  1619 I Hs20UtilService: Starting #21
,08-24 17:08:14.857  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:08:14.857  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:14.857  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:14.857  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:08:14.857  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:08:14.857  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:14.857  4063  4063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:08:14.867  4063  4165 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:14.867  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:14.877   274   983 D CommandListener: Setting iface cfg
,08-24 17:08:14.877  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-24 17:08:14.877  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:08:14.877  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:14.887  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:14.887  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:14.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:14.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:14.897  1015  1125 E WifiNative-wlan0: do suspend false
,08-24 17:08:14.897  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-24 17:08:14.897  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:14.897  1015  1125 D SecContentProvider2: mCursor = null
,08-24 17:08:14.897  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:08:15.117  7664  7664 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 17:08:15.117  7664  7664 I dhcpcd  : version 5.5.6 starting
,08-24 17:08:15.117  7664  7664 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 17:08:15.177  7664  7664 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-24 17:08:15.177  7664  7664 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-24 17:08:15.177  7664  7664 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-24 17:08:15.177  7664  7664 I dhcpcd  : bssid match,
08-24 17:08:15.177  7664  7664 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-24 17:08:15.227  6774  6828 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1356)
08-24 17:08:15.227  6774  6828 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1356)
08-24 17:08:15.227  7664  7664 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-24 17:08:15.227  6774  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1361)
08-24 17:08:15.227  6774  6828 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 17:08:15.227  6774  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1362)
,08-24 17:08:15.237  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:15.237  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b6d6d8 added. We now have 2 listener(s)
,08-24 17:08:15.237  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:08:15.237  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.237  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:15.237  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:15.237  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215f7a31 added. We now have 9 listener(s)
08-24 17:08:15.237  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:15.237  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:15.247  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.247  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.247  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:15.247  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:15.257  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.257  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2888ae97 added. We now have 3 listener(s)
,08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e8884 added. We now have 10 listener(s)
,08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.257  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:15.257  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:15.257  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:15.257  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.257  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:15.257  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b6d6d8 removed from the list
08-24 17:08:15.257  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.257  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215f7a31 removed from the list
08-24 17:08:15.257  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:15.257  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.267  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:15.267  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:15.267  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215f7a31 not in the list
08-24 17:08:15.267  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:15.267  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:15.267  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e8884 removed from the list
08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.267  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:15.267  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.267  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.267  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2888ae97 removed from the list
,08-24 17:08:15.267  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:15.267  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1680886d added. We now have 2 listener(s)
,08-24 17:08:15.277  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:08:15.277  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.277  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.277  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.277  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f997ca2 added. We now have 9 listener(s)
08-24 17:08:15.277  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.277  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:15.277  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.277  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.287  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:15.287  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:15.287  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.287  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114da8f0 added. We now have 3 listener(s)
,08-24 17:08:15.287  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.287  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.287  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:08:15.297  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 17:08:15.297  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.297  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:15.297  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212a3e69 added. We now have 10 listener(s)
08-24 17:08:15.297  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.297  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:15.297  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 17:08:15.297  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:15.297  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:15.297  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:15.297  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:15.307  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:15.307  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:15.307  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:15.307  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:08:15.307  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:15.307  7544  7555 D BtGatt.GattService: registerClient() - UUID=1f8d6876-cb8c-4c5d-b6a3-346c359f519a
,08-24 17:08:15.357  7544  7569 D BtGatt.GattService: onClientRegistered() - UUID=1f8d6876-cb8c-4c5d-b6a3-346c359f519a, clientIf=6,
08-24 17:08:15.357  6774  7187 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:08:15.357  7544  7613 D BtGatt.GattService: start scan with filters
,08-24 17:08:15.357  7544  7574 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:15.357  7544  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c9922ad
,08-24 17:08:15.367  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:15.367  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:15.367  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:15.367  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:15.367  7544  7569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 17:08:15.367  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.367  7544  7574 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:15.367  7544  7574 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:08:15.367  7544  7574 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-24 17:08:15.367  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:08:15.367  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.367  7544  7574 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:08:15.367  7544  7574 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-24 17:08:15.377  7664  7664 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-24 17:08:15.377  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:15.377  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:15.377  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:15.377  7544  7569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-24 17:08:15.377  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.377  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:15.377  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 17:08:15.387  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.387  6774  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:15.387  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:15.387  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:08:15.387  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.387  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:15.387  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 17:08:15.387  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:15.387  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:15.387  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:15.387  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:08:15.387  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:15.397  7544  7615 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:15.397  7544  7558 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:08:15.397  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:15.397  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:15.397  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:15.397  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:15.397  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:15.397  7544  7574 D BtGatt.ScanManager: filter size is 1
,08-24 17:08:15.407  7544  7574 D BtGatt.ScanManager: delete FilterIndex - 3
,08-24 17:08:15.407  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-24 17:08:15.407  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:15.407  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 17:08:15.407  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:08:15.407  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:15.407  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:15.407  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:15.407  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-24 17:08:15.407  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:08:15.407  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.417  7544  7574 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:15.417  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 17:08:15.417  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.417  7544  7574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:08:15.417  7544  7569 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:08:15.417  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.427  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-24 17:08:15.427  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:15.427  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:15.427  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.427  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.427  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:15.427  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.427  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1680886d removed from the list
08-24 17:08:15.427  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:15.427  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f997ca2 removed from the list
08-24 17:08:15.427  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:15.427  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.427  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.427  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.437  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f997ca2 not in the list
08-24 17:08:15.437  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212a3e69 removed from the list
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.437  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.437  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.437  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114da8f0 removed from the list
,08-24 17:08:15.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.437  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f5825 added. We now have 2 listener(s)
,08-24 17:08:15.457  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-24 17:08:15.457  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.457  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.457  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3951fdfa added. We now have 9 listener(s)
,08-24 17:08:15.457  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.457  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:15.457  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.467  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.467  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:15.467  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:15.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1579a608 added. We now have 3 listener(s)
,08-24 17:08:15.467  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-24 17:08:15.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-24 17:08:15.467  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279251a1 added. We now have 10 listener(s)
08-24 17:08:15.467  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.467  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:15.467  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-24 17:08:15.467  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:15.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:15.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:15.467  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:08:15.477  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-24 17:08:15.477  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-24 17:08:15.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:15.487  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:15.497  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:08:15.497  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:15.497  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:15.497  7544  7555 D BtGatt.GattService: registerClient() - UUID=1ebc4a1d-2bf3-4f67-8a29-26e709f0025e
,08-24 17:08:15.547  7544  7569 D BtGatt.GattService: onClientRegistered() - UUID=1ebc4a1d-2bf3-4f67-8a29-26e709f0025e, clientIf=6
08-24 17:08:15.547  6774  6782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 17:08:15.547  7544  7614 D BtGatt.GattService: start scan with filters
,08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: handling starting scan,
08-24 17:08:15.557  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:15.557  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:15.557  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:15.557  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-24 17:08:15.557  7544  7569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 17:08:15.557  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6,
,08-24 17:08:15.557  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 17:08:15.557  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-24 17:08:15.557  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:15.557  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-24 17:08:15.557  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:15.557  7544  7574 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:08:15.567  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:15.567  7544  7569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:08:15.567  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.567  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-24 17:08:15.567  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-24 17:08:15.567  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.577  6774  6828 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 17:08:15.577  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:15.577  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:15.577  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.577  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.577  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f5825 removed from the list
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.577  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3951fdfa removed from the list
08-24 17:08:15.577  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:15.577  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 17:08:15.577  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.577  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3951fdfa not in the list,
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:15.577  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:08:15.577  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:15.587  7544  7558 D BtGatt.GattService: stopScan() - queue size =1,
08-24 17:08:15.587  7544  7574 D BtGatt.ScanManager: filter size is 1
08-24 17:08:15.587  7544  7574 D BtGatt.ScanManager: delete FilterIndex - 4
,08-24 17:08:15.587  7544  7570 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:08:15.587  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 17:08:15.587  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.587  7544  7574 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:15.587  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:15.587  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:15.587  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:08:15.587  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.587  7544  7574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:15.587  7544  7569 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:08:15.587  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:15.587  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:08:15.587  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279251a1 removed from the list,
08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.597  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1579a608 removed from the list
08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256166dd added. We now have 2 listener(s)
08-24 17:08:15.597  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 17:08:15.597  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:15.597  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:15.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-24 17:08:15.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:15.597  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be5252 added. We now have 9 listener(s)
08-24 17:08:15.597  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:15.597  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.607  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.607  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:15.607  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:15.607  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.607  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16552e20 added. We now have 3 listener(s)
,08-24 17:08:15.607  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-24 17:08:15.607  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.607  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.607  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.607  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.607  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31293d9 added. We now have 10 listener(s)
08-24 17:08:15.607  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:15.607  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:15.607  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:15.607  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:15.607  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:15.607  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:15.607  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.617  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:15.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:15.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:15.617  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:15.617  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:15.617  6774  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:15.627  7544  7555 D BtGatt.GattService: registerClient() - UUID=d5d9c8f9-86f1-44d9-aa40-07909b104032,
,08-24 17:08:15.667  7544  7569 D BtGatt.GattService: onClientRegistered() - UUID=d5d9c8f9-86f1-44d9-aa40-07909b104032, clientIf=6
,08-24 17:08:15.667  6774  7187 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:08:15.667  7544  7614 D BtGatt.GattService: start scan with filters
,08-24 17:08:15.667  7544  7574 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:15.667  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:15.667  7544  7569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:08:15.667  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.667  7544  7574 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:15.667  7544  7574 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:08:15.667  7544  7574 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-24 17:08:15.677  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:15.677  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:15.677  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:15.677  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 17:08:15.677  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.677  7544  7574 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:15.677  7544  7574 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:08:15.677  7544  7569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:08:15.677  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.677  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:15.677  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 17:08:15.677  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.687  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:08:15.687  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:15.687  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:15.697  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:15.697  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:15.697  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.697  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.697  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256166dd removed from the list
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.697  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be5252 removed from the list
08-24 17:08:15.697  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:15.697  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 17:08:15.697  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.697  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be5252 not in the list
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:15.697  7544  7555 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:15.697  7544  7574 D BtGatt.ScanManager: filter size is 1
08-24 17:08:15.697  7544  7574 D BtGatt.ScanManager: delete FilterIndex - 5
,08-24 17:08:15.697  7544  7614 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:08:15.697  7544  7569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 17:08:15.697  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.697  7544  7574 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:15.697  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:15.697  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:15.707  7544  7569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:08:15.707  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:15.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:15.707  7544  7574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:08:15.707  7544  7569 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 17:08:15.707  7544  7569 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:15.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:15.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:15.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.707  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:15.707  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:15.707  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:15.707  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31293d9 removed from the list
08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.707  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.707  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.707  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.707  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16552e20 removed from the list
,08-24 17:08:15.717  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:15.717  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370f9495 added. We now have 2 listener(s)
,08-24 17:08:15.717  1015  1125 E WifiNative-wlan0: do suspend true
,08-24 17:08:15.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-24 17:08:15.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:15.717  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.717  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3125d9aa added. We now have 9 listener(s)
,08-24 17:08:15.717  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:15.717  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:15.727  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.727  6774  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.727  6774  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:15.727  6774  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:15.727  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.727  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e6a138 added. We now have 3 listener(s)
,08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aa1e511 added. We now have 10 listener(s)
08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:15.737  6774  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:15.737  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:15.737  6774  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:15.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.737  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:15.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370f9495 removed from the list
08-24 17:08:15.737  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.737  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3125d9aa removed from the list
08-24 17:08:15.737  6774  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.737  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.737  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.737  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-24 17:08:15.747  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.747  6774  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3125d9aa not in the list
08-24 17:08:15.747  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:15.747  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 17:08:15.747  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,08-24 17:08:15.747  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:15.747  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:15.747  6774  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aa1e511 removed from the list
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:15.747  6774  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:15.747  6774  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:15.747  6774  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:15.747  6774  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e6a138 removed from the list
,08-24 17:08:15.747  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 17:08:15.747  6774  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:15.747  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.747  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.747  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.747  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-24 17:08:15.757  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-24 17:08:15.757  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-24 17:08:15.757  6774  7695 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1369, name: My test thread name)
,08-24 17:08:15.757  6774  7695 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1369, thread name: My test thread name)
,08-24 17:08:15.757  6774  7695 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1369, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
,08-24 17:08:15.757  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-24 17:08:15.757  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-24 17:08:15.757  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-24 17:08:15.757  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 17:08:15.767  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 17:08:15.767  6774  7697 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1371, name: My test thread name)
,08-24 17:08:15.767  6774  7697 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1371, thread name: My test thread name)
08-24 17:08:15.767  6774  7697 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1371, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 17:08:15.767  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-24 17:08:15.767  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:15.767  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.767  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.767  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.767  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.777  6774  6828 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-24 17:08:15.777  6774  6828 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 17:08:15.777  6774  6828 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 17:08:15.777  6774  6828 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 17:08:15.777  6774  6828 D com.test.thalitest.ThaliTestRunner: Total duration: 23342 ms
,08-24 17:08:15.777  6774  6828 I jxcore-log: Total number of executed tests:  80,
08-24 17:08:15.777  6774  6828 I jxcore-log: 
08-24 17:08:15.777  6774  6828 I jxcore-log: Number of passed tests:  80
08-24 17:08:15.777  6774  6828 I jxcore-log: 
08-24 17:08:15.777  6774  6828 I jxcore-log: Number of failed tests:  0
08-24 17:08:15.777  6774  6828 I jxcore-log: 
,08-24 17:08:15.777  6774  6828 I jxcore-log: Number of ignored tests:  0
08-24 17:08:15.777  6774  6828 I jxcore-log: 
08-24 17:08:15.777  6774  6828 I jxcore-log: Total duration:  23342,
08-24 17:08:15.777  6774  6828 I jxcore-log: 
08-24 17:08:15.777  6774  6828 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 17:08:15.777  6774  6828 I jxcore-log: 
08-24 17:08:15.777  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.777  6774  6828 I jxcore-log: 
,08-24 17:08:15.787  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:15.787  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:15.787  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:15.787  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:08:15.787  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:08:15.787  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-24 17:08:15.787  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.787  6774  6828 I jxcore-log: 
08-24 17:08:15.787  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-24 17:08:15.787  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.787  6774  6828 I jxcore-log: 
08-24 17:08:15.787  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-24 17:08:15.787  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-24 17:08:15.787  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.787  6774  6828 I jxcore-log: 
08-24 17:08:15.787  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:08:15.787  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.787  6774  6828 I jxcore-log: 
08-24 17:08:15.787  4063  4063 I NearbySettings: MountReceiver.onReceive - Keep current state
08-24 17:08:15.787  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 17:08:15.787  1619  1619 I Hs20UtilService: Starting #22
08-24 17:08:15.787  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-24 17:08:15.787  1015  1127 D ConnectivityService: LTETest block dns file not exists
08-24 17:08:15.787  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.787  6774  6828 I jxcore-log: 
08-24 17:08:15.787  1619  1635 I Hs20UtilService: Message received 5007
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  1015  1127 V NetworkStats: updateIfacesLocked()
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:15.797  6774  6774 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.797  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.797  6774  6828 I jxcore-log: 
08-24 17:08:15.797  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 17:08:15.797  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:15.797  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:15.807  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
,08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  1015  1127 V NetworkStats: performPollLocked() took 5ms
08-24 17:08:15.807  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
,08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
,08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
,08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:15.807  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:15.807  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.807  6774  6828 I jxcore-log: 
08-24 17:08:15.807  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.807  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.807  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.807  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.817  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.817  6774  6828 I jxcore-log: 
08-24 17:08:15.817  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 17:08:15.817  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-24 17:08:15.817  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
08-24 17:08:15.817  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:15.817  6774  6828 I jxcore-log: 
,08-24 17:08:15.817  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:15.817  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-24 17:08:15.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.827  1015  3992 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:15.827  1015  3992 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:15.827  1015  3992 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:15.827  1015  3992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:15.827  1015  3992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:15.827  1619  1619 I Hs20UtilService: Starting #23
,08-24 17:08:15.827  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:15.827  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:08:15.827  1015  1127 E ConnectivityService: updateNetworkInfo()
08-24 17:08:15.827  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-24 17:08:15.827  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.827  1015  1127 V NetworkStats: updateIfacesLocked()
08-24 17:08:15.827  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:15.827  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:15.827  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:15.837  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:15.837  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:15.837  1015  1127 V NetworkStats: performPollLocked() took 7ms
08-24 17:08:15.837  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:15.837  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:08:15.837  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:15.837  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:15.837  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:15.837  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.837  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
08-24 17:08:15.837   287   287 E SMD     : DCD OFF
08-24 17:08:15.837  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:15.837  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-24 17:08:15.837  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:15.837  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-24 17:08:15.847  1015  7662 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:08:15.847   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:08:15.847  1015  1127 D ConnectivityService:    accepting network in place of null
08-24 17:08:15.847   274   979 D Netd    : getNetworkForDns: using netid 504 for uid 1000,
08-24 17:08:15.847  1438  1438 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-24 17:08:15.847  1438  1438 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:08:15.847  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-24 17:08:15.847  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-24 17:08:15.847  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 17:08:15.847  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,08-24 17:08:15.847  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-24 17:08:15.847  4063  4063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:15.847  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
08-24 17:08:15.847  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-24 17:08:15.847  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-24 17:08:15.847  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-24 17:08:15.847  1015  1122 V NetworkStats: updateIfacesLocked()
08-24 17:08:15.847  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.847  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:15.847  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:15.857  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:15.857  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:15.857  1015  1122 V NetworkStats: performPollLocked() took 4ms
,08-24 17:08:15.857  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:15.857  4063  4063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-24 17:08:15.857  4063  4063 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 17:08:15.857  4792  6836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 17:08:15.857  1176  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:08:15.857  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.857  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-24 17:08:15.857  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 17:08:15.857  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:08:15.857  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-24 17:08:15.857  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-24 17:08:15.857  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:15.867  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.867  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.877  1015  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:15.877  1015  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:15.877  1015  1474 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:15.877  1015  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:15.877  1015  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:15.877  4063  4063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:15.887  1619  1619 I Hs20UtilService: Starting #24
08-24 17:08:15.887  4063  4063 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 17:08:15.887  1619  1635 I Hs20UtilService: Message received 5007
,08-24 17:08:15.887  1015  1473 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-24 17:08:15.887  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-24 17:08:15.887  1015  1028 D SecContentProvider2: mCursor = null
,08-24 17:08:15.887  1015  1334 D SecContentProvider2: uri = 15 selection = getToastGravity
08-24 17:08:15.887  1015  1334 D SecContentProvider2: mCursor = null
08-24 17:08:15.897  1015  1364 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-24 17:08:15.897  1015  1364 D SecContentProvider2: mCursor = null,
,08-24 17:08:15.897  1015  1494 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-24 17:08:15.897  1015  1494 D SecContentProvider2: mCursor = null
,08-24 17:08:15.897  1015  1474 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-24 17:08:15.897  1015  1474 D SecContentProvider2: mCursor = null
,08-24 17:08:15.897  1015  1478 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-24 17:08:15.897  1015  1478 D SecContentProvider2: mCursor = null
,08-24 17:08:15.907  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-24 17:08:15.907  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:15.907  6774  6828 I jxcore-log: 
,08-24 17:08:15.927   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,08-24 17:08:15.927  1015  7662 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-24 17:08:15.937  1015  1473 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-24 17:08:15.937  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 17:08:15.987  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:08:15 GMT], X-Android-Received-Millis=[1472051295994], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472051295966]},
08-24 17:08:15.987  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-24 17:08:15.987  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 17:08:15.987  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-24 17:08:15.987  1015  7662 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-24 17:08:15.987  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.,
08-24 17:08:15.987  1176  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:08:15.987  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:15.987  4792  6836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:08:15.987  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 17:08:15.987  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-24 17:08:15.987  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 17:08:15.987  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:08:15.987  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-24 17:08:15.987  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-24 17:08:15.987  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:15.997  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.997  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:16.067  7703  7703 D AndroidRuntime: 
08-24 17:08:16.067  7703  7703 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 17:08:16.067  7703  7703 D AndroidRuntime: CheckJNI is OFF
,08-24 17:08:16.067  7703  7703 D AndroidRuntime: readGMSProperty: start
08-24 17:08:16.067  7703  7703 D AndroidRuntime: readGMSProperty: already setted!!,
08-24 17:08:16.067  7703  7703 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 17:08:16.067  7703  7703 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 17:08:16.067  7703  7703 D AndroidRuntime: readGMSProperty: end
08-24 17:08:16.067  7703  7703 D AndroidRuntime: addProductProperty: start
,08-24 17:08:16.097  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-24 17:08:16.097  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:16.097  6774  6828 I jxcore-log: 
,08-24 17:08:16.167  1015  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 17:08:16.167  1015  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:08:16.167  1015  1094 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-24 17:08:16.167  1015  1094 D BatteryService: stay LED for fully charged
08-24 17:08:16.167  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 17:08:16.167  1015  1015 I MotionRecognitionService: Plugged,
08-24 17:08:16.167  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:08:16.177  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 17:08:16.177  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 17:08:16.177  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 17:08:16.177  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:08:16.187  7544  7544 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 17:08:16.187  7544  7575 D HeadsetStateMachine: Disconnected process message: 10
,08-24 17:08:16.197  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:08:16.197  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:08:16.197  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 17:08:16.207  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-24 17:08:16.207  7703  7703 E AffinityControl: AffinityControl: registerfunction enter
08-24 17:08:16.217  6774  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:16.217  6774  6828 I jxcore-log: 
,08-24 17:08:16.237  7703  7703 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 17:08:16.257  1015  1494 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-24 17:08:16.257  1015  1494 D PackageManager: START PACKAGE DELETE: observer{950215834}
08-24 17:08:16.257  1015  1494 D PackageManager: pkg{<packageName>}
08-24 17:08:16.257  1015  1494 D PackageManager: user{0}
08-24 17:08:16.257  1015  1494 D PackageManager: caller{2000}
08-24 17:08:16.257  1015  1494 D PackageManager: flags{2}
08-24 17:08:16.257  1015  1494 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-24 17:08:16.257  1015  1494 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-24 17:08:16.257  1015  1494 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 17:08:16.257  1015  1494 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-24 17:08:16.257  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-24 17:08:16.257  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 17:08:16.257  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-24 17:08:16.267  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled,
08-24 17:08:16.267  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 17:08:16.267  1015  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-24 17:08:16.317  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-24 17:08:16.317  1015  1040 I ActivityManager: Killing 6774:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-24 17:08:16.347  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:16.357  1015  1054 W PackageSettings: Skipping PackageSetting{28d8a480 com.example.hello/10168} due to missing metadata
,08-24 17:08:16.387  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{22e8871 u0 com.test.thalitest/.MainActivity t2}
,08-24 17:08:16.387  1015  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 17:08:16.397  1015  1040 D InputDispatcher: Focus left window: 6774
,08-24 17:08:16.397   257   432 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-24 17:08:16.407   257   433 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-24 17:08:16.417  1015  1040 D InputDispatcher: Focused application released
,08-24 17:08:16.417  1015  1040 D FocusedStackFrame: Set to : 0
08-24 17:08:16.417  1015  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-24 17:08:16.417  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 17:08:16.417  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:08:16.427  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-24 17:08:16.427  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-24 17:08:16.437  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-24 17:08:16.457  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-24 17:08:16.497  1479  1479 D Launcher: onRestart, Launcher: 419520883
,08-24 17:08:16.497  2663  2663 I art     : Explicit concurrent mark sweep GC freed 20294(1146KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 822us total 47.390ms
,08-24 17:08:16.527  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:16.547  1870  1870 E SamsungIME: mOCRHelper is null
,08-24 17:08:16.557  2041  2213 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 17:08:16.557  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-24 17:08:16.557  1015  1027 D SecContentProvider2: mCursor = null
,08-24 17:08:16.557  4792  4792 I art     : Explicit concurrent mark sweep GC freed 22718(1372KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.308ms total 110.333ms
,08-24 17:08:16.577  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 17:08:16.577  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-24 17:08:16.577  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-24 17:08:16.587  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-24 17:08:16.587  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-24 17:08:16.587  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:16.587  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-24 17:08:16.587  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 17:08:16.587  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:16.587  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:16.587  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-24 17:08:16.587  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 17:08:16.607  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:16.607  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.607  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.607  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:16.607  1015  1122 V NetworkStats: performPollLocked() took 23ms
08-24 17:08:16.607  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:16.617  7715  7715 E Zygote  : MountEmulatedStorage()
08-24 17:08:16.617  7715  7715 E Zygote  : v2
08-24 17:08:16.617  7715  7715 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:08:16.617  7715  7715 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:16.627  7715  7715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:08:16.627  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 17:08:16.627  7715  7715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:16.627  7715  7715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:08:16.627  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:16.627  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:16.637  1479  1479 D Launcher: onStart, Launcher: 419520883
08-24 17:08:16.637  1479  1479 D Launcher.HomeView: onStart
08-24 17:08:16.637  1479  1479 D Launcher: onResume, Launcher: 419520883
08-24 17:08:16.637  1015  1334 D SettingsProvider: name = kids_home_mode
08-24 17:08:16.637  1015  1334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:16.637  1015  1334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:16.637  1015  1334 D SettingsProvider: selectionArgs: false
08-24 17:08:16.637  1015  1334 D SettingsProvider: selectionArgs: 10006
08-24 17:08:16.637  1015  1334 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:16.637  1015  1334 D SettingsProvider: ret = -1
08-24 17:08:16.637  1479  1479 D Launcher.HomeView: onResume
,08-24 17:08:16.637  1427  1427 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:16.647  1427  1427 D RegisteredServicesCache: empty dynamic service
08-24 17:08:16.647  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-24 17:08:16.647  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-24 17:08:16.657  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-24 17:08:16.667  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-24 17:08:16.667  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-24 17:08:16.667  7715  7715 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:16.677  7715  7715 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:16.677  1479  1479 D MenuAppsGridFragment: onResume
,08-24 17:08:16.677  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 17:08:16.677  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 17:08:16.707  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-24 17:08:16.727  1015  1477 D ActivityManager: handle home activity for 0
08-24 17:08:16.727  1015  1477 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-24 17:08:16.727  1015  1477 D KnoxTimeoutHandler: post home show event for user 0
08-24 17:08:16.727  1015  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 17:08:16.727  1015  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 17:08:16.727  1015  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 17:08:16.727  1479  1479 D Launcher.HomeView: onPause
,08-24 17:08:16.727  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-24 17:08:16.727  1427  1427 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 17:08:16.737  1427  1427 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:16.757  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.757   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-24 17:08:16.757  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-24 17:08:16.767  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.767  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-24 17:08:16.777  1015  1476 D InputDispatcher: Focus entered window: 1479
,08-24 17:08:16.777  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:08:16.777  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 17:08:16.777  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:08:16.787  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-24 17:08:16.787  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 17:08:16.787  1015  1054 I art     : Explicit concurrent mark sweep GC freed 78234(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 7.981ms total 319.965ms
08-24 17:08:16.787  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 17:08:16.797  1015  1494 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-24 17:08:16.797  1015  1494 D SecContentProvider2: mCursor = null
,08-24 17:08:16.797  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 17:08:16.797  1015  3343 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-24 17:08:16.797  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{368cb6ec token=android.os.BinderProxy@38813b88 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-24 17:08:16.797  1479  1479 D Launcher.HomeView: onStop
08-24 17:08:16.797  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 17:08:16.797  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 17:08:16.797  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.797  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-24 17:08:16.797  1015  1553 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 17:08:16.817  1015  1553 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6774 uid 10171
,08-24 17:08:16.817  1015  7732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:08:16.817  7715  7715 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 17:08:16.817  7715  7715 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 17:08:16.817  7715  7715 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 17:08:16.827  1870  1870 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-24 17:08:16.837  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.857  7715  7715 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-24 17:08:16.857  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-24 17:08:16.857  7715  7715 I PCWCLIENTTRACE_PushUtil: sales region : global,
08-24 17:08:16.857  1015  3992 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
08-24 17:08:16.857  7715  7715 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 17:08:16.857  1015  3992 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-24 17:08:16.857  7715  7715 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:16.867  1015  1054 D PackageManager: delete codoeFile: ,
,08-24 17:08:16.867  1015  1040 I ActivityManager: Killing 7103:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-24 17:08:16.877  1793  1793 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 17:08:16.887  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-24 17:08:16.887  1015  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-24 17:08:16.887  1015  1054 D PackageManager: result of delete: 1{950215834}
,08-24 17:08:16.887  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-24 17:08:16.887  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.887  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.887  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.887  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:16.887  7703  7703 D AndroidRuntime: Shutting down VM
,08-24 17:08:16.897  2602  3134 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7,
,08-24 17:08:16.897  7736  7736 E Zygote  : MountEmulatedStorage(),
,08-24 17:08:16.907  7736  7736 E Zygote  : v2
08-24 17:08:16.907  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 17:08:16.907  1015  1054 D PackageManager: userId{-1}
08-24 17:08:16.907  1015  1054 D PackageManager: andCode{true}
,08-24 17:08:16.907  7736  7736 I libpersona: KNOX_SDCARD checking this for 10031
08-24 17:08:16.907  7736  7736 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:16.907  1015  1028 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7736 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-24 17:08:16.907  7736  7736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:16.907  1015  1045 W ActivityManager: mDVFSHelper.release()
08-24 17:08:16.907  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ca3973f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147166
08-24 17:08:16.907  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-24 17:08:16.907  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.907  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.907  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.907  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:16.907  7736  7736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:16.917  7736  7736 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:16.927  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-24 17:08:16.927  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-24 17:08:16.927  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-24 17:08:16.927  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-24 17:08:16.927  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-24 17:08:16.927  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-24 17:08:16.937  7745  7745 E Zygote  : MountEmulatedStorage()
,08-24 17:08:16.937  7745  7745 E Zygote  : v2
08-24 17:08:16.937  7745  7745 I libpersona: KNOX_SDCARD checking this for 10003
08-24 17:08:16.937  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.937  7745  7745 I libpersona: KNOX_SDCARD not a persona,
08-24 17:08:16.937  7745  7745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:08:16.937  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.937  7745  7745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:16.937  7745  7745 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:16.947  1176  1176 I StatusBar: Icon Only
,08-24 17:08:16.947  1176  1176 D PanelView: There is/are notification(s) 
,08-24 17:08:16.947  1015  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7745 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 17:08:16.947  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.947  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-24 17:08:16.947  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-24 17:08:16.947  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:16.947  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:16.947  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-24 17:08:16.947  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 17:08:16.947  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:08:16.947  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:08:16.957  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.957  1793  1793 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-24 17:08:16.957  1793  1793 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-24 17:08:16.957  1793  1793 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-24 17:08:16.957  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-24 17:08:16.957  1015  1474 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:16.967  7745  7745 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:16.967  7745  7745 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:16.967   305   305 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 26.365ms
,08-24 17:08:16.967  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.977  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.977  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.977  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 17:08:16.987  7736  7736 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:16.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.987  7736  7736 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:16.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 17:08:16.987   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.650ms
,08-24 17:08:16.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:16.997  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
08-24 17:08:16.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 17:08:16.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:16.997  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.997  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.997  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:16.997  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:17.007   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.334ms
,08-24 17:08:17.017  7766  7766 E Zygote  : MountEmulatedStorage()
,08-24 17:08:17.017  7766  7766 E Zygote  : v2
08-24 17:08:17.017  7766  7766 I libpersona: KNOX_SDCARD checking this for 10001
08-24 17:08:17.017  7766  7766 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:17.017  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:17.017  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:08:17.027  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:17.027  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7766 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:08:17.037  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 17:08:17.037  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-24 17:08:17.047  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-24 17:08:17.047  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-24 17:08:17.047  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:17.057  7766  7766 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:17.067  1015  1553 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-24 17:08:17.067  1015  1364 D RCPManagerService: exchangeData() failure , invalid userId
08-24 17:08:17.067  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-24 17:08:17.067  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:17.067  1015  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:17.067  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-24 17:08:17.077  1015  1553 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:08:17.087  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 17:08:17.087  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 17:08:17.097  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:17.097  7703  7703 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 17:08:17.097  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:17.097  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 17:08:17.127  7252  7252 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-24 17:08:17.127  7035  7785 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-24 17:08:17.127  7035  7785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:08:17.127  7035  7785 I System.out: (HTTPLog)-Static: isShipBuild true
08-24 17:08:17.127  7035  7785 I System.out: (HTTPLog)-Thread-1280-803742310: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-24 17:08:17.127  7035  7785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:08:17.137   274   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:08:17.137   274   979 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-24 17:08:17.167  7168  7168 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:17.167  7168  7168 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-24 17:08:17.167  7168  7168 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-24 17:08:17.167  7168  7168 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-24 17:08:17.167  7147  7147 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-24 17:08:17.167  7194  7194 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-24 17:08:17.167  7194  7194 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-24 17:08:17.167  7194  7194 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-24 17:08:17.177  7035  7785 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 17:08:17.177  2781  7791 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-24 17:08:17.177  2781  7791 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-24 17:08:17.177  2781  7791 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-24 17:08:17.187  7194  7194 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-24 17:08:17.187  7194  7194 I SA      : [OR] == isSIMCardReady false ==
,08-24 17:08:17.197  7194  7194 I SA      : [SCU] == networkStateCheck == true
,08-24 17:08:17.197  7194  7194 I SA      : [DM] getCountryCodeFromCSC : PL
08-24 17:08:17.197  7194  7194 I SA      : isChinaCountryCode : false
08-24 17:08:17.197  7194  7194 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-24 17:08:17.197  7194  7194 I SA      : [OR] == networkStateCheck true ==
,08-24 17:08:17.227  7194  7194 I SA      : [OR] GetMyCountryZoneTask
,08-24 17:08:17.227  7194  7194 I SA      : [OR] onReceive END
,08-24 17:08:17.227  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:17.237  1015  1364 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-24 17:08:17.237  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-24 17:08:17.237  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:17.237  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:17.237  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-24 17:08:17.247  7035  7785 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 17:08:17.247  1015  1473 I ActivityManager: Killing 7217:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-24 17:08:17.267  1015  1027 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-24 17:08:17.267  1015  1027 D SecContentProvider2: mCursor = null
,08-24 17:08:17.267  7194  7795 I SA      : [SRS] prepareGetMyCountryZone
08-24 17:08:17.267  2781  7791 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-24 17:08:17.267  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-24 17:08:17.267  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-24 17:08:17.267  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-24 17:08:17.277  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-24 17:08:17.277  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-24 17:08:17.277  7194  7795 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-24 17:08:17.277  2781  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
08-24 17:08:17.277  7194  7795 I SA      : [SSP] query invoked
,08-24 17:08:17.277  2781  7791 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-24 17:08:17.287  7194  7795 I SA      : [TPMU] GetMccFromDB : null
,08-24 17:08:17.287  7252  7252 W FileUtils: Failed to chmod(/data/data/com.sec.android.app.samsungapps/databases/info2.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-24 17:08:17.297  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38813b88 time:147550
,08-24 17:08:17.297  7194  7795 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-24 17:08:17.297  7194  7795 I SA      : [LBE] isSupportCheckDomainRegion : false
08-24 17:08:17.297  7194  7795 I SA      : [TPM] isNoProxy(default) : true
,08-24 17:08:17.317  7194  7795 E File    : fail readDirectory() errno=2
,08-24 17:08:17.327  2781  7791 E SQLiteLog: (28) failed to open "/data/data/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 17:08:17.327  2781  7791 E SQLiteDatabase: Failed to open database '/data/data/com.policydm/databases/policydmdb.db'.
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdDeviceRegister(XDBSpdAdp.java:27)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:299)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.327  2781  7791 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.,database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdDeviceRegister(XDBSpdAdp.java:27)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:299)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.327  2781  7791 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:17.327  2781  7791 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
,08-24 17:08:17.337  2781  7791 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-24 17:08:17.337  2781  7791 E SQLiteLog: (28) failed to open "/data/data/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 17:08:17.337  2781  7791 E SQLiteDatabase: Failed to open database '/data/data/com.policydm/databases/policydmdb.db'.
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdPushRegId(XDBSpdAdp.java:138)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:305)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.337  2781  7791 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.data,base.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdPushRegId(XDBSpdAdp.java:138)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:305)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.337  2781  7791 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:17.337  2781  7791 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
,08-24 17:08:17.337  2781  7791 E SQLiteLog: (28) failed to open "/data/data/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 17:08:17.347  2781  7791 E SQLiteDatabase: Failed to open database '/data/data/com.policydm/databases/policydmdb.db'.
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdDeviceUpdate(XDBSpdAdp.java:86)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:305)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.347  2781  7791 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:72)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchSpdRow(XDBSqlQuery.java:2210)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:303)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbRead(XDB.java:771)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.db.XDBSpdAdp.xdbGetSpdDeviceUpdate(XDBSpdAdp.java:86)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver.xdmExecResumeCase(XDMBroadcastReceiver.java:305)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at com.policydm.XDMBroadcastReceiver$2.run(XDMBroadcastReceiver.java:119)
08-24 17:08:17.347  2781  7791 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-24 17:08:17.347  2781  7791 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
,08-24 17:08:17.347  2781  7791 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-24 17:08:17.357  7267  7267 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-24 17:08:17.367  7267  7267 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-24 17:08:17.367  7267  7267 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-24 17:08:17.367  7267  7267 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-24 17:08:17.367  1015  1554 I ActivityManager: Killing 6850:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-24 17:08:17.377  2895  2895 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 17:08:17 GMT+02:00 2016
,08-24 17:08:17.377  1015  1364 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 17:08:17.377  1015  1364 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 17:08:17.377  1015  1364 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:17.377  1015  1364 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:17.377  1015  1364 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 17:08:17.387  2895  2895 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.

```
