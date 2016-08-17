#### Test 808075738e7a0be_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
,08-17 19:16:16.759   289   289 E SMD     : DCD OFF
08-17 19:16:16.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
08-17 19:16:16.999  6779  6779 D AndroidRuntime: 
08-17 19:16:16.999  6779  6779 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 19:16:17.009  6779  6779 D AndroidRuntime: CheckJNI is OFF
08-17 19:16:17.009  6779  6779 D AndroidRuntime: readGMSProperty: start
08-17 19:16:17.009  6779  6779 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:16:17.009  6779  6779 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:16:17.009  6779  6779 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:16:17.009  6779  6779 D AndroidRuntime: readGMSProperty: end
08-17 19:16:17.009  6779  6779 D AndroidRuntime: addProductProperty: start
--------- beginning of system
08-17 19:16:17.029  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-17 19:16:17.029  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 19:16:17.029  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:17.029  1015  1027 D BatteryService: stay LED for fully charged
08-17 19:16:17.029  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-17 19:16:17.029  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 19:16:17.029  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 19:16:17.029  1015  1015 I MotionRecognitionService: Plugged
08-17 19:16:17.029  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-17 19:16:17.039  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:17.039  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-17 19:16:17.039  3147  3147 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:17.039  3147  3258 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:17.059  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-17 19:16:17.059  1171  1171 D SViewCoverView: level :100 plugged : 2
08-17 19:16:17.059  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:17.059  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:17.059  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:17.129  6779  6779 E AffinityControl: AffinityControl: registerfunction enter
08-17 19:16:17.159  6779  6779 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 19:16:17.159  1015  1745 E PersonaManagerService: inState():  stateMachine is null !!
08-17 19:16:17.159  1015  1745 I PersonaManagerService: PersonaId don't exist
08-17 19:16:17.159  1015  1745 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 19:16:17.169  1015  1745 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:17.179  1015  1745 W ActivityManager: mDVFSHelper.acquire()
08-17 19:16:17.179  1015  1745 D FocusedStackFrame: Set to : 0
08-17 19:16:17.189  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:16:17.189  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 19:16:17.189  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:17.189  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:17.189  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:17.189  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:17.209  6789  6789 E Zygote  : MountEmulatedStorage()
08-17 19:16:17.209  6789  6789 E Zygote  : v2
08-17 19:16:17.209  6789  6789 I libpersona: KNOX_SDCARD checking this for 10171
08-17 19:16:17.209  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:17.209  6789  6789 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:17.209  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:16:17.209   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 19:16:17.209  6789  6789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:17.209  1015  1745 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6789 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:16:17.209  1015  1745 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 19:16:17.209  1015  1745 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:17.209  6789  6789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:17.219  6789  6789 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 19:16:17.219  1015  1745 D InputDispatcher: Focused application set to: xxxx
08-17 19:16:17.219  1015  1745 D InputDispatcher: Focus left window: 1495
08-17 19:16:17.219  6779  6779 D AndroidRuntime: Shutting down VM
08-17 19:16:17.219  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:17.219  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:17.229  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:17.239  6789  6789 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:17.239  1015  1028 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 19:16:17.239  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:16:17.259  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:16:17.269   259   441 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-17 19:16:17.269   259   439 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-17 19:16:17.279  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{df5103f token=android.os.BinderProxy@35c21b45 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 19:16:17.279  1495  1495 D Launcher: onTrimMemory. Level: 20
08-17 19:16:17.389  6789  6789 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-17 19:16:17.409  6789  6789 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 6567-6571)
08-17 19:16:17.409  6789  6789 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 19:16:17.429  6779  6779 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:16:17.439  6789  6789 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3759bde4}
08-17 19:16:17.439  6789  6789 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 19:16:17.449  6789  6789 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:16:17.489  6789  6789 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-17 19:16:17.489  6789  6789 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:17.499  6789  6789 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:16:17.529  6789  6789 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:17.529  6789  6789 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:17.529  6789  6789 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:17.529  6789  6789 I Adreno-EGL: Local Branch: 
08-17 19:16:17.529  6789  6789 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:17.529  6789  6789 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:17.529  6789  6789 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 19:16:17.609  6789  6789 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:16:17.619  6789  6789 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 19:16:17.619  6789  6789 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 19:16:17.629  6789  6789 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 19:16:17.629  6789  6789 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 19:16:17.759  6789  6789 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:17.769  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{384c27c8 u0 com.test.thalitest/.MainActivity t3}
08-17 19:16:17.769  6789  6789 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 19:16:17.779  6789  6789 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:16:17.779  6789  6789 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-17 19:16:17.789  6789  6789 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-17 19:16:17.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
08-17 19:16:17.799  6789  6789 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:17.799  6789  6789 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:17.869  6789  6831 D OpenGLRenderer: Render dirty regions requested: true
08-17 19:16:17.869  1015  3124 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:16:17.869  1015  3124 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:16:17.869  1015  3124 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 19:16:17.879  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:16:17.879  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:16:17.879  6789  6818 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-17 19:16:17.889  6789  6789 V ActivityThread: updateVisibility : ActivityRecord{3631fe44 token=android.os.BinderProxy@254070f1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-17 19:16:17.889  6789  6789 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:17.889  6789  6789 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:16:17.899   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-17 19:16:17.909  1015  1254 D InputDispatcher: Focus entered window: 6789
08-17 19:16:17.919  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:17.919  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:17.919  6789  6789 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-17 19:16:17.919  6789  6831 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 19:16:17.919  6789  6831 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-17 19:16:17.919  6789  6831 D OpenGLRenderer: Enabling debug mode 0
08-17 19:16:17.939  1015  3124 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 19:16:17.949  1171  1171 I StatusBar: Icon Only
08-17 19:16:17.949  1171  1171 D PanelView: There is/are notification(s) 
08-17 19:16:17.959  1015  1045 I ActivityManager: Displayed Component not be shown by security: +694ms (total +2s273ms)
08-17 19:16:17.959  1015  1045 W ActivityManager: mDVFSHelper.release()
08-17 19:16:17.959  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{384c27c8 u0 com.test.thalitest/.MainActivity t3} time:117128
08-17 19:16:17.959  6789  6789 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-17 19:16:17.959  6789  6789 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@254070f1 time:117129
08-17 19:16:17.969   259   439 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-17 19:16:17.969   259  1095 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-17 19:16:17.999  1015  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-17 19:16:18.029  1845  1845 I SamsungIME: getCurrentCandidateView
08-17 19:16:18.079  6789  6789 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6789
08-17 19:16:18.149  1845  1845 D SamsungIME: Dismiss ExpandCandiate
,08-17 19:16:18.299  1845  1845 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:18.339  1845  1845 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:18.349  1845  1845 I SamsungIME: KeybaordView init() : load resources
,08-17 19:16:18.369  6789  6789 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:16:18.379  1845  1845 I SamsungIME: getCurrentKeyboard
08-17 19:16:18.379  1845  1845 I SamsungIME: getTextKeyboard
,08-17 19:16:18.399  1845  1845 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 19:16:18.449  6789  6837 D jxcore_app_log: JniHelper::setJavaVM(0xb7f0b2b0), pthread_self() = -1203140288
,08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 19:16:18.459  6789  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86881ba added. We now have 1 listener(s)
,08-17 19:16:18.459  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-17 19:16:18.469  6789  6837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:16:18.469  6789  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:18.469  6789  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 19:16:18.469  6789  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ffe7861 added. We now have 1 listener(s)
,08-17 19:16:18.469  6789  6837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 19:16:18.479  6789  6837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:18.489  6789  6837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-17 19:16:18.489  6789  6837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:18.489  6789  6837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:18.489  6789  6837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:16:18.489  6789  6837 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:18.489  6789  6837 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:16:18.499  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:18.499  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:18.519  6789  6789 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:16:18.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:19.369  6789  6844 W jxcore-log: Initializing JXcore engine
08-17 19:16:19.369  6789  6844 W jxcore-log: JXcore engine is ready
,08-17 19:16:19.429  2014  2014 E audit   : type=1400 msg=audit(1471454179.429:205): avc:  denied  { ioctl } for  pid=6844 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 19:16:19.429  2014  2014 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:19.429  2014  2014 E audit   : type=1300 msg=audit(1471454179.429:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e4bd8f8 items=0 ppid=307 ppcomm=main pid=6844 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 19:16:19.429  2014  2014 E audit   : type=1320 msg=audit(1471454179.429:205): 
,08-17 19:16:19.439  6789  6844 W jxcore-log: Starting JXcore engine
,08-17 19:16:19.549  6789  6844 W jxcore-log: Platform android
08-17 19:16:19.549  6789  6844 W jxcore-log: 
08-17 19:16:19.549  6789  6844 W jxcore-log: Process ARCH arm
08-17 19:16:19.549  6789  6844 W jxcore-log: 
,08-17 19:16:19.759   289   289 E SMD     : DCD OFF
,08-17 19:16:19.789   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-17 19:16:19.809  6789  6844 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:16:19.809  6789  6844 I jxcore-log: 
,08-17 19:16:19.809  6789  6844 W jxcore-log: JXcore engine is started
08-17 19:16:19.809  6789  6837 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 19:16:19.819  6789  6789 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:16:20.839  1015  1093 V AlarmManager: waitForAlarm result :4
,08-17 19:16:20.849  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-17 19:16:20.859  2038  2038 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-17 19:16:20.889  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-17 19:16:20.889  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0,
,08-17 19:16:20.889  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.889  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.889  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:20.979  4806  4806 D ConnectivityManager: CallingUid : 10011, CallingPid : 4806
,08-17 19:16:20.989  1015  1489 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:16:20.989  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-17 19:16:20.989  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-17 19:16:20.989  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,08-17 19:16:20.989  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:16:21.039  4806  6847 W DriveInitializer: Background init thread started
,08-17 19:16:21.069   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-17 19:16:21.069   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:21.079  4806  6847 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-17 19:16:21.129  1015  3124 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:21.129  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.139  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.139  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.139  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.169  1015  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-17 19:16:21.169  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.179  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:21.179  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.179  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.179  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.179  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.189  4806  6847 W DriveInitializer: Background init thread ended
,08-17 19:16:21.209  4806  6855 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-17 19:16:21.209  4806  6855 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-17 19:16:21.239  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:16:21.269  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.279  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.279  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.369  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:21.369  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.379  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.379  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.379  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.409  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:21.409  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.409  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.409  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.409  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.459  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.469  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.469  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.469  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.499  1015  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.509  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.509  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.509  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.569  1015  1254 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.569  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.569  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.569  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.579  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:21.579  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.579  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.579  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:21.589  6860  6860 E Zygote  : MountEmulatedStorage()
,08-17 19:16:21.589  6860  6860 E Zygote  : v2
08-17 19:16:21.589  6860  6860 I libpersona: KNOX_SDCARD checking this for 10011
08-17 19:16:21.589  6860  6860 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:21.589  1015  1254 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6860 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-17 19:16:21.589  6860  6860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:21.599  6860  6860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:16:21.599  6860  6860 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:21.619  6860  6860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:21.619  6860  6860 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:21.639  6860  6860 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 19:16:21.639  6860  6860 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 19:16:21.669  6860  6860 I MultiDex: VM with version 2.1.0 has multidex support
,08-17 19:16:21.669  6860  6860 I MultiDex: install
08-17 19:16:21.669  6860  6860 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 19:16:21.709  6860  6860 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-17 19:16:21.769  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-17 19:16:21.769  6860  6860 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 19:16:21.779  6860  6860 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16c22fe0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-17 19:16:21.779  6860  6860 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-17 19:16:21.779  1015  1254 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.779  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.779  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.779  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.789  1015  1254 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.799  6860  6860 D ChimeraCfgMgr: Reading stored module config
,08-17 19:16:21.799  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.799  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.799  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.849  1015  1493 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:16:21.849  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 19:16:21.849  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.859  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:21.859  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.859  2038  2038 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=8ca2d1ea-14b4-4cb0-b377-a839ec7bc940
,08-17 19:16:21.869  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:16:21.869  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:16:21.899  1015  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:21.899  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:21.899  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.899  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:21.919  6860  6879 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-17 19:16:21.939  6860  6860 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 19:16:21.939  6860  6860 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 19:16:22.049   284   284 D WVCdm   : Instantiating CDM.
,08-17 19:16:22.049   284   692 I WVCdm   : CdmEngine::OpenSession
,08-17 19:16:22.049   284   692 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-17 19:16:22.059  4339  4397 I art     : Explicit concurrent mark sweep GC freed 2149(81KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 801us total 22.411ms
,08-17 19:16:22.079   284   692 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-17 19:16:22.099   284   692 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-17 19:16:22.149  6860  6869 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-17 19:16:22.159  6860  6869 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:22.159  6860  6869 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 19:16:22.159  6860  6869 I System.out: (HTTPLog)-Thread-1230-152093709: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-17 19:16:22.159  6860  6869 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:22.159   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:22.159   279   995 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-17 19:16:22.159   284   692 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-17 19:16:22.159   284   284 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-17 19:16:22.159   284   284 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-17 19:16:22.159   284   284 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-17 19:16:22.159   284   284 D WVCdm   : PrepareKeyRequest: nonce=2439629385
,08-17 19:16:22.179  1015  1487 I art     : Explicit concurrent mark sweep GC freed 36786(1935KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 3.049ms total 169.807ms
,08-17 19:16:22.209  6860  6869 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:22.209  6860  6869 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6860, getuid(): 10011
,08-17 19:16:22.249  2038  2205 W GCoreFlp: No location to return for getLastLocation()
,08-17 19:16:22.279  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:22.289  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:22.289  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:22.289  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.289  1015  3124 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:22.289  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:22.289  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:22.299  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.299  1015  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:22.299  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:22.299  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:22.299  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.339  4806  6856 D UdcContextInitService: registered all accounts: true
,08-17 19:16:22.339  2038  2210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:16:22.349  2038  2217 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-17 19:16:22.479  6860  6869 I qtaguid : Untagging socket 30
,08-17 19:16:22.579  2038  2217 I art     : Explicit concurrent mark sweep GC freed 53683(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 11MB/19MB, paused 1.354ms total 95.729ms
,08-17 19:16:22.599  1015  1254 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:16:22.609  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 19:16:22.609  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:22.609  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:22.609  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.639  1015  1493 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:16:22.639  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-17 19:16:22.649  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:22.649  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:22.649  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.649  2038  2217 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:22.659   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:22.659   279   995 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:16:22.659  2038  2217 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:22.659  2038  2217 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:22.689  2038  2217 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:22.709  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:22.759   289   289 E SMD     : DCD OFF
,08-17 19:16:22.959  6891  6891 I dex2oat : ----------------------------------------------------
08-17 19:16:22.959  6891  6891 I dex2oat : <SS>: S T A R T I N G . . .
08-17 19:16:22.959  6891  6891 I dex2oat : <SS>: Zip is absent. Canceled.
,08-17 19:16:22.959  6891  6891 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 19:16:23.039  6891  6891 I dex2oat : dex2oat took 74.063ms (threads: 4)
,08-17 19:16:23.049  6860  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:23.049  6860  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:23.049  6860  6869 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:23.049  6860  6869 I Adreno-EGL: Local Branch: 
08-17 19:16:23.049  6860  6869 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:23.049  6860  6869 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:23.049  6860  6869 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:23.129  6860  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:23.129  6860  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:23.129  6860  6869 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:23.129  6860  6869 I Adreno-EGL: Local Branch: 
08-17 19:16:23.129  6860  6869 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:23.129  6860  6869 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:23.129  6860  6869 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:23.459  6860  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-17 19:16:23.459  6860  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:23.459  6860  6869 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:23.459  6860  6869 I Adreno-EGL: Local Branch: 
08-17 19:16:23.459  6860  6869 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:23.459  6860  6869 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:23.459  6860  6869 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:23.549  2038  6858 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:23.549  2038  6858 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:23.549  2038  6858 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:23.589  2038  6858 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:23.619  1015  3359 D SSRM:n  : SIOP:: AP = 340
,08-17 19:16:23.719  2038  2217 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:16:23.729  2038  2217 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-17 19:16:23.729  2038  2217 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-17 19:16:22.419+0200, stopTime=2016-08-17 19:16:23.741+0200, duration=1322ms
,08-17 19:16:23.749  2038  6900 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:23.749   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:23.749   279   995 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:16:23.769  2038  6900 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:16:23.769  2038  6900 I qtaguid : Tagging socket 74 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:23.799   284   670 I WVCdm   : CdmEngine::CloseSession
,08-17 19:16:23.809  2038  6900 I qtaguid : Tagging socket 77 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:23.809   284   670 I WVCdm   : L3 Terminate.
,08-17 19:16:23.819  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:16:24.029  2038  6900 I qtaguid : Untagging socket 74
,08-17 19:16:24.059  1015  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:24.059  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-17 19:16:24.059  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.059  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.059  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.089  2038  2217 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-17 19:16:24.159  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.159  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.159  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.159  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.179  1015  1745 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.179  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.179  1015  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.179  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.229  1015  1745 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.229  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.229  1015  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.229  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.229  2038  6907 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:16:24.229  2038  6905 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:16:24.229  1015  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.229  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.229  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.229  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.259  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.259  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.259  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.259  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.259  2038  6907 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
08-17 19:16:24.259  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:24.259  2038  6905 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-17 19:16:24.259  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:24.259  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:24.259  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.289  1015  1254 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:24.289  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:24.289  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:24.289  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:24.289  2038  6907 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:16:24.289  2038  6905 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:16:24.289  2038  6905 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-17 19:16:24.309  2038  6905 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:16:24.379  1015  3124 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.409  2038  6905 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.419   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:24.419   279   995 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:16:24.419  2038  6905 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:24.419  2038  6905 I qtaguid : Tagging socket 86 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2038, getuid(): 10011
,08-17 19:16:24.469  2038  6905 I qtaguid : Tagging socket 89 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2038, getuid(): 10011
,08-17 19:16:24.709  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.729  2038  6905 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.729  2038  6905 I qtaguid : Tagging socket 86 with tag fffffca200000000{4294966434,0} for uid -1, pid: 2038, getuid(): 10011
,08-17 19:16:24.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:24.879  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.879  2038  6905 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.879  2038  6905 I qtaguid : Tagging socket 86 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2038, getuid(): 10011
,08-17 19:16:25.019  1015  1487 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:25.029  2038  6905 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:25.029  2038  6905 I qtaguid : Tagging socket 86 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2038, getuid(): 10011
,08-17 19:16:25.759   289   289 E SMD     : DCD OFF
,08-17 19:16:25.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:25.889  2038  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:25.889  2038  6899 I qtaguid : Tagging socket 74 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2038, getuid(): 10011
,08-17 19:16:26.139  2038  6899 I qtaguid : Untagging socket 74
,08-17 19:16:26.139  2038  2223 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-17 19:16:26.169  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:16:26.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:27.089  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:27.089  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:16:27.089  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:27.089  1015  1134 D BatteryService: stay LED for fully charged
,08-17 19:16:27.089  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:27.099  1015  1015 I MotionRecognitionService: Plugged
08-17 19:16:27.099  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:27.099  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:27.099  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:27.099  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:16:27.099  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:27.109  3147  3147 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:27.109  3147  3258 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:27.129  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 19:16:27.129  1171  1171 D SViewCoverView: level :100 plugged : 2
08-17 19:16:27.129  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:27.129  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:27.129  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:27.239  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-17 19:16:27.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:28.539  1015  1509 I ActivityManager: Killing 6493:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-17 19:16:28.759   289   289 E SMD     : DCD OFF,
,08-17 19:16:28.789   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:29.789   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-17 19:16:31.769   289   289 E SMD     : DCD OFF
,08-17 19:16:33.659  1015  3359 D SSRM:n  : SIOP:: AP = 340
,08-17 19:16:33.699  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 19:16:33.699  6789  6844 I jxcore-log: 
,08-17 19:16:33.709  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 19:16:33.709  6789  6844 I jxcore-log: 
,08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:33.709  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:33.719  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:33.719  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:16:33.719  6789  6844 I jxcore-log: 
,08-17 19:16:33.719  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:16:33.719  6789  6844 I jxcore-log: 
,08-17 19:16:34.209  6789  6844 D ExecuteNativeTests: Running unit tests
,08-17 19:16:34.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:16:34.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 added. We now have 2 listener(s)
,08-17 19:16:34.289  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:16:34.289  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:34.289  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:34.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:34.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 added. We now have 2 listener(s)
08-17 19:16:34.289  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:34.289  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:34.299  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.299  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:34.299  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:34.299  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:34.299  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.299  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:34.299  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:34.299  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:16:34.309  6789  6844 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-17 19:16:34.309  6789  6844 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:34.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:34.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:34.309  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:34.309  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.309  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.309  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:34.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 removed from the list
08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 removed from the list
,08-17 19:16:34.309  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 19:16:34.309  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.309  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.309  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.319  6789  6844 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 19:16:34.319  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:34.319  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.319  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:34.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.319  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.319  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.319  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.319  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.319  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.319  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.319  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.319  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.319  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.319  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:34.329  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.329  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.329  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.329  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.329  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.329  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.329  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.329  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.329  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.329  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.329  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.329  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.329  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.329  6789  6844 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:34.329  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.339  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:34.339  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.339  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:34.339  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:34.339  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:34.339  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:34.339  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.339  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:16:34.349  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:34.349  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:34.349  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:34.359  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:34.359  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:16:34.359  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:34.369  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:34.369  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:34.369  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:34.369  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:34.389  3147  3159 D BtGatt.GattService: registerClient() - UUID=d8ef2abf-2eee-4931-ac38-9a5211c4661f
,08-17 19:16:34.429  3147  3248 D BtGatt.GattService: onClientRegistered() - UUID=d8ef2abf-2eee-4931-ac38-9a5211c4661f, clientIf=6
,08-17 19:16:34.439  6789  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:34.439  3147  3157 D BtGatt.GattService: start scan with filters
,08-17 19:16:34.439  3147  3257 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:34.439  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:34.439  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:34.439  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:34.439  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:34.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:34.449  3147  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:34.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:34.449  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:34.449  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-17 19:16:34.459  3147  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:34.459  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.459  3147  3257 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:34.459  3147  3257 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:16:34.459  3147  3257 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:16:34.459  6789  6844 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:34.459  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-17 19:16:34.459  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.459  3147  3257 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:34.459  3147  3257 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:34.459  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:34.459  6789  6844 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:34.459  3147  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:34.459  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.469  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:34.469  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:34.469  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.469  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:16:34.469  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:34.469  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:16:34.469  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:16:34.469  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:16:34.469  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.469  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:34.469  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:34.469  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:34.479  3147  3159 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:34.479  3147  3351 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:34.479  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:16:34.479  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:34.479  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:34.479  3147  3257 D BtGatt.ScanManager: filter size is 1
08-17 19:16:34.479  3147  3257 D BtGatt.ScanManager: delete FilterIndex - 3
08-17 19:16:34.479  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:34.489  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.489  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.489  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.489  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:34.489  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.489  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.489  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.489  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.489  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:34.489  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.489  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.489  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:34.489  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.489  3147  3257 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:34.489  6789  6844 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:16:34.489  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:34.489  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:16:34.499  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.499  3147  3257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:34.499  3147  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:16:34.499  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.499  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:34.499  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:34.509  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:34.509  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.509  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.509  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:16:34.509  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:34.509  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 19:16:34.509  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.509  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:34.519  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:34.519  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:34.519  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:34.529  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:34.529  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:34.529  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:34.529  3147  3157 D BtGatt.GattService: registerClient() - UUID=eef20c76-c252-4737-9ce9-25d524c7578c
,08-17 19:16:34.569  3147  3248 D BtGatt.GattService: onClientRegistered() - UUID=eef20c76-c252-4737-9ce9-25d524c7578c, clientIf=6
,08-17 19:16:34.569  6789  6797 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:34.579  3147  3159 D BtGatt.GattService: start scan with filters
,08-17 19:16:34.579  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:34.579  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:34.579  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:34.579  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:16:34.579  3147  3257 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:34.579  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:34.579  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:34.579  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:34.579  3147  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:34.579  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.579  3147  3257 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:34.579  3147  3257 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:16:34.579  3147  3257 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 19:16:34.589  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:34.589  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:34.589  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.589  3147  3257 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:34.589  3147  3257 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:34.589  6789  6844 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:34.599  3147  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:34.599  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.599  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:34.599  6789  6844 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:34.599  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.599  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:34.599  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.599  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:16:34.599  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:34.599  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:34.599  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:16:34.599  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:16:34.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:34.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:34.609  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:34.609  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.609  3147  3351 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:34.609  3147  3257 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:34.609  3147  3257 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 19:16:34.609  3147  3157 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:34.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:34.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:34.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:34.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:34.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:34.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:34.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:34.619  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 19:16:34.619  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.619  3147  3257 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:34.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:16:34.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:34.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:34.619  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:34.619  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.619  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:34.629  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:34.629  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.629  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:34.629  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:16:34.629  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.629  3147  3257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:34.629  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.629  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:34.629  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.629  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.629  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.629  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.629  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.629  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:34.629  3147  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:34.629  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.629  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.629  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.629  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.639  6789  6844 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:16:34.639  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.639  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:34.639  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:34.639  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:34.649  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:34.649  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:34.649  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:34.649  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.649  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:34.649  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:34.649  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.649  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.659  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:34.659  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:34.659  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:34.659  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:34.659  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:34.669  3147  3351 D BtGatt.GattService: registerClient() - UUID=fd257f20-2399-47cf-9937-a91478a909e1
,08-17 19:16:34.709  3147  3248 D BtGatt.GattService: onClientRegistered() - UUID=fd257f20-2399-47cf-9937-a91478a909e1, clientIf=6
,08-17 19:16:34.709  6789  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:34.709  3147  3157 D BtGatt.GattService: start scan with filters
,08-17 19:16:34.709  3147  3257 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:34.709  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:34.709  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:34.709  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:16:34.709  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:34.709  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:34.719  3147  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:34.719  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:34.719  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.719  3147  3257 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:34.719  3147  3257 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:34.719  3147  3257 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 19:16:34.719  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:34.719  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:34.719  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:34.719  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.719  6789  6844 I io.jxcore.node.ConnectionHelper: start: OK
08-17 19:16:34.719  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.719  6789  6844 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:34.719  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.719  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:34.719  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.719  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:34.719  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:34.719  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:34.719  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:34.719  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:34.719  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:34.719  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:34.719  3147  3257 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:34.719  3147  3257 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:34.729  3147  3159 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:34.729  3147  3351 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:34.729  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:34.729  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:34.729  3147  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:16:34.729  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:34.729  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:34.729  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:34.739  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:16:34.739  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.739  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.739  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.739  6789  6844 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.739  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.739  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.739  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.739  6789  6844 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 19:16:34.739  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.739  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.739  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:34.739  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.739  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.739  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.739  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.739  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.739  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.739  6789  6844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 19:16:34.749  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.749  3147  3257 D BtGatt.ScanManager: filter size is 1
08-17 19:16:34.749  3147  3257 D BtGatt.ScanManager: delete FilterIndex - 5
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.749  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.749  3147  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:34.749  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.749  3147  3257 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:34.749  6789  6844 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 19:16:34.749  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.749  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 19:16:34.749  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:34.749  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:34.749  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:34.749  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.749  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.749  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.749  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.749  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.749  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:34.749  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.749  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:34.749  6789  6844 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-17 19:16:34.749  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:34.759  3147  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:34.759  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:34.759  3147  3257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:16:34.759  6789  6844 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:34.759  6789  6844 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:34.759  6789  6844 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:34.759  3147  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:34.759  3147  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:34.759  6789  6844 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 19:16:34.759  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.759  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.759  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.759  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.759  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.759  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:16:34.759  6789  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
08-17 19:16:34.759  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.759  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.759  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.759  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.759  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.759  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.759  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.759  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.769  6789  6919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
,08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
,08-17 19:16:34.769  6789  6844 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769   289   289 E SMD     : DCD OFF
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6918 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:16:34.769  6789  6844 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:34.769  6789  6844 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:34.769  6789  6844 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:34.769  6789  6844 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.769  6789,  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6918 D BluetoothSocket: connect(): myUserId = 0
08-17 19:16:34.769  6789  6918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.769  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.,769  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.769  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.769  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.769  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.769  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.769  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  3147  3159 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.779  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.779  6789  6918 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:34.779  6789  6789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 19:16:34.779  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:34.779  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  6789  6789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:34.779  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.779  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.779  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.779  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.779  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.779  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.779  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:34.779  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.779  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.779  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.779  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:34.779  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.779  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.779  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.789  6789  6844 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:16:34.789  6789  6844 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:34.789  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:34.789  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.789  6789  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.789  6789  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.789  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.789  6789  6789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 19:16:34.789  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.789  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.789  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.789  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.789  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:34.789  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:34.789  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:34.799  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.799  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.799  6789  6844 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df7e388 not in the list
08-17 19:16:34.799  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.799  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:34.799  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.799  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.799  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:34.799  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:34.799  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:34.799  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:34.799  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:34.799  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0f8121 not in the list
08-17 19:16:34.799  6789  6844 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:34.799  6789  6844 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:34.799  6789  6844 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 19:16:34.799  6789  6844 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:34.799  6789  6844 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:34.799  6789  6844 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 19:16:34.799  6789  6844 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:16:34.799  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:34.799  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24a64d1b added. We now have 2 listener(s)
08-17 19:16:34.799  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:34.799  6789  6844 D BluetoothAdapter: enable()
08-17 19:16:34.799  6789  6844 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 19:16:34.809  1015  1254 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:34.809  1015  1254 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:34.809  1015  1254 D SecContentProvider2: mCursor = null
08-17 19:16:34.809  1015  1254 D WifiService: setWifiEnabled: true pid=6789, uid=10171
08-17 19:16:34.809  1015  1254 W ActivityManager: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:34.819  1015  1254 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:34.819  1015  1254 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:34.819  1015  1254 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:34.819  1015  1254 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:34.819  1015  1254 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:34.819  1015  1254 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:34.819  1015  1254 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:34.819  1015  1254 D SettingsProvider: name = wifi_on
08-17 19:16:34.819  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:34.819  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42f3eb8 added. We now have 3 listener(s)
08-17 19:16:34.819  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:34.819  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:34.819  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2789f491 added. We now have 4 listener(s)
08-17 19:16:34.819  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:34.829  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:34.829  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17677ff6 added. We now have 5 listener(s)
08-17 19:16:34.829  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:34.829  1015  1461 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:34.829  1015  1461 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:34.829  1015  1461 D SecContentProvider2: mCursor = null
08-17 19:16:34.829  1015  1461 D WifiService: setWifiEnabled: false pid=6789, uid=10171
08-17 19:16:34.829  1015  1461 D SettingsProvider: name = wifi_on
08-17 19:16:34.839  6789  6844 D BluetoothAdapter: disable()
08-17 19:16:34.839  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 19:16:34.839  1362  1362 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:34.839  1362  1362 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-17 19:16:34.839  1362  1362 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:34.839  1362  1362 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:16:34.839  1015  1493 D SettingsProvider: name = bluetooth_on
,08-17 19:16:34.849  3147  3244 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 19:16:34.849  3147  3244 D BluetoothAdapterProperties: Setting state to 13,
08-17 19:16:34.849  3147  3244 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:34.849  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:34.849  3147  3244 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:34.849  3147  3244 D BluetoothAdapterService: updateAdapterState state is 13
08-17 19:16:34.849  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:34.849  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:34.849  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:34.849  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:34.849  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:34.849  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:34.859  3147  3147 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
08-17 19:16:34.859  3147  3244 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:34.859  3147  3244 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:16:34.859  3147  3244 D BluetoothAdapterService: terminating service from this receiver
08-17 19:16:34.859  3147  3147 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38da5636, channel: 19, state: LISTENING
08-17 19:16:34.859  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:16:34.859  3147  3147 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38da5636, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@60e795e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1eff5937mSocket: android.net.LocalSocket@3771eea4 impl:android.net.LocalSocketImpl@910c40d fd:FileDescriptor[74]
08-17 19:16:34.859  3147  3147 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3771eea4 impl:android.net.LocalSocketImpl@910c40d fd:FileDescriptor[74]
08-17 19:16:34.859  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:34.859  1015  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:34.859  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:34.859  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.859  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:34.859  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:34.859  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:34.859  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:34.859  3147  3244 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:16:34.859  3147  3244 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:16:34.859  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:34.869  3894  3894 D BluetoothPbap: Proxy object disconnected
08-17 19:16:34.869  3894  3894 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:34.869  3147  3244 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.879  3147  3248 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:34.879  3147  3248 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:34.879  1362  1362 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,08-17 19:16:34.879  3147  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:16:34.879  1015  1123 D WifiP2pService: InactiveState{ what=147461 }
08-17 19:16:34.879  3147  3244 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-17 19:16:34.879  1015  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:34.879  1015  1123 D WifiP2pService: DefaultState{ what=147461 }
08-17 19:16:34.879  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 19:16:34.879  3147  3244 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:16:34.879  3147  3244 E bt-btif : cmd socket is not created
08-17 19:16:34.879  3147  5241 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 19:16:34.879  6789  6918 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15f58e64, channel: -1, state: INIT
08-17 19:16:34.879  6789  6918 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15f58e64, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304848cd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3083a582mSocket: android.net.LocalSocket@9074493 impl:android.net.LocalSocketImpl@2baf2cd0 fd:FileDescriptor[106]
08-17 19:16:34.879  6789  6918 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9074493 impl:android.net.LocalSocketImpl@2baf2cd0 fd:FileDescriptor[106]
08-17 19:16:34.879  6789  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
,08-17 19:16:34.879  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:34.879  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:34.879  3147  3244 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 19:16:34.889  3147  3271 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 19:16:34.889  3147  3271 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 19:16:34.889  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:34.889  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:34.889  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.889  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:34.889  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:34.889  3147  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:34.899  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:34.899  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:34.909  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:34.909  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:34.909  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:34.919  1171  1171 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:34.919  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:34.919  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:34.919  1845  1845 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:34.919  1015  1254 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:34.919  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:34.919  3147  3147 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@be651d3, channel: 5, state: LISTENING
,08-17 19:16:34.919  3147  3147 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@be651d3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39d8813f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a315110mSocket: android.net.LocalSocket@30129409 impl:android.net.LocalSocketImpl@28f9f60e fd:FileDescriptor[76]
,08-17 19:16:34.919  3147  3147 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30129409 impl:android.net.LocalSocketImpl@28f9f60e fd:FileDescriptor[76]
,08-17 19:16:34.929  1015  1745 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:34.929  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:34.929  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:34.929  3147  3147 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:34.929  3147  3147 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@383a382f, channel: 12, state: LISTENING
08-17 19:16:34.929  3147  3147 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@383a382f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c53bd1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11426e3cmSocket: android.net.LocalSocket@154767c5 impl:android.net.LocalSocketImpl@1863651a fd:FileDescriptor[81]
08-17 19:16:34.929  3147  3147 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@154767c5 impl:android.net.LocalSocketImpl@1863651a fd:FileDescriptor[81]
,08-17 19:16:34.929  3147  5241 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:34.939  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.939  1015  3124 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:34.939  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:34.939  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:34.939  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:34.939  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:34.939  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:34.939  3147  3147 V BluetoothOppManager: cleanUp...
,08-17 19:16:34.949  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:34.949  1015  1745 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:16:34.949  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:34.949  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:34.949  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:34.949  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:34.959  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:34.959  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:34.969  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:34.969  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:16:34.969  1015  1493 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:16:34.969  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:34.969  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:34.969  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:34.969  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:34.989  6926  6926 E Zygote  : MountEmulatedStorage()
,08-17 19:16:34.989  6926  6926 E Zygote  : v2
08-17 19:16:34.989  6926  6926 I libpersona: KNOX_SDCARD checking this for 10055
08-17 19:16:34.989  6926  6926 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:34.989  6926  6926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:34.989  1015  1493 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6926 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-17 19:16:34.989  6926  6926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:34.989  6926  6926 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:35.019  6926  6926 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:35.019  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
08-17 19:16:35.019  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:35.019  6926  6926 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:35.029   279   999 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:35.039  2038  3031 V NativeCrypto: Read error: ssl=0xb84088b0: I/O error during system call, Connection timed out
,08-17 19:16:35.039  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:35.039  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:35.039  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.039  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.039  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.039  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:35.039  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:35.039  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:35.039  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:35.039  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-17 19:16:35.039  2038  3031 V NativeCrypto: SSL shutdown failed: ssl=0xb84088b0: I/O error during system call, Broken pipe
,08-17 19:16:35.049  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:35.049  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:16:35.049  2038  3031 E GCM     : Wifi connection closed with errorCode 20
08-17 19:16:35.049  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-17 19:16:35.049  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:16:35.049  1015  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-17 19:16:35.049  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.049  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.049  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 19:16:35.049  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.049  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-17 19:16:35.049  1015  1724 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:35.059  1015  1724 I qtaguid : Tagging socket 349 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,08-17 19:16:35.059  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:16:35.059  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.059  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:35.059  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:35.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.059  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:35.059  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.059  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:16:35.059  1015  1724 I qtaguid : Untagging socket 349
08-17 19:16:35.059  1015  1724 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:35.069  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:35.069  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-17 19:16:35.069  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:35.079  1015  1123 D WifiP2pService: P2pDisablingState
,08-17 19:16:35.079  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 19:16:35.079  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:16:35.079  1015  1123 D WifiP2pService: p2p socket connection lost
08-17 19:16:35.079  1015  1123 D WifiP2pService: P2pDisabledState
08-17 19:16:35.079  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 19:16:35.079  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-17 19:16:35.079  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:35.079  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:16:35.079  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:35.079  1015  1045 D WifiDisplayController: disconnect
08-17 19:16:35.079  1015  1045 D WifiDisplayController: updateConnection
08-17 19:16:35.079  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:35.079  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 19:16:35.079  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:35.079  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:35.079  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:35.079  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:35.089  3147  3271 W bt-l2cap: btif_mce_execute_service enable:0
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:35.089  3147  3271 W bt-btif : ag scb idx 1 not allocated
08-17 19:16:35.089  3147  3271 W bt-btif : ag scb idx 2 not allocated
08-17 19:16:35.089  3147  3271 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 19:16:35.089  3147  3339 I bt_userial_mct: exiting userial_read_thread
08-17 19:16:35.089  3147  3339 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:16:35.089  3147  3248 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:16:35.089  3147  3274 I bt_vendor: hw_epilog_process
,08-17 19:16:35.089  3147  3248 D bt_userial_mct: userial_close
08-17 19:16:35.089  3147  3248 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 19:16:35.089  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:35.109  6926  6926 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:16:35.119  1015  1489 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:35.119  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:35.149  6926  6926 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 19:16:35.149  6926  6926 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:16:35.149  6926  6926 D UserAnalysis: Create SecureDbHelper
,08-17 19:16:35.159  6926  6926 D IntelligenceServiceApplication: onCreate()
,08-17 19:16:35.159  1015  1509 I ActivityManager: Killing 6538:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-17 19:16:35.169  1015  1745 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 19:16:35.169  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.169  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.169  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.169  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.169  6926  6926 D IntelligenceServiceApplication: no applications having user consent for prediction
08-17 19:16:35.169  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 19:16:35.169  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:35.189   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-17 19:16:35.189   279   995 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 19:16:35.189  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 19:16:35.189  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.189  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 19:16:35.189  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:35.189  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:35.189  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:35.189  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 19:16:35.189  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 19:16:35.189  1015  1745 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6950 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:16:35.189  6950  6950 E Zygote  : MountEmulatedStorage()
08-17 19:16:35.189  6950  6950 E Zygote  : v2
08-17 19:16:35.189   279   999 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:35.189  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-17 19:16:35.199  6926  6926 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-17 19:16:35.199  1015  1126 V NetworkStats: performPollLocked() took 8ms
08-17 19:16:35.199  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.199  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-17 19:16:35.199  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:35.199  6950  6950 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:16:35.199  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:35.199  6950  6950 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:35.199  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.199  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:16:35.199  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.199  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 19:16:35.199  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.199  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 19:16:35.199  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.199  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.199  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.199  1171  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 19:16:35.199  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:16:35.199  1362  1362 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:35.199  6950  6950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:35.199  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 19:16:35.199  1015  1724 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:35.199  6926  6926 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-17 19:16:35.199  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:16:35.199  1471  1471 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-17 19:16:35.199  1471  1471 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:16:35.209  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 19:16:35.209  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 19:16:35.209  6950  6950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:35.209  6950  6950 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:35.209  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:35.209  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:35.209  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.209  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.209  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.209  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:35.219  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:35.219  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:35.219  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.219  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.219  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.219  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.219  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:16:35.219  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:35.219  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:35.219  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:35.219  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:35.219  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-17 19:16:35.219  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:35.219  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:35.219  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:35.219  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:35.219  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:35.219  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:35.219  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:35.229  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 19:16:35.229  1171  1171 D HotspotTile: onReceive : 0, 0
08-17 19:16:35.229  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:16:35.229  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 19:16:35.229  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:35.229  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:35.229  1015  1121 V NetworkStats: updateIfacesLocked()
08-17 19:16:35.229  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.229  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:35.229  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:16:35.229  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:35.229  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:35.229  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:35.229  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-17 19:16:35.229  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:35.239  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:35.239  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.239  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.239  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.239  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-17 19:16:35.239  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:16:35.239  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:16:35.239  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:16:35.239  1171  1171 D StatusBar.NetworkController: updateDataNetType()
08-17 19:16:35.239  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:16:35.239  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:16:35.239  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:35.239  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:35.239  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:35.239  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 19:16:35.249  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.249  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:35.249  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:35.249  6950  6950 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:35.249  6950  6950 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:35.279  6789  6789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:16:35.289  1362  1362 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:35.299  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.309  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.309  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.309  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-17 19:16:35.309  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.309  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-17 19:16:35.309  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.319  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-17 19:16:35.319  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.319  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.319  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.319  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.319  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.329  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.329  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.329  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.329  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-17 19:16:35.329  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.329  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-17 19:16:35.329  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.329  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-17 19:16:35.339  3147  3248 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:35.339  3147  3248 I bt_vendor: bluetooth satus is on
08-17 19:16:35.339  3147  3248 I bt_vendor: bt-vendor : resetting BT status
08-17 19:16:35.339  3147  3248 I bt_vendor: Starting hciattach daemon
08-17 19:16:35.339  3147  3248 I bt_vendor: try to set false
,08-17 19:16:35.339  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:35.339  1362  1362 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 19:16:35.339  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:35.339  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:35.339  3147  3248 I bt_vendor: Starting hciattach daemon
08-17 19:16:35.339  3147  3248 I bt_vendor: try to set false
,08-17 19:16:35.339  3147  3248 I bt_vendor: cleanup
08-17 19:16:35.339  3147  3271 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 19:16:35.339  3147  3248 I GKI_LINUX: GKI_exit_task 0 done
08-17 19:16:35.339  3147  3248 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 19:16:35.339  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:35.339  3147  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 19:16:35.339  3147  3244 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:35.339  3147  3244 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 19:16:35.339  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:35.339  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:35.339  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:16:35.339  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.339  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 19:16:35.339  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.339  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.339  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.339  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:35.339  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:35.339  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:35.339  3147  3147 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:35.339  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:35.339  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:35.339  3147  3147 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:16:35.349  3147  3147 D BtGatt.GattService: stop()
08-17 19:16:35.349  3147  3147 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 19:16:35.349  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.349  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.349  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:35.349  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.349  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.349  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:35.349  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:35.349  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:35.349  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:35.349  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:35.349  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:35.349  1015  1745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.349  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.349  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.349  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.349  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:35.349  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.349  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 19:16:35.349  3147  3147 D HeadsetService: Received stop request...Stopping profile...
08-17 19:16:35.349  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:35.349  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.349  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 19:16:35.349  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:35.359  1015  3124 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.359  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.359  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:35.359  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:35.359  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.359  1015  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.359  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:35.359  3894  3894 D HeadsetProfile: Bluetooth service disconnected
08-17 19:16:35.359  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:35.359  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:35.359  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:35.359  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:35.359  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.359  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.359  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.359  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.359  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:35.359  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:35.359  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:35.359  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:35.359  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.359  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.359  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.359  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:35.359  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:35.369  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-17 19:16:35.359  1362  1362 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 19:16:35.369  1015  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.359  1362  1362 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:35.369  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 19:16:35.359  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.359  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.359  1362  1362 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-17 19:16:35.359  1362  1362 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:35.359  1362  1362 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:35.369  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.369  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.369  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 19:16:35.369  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:35.369  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.369  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.369  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:35.369  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.369  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:35.369  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:35.369  1015  1254 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:35.369  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.369  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.369  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.369  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:35.369  1015  1129 E Tethering: No numeric data
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:35.369  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:35.369  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:35.369  1015  1129 D Tethering: clearTetheredNotification()
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService,
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:35.369  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.369  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:35.379  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:35.369  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:35.369  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.369  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:35.369  3147  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:35.369  3147  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:35.379  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.379  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:35.379  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:35.379  3147  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:35.379  3147  3244 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 19:16:35.379  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-17 19:16:35.379  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:35.379  1171  1171 D HotspotTile: updateTetherState():false, false
,08-17 19:16:35.379  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-17 19:16:35.379  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:35.379  3147  3147 D A2dpService: Received stop request...Stopping profile...
08-17 19:16:35.379  3147  3261 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:35.379  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:35.379  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:35.379  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.389  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:35.389  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:16:35.389  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:35.389  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:35.389  3147  3147 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:35.389  3894  3894 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:35.389  3894  3894 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:35.389  3147  3147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:16:35.389  3147  3147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:16:35.389  3147  3147 D HidService: Received stop request...Stopping profile...
08-17 19:16:35.389  3147  3147 D HidService: Stopping Bluetooth HidService
08-17 19:16:35.389  3147  3147 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:35.389  3147  3147 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:35.389  3147  3147 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:35.389  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.389  3894  3894 D BluetoothInputDevice: Proxy object disconnected
08-17 19:16:35.389  3894  3894 D HidProfile: Bluetooth service disconnected
,08-17 19:16:35.389  3147  3147 D HealthService: Received stop request...Stopping profile...
08-17 19:16:35.389  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.389  3147  3147 D PanService: Received stop request...Stopping profile...
08-17 19:16:35.389  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.389  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:35.389  3894  3894 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:35.389  3894  3894 D PanProfile: Bluetooth service disconnected
08-17 19:16:35.389  3147  3147 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.399  3894  3894 D BluetoothMap: Proxy object disconnected
08-17 19:16:35.399  3894  3894 D MapProfile: Bluetooth service disconnected
,08-17 19:16:35.399  3147  3147 D SapService: Received stop request...Stopping profile...
08-17 19:16:35.399  3147  3147 D SapService: Stopping Bluetooth SapService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:35.399  3147  3147 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 19:16:35.399  3147  3262 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 19:16:35.399  3147  3147 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:35.399  3147  3147 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:35.399  3147  3147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:35.399  3147  3147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:35.399  3147  3147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 19:16:35.399  3894  3894 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:16:35.399  3894  3894 D SapProfile: Bluetooth service disconnected
08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:35.399  3147  3147 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-17 19:16:35.399  3147  3147 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:16:35.399  3147  3147 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:35.399  3147  3147 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:35.409  3147  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 19:16:35.409  3147  3244 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:35.409  3147  3244 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 19:16:35.409  3147  3244 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:35.409  3147  3244 D BluetoothAdapterService: updateAdapterState state is 10
08-17 19:16:35.409  1471  1838 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.409  1471  1838 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:35.409  3147  3244 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:35.409  3147  3244 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:16:35.409  3147  3244 I BluetoothAdapterState: Entering OffState
,08-17 19:16:35.409   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:35.409   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:35.409  3147  3159 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-17 19:16:35.409  6950  6987 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:35.409  1439  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.409  1439  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:35.419  3894  3902 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 19:16:35.419  3894  3902 D Bluetoothsap: Unbinding service...
,08-17 19:16:35.419  3147  3157 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:35.419  3147  3157 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:35.419   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb78a67c8
08-17 19:16:35.419   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-17 19:16:35.419  1455  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.419  1455  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:35.419   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 19:16:35.419  6789  6797 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.419  6789  6797 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:35.419  6789  6797 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:16:35.419  6789  6797 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:16:35.419  6789  6797 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 19:16:35.419  6789  6797 D BluetoothLeScanner: Exiting stopAllScan
08-17 19:16:35.419   274   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215666040)
,08-17 19:16:35.419  3894  3902 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.419  3894  3902 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:35.419   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:35.419   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:35.419  3894  3905 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:35.429  6950  6987 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:35.449  3894  3902 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:35.449  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.449  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:35.449  3894  3905 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:35.449  2038  2215 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.449  2038  2215 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:35.449  3894  3902 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:35.449  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:35.449  1171  1800 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:35.449  1171  1800 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:35.459  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 19:16:35.459  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:35.469  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:35.469  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,08-17 19:16:35.469  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:35.479  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:35.479  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:35.479  1171  1756 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:35.479  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:35.479  1171  1171 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:35.479  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:35.479  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:35.479  1171  1756 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:35.479  1845  1845 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:35.479  1015  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:35.489   274   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-17 19:16:35.489   274   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 19:16:35.489   274   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215666040) wakelock released: 1, error no: 0
08-17 19:16:35.489   274   347 I rmt_storage: 
,08-17 19:16:35.489  2038  2221 D BluetoothAdapter: 121746621: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:35.489  1015  3124 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:16:35.489  2038  2221 D BluetoothAdapter: 121746621: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:35.489   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb78a67c8
08-17 19:16:35.489  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:35.489  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:35.489  3147  3248 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 19:16:35.489  3147  3147 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:16:35.489  3147  3147 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 19:16:35.489  1015  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:35.489  3147  3147 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 19:16:35.489  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:35.489  1015  1461 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:35.489  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:35.489  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:35.489  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:35.489  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:35.499  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:35.499  3147  3147 I art     : System.exit called, status: 0
08-17 19:16:35.499  3147  3147 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 19:16:35.509  1362  1362 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:35.549  1015  1461 I ActivityManager: Process com.android.bluetooth (pid 3147)(adj 0) has died(25,718)
,08-17 19:16:35.559  1362  1362 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 19:16:35.559  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:35.559  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:35.559  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.619  6950  6950 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:35.619  6950  6950 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:35.629  1015  1745 I ActivityManager: Killing 6586:com.samsung.android.sm/1000 (adj 15): empty #21
08-17 19:16:35.629  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:35.639  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 19:16:35.639  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:35.639  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:35.639  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.639  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:35.639  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:35.639  1617  1617 I Hs20UtilService: Starting #8
08-17 19:16:35.639  1617  1636 I Hs20UtilService: Message received 5007
08-17 19:16:35.649  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:35.649  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:35.649  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:35.659  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:35.659  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:35.659  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:35.659  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:35.669  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 19:16:35.669  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 19:16:35.669  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:35.679  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:35.679  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.679  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.679  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.679  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:35.679  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:35.679  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-17 19:16:35.679  6950  6997 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-17 19:16:35.679  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:35.679  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:35.679  1171  1171 D HotspotTile: onReceive : 1, 0
08-17 19:16:35.679  2038  2221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:16:35.679  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:35.689  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:35.689  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:35.689  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:16:35.689  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:35.689  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:35.689  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:35.689  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:35.689  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:35.689  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:35.699  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-17 19:16:35.699  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.699  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.699  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.699  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.709  7003  7003 E Zygote  : MountEmulatedStorage()
08-17 19:16:35.709  7003  7003 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:16:35.709  7003  7003 E Zygote  : v2
08-17 19:16:35.709  7003  7003 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:35.709  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7003 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:35.709  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:35.719  1015  3124 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:35.719  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:35.719  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.719  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:35.719  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:35.719  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:35.719  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:35.729  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-17 19:16:35.739  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:35.739  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:35.749  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:35.749  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:35.759  7003  7003 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:35.769  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:35.779  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:35.799  7003  7003 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:35.799  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:16:35.809  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.809  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.809  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.809  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.819  7019  7019 E Zygote  : MountEmulatedStorage()
,08-17 19:16:35.819  7019  7019 E Zygote  : v2
08-17 19:16:35.819  7019  7019 I libpersona: KNOX_SDCARD checking this for 10065
08-17 19:16:35.819  7019  7019 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:35.819  7019  7019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:35.819  7019  7019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:35.819  1015  1487 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7019 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:35.819  1015  1487 I ActivityManager: Killing 6560:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-17 19:16:35.819  7019  7019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:35.839  7019  7019 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:35.839  7019  7019 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:35.849  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:35.859  7019  7019 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:35.869  1015  1493 I ActivityManager: Killing 6610:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-17 19:16:35.869  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:35.869  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:35.869  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-17 19:16:35.869  1015  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-17 19:16:35.869  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.869  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.869  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:35.869  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:35.889  1015  1493 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7034 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 19:16:35.889  7034  7034 E Zygote  : MountEmulatedStorage()
08-17 19:16:35.889  7034  7034 E Zygote  : v2
08-17 19:16:35.889  7034  7034 I libpersona: KNOX_SDCARD checking this for 10102
08-17 19:16:35.889  7034  7034 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:35.889  7034  7034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:35.889  7034  7034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:35.889  7034  7034 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:35.899  7034  7034 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:35.899  7034  7034 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:35.929  7034  7034 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 19:16:36.159  7034  7055 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-17 19:16:36.159  7034  7055 I Babel_SMS: MmsConfig.loadMmsSettings
08-17 19:16:36.159  7034  7055 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-17 19:16:36.159  7034  7055 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 19:16:36.189  7034  7055 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-17 19:16:36.189  7034  7055 I Babel_SMS: MmsConfig.loadFromResources
,08-17 19:16:36.199  7034  7055 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 19:16:36.199  7034  7055 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-17 19:16:36.199  1015  1042 D Tethering: interfaceRemoved wlan0
08-17 19:16:36.199  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:36.199  1015  1461 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 19:16:36.199  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 19:16:36.199  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.199  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:36.199  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:36.219  7034  7034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:36.229  7034  7034 I Babel_Crash: startup - clean
,08-17 19:16:36.249  1015  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:36.249  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:36.249  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.249  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.249  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:36.259  1617  1617 I Hs20UtilService: Starting #9
,08-17 19:16:36.259  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:36.259  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:36.259  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:36.259  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:36.259  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:36.259  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:36.259  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:36.259  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:36.269  1015  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:36.269  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:36.269  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.279  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:36.279  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:36.279  1617  1617 I Hs20UtilService: Starting #10
08-17 19:16:36.279  1617  1636 I Hs20UtilService: Message received 5011
08-17 19:16:36.279  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:36.279  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:36.279  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:36.279  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:36.289  1015  1042 D Tethering: interfaceRemoved p2p0
08-17 19:16:36.289  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:36.289  7034  7034 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:36.289  7034  7034 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:36.299  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.299  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.299  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.299  7034  7034 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:16:36.299  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.299  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.299  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.299  7034  7034 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-17 19:16:36.309  7034  7034 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-17 19:16:36.309  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.309  7034  7034 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 19:16:36.309  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.309  7034  7034 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 19:16:36.309  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.309  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.319  7034  7034 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:16:36.319  7034  7034 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:36.319  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.319  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.319  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.319  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.329  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.329  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.329  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.329  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-17 19:16:36.329  7034  7034 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:36.339  7034  7034 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:36.339  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.339  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.339  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.339  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.349  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.349  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.349  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:36.349  7034  7034 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 19:16:36.349  7034  7034 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:36.349  7034  7034 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:36.349  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:36.349  7034  7034 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-17 19:16:36.349  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:36.349  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:36.349  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.349  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:36.349  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-17 19:16:36.349  7034  7034 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 19:16:36.359  7034  7034 W VideoCapabilities: Unsupported mime video/mp43
,08-17 19:16:36.359  7034  7034 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 19:16:36.359  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:36.359  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:36.369  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:36.369  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:36.369  7034  7034 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 19:16:36.369  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 19:16:36.369  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.379  7059  7059 E Zygote  : MountEmulatedStorage()
08-17 19:16:36.389  7059  7059 E Zygote  : v2
08-17 19:16:36.389  7059  7059 I libpersona: KNOX_SDCARD checking this for 1002
08-17 19:16:36.389  7059  7059 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:36.389  7059  7059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.389  7059  7059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:36.389  1015  1028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7059 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:16:36.389  7059  7059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.399  7034  7034 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 19:16:36.419  7059  7059 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:36.419  7059  7059 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.419  7034  7034 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 19:16:36.419  7034  7034 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 19:16:36.419  7034  7034 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:36.429  7034  7034 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:36.429  1015  1134 I ActivityManager: Killing 6657:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-17 19:16:36.439  7034  7034 I vclib   : onServiceConnected
,08-17 19:16:36.439  7059  7059 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 19:16:36.439  7059  7059 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:36.459  7059  7059 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding HidService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding HealthService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding PanService
08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding SapService
08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 19:16:36.499  7059  7059 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 19:16:36.509  7059  7059 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 19:16:36.509  7059  7059 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:16:36.509  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:16:36.509  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.509  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.509  1015  1028 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1028 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.509  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.509  1015  1028 D SettingsProvider: ret = -1
08-17 19:16:36.509  1015  1461 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 19:16:36.509  1015  1461 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.509  1015  1461 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:36.509  1015  1461 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1461 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.509  1015  1461 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.509  1015  1461 D SettingsProvider: ret = -1
,08-17 19:16:36.509  1015  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 19:16:36.509  1015  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:36.509  1015  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.509  1015  1493 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1493 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:36.509  1015  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:36.509  1015  1493 D SettingsProvider: ret = -1
,08-17 19:16:36.509  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 19:16:36.509  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.509  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.509  1015  1134 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.509  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.509  1015  1134 D SettingsProvider: ret = -1
,08-17 19:16:36.509  1015  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:16:36.509  1015  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.509  1015  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.509  1015  1509 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1509 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.509  1015  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.509  1015  1509 D SettingsProvider: ret = -1
,08-17 19:16:36.509  1015  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:16:36.509  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.509  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.509  1015  1489 D SettingsProvider: selectionArgs: false
08-17 19:16:36.509  1015  1489 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.509  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.509  1015  1489 D SettingsProvider: ret = -1
,08-17 19:16:36.519  1015  1254 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:16:36.519  1015  1254 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:36.519  1015  1254 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  1254 D SettingsProvider: selectionArgs: false
08-17 19:16:36.519  1015  1254 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  1254 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.519  1015  1254 D SettingsProvider: ret = -1
,08-17 19:16:36.519  1015  1745 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-17 19:16:36.519  1015  1745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.519  1015  1745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  1745 D SettingsProvider: selectionArgs: false
,08-17 19:16:36.519  1015  1745 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  1745 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.519  1015  1745 D SettingsProvider: ret = -1
,08-17 19:16:36.519  1015  1745 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:36.519  1015  1745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.519  1015  1745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  1745 D SettingsProvider: selectionArgs: false
08-17 19:16:36.519  1015  1745 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  1745 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 19:16:36.519  1015  1745 D SettingsProvider: ret = -1
08-17 19:16:36.519  1015  3124 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:36.519  1015  3124 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:36.519  1015  3124 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  3124 D SettingsProvider: selectionArgs: false
08-17 19:16:36.519  1015  3124 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  3124 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:36.519  1015  3124 D SettingsProvider: ret = -1
,08-17 19:16:36.519  1015  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:16:36.519  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.519  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  1487 D SettingsProvider: selectionArgs: false
08-17 19:16:36.519  1015  1487 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.519  1015  1487 D SettingsProvider: ret = -1
08-17 19:16:36.519  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:16:36.519  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:36.519  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:36.519  1015  1028 D SettingsProvider: selectionArgs: false
08-17 19:16:36.519  1015  1028 D SettingsProvider: selectionArgs: 1002
08-17 19:16:36.519  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:36.519  1015  1028 D SettingsProvider: ret = -1
,08-17 19:16:36.529  1015  1027 I ActivityManager: Killing 6676:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-17 19:16:36.539  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:36.539  1015  1509 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:36.539  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:36.539  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.539  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:36.539  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:36.549  2038  7075 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:36.549  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:36.549  1015  3124 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:36.559  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.559  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:36.559  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:36.569  1015  1745 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:36.569  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:36.569  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:36.569  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:36.569  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:36.569  1617  1617 I Hs20UtilService: Starting #11
,08-17 19:16:36.569  1617  1636 I Hs20UtilService: Message received 5011
,08-17 19:16:36.569  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:36.569  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:36.569  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:36.579  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:36.579  1015  1254 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:36.579  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:36.579  1015  1254 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:36.579  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:36.589  2038  7075 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:16:36.589  1015  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:16:36.589  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.589  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.589  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.589  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.609  7076  7076 E Zygote  : MountEmulatedStorage(),
08-17 19:16:36.609  7076  7076 E Zygote  : v2
08-17 19:16:36.609  7076  7076 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:36.609  7076  7076 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:36.609  7076  7076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.609  7076  7076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:36.609  1015  1461 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7076 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:36.609  7076  7076 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.629  7076  7076 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:36.629  7076  7076 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.659  7076  7076 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-17 19:16:36.659  7076  7076 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:16:36.659  7076  7076 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 19:16:36.669  7076  7076 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-17 19:16:36.669  7076  7076 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 19:16:36.669  7076  7076 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:16:36.669  7076  7076 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:36.679  1015  1493 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-17 19:16:36.679  7076  7091 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-17 19:16:36.679  1015  1493 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 19:16:36.689  1809  1809 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:36.689  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 19:16:36.689  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.689  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.689  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.689  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.709  7093  7093 E Zygote  : MountEmulatedStorage(),
08-17 19:16:36.709  7093  7093 I libpersona: KNOX_SDCARD checking this for 10001
08-17 19:16:36.709  7093  7093 E Zygote  : v2
08-17 19:16:36.709  7093  7093 I libpersona: KNOX_SDCARD not a persona,
08-17 19:16:36.709  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.709  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7093 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:36.709  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:36.709  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:36.709  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 19:16:36.719  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.719  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.719  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.719  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.739   307   307 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 739us total 30.490ms,
,08-17 19:16:36.749  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:36.749  7093  7093 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.759   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 677us total 19.996ms
,08-17 19:16:36.779   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 674us total 19.450ms
,08-17 19:16:36.799  7108  7108 E Zygote  : MountEmulatedStorage(),
08-17 19:16:36.799  7108  7108 E Zygote  : v2,
08-17 19:16:36.799  7108  7108 I libpersona: KNOX_SDCARD checking this for 10121
08-17 19:16:36.799  7108  7108 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:36.799  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7108 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 19:16:36.809  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.809  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:36.819  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:36.819  1015  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 19:16:36.819  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.819  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.819  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.819  1015  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.829  2634  2645 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-17 19:16:36.839  7121  7121 E Zygote  : MountEmulatedStorage(),
08-17 19:16:36.839  7121  7121 I libpersona: KNOX_SDCARD checking this for 10031
08-17 19:16:36.839  7121  7121 E Zygote  : v2
,08-17 19:16:36.839  7121  7121 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:36.839  7121  7121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.839  1015  1493 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7121 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-17 19:16:36.849  7121  7121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:36.849  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:36.849  7108  7108 D ActivityThread: Added TimaKeyStore provider,
,08-17 19:16:36.849  1809  1809 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-17 19:16:36.849  7121  7121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.849  1809  1809 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-17 19:16:36.849  1809  1809 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-17 19:16:36.849  1809  1809 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:36.869  1809  1809 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:36.869  1809  1809 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-17 19:16:36.869  1015  1745 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 19:16:36.869  7108  7108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:36.879  7108  7108 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:36.879  7108  7108 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:36.879  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.879  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.879  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.879  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.879  7121  7121 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:36.879  7121  7121 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.889  7108  7108 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,08-17 19:16:36.889  7138  7138 E Zygote  : MountEmulatedStorage(),
08-17 19:16:36.889  7138  7138 E Zygote  : v2
08-17 19:16:36.889  1015  1745 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7138 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:36.889  7138  7138 I libpersona: KNOX_SDCARD checking this for 10077
08-17 19:16:36.889  7138  7138 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:36.899  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.899  7108  7108 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-17 19:16:36.899  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:36.899  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.899  7108  7108 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-17 19:16:36.899  1015  1509 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-17 19:16:36.909  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.909  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.909  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.909  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.919  7151  7151 E Zygote  : MountEmulatedStorage()
08-17 19:16:36.919  7151  7151 I libpersona: KNOX_SDCARD checking this for 10141
08-17 19:16:36.919  7151  7151 E Zygote  : v2
08-17 19:16:36.919  7151  7151 I libpersona: KNOX_SDCARD not a persona,
08-17 19:16:36.919  7151  7151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.919  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:36.919  7151  7151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:36.919  7138  7138 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.929  7151  7151 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.929  1015  1509 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7151 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-17 19:16:36.929  1015  1509 I ActivityManager: Killing 6696:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-17 19:16:36.949  7121  7121 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 19:16:36.949  7151  7151 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:36.949  7151  7151 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:36.949  1015  1489 I ActivityManager: Killing 6116:com.android.mms/u0a41 (adj 15): empty #21
,08-17 19:16:36.969  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:16:36.969  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast,
,08-17 19:16:36.979  2790  7170 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 19:16:36.979  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.979  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.979  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:36.979  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:36.979  2790  7170 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-17 19:16:36.979  2790  7170 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-17 19:16:36.979  2790  7170 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-17 19:16:36.979  2790  7170 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 19:16:36.989  7151  7151 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-17 19:16:36.989  7151  7151 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:36.989  7151  7151 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
08-17 19:16:36.989  7151  7151 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:36.989  7171  7171 E Zygote  : MountEmulatedStorage()
08-17 19:16:36.989  7171  7171 I libpersona: KNOX_SDCARD checking this for 10032
08-17 19:16:36.989  7171  7171 E Zygote  : v2
08-17 19:16:36.989  7171  7171 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:36.989  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:36.999  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:36.999  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:16:36.999  1015  1027 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7171 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:37.009  1015  1489 D CountryDetector: No listener is left
,08-17 19:16:37.019  1015  1745 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 19:16:37.019  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.019  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.019  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.019  1015  1745 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.029  7184  7184 E Zygote  : MountEmulatedStorage()
08-17 19:16:37.029  7184  7184 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:37.029  7184  7184 E Zygote  : v2
08-17 19:16:37.029  7184  7184 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:37.029  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:37.029  1015  1745 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:16:37.029  1015  1745 I ActivityManager: Killing 6387:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-17 19:16:37.039  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:37.039  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.039  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:37.039  7171  7171 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.049  1015  1461 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.059  1015  1487 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.069  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:37.069  7184  7184 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.119  7171  7204 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-17 19:16:37.119  7171  7204 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 19:16:37.119  7171  7204 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:16:37.119  7171  7204 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:16:37.119  7171  7204 D SPPClientService: ============PushLog. stop!
08-17 19:16:37.119  7184  7184 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 19:16:37.129  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.139  7171  7171 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-17 19:16:37.149  1015  3124 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-17 19:16:37.149  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.149  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.149  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.149  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.149  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:37.159  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 19:16:37.159  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:37.159  1015  1487 D BatteryService: stay LED for fully charged
08-17 19:16:37.159  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:37.169  1015  3124 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7209 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:37.169  1015  3124 I ActivityManager: Killing 6641:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-17 19:16:37.169  1015  1461 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-17 19:16:37.169  7209  7209 E Zygote  : MountEmulatedStorage(),
08-17 19:16:37.169  7209  7209 E Zygote  : v2
,08-17 19:16:37.169  7209  7209 I libpersona: KNOX_SDCARD checking this for 10036
08-17 19:16:37.169  7209  7209 I libpersona: KNOX_SDCARD not a persona,
,08-17 19:16:37.169  7209  7209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:16:37.179  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.179  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:37.179  1015  1461 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 19:16:37.179  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-17 19:16:37.179  7209  7209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:37.179  7209  7209 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.179  1015  1015 I MotionRecognitionService: Plugged
,08-17 19:16:37.189  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:37.189  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:37.189  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:37.189  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:37.189  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:37.199  1015  1461 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.209  7209  7209 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:37.209  7209  7209 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.219  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 19:16:37.219  1171  1171 D SViewCoverView: level :100 plugged : 2
,08-17 19:16:37.219  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:37.219  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:16:37.219  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:37.259  7209  7209 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@157c914c
,08-17 19:16:37.269  7171  7218 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 19:16:37.269  7209  7209 I SA      : [SSP] onCreated
,08-17 19:16:37.269  1015  1489 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.279  1015  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-17 19:16:37.279  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.279  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.279  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.279  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.279  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.289  7231  7231 E Zygote  : MountEmulatedStorage()
08-17 19:16:37.289  7231  7231 E Zygote  : v2
08-17 19:16:37.289  7231  7231 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:16:37.289  7184  7184 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-17 19:16:37.289  7231  7231 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:37.289  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:37.299  1015  1487 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7231 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-17 19:16:37.299  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:37.299  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.309  7184  7184 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 19:16:37.309  7184  7184 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:37.309  7184  7184 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 19:16:37.309  7184  7184 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-17 19:16:37.309  7184  7184 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 19:16:37.309  7209  7209 I SA      : [TPM] There is no property file
,08-17 19:16:37.309  1015  1745 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.309  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 19:16:37.319  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.319  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.319  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.319  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.319  7209  7209 I SA      : [SCU] isHaveSA() - false
,08-17 19:16:37.319  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:37.319  7231  7231 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.329  7209  7209 I SA      : [TPM] getModelProperty : null
,08-17 19:16:37.329  7209  7209 I SA      : [TPM] getCSCProperty : null
,08-17 19:16:37.329  7209  7209 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-17 19:16:37.329  7209  7209 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-17 19:16:37.329  7209  7209 I SA      : [DM] TFT FEATURE: false
,08-17 19:16:37.329  7248  7248 E Zygote  : MountEmulatedStorage()
,08-17 19:16:37.329  7248  7248 E Zygote  : v2
08-17 19:16:37.329  7248  7248 I libpersona: KNOX_SDCARD checking this for 10008
08-17 19:16:37.329  7248  7248 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:37.329  7248  7248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:16:37.329  1015  1028 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7248 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:37.339  7248  7248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:37.339  1015  1028 I ActivityManager: Killing 6720:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-17 19:16:37.339  1015  1461 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 19:16:37.339  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-17 19:16:37.339  7248  7248 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.339  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.339  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:37.339  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:37.349  7209  7209 I SA      : [DM] init START
,08-17 19:16:37.359  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 19:16:37.359  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.359  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.359  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.359  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.359  7209  7209 I SA      : [DM] This device is not a Vodafone
,08-17 19:16:37.359  7248  7248 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:37.359  7248  7248 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.369  1015  3124 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:37.379  7264  7264 E Zygote  : MountEmulatedStorage()
,08-17 19:16:37.379  7264  7264 E Zygote  : v2
08-17 19:16:37.379  7264  7264 I libpersona: KNOX_SDCARD checking this for 10110
08-17 19:16:37.379  7264  7264 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:37.379  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:37.379  1015  1028 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7264 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:37.379  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:37.379  1015  1493 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 19:16:37.379  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0,
08-17 19:16:37.379  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.379  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:37.379  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-17 19:16:37.379  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-17 19:16:37.389  1015  1509 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-17 19:16:37.389  7209  7209 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-17 19:16:37.399  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.399  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-17 19:16:37.399  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.399  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-17 19:16:37.399  7034  7257 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-17 19:16:37.399  7209  7209 W ResourceType: Failure getting entry for 0x7,f060031 (t=5 e=49) (error -75)
,08-17 19:16:37.409  7209  7209 I SA      : [SCU] isHaveSA() - false
08-17 19:16:37.409  7209  7209 I SA      : support phone number id : false
08-17 19:16:37.409  7209  7209 I SA      : [DM] Supports Ref Jpn : true
08-17 19:16:37.409  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:37.409  7209  7209 I SA      : [DM] init END
08-17 19:16:37.409  7209  7209 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-17 19:16:37.409  7264  7264 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.409  7209  7209 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-17 19:16:37.409  7209  7209 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-17 19:16:37.409  7231  7231 D BadgeProvider: onCreate
08-17 19:16:37.419  7281  7281 I libpersona: KNOX_SDCARD checking this for 10009
08-17 19:16:37.409  7231  7231 D BadgeProvider: DatabaseHelper
08-17 19:16:37.419  7281  7281 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:37.419  7209  7209 I SA      : [SLFUCHKMGR] constructor called
08-17 19:16:37.419  7281  7281 E Zygote  : MountEmulatedStorage()
08-17 19:16:37.419  7281  7281 E Zygote  : v2
08-17 19:16:37.419  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:37.429  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:37.429  1015  1509 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7281 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-17 19:16:37.429  1015  1509 I ActivityManager: Killing 6514:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-17 19:16:37.429  1015  1509 I ActivityManager: Killing 6737:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
,08-17 19:16:37.439  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.459  1015  1461 I ActivityManager: Killing 6553:com.android.calendar/u0a131 (adj 15): empty #21
,08-17 19:16:37.469   307   307 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 40.172ms
,08-17 19:16:37.489   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 18.035ms
,08-17 19:16:37.489  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:37.489  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.509   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 20.094ms
,08-17 19:16:37.509  7209  7209 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 19:16:37.509  7209  7209 I SA      : [OR] == isSIMCardReady false ==
,08-17 19:16:37.519  7209  7209 I SA      : [SCU] == networkStateCheck == false
08-17 19:16:37.519  7209  7209 I SA      : [OR] onReceive END
,08-17 19:16:37.529  1015  1745 I ActivityManager: Killing 6077:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-17 19:16:37.529  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-17 19:16:37.529  1015  1745 I ActivityManager: Killing 5892:com.android.vending/u0a26 (adj 15): empty #21
,08-17 19:16:37.559  2906  2906 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:16:37 GMT+02:00 2016
,08-17 19:16:37.559  1015  1254 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 19:16:37.559  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.559  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.559  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:37.559  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:16:37.569  2906  2906 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:16:37.579  2906  2906 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 19:16:37.579  2906  2906 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:16:37.589  2906  2906 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:16:37.589  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.589  1015  1134 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 19:16:37.589  2906  7299 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 19:16:37.589  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.599  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.599  1015  1461 I ActivityManager: Killing 6860:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-17 19:16:37.609  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:37.609  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0,
08-17 19:16:37.609  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.609  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:37.609  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:37.629  4806  7301 I iu.SyncManager: SYNC; picasa accounts
,08-17 19:16:37.629  4806  4806 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-17 19:16:37.629  2906  7299 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 19:16:37.649  2906  7299 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 19:16:37.649  2906  7299 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-17 19:16:37.649  2906  2906 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 19:16:37.659  1015  1487 I art     : Explicit concurrent mark sweep GC freed 60899(3MB) AllocSpace objects, 10(208KB) LOS objects, 33% free, 24MB/36MB, paused 7.046ms total 234.448ms
,08-17 19:16:37.679  7231  7246 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 19:16:37.689  7231  7246 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 19:16:37.689  1495  1495 D Launcher.Model: reloadBadges entered.
,08-17 19:16:37.689  7231  7246 D BadgeProvider: sendNotify, [notify] : null
08-17 19:16:37.689  7231  7246 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 19:16:37.689  7231  7246 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:16:37.689  7231  7246 D BadgeProvider: update, [UpdateCount] : 1
,08-17 19:16:37.739  1015  1461 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:37.769   289   289 E SMD     : DCD OFF
,08-17 19:16:37.839   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:16:37.839   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:37.839  7264  7306 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:37.849   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:37.849   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:37.849  7264  7306 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:37.859   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:16:37.859   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:37.859  7264  7307 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:37.859   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:37.859   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:37.859  7264  7307 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:37.859  1015  1493 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:37.859  1015  1493 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:37.859  1015  1493 D SecContentProvider2: mCursor = null
,08-17 19:16:37.869  1015  1493 D WifiService: setWifiEnabled: true pid=6789, uid=10171
,08-17 19:16:37.869  1015  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:37.869  1015  1493 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:37.869  1015  1493 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:37.869  1015  1493 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:37.869  1015  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:37.869  1015  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:37.869  1015  1493 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:37.869  1015  1493 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:37.869  1015  1493 D SettingsProvider: name = wifi_on
,08-17 19:16:37.869  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:16:37.889  7264  7264 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 19:16:37.889  7264  7264 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:16:37.889  7264  7264 I GAv4    :   adb logcat -s GAv4
,08-17 19:16:37.909  7264  7264 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:37.909  1015  1509 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:37.929  7264  7264 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:37.949  7264  7310 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:38.179  1015  1745 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:38.179  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.179  1015  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.179  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 19:16:38.219  7264  7264 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 19:16:38.239  1015  1042 D Tethering: interfaceAdded wlan0
,08-17 19:16:38.239  7264  7264 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7404-7406)
,08-17 19:16:38.239  7264  7264 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:38.249  1015  1129 E Tethering: No numeric data
08-17 19:16:38.249  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:38.249  1015  1129 D Tethering: clearTetheredNotification()
08-17 19:16:38.249  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.249  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.249  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:38.249  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.249  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:38.249  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:38.249  1171  1171 D HotspotTile: updateTetherState():false, false
08-17 19:16:38.249  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 19:16:38.249  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:16:38.249  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:38.249  1015  1129 E Tethering: No numeric data
,08-17 19:16:38.249  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:38.249  1015  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:38.259  1015  1042 D Tethering: interfaceAdded p2p0
,08-17 19:16:38.259  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:16:38.259   279   999 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 19:16:38.259   279   999 D SoftapController: Softap fwReload - Ok
,08-17 19:16:38.259  1015  1121 V NetworkStats: performPollLocked() took 10ms
,08-17 19:16:38.259  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:38.259  1171  1171 D HotspotTile: updateTetherState():false, false
,08-17 19:16:38.259  7264  7264 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1eff5937}
08-17 19:16:38.259  7264  7264 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:38.259  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.259   279   999 D CommandListener: Setting iface cfg
08-17 19:16:38.259   279   999 D CommandListener: Trying to bring down wlan0
,08-17 19:16:38.259   279   999 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:38.259  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.259  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.259  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:38.259  7264  7264 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:16:38.259  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:38.259  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.259  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.259  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.269  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:16:38.269  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:38.269  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:38.269  1015  1121 V NetworkStats: performPollLocked() took 8ms
08-17 19:16:38.269  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.269  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.269  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.289  7264  7264 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 19:16:38.289  7264  7264 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:16:38.289  7264  7264 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-17 19:16:38.309  7264  7264 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:38.309  7264  7264 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:38.309  7264  7264 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:38.309  7264  7264 I Adreno-EGL: Local Branch: 
08-17 19:16:38.309  7264  7264 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:38.309  7264  7264 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:38.309  7264  7264 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:38.309  7334  7334 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 19:16:38.309  7334  7334 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 19:16:38.319  7334  7334 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:38.339  7334  7334 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-17 19:16:38.339   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7334
,08-17 19:16:38.339   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-17 19:16:38.339  7334  7334 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:38.339  7334  7334 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:38.339  7334  7334 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:16:38.339  7334  7334 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-17 19:16:38.339   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7334
08-17 19:16:38.339   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-17 19:16:38.369  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 19:16:38.369  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.379  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-17 19:16:38.369  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:38.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.379  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:38.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.369  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:38.369  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 19:16:38.379  1171  1171 D HotspotTile: onReceive : 2, 0
,08-17 19:16:38.379  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:38.379  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.379  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.409  7264  7347 W cr.media: Requires BLUETOOTH permission
,08-17 19:16:38.409  7264  7264 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:16:38.429  7264  7264 I NSApplication: Starting up...
,08-17 19:16:38.429  1015  1254 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:38.429  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:38.439  1015  1254 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 19:16:38.439  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.439  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.439  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.439  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.449  7352  7352 E Zygote  : MountEmulatedStorage()
08-17 19:16:38.449  1015  1254 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7352 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:16:38.449  7352  7352 E Zygote  : v2
08-17 19:16:38.449  7352  7352 I libpersona: KNOX_SDCARD checking this for 10117
08-17 19:16:38.449  7352  7352 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:38.449  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:38.459  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:38.459  1015  1254 I ActivityManager: Killing 7003:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-17 19:16:38.459  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:38.479  7352  7352 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:38.479  7352  7352 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:38.499  7352  7352 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:38.519   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-17 19:16:38.529  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-17 19:16:38.569  7334  7334 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:38.569  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:38.579  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-17 19:16:38.589   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7334
08-17 19:16:38.589   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:38.589  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:16:38.589  7334  7334 I wpa_supplicant: ssSupport state is = 1,
08-17 19:16:38.589  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:16:38.589  7334  7334 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:38.589  7334  7334 E wpa_supplicant: SIM READ ERROR
08-17 19:16:38.589  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:38.589  7334  7334 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:38.589  7334  7334 E wpa_supplicant: SIM READ ERROR
08-17 19:16:38.589  7334  7334 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:16:38.589  7334  7334 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:38.589  7334  7334 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:38.589  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:38.589  7334  7334 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:16:38.589  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:38.589  7334  7334 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:38.589  7334  7334 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:16:38.589  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.589  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.589  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:38.649  7334  7334 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:16:38.669  1015  1047 I PowerManagerService: [PWL] Off : 75s ago,
08-17 19:16:38.669  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-17 19:16:38.669  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-17 19:16:38.669  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=3445)
,08-17 19:16:38.839  7334  7334 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:38.839  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:38.849  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 19:16:38.849   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7334
08-17 19:16:38.849   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-17 19:16:38.849  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-17 19:16:38.849  7334  7334 I wpa_supplicant: ssSupport state is = 1
,08-17 19:16:38.859  7334  7334 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:16:38.859  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:38.869  1015  1323 E Watchdog: !@Sync 4
,08-17 19:16:38.879  1015  3124 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 19:16:38.879  1015  3124 I ActivityManager: Killing 7019:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-17 19:16:38.879  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-17 19:16:38.879   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7334
08-17 19:16:38.879   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:38.879  7334  7334 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:16:38.879  7334  7334 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:38.879  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:38.879  7334  7334 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:38.879  7334  7334 E wpa_supplicant: SIM READ ERROR
08-17 19:16:38.879  7334  7334 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:38.879  7334  7334 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:38.879  7334  7334 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:16:38.889  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:38.889  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.889  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-17 19:16:38.889  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.889  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.889  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:38.889  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:38.889  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:38.889  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.889  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.889  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:38.889  1617  1617 I Hs20UtilService: Starting #12
08-17 19:16:38.889  1617  1636 I Hs20UtilService: Message received 5011
,08-17 19:16:38.899  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:38.899  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:38.899  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:38.899  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:38.989  7334  7334 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:38.989  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:39.109  7334  7334 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 19:16:39.109  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 19:16:39.109  7334  7334 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-17 19:16:39.119  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-17 19:16:39.119  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:39.119  7334  7334 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:16:39.119  7334  7334 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 19:16:39.119  7334  7334 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:39.119  7334  7334 E wpa_supplicant: SIM READ ERROR,
08-17 19:16:39.119  7334  7334 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:39.139  7334  7334 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 19:16:39.149  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:39.149  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:39.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:39.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.149  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.149  7334  7334 I wpa_supplicant: Skip scan - bUseNetwork false,
08-17 19:16:39.149  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:39.149  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
08-17 19:16:39.149  1171  1171 D HotspotTile: onReceive : 3, 0
08-17 19:16:39.149  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.149  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 19:16:39.159  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 19:16:39.159  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:39.159  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-17 19:16:39.159  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:39.159  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:39.159  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:39.159  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.159  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:39.159  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:39.159  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:39.159  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.159  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.159  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:39.169  1617  1617 I Hs20UtilService: Starting #13
,08-17 19:16:39.169  1617  1636 I Hs20UtilService: Message received 5011
,08-17 19:16:39.169  1015  1124 E WifiConfigStore: Not a HS20
,08-17 19:16:39.169  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:39.169  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:16:39.169  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:39.169  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:39.169  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:39.179  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:16:39.179  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-17 19:16:39.179  7334  7334 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:39.179  7334  7334 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-17 19:16:39.179  7334  7334 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:39.179  7334  7334 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:39.179  7334  7334 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:39.179  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:39.179  7334  7334 I wpa_supplicant: First Scan Start
08-17 19:16:39.179  7334  7334 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:39.189  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-17 19:16:39.189  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:16:39.189  1015  1124 I WifiNative-HAL: startHal
08-17 19:16:39.189  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d47888c
08-17 19:16:39.189  1015  1124 I WifiNative-HAL: Could not start hal
,08-17 19:16:39.189  7034  7034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:39.189  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 19:16:39.189  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:39.189  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 19:16:39.189  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:16:39.199   279   999 D CommandListener: Setting iface cfg
08-17 19:16:39.199   279   999 D CommandListener: Trying to bring up p2p0
08-17 19:16:39.199  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:39.199  1015  1148 I WifiNative-HAL: startHal
08-17 19:16:39.199  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e62a9bc
,08-17 19:16:39.199  1015  1148 I WifiNative-HAL: Could not start hal
08-17 19:16:39.199  1015  1148 E WifiScanningService: could not start HAL
08-17 19:16:39.199  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:39.199  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:39.199  1015  1124 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:39.199  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:16:39.199  1015  1123 D WifiP2pService: P2pEnablingState
08-17 19:16:39.199  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-17 19:16:39.199  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 19:16:39.199  1015  1123 D WifiP2pService: P2p socket connection successful
,08-17 19:16:39.199  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:39.199  1015  1123 D WifiP2pService: P2pEnabledState
08-17 19:16:39.199  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:39.199  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:39.199  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:39.199  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:39.199  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:39.199  7334  7334 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:39.199  7334  7334 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:39.199  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:39.199  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-17 19:16:39.199  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:39.199  1015  1045 D WifiDisplayController: disconnect
08-17 19:16:39.199  7334  7334 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-17 19:16:39.199  1015  1045 D WifiDisplayController: updateConnection
08-17 19:16:39.199  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:39.199  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:39.209  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,08-17 19:16:39.209  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:16:39.209  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:39.209  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:16:39.209  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28,
,08-17 19:16:39.209  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:39.209  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:39.209  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:39.209  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:39.209  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:39.209  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:39.209  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:39.209  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  secondary type: null
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  wps: 0
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  grpcapab: 0
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  devcapab: 0
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  status: 3
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  wfdInfo: null
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:39.209  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:39.209  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-17 19:16:39.209  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:39.219  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:39.219  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:39.219  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:39.219  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:39.219  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:39.219  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:39.219  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:39.219  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:39.219  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 19:16:39.219  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.219  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.219  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.219  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.239  7382  7382 E Zygote  : MountEmulatedStorage()
,08-17 19:16:39.239  7382  7382 E Zygote  : v2
08-17 19:16:39.239  7382  7382 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:16:39.239  7382  7382 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.239  7382  7382 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:39.239  1015  1134 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7382 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:16:39.249  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:39.249  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:39.249  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:39.249  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
08-17 19:16:39.249  1015  1123 D WifiP2pService: InactiveState
08-17 19:16:39.249  7382  7382 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:39.249  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:39.249  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:39.249  7334  7334 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:39.249  7382  7382 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:39.249  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:39.249  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:39.269  7382  7382 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.269  7382  7382 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.289  7382  7382 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:39.299  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:39.299  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:39.329  7382  7382 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:39.329  1015  1254 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:16:39.339  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.339  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.339  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.339  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.349  7397  7397 E Zygote  : MountEmulatedStorage(),
08-17 19:16:39.349  7397  7397 E Zygote  : v2
08-17 19:16:39.349  7397  7397 I libpersona: KNOX_SDCARD checking this for 10065
08-17 19:16:39.349  7397  7397 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.349  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:39.349  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:39.349  1015  1254 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7397 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:39.349  1015  1254 I ActivityManager: Killing 6926:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-17 19:16:39.359  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.379  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-17 19:16:39.379  7397  7397 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.399  7397  7397 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:39.409  1015  1134 I ActivityManager: Killing 7059:com.android.bluetooth/1002 (adj 15): empty #21
,08-17 19:16:39.529  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7059
,08-17 19:16:39.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:40.339  7334  7334 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
08-17 19:16:40.339  7334  7334 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:40.339  7334  7334 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 19:16:40.339  7334  7334 I wpa_supplicant: Trying to associate with  'G700',
08-17 19:16:40.339  7334  7334 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 19:16:40.339  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:40.339  1015  7378 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:16:40.359  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:40.359  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:40.459  7334  7334 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:16:40.459  7334  7334 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:40.459  7334  7334 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 19:16:40.459  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:40.459  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:40.459  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:40.459  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:40.459  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:40.459  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:40.459  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:40.459  7334  7334 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-17 19:16:40.459  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:40.459  7334  7334 I wpa_supplicant: Associated with F4.99.3E
08-17 19:16:40.459  7334  7334 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:40.459  7334  7334 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-17 19:16:40.459  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:40.459  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:16:40.459  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:40.469  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:40.469  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
,08-17 19:16:40.469  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:16:40.469  7334  7334 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:40.469  7334  7334 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 19:16:40.469  1015  1129 E Tethering: No numeric data
08-17 19:16:40.469  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:40.469  1015  1129 D Tethering: clearTetheredNotification()
08-17 19:16:40.469  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:40.469  7334  7334 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:16:40.469  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:40.469  7334  7334 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:16:40.469  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:40.469  7334  7334 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 19:16:40.469  1171  1171 D HotspotTile: updateTetherState():false, false
08-17 19:16:40.469  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:40.469  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:40.469  7334  7334 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:16:40.469  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:40.469  7334  7334 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:16:40.469  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:40.469  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:40.469  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:16:40.469  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:40.469  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:40.469  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:40.479  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:40.479  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-17 19:16:40.479  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:40.479  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:40.479  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:16:40.479  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:40.479  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 19:16:40.479  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:16:40.479  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:40.479  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:40.489  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:40.489  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:40.489  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.489  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.489  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.489  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:40.489  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 19:16:40.489  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.489  1015  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:40.489  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.489  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:40.489  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:40.499  1617  1617 I Hs20UtilService: Starting #14
,08-17 19:16:40.499  1617  1636 I Hs20UtilService: Message received 5007
08-17 19:16:40.499  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:40.499  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:40.499  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:40.499  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:40.499  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:40.499  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:40.509  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:40.509  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:40.519   279   999 D CommandListener: Setting iface cfg
,08-17 19:16:40.529  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:16:40.529  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:40.529  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:40.529  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:40.529  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:40.539  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:40.539  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:40.539  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:40.549  1015  1124 E WifiNative-wlan0: do suspend false
,08-17 19:16:40.549  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:40.549  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:40.549  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:40.549  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:40.769  7414  7414 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
08-17 19:16:40.769   289   289 E SMD     : DCD OFF
,08-17 19:16:40.769  7414  7414 I dhcpcd  : version 5.5.6 starting,
,08-17 19:16:40.779  7414  7414 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:40.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:40.839  7414  7414 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 19:16:40.839  7414  7414 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:16:40.839  7414  7414 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-17 19:16:40.839  7414  7414 I dhcpcd  : bssid match
,08-17 19:16:40.839  7414  7414 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 19:16:40.879  1015  1461 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-17 19:16:40.879  1015  1461 D WifiService: setWifiEnabled: false pid=6789, uid=10171,
08-17 19:16:40.879  1015  1461 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-17 19:16:40.879  1015  1461 D SecContentProvider2: mCursor = null,
,08-17 19:16:40.879  1015  1461 D SettingsProvider: name = wifi_on
,08-17 19:16:40.889  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:40.899  1015  1124 E WifiNative-wlan0: do suspend true,
,08-17 19:16:40.919  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:40.919   279   999 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:40.919  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:40.929  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:40.929  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:40.929  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.929  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.929  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.929  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:40.929  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:40.929  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:40.929  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:40.929  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 19:16:40.929  7414  7414 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-17 19:16:40.929   279   999 E Netd    : no such netId 503
08-17 19:16:40.939  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:16:40.939  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-17 19:16:40.939  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-17 19:16:40.939  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 19:16:40.939  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:40.939  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:40.939  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:40.939  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:40.949  1015  1126 V NetworkStats: performPollLocked() took 8ms
,08-17 19:16:40.949  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:40.959  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:40.959  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:40.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:40.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:40.969  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
,08-17 19:16:40.969  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 19:16:40.969  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:16:40.969  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-17 19:16:40.969  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-17 19:16:40.969  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:40.969  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:40.969  1015  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:40.969  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:40.969  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:40.969  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.969  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:40.969  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:40.969  1617  1617 I Hs20UtilService: Starting #15
,08-17 19:16:40.979  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-17 19:16:40.979  1015  7412 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:40.979  1015  7412 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 19:16:40.979  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:16:40.979  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:40.979  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:40.979  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:40.979  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 19:16:40.979  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-17 19:16:40.979  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:40.979  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:40.979  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:40.979  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:40.989  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:40.989  1015  1126 E ConnectivityService: updateNetworkInfo(),
08-17 19:16:40.989  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:40.989  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-17 19:16:40.989  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
08-17 19:16:40.989  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-17 19:16:40.989  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:40.989  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:40.989  1015  1045 D WifiDisplayController: disconnect
08-17 19:16:40.989  1015  1045 D WifiDisplayController: updateConnection
,08-17 19:16:40.989  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:40.989  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:40.989  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-17 19:16:40.999  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-17 19:16:40.999  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:40.999  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:40.999  1015  1123 D WifiP2pService: P2pDisablingState
08-17 19:16:40.999  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:16:40.999  1015  1123 D WifiP2pService: p2p socket connection lost,
08-17 19:16:40.999  1015  1123 D WifiP2pService: P2pDisabledState
,08-17 19:16:40.999  1015  1124 E WifiNative-wlan0: do suspend true,
,08-17 19:16:40.999  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 19:16:40.999  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:40.999  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:40.999  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:40.999  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:40.999  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:40.999  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:40.999  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:41.009  7414  7414 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-17 19:16:41.009  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:41.009  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:41.009  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:41.019  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:41.019  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:41.019  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:41.019  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:41.019  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:41.019  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 19:16:41.019  7382  7382 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:41.029   279   999 D CommandListener: Clearing all IP addresses on wlan0,
08-17 19:16:41.029  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 19:16:41.029  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:41.029  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:41.029  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:41.029  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:41.029  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.029  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.029  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.039  7397  7397 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-17 19:16:41.039  7334  7334 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:41.039  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:41.049  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:41.049  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:41.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-17 19:16:41.059  1015  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:41.059  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:41.059  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:41.059  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:41.059  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:41.059  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:41.059  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:41.059  1617  1617 I Hs20UtilService: Starting #16
,08-17 19:16:41.059  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:41.069  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:41.069  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:41.069  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.069  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.069  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.069  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:41.069  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:41.069  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:41.069  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:41.069  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:41.069  1171  1171 D HotspotTile: onReceive : 0, 0
,08-17 19:16:41.069  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 19:16:41.079  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:41.079  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.079  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:41.079  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:41.079  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:41.079  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:41.079  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:41.079  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.079  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:41.079  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:41.089  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-17 19:16:41.089  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:41.089  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:41.099  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:41.099  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:16:41.099  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:41.099  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:41.099  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:41.099  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:41.099  1617  1617 I Hs20UtilService: Starting #17
08-17 19:16:41.099  1617  1636 I Hs20UtilService: Message received 5011
,08-17 19:16:41.109  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:41.109  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:41.109  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1,
08-17 19:16:41.109  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:41.199  7334  7334 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:41.349  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:41.349  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:41.349  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:41.349  7334  7334 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 19:16:41.379  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-17 19:16:41.379  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.379  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
,08-17 19:16:41.379  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 19:16:41.379  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:41.379  7334  7334 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 19:16:41.379  7334  7334 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:41.379  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.379  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:41.389  7334  7334 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:16:41.389  1015  1129 E Tethering: No numeric data
08-17 19:16:41.389  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:41.389  1015  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:41.389  7334  7334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:41.389  7334  7334 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:41.389  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:41.389  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:41.389  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:41.389  1171  1171 D HotspotTile: updateTetherState():false, false
08-17 19:16:41.389  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:41.389  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:41.389  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:41.389  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.389  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:41.399  1015  1121 V NetworkStats: performPollLocked() took 7ms
08-17 19:16:41.399  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:41.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:16:41.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:41.449  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:16:41.449  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.449  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:41.599  1015  1745 I ActivityManager: Killing 6950:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-17 19:16:41.639  7334  7334 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 19:16:41.699  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.699  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.699  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:41.699  7334  7334 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 19:16:41.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:41.809  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-17 19:16:41.809  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,08-17 19:16:41.819  7034  7034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:41.819  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:41.819  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:41.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:41.819  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:41.819  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-17 19:16:41.819  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:41.819  1171  1171 D HotspotTile: onReceive : 1, 0
,08-17 19:16:41.819  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:41.829  2038  2221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:41.829  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:41.829  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:41.839  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:41.839  1015  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:41.839  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:41.839  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:41.839  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 19:16:41.839  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:41.849  1617  1617 I Hs20UtilService: Starting #18
,08-17 19:16:41.849  1617  1636 I Hs20UtilService: Message received 5011
,08-17 19:16:41.849  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:41.849  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:41.849  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:41.849  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:42.489  1015  1042 D Tethering: interfaceRemoved wlan0
,08-17 19:16:42.489  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:42.619  1015  1042 D Tethering: interfaceRemoved p2p0
,08-17 19:16:42.619  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:42.709  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:42.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:43.379  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-17 19:16:43.449  1015  2075 V SAMP_SPCM_test: CSC File load.. 
,08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings,
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-17 19:16:43.459  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:16:43.499  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-17 19:16:43.509  1015  2075 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:16:43.509  1015  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-17 19:16:43.519  1015  2075 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-17 19:16:43.519  1015  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.519  1015  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.519  1015  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.519  1015  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.539  7445  7445 E Zygote  : MountEmulatedStorage()
08-17 19:16:43.539  7445  7445 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:43.539  7445  7445 E Zygote  : v2
08-17 19:16:43.539  7445  7445 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:43.539  7445  7445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:16:43.539  7445  7445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.539  7445  7445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:43.549  1015  2075 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7445 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:16:43.569  7445  7445 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.569  7445  7445 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.589  7445  7445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:43.629  1015  2075 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 19:16:43.629  1015  1015 I ActivityManager: Killing 7076:com.sec.pcw.device/1000 (adj 15): empty #21
,08-17 19:16:43.689  1015  3359 D SSRM:n  : SIOP:: AP = 350
,08-17 19:16:43.769   289   289 E SMD     : DCD OFF,
,08-17 19:16:43.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:43.889  6789  6844 D BluetoothAdapter: enable()
,08-17 19:16:43.889  1015  3124 W ActivityManager: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:43.889  1015  3124 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:16:43.889  1015  3124 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:43.889  1015  3124 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:43.889  1015  3124 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:43.889  1015  3124 D SettingsProvider: name = bluetooth_on
,08-17 19:16:43.899  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-17 19:16:43.899  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:43.899  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 19:16:43.899  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.899  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.899  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.899  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.909  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.919  7462  7462 E Zygote  : MountEmulatedStorage(),
08-17 19:16:43.919  7462  7462 E Zygote  : v2
08-17 19:16:43.929  7462  7462 I libpersona: KNOX_SDCARD checking this for 1002,
08-17 19:16:43.929  7462  7462 I libpersona: KNOX_SDCARD not a persona,
08-17 19:16:43.929  7462  7462 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:43.929  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7462 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:16:43.929  7462  7462 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.939  7462  7462 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:43.969  7462  7462 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.969  7462  7462 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.989  7462  7462 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:16:43.989  7462  7462 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:44.019  7462  7462 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding A2dpService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding HidService
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding HealthService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding PanService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding SapService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 19:16:44.059  7462  7462 D BtSettings.ProfileConfig: Adding HidDevService
08-17 19:16:44.059  7462  7462 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:16:44.059  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:16:44.059  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.059  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:44.059  1015  1027 D SettingsProvider: selectionArgs: false
08-17 19:16:44.059  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.059  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 19:16:44.069  1015  1027 D SettingsProvider: ret = -1
,08-17 19:16:44.069  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:44.069  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.069  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  1134 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1134 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.069  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1134 D SettingsProvider: ret = -1
,08-17 19:16:44.069  1015  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:44.069  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.069  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  1489 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1489 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.069  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1489 D SettingsProvider: ret = -1
,08-17 19:16:44.069  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-17 19:16:44.069  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.069  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  1028 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.069  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1028 D SettingsProvider: ret = -1,
08-17 19:16:44.069  1015  1461 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:16:44.069  1015  1461 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,08-17 19:16:44.069  1015  1461 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  1461 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1461 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.069  1015  1461 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1461 D SettingsProvider: ret = -1
08-17 19:16:44.069  1015  3124 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:16:44.069  1015  3124 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.069  1015  3124 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  3124 D SettingsProvider: selectionArgs: false
,08-17 19:16:44.069  1015  3124 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.069  1015  3124 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  3124 D SettingsProvider: ret = -1
08-17 19:16:44.069  1015  1254 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:16:44.069  1015  1254 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-17 19:16:44.069  1015  1254 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:44.069  1015  1254 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1254 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.069  1015  1254 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1254 D SettingsProvider: ret = -1
08-17 19:16:44.069  1015  1487 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:16:44.069  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.069  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.069  1015  1487 D SettingsProvider: selectionArgs: false
08-17 19:16:44.069  1015  1487 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.069  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.069  1015  1487 D SettingsProvider: ret = -1
,08-17 19:16:44.079  1015  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:44.079  1015  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.079  1015  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.079  1015  1509 D SettingsProvider: selectionArgs: false
08-17 19:16:44.079  1015  1509 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.079  1015  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.079  1015  1509 D SettingsProvider: ret = -1
08-17 19:16:44.079  1015  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.079  1015  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.079  1015  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.079  1015  1493 D SettingsProvider: selectionArgs: false
08-17 19:16:44.079  1015  1493 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.079  1015  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:44.079  1015  1493 D SettingsProvider: ret = -1
08-17 19:16:44.079  1015  1745 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:16:44.079  1015  1745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.079  1015  1745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.079  1015  1745 D SettingsProvider: selectionArgs: false
08-17 19:16:44.079  1015  1745 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.079  1015  1745 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.079  1015  1745 D SettingsProvider: ret = -1
,08-17 19:16:44.079  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:16:44.079  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.079  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.079  1015  1027 D SettingsProvider: selectionArgs: false
08-17 19:16:44.079  1015  1027 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.079  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.079  1015  1027 D SettingsProvider: ret = -1
,08-17 19:16:44.099  7462  7462 D BluetoothAdapterState: make,
,08-17 19:16:44.099  7462  7462 I bluedroid: init,
,08-17 19:16:44.099  7462  7477 I BluetoothAdapterState: Entering OffState
,08-17 19:16:44.099  7462  7462 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:16:44.109  7462  7462 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:16:44.109  7462  7462 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:16:44.109  7462  7462 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:44.109  7462  7462 E bt-btif : btif_fetch_local_ble_random_bdaddr,
08-17 19:16:44.109  7462  7462 I bluedroid: get_profile_interface socket
08-17 19:16:44.109  7462  7462 I bluedroid: get_profile_interface map_client
08-17 19:16:44.109  7462  7480 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:16:44.109  7462  7462 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:16:44.109  7462  7480 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 19:16:44.109  7462  7480 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:44.109  7462  7480 I bluedroid: getModelRssiValues
08-17 19:16:44.109  7462  7480 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:44.109  7462  7480 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:44.109  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 19:16:44.119  7462  7480 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:16:44.119  7462  7462 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:44.119  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:44.119  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.119  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.119  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:44.119  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.129  7462  7470 I bluedroid: config_hci_snoop_log
,08-17 19:16:44.129  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-17 19:16:44.129  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:16:44.129  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:16:44.129  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:16:44.129  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:44.139  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:44.139  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:44.139  7462  7462 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 19:16:44.139  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:16:44.139  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:44.139  7462  7477 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-17 19:16:44.139  7462  7477 D BluetoothAdapterProperties: Setting state to 11
08-17 19:16:44.139  7462  7477 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 19:16:44.139  7462  7477 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:44.139  7462  7477 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:16:44.149  7462  7477 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:44.149  7462  7477 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:16:44.149  7462  7477 D BluetoothSecureManager: getInstant: null
,08-17 19:16:44.149  7462  7477 D BluetoothSecureManager: calling getMethod for getService
08-17 19:16:44.149  7462  7477 D BluetoothSecureManager: calling getService
,08-17 19:16:44.149  7462  7477 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@25ece57c
,08-17 19:16:44.149  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:44.149  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:16:44.149  1015  1509 D BluetoothSecureManagerService: isSecureModeEnabled
,08-17 19:16:44.149  1015  1509 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-17 19:16:44.149  7462  7477 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:44.149  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:44.149  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 19:16:44.149  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:44.159  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:44.159  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:16:44.159  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:44.159  1171  1171 D BluetoothTile:  getBluetoothState : 11
08-17 19:16:44.159  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:44.169  7462  7477 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:16:44.169  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:44.169  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:44.169  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:16:44.169  1845  1845 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:16:44.169  7462  7477 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:44.169  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.169  7462  7477 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.169  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:44.169  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:44.169  7462  7477 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:44.169  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:44.169  7462  7477 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:16:44.169  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:44.179  1015  1493 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:44.179  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:44.179  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.179  1015  1461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:44.179  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.179  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:44.179  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:44.179  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:44.179  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:44.189  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:44.189  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:44.189  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:44.189  1015  3124 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:16:44.189  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:44.189  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.189  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.189  1015  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:44.189  7462  7477 D BluetoothBondStateMachine: make
,08-17 19:16:44.199  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-17 19:16:44.199  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:44.199  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:16:44.199  7462  7483 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:16:44.209  7484  7484 E Zygote  : MountEmulatedStorage(),
08-17 19:16:44.209  7484  7484 I libpersona: KNOX_SDCARD checking this for 10055
08-17 19:16:44.209  7484  7484 E Zygote  : v2
,08-17 19:16:44.209  7484  7484 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:44.209  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:44.209  1015  3124 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7484 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 19:16:44.209  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:44.209  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.209  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.209  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 19:16:44.209  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.209  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:44.209  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:44.209  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:44.209  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:44.209  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:44.209  7462  7462 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:44.219  7462  7462 D BtGatt.GattService: Received start request. Starting profile...
08-17 19:16:44.219  1015  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:44.219  7462  7462 D BtGatt.GattService: start(),
08-17 19:16:44.219  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 19:16:44.219  7462  7462 D BtGatt.GattService: start()
08-17 19:16:44.219  1015  1254 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.219  7462  7462 I bluedroid: get_profile_interface gatt
08-17 19:16:44.219  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:44.219  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.219  7462  7462 D BtGatt.AdvertiseManager: advertise manager created
08-17 19:16:44.219  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.219  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.219  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:44.219  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:44.219  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:44.219  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:44.219  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.219  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:44.219  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:44.219  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:44.219  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:44.219  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:44.229  1015  1254 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.229  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.229  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:44.229  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.229  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.229  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:44.229  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:44.229  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:44.229  7462  7462 D BtGatt.GattService: mStartError = false
08-17 19:16:44.229  1015  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.229  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:44.229  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-17 19:16:44.229  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.229  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.229  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.239  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:44.239  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:44.239  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:44.239  1015  1254 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.239  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.239  7462  7462 D HeadsetService: Received start request. Starting profile...
08-17 19:16:44.239  7462  7462 D HeadsetService: start()
,08-17 19:16:44.239  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.239  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.239  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:44.239  7462  7462 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 19:16:44.239  7462  7462 D HeadsetStateMachine: make
08-17 19:16:44.239  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:44.239  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.239  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:44.239  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 19:16:44.239  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:44.239  7462  7462 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:44.239  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.239  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.239  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:44.249  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:44.249  1015  1745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:44.249  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.249  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.249  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.249  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:44.249  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.249  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:44.249  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:44.249  1015  3124 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:16:44.249  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:44.249  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-17 19:16:44.249  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:44.249  7462  7477 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:44.249  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.249  1015  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.249  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:44.259  1015  1254 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:16:44.259  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-17 19:16:44.259  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.259  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.259  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-17 19:16:44.259  7462  7462 I bluedroid: get_profile_interface handsfree
,08-17 19:16:44.259  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:44.259  7484  7484 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:44.279  7462  7462 I DualScoManager: Instantiating Dual Sco Manager
08-17 19:16:44.279  7462  7462 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:16:44.279  7462  7462 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:16:44.279  1015  1489 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:16:44.279  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.279  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.279  1015  1489 D SettingsProvider: selectionArgs: false
08-17 19:16:44.279  1015  1489 D SettingsProvider: selectionArgs: 1002
08-17 19:16:44.279  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.279  1015  1489 D SettingsProvider: ret = -1
,08-17 19:16:44.279  7462  7501 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:44.279  7462  7462 D HeadsetService: mStartError = false
08-17 19:16:44.279  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.289  7462  7462 D A2dpService: Received start request. Starting profile...
08-17 19:16:44.289  7462  7501 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 19:16:44.289  7462  7462 D A2dpService: start()
08-17 19:16:44.289  7462  7501 D HeadsetStateMachine: map size, before remove : 0
08-17 19:16:44.289  7462  7501 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:16:44.289  7462  7462 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:44.289  7462  7462 I bluedroid: get_profile_interface avrcp
,08-17 19:16:44.299  7462  7462 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:44.299  7462  7462 D Avrcp   : Initialize Media Controller
08-17 19:16:44.299  7462  7462 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 19:16:44.299  7462  7462 E Avrcp   : getActiveSessions
08-17 19:16:44.299  7462  7462 D Avrcp   : pick active media Controller
08-17 19:16:44.299  7462  7462 D Avrcp   : Get the active Media Controller 
,08-17 19:16:44.299  7484  7484 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:16:44.309  7462  7462 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:44.309  7462  7505 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:44.319  7462  7462 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:16:44.319  7462  7462 D A2dpStateMachine: make
,08-17 19:16:44.319  7462  7462 I bluedroid: get_profile_interface a2dp
,08-17 19:16:44.319  7462  7507 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 19:16:44.319  7462  7462 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:16:44.319  7462  7462 D A2dpService: mStartError = false
08-17 19:16:44.319  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.319  7462  7462 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:44.319  7462  7506 D A2dpStateMachine: Enter Disconnected: -2,
08-17 19:16:44.319  7462  7462 D HidService: Received start request. Starting profile...
08-17 19:16:44.319  7462  7462 D HidService: start()
08-17 19:16:44.319  7462  7462 I bluedroid: get_profile_interface hidhost
,08-17 19:16:44.319  7462  7462 D HidService: setHidService(): set to: null
08-17 19:16:44.319  7462  7462 D HidService: mStartError = false
08-17 19:16:44.319  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:44.319  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-17 19:16:44.319  7462  7462 I BluetoothHealthServiceJni: classInitNative: succeeds,
,08-17 19:16:44.319  7462  7462 D HealthService: Received start request. Starting profile...
,08-17 19:16:44.319  7462  7462 D HealthService: start()
,08-17 19:16:44.329  7462  7462 I bluedroid: get_profile_interface health
08-17 19:16:44.329  7462  7462 D HealthService: mStartError = false
08-17 19:16:44.329  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.329  7462  7462 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:44.329  7462  7462 D PanService: Received start request. Starting profile...
08-17 19:16:44.329  7462  7462 D PanService: start()
,08-17 19:16:44.329  7462  7462 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:44.329  7462  7462 I bluedroid: get_profile_interface pan
,08-17 19:16:44.329  7462  7462 D PanService: mStartError = false
08-17 19:16:44.329  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.329  7462  7505 D BluetoothMediaBrowser: no now playing list
,08-17 19:16:44.329  7462  7505 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:16:44.329  7462  7462 D BluetoothMapService: Received start request. Starting profile...
08-17 19:16:44.329  7462  7462 D BluetoothMapService: start()
,08-17 19:16:44.339  7462  7462 D BluetoothMapService: mStartError = false
,08-17 19:16:44.339  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.339  7462  7462 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 19:16:44.339  7462  7462 D SapService: Received start request. Starting profile...
08-17 19:16:44.339  7462  7462 D SapService: start()
08-17 19:16:44.339  7462  7462 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:44.339  7462  7462 I bluedroid: get_profile_interface sap
08-17 19:16:44.339  7462  7462 D SapService: mStartError = false
08-17 19:16:44.339  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:44.339  7462  7462 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:16:44.339  1439  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:44.339  7484  7484 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-17 19:16:44.339  1439  1439 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 19:16:44.339  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:44.339  1439  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 19:16:44.339  7484  7484 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:16:44.339  7484  7484 D UserAnalysis: Create SecureDbHelper
,08-17 19:16:44.339  7462  7462 D HeadsetStateMachine: Proxy object connected
08-17 19:16:44.339  7462  7462 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 19:16:44.339  7462  7462 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:44.339  7462  7501 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:44.339  7462  7462 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 19:16:44.339  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 19:16:44.339  7462  7501 D HeadsetStateMachine: Disconnected process message: 18
08-17 19:16:44.339  7462  7462 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:44.339  7462  7462 D BluetoothA2dp: Proxy object connected
08-17 19:16:44.339  7462  7462 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:16:44.339  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:44.339  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:16:44.339  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:44.339  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:44.349  7462  7501 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:44.349  7462  7501 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:16:44.349  7462  7501 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:44.349  7484  7484 D IntelligenceServiceApplication: onCreate()
,08-17 19:16:44.359  7484  7484 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 19:16:44.369  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-17 19:16:44.369  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 19:16:44.369  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-17 19:16:44.369  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:44.379  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:16:44.379  1015  1487 I ActivityManager: Killing 7093:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-17 19:16:44.379  7462  7477 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 19:16:44.379  7462  7477 I bluedroid: enable
08-17 19:16:44.379  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-17 19:16:44.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.379  7462  7512 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 19:16:44.379  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:44.379  7462  7477 I bt_hci_bdroid: init
,08-17 19:16:44.399  7514  7514 E Zygote  : MountEmulatedStorage()
,08-17 19:16:44.399  7514  7514 E Zygote  : v2
08-17 19:16:44.399  7514  7514 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:16:44.399  7514  7514 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:44.399  7462  7477 I bt_vendor: bt-vendor : init
08-17 19:16:44.399  7462  7477 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:16:44.399  7462  7477 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 19:16:44.399  7462  7477 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 19:16:44.399  7462  7477 D bt_userial_mct: userial_init
,08-17 19:16:44.399  7462  7477 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:44.399  7462  7477 I bt_vendor: Starting hciattach daemon
08-17 19:16:44.399  7462  7477 I bt_vendor: try to set false
,08-17 19:16:44.399  7462  7477 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 19:16:44.399  7462  7477 I bt_vendor: Starting hciattach daemon
08-17 19:16:44.399  7462  7477 I bt_vendor: try to set true
,08-17 19:16:44.399  1015  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7514 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:16:44.419  7514  7514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:44.419  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-17 19:16:44.419  7514  7514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:44.419  7514  7514 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:44.469  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 19:16:44.469  7538  7538 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:44.479  7514  7514 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:44.479  7514  7514 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:44.489  7540  7540 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 19:16:44.499  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:16:44.509  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 19:16:44.519  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 19:16:44.609   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:44.609   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:44.609  7514  7549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:44.619   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:44.619   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:44.619  7514  7549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:44.759  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-17 19:16:44.759  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 19:16:44.799   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-17 19:16:44.799  7462  7477 I bt_vendor: bluetooth satus is on
,08-17 19:16:44.799  7462  7518 D bt_userial_mct: userial_open(port:0)
08-17 19:16:44.799  7462  7518 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:44.799 , 7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.799  7514  7514 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.799  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.809  7514  7514 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.809  7514  7514 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:44.809  7514  7514 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:44.809  7462  7518 I bt_vendor: Done intiailizing UART
08-17 19:16:44.809  7462  7518 I bt_vendor: Done intiailizing UART
08-17 19:16:44.809  7462  7518 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-17 19:16:44.809  7462  7518 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 19:16:44.809  1015  1493 I ActivityManager: Killing 7108:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-17 19:16:44.809  7462  7563 D bt_userial_mct: Entering userial_read_thread()
08-17 19:16:44.819  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 19:16:44.819  7462  7512 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:16:44.829  7462  7512 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:16:44.829  7462  7512 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:16:44.829  7462  7512 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:16:44.829  7462  7512 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 19:16:44.829  7462  7512 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-17 19:16:44.829  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:44.869  7514  7555 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:16:44.889  1015  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:44.889  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:44.889  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:44.889  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:44.919  7462  7512 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:16:44.919  7462  7512 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40dded1 
,08-17 19:16:44.919  7462  7512 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40dded1 
,08-17 19:16:44.929  7462  7480 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:16:44.929  7462  7480 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:44.939  7462  7480 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:16:44.939  7462  7480 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 19:16:44.939  7462  7480 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:44.939  7462  7480 I bluedroid: getModelRssiValues
,08-17 19:16:44.939  7462  7480 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:44.939  7462  7480 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:44.939  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 19:16:44.939  7462  7480 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:16:44.949  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:44.949  7462  7480 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:44.949  7462  7480 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:44.949  7462  7480 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:44.949  7462  7480 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-17 19:16:44.949  7462  7480 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 19:16:44.949  7462  7480 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-17 19:16:44.949  7462  7480 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-17 19:16:44.949  7462  7480 E bt-btif : btif_sock_init: !vhci_init
08-17 19:16:44.949  7462  7480 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 19:16:44.949  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:44.949  7462  7480 D IOP_DB_BT: db_open: db_open : handle 3027673104l, read 13894 bytes onto local cache
,08-17 19:16:44.949  7462  7480 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 19:16:44.949  7462  7480 D IOP_DB_BT: db_query: result 1
,08-17 19:16:44.949  7462  7563 E bt_mct  : hci lib postload completed
08-17 19:16:44.949  7462  7480 I         : iop_db_open: iop_db_open status 0
,08-17 19:16:44.949  7462  7480 D bte_conf: Device ID record 1 : primary
,08-17 19:16:44.949  7462  7480 D bte_conf:   vendorId            = 0075
08-17 19:16:44.949  7462  7480 D bte_conf:   vendorIdSource      = 0001
08-17 19:16:44.949  7462  7480 D bte_conf:   product             = 0100
08-17 19:16:44.949  7462  7480 D bte_conf:   version             = 0200
08-17 19:16:44.949  7462  7480 D bte_conf:   clientExecutableURL = 
08-17 19:16:44.949  7462  7480 D bte_conf:   serviceDescription  = 
08-17 19:16:44.949  7462  7480 D bte_conf:   documentationURL    = 
08-17 19:16:44.949  7462  7480 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:16:44.959  7462  7480 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:44.959  7462  7477 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:16:44.959  7462  7477 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:16:44.959  7462  7477 D BluetoothAdapterProperties: State =  11
,08-17 19:16:44.959  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:44.959  7462  7477 D BluetoothAdapterProperties: Setting state to 12
08-17 19:16:44.959  7462  7477 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:44.969  7462  7480 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:44.969  7462  7480 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:44.969  7462  7480 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:44.969  1015  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 19:16:44.969  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:44.969  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:44.969  1015  1027 D SettingsProvider: selectionArgs: false
08-17 19:16:44.969  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:44.969  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:44.969  1015  1027 D SettingsProvider: ret = -1
,08-17 19:16:44.969  7462  7477 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:44.969  7462  7477 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.969  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:44.969  1015  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:44.969  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.969  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:44.969  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.969  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.979  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.979  7462  7477 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:44.979  7462  7477 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:16:44.979  7462  7477 D BluetoothAdapterService: starting service from this receiver
,08-17 19:16:44.979  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:44.979  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:44.979  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.979  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.979  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.979  1471  2455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:44.979  1471  2455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:44.989  7462  7481 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:44.989  7462  7477 I BluetoothAdapterState: Entering On State from state = 11
,08-17 19:16:44.989  7462  7472 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:44.989  7462  7472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:44.989  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.989  1439  6982 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:44.989  1439  6982 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:44.989  1439  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:44.989  7462  7462 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:16:44.999  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:44.999  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:44.999  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:44.999  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.999  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:44.999  1439  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:44.999  1439  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:44.999  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:44.999  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:44.999  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:44.999  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.999  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.009  1439  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:45.009  3894  3902 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 19:16:45.009  3894  3902 D Bluetoothsap: Binding service...
08-17 19:16:45.009  7462  7462 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:16:45.009  1015  1487 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:45.009  7462  7569 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:16:45.009  7462  7569 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:45.009  7462  7569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:45.019  3894  3902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:16:45.019  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:45.019  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.019  7462  7569 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-17 19:16:45.019  7462  7569 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:45.019  7462  7569 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:45.019  7462  7569 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@284d299
08-17 19:16:45.019  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.019  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.019  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.019  3894  3902 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 19:16:45.019  3894  3905 D BluetoothPan: Binding service...
,08-17 19:16:45.019  7462  7569 D BluetoothSocket: channel: 19
08-17 19:16:45.019  7462  7569 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:45.019  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:45.019  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 19:16:45.019  3894  3894 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-17 19:16:45.019  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.019  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.019  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.029  3894  3894 D SapProfile: Bluetooth service connected
,08-17 19:16:45.029  3894  3894 D Bluetoothsap: getConnectedDevices()
,08-17 19:16:45.029  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:45.029  1455  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:45.029  6789  6798 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:45.029  6789  6798 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:45.029  3894  3905 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:45.029  3894  3905 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:45.029  3894  3902 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:16:45.029  3894  3894 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:45.029  3894  3894 D PanProfile: Bluetooth service connected
,08-17 19:16:45.029  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-17 19:16:45.029  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.029  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.029  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.029  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.039  1439  6982 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:45.039  3894  3894 D BluetoothMap: Proxy object connected
08-17 19:16:45.039  3894  3894 D MapProfile: Bluetooth service connected
08-17 19:16:45.039  3894  3894 D BluetoothMap: getConnectedDevices()
,08-17 19:16:45.039  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:45.039  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:45.039  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.039  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.039  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.039  1439  6982 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:45.039  3894  3905 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:16:45.039  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 19:16:45.039  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.039  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.039  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:45.039  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.049  3894  3894 D BluetoothPbap: Proxy object connected
08-17 19:16:45.049  3894  3894 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:45.049  1015  1044 D BluetoothPan: Binding service...
,08-17 19:16:45.049  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:45.049  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.049  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:45.049  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:45.049  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:45.049  1471  1838 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:45.049  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:45.049  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:45.049  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.049  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.049  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.049  1471  1838 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:45.049  3894  7570 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:45.059  3894  7570 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:45.059  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:45.059  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.059  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.059  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.059  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.059  3894  3894 D BluetoothA2dp: Proxy object connected
,08-17 19:16:45.059  3894  3894 D A2dpProfile: Bluetooth service connected
08-17 19:16:45.059  2038  2216 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:45.059  2038  2216 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:45.059  3894  3905 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:16:45.059  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:45.059  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.059  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.059  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.059  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.059  3894  3905 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:45.069  3894  3894 D BluetoothInputDevice: Proxy object connected
08-17 19:16:45.069  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:45.069  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:45.069  3894  3894 D HidProfile: Bluetooth service connected
08-17 19:16:45.069  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.069  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.069  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.069  3894  3905 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:45.069  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:45.069  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:45.069  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:45.069  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.069  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:45.069  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:45.069  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:45.069  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:45.069  1171  1185 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:45.069  1015  1015 D BluetoothA2dp: Proxy object connected
,08-17 19:16:45.069  1171  1185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:45.069  7514  7532 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:45.069  7514  7532 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:45.069  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:16:45.069  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:45.079  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:45.079  1439  1439 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@283292e5, true
,08-17 19:16:45.079  1439  1439 D BluetoothHeadset: registerMessageListener
,08-17 19:16:45.079  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:45.079  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:45.079  1171  1171 D BluetoothTile:  getBluetoothState : 12
08-17 19:16:45.079  1845  1845 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:45.089  7462  7470 D HeadsetService: registerMessageListener
,08-17 19:16:45.089  1015  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:45.089  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.089  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:45.089  3894  3894 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:45.089  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.089  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.089  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.089  7462  7470 D HeadsetService: registerMessageListener
,08-17 19:16:45.089  1439  1439 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:16:45.089  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:16:45.099  7462  7501 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:16:45.099  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:45.099  7462  7501 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@60e795e
08-17 19:16:45.099  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:45.099  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:45.099  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:45.099  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:45.099  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:45.099  1015  1745 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:45.099  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:16:45.099  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 19:16:45.099  1015  1134 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:16:45.099  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:45.109  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:16:45.109  3894  3894 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 19:16:45.109  3894  3894 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:16:45.109  3894  3894 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:45.109  3894  3894 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:16:45.109  7462  7574 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:16:45.109  7462  7501 D HeadsetStateMachine: Disconnected process message: 9
,08-17 19:16:45.109  7462  7501 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 19:16:45.109  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null,
,08-17 19:16:45.109  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:45.109  7462  7574 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:45.109  7462  7574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:45.109  7462  7574 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-17 19:16:45.109  7462  7574 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:45.109  7462  7574 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:45.109  7462  7574 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39d8813f
08-17 19:16:45.109  7462  7574 D BluetoothSocket: channel: 5
,08-17 19:16:45.119   284   692 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:45.119   284   692 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:16:45.119   284   692 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:45.119   284   692 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:45.119   284   692 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:16:45.119   284   692 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:16:45.119   284   692 V audio_hw_primary: adev_set_parameters: exit
08-17 19:16:45.119  7462  7501 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:16:45.119  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:45.129  1015  1461 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:45.129  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.129  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.129  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.129  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:45.139  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:45.139  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:45.139  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:45.139  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:45.149  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:45.149  7462  7462 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:45.149  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:45.149  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.149  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.149  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:45.149  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:45.169  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:45.169  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:45.169  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.169  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.169  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.169  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.179  2038  7580 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:45.179  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:45.189  1015  3124 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:45.199  7462  7584 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:45.199  7462  7584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:45.199  7462  7584 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-17 19:16:45.199  7462  7584 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:45.199  7462  7584 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-17 19:16:45.199  7462  7584 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c53bd1
08-17 19:16:45.199  7462  7584 D BluetoothSocket: channel: 12
,08-17 19:16:45.199  7462  7584 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:45.339  1015  1745 I art     : Explicit concurrent mark sweep GC freed 72182(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.300ms total 147.529ms
,08-17 19:16:45.339  1015  1745 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:45.339  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.339  1015  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.339  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.349  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:45.359  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.359  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.359  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.369  2038  7580 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:16:46.769   289   289 E SMD     : DCD OFF,
,08-17 19:16:46.899  6789  6844 D BluetoothAdapter: disable()
,08-17 19:16:46.909  1015  1027 D SettingsProvider: name = bluetooth_on
,08-17 19:16:46.929  7462  7477 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-17 19:16:46.929  1015  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.929  7462  7477 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:46.929  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 19:16:46.929  7462  7477 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:46.929  7462  7477 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:46.929  7462  7477 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:16:46.939  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.939  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.939  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.939  7462  7462 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 19:16:46.939  7462  7477 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:46.939  7462  7477 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:16:46.939  7462  7477 D BluetoothAdapterService: terminating service from this receiver
,08-17 19:16:46.939  7462  7462 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38da5636, channel: 19, state: LISTENING
,08-17 19:16:46.939  7462  7462 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38da5636, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@284d299, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1eff5937mSocket: android.net.LocalSocket@3771eea4 impl:android.net.LocalSocketImpl@910c40d fd:FileDescriptor[74]
08-17 19:16:46.939  7462  7462 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3771eea4 impl:android.net.LocalSocketImpl@910c40d fd:FileDescriptor[74]
,08-17 19:16:46.939  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:46.939  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:46.949  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:46.949  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:46.959  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:46.959  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:46.959  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:46.959  1171  1171 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:46.959  1845  1845 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:16:46.959  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:46.959  1015  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:46.969  1015  1254 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:46.969  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:46.969  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:46.979  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-17 19:16:46.979  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
,08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:46.979  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:46.979  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:46.979  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:46.979  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:16:46.979  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:46.979  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.979  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.979  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:46.979  7462  7477 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:16:46.979  7462  7477 D BluetoothAdapterProperties: mDiscovering is false
08-17 19:16:46.989  1015  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 19:16:46.989  7462  7462 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26ed9fc2, channel: 5, state: LISTENING
08-17 19:16:46.989  7462  7462 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26ed9fc2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39d8813f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@be651d3mSocket: android.net.LocalSocket@1a315110 impl:android.net.LocalSocketImpl@30129409 fd:FileDescriptor[76]
08-17 19:16:46.989  7462  7462 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a315110 impl:android.net.LocalSocketImpl@30129409 fd:FileDescriptor[76]
,08-17 19:16:46.989  7462  7462 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:46.989  7462  7462 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28f9f60e, channel: 12, state: LISTENING
08-17 19:16:46.989  7462  7462 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28f9f60e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c53bd1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@383a382fmSocket: android.net.LocalSocket@11426e3c impl:android.net.LocalSocketImpl@154767c5 fd:FileDescriptor[80]
08-17 19:16:46.989  7462  7462 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11426e3c impl:android.net.LocalSocketImpl@154767c5 fd:FileDescriptor[80]
,08-17 19:16:46.989  7462  7584 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:16:46.989  7462  7584 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:46.989  7462  7477 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:46.989  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.989  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:46.989  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:46.989  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:46.999  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:46.999  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:46.999  6789  6789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:46.999  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:46.999  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:46.999  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.999  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.009  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.009  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:47.009  7462  7480 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:47.009  7462  7480 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:47.009  3894  3894 D BluetoothPbap: Proxy object disconnected
,08-17 19:16:47.009  3894  3894 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:47.009  7462  7477 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:16:47.009  7462  7477 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 19:16:47.009  7462  7477 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:16:47.009  7462  7477 E bt-btif : cmd socket is not created
08-17 19:16:47.019  7462  7477 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:16:47.019  7462  7512 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 19:16:47.019  7462  7512 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:16:47.019  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:47.019  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:47.019  7462  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:47.019  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.019  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.019  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:47.019  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:47.029  7462  7462 V BluetoothOppManager: cleanUp...
,08-17 19:16:47.029  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:47.029  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:16:47.069  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:47.069  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:47.219  7462  7563 I bt_userial_mct: exiting userial_read_thread
,08-17 19:16:47.219  7462  7563 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:16:47.219  7462  7480 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:16:47.219  7462  7518 I bt_vendor: hw_epilog_process
,08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:47.219  7462  7480 D bt_userial_mct: userial_close
08-17 19:16:47.219  7462  7480 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 19:16:47.219  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:47.219  7462  7512 W bt-btif : ag scb idx 1 not allocated
08-17 19:16:47.219  7462  7512 W bt-btif : ag scb idx 2 not allocated
08-17 19:16:47.219  7462  7512 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 19:16:47.219  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:16:47.219  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-17 19:16:47.219  1015  1134 D BatteryService: stay LED for fully charged
08-17 19:16:47.219  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-17 19:16:47.229  1015  1015 I MotionRecognitionService: Plugged
08-17 19:16:47.229  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:47.229  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 19:16:47.229  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:47.229  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:16:47.229  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:47.249  7462  7462 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:47.249  7462  7501 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:47.249  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 19:16:47.259  1171  1171 D SViewCoverView: level :100 plugged : 2
,08-17 19:16:47.259  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:47.259  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:47.259  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:48.029  7462  7480 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 19:16:48.029  7462  7480 I bt_vendor: bluetooth satus is on
08-17 19:16:48.029  7462  7480 I bt_vendor: bt-vendor : resetting BT status,
08-17 19:16:48.029  7462  7480 I bt_vendor: Starting hciattach daemon
08-17 19:16:48.029  7462  7480 I bt_vendor: try to set false
08-17 19:16:48.039  7462  7480 I bt_vendor: Starting hciattach daemon
08-17 19:16:48.039  7462  7480 I bt_vendor: try to set false
,08-17 19:16:48.039  7462  7480 I bt_vendor: cleanup
,08-17 19:16:48.039  7462  7512 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 19:16:48.039  7462  7480 I GKI_LINUX: GKI_exit_task 0 done
,08-17 19:16:48.039  7462  7480 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 19:16:48.039  7462  7477 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 19:16:48.039  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:48.039  7462  7477 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:48.039  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.039  7462  7477 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 19:16:48.039  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:48.039  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:48.039  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.039  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:48.039  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 19:16:48.039  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.039  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:48.039  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.039  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:48.039  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:48.039  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
08-17 19:16:48.049  1015  1745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 19:16:48.039  7462  7462 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:16:48.049  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:48.049  7462  7462 D BtGatt.GattService: Received stop request...Stopping profile...,
08-17 19:16:48.049  7462  7462 D BtGatt.GattService: stop()
08-17 19:16:48.049  7462  7462 D BtGatt.AdvertiseManager: advertise clients cleared,
08-17 19:16:48.049  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.049  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:48.049  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.049  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 19:16:48.049  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.049  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:48.049  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:48.049  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:48.049  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:48.049  7462  7462 D HeadsetService: Received stop request...Stopping profile...
08-17 19:16:48.049  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.049  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.049  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.049  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:48.049  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:48.049  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 19:16:48.049  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:48.049  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.049  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.049  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.059  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 19:16:48.059  3894  3894 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:48.059  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:48.059  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:48.059  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:48.059  1015  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:48.059  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.059  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.059  1015  1745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:48.059  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.059  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 19:16:48.059  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.059  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:48.059  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:48.059  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:48.069  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.069  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.069  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:16:48.069  1015  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:48.069  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.069  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.069  1015  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.069  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:48.069  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:48.069  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-17 19:16:48.069  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.069  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.069  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:48.069  7462  7477 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:48.069  7462  7477 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:48.069  7462  7477 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 19:16:48.069  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 19:16:48.079  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:48.079  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:48.079  7462  7462 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:48.079  7462  7462 D A2dpService: Received stop request...Stopping profile...
,08-17 19:16:48.079  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:48.079  7462  7506 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:48.079  7462  7462 D HidService: Received stop request...Stopping profile...
08-17 19:16:48.079  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:48.079  7462  7462 D HidService: Stopping Bluetooth HidService
08-17 19:16:48.079  7462  7462 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:48.079  7462  7462 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:48.079  7462  7462 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:48.079  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:48.079  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:16:48.079  7462  7462 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:16:48.079  7462  7462 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:16:48.079  3894  3894 D BluetoothA2dp: Proxy object disconnected
,08-17 19:16:48.079  7462  7462 D HealthService: Received stop request...Stopping profile...
08-17 19:16:48.079  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:48.079  3894  3894 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:48.079  3894  3894 D BluetoothInputDevice: Proxy object disconnected
,08-17 19:16:48.089  3894  3894 D HidProfile: Bluetooth service disconnected
,08-17 19:16:48.089  7462  7462 D PanService: Received stop request...Stopping profile...
08-17 19:16:48.089  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:48.089  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:48.089  3894  3894 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:48.089  3894  3894 D PanProfile: Bluetooth service disconnected
,08-17 19:16:48.089  7462  7462 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:48.089  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:48.089  7462  7462 D SapService: Received stop request...Stopping profile...
,08-17 19:16:48.089  7462  7462 D SapService: Stopping Bluetooth SapService
,08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:48.099  3894  3894 D BluetoothMap: Proxy object disconnected
08-17 19:16:48.099  3894  3894 D MapProfile: Bluetooth service disconnected
,08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:16:48.099  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:48.099  7462  7462 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:16:48.099  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:48.099  7462  7507 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 19:16:48.099  7462  7462 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:48.099  7462  7462 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:48.099  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:48.099  7462  7462 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:48.099  7462  7462 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:48.099  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:48.099  7462  7462 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:48.099  7462  7462 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 19:16:48.099  3894  3894 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:16:48.099  3894  3894 D SapProfile: Bluetooth service disconnected
,08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
,08-17 19:16:48.099  7462  7462 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:48.099  7462  7462 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 19:16:48.099  7462  7462 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:16:48.099  7462  7462 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:48.099  7462  7462 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:48.099  7462  7477 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 19:16:48.099  7462  7477 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:48.099  7462  7477 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 19:16:48.099  7462  7477 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:48.099  7462  7477 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 19:16:48.099  7462  7477 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:48.099  7462  7477 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:16:48.099  7462  7477 I BluetoothAdapterState: Entering OffState
,08-17 19:16:48.109  1471  1838 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.109  1471  1838 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.109  7462  7572 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:48.109  7462  7571 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.109  7462  7571 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.109  1439  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.109  1439  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.109  3894  3902 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 19:16:48.109  3894  3902 D Bluetoothsap: Unbinding service...
,08-17 19:16:48.119  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.119  1455  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.119  6789  6798 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.119  6789  6798 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.119  6789  6798 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:16:48.119  6789  6798 D BluetoothLeAdvertiser: Exit stop advertising
,08-17 19:16:48.119  6789  6798 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-17 19:16:48.119  6789  6798 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:16:48.119  3894  3905 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:48.119  3894  3905 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:48.119  3894  3902 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:48.119  3894  7570 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:48.119  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.119  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.119  3894  3905 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:48.129  2038  2047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.129  2038  2047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.129  3894  3902 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:48.129  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:48.129  1171  3239 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:48.129  1171  3239 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.129  7514  7537 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:48.129  7514  7537 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:48.129  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 19:16:48.129  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:48.139  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:48.139  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:16:48.139  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:48.149  7462  7480 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 19:16:48.149  7462  7462 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:16:48.149  7462  7462 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 19:16:48.149  7462  7462 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 19:16:48.149  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:48.149  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:48.149  1171  1756 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:48.149  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:48.149  1171  1171 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:48.149  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:48.149  1171  1171 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:48.149  1845  1845 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:48.149  1015  1509 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:48.149  1015  1461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:48.149  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:48.149  1171  1756 D BluetoothAdapter: 747214870: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:48.149  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:48.149  2038  2221 D BluetoothAdapter: 121746621: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:48.149  2038  2221 D BluetoothAdapter: 121746621: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:48.159  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:48.159  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:48.159  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:48.159  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:48.159  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.159  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.159  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:48.159  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:48.159  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:48.159  1015  1745 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:16:48.159  7462  7462 I art     : System.exit called, status: 0
08-17 19:16:48.159  7462  7462 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 19:16:48.159  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.159  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.169  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.169  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:48.169  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:48.169  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:48.179  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:48.179  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:48.259  1015  1509 I ActivityManager: Process com.android.bluetooth (pid 7462)(adj 0) has died(46,717)
,08-17 19:16:48.259  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:48.269  1015  3124 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:48.269  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.269  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.269  1015  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:48.269  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:48.279  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:48.279  2038  7602 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:48.289  1015  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:48.289  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.289  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:48.289  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:48.299  2038  7602 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:16:49.779   289   289 E SMD     : DCD OFF,
,08-17 19:16:49.929  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:49.929  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:52.779   289   289 E SMD     : DCD OFF,
,08-17 19:16:52.929  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 19:16:52.929  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@321da4c9 added. We now have 6 listener(s)
08-17 19:16:52.929  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-17 19:16:52.929  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:52.929  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b4a97ce added. We now have 7 listener(s),
08-17 19:16:52.929  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:52.929  6789  6844 I System.out: IsBluetoothEnabled
08-17 19:16:52.929  6789  6844 D BluetoothAdapter: disable(),
08-17 19:16:52.929  1015  1745 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-17 19:16:52.939  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:52.939  6789  6844 D BluetoothAdapter: enable(),
,08-17 19:16:52.939  1015  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:52.939  1015  1493 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:16:52.939  1015  1493 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:52.939  1015  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:52.939  1015  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:52.939  1015  1493 D SettingsProvider: name = bluetooth_on
,08-17 19:16:52.949  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-17 19:16:52.949  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:52.949  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,08-17 19:16:52.949  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
08-17 19:16:52.949  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:52.949  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:52.949  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:52.949  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:52.969  7608  7608 E Zygote  : MountEmulatedStorage(),
08-17 19:16:52.969  7608  7608 E Zygote  : v2
08-17 19:16:52.969  7608  7608 I libpersona: KNOX_SDCARD checking this for 1002
,08-17 19:16:52.969  7608  7608 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:52.969  7608  7608 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:52.979  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7608 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:16:52.979  7608  7608 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:52.979  7608  7608 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:53.009  7608  7608 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:53.009  7608  7608 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:53.029  7608  7608 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:16:53.029  7608  7608 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:53.049  7608  7608 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:16:53.079  7608  7608 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding A2dpService
08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding HidService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding HealthService
08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding PanService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding SapService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding SapClientService
08-17 19:16:53.089  7608  7608 D BtSettings.ProfileConfig: Adding HidDevService
08-17 19:16:53.089  7608  7608 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:16:53.089  1015  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-17 19:16:53.089  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.089  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.089  1015  1487 D SettingsProvider: selectionArgs: false
08-17 19:16:53.089  1015  1487 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.089  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.089  1015  1487 D SettingsProvider: ret = -1
,08-17 19:16:53.089  1015  1745 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 19:16:53.089  1015  1745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.089  1015  1745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.089  1015  1745 D SettingsProvider: selectionArgs: false
08-17 19:16:53.089  1015  1745 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.089  1015  1745 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.089  1015  1745 D SettingsProvider: ret = -1
,08-17 19:16:53.089  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 19:16:53.089  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.089  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.089  1015  1028 D SettingsProvider: selectionArgs: false
,08-17 19:16:53.089  1015  1028 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.089  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.089  1015  1028 D SettingsProvider: ret = -1
,08-17 19:16:53.089  1015  1254 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-17 19:16:53.089  1015  1254 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.089  1015  1254 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:53.089  1015  1254 D SettingsProvider: selectionArgs: false
08-17 19:16:53.089  1015  1254 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:53.089  1015  1254 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1254 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  3124 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:16:53.099  1015  3124 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  3124 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  3124 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  3124 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  3124 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  3124 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:16:53.099  1015  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  1493 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  1493 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1493 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:16:53.099  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  1027 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  1027 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1027 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1134 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:16:53.099  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:53.099  1015  1134 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1134 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:53.099  1015  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:53.099  1015  1509 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  1509 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:53.099  1015  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1509 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1461 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.099  1015  1461 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1461 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  1461 D SettingsProvider: selectionArgs: false
08-17 19:16:53.099  1015  1461 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1461 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1461 D SettingsProvider: ret = -1
,08-17 19:16:53.099  1015  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:16:53.099  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  1489 D SettingsProvider: selectionArgs: false,
08-17 19:16:53.099  1015  1489 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1489 D SettingsProvider: ret = -1
08-17 19:16:53.099  1015  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-17 19:16:53.099  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.099  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.099  1015  1487 D SettingsProvider: selectionArgs: false
,08-17 19:16:53.099  1015  1487 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.099  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.099  1015  1487 D SettingsProvider: ret = -1
,08-17 19:16:53.119  7608  7608 D BluetoothAdapterState: make
,08-17 19:16:53.119  7608  7608 I bluedroid: init,
,08-17 19:16:53.119  7608  7623 I BluetoothAdapterState: Entering OffState
,08-17 19:16:53.129  7608  7608 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-17 19:16:53.129  7608  7608 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 19:16:53.129  7608  7608 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 19:16:53.129  7608  7608 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:53.129  7608  7608 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-17 19:16:53.129  7608  7608 I bluedroid: get_profile_interface socket,
08-17 19:16:53.129  7608  7608 I bluedroid: get_profile_interface map_client
08-17 19:16:53.129  7608  7626 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:16:53.129  7608  7608 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:16:53.139  7608  7626 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 19:16:53.139  7608  7626 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:53.139  7608  7626 I bluedroid: getModelRssiValues
08-17 19:16:53.139  7608  7626 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:53.139  7608  7626 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:53.139  7608  7608 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:53.139  1015  1489 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:53.139  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.139  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.139  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.139  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.139  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 19:16:53.139  7608  7616 I bluedroid: config_hci_snoop_log
08-17 19:16:53.139  7608  7626 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:16:53.149  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:16:53.149  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:16:53.149  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:16:53.149  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:16:53.149  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:53.149  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:53.149  7608  7608 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 19:16:53.149  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:53.159  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:16:53.159  7608  7623 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:16:53.159  7608  7623 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:16:53.159  7608  7623 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 19:16:53.159  7608  7623 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:53.159  7608  7623 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:16:53.169  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:53.169  7608  7623 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:53.169  7608  7623 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:16:53.169  7608  7623 D BluetoothSecureManager: getInstant: null
,08-17 19:16:53.169  7608  7623 D BluetoothSecureManager: calling getMethod for getService
08-17 19:16:53.169  7608  7623 D BluetoothSecureManager: calling getService
,08-17 19:16:53.169  7608  7623 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@25ece57c
,08-17 19:16:53.169  1015  1134 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 19:16:53.169  1015  1134 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-17 19:16:53.169  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:53.169  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
08-17 19:16:53.169  7608  7623 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:53.169  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:53.169  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-17 19:16:53.169  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:53.179  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:53.179  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:53.179  1171  1171 D BluetoothTile:  getBluetoothState : 11
,08-17 19:16:53.179  1845  1845 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:53.189  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:53.189  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:16:53.189  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:53.189  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:53.189  1015  1509 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:53.199  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:53.199  7608  7623 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:16:53.199  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:53.199  7608  7623 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:53.199  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.199  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:53.199  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.199  7608  7623 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.199  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:53.199  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.199  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:53.199  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:53.199  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:16:53.199  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:53.199  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:53.209  7608  7623 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:53.209  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:53.209  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:53.209  7608  7623 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:16:53.209  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:53.209  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:53.219  7608  7623 D BluetoothBondStateMachine: make
,08-17 19:16:53.219  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:53.219  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:53.219  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:16:53.229  7608  7630 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:16:53.229  1015  3124 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:53.229  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.229  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.229  1015  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.229  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.229  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:53.229  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:53.229  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:53.229  1015  1745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:53.229  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.229  7608  7608 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:53.229  7608  7608 D BtGatt.GattService: Received start request. Starting profile...
,08-17 19:16:53.229  7608  7608 D BtGatt.GattService: start()
08-17 19:16:53.229  7608  7608 D BtGatt.GattService: start()
,08-17 19:16:53.229  7608  7608 I bluedroid: get_profile_interface gatt
,08-17 19:16:53.229  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:53.229  7608  7608 D BtGatt.AdvertiseManager: advertise manager created
08-17 19:16:53.239  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.239  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.239  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.239  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:53.239  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:53.239  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:53.239  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:53.239  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.239  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.239  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.239  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.239  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:53.239  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:53.239  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:53.249  1015  3124 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:53.249  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.249  1015  3124 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.249  1015  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.249  1015  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.249  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:53.249  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:53.249  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:53.249  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:53.249  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.249  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.249  7608  7608 D BtGatt.GattService: mStartError = false
08-17 19:16:53.249  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:53.249  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:53.249  7608  7608 D HeadsetService: Received start request. Starting profile...
08-17 19:16:53.249  7608  7608 D HeadsetService: start()
,08-17 19:16:53.259  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.259  7608  7608 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 19:16:53.259  7608  7608 D HeadsetStateMachine: make
,08-17 19:16:53.259  7608  7608 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:53.259  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:53.259  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:53.259  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:53.269  1015  1254 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:16:53.269  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.269  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.269  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.269  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:53.269  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:53.269  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.269  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.269  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.269  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.269  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:53.269  1015  1134 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 19:16:53.269  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:53.269  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-17 19:16:53.269  7608  7623 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:53.269  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.269  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.269  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:53.279  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:53.279  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.279  7608  7608 I bluedroid: get_profile_interface handsfree
08-17 19:16:53.279  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.279  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.279  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:53.279  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 19:16:53.279  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:53.279  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-17 19:16:53.279  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.279  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:53.279  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:53.279  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.279  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:53.279  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:53.279  7608  7623 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:53.279  7608  7623 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:53.279  7608  7623 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:53.299  7608  7608 I DualScoManager: Instantiating Dual Sco Manager
,08-17 19:16:53.299  7608  7608 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:16:53.299  7608  7608 D BluetoothAtMessage: createCMTIContentObservers
08-17 19:16:53.299  1015  1487 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:16:53.299  1015  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.299  1015  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.299  1015  1487 D SettingsProvider: selectionArgs: false
08-17 19:16:53.299  1015  1487 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.299  1015  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.299  1015  1487 D SettingsProvider: ret = -1
08-17 19:16:53.299  7608  7636 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:53.299  7608  7608 D HeadsetService: mStartError = false
08-17 19:16:53.299  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:53.309  7608  7636 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 19:16:53.309  7608  7636 D HeadsetStateMachine: map size, before remove : 0
08-17 19:16:53.309  7608  7636 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:16:53.309  7608  7608 D A2dpService: Received start request. Starting profile...
08-17 19:16:53.309  7608  7608 D A2dpService: start()
,08-17 19:16:53.309  7608  7608 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:53.309  7608  7608 I bluedroid: get_profile_interface avrcp
,08-17 19:16:53.319  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:53.319  7608  7608 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:53.319  7608  7608 D Avrcp   : Initialize Media Controller
08-17 19:16:53.319  7608  7608 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 19:16:53.319  7608  7608 E Avrcp   : getActiveSessions
08-17 19:16:53.319  7608  7608 D Avrcp   : pick active media Controller
08-17 19:16:53.319  7608  7608 D Avrcp   : Get the active Media Controller 
,08-17 19:16:53.319  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:53.339  7608  7608 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:53.339  7608  7637 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:53.339  7608  7608 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-17 19:16:53.339  7608  7608 D A2dpStateMachine: make
,08-17 19:16:53.349  7608  7608 I bluedroid: get_profile_interface a2dp
,08-17 19:16:53.349  7608  7639 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 19:16:53.349  7608  7608 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:16:53.349  7608  7608 D A2dpService: mStartError = false
08-17 19:16:53.349  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:53.349  7608  7608 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:53.349  7608  7608 D HidService: Received start request. Starting profile...
08-17 19:16:53.349  7608  7608 D HidService: start()
08-17 19:16:53.349  7608  7608 I bluedroid: get_profile_interface hidhost
08-17 19:16:53.349  7608  7608 D HidService: setHidService(): set to: null
08-17 19:16:53.349  7608  7608 D HidService: mStartError = false
08-17 19:16:53.349  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:53.349  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 19:16:53.349  7608  7608 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:16:53.349  7608  7638 D A2dpStateMachine: Enter Disconnected: -2
08-17 19:16:53.349  7608  7608 D HealthService: Received start request. Starting profile...
08-17 19:16:53.349  7608  7608 D HealthService: start()
,08-17 19:16:53.359  7608  7637 D BluetoothMediaBrowser: no now playing list
08-17 19:16:53.359  7608  7637 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:16:53.359  7608  7608 I bluedroid: get_profile_interface health
,08-17 19:16:53.359  7608  7608 D HealthService: mStartError = false
08-17 19:16:53.359  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:53.359  7608  7608 D HeadsetStateMachine: Try to query the phonestate on bind
08-17 19:16:53.359  1439  7595 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:53.359  1439  1439 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 19:16:53.359  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:53.359  1439  7595 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 19:16:53.359  7608  7608 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:53.359  7608  7608 D PanService: Received start request. Starting profile...
08-17 19:16:53.359  7608  7608 D PanService: start()
08-17 19:16:53.359  7608  7608 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:53.359  7608  7608 I bluedroid: get_profile_interface pan
,08-17 19:16:53.359  7608  7608 D PanService: mStartError = false,
08-17 19:16:53.359  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:53.359  7608  7608 D HeadsetStateMachine: Proxy object connected
,08-17 19:16:53.369  7608  7608 D BluetoothMapService: Received start request. Starting profile...
08-17 19:16:53.369  7608  7608 D BluetoothMapService: start()
,08-17 19:16:53.369  7608  7608 D BluetoothMapService: mStartError = false
08-17 19:16:53.369  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:53.369  7608  7608 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 19:16:53.369  7608  7636 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:53.369  7608  7608 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 19:16:53.369  7608  7608 D SapService: Received start request. Starting profile...
08-17 19:16:53.369  7608  7608 D SapService: start()
08-17 19:16:53.369  7608  7608 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:53.369  7608  7608 I bluedroid: get_profile_interface sap
08-17 19:16:53.369  7608  7608 D SapService: mStartError = false
08-17 19:16:53.369  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
08-17 19:16:53.369  7608  7608 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:53.369  7608  7608 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 19:16:53.369  7608  7608 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:53.369  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 19:16:53.369  7608  7608 D BluetoothA2dp: Proxy object connected
08-17 19:16:53.369  7608  7636 D HeadsetStateMachine: Disconnected process message: 18
08-17 19:16:53.369  7608  7608 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:16:53.369  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:53.369  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-17 19:16:53.369  7608  7636 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:53.369  7608  7636 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:16:53.369  7608  7636 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:53.379  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:53.379  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:53.399  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:16:53.399  7608  7608 E BluetoothAdapterService(636738935): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:53.399  7608  7623 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 19:16:53.399  7608  7623 I bluedroid: enable
08-17 19:16:53.399  7608  7623 I bt_hci_bdroid: init
,08-17 19:16:53.409  7608  7644 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 19:16:53.409  7608  7623 I bt_vendor: bt-vendor : init
08-17 19:16:53.409  7608  7623 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:16:53.409  7608  7623 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 19:16:53.409  7608  7623 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 19:16:53.409  7608  7623 D bt_userial_mct: userial_init
,08-17 19:16:53.409  7608  7623 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:53.409  7608  7623 I bt_vendor: Starting hciattach daemon
,08-17 19:16:53.409  7608  7623 I bt_vendor: try to set false
,08-17 19:16:53.409  7608  7623 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 19:16:53.409  7608  7623 I bt_vendor: Starting hciattach daemon
08-17 19:16:53.409  7608  7623 I bt_vendor: try to set true
,08-17 19:16:53.429  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 19:16:53.469  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 19:16:53.479  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:53.489  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:16:53.499  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:16:53.509  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:16:53.519  7660  7660 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 19:16:53.719  1015  3359 D SSRM:n  : SIOP:: AP = 320,
,08-17 19:16:53.739  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-17 19:16:53.749  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:53.769  7608  7623 I bt_vendor: bluetooth satus is on
08-17 19:16:53.769  7608  7646 D bt_userial_mct: userial_open(port:0)
08-17 19:16:53.769  7608  7646 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 19:16:53.769  7608  7646 I bt_vendor: Done intiailizing UART,
08-17 19:16:53.769  7608  7646 I bt_vendor: Done intiailizing UART
08-17 19:16:53.769  7608  7646 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-17 19:16:53.769  7608  7646 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-17 19:16:53.779  7608  7666 D bt_userial_mct: Entering userial_read_thread()
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_PAN
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_GATT
,08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 19:16:53.779  7608  7644 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 19:16:53.879  7608  7644 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:16:53.879  7608  7644 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40dded1 
,08-17 19:16:53.879  7608  7644 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40dded1 
,08-17 19:16:53.899  7608  7626 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:16:53.899  7608  7626 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:53.899  7608  7626 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:16:53.899  7608  7626 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 19:16:53.899  7608  7626 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:53.899  7608  7626 I bluedroid: getModelRssiValues
,08-17 19:16:53.899  7608  7626 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:53.899  7608  7626 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:53.899  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 19:16:53.909  7608  7626 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:16:53.909  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 19:16:53.919  7608  7626 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:53.919  7608  7626 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:53.919  7608  7626 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:53.919  7608  7626 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-17 19:16:53.919  7608  7626 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-17 19:16:53.919  7608  7626 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 19:16:53.919  7608  7626 E bt-btif : btif_sock_init: !radio_req && !rfc_init,
08-17 19:16:53.919  7608  7626 E bt-btif : btif_sock_init: !vhci_init
08-17 19:16:53.919  7608  7626 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 19:16:53.919  7608  7626 D IOP_DB_BT: db_open: db_open : handle 3027697680l, read 13894 bytes onto local cache
08-17 19:16:53.919  7608  7626 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-17 19:16:53.919  7608  7666 E bt_mct  : hci lib postload completed,
08-17 19:16:53.919  7608  7626 D IOP_DB_BT: db_query: result 1
,08-17 19:16:53.919  7608  7626 I         : iop_db_open: iop_db_open status 0
08-17 19:16:53.919  7608  7626 D bte_conf: Device ID record 1 : primary,
08-17 19:16:53.919  7608  7626 D bte_conf:   vendorId            = 0075
,08-17 19:16:53.919  7608  7626 D bte_conf:   vendorIdSource      = 0001
08-17 19:16:53.919  7608  7626 D bte_conf:   product             = 0100
08-17 19:16:53.919  7608  7626 D bte_conf:   version             = 0200
08-17 19:16:53.919  7608  7626 D bte_conf:   clientExecutableURL = 
,08-17 19:16:53.919  7608  7626 D bte_conf:   serviceDescription  = 
08-17 19:16:53.919  7608  7626 D bte_conf:   documentationURL    = 
08-17 19:16:53.919  7608  7626 D bte_conf: bte_load_did_conf no section named DID2.
08-17 19:16:53.919  7608  7626 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:53.929  7608  7623 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 19:16:53.929  7608  7623 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:16:53.929  7608  7623 D BluetoothAdapterProperties: State =  11
08-17 19:16:53.929  1015  1254 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:53.929  7608  7626 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:53.929  7608  7626 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:53.929  7608  7626 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:53.929  7608  7623 D BluetoothAdapterProperties: Setting state to 12
08-17 19:16:53.929  7608  7623 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:53.939  1015  1134 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 19:16:53.939  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:53.939  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:53.939  1015  1134 D SettingsProvider: selectionArgs: false
08-17 19:16:53.939  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 19:16:53.939  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:53.939  1015  1134 D SettingsProvider: ret = -1
08-17 19:16:53.939  7608  7623 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:53.939  7608  7623 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:16:53.939  1015  1254 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:53.939  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.939  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.939  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.939  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.949  7608  7623 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:53.949  7608  7623 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:16:53.949  7608  7623 D BluetoothAdapterService: starting service from this receiver
,08-17 19:16:53.949  1015  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:53.949  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.949  1471  2455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:53.949  1471  2455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:53.949  7608  7627 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:53.949  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:53.949  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:53.949  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.949  1439  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:53.949  1439  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:53.959  7608  7623 I BluetoothAdapterState: Entering On State from state = 11
,08-17 19:16:53.959  1439  6982 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:53.959  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:53.959  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:53.959  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.959  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.959  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:53.959  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:53.969  1439  6982 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:53.969  1439  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:53.969  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:53.969  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:53.969  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.969  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.969  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.969  1439  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:53.969  3894  7570 D Bluetoothsap: onBluetoothStateChange: up=true
,08-17 19:16:53.969  3894  7570 D Bluetoothsap: Binding service...
,08-17 19:16:53.979  7608  7608 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:16:53.979  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:53.979  3894  7570 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:16:53.979  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:53.979  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:53.979  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:53.979  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.979  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.979  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.989  3894  7570 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 19:16:53.989  3894  3902 D BluetoothPan: Binding service...
,08-17 19:16:53.989  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:53.989  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:53.989  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:53.989  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:53.989  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:53.989  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:53.989  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:53.989  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@105796ef added. We now have 8 listener(s)
08-17 19:16:53.989  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:53.989  7608  7608 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:16:53.999  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:53.999  1015  1254 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:53.999  1455  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:53.999  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:53.999  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:53.999  1015  1027 D SecContentProvider2: mCursor = null
,08-17 19:16:53.999  1015  1027 D SettingsProvider: name = wifi_on
08-17 19:16:53.999  1015  1027 D WifiService: setWifiEnabled: false pid=6789, uid=10171
08-17 19:16:53.999  6789  6797 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:53.999  6789  6797 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:53.999  3894  3905 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:53.999  3894  3905 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:53.999  3894  3894 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 19:16:53.999  3894  3894 D SapProfile: Bluetooth service connected
08-17 19:16:53.999  3894  3894 D Bluetoothsap: getConnectedDevices()
,08-17 19:16:53.999  7608  7670 V BluetoothPbapService: PBAP Service initSocket try: 0
08-17 19:16:53.999  3894  3902 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:54.009  3894  3894 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:54.009  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:16:54.009  3894  3894 D PanProfile: Bluetooth service connected
08-17 19:16:54.009  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 19:16:54.009  7608  7670 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:54.009  7608  7670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:54.009  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.009  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.009  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.009  3894  3894 D BluetoothMap: Proxy object connected
08-17 19:16:54.009  7608  7670 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-17 19:16:54.009  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:54.009  7608  7670 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:54.009  7608  7670 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:54.009  7608  7670 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@284d299
08-17 19:16:54.009  1439  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:54.009  7608  7670 D BluetoothSocket: channel: 19
08-17 19:16:54.009  7608  7670 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:54.009  3894  3894 D MapProfile: Bluetooth service connected
08-17 19:16:54.009  3894  3894 D BluetoothMap: getConnectedDevices()
08-17 19:16:54.019  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:54.019  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:54.019  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:54.019  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.019  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.019  1439  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:54.019  3894  3905 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:16:54.019  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:54.019  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 19:16:54.019  1015  1027 D SecContentProvider2: mCursor = null
,08-17 19:16:54.019  1015  1027 D WifiService: setWifiEnabled: true pid=6789, uid=10171
08-17 19:16:54.019  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:54.019  1015  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:54.019  1015  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6789, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:54.019  1015  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:54.019  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:54.019  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:54.019  1015  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:54.019  1015  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:54.019  1015  1027 D SettingsProvider: name = wifi_on
,08-17 19:16:54.019  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 19:16:54.019  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.019  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.019  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.019  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.029  1015  1044 D BluetoothPan: Binding service...
08-17 19:16:54.029  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:54.029  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 19:16:54.029  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:54.029  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:54.029  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:54.029  1471  1838 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:54.029  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:54.029  3894  3894 D BluetoothPbap: Proxy object connected
08-17 19:16:54.029  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:54.029  3894  3894 D PbapServerProfile: Bluetooth service connected
08-17 19:16:54.029  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.029  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.029  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-17 19:16:54.029  1471  1838 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:54.029  3894  7570 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:54.029  3894  7570 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:54.029  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:54.029  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.039  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.039  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.039  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.039  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:16:54.039  2038  2215 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:54.039  2038  2215 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:54.039  7608  7628 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:54.039  7608  7628 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:54.039  3894  7570 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:16:54.039  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:54.039  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.049  3894  3894 D BluetoothA2dp: Proxy object connected
08-17 19:16:54.049  3894  3894 D A2dpProfile: Bluetooth service connected
,08-17 19:16:54.049  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.049  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.049  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.049  3894  3902 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:54.049  3894  3894 D BluetoothInputDevice: Proxy object connected
08-17 19:16:54.049  3894  3894 D HidProfile: Bluetooth service connected
,08-17 19:16:54.049  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:54.049  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:54.049  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.049  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.049  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.049  3894  3902 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:54.049  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:54.059  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:54.059  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:54.059  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:54.059  1015  1015 D BluetoothA2dp: Proxy object connected
08-17 19:16:54.059  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:54.059  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:54.059  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:54.059  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:54.059  1171  1185 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:54.059  1171  1185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:54.069  7514  7532 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:54.069  7514  7532 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:54.069  3894  3894 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:54.069  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:16:54.069  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:54.079  1171  1171 D BluetoothTile:  onBluetoothStateChange:,
,08-17 19:16:54.079  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:54.079  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:54.079  1171  1171 D BluetoothTile:  getBluetoothState : 12
,08-17 19:16:54.079  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:54.079  1439  1439 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@86881ba, true
08-17 19:16:54.079  1439  1439 D BluetoothHeadset: registerMessageListener
,08-17 19:16:54.079  1015  1254 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:54.079  1015  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:16:54.089  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:54.089  1845  1845 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:54.089  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:54.089  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.089  7608  7616 D HeadsetService: registerMessageListener
,08-17 19:16:54.089  7608  7616 D HeadsetService: registerMessageListener
08-17 19:16:54.089  7608  7636 D HeadsetStateMachine: Disconnected process message: 70
,08-17 19:16:54.089  1439  1439 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:16:54.089  7608  7636 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@60e795e
08-17 19:16:54.089  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:54.089  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:16:54.089  3894  3894 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:54.089  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:54.089  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:54.089  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:54.089  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:54.089  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.089  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:54.089  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:54.089  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:16:54.089  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 19:16:54.089  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:16:54.099  7608  7636 D HeadsetStateMachine: Disconnected process message: 9
,08-17 19:16:54.099  7608  7636 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-17 19:16:54.099  3894  3894 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 19:16:54.099  3894  3894 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:16:54.099  3894  3894 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:54.099  3894  3894 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:16:54.099  1171  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:54.099   284   692 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:54.099   284   692 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:16:54.099   284   692 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:54.099  7608  7675 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:16:54.099   284   692 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:54.099   284   692 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:16:54.099   284   692 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-17 19:16:54.109   284   692 V audio_hw_primary: adev_set_parameters: exit,
08-17 19:16:54.109  7608  7636 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-17 19:16:54.109  3894  3894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:16:54.109  1015  1509 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:54.109  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0,
08-17 19:16:54.109  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.109  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.109  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:54.109  7608  7675 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:54.109  7608  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:54.119  7608  7675 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-17 19:16:54.119  7608  7675 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:54.119  7608  7675 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:54.119  7608  7675 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39d8813f
,08-17 19:16:54.119  7608  7675 D BluetoothSocket: channel: 5
,08-17 19:16:54.119  3894  3894 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:54.129  3894  3894 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:54.129  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:54.129  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:54.139  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:54.139  7608  7608 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:54.139  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:54.139  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.139  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.139  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.139  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:54.149  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:54.149  1015  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:54.149  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:54.149  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.149  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:54.149  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:54.169  2038  7681 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:54.169  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:54.169  1015  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:54.169  1015  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:54.169  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.169  1015  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:54.169  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:54.189  1015  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:54.189  7608  7685 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:54.189  7608  7685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:54.189  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:54.189  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:54.189  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:54.189  7608  7685 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-17 19:16:54.189  7608  7685 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:54.189  7608  7685 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:54.189  7608  7685 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c53bd1
08-17 19:16:54.189  7608  7685 D BluetoothSocket: channel: 12
08-17 19:16:54.189  7608  7685 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:54.199  2038  7681 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:16:54.389  1015  1042 D Tethering: interfaceAdded wlan0
,08-17 19:16:54.399  1015  1129 E Tethering: No numeric data
,08-17 19:16:54.399  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:54.399  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:54.399  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:54.399  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:54.409  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:54.409  1015  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:54.409  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:54.409  1171  1171 D HotspotTile: updateTetherState():false, false
,08-17 19:16:54.409  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:54.409  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:54.409  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:54.409  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:54.409  1015  1121 V NetworkStats: performPollLocked() took 11ms
,08-17 19:16:54.419  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:54.419  1015  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:16:54.419  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:54.419  1015  1129 E Tethering: No numeric data
,08-17 19:16:54.419  1015  1042 D Tethering: interfaceAdded p2p0
,08-17 19:16:54.419  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 19:16:54.419  1015  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:54.429  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:16:54.429  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:54.429  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:54.429  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:54.429  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:16:54.429  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:54.429  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:54.429  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:54.429  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 19:16:54.429  1171  1171 D HotspotTile: updateTetherState():false, false
,08-17 19:16:54.429   279   999 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-17 19:16:54.439   279   999 D SoftapController: Softap fwReload - Ok
,08-17 19:16:54.439   279   999 D CommandListener: Setting iface cfg
08-17 19:16:54.439   279   999 D CommandListener: Trying to bring down wlan0
,08-17 19:16:54.439   279   999 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:54.439  1015  1121 V NetworkStats: performPollLocked() took 11ms
,08-17 19:16:54.439  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:54.439  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:54.439  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:54.449  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:16:54.449  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 19:16:54.449  1015  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-17 19:16:54.459  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:54.459  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 19:16:54.459  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:54.459  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:54.459  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:54.459  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:54.469  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:54.469  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 19:16:54.469  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:54.469  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:54.469  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:54.469  1171  1171 D HotspotTile: onReceive : 2, 0
,08-17 19:16:54.479  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:54.479  1015  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:54.479  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:54.479  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:54.479  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:54.479  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:54.489  1617  1617 I Hs20UtilService: Starting #19
,08-17 19:16:54.489  1617  1636 I Hs20UtilService: Message received 5011
08-17 19:16:54.489  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:54.489  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:54.489  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:54.489  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:54.499  7694  7694 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 19:16:54.499  7694  7694 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 19:16:54.499  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:54.519  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-17 19:16:54.519   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7694
08-17 19:16:54.519   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:54.519  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:54.519  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:54.519  7694  7694 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:16:54.519  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 19:16:54.519   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7694
08-17 19:16:54.519   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 19:16:54.649   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-17 19:16:54.659  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-17 19:16:54.699  7694  7694 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:54.699  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:54.709  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:16:54.709   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694
08-17 19:16:54.709   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:54.709  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-17 19:16:54.709  7694  7694 I wpa_supplicant: ssSupport state is = 1,
08-17 19:16:54.709  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:54.719  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:54.719  7694  7694 E wpa_supplicant: SIM READ ERROR,
08-17 19:16:54.719  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:54.719  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:54.719  7694  7694 E wpa_supplicant: SIM READ ERROR
08-17 19:16:54.719  7694  7694 I wpa_supplicant: Blacklist: Clear (all) ,
08-17 19:16:54.719  7694  7694 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:54.719  7694  7694 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:54.719  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:54.719  7694  7694 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-17 19:16:54.719  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:54.719  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:54.719  7694  7694 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:16:54.719  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:54.719  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:54.719  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:54.789  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:16:54.999  7694  7694 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:54.999  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:55.009  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-17 19:16:55.009   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694
08-17 19:16:55.009   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:55.009  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:55.009  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:55.009  7694  7694 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:55.009  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:55.029  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-17 19:16:55.029   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694
08-17 19:16:55.029   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:55.029  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:55.029  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:55.029  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:55.029  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:55.029  7694  7694 E wpa_supplicant: SIM READ ERROR
08-17 19:16:55.029  7694  7694 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:55.029  7694  7694 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:55.029  7694  7694 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:16:55.029  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.029  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.029  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:55.039  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.039  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.039  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:55.079  7694  7694 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:55.079  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:55.219  7694  7694 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-17 19:16:55.219  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 19:16:55.219  7694  7694 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:55.409  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.409  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:55.409  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:55.449  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 19:16:55.459  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:55.459  7694  7694 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:16:55.459  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:55.459  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:55.459  7694  7694 E wpa_supplicant: SIM READ ERROR
08-17 19:16:55.459  7694  7694 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:55.479  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 19:16:55.489  7694  7694 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:55.489  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:55.499  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:55.499  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:55.499  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:55.499  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:55.499  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:55.499  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:55.499  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:55.499  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 19:16:55.499  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:55.499  1171  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:55.499  1171  1171 D HotspotTile: onReceive : 3, 0
,08-17 19:16:55.509  3894  3894 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:55.509  1015  1124 E WifiConfigStore: Not a HS20
,08-17 19:16:55.509  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:55.519  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:55.519  6789  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:55.519  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:55.519  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:55.519  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 19:16:55.519  7694  7694 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:55.519  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:16:55.519  7694  7694 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:55.519  7694  7694 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:55.519  7694  7694 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:55.519  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:55.519  7694  7694 I wpa_supplicant: First Scan Start
08-17 19:16:55.519  7694  7694 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:55.519  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.519  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.519  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:55.519  1617  1617 I Hs20UtilService: Starting #20
,08-17 19:16:55.519  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
08-17 19:16:55.519  6789  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:55.519  1617  1636 I Hs20UtilService: Message received 5011
08-17 19:16:55.519  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:16:55.519  1015  1124 I WifiNative-HAL: startHal
08-17 19:16:55.519  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d47888c
08-17 19:16:55.519  1015  1124 I WifiNative-HAL: Could not start hal
,08-17 19:16:55.529  7034  7034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:55.529  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 19:16:55.529  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:55.529  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:55.529  6623  6623 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:55.529  6623  6623 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:55.529  6623  6623 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 19:16:55.529  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 19:16:55.529  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3,
08-17 19:16:55.529  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:55.529  1015  1148 I WifiNative-HAL: startHal
08-17 19:16:55.529  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e62a9bc
08-17 19:16:55.529  1015  1123 D WifiP2pService: P2pEnablingState
08-17 19:16:55.529  1015  1148 I WifiNative-HAL: Could not start hal,
,08-17 19:16:55.529  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 },
08-17 19:16:55.529  1015  1148 E WifiScanningService: could not start HAL
08-17 19:16:55.529  1015  1123 D WifiP2pService: P2p socket connection successful
08-17 19:16:55.529   279   999 D CommandListener: Setting iface cfg
08-17 19:16:55.539  1015  1123 D WifiP2pService: P2pEnabledState
08-17 19:16:55.529   279   999 D CommandListener: Trying to bring up p2p0
08-17 19:16:55.529  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-17 19:16:55.529  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:55.529  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:16:55.539  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:55.539  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:55.539  1015  1124 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:55.539  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:55.539  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:55.539  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:55.539  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:55.539  7694  7694 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:55.539  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:55.539  7694  7694 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:55.539  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:55.539  7694  7694 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-17 19:16:55.539  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,08-17 19:16:55.539  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 19:16:55.549  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:55.549  1015  1045 D WifiDisplayController: disconnect
08-17 19:16:55.549  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:55.549  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:55.549  1015  1045 D WifiDisplayController: updateConnection,
08-17 19:16:55.549  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:55.549  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:55.549  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 19:16:55.549  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:55.549  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:55.549  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:55.549  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:16:55.549  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 19:16:55.549  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 19:16:55.549  1015  1493 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:55.549  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:55.549  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:55.549  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:55.549  1015  1124 D SecContentProvider2: mCursor = null
08-17 19:16:55.559  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:55.559  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:55.559  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-17 19:16:55.559  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  secondary type: null
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  wps: 0
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  grpcapab: 0
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  devcapab: 0
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  status: 3
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  wfdInfo: null
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:55.559  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:55.559  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:55.559  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 19:16:55.559  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:55.559  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:55.559  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:55.569  7382  7382 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 19:16:55.569  7382  7382 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:55.569  7397  7397 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:55.579  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:16:55.579  1015  1123 D WifiP2pService: InactiveState
,08-17 19:16:55.579  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:55.579  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:55.579  7694  7694 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:55.579  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:55.579  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:55.779   289   289 E SMD     : DCD OFF,
,08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:56.049  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:56.059  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:56.059  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:16:56.059  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:16:56.059  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1cec98bd Bundle[{}]
,08-17 19:16:56.059  6789  6844 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 19:16:56.059  6789  6844 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 19:16:56.069  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityStarted,
08-17 19:16:56.069  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 19:16:56.069  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 19:16:56.069  6789  6844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:16:56.069  6789  6844 I System.out: Running OutgoingSocketThread
,08-17 19:16:56.069  6789  7702 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1344)
,08-17 19:16:56.079  6789  7702 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39835
,08-17 19:16:56.079  6789  7702 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:16:56.759  7694  7694 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-17 19:16:56.759  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:56.759  7694  7694 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-17 19:16:56.759  7694  7694 I wpa_supplicant: Trying to associate with  'G700'
08-17 19:16:56.759  7694  7694 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 19:16:56.759  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 19:16:56.759  1015  7700 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:16:56.769  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:56.769  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:56.879  7694  7694 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:16:56.879  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:56.879  7694  7694 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 19:16:56.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:56.879  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:56.879  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:56.879  7694  7694 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:16:56.879  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:56.879  7694  7694 I wpa_supplicant: Associated with F4.99.3E
08-17 19:16:56.879  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:56.879  7694  7694 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:16:56.879  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:56.879  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:56.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:56.879  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:56.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:56.879  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:56.879  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:56.879  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
08-17 19:16:56.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 19:16:56.879  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-17 19:16:56.889  1015  1129 E Tethering: No numeric data
,08-17 19:16:56.889  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-17 19:16:56.889  1015  1129 D Tethering: clearTetheredNotification(),
,08-17 19:16:56.889  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:56.889  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:56.889  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:56.889  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:56.889  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
,08-17 19:16:56.889  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:56.889  7694  7694 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 19:16:56.889  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:56.899  7694  7694 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:16:56.899  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 19:16:56.899  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:56.899  1171  1171 D HotspotTile: updateTetherState():false, false
08-17 19:16:56.899  7694  7694 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:16:56.899  7694  7694 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 19:16:56.899  7694  7694 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:16:56.899  7694  7694 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:16:56.899  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:56.899  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:56.899  1015  1121 V NetworkStats: performPollLocked() took 12ms
08-17 19:16:56.899  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
08-17 19:16:56.899  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 19:16:56.899  1015  1042 D Tethering: interfaceStatusChanged wlan0, true,
08-17 19:16:56.909  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:56.909  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:56.909  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:56.909  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:56.909  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-17 19:16:56.919  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:56.919  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:56.919  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:56.919  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.919  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.919  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.919  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.919  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:16:56.919  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:16:56.919  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:56.919  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:56.929  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 19:16:56.929  1015  1254 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:16:56.929  1015  1254 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.929  1015  1254 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:56.929  1015  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.929  1015  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:56.929  1617  1617 I Hs20UtilService: Starting #21
08-17 19:16:56.929  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:56.929  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:56.939  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:56.939  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:56.939  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:56.939  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:56.939  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:56.939  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:56.939  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:56.949   279   999 D CommandListener: Setting iface cfg
,08-17 19:16:56.949  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:16:56.949  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:56.949  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:56.959  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:56.959  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:56.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:56.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:56.969  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:56.969  1015  1124 D SecContentProvider2: mCursor = null
,08-17 19:16:56.969  1015  1124 E WifiNative-wlan0: do suspend false
,08-17 19:16:56.969  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:56.969  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:57.069  6789  6844 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1345),
08-17 19:16:57.069  6789  6844 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1345)
,08-17 19:16:57.079  6789  6844 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1350)
,08-17 19:16:57.079  6789  6844 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 19:16:57.079  6789  6844 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351),
,08-17 19:16:57.079  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:16:57.079  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@112245fc added. We now have 2 listener(s),
08-17 19:16:57.079  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:16:57.079  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.079  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-17 19:16:57.079  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.079  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d2c485 added. We now have 9 listener(s)
08-17 19:16:57.079  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.079  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:57.089  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.089  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.089  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:57.099  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb0b30b added. We now have 3 listener(s)
,08-17 19:16:57.099  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.099  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264bc5e8 added. We now have 10 listener(s)
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.099  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:57.099  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:57.099  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.099  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@112245fc removed from the list
08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.099  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d2c485 removed from the list
08-17 19:16:57.099  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.099  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.099  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.099  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:57.109  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d2c485 not in the list
,08-17 19:16:57.109  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:57.109  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.109  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:57.109  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.109  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 19:16:57.109  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264bc5e8 removed from the list
08-17 19:16:57.109  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 19:16:57.109  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.109  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.109  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:16:57.109  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb0b30b removed from the list
08-17 19:16:57.109  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.109  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e002401 added. We now have 2 listener(s)
,08-17 19:16:57.109  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:16:57.109  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:57.119  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:57.119  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:57.119  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2acdd2a6 added. We now have 9 listener(s)
,08-17 19:16:57.119  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:57.119  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:57.119  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.129  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.129  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:57.129  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:57.129  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.129  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.139  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:16:57.139  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0b5894 added. We now have 3 listener(s)
,08-17 19:16:57.139  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:16:57.139  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:57.139  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:57.139  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:57.139  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c49ff3d added. We now have 10 listener(s)
08-17 19:16:57.139  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:57.139  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:16:57.139  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 19:16:57.139  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:57.139  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:57.139  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:57.149  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:57.159  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:57.159  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:57.159  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:57.159  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:57.159  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:57.169  7608  7627 D BtGatt.GattService: registerClient() - UUID=165b8a13-9606-4b81-92ed-5cd20cefdf82
,08-17 19:16:57.179  7708  7708 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:57.189  7708  7708 I dhcpcd  : version 5.5.6 starting,
,08-17 19:16:57.189  7708  7708 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:57.209  7608  7626 D BtGatt.GattService: onClientRegistered() - UUID=165b8a13-9606-4b81-92ed-5cd20cefdf82, clientIf=6,
,08-17 19:16:57.209  6789  6797 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:16:57.219  7608  7617 D BtGatt.GattService: start scan with filters
08-17 19:16:57.219  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:57.219  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:57.219  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:57.219  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:16:57.219  7608  7633 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:57.229  7608  7633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f3dd77
,08-17 19:16:57.229  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:57.229  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:57.229  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:57.229  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-17 19:16:57.239  7608  7626 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:57.239  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.239  7608  7633 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:57.239  7608  7633 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:57.239  7608  7633 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:16:57.239  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-17 19:16:57.239  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.239  7608  7633 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:57.239  7608  7633 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:16:57.239  6789  6844 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:57.239  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:57.239  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:57.239  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.239  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:57.239  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:57.239  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:57.239  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:57.239  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:57.239  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:57.239  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:57.239  7608  7626 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:57.239  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.239  7608  7674 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:57.239  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:57.239  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.249  7608  7628 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:57.249  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:57.249  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:57.249  7608  7633 D BtGatt.ScanManager: filter size is 1
08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:57.249  7608  7633 D BtGatt.ScanManager: delete FilterIndex - 3
08-17 19:16:57.249  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:57.249  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:57.249  7708  7708 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 19:16:57.249  7708  7708 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-17 19:16:57.249  7708  7708 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 19:16:57.249  7708  7708 I dhcpcd  : bssid match
08-17 19:16:57.249  7708  7708 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-17 19:16:57.249  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:57.249  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.249  7608  7633 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:57.249  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.249  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.249  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:57.259  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:57.259  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:57.259  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.259  7608  7633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:16:57.259  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:57.259  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.259  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e002401 removed from the list
08-17 19:16:57.259  7608  7626 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:57.259  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2acdd2a6 removed from the list
08-17 19:16:57.259  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.259  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.259  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2acdd2a6 not in the list
08-17 19:16:57.259  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c49ff3d removed from the list
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.259  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The gi,ven listener does not exist in the list - probably already removed
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.259  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0b5894 removed from the list
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.259  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e5c5239 added. We now have 2 listener(s)
08-17 19:16:57.259  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:16:57.269  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.269  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.269  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.269  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72907e added. We now have 9 listener(s)
08-17 19:16:57.269  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.269  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:57.269  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:57.279  1015  1493 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:57.279  1015  1493 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 19:16:57.279  1015  1493 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:57.279  1015  1493 D BatteryService: stay LED for fully charged
,08-17 19:16:57.279  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.279  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.279  1015  1015 I MotionRecognitionService: Plugged
08-17 19:16:57.279  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:57.279  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:57.289  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-17 19:16:57.289  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:57.289  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:57.289  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:57.289  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:57.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.289  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2081262c added. We now have 3 listener(s)
,08-17 19:16:57.289  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.289  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 19:16:57.299  7608  7608 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:57.299  7608  7636 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:57.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:16:57.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22a6d8f5 added. We now have 10 listener(s)
08-17 19:16:57.309  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.309  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:57.309  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:57.309  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:57.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:57.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:57.309  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:57.309  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:57.309  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 19:16:57.309  1171  1171 D SViewCoverView: level :100 plugged : 2
,08-17 19:16:57.309  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:57.319  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:57.319  7708  7708 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-17 19:16:57.319  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:16:57.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:57.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:57.319  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:57.329  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:57.329  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:57.329  7608  7616 D BtGatt.GattService: registerClient() - UUID=ed0eeb9a-9d31-44c7-b694-ef929a655980
,08-17 19:16:57.369  7608  7626 D BtGatt.GattService: onClientRegistered() - UUID=ed0eeb9a-9d31-44c7-b694-ef929a655980, clientIf=6
,08-17 19:16:57.369  6789  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:57.369  7608  7674 D BtGatt.GattService: start scan with filters
,08-17 19:16:57.369  7608  7633 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:57.379  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:57.379  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:57.379  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:57.379  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:57.379  7608  7626 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:57.379  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.379  7608  7633 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:57.379  7608  7633 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:16:57.379  7608  7633 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 19:16:57.379  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:57.379  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.379  7608  7633 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:16:57.379  7608  7633 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:57.379  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:57.379  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:57.379  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:57.389  7608  7626 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:16:57.389  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.389  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:16:57.389  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.389  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:57.399  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:16:57.399  6789  6844 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 19:16:57.399  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:57.399  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:57.399  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:57.399  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:57.399  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:57.399  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:57.399  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.399  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e5c5239 removed from the list
,08-17 19:16:57.399  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:57.399  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72907e removed from the list
08-17 19:16:57.409  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:57.409  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:57.409  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-17 19:16:57.409  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 19:16:57.409  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.409  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.409  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f72907e not in the list
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:57.409  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:57.409  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:57.409  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:57.419  7608  7617 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:57.419  7608  7633 D BtGatt.ScanManager: filter size is 1
08-17 19:16:57.419  7608  7633 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 19:16:57.419  7608  7616 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:16:57.419  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:57.419  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.419  7608  7633 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:57.419  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:57.419  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:57.419  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:57.419  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:57.419  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:57.419  7608  7633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:16:57.419  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.419  7608  7626 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:57.419  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.429  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.429  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.429  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22a6d8f5 removed from the list
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.429  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.429  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2081262c removed from the list
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90f71 added. We now have 2 listener(s)
08-17 19:16:57.429  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:16:57.429  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.429  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.429  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15863156 added. We now have 9 listener(s)
08-17 19:16:57.429  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:16:57.429  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:57.439  7708  7708 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.439  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:57.439  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:57.439  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:57.439  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.439  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6000ec4 added. We now have 3 listener(s)
08-17 19:16:57.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-17 19:16:57.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.449  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.449  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e31ad added. We now have 10 listener(s)
08-17 19:16:57.449  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:57.449  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.449  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:57.449  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:57.449  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:57.449  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:57.449  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:57.449  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.449  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:57.459  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:57.459  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:57.469  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:57.469  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:57.469  6789  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:57.469  7608  7628 D BtGatt.GattService: registerClient() - UUID=6ed2daf7-e0a8-4587-b0a1-52ec45d09ea6
,08-17 19:16:57.519  7608  7626 D BtGatt.GattService: onClientRegistered() - UUID=6ed2daf7-e0a8-4587-b0a1-52ec45d09ea6, clientIf=6
,08-17 19:16:57.519  6789  6798 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:16:57.519  7608  7627 D BtGatt.GattService: start scan with filters
,08-17 19:16:57.529  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-17 19:16:57.529  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:57.529  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:57.529  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: handling starting scan,
08-17 19:16:57.529  7608  7626 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:57.529  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-17 19:16:57.529  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:16:57.529  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:57.529  7608  7633 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:16:57.529  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:57.529  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:57.529  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:57.529  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:57.539  7608  7626 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:57.539  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.539  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-17 19:16:57.539  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.549  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 19:16:57.549  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:57.549  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 19:16:57.549  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:16:57.549  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d90f71 removed from the list
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.549  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15863156 removed from the list
08-17 19:16:57.549  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:57.549  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:16:57.549  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.549  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15863156 not in the list
,08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:57.549  7608  7617 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:57.549  7608  7633 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:57.549  7608  7633 D BtGatt.ScanManager: delete FilterIndex - 5
08-17 19:16:57.549  7608  7674 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:57.549  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:57.549  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:57.559  7608  7626 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:57.559  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:57.559  7608  7633 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:57.559  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:57.559  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:57.559  6789  6844 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:57.559  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.559  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e31ad removed from the list
08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.559  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.559  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.559  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.559  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6000ec4 removed from the list
08-17 19:16:57.559  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.559  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35193ba9 added. We now have 2 listener(s)
,08-17 19:16:57.559  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.559  6789  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:57.559  6789  6789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:57.559  7608  7626 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:57.559  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.559  7608  7633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:57.569  7608  7626 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-17 19:16:57.569  7608  7626 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:57.569  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:16:57.569  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.569  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.569  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:57.569  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a2152e added. We now have 9 listener(s)
08-17 19:16:57.569  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.569  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:57.589  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.599  6789  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.609  6789  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:57.609  6789  6844 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b30725c added. We now have 3 listener(s)
,08-17 19:16:57.609  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.609  6789  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a0e965 added. We now have 10 listener(s)
08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:57.609  6789  6844 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:57.609  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:57.609  6789  6844 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:57.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:57.609  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:57.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35193ba9 removed from the list
08-17 19:16:57.609  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.609  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a2152e removed from the list
08-17 19:16:57.609  6789  6844 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:57.609  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.619  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.619  6789  6844 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a2152e not in the list
08-17 19:16:57.619  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:57.619  6789  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a0e965 removed from the list
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:57.619  6789  6844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:57.619  6789  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:57.619  6789  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:57.619  6789  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b30725c removed from the list
,08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:16:57.619  6789  6844 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:57.629  6789  7738 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1358, name: My test thread name)
,08-17 19:16:57.629  6789  7738 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1358, thread name: My test thread name)
,08-17 19:16:57.629  6789  7738 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1358, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:16:57.629  6789  7739 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1360, name: My test thread name)
,08-17 19:16:57.629  6789  7739 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1360, thread name: My test thread name)
,08-17 19:16:57.629  6789  7739 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1360, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:16:57.639  6789  6844 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 19:16:57.639  6789  6844 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-17 19:16:57.639  6789  6844 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:16:57.639  6789  6844 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-17 19:16:57.639  6789  6844 D com.test.thalitest.ThaliTestRunner: Total duration: 23350 ms
,08-17 19:16:57.639  6789  6844 I jxcore-log: Total number of executed tests:  80
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.639  6789  6844 I jxcore-log: Number of passed tests:  80
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.639  6789  6844 I jxcore-log: Number of failed tests:  0
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.639  6789  6844 I jxcore-log: Number of ignored tests:  0
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.639  6789  6844 I jxcore-log: Total duration:  23350
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.639  6789  6844 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:16:57.639  6789  6844 I jxcore-log: 
,08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
08-17 19:16:57.659  6789  6789 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
,08-17 19:16:57.659  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.659  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.669  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.669  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-17 19:16:57.679  6789  6844 I jxcore-log: 
08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.679  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:16:57.679  6789  6844 I jxcore-log: 
,08-17 19:16:57.749  6789  6789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-17 19:16:57.759  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:16:57.759  6789  6844 I jxcore-log: 
,08-17 19:16:57.789  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 19:16:57.809  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
08-17 19:16:57.809  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:57.819  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 19:16:57.819  1015  1124 E WifiStateMachine: VerifyingLinkState enter
,08-17 19:16:57.819  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:57.819  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:57.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.819  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.819  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:57.829  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
,08-17 19:16:57.829  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504,
08-17 19:16:57.829  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-17 19:16:57.829  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:16:57.829  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:16:57.829  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:16:57.829  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:16:57.849  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:57.849  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:57.849  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.849  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.849  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.849  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.859  1015  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:57.859  1015  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:57.859  1015  1461 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.859  1015  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.859  1015  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:57.859  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-17 19:16:57.869  1617  1617 I Hs20UtilService: Starting #22
08-17 19:16:57.869  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:57.869  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:57.869  3894  3894 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:16:57.879  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-17 19:16:57.879  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-17 19:16:57.879  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 19:16:57.879  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-17 19:16:57.889  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0,
08-17 19:16:57.889  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 19:16:57.889  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:57.889  1015  1126 D ConnectivityService: LTETest block dns file not exists
08-17 19:16:57.889  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:57.889  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.889  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.889  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.889  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.889  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 19:16:57.889  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 19:16:57.889  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:16:57.889  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-17 19:16:57.889  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-17 19:16:57.899  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:57.899  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:57.899  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.899  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.899  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.899  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.909  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.909  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:57.909  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:57.909  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 19:16:57.909  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:57.909  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-17 19:16:57.909  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.909  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.909  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:57.909  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:57.919  1617  1617 I Hs20UtilService: Starting #23
,08-17 19:16:57.919  1617  1636 I Hs20UtilService: Message received 5007
,08-17 19:16:57.919  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.919  1015  1126 V NetworkStats: performPollLocked() took 14ms
08-17 19:16:57.919  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:57.919  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.919  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-17 19:16:57.919  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:57.919  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:57.919  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.919  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 19:16:57.919  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 19:16:57.919  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:57.919  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.919  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:57.919  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:57.929  3894  3894 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:57.929  1015  1126 V NetworkStats: performPollLocked() took 4ms
08-17 19:16:57.929  6789  6789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:16:57.929  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-17 19:16:57.929  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.929  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:16:57.929  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:16:57.929  6789  6844 I jxcore-log: 
08-17 19:16:57.929  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:57.929  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 19:16:57.929  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:57.929  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 19:16:57.929  1015  7703 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:57.929  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.929  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.929   279   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:57.929  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:57.929   279   995 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-17 19:16:57.929  1015  1126 D ConnectivityService:    accepting network in place of null
08-17 19:16:57.929  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:57.929  3894  3894 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:57.929  3894  3894 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:57.929  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-17 19:16:57.929  1471  1471 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:16:57.939  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 19:16:57.929  1471  1471 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:16:57.939  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 19:16:57.939  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:16:57.939  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 19:16:57.939  3894  3963 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:57.939  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 19:16:57.939  1015  1129 D Tethering: MasterInitialState.processMessage what=3,
08-17 19:16:57.939  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-17 19:16:57.939  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.939  1015  1121 V NetworkStats: updateIfacesLocked()
08-17 19:16:57.939  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:57.939  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:57.939  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 19:16:57.939  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:57.939  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 19:16:57.939  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:16:57.939  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:16:57.939  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:16:57.939  1171  1171 D StatusBar.NetworkController: updateDataNetType()
08-17 19:16:57.939  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:16:57.939  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 19:16:57.939  1171  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:16:57.949  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:16:57.949  1015  1121 V NetworkStats: performPollLocked() took 9ms
08-17 19:16:57.949  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.949  1015  1745 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:57.949  1015  1745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:57.959  1015  1745 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.959  1015  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:57.959  1015  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:57.959  1617  1617 I Hs20UtilService: Starting #24
,08-17 19:16:57.959  1617  1636 I Hs20UtilService: Message received 5007
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:57.959  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.959  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.959  3894  3894 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:57.959  3894  3894 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:16:57.969  1015  1027 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 19:16:57.969  1015  1745 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-17 19:16:57.969  1015  1745 D SecContentProvider2: mCursor = null
,08-17 19:16:57.969  1015  1461 D SecContentProvider2: uri = 15 selection = getToastGravity
08-17 19:16:57.969  1015  1461 D SecContentProvider2: mCursor = null
08-17 19:16:57.969  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-17 19:16:57.969  1015  1028 D SecContentProvider2: mCursor = null
,08-17 19:16:57.969  1015  1509 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-17 19:16:57.969  1015  1509 D SecContentProvider2: mCursor = null
,08-17 19:16:57.979  1015  1487 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-17 19:16:57.979  1015  1487 D SecContentProvider2: mCursor = null
,08-17 19:16:57.979  1015  3124 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 19:16:57.979  1015  3124 D SecContentProvider2: mCursor = null
,08-17 19:16:57.989  7740  7740 D AndroidRuntime: 
08-17 19:16:57.989  7740  7740 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 19:16:57.989  7740  7740 D AndroidRuntime: CheckJNI is OFF
,08-17 19:16:57.989  7740  7740 D AndroidRuntime: readGMSProperty: start
08-17 19:16:57.989  7740  7740 D AndroidRuntime: readGMSProperty: already setted!!
,08-17 19:16:57.989  7740  7740 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:16:57.989  7740  7740 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:16:57.989  7740  7740 D AndroidRuntime: readGMSProperty: end
,08-17 19:16:57.989  7740  7740 D AndroidRuntime: addProductProperty: start
,08-17 19:16:58.009   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-17 19:16:58.019  1015  1028 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-17 19:16:58.019  1015  7703 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:58.019  1171  1171 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:16:58.059  6789  6789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-17 19:16:58.069  6789  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:16:58.069  6789  6844 I jxcore-log: 
,08-17 19:16:58.079  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:16:58 GMT], X-Android-Received-Millis=[1471454218093], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471454218061]}
08-17 19:16:58.079  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 19:16:58.079  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 19:16:58.079  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:16:58.079  1015  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 19:16:58.079  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 19:16:58.079  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:16:58.079  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 19:16:58.079  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:16:58.089  1171  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: updateDataNetType()
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:16:58.089  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:58.089  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.089  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:58.129  7740  7740 E AffinityControl: AffinityControl: registerfunction enter
,08-17 19:16:58.149  7740  7740 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 19:16:58.159  1015  1509 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-17 19:16:58.159  1015  1509 D PackageManager: START PACKAGE DELETE: observer{460856428}
08-17 19:16:58.159  1015  1509 D PackageManager: pkg{<packageName>}
08-17 19:16:58.159  1015  1509 D PackageManager: user{0}
08-17 19:16:58.159  1015  1509 D PackageManager: caller{2000}
,08-17 19:16:58.159  1015  1509 D PackageManager: flags{2}
08-17 19:16:58.159  1015  1509 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-17 19:16:58.159  1015  1509 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-17 19:16:58.159  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-17 19:16:58.159  1015  1509 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-17 19:16:58.159  1015  1509 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 19:16:58.159  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-17 19:16:58.159  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 19:16:58.159  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled,
08-17 19:16:58.159  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 19:16:58.169  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-17 19:16:58.169  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-17 19:16:58.169  1015  1040 I ActivityManager: Killing 6789:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 19:16:58.169  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{384c27c8 u0 com.test.thalitest/.MainActivity t3},
,08-17 19:16:58.179  1015  1040 D InputDispatcher: Focus left window: 6789
,08-17 19:16:58.179   259  1095 I SurfaceFlinger: id=13 Removed NainActivit (6/9),
08-17 19:16:58.179   259   439 I SurfaceFlinger: id=13 Removed NainActivit (-2/9),
08-17 19:16:58.179  1015  1040 D InputDispatcher: Focused application released
08-17 19:16:58.179  1015  1040 D FocusedStackFrame: Set to : 0
08-17 19:16:58.179  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:58.179  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:16:58.189  1015  1040 W ActivityManager: mDVFSHelper.acquire(),
,08-17 19:16:58.329  1015  1055 W PackageSettings: Skipping PackageSetting{12d4b8a0 com.example.hello/10168} due to missing metadata
,08-17 19:16:58.349  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-17 19:16:58.359  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-17 19:16:58.379  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 19:16:58.439  2682  2682 I art     : Explicit concurrent mark sweep GC freed 21141(1183KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.785ms total 66.660ms
,08-17 19:16:58.439  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:58.459  1495  1495 D Launcher: onRestart, Launcher: 691984915
,08-17 19:16:58.459  1495  1495 D Launcher: onStart, Launcher: 691984915
08-17 19:16:58.459  1495  1495 D Launcher.HomeView: onStart
,08-17 19:16:58.459  1495  1495 D Launcher: onResume, Launcher: 691984915
,08-17 19:16:58.459  1015  3124 D SettingsProvider: name = kids_home_mode
,08-17 19:16:58.459  1015  3124 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:58.459  1015  3124 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:58.459  1015  3124 D SettingsProvider: selectionArgs: false
08-17 19:16:58.459  1015  3124 D SettingsProvider: selectionArgs: 10006
08-17 19:16:58.459  1015  3124 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:58.459  1015  3124 D SettingsProvider: ret = -1
,08-17 19:16:58.459  1495  1495 D Launcher.HomeView: onResume
,08-17 19:16:58.469  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-17 19:16:58.469  1495  1495 D MenuAppsGridFragment: onResume
,08-17 19:16:58.479  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 19:16:58.479  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 19:16:58.519  4806  4806 I art     : Explicit concurrent mark sweep GC freed 22786(1379KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.312ms total 147.646ms
,08-17 19:16:58.529  1471  1471 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 19:16:58.539  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-17 19:16:58.539  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.539  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-17 19:16:58.539  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:58.539  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:58.539  1015  1121 V NetworkStats: performPollLocked() took 4ms
08-17 19:16:58.539  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.539  1845  1845 E SamsungIME: mOCRHelper is null
,08-17 19:16:58.549  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 19:16:58.569  1015  1493 D ActivityManager: handle home activity for 0
,08-17 19:16:58.569  1015  1493 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-17 19:16:58.569  1015  1493 D KnoxTimeoutHandler: post home show event for user 0
08-17 19:16:58.569  2906  2906 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:16:58 GMT+02:00 2016
08-17 19:16:58.569  1015  1493 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-17 19:16:58.569  1015  1493 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:16:58.569  1015  1493 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 19:16:58.569  1495  1495 D Launcher.HomeView: onPause
,08-17 19:16:58.569  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-17 19:16:58.579  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:16:58.589  1455  1455 D RegisteredServicesCache: empty dynamic service
,08-17 19:16:58.639  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 19:16:58.639  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:16:58.649  1015  1015 I art     : Explicit concurrent mark sweep GC freed 79362(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 2.931ms total 275.912ms
08-17 19:16:58.649  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-17 19:16:58.649  1015  1461 I art     : WaitForGcToComplete blocked for 134.248ms for cause Explicit
,08-17 19:16:58.669  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.669  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.689  1015  1040 W ActivityManager: mDVFSHelper.release()
,08-17 19:16:58.709  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:16:58.709  1015  1126 V NetworkStats: updateIfacesLocked()
,08-17 19:16:58.709  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:58.709  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.709  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:16:58.709  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:58.719  1015  1126 V NetworkStats: performPollLocked() took 6ms
08-17 19:16:58.719  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.719  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:16:58.719  1171  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:16:58.719  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:16:58.719  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:16:58.719  1171  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:16:58.729  4806  6846 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:16:58.729  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-17 19:16:58.729  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 19:16:58.729  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-17 19:16:58.729  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-17 19:16:58.729  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-17 19:16:58.739  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 19:16:58.739  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 19:16:58.779   289   289 E SMD     : DCD OFF
,08-17 19:16:58.799  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 19:16:58.799  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 19:16:58.799  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 19:16:58.799  1015  1015 V EnterpriseBillingPolicy: uID is 10171
,08-17 19:16:58.809  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
,08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:16:58.809  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-17 19:16:58.809  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-17 19:16:58.809  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-17 19:16:58.809  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:16:58.809  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:16:58.809  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-17 19:16:58.809  1015  3359 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-17 19:16:58.819  1015  1461 I art     : Explicit concurrent mark sweep GC freed 15050(983KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 5.662ms total 165.592ms
,08-17 19:16:58.819  2038  2210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 19:16:58.819  1015  1055 I art     : WaitForGcToComplete blocked for 379.211ms for cause Explicit
08-17 19:16:58.819  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 19:16:58.819  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-17 19:16:58.819  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:16:58.819  1015  1027 D SecContentProvider2: mCursor = null
,08-17 19:16:58.829  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:58.829  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:58.829  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:16:58.839  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-17 19:16:58.839  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 19:16:58.839  2906  2906 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:16:58.839  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.839  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.839  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-17 19:16:58.849  1015  1028 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-17 19:16:58.849  1015  1028 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 19:16:58.849   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-17 19:16:58.859  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-17 19:16:58.859  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:16:58.859  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.859  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.859  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.859  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:58.859  2906  2906 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 19:16:58.859  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 19:16:58.859  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:58.869  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:58.869  1015  1487 D InputDispatcher: Focus entered window: 1495
,08-17 19:16:58.869  1015  1028 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7759 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-17 19:16:58.879  7759  7759 E Zygote  : MountEmulatedStorage(),
08-17 19:16:58.879  7759  7759 E Zygote  : v2
08-17 19:16:58.879  2906  2906 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
08-17 19:16:58.879  1495  1495 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-17 19:16:58.879  7759  7759 I libpersona: KNOX_SDCARD checking this for 10090
08-17 19:16:58.879  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:58.879  7759  7759 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:58.879  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:58.879  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:16:58.889  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:16:58.889  1015  1493 I TactileAssist: enable value -1
08-17 19:16:58.889  1015  1493 I TactileAssist: internal enable value -1
08-17 19:16:58.889  1015  1493 I TactileAssist: intensity value -1
08-17 19:16:58.889  1015  1493 I TactileAssist: saveAppList value true
08-17 19:16:58.889  7759  7759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:58.889  1015  1493 I TactileAssist: List of disabled apps :
08-17 19:16:58.889  7759  7759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:58.889  7759  7759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:58.889  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-17 19:16:58.899  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{df5103f token=android.os.BinderProxy@35c21b45 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-17 19:16:58.899  1495  1495 D Launcher.HomeView: onStop
,08-17 19:16:58.899  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.899  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.899  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.899  1015  1509 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 19:16:58.899  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:58.899  2906  2906 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:16:58.909  1015  7768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:58.909  7776  7776 E Zygote  : MountEmulatedStorage()
08-17 19:16:58.909  7776  7776 E Zygote  : v2
08-17 19:16:58.909  7776  7776 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:58.909  7776  7776 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:58.919  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 19:16:58.919  7776  7776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:58.919  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED,
08-17 19:16:58.919  7776  7776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:58.919  7776  7776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-17 19:16:58.919  1015  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7776 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:58.919  1015  1509 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6789 uid 10171
,08-17 19:16:58.919  1171  1171 I StatusBar: Icon Only
08-17 19:16:58.919  1171  1171 D PanelView: There is/are notification(s) 
,08-17 19:16:58.929  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-17 19:16:58.929  7759  7759 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:58.929  7759  7759 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:58.929  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.929  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-17 19:16:58.929  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.929  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:58.929  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:58.929  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-17 19:16:58.939  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network,
,08-17 19:16:58.949  7786  7786 E Zygote  : MountEmulatedStorage(),
08-17 19:16:58.949  7786  7786 E Zygote  : v2
08-17 19:16:58.949  7786  7786 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 19:16:58.949  7786  7786 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:58.949  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:16:58.959  1015  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7786 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-17 19:16:58.959  7776  7776 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:58.959  7776  7776 D ActivityThread: Added TimaKeyStore provider,
,08-17 19:16:58.969  1845  1845 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,08-17 19:16:58.969  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:16:58.969  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:58.979   307   307 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 28.662ms
,08-17 19:16:58.999  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-17 19:16:58.999   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 744us total 20.335ms
,08-17 19:16:59.009  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.009  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.009  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.009  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.009  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.019  7786  7786 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.019   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.525ms
,08-17 19:16:59.019  1015  1055 I art     : Explicit concurrent mark sweep GC freed 6968(485KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 3.109ms total 200.663ms
,08-17 19:16:59.029  7807  7807 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:59.029  7807  7807 E Zygote  : v2
08-17 19:16:59.029  7807  7807 I libpersona: KNOX_SDCARD checking this for 10048
08-17 19:16:59.029  7807  7807 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:59.029  7807  7807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:59.029  7807  7807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:59.029  1015  1028 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7807 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-17 19:16:59.039  7807  7807 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.059  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20d4c0cf u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:158223
,08-17 19:16:59.069  7776  7776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-17 19:16:59.079  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-17 19:16:59.079  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-17 19:16:59.079  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-17 19:16:59.079  7807  7807 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.089  7807  7807 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.089  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:59.089  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:59.089  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-17 19:16:59.089  1015  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-17 19:16:59.089  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.089  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.089  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.089  1015  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.099  7759  7759 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-17 19:16:59.099  7759  7759 D elm:15121: ELMEngine.ELMEngine( context ).
,08-17 19:16:59.099  7786  7786 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-17 19:16:59.099  7759  7759 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-17 19:16:59.109  2906  7758 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-17 19:16:59.109  2906  7758 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 19:16:59.109  7823  7823 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.109  7823  7823 E Zygote  : v2
08-17 19:16:59.109  7823  7823 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:59.109  7823  7823 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:59.109  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.109  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.119  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.119  1015  1461 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-17 19:16:59.119  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:59.119  1015  1134 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-17 19:16:59.119  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:59.119  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-17 19:16:59.119  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-17 19:16:59.129  7759  7759 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-17 19:16:59.129  2906  2906 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 19:16:59.129  1015  1254 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:16:59.129  1015  1254 D SecContentProvider2: mCursor = null
,08-17 19:16:59.129  7759  7759 D elm:15121: ElmAgentService : onCreate()
,08-17 19:16:59.139  7759  7831 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-17 19:16:59.139  7759  7831 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-17 19:16:59.139  7759  7831 D elm:15121: MDMBridge.getInstance()
08-17 19:16:59.139  7759  7831 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 19:16:59.149  1015  1461 D SecContentProvider2: uri = -1 selection = getSealedState
,08-17 19:16:59.149  1015  1461 D SecContentProvider2: mCursor = null
08-17 19:16:59.149  7786  7786 I PopupuiReceiver_KNOX: getSealedState : true
,08-17 19:16:59.149  7759  7831 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-17 19:16:59.149  1015  1493 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-17 19:16:59.149  1015  1493 D SecContentProvider2: mCursor = null
,08-17 19:16:59.149  7786  7786 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-17 19:16:59.149  1015  1254 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-17 19:16:59.149  1015  1254 D SecContentProvider2: mCursor = null
,08-17 19:16:59.149  7786  7786 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-17 19:16:59.149  7786  7786 D PopupuiReceiver: Action package removed
,08-17 19:16:59.159  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:16:59.159  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.159  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.159  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.159  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.159  7823  7823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.159  7823  7823 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.169  7840  7840 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.169  7840  7840 E Zygote  : v2
08-17 19:16:59.169  7840  7840 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:59.169  7840  7840 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:59.169  7840  7840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:59.169  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 19:16:59.169  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:59.169  7840  7840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.169  7840  7840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.179  7759  7759 D elm:15121: ElmAgentService : onDestroy().
,08-17 19:16:59.189  1015  1254 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-17 19:16:59.189  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.189  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.189  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.189  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.189  7823  7823 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:59.189  7807  7807 D Compatibility: onReceive() it will make start service
,08-17 19:16:59.209  7852  7852 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.209  7852  7852 E Zygote  : v2
08-17 19:16:59.209  7852  7852 I libpersona: KNOX_SDCARD checking this for 10145
08-17 19:16:59.209  7840  7840 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:59.209  7852  7852 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:59.209  7852  7852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.209  7840  7840 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.209  7852  7852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.209  7852  7852 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.209  1015  1254 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7852 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:59.209  1015  1254 I ActivityManager: Killing 7121:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-17 19:16:59.219  1015  1254 I ActivityManager: Killing 7184:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-17 19:16:59.229  1015  1493 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-17 19:16:59.229  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-17 19:16:59.229  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:59.229  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:59.229  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-17 19:16:59.229  7823  7823 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-17 19:16:59.229  1015  1489 I ActivityManager: Killing 7171:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-17 19:16:59.239  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-17 19:16:59.239  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.239  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.239  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.239  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.239  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.249  1015  1509 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-17 19:16:59.249  1015  1509 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-17 19:16:59.249  7871  7871 E Zygote  : MountEmulatedStorage(),
08-17 19:16:59.249  7871  7871 E Zygote  : v2
08-17 19:16:59.259  7871  7871 I libpersona: KNOX_SDCARD checking this for 10052
,08-17 19:16:59.259  7871  7871 I libpersona: KNOX_SDCARD not a persona,
08-17 19:16:59.259  1015  1487 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7871 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-17 19:16:59.259  1015  1489 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast,
08-17 19:16:59.259  7852  7852 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:59.259  7852  7852 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:59.259  7807  7868 D Compatibility: onHandleIntent()
,08-17 19:16:59.259  7807  7868 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-17 19:16:59.259  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.259  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.259  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.259  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.259  7871  7871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.259  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.269  7871  7871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.269  1015  1055 D PackageManager: delete codoeFile: 
,08-17 19:16:59.269  7871  7871 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:59.269  7807  7868 D Compatibility: found: 2
,08-17 19:16:59.269  7840  7840 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-17 19:16:59.269  7840  7840 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:16:59.269  7840  7840 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 19:16:59.279  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-17 19:16:59.279  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-17 19:16:59.279  7807  7868 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-17 19:16:59.289  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-17 19:16:59.289  7807  7868 D Compatibility: skipping ResolveInfo{1d7366aa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-17 19:16:59.289  7807  7868 D Compatibility: considering ResolveInfo{4e6b29b com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-17 19:16:59.289  7807  7868 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-17 19:16:59.289  7807  7868 D Compatibility: enabling receiver ResolveInfo{1f877638 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-17 19:16:59.289  1015  1055 D PackageManager: result of delete: 1{460856428}
,08-17 19:16:59.289  7807  7868 D Compatibility: enabling receiver ResolveInfo{1a029611 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-17 19:16:59.289  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:16:59.289  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:59.289  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:59.299  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.299  7871  7871 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.309  7871  7871 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.309  7807  7868 D Compatibility: enabling receiver ResolveInfo{3ef94376 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-17 19:16:59.309  7740  7740 D AndroidRuntime: Shutting down VM
,08-17 19:16:59.319  7807  7868 D Compatibility: enabling receiver ResolveInfo{25f3dd77 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-17 19:16:59.319  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 19:16:59.319  1015  1055 D PackageManager: userId{-1}
08-17 19:16:59.319  1015  1055 D PackageManager: andCode{true}
,08-17 19:16:59.319  7889  7889 E Zygote  : MountEmulatedStorage()
,08-17 19:16:59.319  7889  7889 E Zygote  : v2
08-17 19:16:59.319  7889  7889 I libpersona: KNOX_SDCARD checking this for 10087
08-17 19:16:59.319  7889  7889 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:59.319  7889  7889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:59.319  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.319  7889  7889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:59.319  1015  1489 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7889 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-17 19:16:59.329  7889  7889 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:59.329  1015  1489 I ActivityManager: Killing 7209:com.osp.app.signin/u0a36 (adj 15): empty #21
08-17 19:16:59.329  7807  7868 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-17 19:16:59.329  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.329  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:16:59.329  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:16:59.329  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.339  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:16:59.339  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:16:59.339  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:16:59.339  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:16:59.339  1015  1134 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:16:59.339  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:16:59.349  7889  7889 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.349  7889  7889 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.359  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 19:16:59.359  7840  7840 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 19:16:59.359  7840  7840 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 19:16:59.359  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.359  7840  7840 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:16:59.359  7840  7840 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-17 19:16:59.359  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.359  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.369  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.379  7905  7905 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.379  7905  7905 E Zygote  : v2
08-17 19:16:59.379  7905  7905 I libpersona: KNOX_SDCARD checking this for 10003
08-17 19:16:59.379  7905  7905 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:59.379  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7905 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 19:16:59.379  7905  7905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:59.389  7905  7905 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:59.389  7905  7905 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.389  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 19:16:59.389  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-17 19:16:59.399  1015  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-17 19:16:59.399  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.399  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.399  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.399  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.399  7852  7852 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-17 19:16:59.399  7852  7852 D ThemeInfoUtil: isCurrentFestival = false
,08-17 19:16:59.399  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:59.419  7918  7918 E Zygote  : MountEmulatedStorage(),
08-17 19:16:59.419  7918  7918 E Zygote  : v2
,08-17 19:16:59.419  7918  7918 I libpersona: KNOX_SDCARD checking this for 10029
08-17 19:16:59.419  7918  7918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.419  7918  7918 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:59.419  7918  7918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.429  7918  7918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.429  7905  7905 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:59.429  7905  7905 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.429  1015  1489 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7918 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-17 19:16:59.429  1015  1489 I ActivityManager: Killing 7138:com.android.chrome/u0a77 (adj 15): empty #21
,08-17 19:16:59.429  1015  1489 I ActivityManager: Killing 7034:com.google.android.talk/u0a102 (adj 15): empty #21
,08-17 19:16:59.439  1015  3124 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:59.449  7918  7918 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:59.449  1015  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-17 19:16:59.449  1015  1493 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:59.449  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.449  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.449  7918  7918 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:59.449  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.449  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.459  7935  7935 E Zygote  : MountEmulatedStorage(),
08-17 19:16:59.459  7935  7935 I libpersona: KNOX_SDCARD checking this for 10148
08-17 19:16:59.459  7935  7935 E Zygote  : v2
08-17 19:16:59.459  7935  7935 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:59.469  7935  7935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.469  1015  1489 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7935 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-17 19:16:59.469  1015  1489 I ActivityManager: Killing 7231:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-17 19:16:59.469  7935  7935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.469  7935  7935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.499  7935  7935 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.499  7935  7935 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.499  1015  7904 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-17 19:16:59.499  1015  7904 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-17 19:16:59.509  1015  7904 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:59.509  1015  7904 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:59.509  1015  7904 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-17 19:16:59.509  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-17 19:16:59.509  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-17 19:16:59.509  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:59.509  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:59.509  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-17 19:16:59.519  7740  7740 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:16:59.519  1015  1254 I ActivityManager: Killing 7264:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-17 19:16:59.529  1495  1495 I Choreographer: Skipped 35 frames!  The application may be doing too much work on its main thread.
,08-17 19:16:59.529  1495  1495 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35c21b45 time:158697
,08-17 19:16:59.539  1015  1039 W libprocessgroup: failed to kill pid 7231: No such process
,08-17 19:16:59.539  7484  7484 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-17 19:16:59.549  7935  7935 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-17 19:16:59.549  1015  1509 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-17 19:16:59.559  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-17 19:16:59.559  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-17 19:16:59.559  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:59.559  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:59.559  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-17 19:16:59.559  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 19:16:59.569  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.569  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.569  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.569  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.569  7918  7954 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-17 19:16:59.589  7958  7958 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:59.589  7958  7958 E Zygote  : v2
,08-17 19:16:59.589  7958  7958 I libpersona: KNOX_SDCARD checking this for 10032
08-17 19:16:59.589  7958  7958 I libpersona: KNOX_SDCARD not a persona,
,08-17 19:16:59.589  7958  7958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:59.589  1015  1487 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7958 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:59.589  7958  7958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:59.599  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-17 19:16:59.599  7958  7958 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-17 19:16:59.599  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.599  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.599  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.599  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.639  7958  7958 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.639  7958  7958 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.639  7974  7974 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.639  7974  7974 E Zygote  : v2
08-17 19:16:59.639  7974  7974 I libpersona: KNOX_SDCARD checking this for 10152
08-17 19:16:59.639  7974  7974 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:59.639  7974  7974 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:59.639  7918  7954 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-17 19:16:59.639  7918  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:59.639  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.639  7974  7974 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:59.639  7918  7954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:59.639  7918  7954 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-17 19:16:59.639  7974  7974 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.649  1015  1134 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7974 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-17 19:16:59.649  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-17 19:16:59.649  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-17 19:16:59.659  7974  7974 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-17 19:16:59.659  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-17 19:16:59.659  7974  7974 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:59.669   307   307 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 27.845ms
,08-17 19:16:59.669  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-17 19:16:59.669  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-17 19:16:59.669  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-17 19:16:59.669  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-17 19:16:59.679  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-17 19:16:59.679  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-17 19:16:59.679  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-17 19:16:59.679  7445  7953 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-17 19:16:59.689   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 21.003ms
,08-17 19:16:59.689  7918  7954 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-17 19:16:59.689  7918  7954 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-17 19:16:59.689  7918  7954 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-17 19:16:59.689  7918  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:59.699  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.699  7918  7954 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:59.699  7445  7445 I art     : Explicit concurrent mark sweep GC freed 598(45KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 3.058ms total 107.284ms
,08-17 19:16:59.699  7974  7974 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-17 19:16:59.699  7974  7974 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-17 19:16:59.709  7484  7484 D BluetoothAdapter: cancelDiscovery
08-17 19:16:59.709  1015  1509 I ActivityManager: Killing 7281:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-17 19:16:59.709   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 21.312ms
,08-17 19:16:59.709  7608  7628 D BluetoothAdapterProperties: mDiscovering is false
08-17 19:16:59.709  7608  7628 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-17 19:16:59.709  7484  7484 D BluetoothAdapter: cancelDiscovery = true
08-17 19:16:59.709  7484  7484 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-17 19:16:59.709  1015  3124 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 19:16:59.719  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 19:16:59.719  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:16:59.739  7484  7484 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,08-17 19:16:59.739  7974  7974 I TapandpayWidget:Utils: Clear T&P info.
,08-17 19:16:59.739  7918  7954 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:16:59.739  7918  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:59.739  7484  7484 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,08-17 19:16:59.739  7484  7484 E SQLiteDatabase: Error inserting timestamp=1471454219725 message=Predictor: service stopped by removePlaceCategories()
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:59.739  7484  7484 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:59.739  1015  1254 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
08-17 19:16:59.739  7484  7484 E UserAnalysis: It failed to insert to dump_log table
08-17 19:16:59.739  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:59.749  7974  7974 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-17 19:16:59.749  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.749  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.749  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.749  1015  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:59.759  7918  7954 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 19:16:59.759  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.759  7918  7954 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 19:16:59.769  7918  7954 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:16:59.769  7991  7991 E Zygote  : MountEmulatedStorage()
08-17 19:16:59.769  7991  7991 E Zygote  : v2
08-17 19:16:59.769  7991  7991 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:16:59.769  7991  7991 I libpersona: KNOX_SDCARD not a persona,
08-17 19:16:59.769  7918  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
08-17 19:16:59.779  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.779  7918  7954 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.,
,08-17 19:16:59.779  7991  7991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:16:59.779  7918  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 19:16:59.779  7991  7991 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:59.779  7918  7954 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:59.779  7918  7954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 19:16:59.779  1015  1254 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7991 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
08-17 19:16:59.779  7991  7991 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:59.789  1015  7904 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
08-17 19:16:59.789  1015  7904 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.789  1015  7904 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.789  1015  7904 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.789  1015  7904 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:59.789  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.789  7918  7954 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:59.789  7918  7954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:59.799   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:59.809  7918  7954 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-17 19:16:59.809  7918  7954 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:16:59.809  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.809  7918  7954 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:59.819  7918  7954 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-17 19:16:59.819  7918  7954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:59.819  7918  7954 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:59.819  7918  7954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:59.829  8009  8009 E Zygote  : MountEmulatedStorage()
```
