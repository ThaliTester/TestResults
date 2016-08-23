#### Test 82337235c858ce8_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
,08-23 15:43:13.259  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 15:43:13.259  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
--------- beginning of main
08-23 15:43:13.269  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 15:43:13.259  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:13.269  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 15:43:13.259  1015  1027 D BatteryService: stay LED for fully charged
08-23 15:43:13.259  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 15:43:13.259  1015  1015 I MotionRecognitionService: Plugged
08-23 15:43:13.259  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-23 15:43:13.269  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:13.269  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 15:43:13.279  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 15:43:13.279  1174  1174 D SViewCoverView: level :100 plugged : 2
08-23 15:43:13.279  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 15:43:13.279  3174  3276 D HeadsetStateMachine: Disconnected process message: 10
08-23 15:43:13.299  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 15:43:13.299  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 15:43:13.299  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 15:43:13.539  6796  6796 D AndroidRuntime: 
08-23 15:43:13.539  6796  6796 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:43:13.539  6796  6796 D AndroidRuntime: CheckJNI is OFF
08-23 15:43:13.539  6796  6796 D AndroidRuntime: readGMSProperty: start
08-23 15:43:13.539  6796  6796 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:13.539  6796  6796 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:13.539  6796  6796 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:13.539  6796  6796 D AndroidRuntime: readGMSProperty: end
08-23 15:43:13.539  6796  6796 D AndroidRuntime: addProductProperty: start
08-23 15:43:13.679  6796  6796 E AffinityControl: AffinityControl: registerfunction enter
08-23 15:43:13.699  6796  6796 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 15:43:13.719  1015  1471 E PersonaManagerService: inState():  stateMachine is null !!
08-23 15:43:13.719  1015  1471 I PersonaManagerService: PersonaId don't exist
08-23 15:43:13.719  1015  1471 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 15:43:13.719  1015  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:13.739  1015  1471 W ActivityManager: mDVFSHelper.acquire()
08-23 15:43:13.749   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-23 15:43:13.749   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-23 15:43:13.759  1015  1471 D FocusedStackFrame: Set to : 0
08-23 15:43:13.759  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 15:43:13.759  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 15:43:13.769  1015  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:13.769  1015  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:13.769  1015  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:13.769  1015  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:13.779  6807  6807 E Zygote  : MountEmulatedStorage()
08-23 15:43:13.779  6807  6807 I libpersona: KNOX_SDCARD checking this for 10171
08-23 15:43:13.779  6807  6807 E Zygote  : v2
08-23 15:43:13.779  6807  6807 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:13.779  1015  1471 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6807 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 15:43:13.779  1015  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 15:43:13.779  1015  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:13.779  6807  6807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:13.779  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:13.779  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 15:43:13.789  6807  6807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:13.789  6807  6807 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 15:43:13.789  1015  1471 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:13.789  1015  1471 D InputDispatcher: Focus left window: 1498
08-23 15:43:13.789   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-23 15:43:13.789  6796  6796 D AndroidRuntime: Shutting down VM
08-23 15:43:13.799  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:13.809  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:13.809  6807  6807 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:13.809  6807  6807 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:13.809  1015  1766 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 15:43:13.819  1015  1015 V ActivityManager: Display changed displayId=0
08-23 15:43:13.819  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 15:43:13.839  1015  1766 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:13.849  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 15:43:13.869   258   439 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-23 15:43:13.879   258   446 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-23 15:43:13.879  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{2d856ece token=android.os.BinderProxy@ce4707b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 15:43:13.879  1498  1498 D Launcher: onTrimMemory. Level: 20
08-23 15:43:13.949  6807  6807 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 15:43:13.959  6807  6807 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6857-6859)
08-23 15:43:13.959  6807  6807 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 15:43:13.989  6807  6807 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2841fbe6}
08-23 15:43:13.999  6807  6807 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 15:43:13.999  6796  6796 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:14.009  6807  6807 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 15:43:14.049  6807  6807 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-23 15:43:14.049   291   291 E SMD     : DCD OFF
08-23 15:43:14.049  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:14.049  6807  6807 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 15:43:14.099  6807  6807 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:14.099  6807  6807 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:14.099  6807  6807 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:14.099  6807  6807 I Adreno-EGL: Local Branch: 
08-23 15:43:14.099  6807  6807 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:14.099  6807  6807 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:14.099  6807  6807 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-23 15:43:14.199  6807  6807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 15:43:14.209  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 15:43:14.209  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 15:43:14.219  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 15:43:14.219  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 15:43:14.339  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:14.339  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{5e6b6a6 u0 com.test.thalitest/.MainActivity t2}
08-23 15:43:14.349  6807  6807 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 15:43:14.359  6807  6807 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 15:43:14.359  6807  6807 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-23 15:43:14.369  6807  6807 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-23 15:43:14.379  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:14.379  6807  6807 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:14.419  6807  6846 D OpenGLRenderer: Render dirty regions requested: true
08-23 15:43:14.419  1015  1497 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 15:43:14.419  1015  1497 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:14.419  1015  1497 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 15:43:14.419  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:14.419  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 15:43:14.429  6807  6834 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-23 15:43:14.429  6807  6807 V ActivityThread: updateVisibility : ActivityRecord{3a6d6546 token=android.os.BinderProxy@1bb23f2b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 15:43:14.439  6807  6807 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:14.439  6807  6807 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 15:43:14.449   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-23 15:43:14.469  1015  4394 D InputDispatcher: Focus entered window: 6807
08-23 15:43:14.469  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:14.469  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:14.469  6807  6807 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 15:43:14.469  6807  6846 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 15:43:14.479  6807  6846 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 15:43:14.479  6807  6846 D OpenGLRenderer: Enabling debug mode 0
08-23 15:43:14.499  1015  1491 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 15:43:14.499  1174  1174 I StatusBar: Icon Only
08-23 15:43:14.499  1174  1174 D PanelView: There is/are notification(s) 
08-23 15:43:14.499  1015  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 15:43:14.519  1015  1046 I ActivityManager: Displayed Component not be shown by security: +675ms (total +753ms)
08-23 15:43:14.519  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5e6b6a6 u0 com.test.thalitest/.MainActivity t2} time:107413
08-23 15:43:14.519  1015  1046 W ActivityManager: mDVFSHelper.release()
08-23 15:43:14.529   258  1037 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-23 15:43:14.529   258   439 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-23 15:43:14.529  6807  6807 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 15:43:14.529  6807  6807 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bb23f2b time:107422
08-23 15:43:14.549  1871  1871 I SamsungIME: getCurrentCandidateView
08-23 15:43:14.659  1871  1871 D SamsungIME: Dismiss ExpandCandiate
08-23 15:43:14.719  6807  6807 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6807
,08-23 15:43:14.839  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:14.869  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:14.879  1871  1871 I SamsungIME: KeybaordView init() : load resources
,08-23 15:43:14.909  1871  1871 I SamsungIME: getCurrentKeyboard
,08-23 15:43:14.909  1871  1871 I SamsungIME: getTextKeyboard
,08-23 15:43:14.929  6807  6807 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:43:14.939  1871  1871 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 15:43:15.019  6807  6855 D jxcore_app_log: JniHelper::setJavaVM(0xb7c782b0), pthread_self() = -1205838136
,08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 15:43:15.029  6807  6855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e3d5dcc added. We now have 1 listener(s)
,08-23 15:43:15.029  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-23 15:43:15.029  6807  6855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-23 15:43:15.029  6807  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 15:43:15.029  6807  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 15:43:15.039  6807  6855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e5491b added. We now have 1 listener(s)
08-23 15:43:15.039  6807  6855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-23 15:43:15.039  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-23 15:43:15.039  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:43:15.039  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:43:15.049  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-23 15:43:15.049  6807  6855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 15:43:15.049  6807  6855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 15:43:15.049  6807  6855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-23 15:43:15.059  6807  6855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:15.059  6807  6855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:43:15.059  6807  6855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:43:15.059  6807  6855 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 15:43:15.059  6807  6855 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 15:43:15.059  6807  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:15.059  6807  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:15.089  6807  6807 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:43:15.389  1015  1327 E Watchdog: !@Sync 3
,08-23 15:43:15.559  6807  6863 W jxcore-log: Initializing JXcore engine
08-23 15:43:15.559  6807  6863 W jxcore-log: JXcore engine is ready
,08-23 15:43:15.609  2045  2045 E audit   : type=1400 msg=audit(1471959795.609:205): avc:  denied  { ioctl } for  pid=6863 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 15:43:15.619  2045  2045 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:15.619  2045  2045 E audit   : type=1300 msg=audit(1471959795.609:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e0778f8 items=0 ppid=311 ppcomm=main pid=6863 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 15:43:15.619  2045  2045 E audit   : type=1320 msg=audit(1471959795.609:205): 
,08-23 15:43:15.629  6807  6863 W jxcore-log: Starting JXcore engine
,08-23 15:43:15.729  6807  6863 W jxcore-log: Platform android
08-23 15:43:15.729  6807  6863 W jxcore-log: 
08-23 15:43:15.729  6807  6863 W jxcore-log: Process ARCH arm
08-23 15:43:15.729  6807  6863 W jxcore-log: 
,08-23 15:43:15.939  6807  6863 I jxcore-log: JXcore Cordova bridge is ready!
08-23 15:43:15.939  6807  6863 I jxcore-log: 
,08-23 15:43:15.939  6807  6863 W jxcore-log: JXcore engine is started
,08-23 15:43:15.949  6807  6855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 15:43:15.949  6807  6807 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:43:16.659   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 15:43:16.659   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 15:43:17.049   291   291 E SMD     : DCD OFF
,08-23 15:43:20.049   291   291 E SMD     : DCD OFF
,08-23 15:43:20.579  1015  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-23 15:43:20.679  1015  3364 D SSRM:n  : SIOP:: AP = 320
,08-23 15:43:21.659   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:22.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:23.049   291   291 E SMD     : DCD OFF,
,08-23 15:43:23.309  1015  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 15:43:23.309  1015  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-23 15:43:23.309  1015  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:23.309  1015  1552 D BatteryService: stay LED for fully charged
08-23 15:43:23.309  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 15:43:23.319  1015  1015 I MotionRecognitionService: Plugged
08-23 15:43:23.319  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-23 15:43:23.319  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 15:43:23.319  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 15:43:23.319  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:23.319  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:23.329  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:23.329  3174  3276 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:23.349  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-23 15:43:23.349  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:23.349  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:23.349  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:23.349  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:23.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:23.769  5685  5685 D FactoryTest: Not factory mode
,08-23 15:43:23.769  5685  5685 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 15:43:23.779  5685  5685 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 15:43:23.779  5685  5685 D MTPRx   : still no open session command from host, so toast
,08-23 15:43:23.779  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 15:43:23.779  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 15:43:23.779  5685  5685 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116678
,08-23 15:43:23.779  1015  1553 E PersonaManagerService: inState():  stateMachine is null !!
,08-23 15:43:23.779  1015  1553 I PersonaManagerService: PersonaId don't exist
08-23 15:43:23.779  1015  1553 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 15:43:23.789  1015  1553 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:23.789  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:23.789  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:23.789  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-23 15:43:23.799  1015  1553 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:23.809  1015  1553 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:23.819  1015  1553 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:23.819  1015  1553 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:23.819  1015  1553 D InputDispatcher: Focused application set to: xxxx
,08-23 15:43:23.819  1015  1553 D InputDispatcher: Focus left window: 6807
,08-23 15:43:23.819  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 15:43:23.819  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:23.819  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:23.829  5685  5685 E MTPRx   : started activity for popup
,08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:23.879  5685  5685 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 15:43:23.899  5685  5685 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 15:43:23.899  1015  4394 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:23.899  1015  4394 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:23.899  1015  4394 D InputDispatcher: Focused application set to: xxxx
,08-23 15:43:23.899  1015  4394 D InputDispatcher: Focus entered window: 6807
,08-23 15:43:23.909  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:23.909  1015  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 15:43:23.909  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:23.909  1015  1480 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1c1c0e51 attribute=null, token = android.os.BinderProxy@1463aae1
,08-23 15:43:23.949  5685  5685 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 15:43:23.959  5685  5685 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-23 15:43:23.959  5685  5685 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 15:43:23.979  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 15:43:23.979  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-23 15:43:23.979  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-23 15:43:23.979  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 15:43:23.979  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:23.979  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 15:43:23.979  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:23.979  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:23.979  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:23.999  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 15:43:23.999  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 15:43:23.999  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@173b0617 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1b038d6c, 16908290=android.view.AbsSavedState$1@1b038d6c}, android:focusedViewId=100}]}]
,08-23 15:43:23.999  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 15:43:23.999  6807  6807 V ActivityThread: updateVisibility : ActivityRecord{3a6d6546 token=android.os.BinderProxy@1bb23f2b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 15:43:23.999  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 15:43:23.999  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 15:43:23.999  6807  6807 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bb23f2b time:116895
,08-23 15:43:24.009  1015  4392 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:24.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:25.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:26.049   291   291 E SMD     : DCD OFF,
,08-23 15:43:26.669   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-23 15:43:26.799  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-23 15:43:27.109  1015  1094 V AlarmManager: waitForAlarm result :4
,08-23 15:43:27.109  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.169  1015  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:27.169  1015  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmInGmsTaskService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.169  1015  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.169  1015  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.169  1015  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.209  1015  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:27.209  1015  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmInGmsTaskService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.209  1015  1471 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.209  1015  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:27.209  1015  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.249  4845  4845 D ConnectivityManager: CallingUid : 10011, CallingPid : 4845
,08-23 15:43:27.259  1015  1471 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 15:43:27.259  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-23 15:43:27.259  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-23 15:43:27.259  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-23 15:43:27.259  4845  6872 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 15:43:27.309  4845  6873 W DriveInitializer: Background init thread started
,08-23 15:43:27.339   257   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-23 15:43:27.339   257   509 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 15:43:27.339  4845  6873 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-23 15:43:27.359  4845  6874 I GCM-GMS : Registering GMS 745476177629
,08-23 15:43:27.369  1015  1766 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.379  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.379  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.379  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.389  1015  1766 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:27.389  1015  1766 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.389  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.389  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.389  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.389  2056  6882 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,08-23 15:43:27.399  1015  4392 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 15:43:27.399  1015  4392 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 15:43:27.399  1015  4392 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.399  1015  4392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.399  1015  4392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.399  2056  2056 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:27.409  2056  2056 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:27.419  4845  6873 W DriveInitializer: Background init thread ended
,08-23 15:43:27.419  1015  1471 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 15:43:27.419  1015  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.419  1015  1471 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.419  1015  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.419  1015  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.429  2056  6882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:27.429   278   985 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 15:43:27.429   278   985 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 15:43:27.439  1015  1766 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-23 15:43:27.439  2056  6882 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 15:43:27.439  2056  6882 I qtaguid : Tagging socket 62 with tag 1000040700000000{268436487,0} for uid -1, pid: 2056, getuid(): 10011
08-23 15:43:27.439  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.439  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.439  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.479  2056  6882 I qtaguid : Tagging socket 65 with tag 1000040700000000{268436487,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:27.499  2056  2227 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:27.499  2056  2227 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 15:43:27.499  2056  2227 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:27.529  2056  2227 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:27.639  2056  6882 I qtaguid : Untagging socket 62
,08-23 15:43:27.639  4845  6874 I GCM-GMS : Got GMS registration
,08-23 15:43:27.669  2056  2056 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-23 15:43:27.719  1015  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:27.719  1015  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.719  1015  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.719  1015  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.719  1015  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.739  1015  4392 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-23 15:43:27.739  1015  4392 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.749  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.749  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.749  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.779  2056  2056 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:27.789  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:27.789  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.789  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.789  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.789  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.809  2056  6888 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,08-23 15:43:27.809  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.809  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.809  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.829  2056  2056 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-23 15:43:27.849  1015  4392 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:27.849  1015  4392 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.849  1015  4392 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.849  1015  4392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.849  1015  4392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.059  1015  1480 I art     : Explicit concurrent mark sweep GC freed 40207(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.408ms total 147.836ms
,08-23 15:43:28.079  1015  1766 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:28.079  1015  1766 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.079  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.079  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.079  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.109  4845  6891 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-23 15:43:28.109  4845  6891 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 15:43:28.119  1015  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:28.119  1015  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.119  1015  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.119  1015  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.119  1015  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.169  1015  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.169  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.179  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.179  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.239  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.239  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.239  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.239  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.239  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:28.239  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:28.239  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:28.239  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:28.259  6894  6894 E Zygote  : MountEmulatedStorage(),
08-23 15:43:28.259  6894  6894 I libpersona: KNOX_SDCARD checking this for 10011
08-23 15:43:28.259  6894  6894 E Zygote  : v2
08-23 15:43:28.259  6894  6894 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:28.259  1015  1497 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6894 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-23 15:43:28.269  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 15:43:28.269  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:28.269  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:28.289  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:28.289  6894  6894 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:28.309  6894  6894 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-23 15:43:28.309  6894  6894 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 15:43:28.339  6894  6894 I MultiDex: VM with version 2.1.0 has multidex support
08-23 15:43:28.339  6894  6894 I MultiDex: install
08-23 15:43:28.339  6894  6894 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 15:43:28.369  6894  6894 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 15:43:28.429  6894  6894 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 15:43:28.429  6894  6894 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e729182: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 15:43:28.429  6894  6894 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 15:43:28.449  6894  6894 D ChimeraCfgMgr: Reading stored module config,
,08-23 15:43:28.499  6894  6908 I art     : Background sticky concurrent mark sweep GC freed 21423(1038KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 7.878ms total 40.410ms
,08-23 15:43:28.529  6894  6894 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 15:43:28.539  6894  6894 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 15:43:28.549  6894  6908 W art     : Suspending all threads took: 13.842ms
,08-23 15:43:28.559  6894  6908 I art     : Background partial concurrent mark sweep GC freed 888(159KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 16.705ms total 39.294ms
,08-23 15:43:28.569  6894  6911 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 15:43:28.609   283   283 D WVCdm   : Instantiating CDM.
,08-23 15:43:28.609   283   685 I WVCdm   : CdmEngine::OpenSession
,08-23 15:43:28.609   283   685 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-23 15:43:28.639   283   685 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 15:43:28.669   283   685 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-23 15:43:28.709  6894  6904 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-23 15:43:28.709  6894  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 15:43:28.709  6894  6904 I System.out: (HTTPLog)-Static: isShipBuild true
,08-23 15:43:28.709  6894  6904 I System.out: (HTTPLog)-Thread-1223-512700647: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 15:43:28.709  6894  6904 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.709   278   985 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 15:43:28.709   278   985 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 15:43:28.719  6894  6904 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:28.719  6894  6904 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6894, getuid(): 10011
,08-23 15:43:28.729   283   685 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 15:43:28.729   283   720 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-23 15:43:28.729   283   720 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 15:43:28.729   283   720 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-23 15:43:28.739   283   720 D WVCdm   : PrepareKeyRequest: nonce=4124929373
,08-23 15:43:29.009  6894  6904 I qtaguid : Untagging socket 30
,08-23 15:43:29.049   291   291 E SMD     : DCD OFF
,08-23 15:43:29.639  6919  6919 I dex2oat : ----------------------------------------------------
08-23 15:43:29.639  6919  6919 I dex2oat : <SS>: S T A R T I N G . . .
08-23 15:43:29.639  6919  6919 I dex2oat : <SS>: Zip is absent. Canceled.
,08-23 15:43:29.639  6919  6919 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-23 15:43:29.689  6919  6919 I dex2oat : dex2oat took 50.345ms (threads: 4)
,08-23 15:43:29.699  6894  6904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:29.699  6894  6904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:29.699  6894  6904 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:29.699  6894  6904 I Adreno-EGL: Local Branch: 
08-23 15:43:29.699  6894  6904 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:29.699  6894  6904 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:29.699  6894  6904 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:29.779  6894  6904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:29.779  6894  6904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:29.779  6894  6904 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:29.779  6894  6904 I Adreno-EGL: Local Branch: 
08-23 15:43:29.779  6894  6904 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:29.779  6894  6904 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:29.779  6894  6904 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:29.829  1015  3381 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:29.919  6894  6904 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:29.919  6894  6904 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:29.919  6894  6904 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:29.919  6894  6904 I Adreno-EGL: Local Branch: 
08-23 15:43:29.919  6894  6904 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:29.919  6894  6904 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:29.919  6894  6904 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:29.989  2056  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:29.989   278   985 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 15:43:29.989   278   985 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 15:43:29.989  2056  6893 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:29.999  2056  6893 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:30.029  2056  6893 I qtaguid : Tagging socket 74 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:30.179  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:30.179  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-23 15:43:30.179  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:30.179  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.179  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.239  1015  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.249  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:30.249  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.249  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.289   283   283 I WVCdm   : CdmEngine::CloseSession
,08-23 15:43:30.289   283   283 I WVCdm   : L3 Terminate.
,08-23 15:43:30.549  4346  4357 I art     : Explicit concurrent mark sweep GC freed 1412(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 697us total 21.281ms
,08-23 15:43:30.579  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-23 15:43:30.579  1015  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.589  1015  1221 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:30.589  1015  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.589  1015  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.599  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.599  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:30.599  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.599  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.629  2056  2056 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2bf1ae0c-12db-4b92-81fc-cc0f2d8a4485
,08-23 15:43:30.649  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 15:43:30.649  6807  6863 I jxcore-log: 
,08-23 15:43:30.699  1015  3364 D SSRM:n  : SIOP:: AP = 340
,08-23 15:43:30.779  2056  2219 W GCoreFlp: No location to return for getLastLocation()
,08-23 15:43:30.809  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.809  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:30.809  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.809  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.809  1015  1212 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.809  1015  1212 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:30.809  1015  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.809  1015  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.819  1015  1766 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:30.819  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:30.819  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.819  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:30.859  4845  6927 D UdcContextInitService: registered all accounts: true
,08-23 15:43:30.909  2056  2237 I art     : Explicit concurrent mark sweep GC freed 72737(4MB) AllocSpace objects, 25(925KB) LOS objects, 39% free, 11MB/18MB, paused 1.349ms total 76.396ms
,08-23 15:43:30.909  2056  2222 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:30.919  2056  2237 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 15:43:30.969  1015  1553 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:30.969  1015  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
08-23 15:43:30.969  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:30.969  1015  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:30.969  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.079  1015  1766 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.079  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.079  1015  1766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.079  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.099  1015  1497 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 15:43:31.099  1015  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 15:43:31.109  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.109  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.109  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.109  1015  1212 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.109  1015  1212 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.109  1015  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.109  1015  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.159  2056  2237 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 15:43:31.159  2056  2237 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-23 15:43:31.169  1015  1212 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.169  1015  1212 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.169  1015  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.169  1015  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.169  2056  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 15:43:31.169  2056  6933 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 15:43:31.169  2056  6937 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 15:43:31.169  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.169  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.169  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.169  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.179   278   985 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 15:43:31.179   278   985 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 15:43:31.179  2056  6937 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 15:43:31.179  2056  6937 I qtaguid : Tagging socket 89 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:31.199  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.199  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.199  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.199  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.199  2056  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 15:43:31.199  2056  6933 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 15:43:31.209  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.209  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:31.209  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.209  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.229  1015  1552 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:31.229  1015  1552 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:31.229  1015  1552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:31.229  1015  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:31.229  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 15:43:31.229  2056  6935 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 15:43:31.239  2056  6933 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-23 15:43:31.239  2056  6933 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-23 15:43:31.239  2056  6937 I qtaguid : Tagging socket 91 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:31.259  2056  6933 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 15:43:31.309  1015  1766 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:31.379  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:31.389  2056  6933 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:31.389  2056  6933 I qtaguid : Tagging socket 94 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:31.409  2056  6933 I qtaguid : Tagging socket 97 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:31.479  2056  6937 I qtaguid : Untagging socket 89
,08-23 15:43:31.489  2056  2237 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 15:43:31.609  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:31.609   278   985 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 15:43:31.609   278   985 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 15:43:31.619  2056  6933 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:31.619  2056  6933 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:31.649  2056  6933 I qtaguid : Tagging socket 68 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:31.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:31.929  1015  1497 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:31.939  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:31.939  2056  6933 I qtaguid : Tagging socket 55 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:32.049   291   291 E SMD     : DCD OFF
,08-23 15:43:32.069  1015  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:32.079  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:32.079  2056  6933 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:32.209  1015  4394 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:32.219  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:32.219  2056  6933 I qtaguid : Tagging socket 55 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:32.359  1015  1473 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:32.379  2056  6933 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:32.379  2056  6933 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2056, getuid(): 10011
,08-23 15:43:32.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:33.229  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 15:43:33.229  6807  6863 I jxcore-log: 
,08-23 15:43:33.269  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 15:43:33.269  6807  6863 I jxcore-log: 
,08-23 15:43:33.279  2056  6938 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:33.279  2056  6938 I qtaguid : Tagging socket 89 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2056, getuid(): 10011
,08-23 15:43:33.299  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 15:43:33.299  6807  6863 I jxcore-log: 
,08-23 15:43:33.329  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 15:43:33.329  6807  6863 I jxcore-log: 
,08-23 15:43:33.329  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 15:43:33.329  6807  6863 I jxcore-log: 
,08-23 15:43:33.369  1015  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:33.369  1015  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 15:43:33.369  1015  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:33.369  1015  1480 D BatteryService: stay LED for fully charged
,08-23 15:43:33.369  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:33.369  1015  1015 I MotionRecognitionService: Plugged
,08-23 15:43:33.369  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:33.379  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 15:43:33.379  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:33.389  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 15:43:33.389  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 15:43:33.389  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 15:43:33.389  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:33.399  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:33.399  3174  3276 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:33.409  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:33.409  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:33.409  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:33.479  2056  6938 I qtaguid : Untagging socket 89
,08-23 15:43:33.479  2056  2237 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 15:43:33.499  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 15:43:33.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:34.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:34.979  1015  1456 I ActivityManager: Killing 6475:com.samsung.helphub/1000 (adj 15): empty #21
,08-23 15:43:35.059   291   291 E SMD     : DCD OFF,
,08-23 15:43:35.669   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:36.669   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 15:43:37.159  6807  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 15:43:37.159  6807  6863 I jxcore-log: 
,08-23 15:43:37.169  6807  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 15:43:37.169  6807  6863 I jxcore-log: 
,08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:37.169  6807  6863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 15:43:37.169  6807  6863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 15:43:37.179  6807  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 15:43:37.179  6807  6863 I jxcore-log: 
,08-23 15:43:37.179  6807  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 15:43:37.179  6807  6863 I jxcore-log: 
,08-23 15:43:38.059   291   291 E SMD     : DCD OFF,
,08-23 15:43:40.729  1015  3364 D SSRM:n  : SIOP:: AP = 340
,08-23 15:43:41.059   291   291 E SMD     : DCD OFF
,08-23 15:43:42.059  6807  6863 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 15:43:42.059  6807  6863 I jxcore-log: 
,08-23 15:43:42.219  6807  6863 I jxcore-log: ERROR runTests: 
08-23 15:43:42.219  6807  6863 I jxcore-log: 
,08-23 15:43:42.219  6807  6863 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie',
08-23 15:43:42.219  6807  6863 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:43:42.229  6807  6863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:43:42.229  6807  6863 I jxcore-log: 
,08-23 15:43:42.229  6807  6807 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 15:43:42.229  6807  6807 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 15:43:42.229  1015  4392 D FocusedStackFrame: Set to : 0
08-23 15:43:42.239  1015  4392 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:42.239  1015  4392 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 15:43:42.239  1015  4392 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:42.239  1015  4392 D InputDispatcher: Focus left window: 6807
,08-23 15:43:42.239  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:42.239  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:42.249  1015  4392 I ActivityManager: Killing 6509:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 15:43:42.259  6807  6807 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 15:43:42.259  6807  6807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 15:43:42.259  6807  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 15:43:42.259  6807  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 15:43:42.259  6807  6855 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 27ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 15:43:42.259  6807  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 15:43:42.259  6807  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:43:42.259  6807  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e3d5dcc removed from the list
08-23 15:43:42.259  6807  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:43:42.259  6807  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e5491b removed from the list
08-23 15:43:42.259  6807  6807 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:43:42.259  6807  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 15:43:42.269  6807  6807 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 15:43:42.289   258  2046 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-23 15:43:42.289   258  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-23 15:43:42.319  1015  1028 W ActivityManager: mDVFSHelper.acquire(),
,08-23 15:43:42.329  1015  1028 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 15:43:42.349  1498  1498 D Launcher: onRestart, Launcher: 301345149
,08-23 15:43:42.349  1498  1498 D Launcher: onStart, Launcher: 301345149
,08-23 15:43:42.349  1498  1498 D Launcher.HomeView: onStart
,08-23 15:43:42.359  1498  1498 D Launcher: onResume, Launcher: 301345149
,08-23 15:43:42.359  1015  4392 D SettingsProvider: name = kids_home_mode
08-23 15:43:42.359  1015  4392 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 15:43:42.359  1015  4392 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 15:43:42.359  1015  4392 D SettingsProvider: selectionArgs: false
08-23 15:43:42.359  1015  4392 D SettingsProvider: selectionArgs: 10006
08-23 15:43:42.359  1015  4392 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 15:43:42.359  1015  4392 D SettingsProvider: ret = -1
,08-23 15:43:42.359  1498  1498 D Launcher.HomeView: onResume
,08-23 15:43:42.359  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 15:43:42.369  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.369  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.369  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-23 15:43:42.369  1498  1498 D MenuAppsGridFragment: onResume
,08-23 15:43:42.379  1015  1473 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-23 15:43:42.379  1015  1473 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-23 15:43:42.379  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-23 15:43:42.379  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 15:43:42.399  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:42.399  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.399  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
08-23 15:43:42.399  1015  1473 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 15:43:42.399  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.399  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.399  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.399  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:42.419  6953  6953 E Zygote  : MountEmulatedStorage()
,08-23 15:43:42.419  6953  6953 E Zygote  : v2
08-23 15:43:42.419  1015  1473 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6953 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-23 15:43:42.419  6953  6953 I libpersona: KNOX_SDCARD checking this for 10039
08-23 15:43:42.419  6953  6953 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:42.419  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:42.419  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 15:43:42.419  1015  1221 D ActivityManager: handle home activity for 0
08-23 15:43:42.419  1015  1221 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 15:43:42.419  1015  1221 D KnoxTimeoutHandler: post home show event for user 0
08-23 15:43:42.419  1015  1221 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 15:43:42.419  1015  1221 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:42.419  1015  1221 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 15:43:42.419  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 15:43:42.419  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 15:43:42.419  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:42.419  1498  1498 D Launcher.HomeView: onPause
,08-23 15:43:42.419  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 15:43:42.419  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.419  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.419  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-23 15:43:42.429  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.429  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-23 15:43:42.429  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.429  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.429  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-23 15:43:42.429  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.429  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:42.429  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.429  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:42.429  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.449  6962  6962 E Zygote  : MountEmulatedStorage()
08-23 15:43:42.449  6962  6962 E Zygote  : v2
08-23 15:43:42.449  6962  6962 I libpersona: KNOX_SDCARD checking this for 10089
08-23 15:43:42.449  6962  6962 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:42.449  6962  6962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:42.449  1015  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6962 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
08-23 15:43:42.449  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.449  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-23 15:43:42.449  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.449  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-23 15:43:42.449  6962  6962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:42.449  6962  6962 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-23 15:43:42.449  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.449  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.449  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.449  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.459  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:42.469  6953  6953 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:42.469  6979  6979 E Zygote  : MountEmulatedStorage()
08-23 15:43:42.469  6979  6979 E Zygote  : v2
08-23 15:43:42.469  6979  6979 I libpersona: KNOX_SDCARD checking this for 10139
08-23 15:43:42.469  6979  6979 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:42.469  1015  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6979 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-23 15:43:42.469  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:42.479  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:42.479  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:42.489   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-23 15:43:42.489  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 15:43:42.499  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 15:43:42.499  1015  1497 D InputDispatcher: Focus entered window: 1498
08-23 15:43:42.499  1015  1471 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.499  1015  1471 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1498, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-23 15:43:42.499  6962  6962 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:42.499  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:42.499  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:42.499  6962  6962 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:42.499  1498  1498 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 15:43:42.499  1015  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.499  1015  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:42.509  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.509  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 15:43:42.509  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 15:43:42.509  6953  6953 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 15:43:42.509  2575  2575 D Recents_RecreateReceiver: onReceive by home
,08-23 15:43:42.519  1498  1498 D Launcher.HomeView: onStop
08-23 15:43:42.519  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{2d856ece token=android.os.BinderProxy@ce4707b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-23 15:43:42.519  1015  1552 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 15:43:42.519  1015  1766 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.519  1015  1766 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-23 15:43:42.519  1015  1766 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.519  1015  1766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-23 15:43:42.529  6950  6950 D AndroidRuntime: 
08-23 15:43:42.529  6950  6950 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:43:42.529  1015  6998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 15:43:42.529  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.529  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.529  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.529  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:42.529  6950  6950 D AndroidRuntime: CheckJNI is OFF
,08-23 15:43:42.529  6950  6950 D AndroidRuntime: readGMSProperty: start
08-23 15:43:42.529  6950  6950 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:42.529  6950  6950 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:42.529  6950  6950 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:42.529  6950  6950 D AndroidRuntime: readGMSProperty: end
08-23 15:43:42.529  6950  6950 D AndroidRuntime: addProductProperty: start
,08-23 15:43:42.539  1174  1174 I StatusBar: Icon Only
,08-23 15:43:42.539  1174  1174 D PanelView: There is/are notification(s) 
,08-23 15:43:42.549  7000  7000 E Zygote  : MountEmulatedStorage()
08-23 15:43:42.549  7000  7000 I libpersona: KNOX_SDCARD checking this for 10084
08-23 15:43:42.549  7000  7000 E Zygote  : v2
08-23 15:43:42.549  7000  7000 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:42.549  7000  7000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:42.549  7000  7000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:42.549  7000  7000 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-23 15:43:42.559  1015  1766 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7000 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-23 15:43:42.569  6807  6807 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 15:43:42.569  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:42.569  6979  6979 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:42.579  1871  1871 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-23 15:43:42.579  6962  6962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:42.579  6962  6962 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-23 15:43:42.579  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-23 15:43:42.589  1498  1498 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ce4707b time:135481
,08-23 15:43:42.589  7000  7000 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:42.589  7000  7000 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:42.609  7000  7000 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:42.619  6979  6979 V TaskCloserActivity: TaskCloserActivity enter()
,08-23 15:43:42.629  1015  1046 W ActivityManager: mDVFSHelper.release(),
08-23 15:43:42.629  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2934ca25 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:135522
08-23 15:43:42.629  6979  6979 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-23 15:43:42.659  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:42.659  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.659  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-23 15:43:42.659  1015  1473 I ActivityManager: Killing 6536:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-23 15:43:42.679  1015  1221 W ActivityManager: userId = 0, bbcId = -10000,
08-23 15:43:42.679  1015  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-23 15:43:42.679  1015  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:42.679  1015  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-23 15:43:42.689  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.689  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.689  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:42.689  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:42.689  6950  6950 E AffinityControl: AffinityControl: registerfunction enter,
,08-23 15:43:42.699  7026  7026 E Zygote  : MountEmulatedStorage(),
08-23 15:43:42.699  7026  7026 I libpersona: KNOX_SDCARD checking this for 10135
08-23 15:43:42.699  7026  7026 E Zygote  : v2
08-23 15:43:42.699  7026  7026 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:42.699  7026  7026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:42.699  1015  1221 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7026 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,08-23 15:43:42.699  1015  1221 I ActivityManager: Killing 6587:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 15:43:42.709  1015  1221 I ActivityManager: Killing 6568:com.sec.android.fotaclient/u0a8 (adj 15): empty #21,
,08-23 15:43:42.709  7026  7026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 15:43:42.709  7026  7026 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 15:43:42.729  6950  6950 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 15:43:42.739  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:42.739  7026  7026 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:42.739  7026  7026 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:42.749  6953  6953 D NearbySource: Nearby Source Create!
,08-23 15:43:42.749  6953  6953 D NearbyContext: Nearby Context Create!
,08-23 15:43:42.759  1015  1766 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 15:43:42.759  1015  1766 D PackageManager: START PACKAGE DELETE: observer{341138348}
08-23 15:43:42.759  1015  1766 D PackageManager: pkg{<packageName>}
08-23 15:43:42.759  1015  1766 D PackageManager: user{0}
08-23 15:43:42.759  1015  1766 D PackageManager: caller{2000}
08-23 15:43:42.759  1015  1766 D PackageManager: flags{2}
08-23 15:43:42.759  1015  1766 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 15:43:42.759  1015  1766 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 15:43:42.759  1015  1766 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 15:43:42.759  1015  1766 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 15:43:42.759  7026  7026 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
08-23 15:43:42.759  7026  7026 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:42.759  7026  7026 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 15:43:42.759  7026  7026 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-23 15:43:42.759  7026  7026 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,08-23 15:43:42.769  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-23 15:43:42.769  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-23 15:43:42.769  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 15:43:42.769  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 15:43:42.769  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 15:43:42.769  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-23 15:43:42.789  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-23 15:43:42.789  1015  1041 I ActivityManager: Killing 6807:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 15:43:42.799   257   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/,
08-23 15:43:42.799   257   509 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 15:43:42.799  6953  6953 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 15:43:42.799  6953  6953 D SLinkSource: Samsung link source created
,08-23 15:43:42.919  1015  1055 W PackageSettings: Skipping PackageSetting{18f803b7 com.example.hello/10168} due to missing metadata
,08-23 15:43:42.949  1015  1491 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 15:43:42.959  6953  7043 D ContactProvider: getAllContactInfoList Start
,08-23 15:43:42.969  1015  1456 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 15:43:42.969  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-23 15:43:42.969  6953  6953 D GalleryCacheReady: Receive : home resume
,08-23 15:43:42.999  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 15:43:43.029  2649  2649 I art     : Explicit concurrent mark sweep GC freed 19469(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.167ms total 40.305ms
,08-23 15:43:43.029  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 15:43:43.039  1871  1871 E SamsungIME: mOCRHelper is null
,08-23 15:43:43.049  2056  2222 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:43.059  1015  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:43.059  1015  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.059  1015  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-23 15:43:43.069  6134  6134 D Mms/UIEventReceiver: ui event
08-23 15:43:43.069  1474  1474 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 15:43:43.079  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:43.079  4845  4845 I art     : Explicit concurrent mark sweep GC freed 22171(1373KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/16MB, paused 1.284ms total 97.249ms
,08-23 15:43:43.089  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-23 15:43:43.089  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 15:43:43.089  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-23 15:43:43.089  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 15:43:43.089  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 15:43:43.099  1015  1553 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-23 15:43:43.099  1015  1553 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:43.099  1015  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.099  1015  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 15:43:43.109  1457  1457 D RegisteredServicesCache: empty dynamic service
,08-23 15:43:43.109  1015  1122 V NetworkStats: performPollLocked() took 15ms
08-23 15:43:43.109  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:43.109  6979  6979 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-23 15:43:43.109  1015  1491 I ActivityManager: Killing 6617:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-23 15:43:43.119  2901  2901 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 15:43:43 GMT+02:00 2016
,08-23 15:43:43.129  1015  4394 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 15:43:43.129  1015  4394 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.139  1015  4394 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:43.139  1015  4394 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.139  1015  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 15:43:43.139  1457  1457 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 15:43:43.139  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:43.149  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 15:43:43.149  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:43.149  2901  2901 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 15:43:43.149  1015  1497 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-23 15:43:43.149  1015  1497 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 15:43:43.159  1015  1212 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 15:43:43.159  1015  1212 D SecContentProvider2: mCursor = null
,08-23 15:43:43.169  6715  6715 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 15:43:43.169  2901  2901 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 15:43:43.179  1015  1471 I TactileAssist: enable value -1
08-23 15:43:43.179  1015  1471 I TactileAssist: internal enable value -1
08-23 15:43:43.179  1015  1471 I TactileAssist: intensity value -1
08-23 15:43:43.179  1015  1471 I TactileAssist: saveAppList value true
,08-23 15:43:43.179  2901  2901 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 15:43:43.189  1015  1471 I TactileAssist: List of disabled apps :
,08-23 15:43:43.189  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-23 15:43:43.189  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.189  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.189  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.189  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.209  7046  7046 E Zygote  : MountEmulatedStorage(),
08-23 15:43:43.209  7046  7046 E Zygote  : v2
,08-23 15:43:43.209  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7046 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 15:43:43.209  1015  1015 I art     : Explicit concurrent mark sweep GC freed 46353(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 4.265ms total 226.819ms
08-23 15:43:43.209  7046  7046 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:43.209  7046  7046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:43.209  7046  7046 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:43.209  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-23 15:43:43.209  7046  7046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:43.209  1015  1055 I art     : WaitForGcToComplete blocked for 148.284ms for cause Explicit
,08-23 15:43:43.209  7046  7046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.219  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.219  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.219  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.219  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.219  2901  2901 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 15:43:43.229  7060  7060 E Zygote  : MountEmulatedStorage()
,08-23 15:43:43.229  7060  7060 E Zygote  : v2
,08-23 15:43:43.229  7060  7060 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:43.229  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:43.229  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.239  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:43.239  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.239  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:43.239  7046  7046 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:43.249  7046  7046 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.249  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 15:43:43.249  1015  1221 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 15:43:43.249  1015  1221 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.249  1015  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:43.249  1015  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 15:43:43.249  1015  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-23 15:43:43.259  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:43.259  6715  6715 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 15:43:43.259  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.269  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 15:43:43.269  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 15:43:43.269  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 15:43:43.269  6715  6715 D elm:15121: ElmAgentService : onCreate()
,08-23 15:43:43.269  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-23 15:43:43.269  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-23 15:43:43.269  6715  7074 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-23 15:43:43.279  6715  7074 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-23 15:43:43.279  6715  7074 D elm:15121: MDMBridge.getInstance()
08-23 15:43:43.279  6715  7074 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:43.279  6715  7074 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:43.279  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-23 15:43:43.319  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-23 15:43:43.319  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.319  6715  6715 D elm:15121: ElmAgentService : onDestroy().
,08-23 15:43:43.329  7060  7060 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-23 15:43:43.329  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 15:43:43.339  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 15:43:43.339  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 15:43:43.339  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-23 15:43:43.339  1015  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-23 15:43:43.339  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.339  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.339  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.339  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.339  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.349  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.349  7077  7077 E Zygote  : MountEmulatedStorage()
08-23 15:43:43.349  7077  7077 E Zygote  : v2
08-23 15:43:43.349  7077  7077 I libpersona: KNOX_SDCARD checking this for 10048
08-23 15:43:43.349  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:43.349  7077  7077 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:43.349  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.359  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 15:43:43.359  1015  1491 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7077 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-23 15:43:43.359  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:43.359  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 15:43:43.359  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-23 15:43:43.369  6953  7043 D ContactProvider: getAllContactInfoList End
08-23 15:43:43.369  6953  7043 I syncContacts: thread: 1233, sync time = 534
08-23 15:43:43.369  7046  7046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-23 15:43:43.379  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-23 15:43:43.379  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.379  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:43.379  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.379  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-23 15:43:43.389  1015  1473 D SecContentProvider2: uri = -1 selection = getSealedState
08-23 15:43:43.389  1015  1473 D SecContentProvider2: mCursor = null
,08-23 15:43:43.389  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:43.389  7077  7077 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.399  7060  7060 I PopupuiReceiver_KNOX: getSealedState : true
,08-23 15:43:43.399  1015  1456 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-23 15:43:43.399  1015  1456 D SecContentProvider2: mCursor = null
,08-23 15:43:43.399  7060  7060 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-23 15:43:43.399  1015  1480 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-23 15:43:43.399  1015  1480 D SecContentProvider2: mCursor = null
,08-23 15:43:43.409  7060  7060 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-23 15:43:43.409  7060  7060 D PopupuiReceiver: Action package removed
,08-23 15:43:43.409  1015  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-23 15:43:43.409  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.409  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.409  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.409  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.419  7093  7093 E Zygote  : MountEmulatedStorage(),
,08-23 15:43:43.429  7093  7093 E Zygote  : v2
08-23 15:43:43.429  7093  7093 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:43.429  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:43.429  7093  7093 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:43.429  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:43.429  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:43.429  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-23 15:43:43.429  1015  1221 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:43.439  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:43.439  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 15:43:43.439  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:43.439  1015  1027 D BatteryService: stay LED for fully charged
,08-23 15:43:43.439  1015  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-23 15:43:43.449  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.449  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.449  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.449  1015  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.449  7077  7077 D Compatibility: onReceive() it will make start service
,08-23 15:43:43.469  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:43.469  7093  7093 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.469  2901  7045 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-23 15:43:43.479  1015  1055 I art     : Explicit concurrent mark sweep GC freed 13599(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.603ms total 259.701ms
,08-23 15:43:43.479  1015  1212 I art     : WaitForGcToComplete blocked for 312.436ms for cause Explicit
,08-23 15:43:43.479  2901  7045 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-23 15:43:43.479   311   311 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 54.509ms
,08-23 15:43:43.499   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.911ms
,08-23 15:43:43.509  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 15:43:43.509  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.519   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.821ms
,08-23 15:43:43.529  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.539  7108  7108 E Zygote  : MountEmulatedStorage(),
08-23 15:43:43.539  7108  7108 E Zygote  : v2
08-23 15:43:43.539  7108  7108 I libpersona: KNOX_SDCARD checking this for 10145
08-23 15:43:43.539  7108  7108 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:43.539  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.539  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:43.539  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.549  1015  1221 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7108 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 15:43:43.549  1015  1552 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:43.549  1015  1221 I ActivityManager: Killing 6637:com.osp.app.signin/u0a36 (adj 15): empty #21
08-23 15:43:43.549  1015  1552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.549  1015  1552 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-23 15:43:43.549  1015  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-23 15:43:43.549  1015  1552 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-23 15:43:43.559  1015  4394 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-23 15:43:43.559  1015  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.559  1015  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.559  1015  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.559  1015  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.569  7077  7116 D Compatibility: onHandleIntent(),
08-23 15:43:43.569  7093  7093 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:43.569  7077  7116 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-23 15:43:43.579  7124  7124 E Zygote  : MountEmulatedStorage()
08-23 15:43:43.579  7124  7124 E Zygote  : v2
08-23 15:43:43.579  7124  7124 I libpersona: KNOX_SDCARD checking this for 10052
08-23 15:43:43.579  7124  7124 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:43.579  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.579  2901  2901 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-23 15:43:43.579  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:43.579  1015  4394 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7124 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-23 15:43:43.589  1015  1491 I ActivityManager: Killing 6655:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-23 15:43:43.589  7077  7116 D Compatibility: found: 2
,08-23 15:43:43.589  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.599  7077  7116 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-23 15:43:43.599  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:43.599  7077  7116 D Compatibility: skipping ResolveInfo{d3a893c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-23 15:43:43.599  7108  7108 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:43.599  7077  7116 D Compatibility: considering ResolveInfo{1824e6c5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-23 15:43:43.599  7077  7116 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-23 15:43:43.609  7093  7093 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-23 15:43:43.609  1015  1055 D PackageManager: delete codoeFile: 
,08-23 15:43:43.609  1015  1480 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,08-23 15:43:43.609  1015  1480 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-23 15:43:43.609  7077  7116 D Compatibility: enabling receiver ResolveInfo{764781a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 15:43:43.619  1015  1766 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-23 15:43:43.629  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.629  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-23 15:43:43.629  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.629  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.629  1015  1766 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.629  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-23 15:43:43.629  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:43.629  7124  7124 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.639  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-23 15:43:43.639  1015  1055 D PackageManager: result of delete: 1{341138348}
,08-23 15:43:43.639  7140  7140 E Zygote  : MountEmulatedStorage()
08-23 15:43:43.639  7140  7140 E Zygote  : v2
08-23 15:43:43.639  7140  7140 I libpersona: KNOX_SDCARD checking this for 10087
08-23 15:43:43.639  7140  7140 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:43.639  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.639  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:43.639  1015  1766 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7140 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-23 15:43:43.649  1015  1766 I ActivityManager: Killing 6670:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-23 15:43:43.649  7077  7116 D Compatibility: enabling receiver ResolveInfo{7b3f4b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-23 15:43:43.649  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.659  6950  6950 D AndroidRuntime: Shutting down VM
,08-23 15:43:43.689  1015  1212 I art     : Explicit concurrent mark sweep GC freed 5631(280KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 15.349ms total 212.495ms
,08-23 15:43:43.689  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:43.689  7140  7140 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.699  7077  7116 D Compatibility: enabling receiver ResolveInfo{c4fd28 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 15:43:43.709  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:43.709  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:43.709  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:43.709  7077  7116 D Compatibility: enabling receiver ResolveInfo{df22a41 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-23 15:43:43.709  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 15:43:43.709  1015  1055 D PackageManager: userId{-1}
08-23 15:43:43.709  1015  1055 D PackageManager: andCode{true}
,08-23 15:43:43.719  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.719  7077  7116 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-23 15:43:43.739  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.749  7108  7108 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-23 15:43:43.749  7108  7108 D ThemeInfoUtil: isCurrentFestival = false
,08-23 15:43:43.759  1015  4392 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-23 15:43:43.759  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 15:43:43.759  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 15:43:43.759  1015  4392 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.759  1015  4392 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.759  1015  4392 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.759  1015  4392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 15:43:43.769  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 15:43:43.779  7156  7156 E Zygote  : MountEmulatedStorage()
,08-23 15:43:43.779  7156  7156 I libpersona: KNOX_SDCARD checking this for 10148
08-23 15:43:43.779  7156  7156 E Zygote  : v2
,08-23 15:43:43.779  7156  7156 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:43.779  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:43.779  1015  4392 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7156 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
08-23 15:43:43.779  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:43.779  1015  3364 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 15:43:43.779  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:43.779  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 15:43:43.779  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null,
,08-23 15:43:43.789  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:43.789  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 15:43:43.789  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 15:43:43.789  1015  4392 I ActivityManager: Killing 6691:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-23 15:43:43.789  1015  1221 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-23 15:43:43.799  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 15:43:43.799  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.799  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.799  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.799  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.799  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.799  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.809  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:43.809  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:43.809  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:43.819  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:43.819  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:43.819  7169  7169 E Zygote  : MountEmulatedStorage()
,08-23 15:43:43.819  7169  7169 E Zygote  : v2
08-23 15:43:43.819  7169  7169 I libpersona: KNOX_SDCARD checking this for 1000
,08-23 15:43:43.819  7169  7169 I libpersona: KNOX_SDCARD not a persona,
08-23 15:43:43.819  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:43.819  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 15:43:43.819  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:43.819  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7169 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:43.819  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:43.819  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-23 15:43:43.819  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:43.819  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:43.829  1015  1028 I ActivityManager: Killing 6606:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-23 15:43:43.829  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:43.829  1015  1212 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:43.829  1015  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.829  7156  7156 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:43.829  1015  1212 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:43.829  1015  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:43.829  1015  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 15:43:43.839  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-23 15:43:43.839  1015  4394 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:43.839  1015  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-23 15:43:43.839  1015  4394 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:43.839  1015  1766 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 15:43:43.839  1015  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:43.839  1015  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 15:43:43.849  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-23 15:43:43.849  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:43.849  7169  7169 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.849  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 15:43:43.859  6950  6950 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:43.869  1015  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-23 15:43:43.869  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.869  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.869  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.869  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.899  1015  1497 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7188 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 15:43:43.899  7188  7188 E Zygote  : MountEmulatedStorage()
08-23 15:43:43.899  7188  7188 E Zygote  : v2
08-23 15:43:43.899  7188  7188 I libpersona: KNOX_SDCARD checking this for 10055
08-23 15:43:43.899  7188  7188 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:43.899  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:43.899  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:43.899  7169  7169 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 15:43:43.899  7169  7169 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 15:43:43.899  7169  7169 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-23 15:43:43.899  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:43.909  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:43.909  7156  7156 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-23 15:43:43.909  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 15:43:43.909  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:43.909  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 15:43:43.909  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:43.909  1015  1015 I MotionRecognitionService: Plugged
08-23 15:43:43.909  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:43.929  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 15:43:43.929  7188  7188 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:43.939  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 15:43:43.939  3174  3276 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:43.939  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 15:43:43.939  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:43.949  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:43.949  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:43.949  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 15:43:43.969  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-23 15:43:43.969  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-23 15:43:43.969  7169  7169 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-23 15:43:43.969  7169  7169 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 15:43:43.969  7169  7169 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 15:43:43.969  7169  7169 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-23 15:43:43.979  1015  1491 W ActivityManager: userId = 0, bbcId = -10000,
08-23 15:43:43.979  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:43.979  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-23 15:43:43.989  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-23 15:43:43.989  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.989  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.989  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:43.989  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:43.999  7188  7188 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 15:43:44.019  1015  1480 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7206 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
08-23 15:43:44.019  1015  1480 I ActivityManager: Killing 6748:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-23 15:43:44.019  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-23 15:43:44.029  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:44.029  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:44.029  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:44.029  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:44.029  7206  7206 E Zygote  : MountEmulatedStorage()
08-23 15:43:44.029  7206  7206 E Zygote  : v2
08-23 15:43:44.029  7206  7206 I libpersona: KNOX_SDCARD checking this for 10029
08-23 15:43:44.029  7206  7206 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:44.029  7206  7206 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:44.029  7206  7206 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:44.039  7188  7188 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-23 15:43:44.039  7188  7188 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 15:43:44.039  7188  7188 D UserAnalysis: Create SecureDbHelper
,08-23 15:43:44.049  7206  7206 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:44.049  7214  7214 E Zygote  : MountEmulatedStorage(),
08-23 15:43:44.049  1015  1480 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7214 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-23 15:43:44.049  7214  7214 E Zygote  : v2
08-23 15:43:44.049  7214  7214 I libpersona: KNOX_SDCARD checking this for 10152
08-23 15:43:44.049  7214  7214 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:44.059  7214  7214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:44.059  7214  7214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:44.059   291   291 E SMD     : DCD OFF
,08-23 15:43:44.059  7214  7214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:44.069  1015  1473 I ActivityManager: Killing 6544:com.android.calendar/u0a131 (adj 15): empty #21
,08-23 15:43:44.069  7206  7206 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:44.069  7206  7206 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:44.079  7214  7214 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:44.079  7214  7214 D ActivityThread: Added TimaKeyStore provider

```
