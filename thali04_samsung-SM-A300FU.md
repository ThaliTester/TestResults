#### Test 79763830e2067e4_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system,
08-26 14:16:55.173  1016  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 14:16:55.173  1016  1217 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 14:16:55.173  1016  1217 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:16:55.173  1016  1217 D BatteryService: stay LED for fully charged
08-26 14:16:55.173  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 14:16:55.173  1016  1016 I MotionRecognitionService: Plugged
08-26 14:16:55.173  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-26 14:16:55.173  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 14:16:55.173  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:16:55.183  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 14:16:55.183  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 14:16:55.193  3164  3164 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:16:55.193  3164  3265 D HeadsetStateMachine: Disconnected process message: 10
08-26 14:16:55.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:16:55.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:16:55.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:16:55.463  6732  6732 D AndroidRuntime: 
08-26 14:16:55.463  6732  6732 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:16:55.463  6732  6732 D AndroidRuntime: CheckJNI is OFF
08-26 14:16:55.463  6732  6732 D AndroidRuntime: readGMSProperty: start
08-26 14:16:55.463  6732  6732 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:16:55.463  6732  6732 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:16:55.463  6732  6732 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:16:55.463  6732  6732 D AndroidRuntime: readGMSProperty: end
08-26 14:16:55.463  6732  6732 D AndroidRuntime: addProductProperty: start
08-26 14:16:55.603  6732  6732 E AffinityControl: AffinityControl: registerfunction enter
08-26 14:16:55.633  6732  6732 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 14:16:55.643  1016  1478 E PersonaManagerService: inState():  stateMachine is null !!
08-26 14:16:55.643  1016  1478 I PersonaManagerService: PersonaId don't exist
08-26 14:16:55.643  1016  1478 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 14:16:55.653  1016  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:16:55.663  1016  1478 W ActivityManager: mDVFSHelper.acquire()
08-26 14:16:55.663   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 14:16:55.673   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 14:16:55.673  1016  1478 D FocusedStackFrame: Set to : 0
08-26 14:16:55.683  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:16:55.683  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:16:55.683  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:16:55.683  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:16:55.683  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 14:16:55.683  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 14:16:55.693  6743  6743 E Zygote  : MountEmulatedStorage()
08-26 14:16:55.693  6743  6743 E Zygote  : v2
08-26 14:16:55.693  6743  6743 I libpersona: KNOX_SDCARD checking this for 10171
08-26 14:16:55.693  6743  6743 I libpersona: KNOX_SDCARD not a persona
08-26 14:16:55.703  1016  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 14:16:55.703  1016  1478 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6743 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:16:55.703  1016  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:16:55.703  1016  1478 D InputDispatcher: Focused application set to: xxxx
08-26 14:16:55.703  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:16:55.703  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 14:16:55.703  1016  1478 D InputDispatcher: Focus left window: 1480
08-26 14:16:55.703  6732  6732 D AndroidRuntime: Shutting down VM
08-26 14:16:55.703   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-26 14:16:55.703  6743  6743 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:16:55.703  6743  6743 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:16:55.703  6743  6743 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 14:16:55.713  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:16:55.713  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:16:55.723  6743  6743 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:16:55.733  6743  6743 D ActivityThread: Added TimaKeyStore provider
08-26 14:16:55.733  1016  1503 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 14:16:55.743  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:16:55.743  1016  1016 V ActivityManager: Display changed displayId=0
08-26 14:16:55.763  1016  1503 D PersonaManager: isKioskContainerExistOnDevice
08-26 14:16:55.773  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 14:16:55.803   258  1097 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-26 14:16:55.803   258   424 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-26 14:16:55.803  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{1f65789f token=android.os.BinderProxy@229eee2b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 14:16:55.803  1480  1480 D Launcher: onTrimMemory. Level: 20
08-26 14:16:55.873  6743  6743 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 14:16:55.893  6743  6743 I cr.library_loader: Time to load native libraries: 1 ms (timestamps 6903-6904)
08-26 14:16:55.893  6743  6743 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 14:16:55.913  6732  6732 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 14:16:55.913  6743  6743 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21454ac4}
,08-26 14:16:55.913  6743  6743 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 14:16:55.913  6743  6743 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:16:55.953  6743  6743 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 14:16:55.953  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:16:55.953  6743  6743 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 14:16:55.973  6743  6743 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:16:55.973  6743  6743 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:16:55.973  6743  6743 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:16:55.973  6743  6743 I Adreno-EGL: Local Branch: 
08-26 14:16:55.973  6743  6743 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:16:55.973  6743  6743 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:16:55.973  6743  6743 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:16:56.033  6743  6743 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 14:16:56.053  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 14:16:56.053  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 14:16:56.053  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 14:16:56.053  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 14:16:56.123   288   288 E SMD     : DCD OFF
,08-26 14:16:56.173  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:16:56.183  6743  6743 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 14:16:56.193  6743  6743 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 14:16:56.193  6743  6743 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 14:16:56.203  6743  6743 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 14:16:56.203  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:16:56.203  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:16:56.263  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{2b2f4692 u0 com.test.thalitest/.MainActivity t2}
,08-26 14:16:56.273  6743  6784 D OpenGLRenderer: Render dirty regions requested: true
,08-26 14:16:56.283  1016  1503 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 14:16:56.283  1016  1503 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 14:16:56.283  1016  1503 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:16:56.283  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 14:16:56.283  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:16:56.283  6743  6771 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 14:16:56.293  6743  6743 V ActivityThread: updateVisibility : ActivityRecord{2d257b24 token=android.os.BinderProxy@3a56e651 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 14:16:56.293  6743  6743 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:16:56.293  6743  6743 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 14:16:56.303   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 14:16:56.313  1016  2140 D InputDispatcher: Focus entered window: 6743
,08-26 14:16:56.323  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:16:56.323  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:16:56.323  6743  6743 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 14:16:56.323  6743  6784 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 14:16:56.323  6743  6784 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-26 14:16:56.323  6743  6784 D OpenGLRenderer: Enabling debug mode 0
,08-26 14:16:56.343  1016  1325 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:16:56.353  1016  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:16:56.353  1177  1177 I StatusBar: Icon Only
,08-26 14:16:56.353  1177  1177 D PanelView: There is/are notification(s) 
,08-26 14:16:56.363  1016  1046 I ActivityManager: Displayed Component not be shown by security: +600ms (total +687ms),
08-26 14:16:56.363  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b2f4692 u0 com.test.thalitest/.MainActivity t2} time:107379
08-26 14:16:56.363  1016  1046 W ActivityManager: mDVFSHelper.release()
,08-26 14:16:56.373   258   424 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 14:16:56.373  1882  1882 I SamsungIME: getCurrentCandidateView
08-26 14:16:56.373   258  1097 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 14:16:56.383  6743  6743 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 14:16:56.383  6743  6743 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a56e651 time:107392
,08-26 14:16:56.503  1882  1882 D SamsungIME: Dismiss ExpandCandiate
,08-26 14:16:56.523  6743  6743 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6743,
,08-26 14:16:56.643  6743  6743 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:16:56.653  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:16:56.743  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:16:56.753  1882  1882 I SamsungIME: KeybaordView init() : load resources
,08-26 14:16:56.773  1882  1882 I SamsungIME: getCurrentKeyboard
08-26 14:16:56.773  1882  1882 I SamsungIME: getTextKeyboard
,08-26 14:16:56.793  6743  6791 D jxcore_app_log: JniHelper::setJavaVM(0xb78072b0), pthread_self() = -1210497432
,08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 14:16:56.793  1882  1882 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 14:16:56.793  6743  6791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2110959a added. We now have 1 listener(s)
,08-26 14:16:56.803  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-26 14:16:56.803  6743  6791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 14:16:56.803  6743  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:16:56.803  6743  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 14:16:56.813  6743  6791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd05c1 added. We now have 1 listener(s)
08-26 14:16:56.813  6743  6791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:16:56.813  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:16:56.813  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:16:56.813  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 14:16:56.813  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 14:16:56.813  6743  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:16:56.823  6743  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:16:56.823  6743  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 14:16:56.833  6743  6791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:16:56.833  6743  6791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:16:56.833  6743  6791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:16:56.833  6743  6791 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:16:56.843  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:16:56.843  6743  6791 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:16:56.843  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:16:56.863  6743  6743 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:16:56.873  1882  1904 W art     : Suspending all threads took: 10.220ms,
,08-26 14:16:57.423  6743  6799 W jxcore-log: Initializing JXcore engine
08-26 14:16:57.423  6743  6799 W jxcore-log: JXcore engine is ready
,08-26 14:16:57.483  1993  1993 E audit   : type=1400 msg=audit(1472213817.483:205): avc:  denied  { ioctl } for  pid=6799 comm="Thread-1246" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 14:16:57.483  1993  1993 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:16:57.483  1993  1993 E audit   : type=1300 msg=audit(1472213817.483:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9eba18f8 items=0 ppid=304 ppcomm=main pid=6799 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1246" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 14:16:57.483  1993  1993 E audit   : type=1320 msg=audit(1472213817.483:205): 
,08-26 14:16:57.493  6743  6799 W jxcore-log: Starting JXcore engine
,08-26 14:16:57.523  1016  1320 E Watchdog: !@Sync 3
,08-26 14:16:57.593  6743  6799 W jxcore-log: Platform android
08-26 14:16:57.593  6743  6799 W jxcore-log: 
08-26 14:16:57.593  6743  6799 W jxcore-log: Process ARCH arm
08-26 14:16:57.593  6743  6799 W jxcore-log: 
,08-26 14:16:57.803  6743  6799 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:16:57.803  6743  6799 I jxcore-log: 
,08-26 14:16:57.803  6743  6799 W jxcore-log: JXcore engine is started
,08-26 14:16:57.803  6743  6791 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 14:16:57.813  6743  6743 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:16:58.123   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 14:16:58.123   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 14:16:59.123   288   288 E SMD     : DCD OFF
,08-26 14:16:59.983  1016  1095 V AlarmManager: waitForAlarm result :8
,08-26 14:17:02.123   288   288 E SMD     : DCD OFF
,08-26 14:17:02.523  1016  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-26 14:17:02.803  1016  3356 D SSRM:n  : SIOP:: AP = 340
,08-26 14:17:03.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:04.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:04.243  5609  5609 D FactoryTest: Not factory mode
,08-26 14:17:04.243  5609  5609 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 14:17:04.243  5609  5609 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-26 14:17:04.243  5609  5609 D MTPRx   : still no open session command from host, so toast
,08-26 14:17:04.243  5609  5609 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-26 14:17:04.243  5609  5609 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 14:17:04.253  5609  5609 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115261,
08-26 14:17:04.253  1016  1475 E PersonaManagerService: inState():  stateMachine is null !!
08-26 14:17:04.253  1016  1475 I PersonaManagerService: PersonaId don't exist,
08-26 14:17:04.253  1016  1475 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 14:17:04.253  1016  1475 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 14:17:04.253  1016  1475 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:04.253  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:04.253  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 14:17:04.263  1016  1475 W ActivityManager: mDVFSHelper.acquire()
,08-26 14:17:04.283  1016  1475 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:04.283  1016  1475 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:17:04.283  1016  1475 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 14:17:04.283  1016  1475 D InputDispatcher: Focused application set to: xxxx
08-26 14:17:04.283  1016  1475 D InputDispatcher: Focus left window: 6743
,08-26 14:17:04.283  5609  5609 E MTPRx   : started activity for popup
,08-26 14:17:04.293  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:04.293  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:04.313  5609  5609 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:04.343  5609  5609 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 14:17:04.353  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-26 14:17:04.353  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 14:17:04.353  1016  1029 D InputDispatcher: Focused application set to: xxxx
08-26 14:17:04.353  1016  1029 D InputDispatcher: Focus entered window: 6743
,08-26 14:17:04.353  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:04.353  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:04.363  1016  1217 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:17:04.363  1016  1217 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2fd3776d attribute=null, token = android.os.BinderProxy@265e54fd
,08-26 14:17:04.393  5609  5609 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 14:17:04.403  5609  5609 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 14:17:04.403  5609  5609 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 14:17:04.423  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:17:04.423  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 14:17:04.423  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 14:17:04.423  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 14:17:04.433  1016  1325 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 14:17:04.433  1016  1325 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 14:17:04.433  1016  1325 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:17:04.433  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 14:17:04.433  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:17:04.443  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:04.443  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 14:17:04.453  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d96c1d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@196d663a, 16908290=android.view.AbsSavedState$1@196d663a}, android:focusedViewId=100}]}]
08-26 14:17:04.453  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 14:17:04.453  6743  6743 V ActivityThread: updateVisibility : ActivityRecord{2d257b24 token=android.os.BinderProxy@3a56e651 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 14:17:04.453  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 14:17:04.453  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 14:17:04.453  6743  6743 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a56e651 time:115464
,08-26 14:17:04.453  1016  1478 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:05.123   288   288 E SMD     : DCD OFF,
,08-26 14:17:05.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:05.223  1016  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:05.223  1016  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 14:17:05.223  1016  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:17:05.223  1016  1476 D BatteryService: stay LED for fully charged
,08-26 14:17:05.223  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:05.233  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:05.233  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:17:05.233  1016  1016 I MotionRecognitionService: Plugged
,08-26 14:17:05.233  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:17:05.233  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:17:05.233  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 14:17:05.243  3164  3164 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:17:05.243  3164  3265 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:05.263  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:05.263  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:05.263  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:05.733  1016  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-26 14:17:06.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:07.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:07.263  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-26 14:17:08.123   288   288 E SMD     : DCD OFF,
,08-26 14:17:08.133   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 14:17:08.993  1016  1095 V AlarmManager: waitForAlarm result :4,
,08-26 14:17:08.993  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.023  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 14:17:09.023  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-26 14:17:09.023  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 14:17:09.023  2001  2001 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 14:17:09.023  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 14:17:09.023  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 14:17:09.043  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 14:17:09.043  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 14:17:09.053  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:17:09.053  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 14:17:09.053  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 14:17:09.073  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:17:09.073  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:17:09.083  1016  1503 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:09.083  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.093  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:09.093  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.093  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.093  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:17:09.123  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 14:17:09.143  4694  4694 D ConnectivityManager: CallingUid : 10011, CallingPid : 4694
,08-26 14:17:09.153  1016  1029 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:17:09.153  1016  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 14:17:09.153  1016  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-26 14:17:09.153  1016  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 14:17:09.163  4694  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:09.213  4694  6809 W DriveInitializer: Background init thread started
,08-26 14:17:09.253   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 14:17:09.253   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:09.253  4694  6809 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 14:17:09.293  2001  2001 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-26 14:17:09.333  1016  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:09.333  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.333  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.333  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.333  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.343  1016  1325 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-26 14:17:09.343  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.383  1016  2134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:09.383  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.383  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.383  1016  2134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.383  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.393  4694  6809 W DriveInitializer: Background init thread ended
,08-26 14:17:09.413  4694  6817 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 14:17:09.413  4694  6817 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 14:17:09.443  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:17:09.463  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:09.463  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.463  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.703  1016  1465 I art     : Explicit concurrent mark sweep GC freed 37918(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.480ms total 146.491ms
,08-26 14:17:09.723  1016  1077 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:09.723  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.723  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:09.723  1016  1077 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.723  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.753  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:09.753  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 14:17:09.763  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.763  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.763  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.813  1016  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:09.813  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:09.813  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.813  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.833  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:09.843  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.843  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:09.843  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.933  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:09.933  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.933  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:09.933  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:09.943  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:09.943  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:09.943  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:09.943  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:09.953  6822  6822 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:09.953  1016  1029 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6822 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-26 14:17:09.953  6822  6822 E Zygote  : v2
08-26 14:17:09.953  6822  6822 I libpersona: KNOX_SDCARD checking this for 10011
08-26 14:17:09.953  6822  6822 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:09.963  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:09.963  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 14:17:09.963  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:09.983  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:09.993  6822  6822 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:10.003  6822  6822 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 14:17:10.003  6822  6822 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 14:17:10.043  6822  6822 I MultiDex: VM with version 2.1.0 has multidex support
08-26 14:17:10.043  6822  6822 I MultiDex: install
08-26 14:17:10.043  6822  6822 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 14:17:10.083  6822  6822 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 14:17:10.143  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 14:17:10.143  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.143  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.143  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.143  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.153  6822  6822 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:17:10.153  6822  6822 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c8112c0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 14:17:10.153  6822  6822 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 14:17:10.163  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.163  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:10.163  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.163  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.163  6822  6822 D ChimeraCfgMgr: Reading stored module config
,08-26 14:17:10.223  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 14:17:10.223  6743  6799 I jxcore-log: 
,08-26 14:17:10.223  2001  2001 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=429ae762-d06f-49b2-8f88-92cd533a342d
,08-26 14:17:10.223  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 14:17:10.223  6743  6799 I jxcore-log: 
,08-26 14:17:10.233  1016  2134 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:17:10.233  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 14:17:10.233  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:10.233  1016  2134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.233  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:10.243  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:10.243  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-26 14:17:10.243  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:10.243  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-26 14:17:10.253  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 14:17:10.253  6743  6799 I jxcore-log: 
,08-26 14:17:10.253  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 14:17:10.253  6743  6799 I jxcore-log: 
,08-26 14:17:10.273  6822  6841 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 14:17:10.293  1016  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.293  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.293  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.293  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.303  6822  6836 I art     : Background partial concurrent mark sweep GC freed 971(211KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 9.805ms total 34.050ms
,08-26 14:17:10.323  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:17:10.323  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:17:10.383  4282  4291 I art     : Explicit concurrent mark sweep GC freed 1415(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 712us total 21.145ms
,08-26 14:17:10.443   283   283 D WVCdm   : Instantiating CDM.
,08-26 14:17:10.443   283  1014 I WVCdm   : CdmEngine::OpenSession
,08-26 14:17:10.443   283  1014 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 14:17:10.453  2001  2158 W GCoreFlp: No location to return for getLastLocation()
,08-26 14:17:10.473   283  1014 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 14:17:10.493   283  1014 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 14:17:10.503  1016  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.513  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.513  1016  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:10.513  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.523  1016  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.523  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.523  4694  6818 D UdcContextInitService: registered all accounts: true
08-26 14:17:10.523  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.523  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.543  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:10.543  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.543  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.543  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.543  2001  2161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:10.553   283  1014 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 14:17:10.553   283   682 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-26 14:17:10.553   283   682 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 14:17:10.553   283   682 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 14:17:10.563  6822  6830 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 14:17:10.563  6822  6830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:17:10.563  6822  6830 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 14:17:10.563  6822  6830 I System.out: (HTTPLog)-Thread-1219-602038125: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 14:17:10.563  6822  6830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:10.563  2001  2166 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 14:17:10.563   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:17:10.563   278   979 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:17:10.563   283   682 D WVCdm   : PrepareKeyRequest: nonce=2145113811
,08-26 14:17:10.613  6822  6830 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:10.613  6822  6830 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6822, getuid(): 10011
,08-26 14:17:10.713  1016  1077 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:17:10.713  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 14:17:10.713  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.713  1016  1077 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.713  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.743  1016  1217 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:17:10.743  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 14:17:10.743  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:10.743  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:10.743  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:10.753  2001  2166 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:10.753   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:17:10.753   278   979 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:17:10.753  2001  2166 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:10.763  2001  2166 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-26 14:17:10.793  2001  2166 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-26 14:17:10.903  6822  6830 I qtaguid : Untagging socket 33
,08-26 14:17:11.063  6743  6799 D executeNativeTests: Running unit tests
,08-26 14:17:11.123   288   288 E SMD     : DCD OFF
,08-26 14:17:11.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:11.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb added. We now have 2 listener(s)
,08-26 14:17:11.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:11.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:11.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:11.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:11.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 added. We now have 2 listener(s)
08-26 14:17:11.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:11.163  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:11.163  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.173  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:11.173  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:11.173  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:11.173  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.173  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:11.173  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:11.173  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 14:17:11.173  6743  6799 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 14:17:11.173  6743  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:11.173  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:11.173  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:11.173  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 14:17:11.183  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.183  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.183  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.183  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.183  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:11.183  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb removed from the list
08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.183  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 removed from the list
,08-26 14:17:11.183  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.183  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.183  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.183  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.183  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.183  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.183  6743  6799 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 14:17:11.183  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.183  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.183  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.183  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.183  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.183  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
,08-26 14:17:11.183  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.183  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.183  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.183  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.183  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.183  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.193  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.193  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.193  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.193  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.193  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:11.193  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.193  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.193  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.193  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.193  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.193  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.193  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.193  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.193  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.193  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.193  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.193  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.193  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.193  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.203  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.203  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.203  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.203  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.203  6743  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:11.203  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.203  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:11.213  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.213  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:11.213  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:11.213  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:11.213  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:11.213  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:11.213  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:11.213  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:11.213  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:11.223  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:11.223  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:11.233  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:11.233  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 14:17:11.233  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 14:17:11.233  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:11.233  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:11.233  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:11.253  3164  3332 D BtGatt.GattService: registerClient() - UUID=e26ec0ca-8fa9-4979-853a-89ffa9d43f8f
,08-26 14:17:11.303  6853  6853 I dex2oat : ----------------------------------------------------,
08-26 14:17:11.303  6853  6853 I dex2oat : <SS>: S T A R T I N G . . .
,08-26 14:17:11.303  6853  6853 I dex2oat : <SS>: Zip is absent. Canceled.
08-26 14:17:11.303  6853  6853 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 14:17:11.303  3164  3252 D BtGatt.GattService: onClientRegistered() - UUID=e26ec0ca-8fa9-4979-853a-89ffa9d43f8f, clientIf=6,
,08-26 14:17:11.313  6743  6755 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:11.313  3164  3331 D BtGatt.GattService: start scan with filters
,08-26 14:17:11.313  3164  3264 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:11.313  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:11.313  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 14:17:11.313  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 14:17:11.313  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:11.313  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.313  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:11.323  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.323  3164  3264 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:11.323  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:11.333  6743  6799 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:11.333  3164  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 14:17:11.333  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.333  3164  3264 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:11.333  3164  3264 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:11.333  3164  3264 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 14:17:11.333  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:11.333  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.333  3164  3264 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:11.333  3164  3264 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:11.333  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.333  6743  6799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:11.333  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.333  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:11.333  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.333  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:11.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:11.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:11.333  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:11.333  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:11.333  3164  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 14:17:11.333  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:11.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:11.333  3164  3172 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:11.343  3164  3332 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:11.343  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:11.343  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:11.343  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.343  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 14:17:11.343  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:11.343  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 14:17:11.343  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:11.343  3164  3264 D BtGatt.ScanManager: filter size is 1
,08-26 14:17:11.343  3164  3264 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 14:17:11.343  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:11.343  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 14:17:11.343  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.343  3164  3264 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:11.353  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:11.353  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:11.353  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:11.353  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:11.353  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.353  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.353  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.353  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:11.353  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.353  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.353  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.353  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.353  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.353  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.353  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.353  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 14:17:11.353  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.353  6743  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 14:17:11.353  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:11.353  3164  3264 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:11.363  3164  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:11.363  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.363  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:11.363  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:11.363  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:11.363  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:11.363  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 14:17:11.363  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:11.363  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:11.363  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:11.363  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.373  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.373  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:11.383  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:11.383  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:11.383  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:11.383  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 14:17:11.383  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:11.393  6853  6853 I dex2oat : dex2oat took 89.944ms (threads: 4)
,08-26 14:17:11.393  3164  3332 D BtGatt.GattService: registerClient() - UUID=be90836d-edfd-4edd-af0d-d0fd4c9f9dbf
,08-26 14:17:11.403  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:11.403  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:11.403  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:11.403  6822  6830 I Adreno-EGL: Local Branch: 
08-26 14:17:11.403  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:11.403  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:11.403  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:11.433  3164  3252 D BtGatt.GattService: onClientRegistered() - UUID=be90836d-edfd-4edd-af0d-d0fd4c9f9dbf, clientIf=6
,08-26 14:17:11.433  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:11.433  3164  3331 D BtGatt.GattService: start scan with filters
,08-26 14:17:11.433  3164  3264 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:11.433  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:11.433  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:11.433  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 14:17:11.433  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:11.443  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.443  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.443  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:11.443  3164  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:11.443  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.443  3164  3264 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:11.443  3164  3264 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:11.443  3164  3264 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 14:17:11.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:11.453  6743  6799 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:11.453  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:11.453  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.453  3164  3264 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:11.453  3164  3264 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:11.453  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.453  6743  6799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:11.453  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:11.453  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:11.453  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:11.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:11.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 14:17:11.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:11.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:11.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:11.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:11.453  3164  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:11.453  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.463  3164  3172 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:11.463  3164  3332 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:11.463  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:11.463  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:11.463  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:11.463  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:11.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:11.463  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:11.473  3164  3264 D BtGatt.ScanManager: filter size is 1
,08-26 14:17:11.473  3164  3264 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 14:17:11.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:11.473  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:11.473  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:11.473  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:11.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:11.473  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.473  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.473  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.473  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.473  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:11.473  6743  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 14:17:11.473  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.483  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:11.483  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:11.483  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:11.483  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:11.483  6822  6830 I Adreno-EGL: Local Branch: 
08-26 14:17:11.483  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:11.483  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:11.483  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:11.483  3164  3264 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.483  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:11.483  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 14:17:11.483  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.483  3164  3264 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:11.483  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:11.493  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:11.493  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:11.493  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:11.493  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:11.493  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:11.493  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:11.493  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.493  3164  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 14:17:11.493  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.493  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:11.493  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.503  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:11.503  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:11.503  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:11.503  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 14:17:11.503  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:11.503  3164  3172 D BtGatt.GattService: registerClient() - UUID=023b6b7c-315d-419a-a817-0fd02e515b24
,08-26 14:17:11.553  3164  3252 D BtGatt.GattService: onClientRegistered() - UUID=023b6b7c-315d-419a-a817-0fd02e515b24, clientIf=6
,08-26 14:17:11.553  6743  6755 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:11.553  3164  3178 D BtGatt.GattService: start scan with filters
,08-26 14:17:11.553  1016  3369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:11.553  3164  3264 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:11.553  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:11.553  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:11.553  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 14:17:11.553  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:11.563  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.563  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:11.563  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:11.563  3164  3252 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:11.563  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.563  3164  3264 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:11.563  3164  3264 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:11.563  3164  3264 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 14:17:11.563  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:11.563  6743  6799 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:11.563  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.573  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:11.573  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.573  3164  3264 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:11.573  3164  3264 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:11.573  6743  6799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 14:17:11.573  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.573  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 14:17:11.573  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.573  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:11.573  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 14:17:11.573  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:11.573  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:11.573  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:11.573  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 14:17:11.573  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:11.573  3164  3172 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:11.573  3164  3178 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:11.583  3164  3252 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:11.583  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:11.583  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:11.583  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 14:17:11.583  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.583  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.583  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.583  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.583  6743  6799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:11.583  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.583  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.583  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:11.583  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.583  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.583  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.583  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.583  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:11.583  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.583  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 14:17:11.593  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  3164  3264 D BtGatt.ScanManager: filter size is 1
08-26 14:17:11.593  3164  3264 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:11.593  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.593  6743  6799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 14:17:11.593  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.593  6743  6799 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 14:17:11.593  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.593  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
,08-26 14:17:11.593  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.593  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.593  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.593  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.593  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:11.603  3164  3252 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:11.603  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.603  3164  3264 D BtGatt.ScanManager: stopping BLe Batch
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.603  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-26 14:17:11.603  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:11.603  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:11.603  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:11.603  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:11.603  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.603  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.603  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:11.603  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.603  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.603  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop,
,08-26 14:17:11.603  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.603  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.603  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.603  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.603  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.603  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.603  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:11.603  6743  6799 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 14:17:11.603  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:11.603  6743  6799 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:11.603  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:11.603  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 14:17:11.603  6743  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:11.603  6743  6799 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 14:17:11.603  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:11.603  6743  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:11.603  6743  6799 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 14:17:11.613  3164  3252 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:11.613  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.613  3164  3264 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 14:17:11.613  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:11.613  6743  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:11.613  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:11.613  3164  3252 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:11.613  3164  3252 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:11.613  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 14:17:11.623  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 14:17:11.623  6743  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:11.623  6743  6799 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 14:17:11.623  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.623  6743  6862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1310)
08-26 14:17:11.623  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.623  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.623  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.623  6743  6799 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 14:17:11.623  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.623  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.623  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.623  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.623  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.623  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.623  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 14:17:11.633  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.633  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.633  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6862 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 14:17:11.633  6743  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:11.633  6743  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:11.633  6743  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:11.633  6743  6799 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:11.633  6743  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:11.633  6743  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 14:17:11.633  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.633  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.633  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.633  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.633  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.633  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.633  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.643  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.643  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.643  6743  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1310
08-26 14:17:11.643  6743  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1310)
08-26 14:17:11.643  6743  6863 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cb4899a, channel: -1, state: INIT
08-26 14:17:11.643  6743  6863 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cb4899a, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
08-26 14:17:11.643  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.643  6743  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1310)
08-26 14:17:11.643  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.643  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.643  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.643  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 14:17:11.643  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.643  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.643  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.643  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.643  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:11.643  6743  6862 D BluetoothSocket: connect(): myUserId = 0
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 14:17:11.643  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.643  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:11.643  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.643  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6743 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 14:17:11.653  6743  6743 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 14:17:11.653  6743  6862 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cb4899a, channel: -1, state: CLOSED
08-26 14:17:11.653  6743  6862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1310)
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.653  6743  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 14:17:11.653  6743  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.653  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.653  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.653  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.653  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.653  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:11.653  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.653  6743  6799 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 14:17:11.653  6743  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:11.653  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:11.653  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.653  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.653  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.653  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.653  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.653  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.653  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.653  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.663  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.663  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.663  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.663  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.663  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:11.663  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:11.663  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f9dcdb not in the list
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.663  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:11.663  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:11.663  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:11.663  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ff378 not in the list
08-26 14:17:11.663  6743  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 14:17:11.663  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:11.663  6743  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 14:17:11.663  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:11.673  6743  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 14:17:11.673  6743  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:11.673  6743  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:11.673  6743  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 14:17:11.673  6743  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 14:17:11.673  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:11.673  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e7b2cb added. We now have 2 listener(s)
08-26 14:17:11.673  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:11.673  6743  6799 D BluetoothAdapter: enable()
08-26 14:17:11.673  6743  6799 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 14:17:11.683  1016  1077 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:11.683  1016  1077 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:11.683  1016  1077 D SecContentProvider2: mCursor = null
08-26 14:17:11.683  1016  1077 D WifiService: setWifiEnabled: true pid=6743, uid=10171
08-26 14:17:11.683  1016  1077 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:11.683  1016  1077 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:11.683  1016  1077 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:11.683  1016  1077 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 14:17:11.683  1016  1077 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:11.683  1016  1077 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:11.683  1016  1077 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:11.683  1016  1077 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 14:17:11.683  1016  1077 D SettingsProvider: name = wifi_on
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c232aa8 added. We now have 3 listener(s)
08-26 14:17:11.693  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e889c1 added. We now have 4 listener(s)
08-26 14:17:11.693  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:11.693  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3441a566 added. We now have 5 listener(s)
08-26 14:17:11.693  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:11.703  1016  2134 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:11.703  1016  2134 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:11.703  1016  2134 D SecContentProvider2: mCursor = null
08-26 14:17:11.703  1016  2134 D WifiService: setWifiEnabled: false pid=6743, uid=10171
08-26 14:17:11.703  1016  2134 D SettingsProvider: name = wifi_on
08-26 14:17:11.713  1016  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 14:17:11.713  6743  6799 D BluetoothAdapter: disable()
08-26 14:17:11.713  1369  1369 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 14:17:11.713  1369  1369 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 14:17:11.713  1369  1369 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:11.713  1369  1369 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 14:17:11.713  1016  1028 D SettingsProvider: name = bluetooth_on
,08-26 14:17:11.723  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 14:17:11.733  3164  3236 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 14:17:11.733  3164  3236 D BluetoothAdapterProperties: Setting state to 13
08-26 14:17:11.733  3164  3236 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:11.733  3164  3236 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:11.733  3164  3236 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 14:17:11.733  1016  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:11.733  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 14:17:11.733  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:11.733  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:11.733  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:11.733  3164  3164 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 14:17:11.743  3164  3164 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d00016, channel: 19, state: LISTENING
08-26 14:17:11.743  3164  3164 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d00016, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3794473e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@269aed97mSocket: android.net.LocalSocket@3e255b84 impl:android.net.LocalSocketImpl@23e25f6d fd:FileDescriptor[74]
08-26 14:17:11.743  3164  3164 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e255b84 impl:android.net.LocalSocketImpl@23e25f6d fd:FileDescriptor[74]
08-26 14:17:11.743  3164  3236 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:11.743  3164  3236 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 14:17:11.743  3164  3236 D BluetoothAdapterService: terminating service from this receiver
,08-26 14:17:11.743  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:11.743  1016  1127 E WifiNative-wlan0: do suspend true
,08-26 14:17:11.743  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:11.743  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:11.743  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:11.743  3164  3236 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:11.743  3164  3236 D BluetoothAdapterProperties: mDiscovering is false
,08-26 14:17:11.743  1016  2134 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 14:17:11.743  3164  3236 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 14:17:11.753  1303  1303 D BluetoothPbap: Proxy object disconnected
,08-26 14:17:11.753  1303  1303 D PbapServerProfile: Bluetooth service disconnected
08-26 14:17:11.753  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:11.753  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:11.753  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-26 14:17:11.763  3164  3252 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-26 14:17:11.763  1177  1177 D BluetoothTile:  onBluetoothStateChange:
08-26 14:17:11.763  3164  3252 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:11.763  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:11.763  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:11.763  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:11.763  1177  1177 D BluetoothTile:  getBluetoothState : 13
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.763  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:11.763  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:11.763  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.763  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:11.773  1882  1882 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:11.773  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:11.773  1016  1077 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:11.773  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:11.773  1016  1465 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:11.773  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:11.773  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 14:17:11.773  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:11.773  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:11.773  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:11.773  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:11.783  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:11.783  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.783  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.783  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.793  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.793  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:11.803  1016  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:11.803  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:11.803  3164  3236 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 14:17:11.803  3164  3236 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 14:17:11.803  3164  3236 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 14:17:11.803  3164  3236 E bt-btif : cmd socket is not created
08-26 14:17:11.803  3164  5098 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 14:17:11.803  3164  3236 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 14:17:11.803  3164  3278 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-26 14:17:11.803  3164  3278 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 14:17:11.803  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:11.813  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:11.813  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:11.813  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:11.813  3164  3278 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 14:17:11.813  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:11.813  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:11.813  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 14:17:11.813  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:11.813  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:11.813  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:11.813  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:11.823  3164  3164 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3616cc33, channel: 5, state: LISTENING
08-26 14:17:11.823  3164  3164 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3616cc33, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fcb699f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c5eabf0mSocket: android.net.LocalSocket@18528569 impl:android.net.LocalSocketImpl@17fefbee fd:FileDescriptor[76]
08-26 14:17:11.823  3164  3164 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18528569 impl:android.net.LocalSocketImpl@17fefbee fd:FileDescriptor[76]
,08-26 14:17:11.833  3164  3164 I BtOppRfcommListener: stopping Accept Thread
,08-26 14:17:11.833  3164  3164 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3067f88f, channel: 12, state: LISTENING
08-26 14:17:11.833  3164  3164 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3067f88f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3181e131, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@179a971cmSocket: android.net.LocalSocket@22850f25 impl:android.net.LocalSocketImpl@18e2e8fa fd:FileDescriptor[80]
08-26 14:17:11.833  3164  3164 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22850f25 impl:android.net.LocalSocketImpl@18e2e8fa fd:FileDescriptor[80]
,08-26 14:17:11.833  3164  5098 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 14:17:11.833  3164  3164 V BluetoothOppManager: cleanUp...
,08-26 14:17:11.833  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:11.843  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:11.853  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:11.853  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 14:17:11.853  1016  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 14:17:11.853  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:11.853  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:11.853  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:11.853  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:11.853  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:11.853  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:11.853  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:11.853  6822  6830 I Adreno-EGL: Local Branch: 
08-26 14:17:11.853  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:11.853  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:11.853  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:11.863  6871  6871 E Zygote  : MountEmulatedStorage()
08-26 14:17:11.863  6871  6871 E Zygote  : v2
,08-26 14:17:11.863  6871  6871 I libpersona: KNOX_SDCARD checking this for 10055
08-26 14:17:11.863  6871  6871 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:11.863  1016  1475 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6871 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 14:17:11.873  6871  6871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:11.873  6871  6871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:11.873  6871  6871 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:11.903  6871  6871 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 14:17:11.903  6871  6871 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:11.933  6871  6871 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 14:17:11.963  6871  6871 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 14:17:11.963  6871  6871 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 14:17:11.963  6871  6871 D UserAnalysis: Create SecureDbHelper
,08-26 14:17:11.973  6871  6871 D IntelligenceServiceApplication: onCreate(),
,08-26 14:17:11.983  1016  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 14:17:11.983  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:11.983  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:11.983  6871  6871 D IntelligenceServiceApplication: no applications having user consent for prediction
08-26 14:17:11.983  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:11.983  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:12.003  6886  6886 E Zygote  : MountEmulatedStorage()
,08-26 14:17:12.003  6886  6886 E Zygote  : v2
08-26 14:17:12.003  6886  6886 I libpersona: KNOX_SDCARD checking this for 10105
08-26 14:17:12.003  6886  6886 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:12.003  6886  6886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:12.003  1016  1475 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6886 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-26 14:17:12.003  1016  2140 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 14:17:12.003  6886  6886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:12.003  6871  6871 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 14:17:12.003  6886  6886 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:12.003  3164  3278 W bt-btif : ag scb idx 1 not allocated
08-26 14:17:12.003  3164  3278 W bt-btif : ag scb idx 2 not allocated
08-26 14:17:12.003  3164  3278 E bt-btif : BTA AG is already disabled, ignoring ...,
08-26 14:17:12.003  3164  3319 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:12.003  3164  3319 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 14:17:12.003  3164  3252 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:12.003  3164  3280 I bt_vendor: hw_epilog_process
08-26 14:17:12.003  3164  3252 D bt_userial_mct: userial_close
08-26 14:17:12.003  3164  3252 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 14:17:12.013  2001  6870 I art     : Explicit concurrent mark sweep GC freed 55663(3MB) AllocSpace objects, 8(320KB) LOS objects, 40% free, 11MB/18MB, paused 1.616ms total 94.995ms
,08-26 14:17:12.013  6871  6871 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 14:17:12.023  1016  1028 I ActivityManager: Killing 6444:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 14:17:12.033  2001  6820 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:17:12.033  6886  6886 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:12.033  2001  6820 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 14:17:12.033  2001  6820 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
08-26 14:17:12.033  6886  6886 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:12.123   283   283 I WVCdm   : CdmEngine::CloseSession
,08-26 14:17:12.123   283   283 I WVCdm   : L3 Terminate.
,08-26 14:17:12.143   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 14:17:12.143   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:12.143  6886  6910 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 14:17:12.153   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 14:17:12.153   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:12.153  6886  6910 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 14:17:12.153  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.303  1016  1503 I ActivityManager: Killing 6342:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.293  6886  6886 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:12.293  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:12.303  1016  1126 D WifiP2pService: InactiveState{ what=147461 }
08-26 14:17:12.303  1369  1369 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
08-26 14:17:12.313  1016  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-26 14:17:12.313  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:12.313  1016  1126 D WifiP2pService: DefaultState{ what=147461 }
08-26 14:17:12.313   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:12.313  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
08-26 14:17:12.313  2001  3022 V NativeCrypto: Read error: ssl=0xb7cfda80: I/O error during system call, Connection timed out
08-26 14:17:12.313  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 14:17:12.313  2001  6820 I qtaguid : Untagging socket 72
08-26 14:17:12.313  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:12.313  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:12.313  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:12.313  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-26 14:17:12.323  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:12.323  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:12.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.323  2001  3022 V NativeCrypto: SSL shutdown failed: ssl=0xb7cfda80: I/O error during system call, Broken pipe
08-26 14:17:12.323  2001  3022 E GCM     : Wifi connection closed with errorCode 20
08-26 14:17:12.323  1016  1475 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-26 14:17:12.323  3164  3252 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:12.323  3164  3252 I bt_vendor: bluetooth satus is on
08-26 14:17:12.323  3164  3252 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:12.323  3164  3252 I bt_vendor: Starting hciattach daemon
08-26 14:17:12.323  3164  3252 I bt_vendor: try to set false
08-26 14:17:12.333  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:12.333  3164  3252 I bt_vendor: Starting hciattach daemon
08-26 14:17:12.333  3164  3252 I bt_vendor: try to set false
08-26 14:17:12.333  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 14:17:12.333  3164  3252 I bt_vendor: cleanup
08-26 14:17:12.333  3164  3278 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:12.333  3164  3252 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:12.333  3164  3252 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 14:17:12.333  2001  6820 W GLSUser : [AppCertManager] IOException while requesting key: 
08-26 14:17:12.333  2001  6820 W GLSUser : java.net.SocketTimeoutException: failed to connect to android.clients.google.com/172.217.21.110 (port 443) after 30000ms: isConnected failed: ETIMEDOUT (Connection timed out)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:236)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dja.a(:com.google.android.gms:233)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:12.333  2001  6820 W GLSUser : Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
08-26 14:17:12.333  2001  6820 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
08-26 14:17:12.333  2001  6820 W GLSUser : 	... 32 more
08-26 14:17:12.343  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:12.343  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:12.343  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 14:17:12.343  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:12.343  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 14:17:12.343  1016  1739 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:17:12.343  1016  1739 I qtaguid : Tagging socket 345 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
08-26 14:17:12.343  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:12.343  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:12.343  1016  1126 D WifiP2pService: InactiveState{ what=131204 }
08-26 14:17:12.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.343  1016  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 14:17:12.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.343  1016  1739 I qtaguid : Untagging socket 345
08-26 14:17:12.343  1016  1739 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:17:12.353  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 14:17:12.353  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 14:17:12.363  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-26 14:17:12.363  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:12.363  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:12.363  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:12.363  1016  1126 D WifiP2pService: P2pDisablingState
08-26 14:17:12.363  1016  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 14:17:12.363  1016  1126 D WifiP2pService: p2p socket connection lost
08-26 14:17:12.363  3164  3236 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 14:17:12.363  1016  1126 D WifiP2pService: P2pDisabledState
08-26 14:17:12.373  3164  3236 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:12.373  3164  3236 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 14:17:12.373  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:12.373  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:12.373  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 14:17:12.373  1016  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 14:17:12.373  1016  1127 E WifiNative-wlan0: do suspend true
,08-26 14:17:12.383  1016  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 14:17:12.383  1016  1126 D WifiP2pService: DefaultState{ what=143375 }
08-26 14:17:12.383  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 14:17:12.383  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-26 14:17:12.393  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:12.393  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:12.393  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 14:17:12.393  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 14:17:12.393  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:12.393  1016  1046 D WifiDisplayController: disconnect
08-26 14:17:12.393  1016  1046 D WifiDisplayController: updateConnection
08-26 14:17:12.393  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:12.393  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:12.393  1016  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
08-26 14:17:12.393  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.393  1016  1129 V NetworkStats: updateIfacesLocked()
08-26 14:17:12.393  1016  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:12.403  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:12.403   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:17:12.403   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-26 14:17:12.403  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:12.403  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.403  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:12.403  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.403  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.403  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 14:17:12.403  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.403  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 14:17:12.403  3164  3164 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:12.403  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:12.403  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:12.403  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:12.403   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:12.403  3164  3164 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:12.403  3164  3164 D BtGatt.GattService: stop()
08-26 14:17:12.403  3164  3164 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 14:17:12.403  1016  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:12.403  1016  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:12.403  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.403  1016  1129 V NetworkStats: performPollLocked() took 10ms
,08-26 14:17:12.413  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.413  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.413  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:12.413  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:12.413  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:12.413  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.413  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.413  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.413  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.413  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:12.413  1619  1619 I Hs20UtilService: Starting #8
,08-26 14:17:12.413  1619  1678 I Hs20UtilService: Message received 5007
08-26 14:17:12.413  6886  6914 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 14:17:12.413  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:12.413  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:12.413  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:12.413  1016  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.413  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:12.413  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-26 14:17:12.413  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.413  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:12.423  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 14:17:12.413  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.413  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.413  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:12.423  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 14:17:12.423  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 14:17:12.423  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:12.423  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:12.423  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:12.423  1369  1369 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:12.423  1016  1465 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:12.423  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:12.433  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:12.433  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:12.433  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.433  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.433  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.433  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 14:17:12.433  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.433  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:12.433  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.433  1016  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 14:17:12.433  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.433  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.433  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:12.433  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:12.433  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:12.433  1177  1731 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 14:17:12.433  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:12.433  1016  1127 D SecContentProvider2: mCursor = null
08-26 14:17:12.443  1016  1739 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:12.443  4694  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 14:17:12.443  1016  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:12.443  1016  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 14:17:12.443  1016  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 14:17:12.443  1016  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-26 14:17:12.443  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 14:17:12.443  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 14:17:12.443  1458  1458 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:17:12.443  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 14:17:12.453  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:12.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 14:17:12.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:12.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 14:17:12.453  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:12.453  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:12.463  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:12.463  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 14:17:12.463  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.463  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.463  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.463  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.463  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 14:17:12.463  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.463  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.463  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 14:17:12.463  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:12.463  1016  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 14:17:12.463  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 14:17:12.463  1016  2134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:12.463  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.463  1016  2134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:12.463  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 14:17:12.463  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-26 14:17:12.463  1016  1130 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:12.473  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.473  1016  1124 V NetworkStats: updateIfacesLocked()
08-26 14:17:12.473  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:12.473  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:12.473  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:12.473  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:12.473  1016  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 14:17:12.473  1016  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 14:17:12.473  1016  1129 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:12.473  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:12.473  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:12.473  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:12.473  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:12.473  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 14:17:12.473  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 14:17:12.473  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 14:17:12.473  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:12.473  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:12.473  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 14:17:12.473  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 14:17:12.473  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:12.473  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:12.473  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:12.473  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:12.473  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:12.483  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.483  1016  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 14:17:12.483  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.483  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:12.483  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.483  1016  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.483  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:12.483  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.483  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.483  1016  1124 V NetworkStats: performPollLocked() took 14ms
08-26 14:17:12.483  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.483  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:12.483  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:12.483  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-26 14:17:12.483  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:12.483  1016  2134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.483  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 14:17:12.483  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.483  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.483  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:12.483  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.483  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.483  3164  3236 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:12.493  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.493  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:12.493  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:12.493  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:12.493  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 14:17:12.493  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:12.493  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.493  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:12.493  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:12.493  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:12.493  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:12.493  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 14:17:12.493  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:12.493  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:12.493  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:12.493  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 14:17:12.493  3164  3236 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 14:17:12.503  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 14:17:12.503  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.503  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.503  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.503  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:12.513  6929  6929 E Zygote  : MountEmulatedStorage()
08-26 14:17:12.513  1016  1217 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6929 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:12.513  6929  6929 E Zygote  : v2
08-26 14:17:12.513  6929  6929 I libpersona: KNOX_SDCARD checking this for 10064
08-26 14:17:12.513  6929  6929 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:12.513  6929  6929 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:12.513  1016  1077 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 14:17:12.513  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 14:17:12.523  6929  6929 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:12.523  6929  6929 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:12.523  1016  1077 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:12.523  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 14:17:12.523  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:12.523  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:12.523  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:12.523  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:12.523  3164  3236 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:12.523  3164  3236 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 14:17:12.523  3164  3236 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 14:17:12.523  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-26 14:17:12.523  3164  3164 D HeadsetService: Received stop request...Stopping profile...
,08-26 14:17:12.533  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.533  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 14:17:12.533  3164  3164 D A2dpService: Received stop request...Stopping profile...
08-26 14:17:12.533  3164  3268 D A2dpStateMachine: Exit Disconnected: -1
08-26 14:17:12.533  1303  1303 D HeadsetProfile: Bluetooth service disconnected
,08-26 14:17:12.533  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.543  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:12.543  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 14:17:12.543  3164  3164 D HidService: Received stop request...Stopping profile...
08-26 14:17:12.543  3164  3164 D HidService: Stopping Bluetooth HidService
08-26 14:17:12.543  3164  3164 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:12.543  3164  3164 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 14:17:12.543  3164  3164 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 14:17:12.543  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:12.543  1303  1303 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:12.543  1303  1303 D A2dpProfile: Bluetooth service disconnected
08-26 14:17:12.543  1303  1303 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:12.543  1303  1303 D HidProfile: Bluetooth service disconnected
,08-26 14:17:12.543  3164  3164 D HealthService: Received stop request...Stopping profile...
08-26 14:17:12.543  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.543  3164  3164 D PanService: Received stop request...Stopping profile...
08-26 14:17:12.543  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.543  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:12.543  6929  6929 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:12.553  3164  3164 D BluetoothMapService: Received stop request...Stopping profile...
08-26 14:17:12.553  1303  1303 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:12.553  1303  1303 D PanProfile: Bluetooth service disconnected
,08-26 14:17:12.553  6929  6929 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:12.553  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:12.553  2001  2166 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 14:17:12.563  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.563  3164  3164 D SapService: Received stop request...Stopping profile...
08-26 14:17:12.563  3164  3164 D SapService: Stopping Bluetooth SapService
08-26 14:17:12.563  3164  3164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:12.563  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-26 14:17:12.563  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:12.563  3164  3164 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:12.563  1303  1303 D BluetoothMap: Proxy object disconnected
08-26 14:17:12.563  3164  3164 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:12.563  1303  1303 D MapProfile: Bluetooth service disconnected
08-26 14:17:12.563  3164  3164 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:12.563  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 14:17:12.563  1303  1303 D SapProfile: Bluetooth service disconnected
,08-26 14:17:12.563  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 14:17:12.563  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:12.563  3164  3164 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 14:17:12.563  3164  3164 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:12.563  3164  3164 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 14:17:12.573  2001  2166 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-26 14:17:12.573  3164  3269 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 14:17:12.573  3164  3164 I GKI_LINUX: GKI_exit_task 2 done
08-26 14:17:12.573  3164  3164 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 14:17:12.573  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 14:17:12.573  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 14:17:12.573  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:12.573  3164  3164 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:12.573  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 14:17:12.573  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:12.573  3164  3164 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:12.573  3164  3164 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 14:17:12.573  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 14:17:12.573  3164  3164 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:12.573  3164  3164 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 14:17:12.573  3164  3164 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 14:17:12.573  6929  6929 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:12.573  3164  3164 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 14:17:12.573  3164  3164 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 14:17:12.573  2001  2166 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 14:17:10.636+0200, stopTime=2016-08-26 14:17:12.590+0200, duration=1954ms
08-26 14:17:12.573  3164  3236 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 14:17:12.573  3164  3236 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:12.573  3164  3236 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:12.573  3164  3236 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:12.573  3164  3236 D BluetoothAdapterService: updateAdapterState state is 10
08-26 14:17:12.573  1177  1963 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.573  1177  1963 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:12.573  3164  3178 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:12.573  3164  3236 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:12.573  3164  3236 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 14:17:12.573  3164  3236 I BluetoothAdapterState: Entering OffState
,08-26 14:17:12.583  1369  1369 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 14:17:12.583  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:12.583  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:12.583  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:12.583  6743  6755 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.583  6743  6755 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.583  6743  6755 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 14:17:12.583  6743  6755 D BluetoothLeAdvertiser: Exit stop advertising
08-26 14:17:12.583  6743  6755 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 14:17:12.583  6743  6755 D BluetoothLeScanner: Exiting stopAllScan
,08-26 14:17:12.593  2001  6945 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:12.593   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:17:12.593   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 14:17:12.593  2001  2021 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:12.593  2001  2021 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.593  6929  6929 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:12.593  1303  1318 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 14:17:12.593  6929  6929 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 14:17:12.603  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.603  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.603  1458  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.603  1458  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:12.603  1438  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.603  1438  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.603  3164  3332 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.603  3164  3332 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:12.603  1369  1369 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 14:17:12.603  1369  1369 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 14:17:12.603  1369  1369 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 14:17:12.603  1369  1369 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:12.603  1369  1369 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:12.603  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 14:17:12.603  1303  1312 D Bluetoothsap: Unbinding service...
,08-26 14:17:12.603  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.603  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.603  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:12.603  1016  1130 D Tethering: InitialState.processMessage what=4
08-26 14:17:12.613  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.613  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.613  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:12.613  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.613  1016  1130 E Tethering: No numeric data
08-26 14:17:12.613  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:12.613  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:12.613  1016  1130 D Tethering: clearTetheredNotification()
08-26 14:17:12.613  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:12.613  1303  1318 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.613  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 14:17:12.613  1303  1318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.613  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.613  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:12.613  1303  1312 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:12.613  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.613  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:12.613  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:12.613  1303  1318 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 14:17:12.623  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:12.623  1016  1124 V NetworkStats: performPollLocked() took 6ms
,08-26 14:17:12.633  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:12.633  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:12.633  6929  6929 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:12.633  2001  2001 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-26 14:17:12.633  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 14:17:12.633  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:12.633  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.633  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.633  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:12.653  6952  6952 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:12.653  6952  6952 E Zygote  : v2,
08-26 14:17:12.653  6952  6952 I libpersona: KNOX_SDCARD checking this for 10065
08-26 14:17:12.653  6952  6952 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:12.653  6952  6952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 14:17:12.653  1016  1217 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6952 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:12.653  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:12.653  6886  6901 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.653  6886  6901 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:12.663  6952  6952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:12.663  6952  6952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:17:12.663  1016  1503 I ActivityManager: Killing 6479:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 14:17:12.663   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71e87c8
08-26 14:17:12.663   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 14:17:12.663   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
,08-26 14:17:12.663   270   329 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1222735736)
08-26 14:17:12.663  1423  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:12.663  1423  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:12.663  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:12.663  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.673  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:12.673  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.683  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 14:17:12.683  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.683  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:12.683  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.683  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:12.683  6952  6952 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:12.693  6952  6952 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:12.693  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.693  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:12.693  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.693  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:12.693  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.703  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-26 14:17:12.703  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.703  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.703  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.703  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.703  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:12.703  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.703  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.713  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.713  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.713  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.713  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.713  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:12.713  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-26 14:17:12.713  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:12.713  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.713  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:12.723  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.723  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:12.723  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 14:17:12.723  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:12.723  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.723  1177  1752 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:12.723  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:12.723  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 14:17:12.723  1177  1752 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:12.723  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:12.723  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:12.723  1882  1882 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 14:17:12.723  1016  1465 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:12.723  1016  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 14:17:12.723  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:12.723  2001  2168 D BluetoothAdapter: 631950391: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:12.723  2001  2168 D BluetoothAdapter: 631950391: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:12.723  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 14:17:12.723   270   329 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-26 14:17:12.723   270   329 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 14:17:12.723   270   329 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1222735736) wakelock released: 1, error no: 0
08-26 14:17:12.723   270   329 I rmt_storage: 
08-26 14:17:12.733  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:12.733   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71e87c8
08-26 14:17:12.733  3164  3252 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 14:17:12.733  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:12.733  3164  3164 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:12.733  3164  3164 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 14:17:12.733  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:12.733  1016  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:12.733  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:12.733  1016  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 14:17:12.733  3164  3164 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 14:17:12.733  6952  6952 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 14:17:12.733  2001  2166 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 14:17:12.733  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.733  1016  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:12.733  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:12.743  3164  3164 I art     : System.exit called, status: 0
08-26 14:17:12.743  3164  3164 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:12.753  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:12.753  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-26 14:17:12.753  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:12.753  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 14:17:12.753  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.753  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.753  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:12.753  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:12.763  1016  1217 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6984 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 14:17:12.763  6984  6984 E Zygote  : MountEmulatedStorage(),
08-26 14:17:12.763  6984  6984 I libpersona: KNOX_SDCARD checking this for 10102
08-26 14:17:12.763  6984  6984 E Zygote  : v2
08-26 14:17:12.763  6984  6984 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:12.763  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:12.763  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 14:17:12.763  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:12.773  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:12.783  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:12.783  1016  1077 I ActivityManager: Killing 6528:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 14:17:12.793  1016  1476 I ActivityManager: Process com.android.bluetooth (pid 3164)(adj 0) has died(30,715)
,08-26 14:17:12.793  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:12.793  6984  6984 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:12.813  6984  6984 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 14:17:12.813  1016  3356 D SSRM:n  : SIOP:: AP = 380
,08-26 14:17:12.843  1369  1369 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 14:17:12.843  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.843  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:12.843  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:12.953  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 14:17:12.953  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:12.953  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:12.953  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 14:17:12.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:12.963  2001  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:12.963  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:12.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:12.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:12.963  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:12.963  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:12.963  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 14:17:12.963  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:12.963  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:12.963  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 14:17:12.973  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:12.973  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:12.973  1016  1016 I ApplicationPolicy: updateDataUsageMap
,08-26 14:17:12.973  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:12.983  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:12.983  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:13.023  6984  7007 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 14:17:13.033  6984  7007 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 14:17:13.033  6984  7007 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 14:17:13.033  6984  7007 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 14:17:13.063  6984  7007 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 14:17:13.063  6984  7007 I Babel_SMS: MmsConfig.loadFromResources
,08-26 14:17:13.063  6984  7007 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 14:17:13.063  6984  7007 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 14:17:13.083  1016  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 14:17:13.083  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 14:17:13.083  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.083  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:13.083  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 14:17:13.113  6984  6984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:13.113  6984  6984 I Babel_Crash: startup - clean
,08-26 14:17:13.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:13.153  1016  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:13.153  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:13.153  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.153  1016  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.153  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:13.153  1619  1619 I Hs20UtilService: Starting #9
,08-26 14:17:13.153  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:13.163  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:13.163  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:13.163  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:13.163  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:13.163  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:13.163  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:13.163  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:13.163  6984  6984 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:13.173  1016  1503 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:13.173  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:13.173  6984  6984 W AudioCapabilities: Unsupported mime audio/evrc
08-26 14:17:13.173  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.173  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.173  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:13.173  1619  1619 I Hs20UtilService: Starting #10
,08-26 14:17:13.173  6984  6984 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 14:17:13.173  1619  1678 I Hs20UtilService: Message received 5011
,08-26 14:17:13.183  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-26 14:17:13.183  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 14:17:13.183  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 14:17:13.183  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 14:17:13.183  6984  6984 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 14:17:13.193  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.193  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.193  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.213  6984  6984 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 14:17:13.213  6984  6984 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 14:17:13.223  6984  6984 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 14:17:13.223  6984  6984 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 14:17:13.223  6984  6984 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 14:17:13.233  6984  6984 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 14:17:13.233  6984  6984 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 14:17:13.233  6984  6984 W VideoCapabilities: Unsupported mime video/mp43
,08-26 14:17:13.233  6984  6984 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 14:17:13.243  6984  6984 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 14:17:13.253  6984  6984 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 14:17:13.273  6984  6984 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:13.273  6984  6984 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:13.273  6984  6984 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:13.283  6984  6984 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:13.283  1016  1465 I ActivityManager: Killing 6509:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 14:17:13.283  6984  6984 I vclib   : onServiceConnected
,08-26 14:17:13.323  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.323  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.323  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.323  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.323  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.323  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.333  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.333  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.333  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.333  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.333  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.333  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.343  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.343  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.343  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.343  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.343  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.353  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.353  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.353  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.363  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.363  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.363  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.363  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.373  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.373  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.373  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:13.383  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:13.383  1016  1325 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 14:17:13.383  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:13.383  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.383  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.383  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:13.383  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:13.383  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:13.393  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:13.393  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 14:17:13.403  1016  1077 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 14:17:13.403  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.403  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.403  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.403  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.413  1016  1077 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7011 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 14:17:13.413  7011  7011 E Zygote  : MountEmulatedStorage()
08-26 14:17:13.413  7011  7011 E Zygote  : v2
08-26 14:17:13.413  7011  7011 I libpersona: KNOX_SDCARD checking this for 1002
08-26 14:17:13.413  7011  7011 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:13.413  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:13.423  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:13.423  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:13.443  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 14:17:13.443  7011  7011 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:13.453  7011  7011 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 14:17:13.453  7011  7011 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:13.483  7011  7011 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding GattService
,08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding HidService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding HealthService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding PanService
,08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding SapService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding SapClientService
08-26 14:17:13.513  7011  7011 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 14:17:13.513  7011  7011 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 14:17:13.523  1016  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 14:17:13.523  1016  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.523  1016  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.523  1016  1476 D SettingsProvider: selectionArgs: false
,08-26 14:17:13.523  1016  1476 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.523  1016  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:13.523  1016  1476 D SettingsProvider: ret = -1
,08-26 14:17:13.523  1016  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:13.523  1016  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.523  1016  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.523  1016  1479 D SettingsProvider: selectionArgs: false
08-26 14:17:13.523  1016  1479 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:13.523  1016  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.523  1016  1479 D SettingsProvider: ret = -1
,08-26 14:17:13.523  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:13.523  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.523  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.523  1016  1478 D SettingsProvider: selectionArgs: false
,08-26 14:17:13.523  1016  1478 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.523  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.523  1016  1478 D SettingsProvider: ret = -1
,08-26 14:17:13.523  1016  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
08-26 14:17:13.523  1016  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.523  1016  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.523  1016  1465 D SettingsProvider: selectionArgs: false
,08-26 14:17:13.523  1016  1465 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.523  1016  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.523  1016  1465 D SettingsProvider: ret = -1
,08-26 14:17:13.523  1016  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 14:17:13.523  1016  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.523  1016  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.523  1016  1475 D SettingsProvider: selectionArgs: false
08-26 14:17:13.523  1016  1475 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.523  1016  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:13.523  1016  1475 D SettingsProvider: ret = -1,
08-26 14:17:13.523  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-26 14:17:13.523  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-26 14:17:13.533  1016  1029 D SettingsProvider: selectionArgs: false
,08-26 14:17:13.533  1016  1029 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.533  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 14:17:13.533  1016  1029 D SettingsProvider: ret = -1
08-26 14:17:13.533  1016  2134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 14:17:13.533  1016  2134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  2134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.533  1016  2134 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  2134 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:13.533  1016  2134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.533  1016  2134 D SettingsProvider: ret = -1
08-26 14:17:13.533  1016  1503 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 14:17:13.533  1016  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.533  1016  1503 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  1503 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.533  1016  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.533  1016  1503 D SettingsProvider: ret = -1
,08-26 14:17:13.533  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:13.533  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.533  1016  1028 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  1028 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.533  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.533  1016  1028 D SettingsProvider: ret = -1
08-26 14:17:13.533  1016  1077 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:13.533  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 14:17:13.533  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.533  1016  1077 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  1077 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.533  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.533  1016  1077 D SettingsProvider: ret = -1
08-26 14:17:13.533  1016  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 14:17:13.533  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:13.533  1016  1217 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  1217 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:13.533  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:13.533  1016  1217 D SettingsProvider: ret = -1
08-26 14:17:13.533  1016  1325 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 14:17:13.533  1016  1325 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:13.533  1016  1325 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:13.533  1016  1325 D SettingsProvider: selectionArgs: false
08-26 14:17:13.533  1016  1325 D SettingsProvider: selectionArgs: 1002
08-26 14:17:13.533  1016  1325 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:13.533  1016  1325 D SettingsProvider: ret = -1
,08-26 14:17:13.543  1016  1476 I ActivityManager: Killing 6578:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 14:17:13.543  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:13.543  1016  1503 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:13.543  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:13.543  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:13.553  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:13.553  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:13.563  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:13.563  2001  7027 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:13.563  1016  2140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-26 14:17:13.573  1016  2140 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:13.573  1016  2140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:13.573  1016  2140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:13.573  1016  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:13.573  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:13.573  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.573  1016  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:13.573  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:13.583  1619  1619 I Hs20UtilService: Starting #11
,08-26 14:17:13.583  1619  1678 I Hs20UtilService: Message received 5011
,08-26 14:17:13.583  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:13.583  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:13.583  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:13.583  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:13.593  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:13.593  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:13.593  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:13.593  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:13.603  1016  1043 D Tethering: interfaceRemoved wlan0
08-26 14:17:13.603  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-26 14:17:13.603  1016  1077 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 14:17:13.603  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:13.603  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.603  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.603  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.613  2001  7027 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 14:17:13.623  7028  7028 E Zygote  : MountEmulatedStorage()
08-26 14:17:13.623  7028  7028 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:13.623  7028  7028 E Zygote  : v2
08-26 14:17:13.623  7028  7028 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:13.623  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:13.623  1016  1077 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 14:17:13.623  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:13.623  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 14:17:13.653  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.653  7028  7028 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:13.673  7028  7028 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 14:17:13.673  7028  7028 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-26 14:17:13.673  7028  7028 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 14:17:13.693  7028  7028 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 14:17:13.703  7028  7028 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 14:17:13.703  7028  7028 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 14:17:13.703  7028  7028 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:13.703  1016  1503 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-26 14:17:13.703  1016  1503 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 14:17:13.703  7028  7043 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 14:17:13.713  1016  1028 I art     : Explicit concurrent mark sweep GC freed 51450(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.558ms total 160.299ms
,08-26 14:17:13.713  1805  1805 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 14:17:13.713  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 14:17:13.713  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:13.713  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.713  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.713  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.723  7046  7046 E Zygote  : MountEmulatedStorage()
,08-26 14:17:13.723  7046  7046 E Zygote  : v2
08-26 14:17:13.723  7046  7046 I libpersona: KNOX_SDCARD checking this for 10121
08-26 14:17:13.723  7046  7046 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:13.733  7046  7046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:13.733  7046  7046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:13.733  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7046 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 14:17:13.733  7046  7046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:13.733  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 14:17:13.733  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.733  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:13.733  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.733  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 14:17:13.743  1016  1043 D Tethering: interfaceRemoved p2p0
08-26 14:17:13.743  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 14:17:13.753  7058  7058 E Zygote  : MountEmulatedStorage()
,08-26 14:17:13.753  7058  7058 E Zygote  : v2
08-26 14:17:13.753  7058  7058 I libpersona: KNOX_SDCARD checking this for 10001
08-26 14:17:13.753  7058  7058 I libpersona: KNOX_SDCARD not a persona,
08-26 14:17:13.753  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:13.763  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:13.763  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7058 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:13.763  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 14:17:13.763  1016  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 14:17:13.763  7046  7046 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.763  7046  7046 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:13.773  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.773  2606  2619 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-26 14:17:13.773  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.773  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.773  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.783  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.783  7058  7058 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:13.783   304   304 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 946us total 29.908ms
,08-26 14:17:13.803   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.371ms
,08-26 14:17:13.823   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 16.463ms
,08-26 14:17:13.833  7076  7076 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:13.843  7076  7076 E Zygote  : v2
08-26 14:17:13.843  7076  7076 I libpersona: KNOX_SDCARD checking this for 10031
08-26 14:17:13.843  7076  7076 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:13.843  1016  1503 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7076 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,08-26 14:17:13.843  7076  7076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:13.843  1805  1805 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-26 14:17:13.843  1805  1805 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 14:17:13.843  1805  1805 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-26 14:17:13.843  1805  1805 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 14:17:13.853  7076  7076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:13.853  7076  7076 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:13.873  1805  1805 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 14:17:13.883  7046  7046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:13.883  7046  7046 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 14:17:13.883  7046  7046 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:13.883  1805  1805 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 14:17:13.883  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 14:17:13.883  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.883  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.883  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.883  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.883  7076  7076 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.893  7076  7076 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:13.903  7046  7046 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:13.903  7091  7091 E Zygote  : MountEmulatedStorage()
08-26 14:17:13.903  7091  7091 E Zygote  : v2
08-26 14:17:13.903  7091  7091 I libpersona: KNOX_SDCARD checking this for 10077
08-26 14:17:13.903  7091  7091 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:13.903  7091  7091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 14:17:13.903  1016  1217 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7091 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:13.913  7091  7091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:13.913  7091  7091 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 14:17:13.913  7046  7046 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 14:17:13.923  7046  7046 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 14:17:13.923  1016  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 14:17:13.923  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.923  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.923  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.923  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.933  7091  7091 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.933  7091  7091 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:13.943  7106  7106 E Zygote  : MountEmulatedStorage(),
08-26 14:17:13.943  7106  7106 I libpersona: KNOX_SDCARD checking this for 10141
08-26 14:17:13.943  7106  7106 E Zygote  : v2
08-26 14:17:13.943  7106  7106 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:13.943  7106  7106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:13.943  1016  1478 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7106 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-26 14:17:13.943  1016  1478 I ActivityManager: Killing 6590:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-26 14:17:13.953  7106  7106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:13.953  7106  7106 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:13.963  7076  7076 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 14:17:13.963  1016  1325 I ActivityManager: Killing 6611:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 14:17:13.983  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 14:17:13.983  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.983  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.983  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:13.983  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:13.983  7106  7106 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:13.983  7106  7106 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:13.983  2761  7121 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 14:17:13.983  2761  7121 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-26 14:17:13.983  2761  7121 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 14:17:13.993  2761  7121 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-26 14:17:13.993  2761  7121 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 14:17:13.993  7124  7124 E Zygote  : MountEmulatedStorage()
08-26 14:17:13.993  7124  7124 I libpersona: KNOX_SDCARD checking this for 10032
08-26 14:17:13.993  7124  7124 E Zygote  : v2
08-26 14:17:13.993  7124  7124 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:13.993  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:14.003  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:14.003  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 14:17:14.003  1016  1217 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7124 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:14.023  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 14:17:14.023  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.023  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.023  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.023  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.023  7106  7106 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 14:17:14.023  7106  7106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:14.023  7106  7106 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:14.023  7106  7106 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:14.033  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:14.033  7124  7124 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.053  7140  7140 E Zygote  : MountEmulatedStorage()
,08-26 14:17:14.053  7140  7140 E Zygote  : v2
08-26 14:17:14.053  7140  7140 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:14.053  7140  7140 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:14.053  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 14:17:14.053  1016  1479 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7140 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 14:17:14.053  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:14.053  1016  1479 I ActivityManager: Killing 6546:com.android.providers.calendar/u0a37 (adj 15): empty #21,
,08-26 14:17:14.053  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:14.083  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:14.083  7140  7140 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.113  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.123   288   288 E SMD     : DCD OFF
,08-26 14:17:14.133  1016  1476 D RCPManagerService: exchangeData() failure , invalid userId
08-26 14:17:14.133  7140  7140 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 14:17:14.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:14.143  7124  7156 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 14:17:14.143  7124  7156 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 14:17:14.153  7124  7156 D SPPClientService: PushLog.txt file is not deleted.
08-26 14:17:14.153  7124  7156 D SPPClientService: PushLog.txt file is not deleted.
08-26 14:17:14.153  7124  7156 D SPPClientService: ============PushLog. stop!
,08-26 14:17:14.173  7124  7124 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 14:17:14.173  1016  1217 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 14:17:14.173  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.173  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.173  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.173  1016  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.193  7161  7161 E Zygote  : MountEmulatedStorage(),
08-26 14:17:14.193  7161  7161 E Zygote  : v2
08-26 14:17:14.193  7161  7161 I libpersona: KNOX_SDCARD checking this for 10036,
08-26 14:17:14.193  7161  7161 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:14.193  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 14:17:14.203  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:14.203  1016  1217 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7161 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:14.203  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 14:17:14.203  1016  1217 I ActivityManager: Killing 6631:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-26 14:17:14.203  1016  1077 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 14:17:14.203  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 14:17:14.203  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:14.203  1016  1077 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 14:17:14.203  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 14:17:14.233  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:14.233  7161  7161 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.243  1016  1465 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.263  1016  1503 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.273  7161  7161 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@bcae22c
,08-26 14:17:14.283  7140  7140 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-26 14:17:14.293  7161  7161 I SA      : [SSP] onCreated
08-26 14:17:14.293  7124  7176 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 14:17:14.303  7140  7140 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 14:17:14.303  7140  7140 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:14.303  7161  7161 I SA      : [TPM] There is no property file
,08-26 14:17:14.303  7140  7140 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 14:17:14.303  7140  7140 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 14:17:14.303  7140  7140 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 14:17:14.303  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 14:17:14.303  7161  7161 I SA      : [SCU] isHaveSA() - false
,08-26 14:17:14.313  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.313  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.313  7161  7161 I SA      : [TPM] getModelProperty : null
08-26 14:17:14.313  7161  7161 I SA      : [TPM] getCSCProperty : null
,08-26 14:17:14.313  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.313  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.313  7161  7161 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 14:17:14.313  7161  7161 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 14:17:14.313  7161  7161 I SA      : [DM] TFT FEATURE: false
,08-26 14:17:14.313  7161  7161 I SA      : [DM] init START
,08-26 14:17:14.323  7161  7161 I SA      : [DM] This device is not a Vodafone
,08-26 14:17:14.323  7184  7184 E Zygote  : MountEmulatedStorage()
,08-26 14:17:14.323  7184  7184 I libpersona: KNOX_SDCARD checking this for 10008
08-26 14:17:14.323  7184  7184 E Zygote  : v2
08-26 14:17:14.323  7184  7184 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:14.333  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:14.333  1016  1029 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7184 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:14.333  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:14.333  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 14:17:14.333  1016  2134 I ActivityManager: Killing 6055:com.android.mms/u0a41 (adj 15): empty #21
,08-26 14:17:14.353  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:14.353  7184  7184 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 14:17:14.363  7161  7161 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-26 14:17:14.363  1016  1465 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-26 14:17:14.363  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 14:17:14.363  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 14:17:14.363  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 14:17:14.363  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 14:17:14.363  7161  7161 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 14:17:14.373  7161  7161 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 14:17:14.383  7161  7161 I SA      : [SCU] isHaveSA() - false
,08-26 14:17:14.383  7161  7161 I SA      : support phone number id : false
08-26 14:17:14.383  7161  7161 I SA      : [DM] Supports Ref Jpn : true
08-26 14:17:14.383  7201  7201 E Zygote  : MountEmulatedStorage()
08-26 14:17:14.383  7201  7201 I libpersona: KNOX_SDCARD checking this for 10068
08-26 14:17:14.383  7201  7201 E Zygote  : v2
08-26 14:17:14.383  7201  7201 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:14.383  7161  7161 I SA      : [DM] init END
,08-26 14:17:14.383  7161  7161 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-26 14:17:14.383  7201  7201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:14.383  7201  7201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:14.383  1016  1465 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7201 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 14:17:14.383  7161  7161 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-26 14:17:14.383  7161  7161 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-26 14:17:14.383  7201  7201 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 14:17:14.383  1016  1028 D CountryDetector: No listener is left
,08-26 14:17:14.403  7161  7161 I SA      : [SLFUCHKMGR] constructor called
,08-26 14:17:14.403  1016  2140 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 14:17:14.413  1016  2140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 14:17:14.413  7201  7201 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:14.413  1016  2140 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:14.413  1016  2140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:14.413  1016  2140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-26 14:17:14.413  7201  7201 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.423  1016  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 14:17:14.423  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.423  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.423  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.423  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.423  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-26 14:17:14.423  1016  2134 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.433  7220  7220 E Zygote  : MountEmulatedStorage()
,08-26 14:17:14.433  7220  7220 E Zygote  : v2
08-26 14:17:14.433  7220  7220 I libpersona: KNOX_SDCARD checking this for 10110
08-26 14:17:14.433  7220  7220 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:14.433  7220  7220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:14.433  1016  1478 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7220 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:14.443  1016  1325 D RCPManagerService: exchangeData() failure , invalid userId,
,08-26 14:17:14.443  7220  7220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:14.443  7220  7220 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-26 14:17:14.443  7161  7161 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 14:17:14.443  7161  7161 I SA      : [OR] == isSIMCardReady false ==
,08-26 14:17:14.453  1016  2140 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 14:17:14.453  1016  2140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 14:17:14.453  1016  2140 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:14.453  1016  2140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:14.453  1016  2140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 14:17:14.463  7161  7161 I SA      : [SCU] == networkStateCheck == false
08-26 14:17:14.463  7161  7161 I SA      : [OR] onReceive END
,08-26 14:17:14.463  6984  7218 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 14:17:14.463  1016  1475 I ActivityManager: Killing 6655:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 14:17:14.463  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:14.473  7201  7201 D BadgeProvider: onCreate
08-26 14:17:14.473  7201  7201 D BadgeProvider: DatabaseHelper
,08-26 14:17:14.473  1016  1475 I ActivityManager: Killing 6672:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 14:17:14.483  7220  7220 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:14.483  7220  7220 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.493  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.493  1016  1475 I ActivityManager: Killing 6488:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 14:17:14.503  7201  7210 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 14:17:14.503  2878  2878 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 14:17:14 GMT+02:00 2016
08-26 14:17:14.503  1016  2134 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 14:17:14.503  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-26 14:17:14.503  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:14.503  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:14.503  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 14:17:14.513  2878  2878 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 14:17:14.513  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:14.513  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 14:17:14.513  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.513  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.513  2878  2878 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 14:17:14.513  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:14.513  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:14.523  2878  2878 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 14:17:14.523  7201  7210 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-26 14:17:14.523  7201  7210 D BadgeProvider: sendNotify, [notify] : null
08-26 14:17:14.523  7201  7210 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 14:17:14.523  7201  7210 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 14:17:14.523  7201  7210 D BadgeProvider: update, [UpdateCount] : 1
,08-26 14:17:14.523  2878  2878 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 14:17:14.523  2878  7235 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 14:17:14.533  1480  1480 D Launcher.Model: reloadBadges entered.
08-26 14:17:14.533  2878  7235 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-26 14:17:14.533  7236  7236 E Zygote  : MountEmulatedStorage()
08-26 14:17:14.533  7236  7236 E Zygote  : v2
08-26 14:17:14.533  7236  7236 I libpersona: KNOX_SDCARD checking this for 10009
08-26 14:17:14.533  7236  7236 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:14.533  7236  7236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:14.533  7236  7236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:14.533  1016  1029 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7236 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-26 14:17:14.533  7236  7236 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 14:17:14.543  1016  1029 I ActivityManager: Killing 5999:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 14:17:14.543  1016  1029 I ActivityManager: Killing 6687:com.google.android.gms:car/u0a11 (adj 15): empty #22
,08-26 14:17:14.553  2878  7235 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 14:17:14.563  7236  7236 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:14.563  2878  7235 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 14:17:14.563  7236  7236 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:14.573  2878  2878 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 14:17:14.613  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 14:17:14.613  1016  1503 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 14:17:14.613  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 14:17:14.613  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 14:17:14.663  1016  1465 I ActivityManager: Killing 5822:com.android.vending/u0a26 (adj 15): empty #21
,08-26 14:17:14.663  1016  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:14.673  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-26 14:17:14.673  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:14.673  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:14.673  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:14.683  4694  7253 I iu.SyncManager: SYNC; picasa accounts
,08-26 14:17:14.703  4694  4694 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 14:17:14.713  2001  2166 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-26 14:17:14.713  2001  2166 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-26 14:17:14.723  1016  1217 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 14:17:14.763  1016  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:14.763  1016  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:14.763  1016  1478 D SecContentProvider2: mCursor = null
,08-26 14:17:14.763  1016  1478 D WifiService: setWifiEnabled: true pid=6743, uid=10171
,08-26 14:17:14.773  1016  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:14.773  1016  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:14.773  1016  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:14.773  1016  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 14:17:14.773  1016  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:14.773  1016  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:14.773  1016  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:14.773  1016  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 14:17:14.773  1016  1478 D SettingsProvider: name = wifi_on
,08-26 14:17:14.773  1016  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 14:17:14.873  7220  7220 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 14:17:14.873  7220  7220 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 14:17:14.873  7220  7220 I GAv4    :   adb logcat -s GAv4
,08-26 14:17:14.873   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:14.873   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:14.873  7220  7258 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 14:17:14.873   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:14.873   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:14.883  7220  7258 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:14.893  7220  7220 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 14:17:14.893   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:14.893   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 14:17:14.893  1016  1325 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 14:17:14.893  7220  7260 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 14:17:14.893   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:14.893   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:14.903  7220  7260 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:14.903  7220  7220 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:17:14.913  7220  7261 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:17:15.133  1016  1043 D Tethering: interfaceAdded wlan0
,08-26 14:17:15.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:15.143  1016  1130 E Tethering: No numeric data
,08-26 14:17:15.143  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 14:17:15.143  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:15.143  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:15.143  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:15.143  1016  1130 D Tethering: clearTetheredNotification()
08-26 14:17:15.143  1016  1130 D Tethering: InitialState.processMessage what=4
,08-26 14:17:15.143  1016  1043 D Tethering: interfaceAdded p2p0
,08-26 14:17:15.143  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:15.143  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.153  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:15.153  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-26 14:17:15.153  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 14:17:15.153  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:15.153  1016  1130 E Tethering: No numeric data
,08-26 14:17:15.153  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 14:17:15.153  1016  1130 D Tethering: clearTetheredNotification()
08-26 14:17:15.153  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 14:17:15.153  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.153  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:15.153   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 14:17:15.163   278   983 D SoftapController: Softap fwReload - Ok
,08-26 14:17:15.163  1016  1124 V NetworkStats: performPollLocked() took 12ms,
08-26 14:17:15.163  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.163   278   983 D CommandListener: Setting iface cfg
,08-26 14:17:15.163   278   983 D CommandListener: Trying to bring down wlan0
08-26 14:17:15.163  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.163   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:15.163  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:15.163  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:15.163  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 14:17:15.163  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:15.163  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:15.163  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:15.163  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:15.163  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.173  1016  1127 E WifiHW  : supplicant_name : p2p_supplicant
08-26 14:17:15.173  1016  1124 V NetworkStats: performPollLocked() took 6ms
08-26 14:17:15.173  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.173  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.173  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:15.183  1016  1325 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:15.183  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:15.183  1016  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:15.183  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 14:17:15.203  7220  7220 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 14:17:15.233  7220  7220 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 6227-6241),
08-26 14:17:15.233  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 14:17:15.253  7220  7220 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {269aed97}
,08-26 14:17:15.253  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 14:17:15.253  7220  7220 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:17:15.273  7284  7284 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 14:17:15.273  7284  7284 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 14:17:15.273  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 14:17:15.273  7220  7220 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 14:17:15.273  7220  7220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:15.273  1016  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 14:17:15.283  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:15.283  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:15.283  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:15.283  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:15.283  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:15.283  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:15.283  1016  2134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 14:17:15.283  1016  2134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 14:17:15.283  1016  2134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:17:15.283  1016  2134 D BatteryService: stay LED for fully charged
08-26 14:17:15.283  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 14:17:15.293  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:15.293  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:15.293  7220  7220 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 14:17:15.293  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:15.293  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:15.293  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 14:17:15.293  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:15.293  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:15.293  1177  1177 D HotspotTile: onReceive : 2, 0,
08-26 14:17:15.293  1016  1016 I MotionRecognitionService: Plugged
,08-26 14:17:15.293  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 14:17:15.293  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:15.303  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:17:15.303  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:17:15.303  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 14:17:15.303  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 14:17:15.303   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7284
08-26 14:17:15.303   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 14:17:15.303  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 14:17:15.303  7284  7284 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:15.303  7284  7284 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 14:17:15.303  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 14:17:15.303   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7284
08-26 14:17:15.303   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 14:17:15.313  7220  7220 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:15.313  7220  7220 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:15.313  7220  7220 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:15.313  7220  7220 I Adreno-EGL: Local Branch: 
08-26 14:17:15.313  7220  7220 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:15.313  7220  7220 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:15.313  7220  7220 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:15.323  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:15.323  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:17:15.323  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:15.373  7220  7220 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,08-26 14:17:15.383  7220  7299 W cr.media: Requires BLUETOOTH permission
,08-26 14:17:15.383  7220  7220 I NSApplication: Starting up...
,08-26 14:17:15.383  1016  1465 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 14:17:15.393  1016  2134 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 14:17:15.393  1016  1325 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 14:17:15.393  1016  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:15.393  1016  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:15.393  1016  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:15.393  1016  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:15.413  7304  7304 E Zygote  : MountEmulatedStorage()
08-26 14:17:15.413  7304  7304 E Zygote  : v2
08-26 14:17:15.413  7304  7304 I libpersona: KNOX_SDCARD checking this for 10117
08-26 14:17:15.413  7304  7304 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:15.413  7304  7304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:15.413  7304  7304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:15.413  7304  7304 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 14:17:15.423  1016  1325 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7304 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:17:15.423  1016  1325 I ActivityManager: Killing 6929:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-26 14:17:15.433  7304  7304 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:15.433  7304  7304 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:15.453   304   304 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 34.971ms
,08-26 14:17:15.463  7304  7304 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:15.473   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 18.379ms
,08-26 14:17:15.493   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.531ms
,08-26 14:17:15.513   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 14:17:15.513  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-26 14:17:15.563  7284  7284 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 14:17:15.563  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 14:17:15.573  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 14:17:15.573   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
,08-26 14:17:15.573   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 14:17:15.573  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 14:17:15.573  7284  7284 I wpa_supplicant: ssSupport state is = 1,
08-26 14:17:15.573  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 14:17:15.573  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:15.573  7284  7284 E wpa_supplicant: SIM READ ERROR,
08-26 14:17:15.573  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:15.573  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 14:17:15.573  7284  7284 E wpa_supplicant: SIM READ ERROR
08-26 14:17:15.573  7284  7284 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 14:17:15.573  7284  7284 I wpa_supplicant: wpa_default_ap_write_once,
08-26 14:17:15.573  7284  7284 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:15.573  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 14:17:15.583  7284  7284 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-26 14:17:15.583  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:15.583  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-26 14:17:15.583  7284  7284 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 14:17:15.583  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:15.583  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:15.583  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:15.703  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 14:17:15.823  1016  1475 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 14:17:15.823  1016  1475 I ActivityManager: Killing 6952:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-26 14:17:15.833  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:15.833  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:15.833  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:15.833  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:15.833  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:15.833  1619  1619 I Hs20UtilService: Starting #12
,08-26 14:17:15.833  1619  1678 I Hs20UtilService: Message received 5011
,08-26 14:17:15.843  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:15.843  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 14:17:15.843  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:15.843  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:15.893  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-26 14:17:15.893  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 14:17:15.903  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-26 14:17:15.913   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
08-26 14:17:15.913   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 14:17:15.913  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 14:17:15.913  7284  7284 I wpa_supplicant: ssSupport state is = 1
,08-26 14:17:15.913  7284  7284 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 14:17:15.913  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 14:17:15.923  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 14:17:15.923   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
08-26 14:17:15.923   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 14:17:15.923  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 14:17:15.923  7284  7284 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:15.923  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 14:17:15.923  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:15.923  7284  7284 E wpa_supplicant: SIM READ ERROR
08-26 14:17:15.923  7284  7284 I wpa_supplicant: wpa_default_ap_write_once
08-26 14:17:15.923  7284  7284 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-26 14:17:15.923  7284  7284 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 14:17:15.923  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.923  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.923  1016  1043 D Tethering: interfaceStatusChanged p2p0, false,
08-26 14:17:15.933  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.933  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:15.933  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:15.983  7284  7284 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 14:17:15.983  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 14:17:16.093  7284  7284 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 14:17:16.093  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 14:17:16.093  7284  7284 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:16.103  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-26 14:17:16.103  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:16.103  7284  7284 I wpa_supplicant: HOTSPOT20_ENABLE called,
,08-26 14:17:16.113  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 14:17:16.113  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 14:17:16.113  7284  7284 E wpa_supplicant: SIM READ ERROR
08-26 14:17:16.113  7284  7284 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 14:17:16.133  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 14:17:16.133  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-26 14:17:16.133  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:16.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:16.153  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 14:17:16.163  7284  7284 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:16.163  1016  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 14:17:16.163  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:16.163  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:16.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:16.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 14:17:16.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:16.173  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:16.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:16.173  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:16.173  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:16.173  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 14:17:16.173  1177  1177 D HotspotTile: onReceive : 3, 0
,08-26 14:17:16.173  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-26 14:17:16.173  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:16.183  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:16.183  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:16.183  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:16.183  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:16.183  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:16.183  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:16.183  1016  1127 E WifiConfigStore: Not a HS20
08-26 14:17:16.183  1016  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 14:17:16.183  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 14:17:16.193  1016  1325 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:16.193  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:16.193  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:16.193  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:16.193  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:16.193  1619  1619 I Hs20UtilService: Starting #13
,08-26 14:17:16.193  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:16.193  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 14:17:16.203  7284  7284 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 14:17:16.203  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 14:17:16.203  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 14:17:16.203  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:16.203  7284  7284 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 14:17:16.203  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:16.203  1619  1678 I Hs20UtilService: Message received 5011
08-26 14:17:16.203  7284  7284 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:16.203  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 14:17:16.203  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 14:17:16.203  7284  7284 I wpa_supplicant: First Scan Start
,08-26 14:17:16.203  1016  1127 D WifiNative-wlan0: Setting external_sim to 1
08-26 14:17:16.203  7284  7284 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 14:17:16.203  1016  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:16.203  1016  1127 I WifiNative-HAL: startHal
08-26 14:17:16.203  1016  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5e488c,
08-26 14:17:16.203  1016  1127 I WifiNative-HAL: Could not start hal
,08-26 14:17:16.203  6984  6984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:16.203  1016  1127 E WifiNative-wlan0: do suspend true
,08-26 14:17:16.203  1016  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 14:17:16.203   278   983 D CommandListener: Setting iface cfg
08-26 14:17:16.203   278   983 D CommandListener: Trying to bring up p2p0
08-26 14:17:16.213  1016  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 14:17:16.213  1016  1126 D WifiP2pService: P2pEnablingState
08-26 14:17:16.213  1016  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-26 14:17:16.213  1016  1126 D WifiP2pService: P2p socket connection successful
08-26 14:17:16.213  1016  1126 D WifiP2pService: P2pEnabledState
,08-26 14:17:16.213  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 14:17:16.213  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 14:17:16.213  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:16.213  1016  1149 I WifiNative-HAL: startHal
08-26 14:17:16.213  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9eba09bc
08-26 14:17:16.213  1016  1149 I WifiNative-HAL: Could not start hal
08-26 14:17:16.213  1016  1149 E WifiScanningService: could not start HAL
08-26 14:17:16.213  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-26 14:17:16.213  1016  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:16.213  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:16.213  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:16.213  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:16.213  1016  1127 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:16.213  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 14:17:16.213  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:16.213  7284  7284 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:16.223  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 14:17:16.223  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:16.223  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:16.223  1016  1046 D WifiDisplayController: disconnect
08-26 14:17:16.223  1016  1046 D WifiDisplayController: updateConnection
08-26 14:17:16.223  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:16.223  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:16.223  7284  7284 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 14:17:16.223  1016  1127 E WifiStateMachine: Failed to set frequency band 0
,08-26 14:17:16.223  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:16.223  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:16.223  1016  1127 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:16.223  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:16.223  1016  1127 D SecContentProvider2: mCursor = null
08-26 14:17:16.223  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 14:17:16.223  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 14:17:16.223  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:16.223  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:16.223  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:16.223  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:16.223  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-26 14:17:16.223  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:16.233  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 14:17:16.233  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:16.233  1016  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:16.233  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 14:17:16.233  1016  1126 D WifiP2pService: DeviceAddress: 0a:76:28
08-26 14:17:16.233  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  secondary type: null
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  wps: 0
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  grpcapab: 0
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  devcapab: 0
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  status: 3
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  wfdInfo: null
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-26 14:17:16.233  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-26 14:17:16.233  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:16.233  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:16.233  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:16.233  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:16.233  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:16.233  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:16.233  1016  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 14:17:16.233  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.233  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:16.233  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:16.233  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.243  7335  7335 E Zygote  : MountEmulatedStorage()
,08-26 14:17:16.253  7335  7335 E Zygote  : v2
08-26 14:17:16.253  7335  7335 I libpersona: KNOX_SDCARD checking this for 10064
,08-26 14:17:16.253  7335  7335 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:16.253  1016  1126 D WifiP2pService: sending p2p persistent groups changed broadcast,
,08-26 14:17:16.253  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:16.253  1016  1478 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7335 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 14:17:16.253  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:16.253  1016  1126 D WifiP2pService: InactiveState
08-26 14:17:16.253  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:16.253  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:16.253  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:16.253  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:16.263  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:16.263  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:16.273  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:16.273  7335  7335 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:16.293  7335  7335 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 14:17:16.303  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:16.303  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 14:17:16.333  7335  7335 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:16.333  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 14:17:16.333  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.333  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:16.333  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:16.333  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.343  7350  7350 E Zygote  : MountEmulatedStorage()
,08-26 14:17:16.343  1016  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7350 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:16.343  7350  7350 E Zygote  : v2
08-26 14:17:16.343  7350  7350 I libpersona: KNOX_SDCARD checking this for 10065
08-26 14:17:16.343  7350  7350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:16.343  7350  7350 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:16.343  1016  1029 I ActivityManager: Killing 6871:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-26 14:17:16.353  7350  7350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:16.353  7350  7350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:16.363  7350  7350 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:16.363  7350  7350 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:16.383  7350  7350 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:16.393  1016  1325 I ActivityManager: Killing 7011:com.android.bluetooth/1002 (adj 15): empty #21
,08-26 14:17:16.943  1016  1503 I ActivityManager: Killing 6886:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 14:17:17.133   288   288 E SMD     : DCD OFF,
,08-26 14:17:17.133   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:17.473  7284  7284 I wpa_supplicant: nl80211: Received scan results (33 BSSes)
08-26 14:17:17.473  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-26 14:17:17.473  7284  7284 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-26 14:17:17.483  1016  7330 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-26 14:17:17.483  7284  7284 I wpa_supplicant: Trying to associate with  'G700'
,08-26 14:17:17.483  7284  7284 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-26 14:17:17.483  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-26 14:17:17.503  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:17.503  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:17.593  7284  7284 E wpa_supplicant: Cmd 35605 not handled
,08-26 14:17:17.593  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:17.593  7284  7284 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-26 14:17:17.593  7284  7284 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 14:17:17.593  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-26 14:17:17.593  7284  7284 I wpa_supplicant: Associated with F4.99.3E,
08-26 14:17:17.593  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:17.603  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.593  7284  7284 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-26 14:17:17.593  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.593  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:17.603  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.593  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:17.603  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.603  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:17.603  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.603  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:17.603  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:17.603  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 14:17:17.603  1016  1043 D Tethering: interfaceStatusChanged wlan0, true,
08-26 14:17:17.603  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:17.603  7284  7284 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 14:17:17.603  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-26 14:17:17.603  1016  1127 D SecContentProvider2: mCursor = null
08-26 14:17:17.613  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 14:17:17.613  7284  7284 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 14:17:17.613  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:17.613  7284  7284 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 14:17:17.613  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-26 14:17:17.613  7284  7284 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 14:17:17.613  7284  7284 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 14:17:17.613  7284  7284 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 14:17:17.613  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 14:17:17.613  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-26 14:17:17.623  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:17.613  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 14:17:17.613  1016  1130 E Tethering: No numeric data
08-26 14:17:17.613  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-26 14:17:17.613  1016  1127 D SecContentProvider2: mCursor = null
08-26 14:17:17.623  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:17.613  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:17.623  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 14:17:17.613  1016  1130 D Tethering: clearTetheredNotification()
,08-26 14:17:17.623  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.623  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:17.623  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:17.623  1016  1124 V NetworkStats: performPollLocked() took 4ms
08-26 14:17:17.623  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.623  1016  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 14:17:17.623  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.623  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:17.623  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 14:17:17.633  1016  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 14:17:17.633  1016  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 14:17:17.633  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:17.633  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 14:17:17.633  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:17.633  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:17.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.633  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:17.633  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:17.633  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:17.643  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:17.643  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:17.643  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:17.643  1619  1619 I Hs20UtilService: Starting #14
,08-26 14:17:17.643  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:17.643  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:17.643  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:17.643  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:17.643  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:17.643  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 14:17:17.643  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:17.643  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:17.653  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:17.663   278   983 D CommandListener: Setting iface cfg
,08-26 14:17:17.663  1016  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 14:17:17.673  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:17.673  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:17.673  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:17.683  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 14:17:17.683  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.683  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.683  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.683  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.683  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:17.683  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:17.693  1016  1127 E WifiNative-wlan0: do suspend false
,08-26 14:17:17.693  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 14:17:17.693  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 14:17:17.773  1016  2140 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:17.773  1016  2140 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:17.773  1016  2140 D SecContentProvider2: mCursor = null
,08-26 14:17:17.783  1016  2140 D WifiService: setWifiEnabled: false pid=6743, uid=10171
,08-26 14:17:17.783  1016  2140 D SettingsProvider: name = wifi_on
,08-26 14:17:17.793  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:17.803  1016  1127 E WifiNative-wlan0: do suspend true,
,08-26 14:17:17.823  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 14:17:17.823  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 14:17:17.833   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:17.833  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:17.833  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:17.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.843  1016  1129 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:17.843  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 14:17:17.843  1016  1129 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:17.843  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
,08-26 14:17:17.843  1016  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 14:17:17.843  1016  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-26 14:17:17.843  1016  1126 D WifiP2pService: P2pEnabledState{ what=131204 },
08-26 14:17:17.853  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 14:17:17.853   278   983 E Netd    : no such netId 503
08-26 14:17:17.853  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 14:17:17.863  1016  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 14:17:17.863  1016  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 14:17:17.863  1016  1129 V NetworkStats: updateIfacesLocked()
08-26 14:17:17.863  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.863  1016  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:17.863  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:17.863  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:17.873  1016  1129 V NetworkStats: performPollLocked() took 10ms
08-26 14:17:17.873  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:17.873  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 14:17:17.873  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:17.873  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:17.873  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 14:17:17.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.873  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.873  1016  1016 D RttService: SCAN_AVAILABLE : 1
,08-26 14:17:17.873  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:17.883  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 14:17:17.883  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:17.883  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:17.883  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:17.883  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:17.883  1016  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-26 14:17:17.883  1016  1126 D WifiP2pService: P2pDisablingState
08-26 14:17:17.883  1016  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:17.883  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:17.883  1016  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-26 14:17:17.883  1016  1126 D WifiP2pService: p2p socket connection lost
08-26 14:17:17.883  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.883  1016  1126 D WifiP2pService: P2pDisabledState
,08-26 14:17:17.883  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:17.883  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:17.883  1016  7366 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:17.883  1016  7366 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-26 14:17:17.883  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.883  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:17.883  1619  1619 I Hs20UtilService: Starting #15
,08-26 14:17:17.893  1016  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 14:17:17.893  1016  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 14:17:17.893  1016  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 14:17:17.893  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:17.893  1016  1129 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:17.893  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 14:17:17.893  1016  1127 E WifiNative-wlan0: do suspend true
,08-26 14:17:17.893  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:17.893  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 14:17:17.893  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 14:17:17.893  1016  1046 D WifiDisplayController: disconnect
08-26 14:17:17.893  1016  1046 D WifiDisplayController: updateConnection
08-26 14:17:17.893  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 14:17:17.893  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:17.903  7369  7369 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 14:17:17.903  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 14:17:17.903  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:17.903  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:17.903  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:17.903  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:17.913  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 14:17:17.913  1016  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:17.913  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:17.913  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 14:17:17.913  7369  7369 I dhcpcd  : version 5.5.6 starting
08-26 14:17:17.913  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:17.913  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:17.913  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:17.913  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:17.913  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:17.923  7369  7369 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 14:17:17.923  1016  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 14:17:17.923  1016  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-26 14:17:17.923   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:17.923  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:17.923  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:17.933  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:17.933  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:17.933  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:17.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.933  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.933  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:17.933  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:17.933  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:17.933  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:17.933  7284  7284 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:17.933  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:17.943  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:17.943  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:17.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.943  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:17.943  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 14:17:17.943  7335  7335 D FileShare-Client: Outbound.stopDelayTimer - 
08-26 14:17:17.943  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:17.943  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:17.953  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:17.953  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:17.953  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:17.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.953  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:17.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.953  1177  1177 D HotspotTile: onReceive : 0, 0
08-26 14:17:17.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:17.953  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:17.953  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:17.953  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 14:17:17.953  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:17.953  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:17.953  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:17.953  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:17.953  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:17.963  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:17.963  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:17.963  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:17.963  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:17.963  7350  7350 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:17.963  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 14:17:17.963  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:17.963  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:17.963  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:17.963  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:17.973  1619  1619 I Hs20UtilService: Starting #16
,08-26 14:17:17.973  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:17.973  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-26 14:17:17.973  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:17.973  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:17.983  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:17.983  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:17.983  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:17.983  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:17.983  7369  7369 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 14:17:17.983  7369  7369 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 14:17:17.983  7369  7369 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-26 14:17:17.983  7369  7369 I dhcpcd  : bssid match
,08-26 14:17:17.983  1016  1503 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:17.983  7369  7369 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-26 14:17:17.983  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:17.983  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:17.983  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:17.983  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:17.983  1619  1619 I Hs20UtilService: Starting #17
,08-26 14:17:17.993  1619  1678 I Hs20UtilService: Message received 5011,
,08-26 14:17:17.993  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:17.993  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:17.993  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:17.993  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:18.103  7284  7284 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:18.113  7369  7369 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-26 14:17:18.143   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 14:17:18.173  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-26 14:17:18.173  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:18.173  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:18.173  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:18.203  7284  7284 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-26 14:17:18.203  7284  7284 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-26 14:17:18.203  7284  7284 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 14:17:18.203  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-26 14:17:18.203  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 14:17:18.203  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 14:17:18.203  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:18.203  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.203  1016  1130 D Tethering: InitialState.processMessage what=4
08-26 14:17:18.203  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 14:17:18.203  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:18.203  1016  1130 E Tethering: No numeric data
08-26 14:17:18.203  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:18.203  1016  1130 D Tethering: clearTetheredNotification()
08-26 14:17:18.203  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.203  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:18.203  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:18.203  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:18.213  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:18.213  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.213  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-26 14:17:18.213  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:18.213  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 14:17:18.213  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:18.213  1016  1124 V NetworkStats: performPollLocked() took 8ms
,08-26 14:17:18.213  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:18.213  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:18.213  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:18.263  7369  7369 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-26 14:17:18.443  7284  7284 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:18.583  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.583  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.583  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:18.583  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:18.583  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:18.583  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:18.583  7284  7284 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 14:17:18.623  1016  1029 I ActivityManager: Killing 7028:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 14:17:18.693  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 14:17:18.693  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:18.693  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:18.693  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 14:17:18.703  6984  6984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:18.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:18.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:18.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:18.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:18.703  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 14:17:18.703  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:18.703  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 14:17:18.703  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:18.703  2001  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:18.703  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 14:17:18.713  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:18.713  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:18.713  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:18.713  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:18.713  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:18.713  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:18.713  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 14:17:18.713  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-26 14:17:18.713  1619  1619 I Hs20UtilService: Starting #18
08-26 14:17:18.713  1619  1678 I Hs20UtilService: Message received 5011
,08-26 14:17:18.723  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:18.723  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:18.723  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:18.723  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:19.423   278   977 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-26 14:17:19.423  1016  1043 D Tethering: interfaceRemoved wlan0
,08-26 14:17:19.423  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 14:17:19.703  1016  1043 D Tethering: interfaceRemoved p2p0
,08-26 14:17:19.703  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 14:17:20.143   288   288 E SMD     : DCD OFF,
,08-26 14:17:20.533  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 14:17:20.793  6743  6799 D BluetoothAdapter: enable()
,08-26 14:17:20.793  1016  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 14:17:20.793  1016  1478 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 14:17:20.793  1016  1478 W BluetoothManagerService: 	,at android.os.Binder.execTransact(Binder.java:446)
08-26 14:17:20.793  1016  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:20.793  1016  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:20.793  1016  1478 D SettingsProvider: name = bluetooth_on,
,08-26 14:17:20.803  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-26 14:17:20.803  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:20.803  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 14:17:20.803  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 14:17:20.803  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:20.803  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:20.803  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:20.803  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:20.813  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7399 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 14:17:20.813  7399  7399 E Zygote  : MountEmulatedStorage()
,08-26 14:17:20.813  7399  7399 E Zygote  : v2
08-26 14:17:20.813  7399  7399 I libpersona: KNOX_SDCARD checking this for 1002
08-26 14:17:20.813  7399  7399 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:20.823  7399  7399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:20.823  7399  7399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:20.823  7399  7399 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:20.853  7399  7399 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:20.853  7399  7399 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:20.873  7399  7399 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 14:17:20.873  7399  7399 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:20.903  7399  7399 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding GattService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding HidService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding HealthService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding PanService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding SapService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding SapClientService
08-26 14:17:20.943  7399  7399 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 14:17:20.943  7399  7399 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 14:17:20.953  1016  1325 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 14:17:20.953  1016  1325 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.953  1016  1325 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.953  1016  1325 D SettingsProvider: selectionArgs: false
08-26 14:17:20.953  1016  1325 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.953  1016  1325 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.953  1016  1325 D SettingsProvider: ret = -1
,08-26 14:17:20.953  1016  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 14:17:20.953  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.953  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.953  1016  1217 D SettingsProvider: selectionArgs: false
08-26 14:17:20.953  1016  1217 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:20.953  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.953  1016  1217 D SettingsProvider: ret = -1
,08-26 14:17:20.953  1016  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:20.953  1016  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.953  1016  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.953  1016  1465 D SettingsProvider: selectionArgs: false
,08-26 14:17:20.953  1016  1465 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.953  1016  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:20.953  1016  1465 D SettingsProvider: ret = -1
,08-26 14:17:20.953  1016  1503 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-26 14:17:20.953  1016  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.953  1016  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:20.953  1016  1503 D SettingsProvider: selectionArgs: false
08-26 14:17:20.963  1016  1503 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:20.963  1016  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.963  1016  1503 D SettingsProvider: ret = -1
,08-26 14:17:20.963  1016  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-26 14:17:20.963  1016  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.963  1016  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.963  1016  1479 D SettingsProvider: selectionArgs: false
,08-26 14:17:20.963  1016  1479 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.963  1016  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:20.963  1016  1479 D SettingsProvider: ret = -1
,08-26 14:17:20.963  1016  1077 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-26 14:17:20.963  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.963  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.963  1016  1077 D SettingsProvider: selectionArgs: false
,08-26 14:17:20.963  1016  1077 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.963  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:20.963  1016  1077 D SettingsProvider: ret = -1
,08-26 14:17:20.963  1016  2134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:20.963  1016  2134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.963  1016  2134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.963  1016  2134 D SettingsProvider: selectionArgs: false
,08-26 14:17:20.963  1016  2134 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.963  1016  2134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:20.973  1016  2134 D SettingsProvider: ret = -1
,08-26 14:17:20.973  1016  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-26 14:17:20.973  1016  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.973  1016  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.973  1016  1476 D SettingsProvider: selectionArgs: false
08-26 14:17:20.973  1016  1476 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:20.973  1016  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.973  1016  1476 D SettingsProvider: ret = -1
,08-26 14:17:20.973  1016  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:20.973  1016  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.973  1016  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.973  1016  1475 D SettingsProvider: selectionArgs: false
08-26 14:17:20.973  1016  1475 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:20.973  1016  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.973  1016  1475 D SettingsProvider: ret = -1,
08-26 14:17:20.973  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:20.973  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.973  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.973  1016  1478 D SettingsProvider: selectionArgs: false
08-26 14:17:20.973  1016  1478 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.973  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.973  1016  1478 D SettingsProvider: ret = -1
08-26 14:17:20.973  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:20.973  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.973  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.973  1016  1028 D SettingsProvider: selectionArgs: false
08-26 14:17:20.973  1016  1028 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.973  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.973  1016  1028 D SettingsProvider: ret = -1
08-26 14:17:20.973  1016  2140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-26 14:17:20.973  1016  2140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:20.973  1016  2140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:20.973  1016  2140 D SettingsProvider: selectionArgs: false
08-26 14:17:20.973  1016  2140 D SettingsProvider: selectionArgs: 1002
08-26 14:17:20.973  1016  2140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:20.973  1016  2140 D SettingsProvider: ret = -1
,08-26 14:17:20.993  7399  7399 D BluetoothAdapterState: make
,08-26 14:17:20.993  7399  7399 I bluedroid: init
,08-26 14:17:20.993  7399  7414 I BluetoothAdapterState: Entering OffState
,08-26 14:17:21.003  7399  7399 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-26 14:17:21.003  7399  7399 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 14:17:21.003  7399  7399 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:21.003  7399  7399 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 14:17:21.003  7399  7399 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 14:17:21.003  7399  7399 I bluedroid: get_profile_interface socket
08-26 14:17:21.003  7399  7399 I bluedroid: get_profile_interface map_client
,08-26 14:17:21.003  7399  7399 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-26 14:17:21.003  7399  7417 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 14:17:21.003  7399  7417 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 14:17:21.013  7399  7399 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-26 14:17:21.013  7399  7417 E BluetoothServiceJni: populateRssiValuesNative
08-26 14:17:21.013  1016  1475 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:21.013  7399  7417 I bluedroid: getModelRssiValues
08-26 14:17:21.013  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.013  7399  7417 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:21.013  7399  7417 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-26 14:17:21.013  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.013  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.013  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.013  1016  1016 D SettingsProvider: name = bluetooth_name
,08-26 14:17:21.013  7399  7407 I bluedroid: config_hci_snoop_log
,08-26 14:17:21.013  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-26 14:17:21.023  7399  7417 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 14:17:21.023  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-26 14:17:21.023  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 14:17:21.023  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 14:17:21.023  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:21.023  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:21.023  7399  7399 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 14:17:21.023  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:21.043  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 14:17:21.043  7399  7414 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 14:17:21.043  7399  7414 D BluetoothAdapterProperties: Setting state to 11
,08-26 14:17:21.053  7399  7414 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:21.053  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 14:17:21.053  7399  7414 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 14:17:21.053  7399  7414 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 14:17:21.053  7399  7414 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:21.053  7399  7414 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 14:17:21.053  7399  7414 D BluetoothSecureManager: getInstant: null
,08-26 14:17:21.053  7399  7414 D BluetoothSecureManager: calling getMethod for getService
,08-26 14:17:21.053  7399  7414 D BluetoothSecureManager: calling getService
,08-26 14:17:21.053  7399  7414 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3a612e5c
,08-26 14:17:21.063  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.063  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-26 14:17:21.063  1016  1077 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 14:17:21.063  1016  1077 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 14:17:21.063  7399  7414 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 14:17:21.063  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 14:17:21.073  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 14:17:21.073  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 14:17:21.073  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:21.073  7399  7414 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:21.073  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:21.083  7399  7414 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 14:17:21.083  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:21.083  1882  1882 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:21.083  1016  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:21.093  1016  2134 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:21.093  1016  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:21.093  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.093  7399  7414 D BluetoothBondStateMachine: make
,08-26 14:17:21.093  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:21.093  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:21.093  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.093  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 14:17:21.093  1016  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:21.093  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:17:21.093  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.093  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.103  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:21.103  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:21.103  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:21.103  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 14:17:21.103  7399  7419 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 14:17:21.103  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.103  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 14:17:21.113  1016  2140 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 14:17:21.113  1016  2140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:21.113  1016  2140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.113  1016  2140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.113  1016  2140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:21.123  7422  7422 E Zygote  : MountEmulatedStorage(),
08-26 14:17:21.123  1016  2140 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7422 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 14:17:21.123  7422  7422 E Zygote  : v2
08-26 14:17:21.123  7422  7422 I libpersona: KNOX_SDCARD checking this for 10055
08-26 14:17:21.123  7422  7422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:21.123  7422  7422 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:21.123  1016  2134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.123  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 14:17:21.123  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.123  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.133  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.133  7399  7399 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:21.133  7399  7399 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:21.133  7399  7399 D BtGatt.GattService: start()
08-26 14:17:21.133  7399  7399 D BtGatt.GattService: start()
08-26 14:17:21.133  7399  7399 I bluedroid: get_profile_interface gatt
08-26 14:17:21.133  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:21.133  7399  7399 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:21.133  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:21.133  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:21.133  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:21.133  1016  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.133  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 14:17:21.133  7422  7422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:21.133  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.133  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.133  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:21.133  7422  7422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:21.133  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 14:17:21.133  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:21.133  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 14:17:21.143  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.143  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.143  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.143  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.143  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.143  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:21.143  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:21.143  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:21.143  1016  2140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.143  1016  2140 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.143  1016  2140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 14:17:21.143  1016  2140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.143  1016  2140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.143  7399  7399 D BtGatt.GattService: mStartError = false
08-26 14:17:21.143  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.143  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 14:17:21.143  1016  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.143  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:21.143  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 14:17:21.143  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 14:17:21.143  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.143  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.143  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:21.143  7399  7399 D HeadsetService: Received start request. Starting profile...
,08-26 14:17:21.143  7399  7399 D HeadsetService: start()
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:21.153  1016  2134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:21.153  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:21.153  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.153  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.153  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.153  7399  7399 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:21.153  7399  7399 D HeadsetStateMachine: make
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:21.153  1016  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:21.153  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:21.153  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.153  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.153  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 14:17:21.153  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:21.153  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.153  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.153  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.153  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:21.153  7399  7399 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:21.153  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:21.153  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 14:17:21.163  7399  7414 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 14:17:21.163  1016  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 14:17:21.163  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.163  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.163  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.163  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:21.163  1016  1217 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 14:17:21.163  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.173  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.173  1016  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.173  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:21.173  7399  7399 I bluedroid: get_profile_interface handsfree
,08-26 14:17:21.173  7422  7422 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:21.173  7422  7422 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:21.193  7399  7399 I DualScoManager: Instantiating Dual Sco Manager
08-26 14:17:21.193  7399  7399 I DualScoManager: Set HeadsetServiceHelper
,08-26 14:17:21.193  7399  7399 D BluetoothAtMessage: createCMTIContentObservers
08-26 14:17:21.193  1016  2140 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 14:17:21.193  1016  2140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:21.193  1016  2140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:21.193  1016  2140 D SettingsProvider: selectionArgs: false
08-26 14:17:21.193  1016  2140 D SettingsProvider: selectionArgs: 1002
08-26 14:17:21.193  1016  2140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:21.193  1016  2140 D SettingsProvider: ret = -1
,08-26 14:17:21.193  7399  7435 D HeadsetStateMachine: Enter Disconnected: -2
08-26 14:17:21.193  7399  7399 D HeadsetService: mStartError = false
08-26 14:17:21.193  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.193  7399  7435 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 14:17:21.193  7399  7435 D HeadsetStateMachine: map size, before remove : 0
08-26 14:17:21.193  7399  7435 D HeadsetStateMachine: map size, after remove: 0
08-26 14:17:21.203  7399  7399 D A2dpService: Received start request. Starting profile...
08-26 14:17:21.203  7399  7399 D A2dpService: start()
,08-26 14:17:21.203  7399  7399 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 14:17:21.203  7399  7399 I bluedroid: get_profile_interface avrcp
,08-26 14:17:21.213  7422  7422 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 14:17:21.213  7399  7399 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:21.213  7399  7399 D Avrcp   : Initialize Media Controller
08-26 14:17:21.213  7399  7399 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 14:17:21.213  7399  7399 E Avrcp   : getActiveSessions
,08-26 14:17:21.213  7399  7399 D Avrcp   : pick active media Controller
08-26 14:17:21.213  7399  7399 D Avrcp   : Get the active Media Controller 
,08-26 14:17:21.223  7399  7399 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 14:17:21.223  7399  7443 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 14:17:21.233  7399  7399 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:21.233  7399  7399 D A2dpStateMachine: make
,08-26 14:17:21.233  7399  7399 I bluedroid: get_profile_interface a2dp
08-26 14:17:21.233  7399  7445 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:21.233  7399  7399 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 14:17:21.233  7399  7399 D A2dpService: mStartError = false
08-26 14:17:21.233  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:21.233  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 14:17:21.233  7399  7399 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 14:17:21.233  7399  7444 D A2dpStateMachine: Enter Disconnected: -2
,08-26 14:17:21.233  7399  7399 D HidService: Received start request. Starting profile...
08-26 14:17:21.233  7399  7399 D HidService: start()
08-26 14:17:21.233  7399  7399 I bluedroid: get_profile_interface hidhost
08-26 14:17:21.233  7399  7399 D HidService: setHidService(): set to: null
08-26 14:17:21.233  7399  7399 D HidService: mStartError = false
08-26 14:17:21.233  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.243  7399  7399 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:21.243  7399  7399 D HealthService: Received start request. Starting profile...
08-26 14:17:21.243  7399  7399 D HealthService: start()
,08-26 14:17:21.243  7399  7443 D BluetoothMediaBrowser: no now playing list
08-26 14:17:21.243  7422  7422 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 14:17:21.243  7399  7443 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 14:17:21.243  7422  7422 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 14:17:21.243  7422  7422 D UserAnalysis: Create SecureDbHelper
,08-26 14:17:21.243  7399  7399 I bluedroid: get_profile_interface health
08-26 14:17:21.243  7399  7399 D HealthService: mStartError = false
08-26 14:17:21.243  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:21.243  7399  7399 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 14:17:21.243  7399  7399 D PanService: Received start request. Starting profile...
08-26 14:17:21.243  7399  7399 D PanService: start()
08-26 14:17:21.243  7399  7399 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:21.243  7399  7399 I bluedroid: get_profile_interface pan
08-26 14:17:21.243  7399  7399 D PanService: mStartError = false
08-26 14:17:21.243  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.253  7399  7399 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:21.253  7399  7399 D BluetoothMapService: start()
,08-26 14:17:21.253  7422  7422 D IntelligenceServiceApplication: onCreate()
,08-26 14:17:21.253  7399  7399 D BluetoothMapService: mStartError = false
08-26 14:17:21.253  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.253  7399  7399 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 14:17:21.253  1016  1325 I ActivityManager: Killing 7058:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 14:17:21.253  7399  7399 D SapService: Received start request. Starting profile...
08-26 14:17:21.253  7399  7399 D SapService: start()
08-26 14:17:21.253  7399  7399 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 14:17:21.253  7399  7399 I bluedroid: get_profile_interface sap
08-26 14:17:21.253  7399  7399 D SapService: mStartError = false
08-26 14:17:21.253  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:21.253  7399  7399 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 14:17:21.263  1423  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 14:17:21.263  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 14:17:21.263  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:21.263  1423  1446 I Telecom : BluetoothPhoneService: Result of Message : true
08-26 14:17:21.263  7422  7422 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 14:17:21.263  7399  7399 D HeadsetStateMachine: Proxy object connected
08-26 14:17:21.263  7399  7399 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 14:17:21.263  7399  7399 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 14:17:21.263  7399  7399 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 14:17:21.263  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 14:17:21.263  7399  7399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:17:21.263  7399  7399 D BluetoothA2dp: Proxy object connected
08-26 14:17:21.263  7399  7399 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 14:17:21.263  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 14:17:21.263  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 14:17:21.263  7399  7435 D HeadsetStateMachine: Disconnected process message: 11
08-26 14:17:21.263  7399  7435 D HeadsetStateMachine: Disconnected process message: 18
08-26 14:17:21.263  7399  7435 D HeadsetStateMachine: Disconnected process message: 10
08-26 14:17:21.263  7399  7435 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:21.263  7399  7435 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:21.263  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 14:17:21.263  7422  7422 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 14:17:21.263  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 14:17:21.263  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 14:17:21.283  7422  7422 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 14:17:21.293  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 14:17:21.293  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 14:17:21.303  7399  7414 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 14:17:21.303  7399  7414 I bluedroid: enable
,08-26 14:17:21.303  7399  7414 I bt_hci_bdroid: init
,08-26 14:17:21.303  7399  7451 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 14:17:21.303  1016  1077 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 14:17:21.303  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:21.303  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.303  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.303  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:21.323  7453  7453 E Zygote  : MountEmulatedStorage()
08-26 14:17:21.323  7453  7453 I libpersona: KNOX_SDCARD checking this for 10105
08-26 14:17:21.323  7453  7453 E Zygote  : v2
08-26 14:17:21.323  7453  7453 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:21.323  7399  7414 I bt_vendor: bt-vendor : init
08-26 14:17:21.323  7399  7414 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:21.323  7399  7414 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 14:17:21.323  7399  7414 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 14:17:21.323  7399  7414 D bt_userial_mct: userial_init
,08-26 14:17:21.323  7399  7414 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:21.323  7399  7414 I bt_vendor: Starting hciattach daemon
08-26 14:17:21.323  7399  7414 I bt_vendor: try to set false
08-26 14:17:21.323  1016  1077 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7453 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 14:17:21.323  7453  7453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:21.323  7399  7414 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 14:17:21.323  7399  7414 I bt_vendor: Starting hciattach daemon
08-26 14:17:21.323  7399  7414 I bt_vendor: try to set true
08-26 14:17:21.323  7453  7453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:21.323  7453  7453 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 14:17:21.343  7464  7464 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 14:17:21.363  7453  7453 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 14:17:21.363  7453  7453 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:21.393  7476  7476 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 14:17:21.403  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:21.423  7479  7479 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:21.433  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 14:17:21.443  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:21.453  7482  7482 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 14:17:21.493   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 14:17:21.493   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:21.493  7453  7488 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 14:17:21.503   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 14:17:21.503   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:21.503  7453  7488 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.643  7453  7453 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:21.643  7453  7453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:21.653  1016  1217 I ActivityManager: Killing 7046:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-26 14:17:21.653  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:21.663  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:21.693  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-26 14:17:21.703  7453  7498 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 14:17:21.703  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 14:17:21.723  7399  7414 I bt_vendor: bluetooth satus is on
,08-26 14:17:21.723  7399  7459 D bt_userial_mct: userial_open(port:0)
08-26 14:17:21.723  7399  7459 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 14:17:21.733  7399  7459 I bt_vendor: Done intiailizing UART
,08-26 14:17:21.733  7399  7459 I bt_vendor: Done intiailizing UART,
08-26 14:17:21.733  7399  7459 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 14:17:21.733  7399  7459 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 14:17:21.733  7399  7503 D bt_userial_mct: Entering userial_read_thread()
,08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 14:17:21.743  7399  7451 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 14:17:21.833  7399  7451 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 14:17:21.833  7399  7451 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41d6ed1 
,08-26 14:17:21.833  7399  7451 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41d6ed1 
,08-26 14:17:21.843  7399  7417 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 14:17:21.853  7399  7417 E bt-btif : Calling BTA_HhEnable
,08-26 14:17:21.853  7399  7417 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 14:17:21.853  7399  7417 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 14:17:21.853  7399  7417 E BluetoothServiceJni: populateRssiValuesNative
,08-26 14:17:21.853  7399  7417 I bluedroid: getModelRssiValues
08-26 14:17:21.853  7399  7417 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:21.853  7399  7417 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:21.893  1016  1465 I art     : Explicit concurrent mark sweep GC freed 67654(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.414ms total 152.388ms
,08-26 14:17:21.893  1016  1016 D SettingsProvider: name = bluetooth_name
,08-26 14:17:21.893  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:21.893  7399  7417 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 14:17:21.903  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.903  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:21.903  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 14:17:21.913  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.913  7399  7417 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:21.913  7399  7417 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:21.913  7399  7417 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:21.913  7399  7417 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 14:17:21.913  7399  7417 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 14:17:21.913  7399  7417 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 14:17:21.913  7399  7417 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 14:17:21.913  7399  7417 E bt-btif : btif_sock_init: !vhci_init
08-26 14:17:21.913  7399  7417 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 14:17:21.913  7399  7417 D IOP_DB_BT: db_open: db_open : handle 3028439056l, read 13894 bytes onto local cache
08-26 14:17:21.913  7399  7417 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-26 14:17:21.913  7399  7417 D IOP_DB_BT: db_query: result 1
08-26 14:17:21.913  7399  7417 I         : iop_db_open: iop_db_open status 0
08-26 14:17:21.913  7399  7417 D bte_conf: Device ID record 1 : primary
08-26 14:17:21.913  7399  7417 D bte_conf:   vendorId            = 0075
08-26 14:17:21.913  7399  7417 D bte_conf:   vendorIdSource      = 0001
08-26 14:17:21.913  7399  7417 D bte_conf:   product             = 0100
08-26 14:17:21.913  7399  7417 D bte_conf:   version             = 0200
08-26 14:17:21.913  7399  7417 D bte_conf:   clientExecutableURL = 
08-26 14:17:21.913  7399  7417 D bte_conf:   serviceDescription  = 
08-26 14:17:21.913  7399  7417 D bte_conf:   documentationURL    = 
08-26 14:17:21.913  7399  7417 D bte_conf: bte_load_did_conf no section named DID2.
08-26 14:17:21.913  7399  7417 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 14:17:21.923  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.923  7399  7414 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 14:17:21.923  7399  7414 D BluetoothAdapterProperties: ScanMode =  20
08-26 14:17:21.923  7399  7414 D BluetoothAdapterProperties: State =  11
,08-26 14:17:21.923  1016  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:21.923  7399  7503 E bt_mct  : hci lib postload completed
,08-26 14:17:21.923  7399  7414 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:21.923  7399  7414 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 14:17:21.933  7399  7417 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:21.933  7399  7417 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:21.933  7399  7417 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:21.933  1016  2140 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 14:17:21.933  1016  2140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:21.933  1016  2140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:21.933  1016  2140 D SettingsProvider: selectionArgs: false
08-26 14:17:21.933  1016  2140 D SettingsProvider: selectionArgs: 1002
08-26 14:17:21.933  1016  2140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:21.933  1016  2140 D SettingsProvider: ret = -1
,08-26 14:17:21.933  7399  7414 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:21.933  7399  7414 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 14:17:21.933  1016  1077 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:21.933  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.943  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:21.943  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.943  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.943  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.943  7399  7414 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:21.943  7399  7414 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 14:17:21.943  7399  7414 D BluetoothAdapterService: starting service from this receiver
,08-26 14:17:21.943  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:21.943  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.953  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.953  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.953  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.953  7399  7414 I BluetoothAdapterState: Entering On State from state = 11
,08-26 14:17:21.953  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:21.953  1177  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:21.953  1177  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.953  7399  7407 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:21.953  7399  7407 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.953  6743  6755 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:21.953  6743  6755 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.953  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 14:17:21.953  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:21.953  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:21.953  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:21.953  2001  2165 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:21.963  2001  2165 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.973  1016  1045 D BluetoothPan: Binding service...
,08-26 14:17:21.973  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 14:17:21.973  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
,08-26 14:17:21.973  1423  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:21.973  7399  7399 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.973  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:21.983  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:21.983  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:21.983  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.983  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.983  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.983  1423  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:21.983  1303  7045 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:21.983  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:21.983  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-26 14:17:21.983  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.993  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.993  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.993  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.993  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:21.993  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:21.993  1458  1839 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:21.993  1458  1839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.993  1438  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:21.993  1438  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.993  7453  7463 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:21.993  7453  7463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:21.993  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 14:17:21.993  1303  1312 D Bluetoothsap: Binding service...
,08-26 14:17:22.003  7399  7399 I BluetoothPbapService: Handler(): got msg=1
,08-26 14:17:22.003  1016  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:22.003  1303  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 14:17:22.013  7399  7509 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 14:17:22.013  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 14:17:22.013  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.013  1303  1303 D BluetoothInputDevice: Proxy object connected
08-26 14:17:22.013  1303  1303 D HidProfile: Bluetooth service connected
,08-26 14:17:22.013  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.013  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.013  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.013  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:22.013  1303  1312 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 14:17:22.023  1303  7045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:22.023  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-26 14:17:22.023  1303  1303 D SapProfile: Bluetooth service connected
08-26 14:17:22.023  1303  1303 D Bluetoothsap: getConnectedDevices()
08-26 14:17:22.023  1303  7045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:22.023  1303  1318 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:22.023  7399  7509 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 14:17:22.023  7399  7509 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:22.023  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 14:17:22.023  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.023  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.023  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.023  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.023  1303  1312 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 14:17:22.023  7399  7509 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-26 14:17:22.023  7399  7509 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:22.023  7399  7509 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:22.023  7399  7509 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@272babf9
,08-26 14:17:22.023  1303  1303 D BluetoothMap: Proxy object connected
08-26 14:17:22.023  7399  7509 D BluetoothSocket: channel: 19
08-26 14:17:22.023  7399  7509 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 14:17:22.023  1303  1303 D MapProfile: Bluetooth service connected
08-26 14:17:22.023  1303  1303 D BluetoothMap: getConnectedDevices()
,08-26 14:17:22.033  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 14:17:22.033  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.033  1016  1045 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:22.033  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.033  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.033  1423  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:22.033  1303  1303 D BluetoothPbap: Proxy object connected
08-26 14:17:22.033  1303  1303 D PbapServerProfile: Bluetooth service connected
08-26 14:17:22.033  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:22.033  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:22.033  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.033  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.033  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.033  1423  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:22.043  1303  7045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:22.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:22.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:22.043  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.043  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.043  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.043  1303  7045 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:22.043  1303  1303 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:22.043  1458  1649 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:22.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:22.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:22.043  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.043  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:22.043  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.043  1458  1649 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:22.043  1423  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:22.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:22.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:22.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.053  1423  1446 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:22.053  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:22.053  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 14:17:22.053  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:22.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.053  7399  7508 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:22.053  1016  1016 D BluetoothA2dp: Proxy object connected
08-26 14:17:22.053  1303  1318 D BluetoothPan: Binding service...
,08-26 14:17:22.053  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 14:17:22.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.053  1423  7510 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:22.053  1423  7510 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:22.053  1303  7045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:22.053  1303  1303 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:22.053  1303  1303 D PanProfile: Bluetooth service connected
,08-26 14:17:22.053  1303  7045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:22.053  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:22.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.053  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.053  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 14:17:22.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:22.063  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.063  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-26 14:17:22.063  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:22.063  1303  1303 D BluetoothA2dp: Proxy object connected
08-26 14:17:22.063  1303  1303 D A2dpProfile: Bluetooth service connected
,08-26 14:17:22.063  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:22.063  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@9a10a45, true
,08-26 14:17:22.073  1423  1423 D BluetoothHeadset: registerMessageListener
,08-26 14:17:22.073  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:22.073  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.073  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 14:17:22.073  1882  1882 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:22.073  1016  1325 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:22.073  1016  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 14:17:22.073  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:22.083  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:22.083  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.083  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:22.083  7399  7408 D HeadsetService: registerMessageListener
08-26 14:17:22.083  1016  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:22.083  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.083  7399  7408 D HeadsetService: registerMessageListener
,08-26 14:17:22.083  7399  7435 D HeadsetStateMachine: Disconnected process message: 70
08-26 14:17:22.083  7399  7435 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3794473e
08-26 14:17:22.083  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 14:17:22.083  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:22.083  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:22.083  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.083  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.083  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.083  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.093  7399  7512 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 14:17:22.093  1303  1303 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 14:17:22.093  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 14:17:22.093  1303  1303 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 14:17:22.093  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 14:17:22.093  1303  1303 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 14:17:22.093  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 14:17:22.093  1303  1303 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 14:17:22.093  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:22.093  7399  7435 D HeadsetStateMachine: Disconnected process message: 9
08-26 14:17:22.093  7399  7435 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 14:17:22.103  7399  7512 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 14:17:22.103  7399  7512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:22.103   283   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 14:17:22.103   283   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 14:17:22.103   283   695 V voice   : voice_set_parameters: exit with code(-2)
08-26 14:17:22.103   283   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 14:17:22.103   283   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 14:17:22.103   283   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 14:17:22.103   283   695 V audio_hw_primary: adev_set_parameters: exit
08-26 14:17:22.103  7399  7435 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 14:17:22.103  7399  7512 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,08-26 14:17:22.103  7399  7512 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:22.103  7399  7512 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:22.103  7399  7512 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fcb699f
,08-26 14:17:22.103  7399  7512 D BluetoothSocket: channel: 5
08-26 14:17:22.103  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:22.113  1016  2134 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 14:17:22.113  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.113  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.113  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:22.113  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:22.123  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:22.123  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:22.133  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:22.133  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 14:17:22.143  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:22.143  7399  7399 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 14:17:22.143  1016  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 14:17:22.143  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.143  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0,
08-26 14:17:22.143  1016  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.143  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.153  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.,
08-26 14:17:22.153  1016  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:22.153  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.163  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.163  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.163  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.163  2001  7518 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:22.173  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:22.173  1016  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:22.173  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.173  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.173  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.183  1016  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:22.193  1016  1077 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:22.193  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.193  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.193  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.203  7399  7522 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:22.203  7399  7522 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:22.203  2001  7518 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 14:17:22.203  7399  7522 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-26 14:17:22.203  7399  7522 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:22.203  7399  7522 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:22.203  7399  7522 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3181e131
08-26 14:17:22.203  7399  7522 D BluetoothSocket: channel: 12
08-26 14:17:22.203  7399  7522 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:22.853  1016  3356 D SSRM:n  : SIOP:: AP = 370
,08-26 14:17:23.133   288   288 E SMD     : DCD OFF
,08-26 14:17:23.813  6743  6799 D BluetoothAdapter: disable()
,08-26 14:17:23.813  1016  1325 D SettingsProvider: name = bluetooth_on
,08-26 14:17:23.813  7399  7414 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 14:17:23.813  7399  7414 D BluetoothAdapterProperties: Setting state to 13
08-26 14:17:23.813  7399  7414 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:23.813  7399  7414 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:23.813  7399  7414 D BluetoothAdapterService: updateAdapterState state is 13
08-26 14:17:23.813  1016  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:23.813  1016  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:23.813  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.813  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.813  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:23.813  7399  7399 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 14:17:23.813  7399  7414 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:23.813  7399  7414 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 14:17:23.823  7399  7414 D BluetoothAdapterService: terminating service from this receiver
,08-26 14:17:23.823  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:23.823  7399  7399 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d00016, channel: 19, state: LISTENING
08-26 14:17:23.823  7399  7399 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d00016, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@272babf9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@269aed97mSocket: android.net.LocalSocket@3e255b84 impl:android.net.LocalSocketImpl@23e25f6d fd:FileDescriptor[74]
08-26 14:17:23.823  7399  7399 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e255b84 impl:android.net.LocalSocketImpl@23e25f6d fd:FileDescriptor[74]
,08-26 14:17:23.823  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.823  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.823  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:23.823  1303  1303 D BluetoothPbap: Proxy object disconnected
08-26 14:17:23.823  7399  7414 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:23.823  7399  7414 D BluetoothAdapterProperties: mDiscovering is false
,08-26 14:17:23.823  1016  1077 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:23.823  7399  7414 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 14:17:23.823  1303  1303 D PbapServerProfile: Bluetooth service disconnected
,08-26 14:17:23.833  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:23.833  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-26 14:17:23.843  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:23.843  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:23.843  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:23.843  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:23.843  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:23.843  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 14:17:23.853  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:23.853  1016  1077 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:23.853  1016  1217 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:23.853  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:23.853  1882  1882 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 14:17:23.853  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:23.863  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.863  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:23.863  7399  7399 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3616cc33, channel: 5, state: LISTENING
,08-26 14:17:23.863  7399  7399 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3616cc33, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fcb699f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c5eabf0mSocket: android.net.LocalSocket@18528569 impl:android.net.LocalSocketImpl@17fefbee fd:FileDescriptor[76]
08-26 14:17:23.863  7399  7399 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18528569 impl:android.net.LocalSocketImpl@17fefbee fd:FileDescriptor[76]
,08-26 14:17:23.863  7399  7399 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:23.863  7399  7399 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3067f88f, channel: 12, state: LISTENING
08-26 14:17:23.863  7399  7399 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3067f88f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3181e131, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@179a971cmSocket: android.net.LocalSocket@22850f25 impl:android.net.LocalSocketImpl@18e2e8fa fd:FileDescriptor[81]
08-26 14:17:23.863  7399  7399 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22850f25 impl:android.net.LocalSocketImpl@18e2e8fa fd:FileDescriptor[81]
,08-26 14:17:23.863  7399  7522 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 14:17:23.863  7399  7522 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 14:17:23.863  1016  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:23.863  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:23.863  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.863  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:23.863  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:23.863  7399  7417 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:23.873  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.873  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:23.873  7399  7417 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:23.873  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.873  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:23.873  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:23.873  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:23.873  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:23.883  1016  1503 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 14:17:23.883  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:23.883  7399  7414 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 14:17:23.883  7399  7414 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 14:17:23.883  7399  7414 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 14:17:23.883  7399  7414 E bt-btif : cmd socket is not created
08-26 14:17:23.883  7399  7414 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 14:17:23.883  7399  7451 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 14:17:23.883  7399  7451 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 14:17:23.883  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:23.883  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 14:17:23.883  7399  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 14:17:23.883  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:23.893  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.893  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.893  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:23.893  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:23.893  7399  7399 V BluetoothOppManager: cleanUp...
,08-26 14:17:23.903  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:23.903  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:23.913  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:23.913  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 14:17:23.933  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:23.943  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 14:17:24.093  7399  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:24.093  7399  7451 W bt-btif : ag scb idx 1 not allocated
,08-26 14:17:24.093  7399  7451 W bt-btif : ag scb idx 2 not allocated,
08-26 14:17:24.093  7399  7451 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 14:17:24.093  7399  7503 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:24.093  7399  7503 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-26 14:17:24.093  7399  7417 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:24.093  7399  7459 I bt_vendor: hw_epilog_process
08-26 14:17:24.093  7399  7417 D bt_userial_mct: userial_close,
08-26 14:17:24.093  7399  7417 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 14:17:25.353  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:25.353  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 14:17:25.353  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:17:25.353  1016  1029 D BatteryService: stay LED for fully charged
08-26 14:17:25.353  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:25.353  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:25.353  1016  1016 I MotionRecognitionService: Plugged
08-26 14:17:25.353  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:17:25.353  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-26 14:17:25.363  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 14:17:25.363  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 14:17:25.373  7399  7399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:17:25.373  7399  7435 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:25.383  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:25.383  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:17:25.383  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:25.443  7399  7417 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:25.443  7399  7417 I bt_vendor: bluetooth satus is on
08-26 14:17:25.443  7399  7417 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:25.443  7399  7417 I bt_vendor: Starting hciattach daemon
08-26 14:17:25.443  7399  7417 I bt_vendor: try to set false
,08-26 14:17:25.443  7399  7417 I bt_vendor: Starting hciattach daemon
08-26 14:17:25.443  7399  7417 I bt_vendor: try to set false
08-26 14:17:25.443  7399  7417 I bt_vendor: cleanup,
,08-26 14:17:25.443  7399  7451 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:25.443  7399  7417 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:25.443  7399  7417 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 14:17:25.443  7399  7414 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 14:17:25.443  1016  2134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.443  7399  7414 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:25.443  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 14:17:25.443  7399  7414 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 14:17:25.443  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.443  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:25.443  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
08-26 14:17:25.443  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:25.453  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.443  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 14:17:25.453  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
08-26 14:17:25.443  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.443  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.443  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:25.443  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:25.443  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:25.443  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:25.443  7399  7399 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:25.443  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.443  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:25.443  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:25.443  7399  7399 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:25.443  7399  7399 D BtGatt.GattService: stop()
08-26 14:17:25.443  7399  7399 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 14:17:25.453  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:25.453  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:25.453  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 14:17:25.453  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:25.453  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.453  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:25.453  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:25.453  7399  7399 D HeadsetService: Received stop request...Stopping profile...
08-26 14:17:25.453  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7,
,08-26 14:17:25.463  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:25.463  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 14:17:25.463  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:25.463  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:25.463  1016  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.463  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.463  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.463  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.463  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:25.463  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 14:17:25.463  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:25.463  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 14:17:25.463  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.463  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.463  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.463  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.463  1303  1303 D HeadsetProfile: Bluetooth service disconnected
08-26 14:17:25.463  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:25.473  1016  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.473  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.473  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.473  1016  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.473  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.473  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:25.473  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.473  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.473  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.473  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 14:17:25.473  1016  1077 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:25.473  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 14:17:25.473  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.473  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.473  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:25.473  7399  7414 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:25.473  7399  7414 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 14:17:25.473  7399  7414 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 14:17:25.473  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 14:17:25.473  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 14:17:25.473  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:25.473  7399  7399 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:25.483  7399  7399 D A2dpService: Received stop request...Stopping profile...
08-26 14:17:25.483  7399  7444 D A2dpStateMachine: Exit Disconnected: -1
,08-26 14:17:25.483  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:25.483  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:25.483  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 14:17:25.483  7399  7399 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 14:17:25.483  7399  7399 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:25.483  1303  1303 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:25.483  1303  1303 D A2dpProfile: Bluetooth service disconnected
,08-26 14:17:25.483  7399  7399 D HidService: Received stop request...Stopping profile...
08-26 14:17:25.483  7399  7399 D HidService: Stopping Bluetooth HidService
,08-26 14:17:25.483  7399  7399 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:25.483  7399  7399 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 14:17:25.483  7399  7399 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 14:17:25.483  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:25.493  7399  7399 D HealthService: Received stop request...Stopping profile...
,08-26 14:17:25.493  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7,
,08-26 14:17:25.493  1303  1303 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:25.493  1303  1303 D HidProfile: Bluetooth service disconnected
,08-26 14:17:25.493  7399  7399 D PanService: Received stop request...Stopping profile...
,08-26 14:17:25.493  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:25.493  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 14:17:25.493  7399  7399 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 14:17:25.493  1303  1303 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:25.493  1303  1303 D PanProfile: Bluetooth service disconnected
,08-26 14:17:25.503  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:25.503  7399  7399 D SapService: Received stop request...Stopping profile...
,08-26 14:17:25.503  7399  7399 D SapService: Stopping Bluetooth SapService
08-26 14:17:25.503  7399  7399 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:25.503  1303  1303 D BluetoothMap: Proxy object disconnected
08-26 14:17:25.503  1303  1303 D MapProfile: Bluetooth service disconnected
,08-26 14:17:25.503  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 14:17:25.503  1303  1303 D SapProfile: Bluetooth service disconnected
,08-26 14:17:25.503  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 14:17:25.503  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:25.503  7399  7399 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:25.503  7399  7399 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:25.503  7399  7399 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 14:17:25.503  7399  7445 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 14:17:25.503  7399  7399 I GKI_LINUX: GKI_exit_task 2 done
,08-26 14:17:25.513  7399  7399 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 14:17:25.513  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 14:17:25.513  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.513  7399  7399 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.513  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-26 14:17:25.513  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.513  7399  7399 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:25.513  7399  7399 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:25.513  7399  7399 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 14:17:25.513  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-26 14:17:25.513  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:25.513  7399  7399 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:25.513  7399  7399 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-26 14:17:25.513  7399  7399 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 14:17:25.513  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-26 14:17:25.513  7399  7399 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:25.513  7399  7399 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-26 14:17:25.513  7399  7399 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-26 14:17:25.513  7399  7399 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-26 14:17:25.523  7399  7399 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 14:17:25.523  7399  7414 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 14:17:25.523  7399  7414 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:25.523  7399  7414 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:25.523  7399  7414 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:25.523  7399  7414 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 14:17:25.523  7399  7414 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:25.523  7399  7414 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 14:17:25.523  7399  7414 I BluetoothAdapterState: Entering OffState
08-26 14:17:25.523  1177  4413 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.523  1177  4413 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.523  7399  7508 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.523  7399  7508 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.523  6743  6755 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:25.523  6743  6755 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.523  6743  6755 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 14:17:25.523  6743  6755 D BluetoothLeAdvertiser: Exit stop advertising
08-26 14:17:25.523  6743  6755 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 14:17:25.523  6743  6755 D BluetoothLeScanner: Exiting stopAllScan
,08-26 14:17:25.523  2001  6717 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:25.523  2001  6717 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.523  1303  7045 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.533  1458  1649 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:25.533  1458  1649 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.533  1438  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1438  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.533  7453  7468 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:25.533  7453  7468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.533  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1303  1312 D Bluetoothsap: Unbinding service...
,08-26 14:17:25.533  1303  1318 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1303  1318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.533  1303  7045 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 14:17:25.533  1303  1312 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 14:17:25.543  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:25.543  7399  7511 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:25.543  1423  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:25.543  1423  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:25.543  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:25.543  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 14:17:25.543  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:25.553  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:25.553  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
,08-26 14:17:25.553  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:25.563  7399  7417 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 14:17:25.563  7399  7399 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:25.563  7399  7399 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 14:17:25.563  7399  7399 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 14:17:25.563  7399  7399 I art     : System.exit called, status: 0
08-26 14:17:25.563  7399  7399 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:25.563  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:25.563  1177  1752 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:25.563  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-26 14:17:25.563  1177  1752 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1882  1882 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 14:17:25.563  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1177  1177 D BluetoothAdapter: 571615735: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1016  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:25.563  2001  2168 D BluetoothAdapter: 631950391: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:25.563  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:25.573  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:25.573  2001  2168 D BluetoothAdapter: 631950391: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:25.573  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:25.573  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:25.573  1016  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:25.573  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 14:17:25.573  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:25.573  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:25.573  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:25.573  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:25.573  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:25.583  1016  1475 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:25.583  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.583  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.583  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.583  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:25.593  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:25.593  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:25.593  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:25.593  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 14:17:25.663  1016  2134 I ActivityManager: Process com.android.bluetooth (pid 7399)(adj 0) has died(53,704)
,08-26 14:17:25.673  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:25.673  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:25.673  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:25.673  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:25.673  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:25.673  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:25.683  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
,08-26 14:17:25.683  2001  7539 D EasyUnlockInitService: Handling intent for initializer IntentService.,
08-26 14:17:25.693  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:25.693  1016  1028 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:25.693  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:25.693  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:25.693  2001  7539 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 14:17:26.133   288   288 E SMD     : DCD OFF
,08-26 14:17:26.823  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:26.823  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:27.533  1016  1320 E Watchdog: !@Sync 4,
,08-26 14:17:27.533  1016  1048 I PowerManagerService: [PWL] Off : 75s ago,
08-26 14:17:27.533  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-26 14:17:27.533  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-26 14:17:27.533  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=15058)
,08-26 14:17:28.143   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:29.143   288   288 E SMD     : DCD OFF
,08-26 14:17:29.143   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:29.823  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 14:17:29.823  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36d44954 added. We now have 6 listener(s)
,08-26 14:17:29.823  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:29.823  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:29.823  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11b300fd added. We now have 7 listener(s)
08-26 14:17:29.823  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:29.823  6743  6799 I System.out: IsBluetoothEnabled,
08-26 14:17:29.823  6743  6799 D BluetoothAdapter: disable()
,08-26 14:17:29.823  1016  1028 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
08-26 14:17:29.823  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:29.823  1016  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:29.823  6743  6799 D BluetoothAdapter: enable()
08-26 14:17:29.823  1016  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 14:17:29.823  1016  1478 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 14:17:29.823  1016  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:29.833  1016  1478 D SettingsProvider: name = bluetooth_on
,08-26 14:17:29.833  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:29.833  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:29.833  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-26 14:17:29.833  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 14:17:29.843  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:29.843  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:29.843  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:29.843  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:29.853  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7544 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 14:17:29.853  7544  7544 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:29.853  7544  7544 E Zygote  : v2,
08-26 14:17:29.853  7544  7544 I libpersona: KNOX_SDCARD checking this for 1002
,08-26 14:17:29.853  7544  7544 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:29.863  7544  7544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 14:17:29.863  7544  7544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 14:17:29.873  7544  7544 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 14:17:29.893  7544  7544 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:29.893  7544  7544 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:29.903  7544  7544 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 14:17:29.903  7544  7544 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:29.923  7544  7544 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding GattService
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding A2dpService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding HidService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding HealthService
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding PanService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding SapService
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 14:17:29.953  7544  7544 D BtSettings.ProfileConfig: Adding HidDevService
08-26 14:17:29.953  7544  7544 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 14:17:29.963  1016  1325 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 14:17:29.963  1016  1325 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1325 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1325 D SettingsProvider: selectionArgs: false
08-26 14:17:29.963  1016  1325 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1325 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.963  1016  1325 D SettingsProvider: ret = -1
,08-26 14:17:29.963  1016  1077 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:29.963  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1077 D SettingsProvider: selectionArgs: false
,08-26 14:17:29.963  1016  1077 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:29.963  1016  1077 D SettingsProvider: ret = -1
,08-26 14:17:29.963  1016  1503 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 14:17:29.963  1016  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1503 D SettingsProvider: selectionArgs: false
08-26 14:17:29.963  1016  1503 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.963  1016  1503 D SettingsProvider: ret = -1
,08-26 14:17:29.963  1016  2140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 14:17:29.963  1016  2140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  2140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  2140 D SettingsProvider: selectionArgs: false
08-26 14:17:29.963  1016  2140 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:29.963  1016  2140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.963  1016  2140 D SettingsProvider: ret = -1
,08-26 14:17:29.963  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 14:17:29.963  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1028 D SettingsProvider: selectionArgs: false
08-26 14:17:29.963  1016  1028 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.963  1016  1028 D SettingsProvider: ret = -1
,08-26 14:17:29.963  1016  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
,08-26 14:17:29.963  1016  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-26 14:17:29.963  1016  1479 D SettingsProvider: selectionArgs: false,
08-26 14:17:29.963  1016  1479 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:29.963  1016  1479 D SettingsProvider: ret = -1
08-26 14:17:29.963  1016  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 14:17:29.963  1016  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1476 D SettingsProvider: selectionArgs: false
08-26 14:17:29.963  1016  1476 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:29.963  1016  1476 D SettingsProvider: ret = -1
08-26 14:17:29.963  1016  1465 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 14:17:29.963  1016  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.963  1016  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.963  1016  1465 D SettingsProvider: selectionArgs: false
,08-26 14:17:29.963  1016  1465 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.963  1016  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.963  1016  1465 D SettingsProvider: ret = -1
08-26 14:17:29.973  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:29.973  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.973  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.973  1016  1478 D SettingsProvider: selectionArgs: false
,08-26 14:17:29.973  1016  1478 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.973  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.973  1016  1478 D SettingsProvider: ret = -1
08-26 14:17:29.973  1016  2134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:29.973  1016  2134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.973  1016  2134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:29.973  1016  2134 D SettingsProvider: selectionArgs: false
08-26 14:17:29.973  1016  2134 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.973  1016  2134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.973  1016  2134 D SettingsProvider: ret = -1
08-26 14:17:29.973  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:29.973  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.973  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.973  1016  1029 D SettingsProvider: selectionArgs: false
08-26 14:17:29.973  1016  1029 D SettingsProvider: selectionArgs: 1002
08-26 14:17:29.973  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.973  1016  1029 D SettingsProvider: ret = -1
08-26 14:17:29.973  1016  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 14:17:29.973  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:29.973  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:29.973  1016  1217 D SettingsProvider: selectionArgs: false
08-26 14:17:29.973  1016  1217 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:29.973  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:29.973  1016  1217 D SettingsProvider: ret = -1
,08-26 14:17:29.983  7544  7544 D BluetoothAdapterState: make,
,08-26 14:17:29.993  7544  7544 I bluedroid: init,
,08-26 14:17:29.993  7544  7544 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-26 14:17:29.993  7544  7559 I BluetoothAdapterState: Entering OffState
08-26 14:17:29.993  7544  7544 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 14:17:29.993  7544  7544 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:29.993  7544  7544 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 14:17:29.993  7544  7544 E bt-btif : btif_fetch_local_ble_random_bdaddr,
08-26 14:17:29.993  7544  7544 I bluedroid: get_profile_interface socket
08-26 14:17:29.993  7544  7544 I bluedroid: get_profile_interface map_client
08-26 14:17:29.993  7544  7562 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 14:17:29.993  7544  7562 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-26 14:17:29.993  7544  7562 E BluetoothServiceJni: populateRssiValuesNative
08-26 14:17:29.993  7544  7562 I bluedroid: getModelRssiValues
08-26 14:17:29.993  7544  7562 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:29.993  7544  7562 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:30.003  7544  7544 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 14:17:30.003  1016  1016 D SettingsProvider: name = bluetooth_name
,08-26 14:17:30.003  7544  7562 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 14:17:30.003  7544  7544 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:30.003  1016  2134 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:30.003  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.013  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.013  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.013  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.013  7544  7557 I bluedroid: config_hci_snoop_log
,08-26 14:17:30.013  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 14:17:30.013  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-26 14:17:30.013  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 14:17:30.013  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 14:17:30.013  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:30.023  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:30.023  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.023  7544  7544 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!,
,08-26 14:17:30.033  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 14:17:30.033  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:30.033  7544  7559 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 14:17:30.033  7544  7559 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:30.033  7544  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:30.033  7544  7559 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:30.033  7544  7559 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 14:17:30.033  7544  7559 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:30.033  7544  7559 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 14:17:30.033  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.033  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-26 14:17:30.033  7544  7559 D BluetoothSecureManager: getInstant: null
08-26 14:17:30.043  7544  7559 D BluetoothSecureManager: calling getMethod for getService
,08-26 14:17:30.043  7544  7559 D BluetoothSecureManager: calling getService
08-26 14:17:30.043  7544  7559 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3a612e5c
,08-26 14:17:30.043  1016  1479 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 14:17:30.043  1016  1479 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 14:17:30.043  7544  7559 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:30.043  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 14:17:30.043  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 14:17:30.043  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:30.043  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.043  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:30.043  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 14:17:30.043  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:30.043  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:30.043  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:30.043  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-26 14:17:30.043  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-26 14:17:30.043  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 14:17:30.043  1882  1882 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:30.043  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:30.053  1016  1465 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:30.053  1016  1217 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:30.053  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:30.053  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:30.053  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:30.053  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:30.053  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.053  7544  7559 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 14:17:30.063  1016  1503 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:30.063  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.063  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.063  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.063  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:30.063  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:30.063  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:30.063  7544  7559 D BluetoothBondStateMachine: make
,08-26 14:17:30.073  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:30.073  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:30.073  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 14:17:30.073  7544  7566 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 14:17:30.073  1016  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.073  1016  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.073  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.073  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.073  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.073  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.073  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.073  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:30.073  7544  7544 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:30.073  7544  7544 D BtGatt.GattService: Received start request. Starting profile...
,08-26 14:17:30.083  7544  7544 D BtGatt.GattService: start()
08-26 14:17:30.083  7544  7544 D BtGatt.GattService: start()
08-26 14:17:30.083  7544  7544 I bluedroid: get_profile_interface gatt
,08-26 14:17:30.083  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:30.083  7544  7544 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:30.083  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.083  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 14:17:30.083  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.083  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.083  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.083  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.083  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.093  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:30.093  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:30.093  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:30.093  1016  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:30.093  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.093  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.093  1016  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.093  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.093  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:30.093  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:30.093  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:30.093  1016  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.093  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.103  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.103  1016  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.103  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.103  7544  7544 D BtGatt.GattService: mStartError = false
08-26 14:17:30.103  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:30.103  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 14:17:30.103  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:30.103  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 14:17:30.103  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:30.103  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.103  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.103  7544  7544 D HeadsetService: Received start request. Starting profile...
08-26 14:17:30.103  7544  7544 D HeadsetService: start()
,08-26 14:17:30.103  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.103  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.103  7544  7544 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 14:17:30.103  7544  7544 D HeadsetStateMachine: make
,08-26 14:17:30.103  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 14:17:30.103  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 14:17:30.113  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:30.113  7544  7544 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 14:17:30.113  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.123  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.123  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.123  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.123  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.123  1016  1077 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 14:17:30.123  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.123  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.123  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.123  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:30.123  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:30.123  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:30.123  7544  7559 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:30.123  1016  1325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.123  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.123  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.123  1016  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.123  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.133  1016  1503 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 14:17:30.133  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.133  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.133  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:30.133  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:30.133  7544  7544 I bluedroid: get_profile_interface handsfree
,08-26 14:17:30.143  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:30.143  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:30.143  7544  7559 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 14:17:30.143  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:30.143  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.143   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:30.143  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.143  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:30.143  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:30.153  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:30.153  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:30.153  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:30.153  7544  7544 I DualScoManager: Instantiating Dual Sco Manager
,08-26 14:17:30.153  7544  7544 I DualScoManager: Set HeadsetServiceHelper
08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-26 14:17:30.153  7544  7559 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:30.153  7544  7559 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 14:17:30.153  7544  7559 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 14:17:30.153  7544  7544 D BluetoothAtMessage: createCMTIContentObservers
,08-26 14:17:30.153  1016  1217 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 14:17:30.153  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:30.153  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:30.153  1016  1217 D SettingsProvider: selectionArgs: false
08-26 14:17:30.153  1016  1217 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:30.163  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:30.163  1016  1217 D SettingsProvider: ret = -1
,08-26 14:17:30.163  7544  7569 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 14:17:30.163  7544  7544 D HeadsetService: mStartError = false
08-26 14:17:30.163  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:30.163  7544  7569 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 14:17:30.163  7544  7569 D HeadsetStateMachine: map size, before remove : 0
08-26 14:17:30.163  7544  7569 D HeadsetStateMachine: map size, after remove: 0
,08-26 14:17:30.163  7544  7544 D A2dpService: Received start request. Starting profile...
,08-26 14:17:30.163  7544  7544 D A2dpService: start()
,08-26 14:17:30.163  7544  7544 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 14:17:30.173  7544  7544 I bluedroid: get_profile_interface avrcp
,08-26 14:17:30.173  7544  7544 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:30.173  7544  7544 D Avrcp   : Initialize Media Controller
08-26 14:17:30.173  7544  7544 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 14:17:30.173  7544  7544 E Avrcp   : getActiveSessions
,08-26 14:17:30.173  7544  7544 D Avrcp   : pick active media Controller
08-26 14:17:30.173  7544  7544 D Avrcp   : Get the active Media Controller 
,08-26 14:17:30.193  7544  7544 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 14:17:30.193  7544  7573 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 14:17:30.193  7544  7544 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:30.193  7544  7544 D A2dpStateMachine: make
,08-26 14:17:30.193  7544  7544 I bluedroid: get_profile_interface a2dp
08-26 14:17:30.193  7544  7575 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:30.193  7544  7544 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 14:17:30.203  7544  7544 D A2dpService: mStartError = false
08-26 14:17:30.203  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:30.203  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 14:17:30.203  7544  7544 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 14:17:30.203  7544  7544 D HidService: Received start request. Starting profile...
08-26 14:17:30.203  7544  7544 D HidService: start()
08-26 14:17:30.203  7544  7544 I bluedroid: get_profile_interface hidhost
08-26 14:17:30.203  7544  7544 D HidService: setHidService(): set to: null
08-26 14:17:30.203  7544  7544 D HidService: mStartError = false
08-26 14:17:30.203  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:30.203  7544  7544 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:30.203  7544  7544 D HealthService: Received start request. Starting profile...
08-26 14:17:30.203  7544  7544 D HealthService: start()
,08-26 14:17:30.203  7544  7574 D A2dpStateMachine: Enter Disconnected: -2
,08-26 14:17:30.203  7544  7544 I bluedroid: get_profile_interface health
,08-26 14:17:30.203  7544  7544 D HealthService: mStartError = false
08-26 14:17:30.203  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:30.213  7544  7544 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 14:17:30.213  7544  7544 D PanService: Received start request. Starting profile...
08-26 14:17:30.213  7544  7544 D PanService: start()
08-26 14:17:30.213  7544  7544 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:30.213  7544  7544 I bluedroid: get_profile_interface pan
,08-26 14:17:30.213  7544  7544 D PanService: mStartError = false
08-26 14:17:30.213  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:30.213  7544  7544 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 14:17:30.213  1423  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 14:17:30.213  7544  7573 D BluetoothMediaBrowser: no now playing list
08-26 14:17:30.213  7544  7573 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-26 14:17:30.213  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 14:17:30.213  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:30.213  1423  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 14:17:30.213  7544  7544 D BluetoothMapService: Received start request. Starting profile...
,08-26 14:17:30.223  7544  7544 D BluetoothMapService: start()
,08-26 14:17:30.223  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:30.223  7544  7544 D BluetoothMapService: mStartError = false
08-26 14:17:30.223  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:30.223  7544  7544 D HeadsetStateMachine: Proxy object connected
,08-26 14:17:30.223  7544  7544 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 14:17:30.223  7544  7544 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 14:17:30.223  7544  7544 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 14:17:30.223  7544  7569 D HeadsetStateMachine: Disconnected process message: 11
08-26 14:17:30.223  7544  7544 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 14:17:30.223  7544  7569 D HeadsetStateMachine: Disconnected process message: 18
,08-26 14:17:30.233  7544  7544 D SapService: Received start request. Starting profile...
08-26 14:17:30.233  7544  7544 D SapService: start()
08-26 14:17:30.233  7544  7544 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 14:17:30.233  7544  7544 I bluedroid: get_profile_interface sap
08-26 14:17:30.233  7544  7544 D SapService: mStartError = false
08-26 14:17:30.233  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:30.233  7544  7544 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:17:30.233  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 14:17:30.233  7544  7544 D BluetoothA2dp: Proxy object connected
08-26 14:17:30.233  7544  7544 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 14:17:30.233  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 14:17:30.233  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 14:17:30.233  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 14:17:30.233  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 14:17:30.233  7544  7569 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:30.233  7544  7569 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:30.233  7544  7569 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:30.233  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:30.253  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 14:17:30.253  7544  7544 E BluetoothAdapterService(940839383): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 14:17:30.263  7544  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 14:17:30.263  7544  7559 I bluedroid: enable
,08-26 14:17:30.263  7544  7559 I bt_hci_bdroid: init
,08-26 14:17:30.263  7544  7559 I bt_vendor: bt-vendor : init
08-26 14:17:30.263  7544  7559 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:30.263  7544  7559 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 14:17:30.263  7544  7559 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 14:17:30.263  7544  7559 D bt_userial_mct: userial_init
,08-26 14:17:30.263  7544  7559 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:30.263  7544  7559 I bt_vendor: Starting hciattach daemon
,08-26 14:17:30.263  7544  7559 I bt_vendor: try to set false
,08-26 14:17:30.263  7544  7579 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 14:17:30.263  7544  7559 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 14:17:30.263  7544  7559 I bt_vendor: Starting hciattach daemon
08-26 14:17:30.263  7544  7559 I bt_vendor: try to set true
,08-26 14:17:30.283  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 14:17:30.333  7589  7589 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 14:17:30.343  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:30.353  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:30.363  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 14:17:30.373  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:30.383  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 14:17:30.743  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-26 14:17:30.753  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:30.813  7544  7559 I bt_vendor: bluetooth satus is on,
08-26 14:17:30.813  7544  7581 D bt_userial_mct: userial_open(port:0),
08-26 14:17:30.813  7544  7581 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 14:17:30.813  7544  7581 I bt_vendor: Done intiailizing UART
,08-26 14:17:30.823  7544  7581 I bt_vendor: Done intiailizing UART,
08-26 14:17:30.823  7544  7581 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 14:17:30.823  7544  7581 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_A2D,
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_GAP,
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_SDP,
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 14:17:30.823  7544  7579 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-26 14:17:30.823  7544  7601 D bt_userial_mct: Entering userial_read_thread(),
,08-26 14:17:30.933  7544  7579 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 14:17:30.933  7544  7579 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41e2ed1 
,08-26 14:17:30.933  7544  7579 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41e2ed1 
,08-26 14:17:30.943  7544  7562 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 14:17:30.943  7544  7562 E bt-btif : Calling BTA_HhEnable
,08-26 14:17:30.943  7544  7562 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 14:17:30.943  7544  7562 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-26 14:17:30.943  7544  7562 E BluetoothServiceJni: populateRssiValuesNative
,08-26 14:17:30.943  7544  7562 I bluedroid: getModelRssiValues
08-26 14:17:30.943  7544  7562 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:30.943  7544  7562 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:30.953  7544  7562 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 14:17:30.953  1016  1016 D SettingsProvider: name = bluetooth_name
,08-26 14:17:30.953  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:30.953  7544  7562 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:30.953  7544  7562 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:30.953  7544  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:30.953  7544  7562 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 14:17:30.953  7544  7562 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 14:17:30.953  7544  7562 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 14:17:30.953  7544  7562 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 14:17:30.953  7544  7562 E bt-btif : btif_sock_init: !vhci_init
08-26 14:17:30.963  7544  7562 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-26 14:17:30.963  7544  7562 D IOP_DB_BT: db_open: db_open : handle 3028443152l, read 13894 bytes onto local cache
08-26 14:17:30.963  7544  7562 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-26 14:17:30.963  7544  7562 D IOP_DB_BT: db_query: result 1
08-26 14:17:30.963  7544  7562 I         : iop_db_open: iop_db_open status 0
,08-26 14:17:30.963  7544  7562 D bte_conf: Device ID record 1 : primary
08-26 14:17:30.963  7544  7562 D bte_conf:   vendorId            = 0075
08-26 14:17:30.963  7544  7562 D bte_conf:   vendorIdSource      = 0001
08-26 14:17:30.963  7544  7562 D bte_conf:   product             = 0100
08-26 14:17:30.963  7544  7562 D bte_conf:   version             = 0200
08-26 14:17:30.963  7544  7562 D bte_conf:   clientExecutableURL = 
08-26 14:17:30.963  7544  7562 D bte_conf:   serviceDescription  = 
08-26 14:17:30.963  7544  7562 D bte_conf:   documentationURL    = 
08-26 14:17:30.963  7544  7562 D bte_conf: bte_load_did_conf no section named DID2.
08-26 14:17:30.963  7544  7562 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 14:17:30.963  7544  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 14:17:30.963  7544  7559 D BluetoothAdapterProperties: ScanMode =  20
,08-26 14:17:30.963  7544  7559 D BluetoothAdapterProperties: State =  11
,08-26 14:17:30.963  1016  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:30.963  7544  7559 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:30.963  7544  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 14:17:30.973  7544  7562 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:30.973  7544  7562 D BluetoothAdapterProperties: Scan Mode:21
,08-26 14:17:30.973  1016  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 14:17:30.973  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:30.973  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:30.973  1016  1028 D SettingsProvider: selectionArgs: false
08-26 14:17:30.973  1016  1028 D SettingsProvider: selectionArgs: 1002
08-26 14:17:30.973  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:30.973  1016  1028 D SettingsProvider: ret = -1
,08-26 14:17:30.973  7544  7559 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:30.973  7544  7559 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 14:17:30.973  7544  7601 E bt_mct  : hci lib postload completed
08-26 14:17:30.973  1016  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:30.973  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.973  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.973  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.973  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.973  7544  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:30.983  7544  7559 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:30.983  7544  7559 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 14:17:30.983  7544  7559 D BluetoothAdapterService: starting service from this receiver
,08-26 14:17:30.983  1016  2134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:30.983  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 14:17:30.983  1177  1199 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:30.983  1177  1199 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:30.983  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:30.983  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.983  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.983  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:30.983  6743  6751 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:30.983  6743  6751 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:30.983  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:30.983  7544  7559 I BluetoothAdapterState: Entering On State from state = 11
08-26 14:17:30.993  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:30.993  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:30.993  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:30.993  7544  7557 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:30.993  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:30.993  2001  2165 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:30.993  2001  2165 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:30.993  1016  1045 D BluetoothPan: Binding service...
,08-26 14:17:31.003  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 14:17:31.003  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.003  1423  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.003  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.003  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.013  7544  7544 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 14:17:31.013  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.013  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.013  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.013  1423  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.013  1303  1312 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:31.023  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-26 14:17:31.023  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.023  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.023  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.023  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.023  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.023  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.023  1458  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.023  1458  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.023  1438  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.023  1438  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.023  7453  7463 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.023  7453  7463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.023  7544  7557 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.023  7544  7557 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.023  1303  1318 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 14:17:31.023  1303  1318 D Bluetoothsap: Binding service...
,08-26 14:17:31.033  1303  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-26 14:17:31.033  7544  7544 I BluetoothPbapService: Handler(): got msg=1
,08-26 14:17:31.033  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 14:17:31.033  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.033  1016  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:31.033  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.033  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.033  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.033  1303  1318 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 14:17:31.033  1303  7045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.033  1303  7045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.033  1303  1312 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 14:17:31.033  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:31.033  1303  1303 D BluetoothInputDevice: Proxy object connected
,08-26 14:17:31.033  1303  1303 D HidProfile: Bluetooth service connected
,08-26 14:17:31.043  7544  7605 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 14:17:31.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 14:17:31.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.043  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.043  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.043  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.043  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-26 14:17:31.043  1303  1303 D SapProfile: Bluetooth service connected
08-26 14:17:31.043  1303  1303 D Bluetoothsap: getConnectedDevices()
08-26 14:17:31.043  1303  7045 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 14:17:31.043  1303  1303 D BluetoothMap: Proxy object connected
,08-26 14:17:31.043  7544  7605 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:31.053  7544  7605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.053  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 14:17:31.053  1303  1303 D MapProfile: Bluetooth service connected
08-26 14:17:31.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 14:17:31.053  1303  1303 D BluetoothMap: getConnectedDevices()
,08-26 14:17:31.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.053  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.053  7544  7605 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-26 14:17:31.053  1423  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.053  7544  7605 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:31.053  7544  7605 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:31.053  7544  7605 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@272babf9
08-26 14:17:31.053  7544  7605 D BluetoothSocket: channel: 19
08-26 14:17:31.053  7544  7605 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 14:17:31.053  1303  1303 D BluetoothPbap: Proxy object connected
,08-26 14:17:31.053  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.063  1303  1303 D PbapServerProfile: Bluetooth service connected
08-26 14:17:31.063  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.063  1423  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.063  1303  1312 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.063  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.063  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.063  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.063  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.063  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.063  1303  1303 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:31.063  1303  1312 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.063  1458  1649 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.073  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:31.073  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.073  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.073  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.073  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.073  1458  1649 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.073  1423  7510 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.073  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.073  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.073  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.073  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.073  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.073  1423  7510 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.073  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:31.073  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.073  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:31.083  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.083  1016  1016 D BluetoothA2dp: Proxy object connected
,08-26 14:17:31.083  1303  1318 D BluetoothPan: Binding service...
,08-26 14:17:31.083  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 14:17:31.083  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.083  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.083  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.083  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.083  1303  1303 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:31.083  1303  1303 D PanProfile: Bluetooth service connected
08-26 14:17:31.083  1423  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.083  1423  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:31.083  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:31.083  1303  1312 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.083  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:31.083  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.093  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.093  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.093  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.093  1303  1303 D BluetoothA2dp: Proxy object connected
08-26 14:17:31.093  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 14:17:31.093  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:31.093  1303  1303 D A2dpProfile: Bluetooth service connected
,08-26 14:17:31.093  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.093  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-26 14:17:31.093  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:31.103  1177  1177 D BluetoothTile:  onBluetoothStateChange:,
,08-26 14:17:31.103  1882  1882 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-26 14:17:31.103  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2110959a, true
08-26 14:17:31.113  1423  1423 D BluetoothHeadset: registerMessageListener
,08-26 14:17:31.113  1016  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:31.113  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.113  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 14:17:31.113  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.113  1016  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.113  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:17:31.113  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:31.113  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.113  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.113  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 14:17:31.113  7544  7558 D HeadsetService: registerMessageListener
,08-26 14:17:31.113  7544  7558 D HeadsetService: registerMessageListener
,08-26 14:17:31.113  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:31.113  7544  7569 D HeadsetStateMachine: Disconnected process message: 70
08-26 14:17:31.113  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 14:17:31.113  7544  7569 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3794473e
,08-26 14:17:31.113  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 14:17:31.113  7544  7606 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 14:17:31.113  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 14:17:31.113  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 14:17:31.113  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 14:17:31.123  1303  1303 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 14:17:31.123  1016  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:31.123  1303  1303 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 14:17:31.123  1303  1303 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 14:17:31.123  1303  1303 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 14:17:31.123  1016  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-26 14:17:31.123  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:31.123  7544  7569 D HeadsetStateMachine: Disconnected process message: 9
08-26 14:17:31.123  7544  7569 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-26 14:17:31.123  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:31.123  7544  7606 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:31.123  7544  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.133  1177  1752 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:31.133  7544  7606 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 14:17:31.133  7544  7606 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:31.133  7544  7606 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:31.133  7544  7606 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fcb699f
08-26 14:17:31.133  7544  7606 D BluetoothSocket: channel: 5
08-26 14:17:31.133   283   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 14:17:31.133   283   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 14:17:31.133   283   682 V voice   : voice_set_parameters: exit with code(-2)
08-26 14:17:31.133   283   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 14:17:31.133   283   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 14:17:31.133   283   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 14:17:31.133   283   682 V audio_hw_primary: adev_set_parameters: exit
08-26 14:17:31.133  7544  7569 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-26 14:17:31.133  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 14:17:31.133  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:31.133  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 14:17:31.133  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.133  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.143  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-26 14:17:31.143   314   314 I ServiceManager: Waiting for service AtCmdFwd...
08-26 14:17:31.153  1303  1303 D DockEventReceiver: finishStartingService: stopping service
08-26 14:17:31.153  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
08-26 14:17:31.153  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.163  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-26 14:17:31.163  7544  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
08-26 14:17:31.163  7544  7544 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:31.173  1016  2140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:31.173  1016  2140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
08-26 14:17:31.173  1016  2140 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.173  1016  2140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.173  1016  2140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.183  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:31.183  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:31.183  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.183  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.183  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.193  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:31.193  2001  7613 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:31.203  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:31.203  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:31.203  1016  1503 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:31.203  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.203  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.203  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:31.213  1016  2134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:31.213  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.213  1016  2134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.213  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:31.223  7544  7617 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:31.223  7544  7617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:31.223  7544  7617 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 14:17:31.223  7544  7617 D BluetoothSocket: bindListen(), new LocalSocket 
,08-26 14:17:31.233  7544  7617 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 14:17:31.233  7544  7617 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3181e131
08-26 14:17:31.233  7544  7617 D BluetoothSocket: channel: 12
08-26 14:17:31.233  7544  7617 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:31.233  2001  7613 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 14:17:31.563  1016  3369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:31.843  1016  2057 V SAMP_SPCM_test: CSC File load.. 
,08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:31.853  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:31.853  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:31.853  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:31.853  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1432b1f2 added. We now have 8 listener(s)
,08-26 14:17:31.853  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:31.863  1016  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:31.863  1016  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:31.863  1016  1478 D SecContentProvider2: mCursor = null,
,08-26 14:17:31.863  1016  1478 D WifiService: setWifiEnabled: false pid=6743, uid=10171,
08-26 14:17:31.863  1016  1478 D SettingsProvider: name = wifi_on
,08-26 14:17:31.873  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 14:17:31.873  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 14:17:31.873  1016  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:31.873  1016  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 14:17:31.873  1016  1475 D SecContentProvider2: mCursor = null
,08-26 14:17:31.873  1016  1475 D WifiService: setWifiEnabled: true pid=6743, uid=10171
,08-26 14:17:31.883  1016  1475 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:31.883  1016  1475 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:31.883  1016  1475 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:31.883  1016  1475 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 14:17:31.883  1016  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:31.883  1016  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:31.883  1016  1475 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:31.883  1016  1475 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 14:17:31.883  1016  1475 D SettingsProvider: name = wifi_on
,08-26 14:17:31.893  1016  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 14:17:31.933  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 14:17:31.943  1016  2057 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 14:17:31.943  1016  2057 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-26 14:17:31.953  1016  2057 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-26 14:17:31.953  1016  2057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:31.953  1016  2057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:31.953  1016  2057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:31.953  1016  2057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:31.963  7622  7622 E Zygote  : MountEmulatedStorage()
08-26 14:17:31.963  7622  7622 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:31.963  7622  7622 E Zygote  : v2
08-26 14:17:31.963  7622  7622 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:31.963  1016  2057 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 14:17:31.973  7622  7622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:31.973  7622  7622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:31.973  7622  7622 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:31.993  7622  7622 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:32.003  7622  7622 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:32.013  7622  7622 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:32.063  1016  2057 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 14:17:32.133   288   288 E SMD     : DCD OFF
,08-26 14:17:32.143   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:32.253  1016  1043 D Tethering: interfaceAdded wlan0
,08-26 14:17:32.263  1016  1130 E Tethering: No numeric data
08-26 14:17:32.263  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:32.263  1016  1130 D Tethering: clearTetheredNotification()
,08-26 14:17:32.263  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:32.263  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:32.263  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:32.263  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:32.263  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:32.263  1016  1130 D Tethering: InitialState.processMessage what=4
08-26 14:17:32.273  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:32.273  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:32.273  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 14:17:32.273  1016  1043 D Tethering: interfaceAdded p2p0
08-26 14:17:32.273  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 14:17:32.273  1016  1130 E Tethering: No numeric data
08-26 14:17:32.273  1016  1124 V NetworkStats: performPollLocked() took 12ms
08-26 14:17:32.283  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:32.283  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 14:17:32.283  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:32.283  1016  1130 D Tethering: clearTetheredNotification()
,08-26 14:17:32.283  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 14:17:32.283  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:32.293   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 14:17:32.293   278   983 D SoftapController: Softap fwReload - Ok
,08-26 14:17:32.293  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 14:17:32.293  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 14:17:32.293   278   983 D CommandListener: Setting iface cfg
08-26 14:17:32.293   278   983 D CommandListener: Trying to bring down wlan0
08-26 14:17:32.293  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:32.293  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:32.293  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:32.303  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:32.293  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:32.303   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:32.303  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:32.303  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:32.303  1016  1124 V NetworkStats: performPollLocked() took 9ms
,08-26 14:17:32.303  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:32.303  1016  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 14:17:32.313  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:32.313  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:32.313  1016  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 14:17:32.313  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:32.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:32.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:32.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:32.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:32.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:32.323  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:32.323  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 14:17:32.323  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:32.323  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:32.323  1177  1177 D HotspotTile: onReceive : 2, 0
,08-26 14:17:32.323  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:32.333  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:32.333  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:32.333  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:32.333  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:32.333  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:32.333  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:32.333  1619  1619 I Hs20UtilService: Starting #19
,08-26 14:17:32.333  1619  1678 I Hs20UtilService: Message received 5011
,08-26 14:17:32.333  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:32.333  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:32.333  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:32.333  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:32.363  7645  7645 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 14:17:32.363  7645  7645 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 14:17:32.363  7645  7645 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 14:17:32.373  7645  7645 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-26 14:17:32.373   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7645
08-26 14:17:32.373   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 14:17:32.373  7645  7645 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-26 14:17:32.373  7645  7645 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:32.373  7645  7645 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 14:17:32.373  7645  7645 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 14:17:32.373   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7645
08-26 14:17:32.373   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 14:17:32.523   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-26 14:17:32.523  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 14:17:32.573  7645  7645 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 14:17:32.573  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 14:17:32.583  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 14:17:32.583   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7645,
08-26 14:17:32.583   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 14:17:32.583  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 14:17:32.583  7645  7645 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:32.583  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:32.583  7645  7645 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 14:17:32.583  7645  7645 E wpa_supplicant: SIM READ ERROR
08-26 14:17:32.583  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:32.583  7645  7645 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:32.583  7645  7645 E wpa_supplicant: SIM READ ERROR
08-26 14:17:32.583  7645  7645 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:32.583  7645  7645 I wpa_supplicant: wpa_default_ap_write_once
08-26 14:17:32.583  7645  7645 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:32.583  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:32.583  7645  7645 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 14:17:32.583  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:32.583  7645  7645 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-26 14:17:32.583  7645  7645 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 14:17:32.593  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:32.593  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 14:17:32.593  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:32.633  7645  7645 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 14:17:32.753  7645  7645 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 14:17:32.753  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 14:17:32.763  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 14:17:32.763   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7645,
08-26 14:17:32.763   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 14:17:32.763  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 14:17:32.763  7645  7645 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:32.763  7645  7645 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 14:17:32.763  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 14:17:32.783  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 14:17:32.783   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7645
08-26 14:17:32.783   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 14:17:32.783  7645  7645 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 14:17:32.783  7645  7645 I wpa_supplicant: ssSupport state is = 1,
08-26 14:17:32.783  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:32.783  7645  7645 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:32.783  7645  7645 E wpa_supplicant: SIM READ ERROR
08-26 14:17:32.783  7645  7645 I wpa_supplicant: wpa_default_ap_write_once,
08-26 14:17:32.783  7645  7645 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:32.783  7645  7645 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 14:17:32.783  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 14:17:32.783  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:32.783  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:32.783  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:32.783  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:32.783  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:32.833  7645  7645 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 14:17:32.833  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 14:17:32.863  1016  3356 D SSRM:n  : SIOP:: AP = 340,
,08-26 14:17:33.153   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 14:17:33.203  7645  7645 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 14:17:33.203  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 14:17:33.203  7645  7645 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-26 14:17:33.213  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 14:17:33.213  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:33.213  7645  7645 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 14:17:33.213  7645  7645 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:33.213  7645  7645 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:33.213  7645  7645 E wpa_supplicant: SIM READ ERROR
08-26 14:17:33.213  7645  7645 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:33.233  7645  7645 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 14:17:33.243  7645  7645 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:33.243  1016  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 14:17:33.253  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:33.253  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:33.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:33.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:33.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:33.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:33.253  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:33.253  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 14:17:33.253  1177  1752 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:33.253  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:33.253  1177  1177 D HotspotTile: onReceive : 3, 0
,08-26 14:17:33.263  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:33.263  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 14:17:33.263  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:33.263  1016  1127 E WifiConfigStore: Not a HS20
,08-26 14:17:33.263  1016  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 14:17:33.263  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
08-26 14:17:33.263  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:33.273  1016  1465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:33.273  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:33.273  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 14:17:33.273  7645  7645 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 14:17:33.273  7645  7645 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 14:17:33.273  7645  7645 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 14:17:33.273  7645  7645 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:33.273  7645  7645 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 14:17:33.273  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:33.273  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 14:17:33.273  1016  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:33.273  7645  7645 I wpa_supplicant: First Scan Start
08-26 14:17:33.273  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:33.273  7645  7645 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 14:17:33.273  1016  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-26 14:17:33.273  1016  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:33.273  1016  1127 I WifiNative-HAL: startHal
08-26 14:17:33.273  1016  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5e488c
08-26 14:17:33.273  1016  1127 I WifiNative-HAL: Could not start hal
,08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.273  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:33.283  1016  1127 E WifiNative-wlan0: do suspend true
08-26 14:17:33.283  1619  1619 I Hs20UtilService: Starting #20
08-26 14:17:33.283  1619  1678 I Hs20UtilService: Message received 5011
08-26 14:17:33.283  1016  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 14:17:33.283  6984  6984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:33.283  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:33.283  1016  1126 D WifiP2pService: P2pEnablingState
08-26 14:17:33.283   278   983 D CommandListener: Setting iface cfg
08-26 14:17:33.283  1016  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 14:17:33.283   278   983 D CommandListener: Trying to bring up p2p0
08-26 14:17:33.283  1016  1126 D WifiP2pService: P2p socket connection successful
08-26 14:17:33.283  1016  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 14:17:33.283  1016  1126 D WifiP2pService: P2pEnabledState
,08-26 14:17:33.283  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:33.283  6562  6562 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:33.283  6562  6562 D SecurityLogAgent: StateMachine : Current State = 1,
08-26 14:17:33.283  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 14:17:33.283  6562  6562 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 14:17:33.283  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 14:17:33.283  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:33.283  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 14:17:33.283  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 14:17:33.283  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:33.283  1016  1046 D WifiDisplayController: disconnect
08-26 14:17:33.283  1016  1046 D WifiDisplayController: updateConnection
08-26 14:17:33.283  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:33.283  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:33.293  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3,
,08-26 14:17:33.293  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:33.293  1016  1149 I WifiNative-HAL: startHal
08-26 14:17:33.293  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9eba09bc,
08-26 14:17:33.293  1016  1149 I WifiNative-HAL: Could not start hal
08-26 14:17:33.293  1016  1149 E WifiScanningService: could not start HAL
,08-26 14:17:33.293  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:33.293  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:33.293  1016  1127 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:33.293  1016  1016 D RttService: SCAN_AVAILABLE : 3
,08-26 14:17:33.293  1016  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:33.293  7645  7645 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 14:17:33.293  7645  7645 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 14:17:33.293  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:33.293  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:33.293  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:33.293  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:33.303  7645  7645 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 14:17:33.303  1016  1127 E WifiStateMachine: Failed to set frequency band 0
08-26 14:17:33.303  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 14:17:33.303  1016  1503 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:33.303  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:33.303  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:33.303  1016  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 14:17:33.303  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:33.303  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:33.303  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:33.303  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 14:17:33.303  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 14:17:33.313  1016  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 14:17:33.313  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  secondary type: null
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  wps: 0
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  grpcapab: 0
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  devcapab: 0
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  status: 3
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  wfdInfo: null
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-26 14:17:33.313  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-26 14:17:33.313  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:33.313  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:33.313  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 14:17:33.323  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:33.323  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:33.323  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:33.323  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 14:17:33.323  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:33.323  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:33.323  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:33.333  7335  7335 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 14:17:33.333  7335  7335 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:33.333  1016  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 14:17:33.333  1016  1126 D WifiP2pService: InactiveState
,08-26 14:17:33.333  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:33.333  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:33.333  7645  7645 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 14:17:33.333  7350  7350 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:33.343  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-26 14:17:33.343  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.903  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:33.903  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:33.913  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 14:17:33.913  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 14:17:33.913  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d96c1d Bundle[{}]
,08-26 14:17:33.923  6743  6799 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:17:33.923  6743  6799 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 14:17:33.923  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:17:33.923  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 14:17:33.923  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 14:17:33.923  6743  6799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:33.933  6743  6799 I System.out: Running OutgoingSocketThread
,08-26 14:17:33.933  6743  7652 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1340)
,08-26 14:17:33.933  6743  7652 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 59358
,08-26 14:17:33.943  6743  7652 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 14:17:34.493  7645  7645 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
08-26 14:17:34.493  7645  7645 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 14:17:34.493  7645  7645 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-26 14:17:34.493  7645  7645 I wpa_supplicant: Trying to associate with  'G700'
,08-26 14:17:34.493  7645  7645 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-26 14:17:34.493  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-26 14:17:34.503  1016  7650 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-26 14:17:34.523  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:34.523  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:34.623  7645  7645 E wpa_supplicant: Cmd 35605 not handled
,08-26 14:17:34.623  7645  7645 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:34.623  7645  7645 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 14:17:34.623  7645  7645 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 14:17:34.623  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 14:17:34.623  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:34.623  7645  7645 I wpa_supplicant: Associated with F4.99.3E
08-26 14:17:34.623  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:34.623  7645  7645 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:34.623  7645  7645 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 14:17:34.623  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:34.623  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 14:17:34.623  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:34.623  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:34.623  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:34.623  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:34.623  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:34.623  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:34.633  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 14:17:34.633  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 14:17:34.633  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-26 14:17:34.633  1016  1130 E Tethering: No numeric data
,08-26 14:17:34.633  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:34.633  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:34.633  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,08-26 14:17:34.633  1016  1130 D Tethering: clearTetheredNotification()
08-26 14:17:34.643  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:34.643  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:34.643  7645  7645 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 14:17:34.643  7645  7645 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
08-26 14:17:34.643  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:34.643  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:34.643  7645  7645 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 14:17:34.643  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:34.643  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 14:17:34.643  7645  7645 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:34.643  1016  1124 V NetworkStats: performPollLocked() took 8ms
08-26 14:17:34.643  7645  7645 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 14:17:34.643  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 14:17:34.643  7645  7645 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 14:17:34.643  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 14:17:34.643  7645  7645 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 14:17:34.643  7645  7645 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:34.643  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 14:17:34.643  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-26 14:17:34.643  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:34.653  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:34.653  1016  1127 D SecContentProvider2: mCursor = null
08-26 14:17:34.653  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:34.653  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:34.663  1016  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 14:17:34.663  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 14:17:34.663  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:34.663  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:34.673  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:34.673  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:34.673  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:34.673  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:34.673  1016  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 14:17:34.673  1016  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 14:17:34.673  1016  1129 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:34.673  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 14:17:34.673  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:34.673  1016  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:34.673  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:34.673  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:34.673  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.673  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:34.683  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:34.693  1619  1619 I Hs20UtilService: Starting #21
,08-26 14:17:34.693  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:34.693  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:34.693  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-26 14:17:34.693  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-26 14:17:34.693  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:34.693  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 14:17:34.693  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:34.703  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:34.703   278   983 D CommandListener: Setting iface cfg
,08-26 14:17:34.713  1016  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 14:17:34.713  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:34.713  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:34.723  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-26 14:17:34.723  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:34.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:34.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 14:17:34.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 14:17:34.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-26 14:17:34.733  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:34.733  1016  1127 D SecContentProvider2: mCursor = null
,08-26 14:17:34.733  1016  1127 E WifiNative-wlan0: do suspend false
,08-26 14:17:34.743  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 14:17:34.743  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 14:17:34.943  6743  6799 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1341)
08-26 14:17:34.943  6743  6799 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1341)
08-26 14:17:34.943  6743  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1346)
08-26 14:17:34.943  6743  6799 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 14:17:34.943  6743  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1347)
08-26 14:17:34.943  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:34.943  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ef9b043 added. We now have 2 listener(s)
,08-26 14:17:34.943  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 14:17:34.943  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:34.943  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:34.943  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:34.943  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad6a6c0 added. We now have 9 listener(s)
08-26 14:17:34.943  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:34.943  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:34.953  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:34.953  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:34.963  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:34.963  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb5fb3e added. We now have 3 listener(s)
08-26 14:17:34.963  7655  7655 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-26 14:17:34.963  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efd0d9f added. We now have 10 listener(s)
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:34.963  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:34.963  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:34.963  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:34.963  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:34.963  7655  7655 I dhcpcd  : version 5.5.6 starting
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ef9b043 removed from the list,
08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:34.963  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad6a6c0 removed from the list
08-26 14:17:34.963  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:34.963  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:34.963  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:34.963  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:34.963  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad6a6c0 not in the list
08-26 14:17:34.963  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:34.963  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:34.973  7655  7655 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efd0d9f removed from the list
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:34.973  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:34.973  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb5fb3e removed from the list
08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df6eec added. We now have 2 listener(s)
08-26 14:17:34.973  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:34.973  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:34.973  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:34.973  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307652b5 added. We now have 9 listener(s)
08-26 14:17:34.973  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:34.973  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:34.983  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:34.983  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:34.993  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:34.993  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:34.993  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22aee4bb added. We now have 3 listener(s)
,08-26 14:17:34.993  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 14:17:34.993  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:34.993  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:34.993  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:34.993  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 14:17:34.993  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ca8dd8 added. We now have 10 listener(s)
08-26 14:17:34.993  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:34.993  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:34.993  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:34.993  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:34.993  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:34.993  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-26 14:17:34.993  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.003  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:35.003  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:35.003  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:35.013  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-26 14:17:35.013  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:35.013  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-26 14:17:35.013  7544  7564 D BtGatt.GattService: registerClient() - UUID=669a9c85-9a0d-402b-8412-89cc2802dc51,
,08-26 14:17:35.053  7655  7655 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 14:17:35.053  7655  7655 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 14:17:35.053  7655  7655 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 14:17:35.053  7655  7655 I dhcpcd  : bssid match
08-26 14:17:35.053  7655  7655 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 14:17:35.053  7544  7562 D BtGatt.GattService: onClientRegistered() - UUID=669a9c85-9a0d-402b-8412-89cc2802dc51, clientIf=6,
,08-26 14:17:35.063  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:35.063  7544  7558 D BtGatt.GattService: start scan with filters
,08-26 14:17:35.063  7544  7568 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:35.063  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:35.063  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:35.063  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:35.063  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:35.063  7544  7568 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@381411d7
,08-26 14:17:35.073  7544  7562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 14:17:35.073  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.073  7544  7568 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:35.073  7544  7568 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:35.073  7544  7568 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 14:17:35.073  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:35.073  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.073  7544  7568 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:35.073  7544  7568 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:35.073  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:35.073  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:35.083  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:35.083  7544  7562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:35.083  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.083  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:35.083  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 14:17:35.083  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.093  6743  6799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 14:17:35.093  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-26 14:17:35.093  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:35.093  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.093  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:35.093  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:35.093  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:35.093  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-26 14:17:35.093  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:35.093  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:35.093  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:35.103  7544  7607 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:35.103  7544  7558 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:35.103  7544  7568 D BtGatt.ScanManager: filter size is 1
08-26 14:17:35.103  7544  7568 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 14:17:35.103  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:35.103  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:35.103  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:35.103  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:35.103  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:35.103  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:35.103  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.103  7544  7568 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:35.103  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:35.113  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:35.113  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:35.113  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.113  7544  7568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 14:17:35.113  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 14:17:35.113  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:35.113  7544  7562 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:35.113  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.113  7655  7655 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-26 14:17:35.113  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.113  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:35.113  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:35.113  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:35.123  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:35.123  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:35.123  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:35.123  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:35.123  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.123  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.123  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:35.123  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df6eec removed from the list
,08-26 14:17:35.123  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.123  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307652b5 removed from the list
,08-26 14:17:35.123  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:35.123  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.123  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:35.123  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.133  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307652b5 not in the list
,08-26 14:17:35.133  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:35.133  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:35.133  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ca8dd8 removed from the list
08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:35.133  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.133  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.133  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:35.133  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22aee4bb removed from the list
,08-26 14:17:35.133  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:35.133  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@446af84 added. We now have 2 listener(s)
,08-26 14:17:35.143   288   288 E SMD     : DCD OFF,
08-26 14:17:35.143  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:35.143  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:35.143  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:35.143  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:35.143  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fab236d added. We now have 9 listener(s)
,08-26 14:17:35.143  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:35.143  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:35.143  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:35.153  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:35.153  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:35.153  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:35.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:35.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9573033 added. We now have 3 listener(s)
,08-26 14:17:35.153  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.153  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:35.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 14:17:35.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:35.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:35.153  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5413ff0 added. We now have 10 listener(s),
08-26 14:17:35.153  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:35.153  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:35.153  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:35.153  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:35.153  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:35.153  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:35.153  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:35.163  7655  7655 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 14:17:35.163  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:35.163  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:35.163  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:35.173  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:35.173  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:35.173  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:35.183  7544  7558 D BtGatt.GattService: registerClient() - UUID=1a7f368b-107b-4818-9a05-cb236b27acfd
,08-26 14:17:35.223  7544  7562 D BtGatt.GattService: onClientRegistered() - UUID=1a7f368b-107b-4818-9a05-cb236b27acfd, clientIf=6
,08-26 14:17:35.223  6743  6755 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-26 14:17:35.223  7544  7557 D BtGatt.GattService: start scan with filters
08-26 14:17:35.223  7544  7568 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:35.223  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:35.223  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:35.223  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:35.223  7544  7562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 14:17:35.223  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.223  7544  7568 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:35.223  7544  7568 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 14:17:35.223  7544  7568 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 14:17:35.223  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 14:17:35.223  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:35.223  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.233  7544  7568 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:35.233  7544  7568 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:35.233  7544  7562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-26 14:17:35.233  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.233  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:35.233  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:35.233  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:35.253  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:35.253  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.253  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:35.263  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:35.263  6743  6799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 14:17:35.263  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:35.263  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:35.263  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:35.263  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:35.263  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.263  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:35.263  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:35.263  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@446af84 removed from the list
08-26 14:17:35.263  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.263  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fab236d removed from the list
08-26 14:17:35.263  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:35.263  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.263  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.263  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 14:17:35.263  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.263  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.273  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fab236d not in the list
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:35.273  7544  7607 D BtGatt.GattService: stopScan() - queue size =1
08-26 14:17:35.273  7544  7558 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:35.273  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:35.273  7544  7568 D BtGatt.ScanManager: filter size is 1
08-26 14:17:35.273  7544  7568 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 14:17:35.273  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:35.273  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 14:17:35.273  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.273  7544  7568 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:35.283  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:35.283  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.283  7544  7568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:35.283  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:35.283  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:35.283  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:35.283  7544  7562 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:35.283  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.283  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.293  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:35.293  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 14:17:35.293  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.293  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5413ff0 removed from the list
08-26 14:17:35.293  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:35.293  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:35.293  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:35.293  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:35.293  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9573033 removed from the list
,08-26 14:17:35.293  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:35.293  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:35.293  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:35.293  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:35.293  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e126b1c added. We now have 2 listener(s)
,08-26 14:17:35.303  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:35.303  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:35.303  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:35.303  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:35.303  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e225325 added. We now have 9 listener(s)
08-26 14:17:35.303  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:35.303  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:35.303  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:35.303  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:35.313  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:35.313  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:35.313  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:35.313  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5e72ab added. We now have 3 listener(s)
,08-26 14:17:35.313  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.313  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.323  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 14:17:35.323  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:35.323  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:35.323  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 14:17:35.323  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13691d08 added. We now have 10 listener(s),
08-26 14:17:35.323  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:35.323  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:35.323  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:35.323  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:35.323  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:35.323  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:35.333  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:35.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:35.333  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:35.343  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:35.343  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:35.343  6743  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:35.343  7544  7607 D BtGatt.GattService: registerClient() - UUID=132c20e8-af99-4d49-81fc-036777cc514d
,08-26 14:17:35.393  7544  7562 D BtGatt.GattService: onClientRegistered() - UUID=132c20e8-af99-4d49-81fc-036777cc514d, clientIf=6
08-26 14:17:35.393  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 14:17:35.393  7544  7564 D BtGatt.GattService: start scan with filters
,08-26 14:17:35.393  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:35.393  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:35.393  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:35.393  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:35.393  7544  7562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-26 14:17:35.393  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-26 14:17:35.393  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:35.393  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:35.393  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.393  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 14:17:35.393  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:35.393  7544  7568 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:35.393  7544  7562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:35.393  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.393  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:35.393  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:35.393  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.403  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:35.403  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:35.403  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:35.403  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:35.403  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.403  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:35.403  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:35.403  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e126b1c removed from the list
08-26 14:17:35.403  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.403  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e225325 removed from the list
08-26 14:17:35.403  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:35.403  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.403  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.403  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 14:17:35.403  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:35.403  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.413  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e225325 not in the list
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:35.413  7544  7607 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:35.413  7544  7568 D BtGatt.ScanManager: filter size is 1
,08-26 14:17:35.413  7544  7568 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 14:17:35.413  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:35.413  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 14:17:35.413  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:17:35.413  1016  1028 D BatteryService: stay LED for fully charged
08-26 14:17:35.413  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:35.413  7544  7562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:35.413  7544  7564 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:35.413  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.413  7544  7568 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:35.413  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:35.413  1016  1016 I MotionRecognitionService: Plugged
,08-26 14:17:35.413  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:17:35.413  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:35.423  7544  7562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:35.423  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:35.423  7544  7568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:35.423  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:35.423  6743  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:35.423  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-26 14:17:35.423  7544  7562 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:35.423  7544  7562 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:35.423  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:35.423  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:17:35.423  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:17:35.423  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 14:17:35.443  7544  7544 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:17:35.443  7544  7569 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:35.443  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:35.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:35.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.443  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13691d08 removed from the list
08-26 14:17:35.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:35.443  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.443  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:35.443  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:35.443  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5e72ab removed from the list
,08-26 14:17:35.443  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:35.443  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:35.443  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f701b4 added. We now have 2 listener(s)
,08-26 14:17:35.443  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:35.443  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:35.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 14:17:35.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:35.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:35.453  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:35.453  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e8c1dd added. We now have 9 listener(s)
08-26 14:17:35.453  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:35.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:35.453  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:17:35.453  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:17:35.453  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 14:17:35.453  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:35.453  6743  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:35.463  6743  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:35.463  6743  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:35.463  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:35.463  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecc8c23 added. We now have 3 listener(s)
,08-26 14:17:35.463  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.463  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:35.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 14:17:35.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:35.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:35.463  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:35.463  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25dc8520 added. We now have 10 listener(s)
08-26 14:17:35.463  6743  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:35.463  6743  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:35.463  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 14:17:35.473  6743  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:35.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:35.473  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f701b4 removed from the list
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:35.473  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e8c1dd removed from the list
,08-26 14:17:35.473  6743  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:35.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:35.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:35.473  6743  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e8c1dd not in the list
08-26 14:17:35.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:35.473  6743  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25dc8520 removed from the list
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:35.473  6743  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:35.473  6743  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:35.473  6743  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:35.483  6743  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecc8c23 removed from the list
,08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 14:17:35.483  6743  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:35.483  6743  7687 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1354, name: My test thread name)
,08-26 14:17:35.493  6743  7687 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1354, thread name: My test thread name)
,08-26 14:17:35.493  6743  7687 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1354, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:35.493  6743  7688 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1356, name: My test thread name)
,08-26 14:17:35.493  6743  7688 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1356, thread name: My test thread name)
,08-26 14:17:35.493  6743  7688 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1356, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:35.493  6743  6799 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 14:17:35.493  6743  6799 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 14:17:35.493  6743  6799 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 14:17:35.493  6743  6799 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 14:17:35.493  6743  6799 D com.test.thalitest.ThaliTestRunner: Total duration: 24343 ms
,08-26 14:17:35.493  6743  6799 I jxcore-log: *Native tests were executed*
08-26 14:17:35.493  6743  6799 I jxcore-log: 
,08-26 14:17:35.493  6743  6799 I jxcore-log: Total number of executed tests:  80
08-26 14:17:35.493  6743  6799 I jxcore-log: 
08-26 14:17:35.493  6743  6799 I jxcore-log: Number of passed tests:  80
08-26 14:17:35.493  6743  6799 I jxcore-log: 
08-26 14:17:35.493  6743  6799 I jxcore-log: Number of failed tests:  0
08-26 14:17:35.493  6743  6799 I jxcore-log: 
,08-26 14:17:35.493  6743  6799 I jxcore-log: Number of ignored tests:  0
08-26 14:17:35.493  6743  6799 I jxcore-log: 
08-26 14:17:35.493  6743  6799 I jxcore-log: Total duration:  24343
08-26 14:17:35.493  6743  6799 I jxcore-log: 
,08-26 14:17:35.493  6743  6799 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 14:17:35.493  6743  6799 I jxcore-log: 
,08-26 14:17:35.503  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.503  6743  6799 I jxcore-log: 
08-26 14:17:35.503  6743  6743 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 14:17:35.503  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.503  6743  6799 I jxcore-log: 
08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
,08-26 14:17:35.513  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:35.513  6743  6799 I jxcore-log: 
,08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
,08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
,08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
,08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.523  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.523  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
,08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
,08-26 14:17:35.533  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:35.533  6743  6799 I jxcore-log: 
,08-26 14:17:35.553  1016  1127 E WifiNative-wlan0: do suspend true
,08-26 14:17:35.573  1016  1126 D WifiP2pService: InactiveState{ what=143375 },
08-26 14:17:35.573  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-26 14:17:35.583  1016  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 14:17:35.583  1016  1127 E WifiStateMachine: VerifyingLinkState enter
,08-26 14:17:35.583  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:35.583  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 14:17:35.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-26 14:17:35.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.583  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:35.593  1016  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-26 14:17:35.593  1016  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 14:17:35.593  1016  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 14:17:35.593  1016  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 14:17:35.593  1016  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 14:17:35.593  1016  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 14:17:35.593  1016  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 14:17:35.603  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:35.603  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:35.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.603  1016  2134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:35.603  1016  2134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:35.603  1016  2134 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:35.603  1016  2134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:35.603  1016  2134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:35.603  1619  1619 I Hs20UtilService: Starting #22
08-26 14:17:35.603  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:35.613  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:35.613  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 14:17:35.613  1016  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 14:17:35.623  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:35.623  1016  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 14:17:35.623  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:35.623  6743  6799 I jxcore-log: 
,08-26 14:17:35.623  1016  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 14:17:35.623  1016  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-26 14:17:35.623  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 14:17:35.623  1016  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 14:17:35.623  1016  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-26 14:17:35.633  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:35.633  1016  1129 D ConnectivityService: LTETest block dns file not exists
08-26 14:17:35.633  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:35.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.633  1016  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 14:17:35.633  1016  1129 V NetworkStats: updateIfacesLocked()
08-26 14:17:35.633  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.633  1016  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:35.633  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 14:17:35.633  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
,08-26 14:17:35.633  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-26 14:17:35.633  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:35.633  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:35.643  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:35.643  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:35.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.643  1016  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 14:17:35.643  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:35.643  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:35.643  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:35.643  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:35.643  1016  1129 V NetworkStats: performPollLocked() took 10ms
08-26 14:17:35.643  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:35.643  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:35.653  1619  1619 I Hs20UtilService: Starting #23
,08-26 14:17:35.653  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:35.653  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:35.653  1016  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.653  1016  1129 E ConnectivityService: updateNetworkInfo()
08-26 14:17:35.653  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:35.653  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.653  1016  1129 V NetworkStats: updateIfacesLocked()
08-26 14:17:35.653  1016  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:35.663  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.663  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:35.663  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:35.663  1016  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-26 14:17:35.663  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:35.663  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:35.663  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:35.663  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.663  1016  1129 V NetworkStats: performPollLocked() took 6ms
,08-26 14:17:35.663  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.663  1016  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.663  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.663  1016  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.663  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:35.663  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 14:17:35.663  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:35.663  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-26 14:17:35.663  1016  7653 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-26 14:17:35.663  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:35.663  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:35.663  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:35.673   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:17:35.673   278   979 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-26 14:17:35.673  1303  2238 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:35.673  1016  1129 D ConnectivityService:    accepting network in place of null
08-26 14:17:35.673  1016  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 14:17:35.673  1016  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 14:17:35.673  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 14:17:35.673  1458  1458 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:35.673  1016  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 14:17:35.673  1016  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 14:17:35.673  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 14:17:35.683  1016  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:35.683  1016  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-26 14:17:35.683  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:35.683  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:35.683  1016  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.683  1016  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:35.683  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:35.683  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 14:17:35.683  1177  1731 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:35.683  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 14:17:35.683  1016  1130 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:35.683  1619  1619 I Hs20UtilService: Starting #24
08-26 14:17:35.693  1619  1678 I Hs20UtilService: Message received 5007
,08-26 14:17:35.693  4694  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:35.693  1016  1124 V NetworkStats: updateIfacesLocked()
08-26 14:17:35.693  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.693  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:35.693  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 14:17:35.693  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:35.693  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 14:17:35.693  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 14:17:35.693  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-26 14:17:35.693  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:35.693  1016  1124 V NetworkStats: performPollLocked() took 6ms
08-26 14:17:35.693  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:35.693  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 14:17:35.693  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:35.703  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.703  1016  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:35.703  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
,08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.703  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.703  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:35.703  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:35.713  1016  1029 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 14:17:35.713  1016  1028 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 14:17:35.713  1016  1028 D SecContentProvider2: mCursor = null
,08-26 14:17:35.713  1016  1478 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 14:17:35.713  1016  1478 D SecContentProvider2: mCursor = null
,08-26 14:17:35.713  1016  2140 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 14:17:35.713  1016  2140 D SecContentProvider2: mCursor = null
,08-26 14:17:35.713  1016  1475 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 14:17:35.713  1016  1475 D SecContentProvider2: mCursor = null
,08-26 14:17:35.723  1016  1479 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-26 14:17:35.723  1016  1479 D SecContentProvider2: mCursor = null
,08-26 14:17:35.723  1016  2134 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-26 14:17:35.723  1016  2134 D SecContentProvider2: mCursor = null
,08-26 14:17:35.743   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 14:17:35.753  1016  1028 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-26 14:17:35.753  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 14:17:35.763  1016  7653 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:35.783  7689  7689 D AndroidRuntime: ,
08-26 14:17:35.783  7689  7689 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 14:17:35.783  7689  7689 D AndroidRuntime: CheckJNI is OFF
08-26 14:17:35.783  7689  7689 D AndroidRuntime: readGMSProperty: start
08-26 14:17:35.783  7689  7689 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:17:35.783  7689  7689 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:17:35.783  7689  7689 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:17:35.783  7689  7689 D AndroidRuntime: readGMSProperty: end
08-26 14:17:35.783  7689  7689 D AndroidRuntime: addProductProperty: start
,08-26 14:17:35.793  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 14:17:35.793  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-26 14:17:35.793  6743  6799 I jxcore-log: 
,08-26 14:17:35.843  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:35 GMT], X-Android-Received-Millis=[1472213855855], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472213855817]}
08-26 14:17:35.843  1016  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.843  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 14:17:35.843  1016  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.843  1016  7653 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 14:17:35.843  1016  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 14:17:35.843  1016  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 14:17:35.843  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 14:17:35.843  4694  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:35.843  1177  1731 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:35.843  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 14:17:35.843  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 14:17:35.843  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 14:17:35.843  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:35.843  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:35.843  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:35.853  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:35.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:35.903  7689  7689 E AffinityControl: AffinityControl: registerfunction enter,
,08-26 14:17:35.933  7689  7689 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-26 14:17:35.943  1016  1465 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 14:17:35.943  1016  1465 D PackageManager: START PACKAGE DELETE: observer{869158422}
08-26 14:17:35.943  1016  1465 D PackageManager: pkg{<packageName>}
08-26 14:17:35.943  1016  1465 D PackageManager: user{0}
08-26 14:17:35.943  1016  1465 D PackageManager: caller{2000}
08-26 14:17:35.943  1016  1465 D PackageManager: flags{2}
08-26 14:17:35.943  1016  1465 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 14:17:35.943  1016  1465 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 14:17:35.943  1016  1465 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 14:17:35.943  1016  1465 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-26 14:17:35.943  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 14:17:35.953  6743  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:35.953  6743  6799 I jxcore-log: 
,08-26 14:17:35.953  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-26 14:17:35.953  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 14:17:35.953  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 14:17:35.953  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 14:17:35.953  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 14:17:35.953  1016  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-26 14:17:35.963  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-26 14:17:35.973  1016  1041 I ActivityManager: Killing 6743:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 14:17:36.063  1016  1055 W PackageSettings: Skipping PackageSetting{2b8d5214 com.example.hello/10168} due to missing metadata
,08-26 14:17:36.093  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{2b2f4692 u0 com.test.thalitest/.MainActivity t2}
,08-26 14:17:36.093  1016  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,08-26 14:17:36.103  1016  1041 D InputDispatcher: Focus left window: 6743,
,08-26 14:17:36.103   258   428 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-26 14:17:36.103   258   424 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 14:17:36.123  1016  1041 D InputDispatcher: Focused application released
08-26 14:17:36.123  1016  1041 D FocusedStackFrame: Set to : 0
08-26 14:17:36.123  1016  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-26 14:17:36.123  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:17:36.123  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:36.123  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-26 14:17:36.133  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 14:17:36.133  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-26 14:17:36.143  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 14:17:36.183  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:36.193  2643  2643 I art     : Explicit concurrent mark sweep GC freed 19566(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 797us total 39.612ms
,08-26 14:17:36.193  1480  1480 D Launcher: onRestart, Launcher: 295564403
,08-26 14:17:36.203  1480  1480 D Launcher: onStart, Launcher: 295564403
08-26 14:17:36.203  1480  1480 D Launcher.HomeView: onStart
,08-26 14:17:36.203  1480  1480 D Launcher: onResume, Launcher: 295564403
,08-26 14:17:36.203  1016  1217 D SettingsProvider: name = kids_home_mode
08-26 14:17:36.203  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:36.203  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:36.203  1016  1217 D SettingsProvider: selectionArgs: false
08-26 14:17:36.203  1016  1217 D SettingsProvider: selectionArgs: 10006
08-26 14:17:36.203  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:36.203  1016  1217 D SettingsProvider: ret = -1
08-26 14:17:36.203  1480  1480 D Launcher.HomeView: onResume
,08-26 14:17:36.233  4694  4694 I art     : Explicit concurrent mark sweep GC freed 23066(1387KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.294ms total 88.762ms
,08-26 14:17:36.233  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 14:17:36.243  1016  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 14:17:36.253  1882  1882 E SamsungIME: mOCRHelper is null
,08-26 14:17:36.273  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 14:17:36.273  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 14:17:36.273  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-26 14:17:36.283  1016  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 14:17:36.283  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:36.283  1016  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-26 14:17:36.283  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:36.283  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:36.283  1016  1124 V NetworkStats: performPollLocked() took 6ms
08-26 14:17:36.283  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:36.293  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.293  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.313  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.313  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.323  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:36.323  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:36.333  1480  1480 D MenuAppsGridFragment: onResume
,08-26 14:17:36.333  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 14:17:36.333  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 14:17:36.353  1016  1476 I ActivityManager: Killing 7076:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-26 14:17:36.353  2878  2878 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 14:17:36 GMT+02:00 2016
,08-26 14:17:36.363  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:36.363  1016  1465 D ActivityManager: handle home activity for 0
08-26 14:17:36.363  1016  1465 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 14:17:36.363  1016  1465 D KnoxTimeoutHandler: post home show event for user 0
,08-26 14:17:36.363  1016  1465 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 14:17:36.363  1016  1465 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 14:17:36.363  1016  1465 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:17:36.363  1480  1480 D Launcher.HomeView: onPause
08-26 14:17:36.363  1438  1438 D RegisteredServicesCache: empty dynamic service
08-26 14:17:36.363  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 14:17:36.383  1016  1016 I art     : Explicit concurrent mark sweep GC freed 90756(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 25MB/37MB, paused 15.334ms total 235.956ms
,08-26 14:17:36.383  1016  1055 I art     : WaitForGcToComplete blocked for 184.886ms for cause Explicit
,08-26 14:17:36.403  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 14:17:36.403  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:36.403  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 14:17:36.413  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.423  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.443  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.453  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-26 14:17:36.453  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 14:17:36.453  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:36.453  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:36.453  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:36.463  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 14:17:36.463  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 14:17:36.463  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-26 14:17:36.463  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.473  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 14:17:36.473  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 14:17:36.483  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.483  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.483  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:36.483  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 14:17:36.493  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:36.503  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 14:17:36.503  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 14:17:36.503  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:36.533  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 14:17:36.533  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 14:17:36.543  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 14:17:36.543  1016  1055 I art     : Explicit concurrent mark sweep GC freed 15661(1248KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.393ms total 160.210ms
08-26 14:17:36.543  1016  1325 I art     : WaitForGcToComplete blocked for 219.787ms for cause Explicit
,08-26 14:17:36.563  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-26 14:17:36.563  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 14:17:36.563  1016  3356 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 14:17:36.563  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 14:17:36.573  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-26 14:17:36.573  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-26 14:17:36.573  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 14:17:36.573  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 14:17:36.573  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 14:17:36.573  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-26 14:17:36.623  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-26 14:17:36.623  1016  1055 D PackageManager: delete codoeFile: 
,08-26 14:17:36.633  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-26 14:17:36.633  1016  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-26 14:17:36.633  1016  1055 D PackageManager: result of delete: 1{869158422}
,08-26 14:17:36.643  7689  7689 D AndroidRuntime: Shutting down VM
,08-26 14:17:36.683  1016  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 14:17:36.703  1016  1325 I art     : Explicit concurrent mark sweep GC freed 7579(501KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 4.507ms total 155.835ms
,08-26 14:17:36.703  1016  1475 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 14:17:36.703  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:36.703  2001  2161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:36.703  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:36.703  1016  2140 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 14:17:36.703  1016  2140 D SecContentProvider2: mCursor = null
,08-26 14:17:36.713  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:36.713  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 14:17:36.713  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{1305c055 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
,08-26 14:17:36.713  1480  1480 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
,08-26 14:17:36.723  2878  2878 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 14:17:36.723  1016  1465 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-26 14:17:36.723  1016  1465 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-26 14:17:36.723  1016  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 14:17:36.723  2878  2878 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 14:17:36.723   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-26 14:17:36.723  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.723  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.723  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.723  1016  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:36.733  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:17:36.733  2878  2878 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 14:17:36.733  1016  1325 D InputDispatcher: Focus entered window: 1480
,08-26 14:17:36.733  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:36.733  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:36.743  2878  2878 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 14:17:36.743  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-26 14:17:36.743  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:17:36.743  7709  7709 E Zygote  : MountEmulatedStorage()
08-26 14:17:36.743  7709  7709 I libpersona: KNOX_SDCARD checking this for 10090
08-26 14:17:36.743  7709  7709 E Zygote  : v2
,08-26 14:17:36.743  7709  7709 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:36.743  7709  7709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:36.753  1016  1465 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7709 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-26 14:17:36.753  7709  7709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:36.753  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 14:17:36.753  7709  7709 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:36.753  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast,
,08-26 14:17:36.753  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-26 14:17:36.763  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{1f65789f token=android.os.BinderProxy@229eee2b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-26 14:17:36.763  1480  1480 D Launcher.HomeView: onStop
,08-26 14:17:36.763  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.763  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.763  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.763  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:36.773  1016  1475 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 14:17:36.773  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-26 14:17:36.773  1016  1029 I TactileAssist: enable value -1
08-26 14:17:36.773  1016  1029 I TactileAssist: internal enable value -1
08-26 14:17:36.773  1016  1029 I TactileAssist: intensity value -1
08-26 14:17:36.773  1016  1029 I TactileAssist: saveAppList value true
,08-26 14:17:36.773  1016  7720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:36.773  1016  1029 I TactileAssist: List of disabled apps :
,08-26 14:17:36.773  1016  1475 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6743 uid 10171
,08-26 14:17:36.773  7723  7723 E Zygote  : MountEmulatedStorage(),
08-26 14:17:36.773  7723  7723 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:36.773  7723  7723 E Zygote  : v2
08-26 14:17:36.773  7723  7723 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:36.773  7723  7723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:36.783  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-26 14:17:36.783  7723  7723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:36.783  7723  7723 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:36.783  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 14:17:36.783  1177  1177 I StatusBar: Icon Only
08-26 14:17:36.783  1177  1177 D PanelView: There is/are notification(s) 
,08-26 14:17:36.783  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-26 14:17:36.783  7709  7709 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:36.793  7709  7709 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:36.793  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:36.793  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.793  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.793  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:36.803  1882  1882 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 14:17:36.803  7739  7739 E Zygote  : MountEmulatedStorage()
,08-26 14:17:36.803  7739  7739 E Zygote  : v2
08-26 14:17:36.803  7739  7739 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:36.803  7739  7739 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:36.803  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:36.813  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:36.813  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:36.833  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7739 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-26 14:17:36.843  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1305c055 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147853
,08-26 14:17:36.843  7689  7689 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 14:17:36.853  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 14:17:36.853  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:36.853  7723  7723 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:36.853  7739  7739 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:36.853  7723  7723 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:36.863  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 14:17:36.863  1016  1055 D PackageManager: userId{-1}
08-26 14:17:36.863  1016  1055 D PackageManager: andCode{true}
,08-26 14:17:36.873  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 14:17:36.873  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.873  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.873  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.873  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:36.883  2878  7708 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-26 14:17:36.883  2878  7708 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-26 14:17:36.893  7709  7709 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 14:17:36.893  7709  7709 D elm:15121: ELMEngine.ELMEngine( context ).,
,08-26 14:17:36.893  7709  7709 D elm:15121: MDMBridge.setEnterpriseBridge(),
,08-26 14:17:36.903  7757  7757 E Zygote  : MountEmulatedStorage(),
08-26 14:17:36.903  7739  7739 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED,
08-26 14:17:36.903  7757  7757 E Zygote  : v2
08-26 14:17:36.903  7757  7757 I libpersona: KNOX_SDCARD checking this for 10003
08-26 14:17:36.903  7757  7757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:36.903  7757  7757 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:36.903  7757  7757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:36.913  1016  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7757 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 14:17:36.913  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-26 14:17:36.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.913  1016  1478 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 14:17:36.913  1016  1478 D SecContentProvider2: mCursor = null
08-26 14:17:36.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:36.923  7757  7757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:36.933   304   304 I art     : Explicit concurrent mark sweep GC freed 8703(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 20.816ms
,08-26 14:17:36.933  7757  7757 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:36.933  7757  7757 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:36.943   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.337ms
,08-26 14:17:36.963   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 17.591ms,
,08-26 14:17:36.973  7544  7560 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,08-26 14:17:36.983  7773  7773 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:36.983  7773  7773 E Zygote  : v2
08-26 14:17:36.983  7773  7773 I libpersona: KNOX_SDCARD checking this for 10048
08-26 14:17:36.983  7773  7773 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:36.983  1016  1028 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7773 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a,
08-26 14:17:36.983  7773  7773 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:17:36.983  1016  1465 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-26 14:17:36.983  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0,
,08-26 14:17:36.983  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:36.983  1016  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:36.983  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-26 14:17:36.993  7709  7709 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-26 14:17:36.993  1016  1077 D SecContentProvider2: uri = -1 selection = getSealedState
08-26 14:17:36.993  1016  1077 D SecContentProvider2: mCursor = null
08-26 14:17:36.993  7773  7773 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:36.993  7709  7709 D elm:15121: ElmAgentService : onCreate()
08-26 14:17:36.993  7773  7773 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 14:17:36.993  7739  7739 I PopupuiReceiver_KNOX: getSealedState : true
08-26 14:17:36.993  1016  1479 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-26 14:17:36.993  1016  1479 D SecContentProvider2: mCursor = null
,08-26 14:17:36.993  7739  7739 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-26 14:17:36.993  1016  1077 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-26 14:17:36.993  1016  1077 D SecContentProvider2: mCursor = null
08-26 14:17:36.993  7709  7779 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-26 14:17:37.003  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 14:17:37.003  7709  7779 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-26 14:17:37.003  7709  7779 D elm:15121: MDMBridge.getInstance()
08-26 14:17:37.003  7709  7779 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 14:17:37.003  7723  7723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-26 14:17:37.003  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:37.003  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:37.003  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:37.003  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:37.003  2878  2878 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-26 14:17:37.003  7739  7739 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-26 14:17:37.003  7739  7739 D PopupuiReceiver: Action package removed
,08-26 14:17:37.013  7709  7779 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 14:17:37.023  7785  7785 E Zygote  : MountEmulatedStorage()
08-26 14:17:37.023  7785  7785 E Zygote  : v2
08-26 14:17:37.023  7785  7785 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:37.023  7785  7785 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:37.023  7785  7785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 14:17:37.023  7785  7785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 14:17:37.023  7785  7785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:37.033  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 14:17:37.033  1016  1475 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-26 14:17:37.033  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-26 14:17:37.043  7773  7773 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:37.043  7773  7773 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:37.043  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:37.043  1016  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:37.043  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-26 14:17:37.053  7709  7709 D elm:15121: ElmAgentService : onDestroy().
08-26 14:17:37.053  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-26 14:17:37.053  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:37.053  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:37.053  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:37.053  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:37.053  7785  7785 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:37.053  7785  7785 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:37.063  7723  7806 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:37.063  7723  7806 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:37.063  7723  7806 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 14:17:37.063  7723  7806 W System.,err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:37.063  7723  7806 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-26 14:17:37.063  7723  7806 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:37.063  7723  7806 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:37.073  7807  7807 E Zygote  : MountEmulatedStorage()
08-26 14:17:37.073  7807  7807 E Zygote  : v2
08-26 14:17:37.073  7807  7807 I libpersona: KNOX_SDCARD checking this for 10145
08-26 14:17:37.073  7807  7807 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:37.073  7807  7807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:17:37.073  7807  7807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:17:37.073  7807  7807 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:17:37.073  1016  1029 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7807 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:37.073  1016  1029 I ActivityManager: Killing 7140:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-26 14:17:37.083  1016  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast

```
