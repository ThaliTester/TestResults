#### Test 8288334166fab8f_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-29 16:40:15.603  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:40:15.603  1015  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:40:15.603  1015  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:40:15.603  1015  1484 D BatteryService: stay LED for fully charged
08-29 16:40:15.603  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-29 16:40:15.603  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:40:15.613  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:40:15.613  1015  1015 I MotionRecognitionService: Plugged
08-29 16:40:15.613  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:40:15.613  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:40:15.613  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-29 16:40:15.623  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:40:15.623  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
08-29 16:40:15.633  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 16:40:15.633  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:40:15.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:15.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:15.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:15.873  6813  6813 D AndroidRuntime: 
08-29 16:40:15.873  6813  6813 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 16:40:15.883  6813  6813 D AndroidRuntime: CheckJNI is OFF
08-29 16:40:15.883  6813  6813 D AndroidRuntime: readGMSProperty: start
08-29 16:40:15.883  6813  6813 D AndroidRuntime: readGMSProperty: already setted!!
08-29 16:40:15.883  6813  6813 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 16:40:15.883  6813  6813 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 16:40:15.883  6813  6813 D AndroidRuntime: readGMSProperty: end
08-29 16:40:15.883  6813  6813 D AndroidRuntime: addProductProperty: start
08-29 16:40:16.013  6813  6813 E AffinityControl: AffinityControl: registerfunction enter
08-29 16:40:16.043  6813  6813 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 16:40:16.063  1015  1027 E PersonaManagerService: inState():  stateMachine is null !!
08-29 16:40:16.063  1015  1027 I PersonaManagerService: PersonaId don't exist
08-29 16:40:16.063  1015  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 16:40:16.063  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 16:40:16.083  1015  1027 W ActivityManager: mDVFSHelper.acquire()
08-29 16:40:16.093   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-29 16:40:16.093   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-29 16:40:16.103  1015  1027 D FocusedStackFrame: Set to : 0
08-29 16:40:16.103  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 16:40:16.103  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 16:40:16.113  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:16.113  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:16.113  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:16.113  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:16.123  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 16:40:16.123  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 16:40:16.123  6826  6826 E Zygote  : MountEmulatedStorage()
08-29 16:40:16.123  6826  6826 E Zygote  : v2
08-29 16:40:16.123  1015  1027 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6826 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 16:40:16.123  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 16:40:16.123  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 16:40:16.123  6826  6826 I libpersona: KNOX_SDCARD checking this for 10171
08-29 16:40:16.123  6826  6826 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:16.123  6826  6826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:16.123   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-29 16:40:16.133  6826  6826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:16.133  1015  1027 D InputDispatcher: Focused application set to: xxxx
08-29 16:40:16.133  1015  1027 D InputDispatcher: Focus left window: 1498
08-29 16:40:16.133  6826  6826 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 16:40:16.133  6813  6813 D AndroidRuntime: Shutting down VM
08-29 16:40:16.133  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 16:40:16.133  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 16:40:16.153  6826  6826 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 16:40:16.153  6826  6826 D ActivityThread: Added TimaKeyStore provider
08-29 16:40:16.153  1015  1497 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 16:40:16.163  1015  1015 V ActivityManager: Display changed displayId=0
08-29 16:40:16.173  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 16:40:16.183  1015  1497 D PersonaManager: isKioskContainerExistOnDevice
08-29 16:40:16.193  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 16:40:16.213   258  1037 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-29 16:40:16.213   258  6093 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-29 16:40:16.223  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{c204364 token=android.os.BinderProxy@1d4b89ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 16:40:16.223  1498  1498 D Launcher: onTrimMemory. Level: 20
08-29 16:40:16.283  6826  6826 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 16:40:16.303  6826  6826 I cr.library_loader: Time to load native libraries: 1 ms (timestamps 6866-6867)
08-29 16:40:16.303  6826  6826 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 16:40:16.323  6826  6826 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3800af3c}
08-29 16:40:16.323  6826  6826 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 16:40:16.323  6826  6826 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 16:40:16.343  6813  6813 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 16:40:16.363  6826  6826 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 16:40:16.363  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 16:40:16.363  6826  6826 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 16:40:16.383  6826  6826 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 16:40:16.383  6826  6826 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 16:40:16.383  6826  6826 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 16:40:16.383  6826  6826 I Adreno-EGL: Local Branch: 
08-29 16:40:16.383  6826  6826 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 16:40:16.383  6826  6826 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 16:40:16.383  6826  6826 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 16:40:16.443  6826  6826 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 16:40:16.453  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 16:40:16.453  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 16:40:16.463  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 16:40:16.463  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 16:40:16.463   291   291 E SMD     : DCD OFF
,08-29 16:40:16.573  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 16:40:16.593  6826  6826 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 16:40:16.603  6826  6826 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-29 16:40:16.603  6826  6826 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-29 16:40:16.603  6826  6826 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-29 16:40:16.613  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 16:40:16.613  6826  6826 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 16:40:16.653  6826  6865 D OpenGLRenderer: Render dirty regions requested: true
,08-29 16:40:16.653  1015  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 16:40:16.653  1015  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 16:40:16.653  1015  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 16:40:16.653  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 16:40:16.653  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 16:40:16.663  6826  6853 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-29 16:40:16.673  6826  6826 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 16:40:16.673  6826  6826 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 16:40:16.683   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 16:40:16.693  1015  1134 D InputDispatcher: Focus entered window: 6826,
,08-29 16:40:16.703  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 16:40:16.703  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 16:40:16.703  6826  6826 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 16:40:16.703  6826  6865 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 16:40:16.703  6826  6865 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
08-29 16:40:16.703  6826  6865 D OpenGLRenderer: Enabling debug mode 0
,08-29 16:40:16.723  6826  6826 V ActivityThread: updateVisibility : ActivityRecord{1d259a5 token=android.os.BinderProxy@37a827e9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 16:40:16.763  1015  2093 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 16:40:16.773  1015  6870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:40:16.773  1174  1174 I StatusBar: Icon Only
,08-29 16:40:16.773  1174  1174 D PanelView: There is/are notification(s) 
,08-29 16:40:16.783  6826  6826 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-29 16:40:16.783  6826  6826 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37a827e9 time:107343
,08-29 16:40:16.783  1015  1046 I ActivityManager: Displayed Component not be shown by security: +599ms (total +678ms)
,08-29 16:40:16.783  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5080e15 u0 com.test.thalitest/.MainActivity t2} time:107349
08-29 16:40:16.783  1015  1046 W ActivityManager: mDVFSHelper.release()
,08-29 16:40:16.793   258  1037 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-29 16:40:16.793   258  6093 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 16:40:16.833  1859  1859 I SamsungIME: getCurrentCandidateView
,08-29 16:40:16.903  6826  6826 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6826
,08-29 16:40:16.923  1859  1859 D SamsungIME: Dismiss ExpandCandiate
,08-29 16:40:17.093  6826  6826 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 16:40:17.093  1859  1859 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 16:40:17.133  1859  1859 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 16:40:17.143  1859  1859 I SamsungIME: KeybaordView init() : load resources
,08-29 16:40:17.173  1859  1859 I SamsungIME: getCurrentKeyboard
08-29 16:40:17.173  1859  1859 I SamsungIME: getTextKeyboard
,08-29 16:40:17.193  1859  1859 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 16:40:17.193  6826  6872 D jxcore_app_log: JniHelper::setJavaVM(0xb703e2b0), pthread_self() = -1218624024
,08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 16:40:17.203  6826  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106be5d2 added. We now have 1 listener(s)
,08-29 16:40:17.203  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-29 16:40:17.203  6826  6872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 16:40:17.203  6826  6872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:40:17.203  6826  6872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 16:40:17.213  6826  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@379ddd59 added. We now have 1 listener(s)
,08-29 16:40:17.213  6826  6872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:17.223  6826  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-29 16:40:17.233  6826  6872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:17.233  6826  6872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:40:17.233  6826  6872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 16:40:17.233  6826  6872 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:17.233  6826  6872 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 16:40:17.233  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:17.243  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:17.263  6826  6826 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 16:40:17.563  1015  1322 E Watchdog: !@Sync 3
,08-29 16:40:17.743  6826  6879 W jxcore-log: Initializing JXcore engine
08-29 16:40:17.743  6826  6879 W jxcore-log: JXcore engine is ready
,08-29 16:40:17.803  2034  2034 E audit   : type=1400 msg=audit(1472481617.803:205): avc:  denied  { ioctl } for  pid=6879 comm="Thread-1275" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 16:40:17.803  2034  2034 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:17.803  2034  2034 E audit   : type=1300 msg=audit(1472481617.803:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f4528f8 items=0 ppid=309 ppcomm=main pid=6879 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1275" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 16:40:17.803  2034  2034 E audit   : type=1320 msg=audit(1472481617.803:205): 
,08-29 16:40:17.813  6826  6879 W jxcore-log: Starting JXcore engine
,08-29 16:40:17.913  6826  6879 W jxcore-log: Platform android
08-29 16:40:17.913  6826  6879 W jxcore-log: 
08-29 16:40:17.913  6826  6879 W jxcore-log: Process ARCH arm
08-29 16:40:17.913  6826  6879 W jxcore-log: 
,08-29 16:40:18.123  6826  6879 I jxcore-log: JXcore Cordova bridge is ready!,
08-29 16:40:18.123  6826  6879 I jxcore-log: 
08-29 16:40:18.123  6826  6879 W jxcore-log: JXcore engine is started
,08-29 16:40:18.123  6826  6872 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 16:40:18.133  6826  6826 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 16:40:18.463   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 16:40:18.463   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 16:40:19.463   291   291 E SMD     : DCD OFF,
,08-29 16:40:22.473   291   291 E SMD     : DCD OFF
,08-29 16:40:22.613  1015  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-29 16:40:22.743  1015  3363 D SSRM:n  : SIOP:: AP = 360
,08-29 16:40:23.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:40:24.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:40:24.953  5675  5675 D FactoryTest: Not factory mode
,08-29 16:40:24.953  5675  5675 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 16:40:24.953  5675  5675 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 16:40:24.953  5675  5675 D MTPRx   : still no open session command from host, so toast
,08-29 16:40:24.963  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-29 16:40:24.963  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 16:40:24.963  5675  5675 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115521
,08-29 16:40:24.963  1015  1524 E PersonaManagerService: inState():  stateMachine is null !!
,08-29 16:40:24.963  1015  1524 I PersonaManagerService: PersonaId don't exist
08-29 16:40:24.963  1015  1524 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 16:40:24.963  1015  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 16:40:24.963  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:24.963  1015  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:24.963  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 16:40:24.973  1015  1524 W ActivityManager: mDVFSHelper.acquire()
,08-29 16:40:24.993  1015  1524 D PersonaManager: isKioskContainerExistOnDevice
,08-29 16:40:24.993  1015  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 16:40:24.993  1015  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 16:40:24.993  1015  1524 D InputDispatcher: Focused application set to: xxxx
,08-29 16:40:24.993  1015  1524 D InputDispatcher: Focus left window: 6826
,08-29 16:40:24.993  5675  5675 E MTPRx   : started activity for popup
,08-29 16:40:25.003  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 16:40:25.003  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 16:40:25.023  5675  5675 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 16:40:25.023  5675  5675 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-29 16:40:25.033  5675  5675 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 16:40:25.033  5675  5675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 16:40:25.033  5675  5675 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 16:40:25.033  5675  5675 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 16:40:25.053  5675  5675 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 16:40:25.053  1015  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 16:40:25.053  1015  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 16:40:25.053  1015  1489 D InputDispatcher: Focused application set to: xxxx
,08-29 16:40:25.053  1015  1489 D InputDispatcher: Focus entered window: 6826
,08-29 16:40:25.063  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 16:40:25.063  1015  1497 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 16:40:25.063  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 16:40:25.063  1015  1497 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3aea9c5c attribute=null, token = android.os.BinderProxy@cfcd02c
,08-29 16:40:25.113  5675  5675 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 16:40:25.113  5675  5675 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-29 16:40:25.113  5675  5675 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 16:40:25.143  6826  6826 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 16:40:25.143  6826  6826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 16:40:25.143  6826  6826 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 16:40:25.143  6826  6826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 16:40:25.143  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 16:40:25.143  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 16:40:25.143  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 16:40:25.143  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 16:40:25.143  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 16:40:25.153  6826  6826 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 16:40:25.153  6826  6826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 16:40:25.163  6826  6826 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39bfb935 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9184ec3, 16908290=android.view.AbsSavedState$1@9184ec3}, android:focusedViewId=100}]}]
08-29 16:40:25.163  6826  6826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 16:40:25.163  6826  6826 V ActivityThread: updateVisibility : ActivityRecord{1d259a5 token=android.os.BinderProxy@37a827e9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 16:40:25.163  6826  6826 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 16:40:25.163  6826  6826 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 16:40:25.163  6826  6826 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37a827e9 time:115724
,08-29 16:40:25.163  1015  2093 D PersonaManager: isKioskContainerExistOnDevice
,08-29 16:40:25.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:25.473   291   291 E SMD     : DCD OFF
,08-29 16:40:25.653  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:40:25.653  1015  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:40:25.653  1015  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:40:25.653  1015  1497 D BatteryService: stay LED for fully charged
08-29 16:40:25.653  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:40:25.663  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:40:25.663  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:40:25.663  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:40:25.663  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:40:25.663  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:40:25.663  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:40:25.673  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:40:25.673  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:40:25.693  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:40:25.693  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:40:25.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:25.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:25.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:26.163  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-29 16:40:26.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:27.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:40:27.973  1015  1041 W ActivityManager: mDVFSHelper.release(),
,08-29 16:40:28.463   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 16:40:28.473   291   291 E SMD     : DCD OFF,
,08-29 16:40:29.443  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 16:40:29.443  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-29 16:40:29.473  2001  2001 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-29 16:40:29.653  1015  1027 I art     : Explicit concurrent mark sweep GC freed 32879(1884KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.420ms total 155.521ms
,08-29 16:40:29.663  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 16:40:29.663  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-29 16:40:29.663  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:29.663  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:29.663  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:29.673  4732  4732 D ConnectivityManager: CallingUid : 10011, CallingPid : 4732
08-29 16:40:29.683  1015  1496 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 16:40:29.683  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-29 16:40:29.683  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-29 16:40:29.683  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
08-29 16:40:29.683  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 16:40:29.743  4732  6888 W DriveInitializer: Background init thread started
,08-29 16:40:29.763   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-29 16:40:29.763   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:29.763  4732  6888 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-29 16:40:29.803  2001  2001 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-29 16:40:29.853  4732  6888 W DriveInitializer: Background init thread ended
,08-29 16:40:29.863  1015  1524 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 16:40:29.863  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,08-29 16:40:29.863  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:29.863  1015  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:29.863  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:29.893  1015  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 16:40:29.893  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-29 16:40:29.893  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:29.893  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:29.903  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:29.923  1015  1487 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-29 16:40:29.923  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-29 16:40:29.973  1015  2093 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:29.973  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:29.973  1015  2093 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:29.973  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:29.983  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:29.983  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:29.983  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:29.983  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:29.993  2001  2001 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 16:40:30.003  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 16:40:30.023  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.023  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.023  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.103  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 16:40:30.103  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-29 16:40:30.103  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.103  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.103  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.133  4732  6898 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-29 16:40:30.133  4732  6898 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-29 16:40:30.143  2001  6896 I art     : Explicit concurrent mark sweep GC freed 68066(3MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 10MB/17MB, paused 1.370ms total 71.597ms
,08-29 16:40:30.203  1015  1495 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 16:40:30.203  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 16:40:30.213  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.213  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.213  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.213  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 16:40:30.213  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 16:40:30.233  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:30.233  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.233  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.233  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.333  1015  1487 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 16:40:30.333  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-29 16:40:30.333  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.333  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.333  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.363  2001  6896 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-29 16:40:30.363  2001  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 16:40:30.363  2001  6896 I System.out: (HTTPLog)-Static: isShipBuild true
,08-29 16:40:30.363  2001  6896 I System.out: (HTTPLog)-Thread-265-145436014: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 16:40:30.363  2001  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:30.363   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:30.363   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 16:40:30.363  2001  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 16:40:30.363  2001  6896 I qtaguid : Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:30.413  2001  6896 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:30.423  6826  6879 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 16:40:30.423  6826  6879 I jxcore-log: 
,08-29 16:40:30.423  6826  6879 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 16:40:30.423  6826  6879 I jxcore-log: 
,08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:30.433  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:30.433  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:30.433  6826  6879 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 16:40:30.433  6826  6879 I jxcore-log: 
,08-29 16:40:30.433  6826  6879 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 16:40:30.433  6826  6879 I jxcore-log: 
,08-29 16:40:30.683  1015  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 16:40:30.683  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-29 16:40:30.683  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.683  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.693  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.733  2001  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:30.733   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:30.733   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 16:40:30.743  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:30.743  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.743  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.743  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.773  2001  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 16:40:30.773  2001  6896 I qtaguid : Tagging socket 63 with tag 1000120300000000{268440067,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:30.793  1015  2093 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:30.803  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:30.803  1015  2093 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:30.803  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:30.803  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:30.803  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:30.803  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:30.803  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:30.813  6906  6906 E Zygote  : MountEmulatedStorage(),
,08-29 16:40:30.813  6906  6906 E Zygote  : v2
08-29 16:40:30.823  6906  6906 I libpersona: KNOX_SDCARD checking this for 10011
,08-29 16:40:30.823  6906  6906 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:30.823  1015  2093 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6906 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-29 16:40:30.823  6906  6906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 16:40:30.823  6906  6906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 16:40:30.823  6906  6906 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 16:40:30.833  2001  6896 I qtaguid : Tagging socket 66 with tag 1000120300000000{268440067,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:30.843  6906  6906 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:30.853  6906  6906 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:30.863  6906  6906 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-29 16:40:30.863  6906  6906 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 16:40:30.903  6906  6906 I MultiDex: VM with version 2.1.0 has multidex support
08-29 16:40:30.903  6906  6906 I MultiDex: install
08-29 16:40:30.903  6906  6906 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 16:40:30.933  6906  6906 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-29 16:40:30.993  6906  6906 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 16:40:30.993  6906  6906 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39f390b8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-29 16:40:30.993  6906  6906 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 16:40:31.033  6906  6906 D ChimeraCfgMgr: Reading stored module config
,08-29 16:40:31.063  6906  6919 W art     : Suspending all threads took: 7.721ms
,08-29 16:40:31.073  2001  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:31.073  2001  6896 I qtaguid : Tagging socket 63 with tag 1000120300000000{268440067,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:31.073  6906  6919 I art     : Background sticky concurrent mark sweep GC freed 26056(1231KB) AllocSpace objects, 3(133KB) LOS objects, 3% free, 7MB/7MB, paused 12.985ms total 59.707ms
,08-29 16:40:31.113  6906  6923 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-29 16:40:31.113  6906  6906 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 16:40:31.113  6906  6906 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 16:40:31.183  1015  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:31.183  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:31.183  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:31.183  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:31.213  1015  1524 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 16:40:31.213  1015  1524 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 16:40:31.213  1015  1524 D SecContentProvider2: mCursor = null
,08-29 16:40:31.213  1015  1524 D WifiService: setWifiEnabled: true pid=6826, uid=10171
08-29 16:40:31.213  1015  1524 W ActivityManager: Permission Denial: getCurrentUser() from pid=6826, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 16:40:31.233   283   691 D WVCdm   : Instantiating CDM.
,08-29 16:40:31.233   283   283 I WVCdm   : CdmEngine::OpenSession
08-29 16:40:31.233   283   283 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-29 16:40:31.233  1015  1524 W WifiService: Failed getting userId using ActivityManagerNative
08-29 16:40:31.233  1015  1524 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6826, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 16:40:31.233  1015  1524 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 16:40:31.233  1015  1524 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 16:40:31.233  1015  1524 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 16:40:31.233  1015  1524 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 16:40:31.233  1015  1524 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 16:40:31.243  1015  1524 D SettingsProvider: name = wifi_on
,08-29 16:40:31.243  1015  1497 I WifiService: disconnect: pid=6826, uid=10171
,08-29 16:40:31.243  1366  1366 I wpa_supplicant: [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,08-29 16:40:31.253   283   283 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-29 16:40:31.273  1366  1366 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 16:40:31.273  1366  1366 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 16:40:31.273  1366  1366 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 16:40:31.273  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 16:40:31.273  1366  1366 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 16:40:31.273  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 16:40:31.273   283   283 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
08-29 16:40:31.273  1366  1366 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 16:40:31.273  1366  1366 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 16:40:31.273  1366  1366 E wpa_supplicant: Cmd 35605 not handled
08-29 16:40:31.273  1366  1366 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 16:40:31.273  1366  1366 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 16:40:31.273  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 16:40:31.273  1366  1366 I wpa_supplicant: First Scan Start
,08-29 16:40:31.273  1366  1366 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 16:40:31.273  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 16:40:31.273  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 16:40:31.273  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 16:40:31.273  1015  1129 D Tethering: InitialState.processMessage what=4
08-29 16:40:31.273  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 16:40:31.273  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 16:40:31.273  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 16:40:31.283  1015  1129 E Tethering: No numeric data
,08-29 16:40:31.283  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 16:40:31.283  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 16:40:31.283  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 16:40:31.283  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 16:40:31.283  1015  1129 D Tethering: clearTetheredNotification()
,08-29 16:40:31.283  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 16:40:31.283  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.283  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 16:40:31.283  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:31.283  1174  1174 D HotspotTile: updateTetherState():false, false
08-29 16:40:31.283  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:31.293  6826  6879 D BluetoothAdapter: enable(),
,08-29 16:40:31.293  1015  1121 V NetworkStats: performPollLocked() took 7ms
08-29 16:40:31.293  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.293  6826  6879 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 16:40:31.293  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.293  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.303  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:31.303  1015  3997 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:31.303  1015  3997 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 16:40:31.303  1015  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:31.303  1015  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:31.303  6826  6879 I jxcore-log: Unit Test app is loaded
08-29 16:40:31.303  6826  6879 I jxcore-log: 
,08-29 16:40:31.313  6826  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:40:31.313  6826  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@352b2340 added. We now have 2 listener(s)
,08-29 16:40:31.313  6826  6826 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 16:40:31.323  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 16:40:31.323  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:40:31.323  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:40:31.323  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:40:31.323  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9bb279 added. We now have 2 listener(s)
08-29 16:40:31.323  6826  6879 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:40:31.323  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-29 16:40:31.323   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74aa7c8
08-29 16:40:31.323   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-29 16:40:31.333   269   269 I rmt_storage: wakelock acquired: 1, error no: 42,
,08-29 16:40:31.333  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
08-29 16:40:31.333   269   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219843960)
08-29 16:40:31.333  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 16:40:31.333  1015  1124 E WifiNative-wlan0: do suspend true
08-29 16:40:31.333   278  1014 D CommandListener: Clearing all IP addresses on wlan0
08-29 16:40:31.333   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-29 16:40:31.333  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:31.333  2001  3043 V NativeCrypto: Read error: ssl=0xb752d690: I/O error during system call, Connection timed out
,08-29 16:40:31.343  4326  4339 I art     : Explicit concurrent mark sweep GC freed 1508(52KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 730us total 28.370ms
08-29 16:40:31.343  2001  3043 V NativeCrypto: SSL shutdown failed: ssl=0xb752d690: I/O error during system call, Broken pipe
,08-29 16:40:31.343  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 16:40:31.343  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 16:40:31.343  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 16:40:31.343  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-29 16:40:31.353  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:31.353  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 16:40:31.353  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.353  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.353  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.353  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:31.353  2001  3043 E GCM     : Wifi connection closed with errorCode 20
,08-29 16:40:31.353  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 16:40:31.353   283  1334 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-29 16:40:31.353   283  1334 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-29 16:40:31.353   283  1334 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-29 16:40:31.353  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 16:40:31.353  1015  1124 E WifiStateMachine: Start Disconnecting Watchdog 1
,08-29 16:40:31.353  1366  1366 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 16:40:31.363  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 16:40:31.363   283  1334 D WVCdm   : PrepareKeyRequest: nonce=3391756306
08-29 16:40:31.373  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 16:40:31.373  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 16:40:31.373  1015  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-29 16:40:31.373  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:31.373  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:31.373  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:31.373  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:31.383  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.383  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.383  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:31.383  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:31.383  6826  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:31.383  6826  6879 D ExecuteNativeTests: Running unit tests
08-29 16:40:31.383  1015  1484 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 16:40:31.383  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 16:40:31.383  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:31.383  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:31.383  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:31.383  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:31.393  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:31.393  1617  1617 I Hs20UtilService: Starting #8
08-29 16:40:31.393  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast
,08-29 16:40:31.393  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.393  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.393  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.393  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:31.393  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:31.393  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:31.393  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:31.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.393   269   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-29 16:40:31.393   269   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 16:40:31.393   269   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219843960) wakelock released: 1, error no: 0
08-29 16:40:31.393   269   326 I rmt_storage: 
,08-29 16:40:31.393   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb74aa7c8,
08-29 16:40:31.403  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-30ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
08-29 16:40:31.403  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-30ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 16:40:31.403  1015  1495 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=6932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 16:40:31.403  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 16:40:31.403  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 16:40:31.403  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-29 16:40:31.403  1015  1742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 16:40:31.403  1015  1742 I qtaguid : Tagging socket 341 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-29 16:40:31.403  1015  1742 I qtaguid : Untagging socket 341
08-29 16:40:31.403  1015  1742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 16:40:31.413  2001  6896 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
08-29 16:40:31.413  6932  6932 E Zygote  : MountEmulatedStorage()
08-29 16:40:31.413  6932  6932 I libpersona: KNOX_SDCARD checking this for 1000
08-29 16:40:31.413  6932  6932 E Zygote  : v2
,08-29 16:40:31.413  6932  6932 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:31.413  6932  6932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:31.423  6932  6932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:31.423  6932  6932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 16:40:31.423  6906  6918 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 16:40:31.423  6906  6918 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 16:40:31.423  6906  6918 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 16:40:31.423  6906  6918 I System.out: (HTTPLog)-Thread-1254-819039877: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 16:40:31.423  6906  6918 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:31.433  1015  1524 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 16:40:31.433  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:31.433  1015  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:31.433  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:31.453   278  1014 D CommandListener: Clearing all IP addresses on wlan0,
08-29 16:40:31.453   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:31.453  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 16:40:31.453   278  1010 D Netd    : getNetworkForDns: using netid 0 for uid 1000,
08-29 16:40:31.453  1015  1126 V NetworkStats: updateIfacesLocked()
08-29 16:40:31.453   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:31.453  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 16:40:31.453   278  1010 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-29 16:40:31.453  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 16:40:31.453  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:31.453  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:31.453  6932  6932 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:31.463  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 16:40:31.463  6932  6932 D ActivityThread: Added TimaKeyStore provider
08-29 16:40:31.463  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-29 16:40:31.463  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-29 16:40:31.463  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:31.463  1015  1126 V NetworkStats: performPollLocked() took 11ms
08-29 16:40:31.463  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:31.463  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.463  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.463  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.463  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.463  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.473  1174  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 16:40:31.473  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-29 16:40:31.473  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 16:40:31.473  1015  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 16:40:31.473  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 16:40:31.473   291   291 E SMD     : DCD OFF
,08-29 16:40:31.473  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:31.473  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.473  1015  1124 D SecContentProvider2: mCursor = null
08-29 16:40:31.473  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.473  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 16:40:31.473  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:31.473  1015  1124 D SecContentProvider2: mCursor = null
,08-29 16:40:31.483  2001  6896 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
08-29 16:40:31.483  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 16:40:31.483  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 16:40:31.483  1469  1469 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 16:40:31.493  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 16:40:31.493  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-29 16:40:31.493  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-29 16:40:31.493  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 16:40:31.503  6932  6932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 16:40:31.503  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 16:40:31.503  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 16:40:31.503  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:40:31.513  1015  1121 V NetworkStats: updateIfacesLocked()
08-29 16:40:31.513  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.513  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 16:40:31.513  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:31.513  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 16:40:31.513  1015  1121 V NetworkStats: performPollLocked() took 4ms
08-29 16:40:31.513  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.513  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 16:40:31.513  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-29 16:40:31.523  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 16:40:31.523  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-29 16:40:31.523  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 16:40:31.523  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 16:40:31.523  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-29 16:40:31.523  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 16:40:31.523  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 16:40:31.523  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.523  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.523  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.533  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 16:40:31.533  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:31.533  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:31.543  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:31.543  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:31.553  6826  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:40:31.553  6826  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f added. We now have 3 listener(s)
08-29 16:40:31.563  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 16:40:31.563  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:40:31.563  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:40:31.563  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:40:31.563  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c added. We now have 3 listener(s)
08-29 16:40:31.563  6826  6879 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:40:31.563  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:40:31.563  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:31.573  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:31.583  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:31.583  6826  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:31.583  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:40:31.583  6826  6879 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 16:40:31.583  6826  6879 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 16:40:31.583  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:40:31.583  6826  6879 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:31.583  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:31.583  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:31.583  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:31.583  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.583  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:31.583  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f removed from the list
08-29 16:40:31.583  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.583  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c removed from the list
08-29 16:40:31.583  6826  6879 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:31.583  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.583  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.593  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:31.593  6932  6932 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.593  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:31.593  6826  6879 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 16:40:31.593  6826  6879 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:31.593  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:31.593  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:31.593  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.593  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.593  6826  6879 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f not in the list
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.593  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:31.593  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:31.593  6826  6879 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:31.593  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.593  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.593  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.593  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:31.593  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.593  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:31.593  6932  6932 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
08-29 16:40:31.603  6932  6932 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 16:40:31.613  6826  6879 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:40:31.613  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:40:31.613  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:40:31.613  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:31.613  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.613  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.613  6826  6879 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f not in the list
08-29 16:40:31.613  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.613  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:31.613  6826  6879 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:31.613  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:31.613  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.613  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 16:40:31.613  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:31.613  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:40:31.613  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:31.613  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:31.613  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:31.623  6826  6879 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-29 16:40:31.623  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:31.633  6932  6932 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
08-29 16:40:31.633  6932  6932 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
08-29 16:40:31.633  6932  6932 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:31.653  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:40:31.653  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 16:40:31.653  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:40:31.653  6826  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:31.653  6826  6879 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 16:40:31.653  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 16:40:31.653  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:40:31.653  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 16:40:31.653  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 16:40:31.653  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:31.653  6953  6953 I dex2oat : ----------------------------------------------------
08-29 16:40:31.653  6953  6953 I dex2oat : <SS>: S T A R T I N G . . .
08-29 16:40:31.653  6953  6953 I dex2oat : <SS>: Zip is absent. Canceled.
08-29 16:40:31.653  6953  6953 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-29 16:40:31.653  6932  6932 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 16:40:31.663  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 16:40:31.663  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 16:40:31.663  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:40:31.663  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 16:40:31.663  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 16:40:31.663  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:40:31.663  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-29 16:40:31.663  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:31.663  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:40:31.663  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 16:40:31.673  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 16:40:31.673  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:40:31.683  6826  6957 D BluetoothSocket: bindListen(): myUserId = 0
08-29 16:40:31.683  6826  6957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:40:31.683  6826  6957 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,08-29 16:40:31.683  6826  6957 D BluetoothSocket: bindListen(), new LocalSocket 
,08-29 16:40:31.683  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 16:40:31.683  6826  6957 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-29 16:40:31.693  6826  6957 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@207cc988
08-29 16:40:31.693  6826  6957 D BluetoothSocket: channel: 6
08-29 16:40:31.693  6826  6957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 16:40:31.693  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.693  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:40:31.693  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.693  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.693  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.693  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-29 16:40:31.693  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 16:40:31.693  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 16:40:31.693  6932  6932 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 16:40:31.703  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.703  6932  6955 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 16:40:31.703  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 16:40:31.703  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 16:40:31.703  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 76 27
,08-29 16:40:31.703  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:31.703  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:31.703  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 16:40:31.703  1015  1027 I ActivityManager: Killing 6410:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-29 16:40:31.703  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.713  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.713  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.713  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.713  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.713  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.713  3156  3165 D BtGatt.GattService: registerClient() - UUID=47fbf3cb-b06b-468f-a1d8-961979f600e5
,08-29 16:40:31.723  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:31.723  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:31.723  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-29 16:40:31.723  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-29 16:40:31.723  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.723  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.723  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:31.723  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:31.723  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.733  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.733  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.733  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 16:40:31.733  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.733  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 16:40:31.733  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.733  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 16:40:31.743  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 16:40:31.743  6953  6953 I dex2oat : dex2oat took 83.754ms (threads: 4)
08-29 16:40:31.743  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 16:40:31.743  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.743  6971  6971 E Zygote  : MountEmulatedStorage()
08-29 16:40:31.743  6971  6971 I libpersona: KNOX_SDCARD checking this for 10102
08-29 16:40:31.743  6971  6971 E Zygote  : v2
08-29 16:40:31.743  6971  6971 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:31.743  6971  6971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:31.743  1015  1495 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6971 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 16:40:31.743  6971  6971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 16:40:31.743  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 16:40:31.743  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 16:40:31.753  6971  6971 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 16:40:31.753  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 16:40:31.753  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 16:40:31.753  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 16:40:31.753  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 16:40:31.753  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 16:40:31.753  6906  6918 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 16:40:31.753  6906  6918 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 16:40:31.753  6906  6918 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 16:40:31.753  6906  6918 I Adreno-EGL: Local Branch: 
08-29 16:40:31.753  6906  6918 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 16:40:31.753  6906  6918 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 16:40:31.753  6906  6918 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 16:40:31.783  3156  3254 D BtGatt.GattService: onClientRegistered() - UUID=47fbf3cb-b06b-468f-a1d8-961979f600e5, clientIf=6
,08-29 16:40:31.783  6971  6971 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 16:40:31.783  6971  6971 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:31.783  6826  6837 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,08-29 16:40:31.793  3156  3256 D BtGatt.AdvertiseManager: message : 0
,08-29 16:40:31.793  3156  3256 D BtGatt.AdvertiseManager: number of adv instance running0
08-29 16:40:31.793  3156  3256 D BtGatt.AdvertiseManager: size of list is =0
,08-29 16:40:31.793  3156  3256 D BtGatt.AdvertiseManager: starting advertising
,08-29 16:40:31.793  3156  3256 D BtGatt.AdvertiseManager: isStandardAdvfalse
,08-29 16:40:31.803  3156  3254 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,08-29 16:40:31.803  3156  3256 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 16:40:31.803  3156  3254 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
08-29 16:40:31.803  3156  3256 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
08-29 16:40:31.803  3156  3256 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,08-29 16:40:31.803  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
08-29 16:40:31.803  6971  6971 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 16:40:31.813  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:40:31.813  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:40:31.813  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:40:31.813  6826  6879 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:40:31.823  6826  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 16:40:31.823  6826  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 16:40:31.823  6826  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 16:40:31.823  6826  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 16:40:31.823  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 16:40:31.823  6826  6826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:31.823  6826  6826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:31.863   283   283 I WVCdm   : CdmEngine::OpenSession
,08-29 16:40:31.993  6971  7000 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 16:40:31.993  6971  7000 I Babel_SMS: MmsConfig.loadMmsSettings
08-29 16:40:31.993  6971  7000 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 16:40:31.993  6971  7000 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 16:40:32.003  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:32.013  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-29 16:40:32.013  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:32.033  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:40:32.043  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:40:32.043  6971  7000 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 16:40:32.043  6971  7000 I Babel_SMS: MmsConfig.loadFromResources
,08-29 16:40:32.043  6971  7000 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:40:32.043  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:32.053  6971  7000 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 16:40:32.093  1015  1134 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 16:40:32.103  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 16:40:32.103  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.103  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:32.103  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 16:40:32.123  6971  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:40:32.123  6971  6971 I Babel_Crash: startup - clean
,08-29 16:40:32.153  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 16:40:32.153  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 16:40:32.153  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.153  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 16:40:32.153  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 16:40:32.153  1617  1617 I Hs20UtilService: Starting #9
,08-29 16:40:32.163  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:32.163  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 16:40:32.163  6932  6932 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 16:40:32.163  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 16:40:32.163  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-29 16:40:32.163  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 16:40:32.163  6932  6932 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 16:40:32.163  6932  6955 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 16:40:32.173  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.173  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:32.173  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:32.173  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:32.183  6971  6971 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 16:40:32.183  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.183  1015  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.183  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.193  6971  6971 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 16:40:32.193  6971  6971 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 16:40:32.193  6971  6971 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 16:40:32.213  6971  6971 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 16:40:32.213  6971  6971 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 16:40:32.223  6971  6971 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 16:40:32.223  6971  6971 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 16:40:32.243  6971  6971 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 16:40:32.243  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 16:40:32.253  6971  6971 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 16:40:32.253  6971  6971 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 16:40:32.253  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 16:40:32.263  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 16:40:32.263  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 16:40:32.273  6971  6971 W VideoCapabilities: Unsupported mime video/mp43
,08-29 16:40:32.273  6971  6971 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 16:40:32.283  6971  6971 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 16:40:32.303  6971  6971 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 16:40:32.323  6826  6826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
08-29 16:40:32.323  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 16:40:32.323  6826  6826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:32.333  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:32.333  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:32.343  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:32.343  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:40:32.353  1015  3997 I ActivityManager: Killing 6545:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-29 16:40:32.353  6971  6971 I vclib   : onServiceConnected
,08-29 16:40:32.363  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.363  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.363  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.373  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.373  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.373  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.373  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.383  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.383  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.383  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.383  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.383  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.393  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.393  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.393  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.393  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.403  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.403  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.403  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:32.403  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 16:40:32.403  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 16:40:32.403  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.403  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.403  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.403  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.433  7004  7004 E Zygote  : MountEmulatedStorage(),
08-29 16:40:32.433  7004  7004 E Zygote  : v2
08-29 16:40:32.433  7004  7004 I libpersona: KNOX_SDCARD checking this for 1000
08-29 16:40:32.433  7004  7004 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.433  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 16:40:32.433  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 16:40:32.443  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 16:40:32.443  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.453   309   309 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 22.500ms
,08-29 16:40:32.453  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 16:40:32.453  7004  7004 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.473   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.495ms
08-29 16:40:32.473  1366  1366 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
08-29 16:40:32.473  1366  1366 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 16:40:32.483  1366  1366 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 16:40:32.483  1366  1366 I wpa_supplicant: Trying to associate with  'G700'
,08-29 16:40:32.483  1366  1366 I wpa_supplicant: Re-associate with F4.99.3E
08-29 16:40:32.483  1366  1366 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-29 16:40:32.483  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-29 16:40:32.483  1015  1533 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 16:40:32.483   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.490ms
,08-29 16:40:32.493  7004  7004 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
08-29 16:40:32.493  7004  7004 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 16:40:32.493  7004  7004 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 16:40:32.493  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:32.493  1015  1124 D SecContentProvider2: mCursor = null
,08-29 16:40:32.503  7004  7004 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 16:40:32.503  7004  7004 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-29 16:40:32.503  7004  7004 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 16:40:32.503  7004  7004 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:32.503  1015  1216 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-29 16:40:32.503  7004  7019 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 16:40:32.503  1015  1216 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 16:40:32.513  1015  1041 I ActivityManager: Killing 6596:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 16:40:32.513  1768  1768 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:32.523  1015  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 16:40:32.523  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.523  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.523  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.523  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.543  7021  7021 E Zygote  : MountEmulatedStorage()
,08-29 16:40:32.543  7021  7021 E Zygote  : v2
08-29 16:40:32.543  7021  7021 I libpersona: KNOX_SDCARD checking this for 10031
08-29 16:40:32.543  7021  7021 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.543  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 16:40:32.543  1015  1489 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7021 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 16:40:32.543  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:32.543  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.543  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
08-29 16:40:32.553  2449  2459 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
08-29 16:40:32.553  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.553  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.553  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.553  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.563  7031  7031 E Zygote  : MountEmulatedStorage()
,08-29 16:40:32.563  7031  7031 I libpersona: KNOX_SDCARD checking this for 10121
08-29 16:40:32.563  7031  7031 E Zygote  : v2
08-29 16:40:32.563  7031  7031 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:32.563  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:32.563  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7031 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 16:40:32.563  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 16:40:32.573  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 16:40:32.573  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 16:40:32.573  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 16:40:32.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.573  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.573  7021  7021 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.583  7044  7044 E Zygote  : MountEmulatedStorage()
,08-29 16:40:32.583  7044  7044 I libpersona: KNOX_SDCARD checking this for 10001
08-29 16:40:32.583  7044  7044 E Zygote  : v2
08-29 16:40:32.583  7044  7044 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:32.583  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:32.593  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:32.593  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7044 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 16:40:32.593  1768  1768 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-29 16:40:32.593  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.593  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 16:40:32.593  1366  1366 E wpa_supplicant: Cmd 35605 not handled
,08-29 16:40:32.593  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 16:40:32.593  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 16:40:32.593  1366  1366 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 16:40:32.593  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 16:40:32.593  1366  1366 I wpa_supplicant: Associated with F4.99.3E,
08-29 16:40:32.593  1366  1366 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 16:40:32.593  1366  1366 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 16:40:32.593  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 16:40:32.603  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 16:40:32.603  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 16:40:32.603  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 16:40:32.603  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 16:40:32.603  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 16:40:32.603  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 16:40:32.603  1015  1129 E Tethering: No numeric data
08-29 16:40:32.603  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 16:40:32.603  1015  1129 D Tethering: clearTetheredNotification()
,08-29 16:40:32.603  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:32.603  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 16:40:32.613  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:32.613  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:32.613  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:32.613  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 16:40:32.613  1015  1124 D SecContentProvider2: mCursor = null
08-29 16:40:32.613  1174  1174 D HotspotTile: updateTetherState():false, false
,08-29 16:40:32.613  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:32.613  1015  1121 V NetworkStats: performPollLocked() took 3ms
,08-29 16:40:32.613  1768  1768 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 16:40:32.613  1768  1768 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 16:40:32.613  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:32.613  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:32.613  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:32.623  1366  1366 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 16:40:32.623  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:32.623  1015  1124 D SecContentProvider2: mCursor = null
08-29 16:40:32.623  1366  1366 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 16:40:32.623  1366  1366 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 16:40:32.623  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-29 16:40:32.623  1366  1366 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 16:40:32.623  1366  1366 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 16:40:32.623  1366  1366 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-29 16:40:32.623  1366  1366 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 16:40:32.623  1366  1366 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 16:40:32.623  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 16:40:32.623  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 16:40:32.623  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 16:40:32.623  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-29 16:40:32.623  7044  7044 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.633  1768  1768 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:32.633  1768  1768 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-29 16:40:32.633  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 16:40:32.633  7031  7031 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.633  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 16:40:32.633  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 16:40:32.643  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.643  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.643  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.643  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.653  7066  7066 E Zygote  : MountEmulatedStorage(),
,08-29 16:40:32.653  7066  7066 E Zygote  : v2
08-29 16:40:32.653  7066  7066 I libpersona: KNOX_SDCARD checking this for 10077
08-29 16:40:32.653  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:32.653  7066  7066 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:32.653  1015  1487 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7066 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 16:40:32.663  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:32.663  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.663  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 16:40:32.673  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 16:40:32.673  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 16:40:32.673  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 16:40:32.673  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 16:40:32.673  7021  7021 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
08-29 16:40:32.673  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:32.673  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:32.673  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:32.673  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:32.673  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:32.673  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:32.673  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:32.683  1015  1028 I ActivityManager: Killing 6569:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 16:40:32.683  7031  7031 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 16:40:32.683  7031  7031 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 16:40:32.683  7031  7031 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 16:40:32.693  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:40:32.693  1015  3998 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 16:40:32.703  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.703  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.703  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.703  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.703  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 16:40:32.703  7066  7066 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.703  2800  7082 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 16:40:32.703  2800  7082 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 16:40:32.713  2800  7082 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-29 16:40:32.713  7031  7031 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:32.713  2800  7082 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-29 16:40:32.713  2800  7082 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 16:40:32.713  7083  7083 E Zygote  : MountEmulatedStorage(),
08-29 16:40:32.723  7083  7083 E Zygote  : v2
08-29 16:40:32.723  7083  7083 I libpersona: KNOX_SDCARD checking this for 10032
08-29 16:40:32.723  7083  7083 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.723  7083  7083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 16:40:32.723  1015  3998 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7083 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 16:40:32.723  7083  7083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:32.723  7083  7083 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.743   278  1014 D CommandListener: Setting iface cfg
,08-29 16:40:32.743  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 16:40:32.743  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-29 16:40:32.743  1015  1124 D SecContentProvider2: mCursor = null
,08-29 16:40:32.753  1015  1124 E WifiNative-wlan0: do suspend false
,08-29 16:40:32.763  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 16:40:32.763  1015  1124 D SecContentProvider2: mCursor = null
,08-29 16:40:32.763  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 16:40:32.763  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 16:40:32.763  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:32.763  7083  7083 D ActivityThread: Added TimaKeyStore provider
08-29 16:40:32.763  1015  3363 D SSRM:n  : SIOP:: AP = 400
08-29 16:40:32.763  7031  7031 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 16:40:32.773  7031  7031 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 16:40:32.773  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-29 16:40:32.773  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.773  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.773  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.773  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.793  7100  7100 E Zygote  : MountEmulatedStorage()
,08-29 16:40:32.793  7100  7100 E Zygote  : v2
08-29 16:40:32.793  7100  7100 I libpersona: KNOX_SDCARD checking this for 10141
08-29 16:40:32.793  7100  7100 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.803  7100  7100 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 16:40:32.803  1015  1028 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7100 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-29 16:40:32.803  1015  1028 I ActivityManager: Killing 6606:com.samsung.android.securitylogagent/1000 (adj 15): empty #21,
,08-29 16:40:32.813  7100  7100 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:32.813  7100  7100 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:32.823  1015  3998 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 16:40:32.823  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.823  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.823  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.823  1015  3998 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.833  7100  7100 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:32.843  7100  7100 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.843  7083  7114 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 16:40:32.843  7083  7114 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 16:40:32.843  7116  7116 E Zygote  : MountEmulatedStorage()
,08-29 16:40:32.843  7116  7116 E Zygote  : v2
08-29 16:40:32.843  7116  7116 I libpersona: KNOX_SDCARD checking this for 1000
08-29 16:40:32.843  7116  7116 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.843  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:32.853  1015  3998 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 16:40:32.853  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:32.853  1015  3998 I ActivityManager: Killing 6645:com.osp.app.signin/u0a36 (adj 15): empty #21
08-29 16:40:32.853  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 16:40:32.853  7083  7114 D SPPClientService: PushLog.txt file is not deleted.
08-29 16:40:32.853  7083  7114 D SPPClientService: PushLog.txt file is not deleted.
08-29 16:40:32.853  7083  7114 D SPPClientService: ============PushLog. stop!
,08-29 16:40:32.863  7083  7083 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 16:40:32.873  1015  1497 I ActivityManager: Killing 6661:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 16:40:32.873  1015  1497 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 16:40:32.873  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:32.873  7116  7116 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.883  7100  7100 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-29 16:40:32.883  7100  7100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 16:40:32.883  7100  7100 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 16:40:32.883  7100  7100 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 16:40:32.903  1015  1497 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.osp.app.signin/com.osp.app.signin.OspReceiver}
08-29 16:40:32.903  1015  1497 W BroadcastQueue: android.os.TransactionTooLargeException
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 16:40:32.903  1015  1497 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 16:40:32.903  1015  1497 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 16:40:32.903  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.903  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:32.903  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.903  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:32.923  1015  1497 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7132 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 16:40:32.933  7132  7132 E Zygote  : MountEmulatedStorage()
08-29 16:40:32.933  7132  7132 E Zygote  : v2
08-29 16:40:32.933  7132  7132 I libpersona: KNOX_SDCARD checking this for 10036
08-29 16:40:32.933  7132  7132 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:32.933  7132  7132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:32.933  7132  7132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:32.933  7132  7132 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 16:40:32.933  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:32.943  1015  3997 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-29 16:40:32.943  1015  3997 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 16:40:32.943  1015  3997 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:32.943  1015  3997 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 16:40:32.943  1015  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 16:40:32.963  1015  1040 W libprocessgroup: failed to open /acct/uid_10036/pid_6645/cgroup.procs: No such file or directory
,08-29 16:40:32.963  1015  1496 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:32.973  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:32.973  7132  7132 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:32.983  7149  7149 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 16:40:32.993  7149  7149 I dhcpcd  : version 5.5.6 starting
,08-29 16:40:32.993  7149  7149 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 16:40:33.033  7132  7132 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2c0d0fa4
,08-29 16:40:33.033  7116  7116 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 16:40:33.033  1015  2093 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:33.043  7083  7140 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 16:40:33.053  7132  7132 I SA      : [SSP] onCreated
,08-29 16:40:33.053  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:33.063  7149  7149 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 16:40:33.063  7149  7149 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 16:40:33.063  7149  7149 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-29 16:40:33.063  7149  7149 I dhcpcd  : bssid match
08-29 16:40:33.063  7149  7149 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 16:40:33.103  1015  1216 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 16:40:33.103  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.103  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.103  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.103  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:33.113  1015  1216 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7164 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 16:40:33.123  7149  7149 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-29 16:40:33.123  7164  7164 I libpersona: KNOX_SDCARD checking this for 10068
08-29 16:40:33.123  7164  7164 E Zygote  : MountEmulatedStorage()
08-29 16:40:33.123  7164  7164 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:33.123  7164  7164 E Zygote  : v2
08-29 16:40:33.123  7164  7164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:33.123  7164  7164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:33.133  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:33.133  7164  7164 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 16:40:33.143  1015  1487 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:33.153   283   691 I WVCdm   : CdmEngine::CloseSession
,08-29 16:40:33.153  7164  7164 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:33.153  7164  7164 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:33.173  7149  7149 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-29 16:40:33.173   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-29 16:40:33.173  7132  7132 I SA      : [TPM] There is no property file
,08-29 16:40:33.183  7132  7132 I SA      : [SCU] isHaveSA() - false
,08-29 16:40:33.183   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-29 16:40:33.183   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-29 16:40:33.183   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
08-29 16:40:33.183  7132  7132 I SA      : [TPM] getModelProperty : null
08-29 16:40:33.183  7132  7132 I SA      : [TPM] getCSCProperty : null
,08-29 16:40:33.183  7132  7132 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 16:40:33.183   283   283 D WVCdm   : PrepareKeyRequest: nonce=2872932369
,08-29 16:40:33.193  7132  7132 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 16:40:33.193  7132  7132 I SA      : [DM] TFT FEATURE: false
,08-29 16:40:33.193  7132  7132 I SA      : [DM] init START
,08-29 16:40:33.203  7164  7164 D BadgeProvider: onCreate
,08-29 16:40:33.203  7164  7164 D BadgeProvider: DatabaseHelper
,08-29 16:40:33.203  7132  7132 I SA      : [DM] This device is not a Vodafone
,08-29 16:40:33.223  7164  7174 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 16:40:33.233  1015  1489 D RCPManagerService: exchangeData() failure , invalid userId,
,08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75),
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75),
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75),
,08-29 16:40:33.243  7132  7132 W ResourceType: No package identifier when getting value for resource number 0x00000000,
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-29 16:40:33.243  7132  7132 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75),
,08-29 16:40:33.273  7116  7116 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,08-29 16:40:33.283  7116  7116 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-29 16:40:33.293  7116  7116 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:33.293  7116  7116 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 16:40:33.293  7116  7116 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 16:40:33.293  7116  7116 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 16:40:33.293  7164  7174 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 16:40:33.293  7164  7174 D BadgeProvider: sendNotify, [notify] : null
,08-29 16:40:33.293  7164  7174 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 16:40:33.293  7164  7174 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 16:40:33.293  7164  7174 D BadgeProvider: update, [UpdateCount] : 1
,08-29 16:40:33.293  7132  7132 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-29 16:40:33.293  7132  7132 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 16:40:33.293  7132  7132 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-29 16:40:33.293  7132  7132 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-29 16:40:33.293  7132  7132 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-29 16:40:33.303  7132  7132 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-29 16:40:33.303  1015  1524 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 16:40:33.303  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 16:40:33.303  1498  1498 D Launcher.Model: reloadBadges entered.
,08-29 16:40:33.313  7132  7132 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 16:40:33.313  1015  1496 D RCPManagerService: exchangeData() failure , invalid userId
08-29 16:40:33.313  7132  7132 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 16:40:33.313  7132  7132 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-29 16:40:33.313  7132  7132 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-29 16:40:33.313  7132  7132 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 16:40:33.313  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:33.313  1015  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:33.313  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 16:40:33.313  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 16:40:33.323  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.323  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.323  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.323  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:33.333  7132  7132 I SA      : [SCU] isHaveSA() - false,
08-29 16:40:33.333  7132  7132 I SA      : support phone number id : false
08-29 16:40:33.333  7132  7132 I SA      : [DM] Supports Ref Jpn : true
08-29 16:40:33.333  7132  7132 I SA      : [DM] init END
08-29 16:40:33.333  7132  7132 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 16:40:33.333  7132  7132 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 16:40:33.333  7132  7132 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 16:40:33.333  7205  7205 E Zygote  : MountEmulatedStorage(),
08-29 16:40:33.333  1015  1028 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7205 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 16:40:33.333  7205  7205 E Zygote  : v2
08-29 16:40:33.333  7205  7205 I libpersona: KNOX_SDCARD checking this for 10008
08-29 16:40:33.333  7205  7205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 16:40:33.333  7205  7205 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:33.333  1015  1028 I ActivityManager: Killing 6677:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-29 16:40:33.343  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:33.343  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:33.343  1015  1487 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 16:40:33.343  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
08-29 16:40:33.343  1015  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-29 16:40:33.343  7205  7205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:33.343  7205  7205 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-29 16:40:33.343  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-29 16:40:33.353  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.353  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.353  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.353  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:33.353  7132  7132 I SA      : [SLFUCHKMGR] constructor called
,08-29 16:40:33.363  6971  7203 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 16:40:33.373  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 16:40:33.373  7222  7222 E Zygote  : MountEmulatedStorage(),
08-29 16:40:33.373  7222  7222 E Zygote  : v2
08-29 16:40:33.383  7222  7222 I libpersona: KNOX_SDCARD checking this for 10009
08-29 16:40:33.383  7222  7222 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:33.383  1015  1028 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7222 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 16:40:33.383  7222  7222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:33.383  7222  7222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 16:40:33.383  7222  7222 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 16:40:33.383  7205  7205 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:33.383  7205  7205 D ActivityThread: Added TimaKeyStore provider
08-29 16:40:33.393  1015  1028 I ActivityManager: Killing 6693:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-29 16:40:33.403  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 16:40:33.403  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 16:40:33.403  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 16:40:33.403  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.403  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.403  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:33.403  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:33.403   309   309 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 911us total 30.769ms
08-29 16:40:33.413  7222  7222 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:33.413  7222  7222 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:33.413  7132  7132 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 16:40:33.413  7132  7132 I SA      : [OR] == isSIMCardReady false ==
,08-29 16:40:33.423  7132  7132 I SA      : [SCU] == networkStateCheck == false,
08-29 16:40:33.423  7132  7132 I SA      : [OR] onReceive END
,08-29 16:40:33.433   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.746ms
,08-29 16:40:33.463   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 23.046ms
,08-29 16:40:33.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:40:33.493  7240  7240 E Zygote  : MountEmulatedStorage()
08-29 16:40:33.493  7240  7240 I libpersona: KNOX_SDCARD checking this for 10110
08-29 16:40:33.493  7240  7240 E Zygote  : v2
08-29 16:40:33.493  7240  7240 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:33.493  7240  7240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:33.493  7240  7240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:33.493  7240  7240 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 16:40:33.503  1015  1028 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7240 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 16:40:33.503  1015  1028 I ActivityManager: Killing 6622:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-29 16:40:33.513  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:33.523  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 16:40:33.523  1015  1124 E WifiStateMachine: VerifyingLinkState enter
,08-29 16:40:33.523  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-29 16:40:33.523  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 16:40:33.523  7240  7240 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:33.533  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 16:40:33.533  7240  7240 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:33.533  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:33.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.533  1015  1126 D ConnectivityService: Adding iface wlan0 to network 503
,08-29 16:40:33.563  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,08-29 16:40:33.563  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,08-29 16:40:33.563  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,08-29 16:40:33.563  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 16:40:33.563  1015  1126 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,08-29 16:40:33.563  1015  1126 D ConnectivityService: LTETest block dns file not exists
,08-29 16:40:33.563  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-29 16:40:33.573  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 16:40:33.573  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 16:40:33.573  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 16:40:33.573  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 16:40:33.573  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 16:40:33.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.583  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.583  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 16:40:33.583  1015  1126 V NetworkStats: updateIfacesLocked()
,08-29 16:40:33.583  1015  1028 I ActivityManager: Killing 6123:com.android.mms/u0a41 (adj 15): empty #21
08-29 16:40:33.583  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 16:40:33.583  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.583  1015  1495 I art     : Explicit concurrent mark sweep GC freed 63321(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 3.200ms total 241.189ms
,08-29 16:40:33.593  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 16:40:33.593  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:33.593  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 16:40:33.603  1015  1126 V NetworkStats: performPollLocked() took 22ms
,08-29 16:40:33.603  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.613  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 16:40:33.613  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 16:40:33.613  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 16:40:33.633  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 16:40:33.633  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 16:40:33.633  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-29 16:40:33.633  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:33.633  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 16:40:33.633  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.633  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.633  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.633  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.643  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:33.643  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 16:40:33.643  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.643  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.643  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-29 16:40:33.643  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.643  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 16:40:33.643  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.643  1015  1126 V NetworkStats: updateIfacesLocked()
08-29 16:40:33.643  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 16:40:33.643  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 16:40:33.643  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 16:40:33.643  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.643  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:33.643  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:33.643  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.643  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.653  1015  1126 V NetworkStats: performPollLocked() took 7ms
08-29 16:40:33.653  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.653  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.653  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.653  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-29 16:40:33.653  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,08-29 16:40:33.653  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 16:40:33.653  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 16:40:33.653  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 16:40:33.653  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-29 16:40:33.653  1015  7073 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:33.663   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:33.663   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,08-29 16:40:33.663  1015  1126 D ConnectivityService:    accepting network in place of null
,08-29 16:40:33.663  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 16:40:33.663  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-29 16:40:33.663  1469  1469 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 16:40:33.663  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-29 16:40:33.663  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 16:40:33.663  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-29 16:40:33.663  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 16:40:33.673  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-29 16:40:33.673  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 16:40:33.673  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:40:33.673  1015  1121 V NetworkStats: updateIfacesLocked()
08-29 16:40:33.673  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.673  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 16:40:33.673  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 16:40:33.673  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:33.673  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-29 16:40:33.673  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-29 16:40:33.673  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 16:40:33.673  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 16:40:33.673  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-29 16:40:33.673  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 16:40:33.673  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 16:40:33.683  1015  3998 I ActivityManager: Killing 6720:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-29 16:40:33.683  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:33.683  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.683  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.683  1174  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 16:40:33.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.683  1015  1121 V NetworkStats: performPollLocked() took 11ms
08-29 16:40:33.683  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.683  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 16:40:33.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.683  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.683  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 16:40:33.683  1015  1497 I ActivityManager: Killing 6737:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-29 16:40:33.693  1015  1134 D CountryDetector: No listener is left
,08-29 16:40:33.693  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:33.693  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:33.693  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 16:40:33 GMT+02:00 2016
,08-29 16:40:33.693  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 16:40:33.693  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 16:40:33.703  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:33.703  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:33.703  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 16:40:33.703  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 16:40:33.713  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 16:40:33.713  2933  2933 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 16:40:33.713  2933  2933 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 16:40:33.723  2933  7262 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 16:40:33.723  2933  7262 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 16:40:33.723  2933  7262 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-29 16:40:33.723  2933  7262 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-29 16:40:33.733  2933  7262 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-29 16:40:33.733  1015  7073 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 16:40:33.743  2933  7262 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-29 16:40:33.743  2933  7262 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 16:40:33.743  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 16:40:33.793  7222  7222 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-29 16:40:33.803  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:40:33 GMT], X-Android-Received-Millis=[1472481633818], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472481633782]}
08-29 16:40:33.803  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 16:40:33.803  1015  7073 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 16:40:33.803  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-29 16:40:33.803  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-29 16:40:33.803  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-29 16:40:33.803  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-29 16:40:33.803  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 16:40:33.813  1174  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 16:40:33.813  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 16:40:33.813  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 16:40:33.813  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 16:40:33.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 16:40:33.813  1015  1134 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 16:40:33.843  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-29 16:40:33.843  1015  1524 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 16:40:33.843  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 16:40:33.843  1015  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 16:40:33.953   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 16:40:33.953   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:33.953  7240  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 16:40:33.953   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 16:40:33.953   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:33.953  7240  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 16:40:33.973   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 16:40:33.973   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:33.973  7240  7271 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 16:40:33.973   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 16:40:33.973   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:33.973  7240  7271 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 16:40:34.003  7240  7240 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 16:40:34.003  7240  7240 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 16:40:34.003  7240  7240 I GAv4    :   adb logcat -s GAv4
,08-29 16:40:34.023  7240  7240 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:34.023  1015  1216 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 16:40:34.033  7240  7240 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:34.043  1015  1028 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-29 16:40:34.043  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
08-29 16:40:34.043  7240  7273 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:40:34.043  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:34.043  1015  1028 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 16:40:34.043  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 16:40:34.053  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 16:40:34.053  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 16:40:34.053  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:34.053  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:34.053  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:34.063  7222  7222 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 16:40:34.063  7222  7222 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: exit::IDLE
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-29 16:40:34.063  7222  7222 D InitializeManagerStateMachine: entry::SUCCESS
08-29 16:40:34.063  7222  7222 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-29 16:40:34.073  7222  7222 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 16:40:34.073  7222  7222 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-29 16:40:34.073  7222  7222 D InitializeManagerStateMachine: exit::SUCCESS
08-29 16:40:34.073  7222  7222 D InitializeManagerStateMachine: entry::IDLE
,08-29 16:40:34.083  4732  7275 I iu.SyncManager: SYNC; picasa accounts
,08-29 16:40:34.103  4732  4732 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 16:40:34.103  4732  4732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:40:34.113  1015  1489 I ActivityManager: Killing 6559:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 16:40:34.123  4732  7275 I iu.UploadsManager: num queued entries: 0
,08-29 16:40:34.123  4732  7275 I iu.UploadsManager: num updated entries: 0
,08-29 16:40:34.123  4732  7275 I iu.SyncManager: NEXT; no task
,08-29 16:40:34.173  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:34.193  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:34.203  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:34.203  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:34.203  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:34.213  6826  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:34.213  6826  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:34.223  1015  1524 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-29 16:40:34.223  1015  1524 D SecContentProvider2: mCursor = null
,08-29 16:40:34.243  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:34.303  1015  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:34.303  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:34.303  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:34.303  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 16:40:34.323  7240  7240 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500),
,08-29 16:40:34.353  7240  7240 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 4902-4909)
08-29 16:40:34.353  7240  7240 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 16:40:34.373  7240  7240 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30d18e85}
,08-29 16:40:34.373  7240  7240 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 16:40:34.373  7240  7240 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 16:40:34.393  7240  7240 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 16:40:34.393  7240  7240 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 16:40:34.393  7240  7240 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 16:40:34.413  7240  7240 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 16:40:34.413  7240  7240 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 16:40:34.413  7240  7240 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 16:40:34.413  7240  7240 I Adreno-EGL: Local Branch: 
08-29 16:40:34.413  7240  7240 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 16:40:34.413  7240  7240 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 16:40:34.413  7240  7240 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 16:40:34.463   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:34.473  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 16:40:34.473  1015  1126 V NetworkStats: updateIfacesLocked()
08-29 16:40:34.473  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:34.473  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 16:40:34.473  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 16:40:34.473  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 16:40:34.473   291   291 E SMD     : DCD OFF,
08-29 16:40:34.473  1015  1126 V NetworkStats: performPollLocked() took 3ms
08-29 16:40:34.473  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:34.473  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-29 16:40:34.483  1174  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 16:40:34.483  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-29 16:40:34.483  1174  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 16:40:34.493  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 16:40:34.493  7240  7240 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 16:40:34.503  4732  6887 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 16:40:34.503  7240  7240 I NSApplication: Starting up...
,08-29 16:40:34.503  1015  1495 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-29 16:40:34.503  7240  7302 W cr.media: Requires BLUETOOTH permission
,08-29 16:40:34.503  1015  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 16:40:34.513  1015  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 16:40:34.513  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:34.513  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:34.513  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:34.513  1015  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:34.523  1015  1487 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7307 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 16:40:34.523  7307  7307 E Zygote  : MountEmulatedStorage()
08-29 16:40:34.523  7307  7307 I libpersona: KNOX_SDCARD checking this for 10117
08-29 16:40:34.523  7307  7307 E Zygote  : v2
08-29 16:40:34.523  7307  7307 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:34.533  7307  7307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:34.533  1015  1487 I ActivityManager: Killing 6752:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-29 16:40:34.533  7307  7307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:34.533  7307  7307 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 16:40:34.533  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 16:40:34.533  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 16:40:34.553  7307  7307 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:34.563  7307  7307 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:34.573  7307  7307 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 16:40:34.673  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 16:40:34.803   283   678 I WVCdm   : CdmEngine::CloseSession
,08-29 16:40:34.803   283   678 I WVCdm   : L3 Terminate.
,08-29 16:40:34.843  2001  6905 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:34.853   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:34.853   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 10011
,08-29 16:40:34.893  2001  6905 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 16:40:34.893  2001  6905 I qtaguid : Tagging socket 47 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:34.923  2001  6905 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:34.933  1015  1497 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 16:40:34.933  1015  1497 I ActivityManager: Killing 6056:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-29 16:40:34.943  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 16:40:34.943  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 16:40:34.943  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:34.943  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:34.943  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 16:40:34.943  1617  1617 I Hs20UtilService: Starting #10
,08-29 16:40:34.943  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:34.943  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 16:40:34.943  6932  6932 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 16:40:34.943  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-29 16:40:34.953  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-29 16:40:34.953  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 16:40:34.953  6932  6932 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 16:40:34.963  1015  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 16:40:34.963  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 16:40:34.963  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:34.963  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:34.963  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 16:40:34.963  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 16:40:34.963  1617  1617 I Hs20UtilService: Starting #11
,08-29 16:40:34.963  6932  6932 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 16:40:34.963  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:34.983  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 16:40:34.983  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 16:40:34.983  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:34.983  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:34.983  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 16:40:34.983  1617  1617 I Hs20UtilService: Starting #12
,08-29 16:40:34.983  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:34.983  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 16:40:34.983  6932  6932 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 16:40:34.983  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-29 16:40:34.993  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-29 16:40:34.993  6932  6932 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 16:40:34.993  6932  6932 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 16:40:35.003  1015  2093 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 16:40:35.003  1015  2093 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 16:40:35.003  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.003  1015  2093 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:35.003  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 16:40:35.003  1617  1617 I Hs20UtilService: Starting #13
,08-29 16:40:35.003  1617  1637 I Hs20UtilService: Message received 5007
,08-29 16:40:35.003  6932  6932 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 16:40:35.003  6932  6932 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 16:40:35.013  1015  1216 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 16:40:35.013  1015  1487 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-29 16:40:35.013  1015  1487 D SecContentProvider2: mCursor = null
,08-29 16:40:35.023  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-29 16:40:35.023  1015  1027 D SecContentProvider2: mCursor = null
,08-29 16:40:35.023  1015  1134 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 16:40:35.023  1015  1134 D SecContentProvider2: mCursor = null
,08-29 16:40:35.023  1015  3998 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-29 16:40:35.023  1015  3998 D SecContentProvider2: mCursor = null
,08-29 16:40:35.033  1015  1028 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-29 16:40:35.033  1015  1028 D SecContentProvider2: mCursor = null
,08-29 16:40:35.033  1015  1216 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-29 16:40:35.033  1015  1216 D SecContentProvider2: mCursor = null
,08-29 16:40:35.043  7004  7004 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 16:40:35.043  7004  7004 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 16:40:35.043  7004  7004 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 16:40:35.043  7004  7004 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:35.043  1015  2093 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 16:40:35.043  1015  2093 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 16:40:35.053  1768  1768 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:35.063   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-29 16:40:35.063  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-29 16:40:35.063  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.063  7031  7031 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-29 16:40:35.063  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:35.073  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:35.073  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-29 16:40:35.073  2001  6905 W GLSUser : [AppCertManager] IOException while requesting key: 
08-29 16:40:35.073  2001  6905 W GLSUser : java.io.IOException: Invalid device key response.
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dxt.a(:com.google.android.gms:267)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-29 16:40:35.073  2001  6905 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
,08-29 16:40:35.073  2449  2459 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-29 16:40:35.083  1015  1497 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-29 16:40:35.083  7116  7116 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:35.083  7116  7116 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 16:40:35.083  7116  7116 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-29 16:40:35.083  7116  7116 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-29 16:40:35.083  7031  7031 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 16:40:35.083  7031  7031 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 16:40:35.093  1768  1768 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 16:40:35.093  1768  1768 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 16:40:35.093  1768  1768 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 16:40:35.093  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:35.093  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 16:40:35.113  1768  1768 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 16:40:35.113  1768  1768 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 16:40:35.113  1015  1524 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:35.113  1015  3998 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 16:40:35.143  1015  2093 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-29 16:40:35.143  1015  2093 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.143  7083  7083 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-29 16:40:35.143  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.143  1015  2093 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 16:40:35.143  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 16:40:35.153  1015  1524 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 16:40:35.153  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
08-29 16:40:35.153  2800  7335 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-29 16:40:35.153  2800  7335 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-29 16:40:35.153  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.153  1015  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.153  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.153  2800  7335 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 16:40:35.153  1015  1484 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-29 16:40:35.153  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.153  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.153  1015  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.153  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-29 16:40:35.163  7222  7222 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 16:40:35.163  7132  7132 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 16:40:35.163  7132  7132 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-29 16:40:35.163  7132  7132 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 16:40:35.173  7222  7222 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: exit::IDLE
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-29 16:40:35.173  7222  7222 D InitializeManagerStateMachine: entry::SUCCESS
08-29 16:40:35.173  7222  7222 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-29 16:40:35.173  7132  7132 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 16:40:35.173  7132  7132 I SA      : [OR] == isSIMCardReady false ==
,08-29 16:40:35.183  7132  7132 I SA      : [SCU] == networkStateCheck == true
,08-29 16:40:35.183  7132  7132 I SA      : [DM] getCountryCodeFromCSC : PL
08-29 16:40:35.183  7132  7132 I SA      : isChinaCountryCode : false
08-29 16:40:35.183  7132  7132 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-29 16:40:35.183  7132  7132 I SA      : [OR] == networkStateCheck true ==
,08-29 16:40:35.183  7222  7222 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 16:40:35.183  7222  7222 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-29 16:40:35.183  2800  7335 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-29 16:40:35.183  7222  7222 D InitializeManagerStateMachine: exit::SUCCESS
08-29 16:40:35.183  7222  7222 D InitializeManagerStateMachine: entry::IDLE
,08-29 16:40:35.183  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-29 16:40:35.193  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 16:40:35.193  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-29 16:40:35.193  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-29 16:40:35.193  7132  7132 I SA      : [OR] GetMyCountryZoneTask,
08-29 16:40:35.193  7132  7132 I SA      : [OR] onReceive END
,08-29 16:40:35.193  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.193  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.193  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 16:40:35.203  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-29 16:40:35.203  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-29 16:40:35.203  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-29 16:40:35.203  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:40:35.203  2800  7335 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-29 16:40:35.213  1015  1496 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-29 16:40:35.213  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.213  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.213  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:35.213  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-29 16:40:35.213  7132  7339 I SA      : [SRS] prepareGetMyCountryZone
,08-29 16:40:35.223  6971  7340 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-29 16:40:35.223  6971  7340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 16:40:35.223  6971  7340 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 16:40:35.223  6971  7340 I System.out: (HTTPLog)-Thread-1275-327060766: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 16:40:35.223  6971  7340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:35.223   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:35.223   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 10102
,08-29 16:40:35.233  2800  7335 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-29 16:40:35.233  7132  7339 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 16:40:35.233  1015  1524 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-29 16:40:35.233  1015  1524 D SecContentProvider2: mCursor = null
08-29 16:40:35.233  7132  7339 I SA      : [SSP] query invoked
,08-29 16:40:35.243  7132  7339 I SA      : [TPMU] GetMccFromDB : null
,08-29 16:40:35.243  2800  7335 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-29 16:40:35.253  7132  7339 I SA      : [SCU] getMccFromPreferece mcc = 260
08-29 16:40:35.253  7132  7339 I SA      : [LBE] isSupportCheckDomainRegion : false
08-29 16:40:35.253  7132  7339 I SA      : [TPM] isNoProxy(default) : true
,08-29 16:40:35.263  6971  7340 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 16:40:35.263  2800  7335 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 16:40:35.263  7132  7339 E File    : fail readDirectory() errno=2
08-29 16:40:35.263  1015  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.273  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:35.273  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.273  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.293  7205  7205 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-29 16:40:35.303  7205  7205 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-29 16:40:35.303  7205  7205 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-29 16:40:35.313  7205  7205 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-29 16:40:35.323  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 16:40:35 GMT+02:00 2016
,08-29 16:40:35.323  1015  1496 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 16:40:35.323  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.323  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.323  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 16:40:35.323  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 16:40:35.323  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-29 16:40:35.323  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 16:40:35.323  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.323  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.323  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:35.323  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.333  6971  7340 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:40:35.333  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 16:40:35.333  2933  2933 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 16:40:35.343  2933  2933 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 16:40:35.343  2933  7347 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 16:40:35.343  2933  7347 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 16:40:35.353  2933  7347 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-29 16:40:35.353  2933  7347 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-29 16:40:35.373  2933  7347 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-29 16:40:35.373  1015  1487 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 16:40:35.383  2933  7347 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-29 16:40:35.383  2933  7347 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 16:40:35.383  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 16:40:35.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:35.613  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-29 16:40:35.633  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.633  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:35.633  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.633  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.633  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.643  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.643  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:35.643  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.693  2001  2001 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c24388bc-9191-4492-a940-9266d9e997e4
,08-29 16:40:35.713  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:40:35.713  1015  3998 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:40:35.713  1015  3998 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:40:35.713  1015  3998 D BatteryService: stay LED for fully charged
08-29 16:40:35.713  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:40:35.723  1015  1015 I MotionRecognitionService: Plugged
08-29 16:40:35.723  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:40:35.723  7132  7339 I SA      : [RC New] Execute method=[GET] start
,08-29 16:40:35.723  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:40:35.723  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:40:35.733  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:40:35.733  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:40:35.743  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:40:35.743  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:40:35.743  1015  1484 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 16:40:35.743  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 16:40:35.743  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.743  1015  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.743  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.753  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:40:35.753  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:40:35.753  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:35.753  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:35.753  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:35.763  7132  7339 I SA      : [RC New] Security=[true]
,08-29 16:40:35.763  7132  7339 I System.out: Thread-1316(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-29 16:40:35.763  7132  7339 I System.out: Thread-1316(ApacheHTTPLog):isSBSettingEnabled false
08-29 16:40:35.763  7132  7339 I System.out: Thread-1316(ApacheHTTPLog):isShipBuild true
08-29 16:40:35.763  7132  7339 I System.out: Thread-1316(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-29 16:40:35.763  7132  7339 I System.out: Thread-1316(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-29 16:40:35.763   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:35.763   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 10036
,08-29 16:40:35.863  2001  2148 W GCoreFlp: No location to return for getLastLocation()
,08-29 16:40:35.893  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.893  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:35.893  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.893  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.893  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.893  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.893  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.893  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.903  1015  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:35.903  1015  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:35.903  1015  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:35.903  1015  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:35.913  4732  7336 D UdcContextInitService: registered all accounts: true
,08-29 16:40:35.923  2001  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 16:40:35.933  2001  2167 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-29 16:40:36.093  2001  2167 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 16:40:36.093  2001  2167 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-29 16:40:36.113  2001  7357 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:36.123   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-29 16:40:36.123   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 10011
,08-29 16:40:36.133  2001  2001 I art     : Explicit concurrent mark sweep GC freed 81209(4MB) AllocSpace objects, 18(839KB) LOS objects, 39% free, 11MB/19MB, paused 6.839ms total 102.930ms
,08-29 16:40:36.133  1015  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 16:40:36.133  1015  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-29 16:40:36.133  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:36.133  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.133  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.153  2001  7357 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 16:40:36.153  2001  7357 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:36.153  1015  2093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 16:40:36.193  2001  7357 I qtaguid : Tagging socket 60 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:36.253  1015  3997 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:36.253  1015  3997 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:36.253  1015  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.253  1015  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.293  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:36.293  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:36.293  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.293  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.293  2001  7364 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 16:40:36.293  2001  7362 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 16:40:36.293  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:36.293  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:36.293  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.293  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.323  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:36.323  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:36.323  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.323  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 16:40:36.323  2001  7364 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-29 16:40:36.323  2001  7362 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-29 16:40:36.323  1015  3998 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 16:40:36.323  1015  3998 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:36.323  1015  3998 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:36.323  1015  3998 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.353  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:36.353  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:36.353  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:36.353  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:36.353  2001  7364 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 16:40:36.353  2001  7362 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-29 16:40:36.353  2001  7362 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-29 16:40:36.363  2001  7362 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 16:40:36.383  7132  7339 I SA      : [RC New] [v2liruge] api execute + 619
08-29 16:40:36.383  7132  7339 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,08-29 16:40:36.403  7132  7339 I System.out: AsyncTask #1 calls detatch()
,08-29 16:40:36.403  7132  7339 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,08-29 16:40:36.413  7132  7339 I SA      : [OCP] update openData : PL
,08-29 16:40:36.413  7132  7339 I SA      : [TPMU] getNetworkMcc : 
,08-29 16:40:36.423  2001  7357 I qtaguid : Untagging socket 47
,08-29 16:40:36.423  7132  7339 I SA      : [SCU] saveMccToPreferece Start
08-29 16:40:36.423  7132  7339 I SA      : [SCU] RegionMCC : 260
08-29 16:40:36.423  7132  7339 I SA      : [SSP] query invoked
,08-29 16:40:36.423  7132  7339 I SA      : [TPMU] GetMccFromDB : null
08-29 16:40:36.423  7132  7339 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-29 16:40:36.423  7132  7339 I SA      : [SCU] saveMccToPreferece End
,08-29 16:40:36.423  7132  7339 I SA      : [RC New] executeRequest [v2liruge] end. 701
08-29 16:40:36.423  7132  7339 I SA      : [RC New] Execute end
08-29 16:40:36.423  7132  7132 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-29 16:40:36.423  7132  7132 I SA      : [OR] GetMyCountryZoneTask Success
,08-29 16:40:36.423  2001  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-29 16:40:36.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:36.513  1015  1497 I art     : Explicit concurrent mark sweep GC freed 40689(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.453ms total 145.651ms
,08-29 16:40:36.543  4326  4434 I art     : Explicit concurrent mark sweep GC freed 2577(103KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 684us total 23.621ms
,08-29 16:40:36.593  1015  3998 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 16:40:36.643  2001  7362 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:36.643   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 16:40:36.643   278  1010 D Netd    : getNetworkForDns: using netid 503 for uid 10011
,08-29 16:40:36.653  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:40:36.683  2001  7362 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 16:40:36.683  2001  7362 I qtaguid : Tagging socket 78 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:36.733  2001  7362 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:36.823  6826  6879 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 16:40:36.823  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 16:40:36.823  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:40:36.823  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 16:40:36.823  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:40:36.823  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 16:40:36.823  6826  6879 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10568f46, channel: 6, state: LISTENING
08-29 16:40:36.823  6826  6879 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10568f46, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@207cc988, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2aa68507mSocket: android.net.LocalSocket@fd8f634 impl:android.net.LocalSocketImpl@3a9cdc5d fd:FileDescriptor[107]
08-29 16:40:36.823  6826  6879 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fd8f634 impl:android.net.LocalSocketImpl@3a9cdc5d fd:FileDescriptor[107]
08-29 16:40:36.833  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:40:36.833  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:40:36.833  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 16:40:36.833  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:40:36.833  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:40:36.833  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:40:36.833  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 16:40:36.833  6826  6957 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10568f46, channel: 6, state: CLOSED
,08-29 16:40:36.833  6826  6957 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 16:40:36.833  6826  6957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:40:36.833  6826  6957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:40:36.833  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:40:36.833  6826  6879 D BluetoothLeScanner: could not find callback wrapper
,08-29 16:40:36.843  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 16:40:36.843  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-29 16:40:36.843  3156  3256 D BtGatt.AdvertiseManager: message : 1
,08-29 16:40:36.843  3156  3256 D BtGatt.AdvertiseManager: stop advertise for client 6
,08-29 16:40:36.843  3156  3256 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,08-29 16:40:36.843  3156  3256 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,08-29 16:40:36.853  3156  3254 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,08-29 16:40:36.853  3156  3254 D BtGatt.GattService: Client app is not null!
,08-29 16:40:36.863  3156  5230 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 16:40:36.873  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 16:40:36.873  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 16:40:36.873  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:40:36.873  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:40:36.883  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:40:36.883  6826  6826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:36.883  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:40:36.883  6826  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 16:40:36.883  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:40:36.883  6826  6826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:40:36.883  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:36.883  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:40:36.883  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:36.883  6826  6879 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f not in the list
08-29 16:40:36.883  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:40:36.883  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:36.883  6826  6879 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:40:36.883  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:40:37.033  1015  1484 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 16:40:37.043  2001  7362 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:37.043  2001  7362 I qtaguid : Tagging socket 78 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:37.193  1015  1524 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 16:40:37.203  2001  7362 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:37.203  2001  7362 I qtaguid : Tagging socket 78 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 16:40:37.273  7149  7149 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,08-29 16:40:37.383  6826  6826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:40:37.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:37.473   291   291 E SMD     : DCD OFF
,08-29 16:40:38.153  1015  3997 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-29 16:40:38.153  1015  3997 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 16:40:38.153  1015  3997 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:38.153  1015  3997 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 16:40:38.153  1015  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 16:40:38.223  2001  7356 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 16:40:38.223  2001  7356 I qtaguid : Tagging socket 47 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 16:40:38.403  2001  7356 I qtaguid : Untagging socket 47
,08-29 16:40:38.413  2001  2170 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-29 16:40:38.443  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 16:40:38.473   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 16:40:38.553   258  6093 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,08-29 16:40:38.553   258  1037 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,08-29 16:40:38.553  1015  3998 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 129119
,08-29 16:40:38.563  1015  3998 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0),
08-29 16:40:38.563  1015  3998 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3481),
,08-29 16:40:39.833  1015  2093 I ActivityManager: Killing 6790:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
,08-29 16:40:40.053  7004  7004 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected,
,08-29 16:40:40.063  7004  7369 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,08-29 16:40:40.093  7004  7369 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,08-29 16:40:40.093  7004  7369 I ReactiveServiceManager: Supported : 1
,08-29 16:40:40.093  1015  1484 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,08-29 16:40:40.093  1015  1484 D QSEECOMAPI: : App is not loaded in QSEE
,08-29 16:40:40.113  1015  1484 D QSEECOMAPI: : Loaded image: APP id = 12
,08-29 16:40:40.123  1015  1484 D QSEECOMAPI: : QSEECom_dealloc_memory 
,08-29 16:40:40.123  1015  1484 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
08-29 16:40:40.123  1015  1484 E terrier : handleString: Failed to handle string(-4)
08-29 16:40:40.123  1015  1484 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,08-29 16:40:40.123  7004  7369 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
08-29 16:40:40.123  7004  7369 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,08-29 16:40:40.123  7004  7369 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 16:40:40.123  7004  7369 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 16:40:40.123  7004  7369 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-29 16:40:40.123  7004  7369 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,08-29 16:40:40.483   291   291 E SMD     : DCD OFF,
,08-29 16:40:41.283  7149  7149 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,08-29 16:40:41.893  6826  6879 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true,
,08-29 16:40:41.893  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:41.893  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:41.903  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:41.903  6826  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:40:41.903  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:41.903  6826  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:40:41.903  6826  6879 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-29 16:40:41.903  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-29 16:40:41.913  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
08-29 16:40:41.913  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 16:40:41.913  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 16:40:41.913  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 16:40:41.913  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 16:40:41.913  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:41.913  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:40:41.923  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-29 16:40:41.923  6826  7372 D BluetoothSocket: bindListen(): myUserId = 0
08-29 16:40:41.923  6826  7372 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:40:41.923  6826  7372 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,08-29 16:40:41.923  6826  7372 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 16:40:41.923  6826  7372 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 16:40:41.923  6826  7372 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4fe159
08-29 16:40:41.923  6826  7372 D BluetoothSocket: channel: 6
,08-29 16:40:41.923  6826  7372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 16:40:41.923  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:40:41.933  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:40:41.933  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 16:40:41.933  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 16:40:41.933  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 76 27
,08-29 16:40:41.933  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 16:40:41.933  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 16:40:41.933  6826  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 16:40:41.933  3156  5230 D BtGatt.GattService: registerClient() - UUID=f9e73279-4872-4cb4-a9ed-0354d42e4196
,08-29 16:40:41.983  3156  3254 D BtGatt.GattService: onClientRegistered() - UUID=f9e73279-4872-4cb4-a9ed-0354d42e4196, clientIf=6
,08-29 16:40:41.983  6826  6835 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,08-29 16:40:41.983  3156  3256 D BtGatt.AdvertiseManager: message : 0
,08-29 16:40:41.983  3156  3256 D BtGatt.AdvertiseManager: number of adv instance running0
,08-29 16:40:41.983  3156  3256 D BtGatt.AdvertiseManager: size of list is =0
,08-29 16:40:41.983  3156  3256 D BtGatt.AdvertiseManager: starting advertising
,08-29 16:40:41.983  3156  3256 D BtGatt.AdvertiseManager: isStandardAdvfalse
,08-29 16:40:41.993  3156  3254 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,08-29 16:40:42.003  3156  3256 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 16:40:42.003  3156  3254 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,08-29 16:40:42.003  3156  3256 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,08-29 16:40:42.003  3156  3256 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,08-29 16:40:42.003  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 16:40:42.003  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:40:42.003  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:40:42.013  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:40:42.013  6826  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 16:40:42.013  6826  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 16:40:42.013  6826  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 16:40:42.013  6826  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 16:40:42.013  6826  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 16:40:42.013  6826  6879 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:40:42.013  6826  6826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:42.013  6826  6826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:40:42.523  6826  6826 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 16:40:42.523  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 16:40:42.523  6826  6826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:42.803  1015  3363 D SSRM:n  : SIOP:: AP = 380
,08-29 16:40:43.483   291   291 E SMD     : DCD OFF
,08-29 16:40:44.053  1015  1524 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-29 16:40:44.053  1015  1524 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,08-29 16:40:44.053  1015  1524 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:44.053  1015  1524 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-29 16:40:44.053  1015  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 16:40:44.073  7222  7222 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,08-29 16:40:44.073  7222  7222 D PreloadUpdateManagerStateMachine: exit::IDLE
,08-29 16:40:44.073  7222  7222 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-29 16:40:44.073  7222  7222 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,08-29 16:40:44.083  7222  7222 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,08-29 16:40:44.083  7222  7222 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,08-29 16:40:44.083  7222  7222 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,08-29 16:40:44.083  7222  7222 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-29 16:40:45.153  1015  1495 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-29 16:40:45.153  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,08-29 16:40:45.153  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:45.153  1015  1495 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-29 16:40:45.153  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: exit::IDLE
08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-29 16:40:45.173  7222  7222 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
08-29 16:40:45.173  7222  7222 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-29 16:40:45.283  7149  7149 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 16:40:45.283  7149  7149 I dhcpcd  : wlan0: no IPv6 Routers available
,08-29 16:40:45.783  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:40:45.783  1015  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:40:45.783  1015  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:40:45.783  1015  1497 D BatteryService: stay LED for fully charged
,08-29 16:40:45.783  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:40:45.793  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-29 16:40:45.793  1015  1015 I MotionRecognitionService: Plugged
08-29 16:40:45.793  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:40:45.793  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
08-29 16:40:45.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:40:45.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:40:45.803  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:40:45.803  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:40:45.813  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:40:45.813  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:40:45.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:45.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:40:45.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:46.493   291   291 E SMD     : DCD OFF,
,08-29 16:40:47.013  6826  6879 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:40:47.013  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 16:40:47.013  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:40:47.013  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 16:40:47.013  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:40:47.013  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 16:40:47.013  6826  6879 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a810dff, channel: 6, state: LISTENING
08-29 16:40:47.013  6826  6879 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a810dff, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4fe159, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d70d7ccmSocket: android.net.LocalSocket@2e943a15 impl:android.net.LocalSocketImpl@d512a fd:FileDescriptor[107]
,08-29 16:40:47.013  6826  6879 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e943a15 impl:android.net.LocalSocketImpl@d512a fd:FileDescriptor[107]
,08-29 16:40:47.013  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:40:47.013  6826  6879 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 16:40:47.013  6826  7372 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a810dff, channel: 6, state: CLOSED
08-29 16:40:47.013  6826  7372 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 16:40:47.013  6826  7372 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:40:47.013  6826  7372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:40:47.013  6826  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 16:40:47.023  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-29 16:40:47.023  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 16:40:47.023  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:40:47.023  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:40:47.023  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:40:47.023  6826  6879 D BluetoothLeScanner: could not find callback wrapper,
08-29 16:40:47.023  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:40:47.023  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-29 16:40:47.023  3156  3256 D BtGatt.AdvertiseManager: message : 1
08-29 16:40:47.023  3156  3256 D BtGatt.AdvertiseManager: stop advertise for client 6
08-29 16:40:47.023  3156  3256 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,08-29 16:40:47.023  3156  3256 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,08-29 16:40:47.033  3156  3254 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
08-29 16:40:47.033  3156  3254 D BtGatt.GattService: Client app is not null!
08-29 16:40:47.043  3156  3172 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-29 16:40:47.043  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 16:40:47.043  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 16:40:47.043  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:40:47.043  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:40:47.043  6826  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:40:47.053  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:47.053  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:40:47.053  6826  6879 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c3430f not in the list
08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:47.053  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
08-29 16:40:47.053  6826  6879 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:40:47.053  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:40:47.053  6826  6879 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:40:47.053  6826  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:40:47.053  6826  6826 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:40:47.053  6826  6826 D AndroidRuntime: Shutting down VM
,08-29 16:40:47.053  6826  6826 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:40:47.053  6826  6826 E AndroidRuntime: Process: com.test.thalitest, PID: 6826
08-29 16:40:47.053  6826  6826 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 16:40:47.053  6826  6826 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:40:47.053  6826  6879 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c4f9c not in the list
,08-29 16:40:47.053  6826  6879 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 16:40:47.053  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:40:47.063  1015  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
,08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:40:47.063  6826  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:40:47.073  6826  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:40:47.073  6826  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:40:47.073  6826  6879 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:40:47.073  6826  6879 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:40:47.073  6826  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:40:47.073  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:40:47.073  6826  6879 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:40:47.073  6826  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:40:47.083  1015  1487 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-29 16:40:47.083  1015  1487 D FocusedStackFrame: Set to : 0
,08-29 16:40:47.083  1015  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 16:40:47.083  1015  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,08-29 16:40:47.083  1015  1487 D InputDispatcher: Focused application set to: xxxx
,08-29 16:40:47.093  1015  1487 D InputDispatcher: Focus left window: 6826
,08-29 16:40:47.093  1015  1487 I ActivityManager: Killing 5903:com.android.vending/u0a26 (adj 15): empty #21
,08-29 16:40:47.103  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 16:40:47.103  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 16:40:47.103  6826  6826 I Process : Sending signal. PID: 6826 SIG: 9
,08-29 16:40:47.113  1015  1015 D CrashAnrDetector: processName: com.test.thalitest
08-29 16:40:47.113  1015  1015 D CrashAnrDetector: broadcastEvent : com.test.thalitest data_app_crash
,08-29 16:40:47.113  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-29 16:40:47.113  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.113  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.113  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.113  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.123  1015  1015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 ,
,08-29 16:40:47.133  7377  7377 E Zygote  : MountEmulatedStorage(),
08-29 16:40:47.133  7377  7377 E Zygote  : v2
08-29 16:40:47.133  7377  7377 I libpersona: KNOX_SDCARD checking this for 1000,
08-29 16:40:47.133  7377  7377 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:47.143  1015  1041 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7377 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 16:40:47.143  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:47.143  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:47.143  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.183  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.183  7377  7377 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.193  7377  7377 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 16:40:47.233  7377  7377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.sm.common.SmartManagerReceiver.b:199 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:93 
,08-29 16:40:47.233  1015  1484 D ActivityManager: startService callerProcessName:com.samsung.android.sm, calleePkgName: com.samsung.android.sm
,08-29 16:40:47.233  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sm/com.samsung.android.sm.common.notification.CrashedAppLoggingService; callingUser = 0; userId(target) = 0
,08-29 16:40:47.243  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.243  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.243  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sm, destAppInfo.processName = com.samsung.android.sm
,08-29 16:40:47.253  1015  2093 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:47.253  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.253  1015  2093 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:47.253  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:47.263  1015  1487 I WindowState: WIN DEATH: Window{3d1a3af5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 16:40:47.263  1015  1134 I ActivityManager: Process com.test.thalitest (pid 6826)(adj 9) has died(151,702)
,08-29 16:40:47.263   258  1037 I SurfaceFlinger: id=13 Removed NainActivit (6/8),
08-29 16:40:47.263   258  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-29 16:40:47.273   258   449 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-29 16:40:47.283  1015  1134 W ActivityManager: mDVFSHelper.acquire(),
,08-29 16:40:47.283  1015  1134 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.am.SmartAdjustManager.SPCMLocked:1235 com.android.server.am.ActivityManagerService.updateOomAdjLocked:22618 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:2721 com.android.server.am.ActivityStack.resumeTopActivityLocked:2240 
,08-29 16:40:47.293  1015  1134 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,08-29 16:40:47.303  7377  7392 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-29 16:40:47.313  1498  1498 D Launcher: onRestart, Launcher: 276569419
,08-29 16:40:47.313  1498  1498 D Launcher: onStart, Launcher: 276569419
08-29 16:40:47.313  1498  1498 D Launcher.HomeView: onStart
,08-29 16:40:47.313  1498  1498 D Launcher: onResume, Launcher: 276569419
,08-29 16:40:47.313  1015  2093 D SettingsProvider: name = kids_home_mode
,08-29 16:40:47.313  1015  2093 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 16:40:47.313  1015  2093 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 16:40:47.313  1015  2093 D SettingsProvider: selectionArgs: false
08-29 16:40:47.313  1015  2093 D SettingsProvider: selectionArgs: 10006
08-29 16:40:47.313  1015  2093 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 16:40:47.313  1015  2093 D SettingsProvider: ret = -1
08-29 16:40:47.313  1498  1498 D Launcher.HomeView: onResume
,08-29 16:40:47.323  1015  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:47.323  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 16:40:47.323  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.323  1015  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:47.323  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:47.333  1498  1498 D MenuAppsGridFragment: onResume
,08-29 16:40:47.333  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.333  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.333  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-29 16:40:47.333  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 16:40:47.333  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 16:40:47.333  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:47.333  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.343  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:40:47.343  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:47.343  1015  1216 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-29 16:40:47.343  1015  1216 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-29 16:40:47.343  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.343  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.343  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-29 16:40:47.343  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-29 16:40:47.343  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.343  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.343  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.343  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.363  7395  7395 E Zygote  : MountEmulatedStorage()
,08-29 16:40:47.363  7395  7395 E Zygote  : v2
,08-29 16:40:47.363  7395  7395 I libpersona: KNOX_SDCARD checking this for 10039
08-29 16:40:47.363  7395  7395 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:47.363  1015  1216 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7395 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-29 16:40:47.363  7395  7395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:47.363  1015  1487 D ActivityManager: handle home activity for 0
08-29 16:40:47.363  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 16:40:47.363  1015  1487 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-29 16:40:47.363  1015  1487 D KnoxTimeoutHandler: post home show event for user 0
08-29 16:40:47.363  1015  1487 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 16:40:47.363  1015  1487 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 16:40:47.363  1015  1487 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 16:40:47.363  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-29 16:40:47.363  1498  1498 D Launcher.HomeView: onPause
,08-29 16:40:47.363  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-29 16:40:47.363  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 16:40:47.363  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-29 16:40:47.363  7395  7395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:47.363  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.363  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.363  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-29 16:40:47.363  7395  7395 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.373  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.373  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-29 16:40:47.373  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.373  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-29 16:40:47.373  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.373  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.373  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.373  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.383  7409  7409 E Zygote  : MountEmulatedStorage()
,08-29 16:40:47.383  7409  7409 E Zygote  : v2
08-29 16:40:47.383  7409  7409 I libpersona: KNOX_SDCARD checking this for 10089
08-29 16:40:47.383  7409  7409 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:47.383  7409  7409 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:47.393  7409  7409 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:47.393  1015  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7409 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-29 16:40:47.393  7409  7409 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.393  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-29 16:40:47.393  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.393  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.393  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-29 16:40:47.393  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.393  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.393  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.393  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.403  7395  7395 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 16:40:47.403  7395  7395 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.413  7420  7420 E Zygote  : MountEmulatedStorage()
,08-29 16:40:47.413  7420  7420 I libpersona: KNOX_SDCARD checking this for 10139
08-29 16:40:47.413  7420  7420 E Zygote  : v2
08-29 16:40:47.413  7420  7420 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:47.413  7420  7420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:47.413  1015  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7420 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-29 16:40:47.413  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:40:47.413  7420  7420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:47.413  7420  7420 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 16:40:47.413  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.413  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 16:40:47.413  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 16:40:47.433  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-29 16:40:47.433  7420  7420 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.433  7420  7420 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.433  7409  7409 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.443   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-29 16:40:47.443  7409  7409 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.443  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 16:40:47.443  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 16:40:47.443  1015  1495 D InputDispatcher: Focus entered window: 1498
,08-29 16:40:47.453  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 16:40:47.453  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 16:40:47.453  1498  1498 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 16:40:47.453  7395  7395 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 16:40:47.463  1015  3998 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.463  1015  3998 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1498, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-29 16:40:47.463  1015  3998 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.463  1015  3998 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-29 16:40:47.463  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{c204364 token=android.os.BinderProxy@1d4b89ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-29 16:40:47.463  1498  1498 D Launcher.HomeView: onStop
,08-29 16:40:47.463  1015  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 16:40:47.463  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.463  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.463  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-29 16:40:47.463  7409  7409 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-29 16:40:47.463  7409  7409 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.,
08-29 16:40:47.473  2559  2559 D Recents_RecreateReceiver: onReceive by home
08-29 16:40:47.473  1015  7440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:40:47.473  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.483  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-29 16:40:47.473  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.483  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-29 16:40:47.483  1015  1496 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6826 uid 10171
,08-29 16:40:47.493  1174  1174 I StatusBar: Icon Only
,08-29 16:40:47.493  1174  1174 D PanelView: There is/are notification(s) 
08-29 16:40:47.493  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.493  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.493  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.493  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.503  4732  7393 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.,
,08-29 16:40:47.513  1859  1859 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-29 16:40:47.533  7420  7420 V TaskCloserActivity: TaskCloserActivity enter()
08-29 16:40:47.533  7443  7443 E Zygote  : MountEmulatedStorage()
08-29 16:40:47.533  7443  7443 I libpersona: KNOX_SDCARD checking this for 10084
08-29 16:40:47.533  7443  7443 E Zygote  : v2
08-29 16:40:47.533  7443  7443 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:47.533  7443  7443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:47.543  7443  7443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:47.543  7443  7443 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.543  1015  1027 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7443 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-29 16:40:47.553  1498  1498 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d4b89ac time:138117
,08-29 16:40:47.563  7420  7420 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-29 16:40:47.563  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:47.563  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.563  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-29 16:40:47.573  1015  1322 E Watchdog: !@Sync 4
,08-29 16:40:47.573  1015  1496 I ActivityManager: Killing 7164:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 16:40:47.583  1015  1046 W ActivityManager: mDVFSHelper.release()
,08-29 16:40:47.583  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8d7286d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:138149
,08-29 16:40:47.593  1015  1524 D PersonaManager: isKioskContainerExistOnDevice
,08-29 16:40:47.593  7443  7443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.593  7443  7443 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.603  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.603  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.603  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-29 16:40:47.603  1015  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,08-29 16:40:47.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.613  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
08-29 16:40:47.613  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 16:40:47.613  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 16:40:47.613  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3156, ws=null) (elapsedTime=585)
,08-29 16:40:47.623  7461  7461 E Zygote  : MountEmulatedStorage()
08-29 16:40:47.623  7461  7461 I libpersona: KNOX_SDCARD checking this for 10135
08-29 16:40:47.623  7461  7461 E Zygote  : v2
08-29 16:40:47.623  7461  7461 I libpersona: KNOX_SDCARD not a persona
08-29 16:40:47.623  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:47.623  1015  1489 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7461 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
08-29 16:40:47.623  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 16:40:47.623  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.623  1015  1489 I ActivityManager: Killing 7004:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 16:40:47.643  7443  7443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 16:40:47.643  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.643  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.653  1015  1497 I ActivityManager: Killing 7044:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 16:40:47.663  7461  7461 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-29 16:40:47.663  7461  7461 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 16:40:47.663  7461  7461 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-29 16:40:47.663  7461  7461 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-29 16:40:47.663  7461  7461 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 16:40:47.683  7395  7395 D NearbySource: Nearby Source Create!
,08-29 16:40:47.683  7395  7395 D NearbyContext: Nearby Context Create!
,08-29 16:40:47.703  1015  3998 I ActivityManager: Killing 7031:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-29 16:40:47.723   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-29 16:40:47.723   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 16:40:47.723  7395  7395 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-29 16:40:47.723  7395  7395 D SLinkSource: Samsung link source created
,08-29 16:40:47.763  7395  7477 D ContactProvider: getAllContactInfoList Start
,08-29 16:40:47.773  1015  3998 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 16:40:47.773  1015  2093 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 16:40:47.773  7395  7395 D GalleryCacheReady: Receive : home resume
,08-29 16:40:47.783  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 16:40:47.783  1015  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:47.783  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
08-29 16:40:47.783  1015  1497 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-29 16:40:47.783  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.783  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:47.783  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.783  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:47.793  7478  7478 E Zygote  : MountEmulatedStorage(),
08-29 16:40:47.793  7478  7478 E Zygote  : v2
08-29 16:40:47.793  7478  7478 I libpersona: KNOX_SDCARD checking this for 10041
08-29 16:40:47.793  7478  7478 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:47.793  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:47.803  1015  1497 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7478 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,08-29 16:40:47.803  1015  1497 I ActivityManager: Killing 7021:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 16:40:47.803  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 16:40:47.803  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 16:40:47.823  7395  7477 D ContactProvider: getAllContactInfoList End
,08-29 16:40:47.823  7395  7477 I syncContacts: thread: 1348, sync time = 67
,08-29 16:40:47.833  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:47.833  7478  7478 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:47.843  7478  7478 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-29 16:40:47.843  7478  7478 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 16:40:47.843  7478  7478 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 16:40:47.843  7478  7478 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 16:40:47.843  7478  7478 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-29 16:40:47.873  7478  7478 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-29 16:40:48.073  7478  7493 D Mms/ArtClassLoader: init before art
,08-29 16:40:48.073  7478  7478 D Mms/TelephonyPermission: start operation mode monitor
,08-29 16:40:48.083  7478  7478 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 16:40:48.093  7478  7478 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-29 16:40:48.093  7478  7478 D Mms/TelephonyPermission: isDefault true
,08-29 16:40:48.093  7478  7478 D Mms/MmsApp: onCreate() com.android.mms
,08-29 16:40:48.383  7478  7478 D Mms/MmsApp: [start]    initCountryIso consume time = 503.779791
,08-29 16:40:48.383  1015  2093 D CountryDetector: The first listener is added
,08-29 16:40:48.393  7478  7478 D Mms/MmsApp: [end]    initCountryIso consume time = 9.555417,
08-29 16:40:48.393  7478  7478 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.153437
,08-29 16:40:48.403  7478  7478 D Mms/MmsConfig: before partial update
,08-29 16:40:48.423  7478  7478 D Mms/MmsConfig: Load Resize quality : 80
,08-29 16:40:48.423  7478  7478 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,08-29 16:40:48.433  7478  7478 D EasySignUpManager_1.0.1: isAuth is false
,08-29 16:40:48.433  7478  7478 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-29 16:40:48.433  1469  2677 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7478
,08-29 16:40:48.443  1469  2677 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.100 ms
,08-29 16:40:48.443  7478  7478 D EasySignUpManager_1.0.1: isAuth is false
08-29 16:40:48.443  7478  7478 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-29 16:40:48.453  7478  7478 E CscParser: mps_code.dat does not exist
08-29 16:40:48.453  7478  7478 E CscParser: customer_path =/system/csc/customer.xml
08-29 16:40:48.453  7478  7478 E CscParser: fileName + /system/csc/customer.xml
,08-29 16:40:48.463  7478  7478 E CscParser: mps_code.dat does not exist
,08-29 16:40:48.463  7478  7478 E CscParser: customer_path =/system/csc/customer.xml
,08-29 16:40:48.463  7478  7478 E CscParser: fileName + /system/csc/customer.xml
,08-29 16:40:48.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:40:48.473  7478  7478 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-29 16:40:48.473  7478  7478 D Mms/MmsConfig:  enable multiwindow = false
,08-29 16:40:48.483  7478  7478 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-29 16:40:48.483  7478  7478 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-29 16:40:48.493  7478  7478 D Mms/MmsConfig: [end]    init() consume time = 100.730365
,08-29 16:40:48.493  7478  7478 D Mms/Contact: [start]    init() consume time = 1.021406
,08-29 16:40:48.493  1469  1490 D TP/MmsSmsProvider: query,matched:13, calling pid = 7478
,08-29 16:40:48.503  1469  1490 D TP/MmsSmsProvider: match 13:Elapsed time : 1.923 ms
,08-29 16:40:48.503  7478  7478 D Mms/Contact: [end]    init consume time = 13.529271
,08-29 16:40:48.513  7478  7500 D Mms/DraftCache: [start]    rebuildCache consume time = 8.073594
,08-29 16:40:48.513  7478  7478 D Mms/MethodReflector: getSubId is called
,08-29 16:40:48.513  7478  7478 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 16:40:48.513  1469  2677 D TP/MmsSmsProvider: query,matched:12, calling pid = 7478
,08-29 16:40:48.513  7478  7478 D Mms/MethodReflector: getTelephonyProperty is called
08-29 16:40:48.513  7478  7478 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 16:40:48.513  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 16:40:48.513  7478  7478 D Mms/DownloadManager: auto download without roaming -> true
08-29 16:40:48.513  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,08-29 16:40:48.513  7478  7478 D Mms/MethodReflector: getSubId is called
,08-29 16:40:48.513  1469  2677 D TP/MmsSmsProvider: match 12:Elapsed time : 2.523 ms,
,08-29 16:40:48.523  7478  7478 D Mms/MethodReflector: getDefaultSmsSubId is called
,08-29 16:40:48.523  7478  7478 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
,08-29 16:40:48.523  7478  7478 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,08-29 16:40:48.523  7478  7478 D Mms/MethodReflector: getTelephonyProperty is called
08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: roaming -> false (slotId = 1)
,08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: auto download without roaming -> true
08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: auto download during roaming secondary -> false
,08-29 16:40:48.523  7478  7478 D Mms/DownloadManager: mAutoDownload ------> true
08-29 16:40:48.523  7478  7493 D Mms/ArtClassLoader: init [DONE] art
,08-29 16:40:48.523  7478  7500 D Mms/DraftCache: [end]    rebuildCache consume time = 13.046042
,08-29 16:40:48.553  7478  7478 D ComposerPerformance: 1472481648563 ms / [DONE] Composer constructor
,08-29 16:40:48.553  7478  7501 D Mms/Conversation: [start]    init() consume time = 28.386822
,08-29 16:40:48.553  7478  7478 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-29 16:40:48.553  7478  7478 I Mms/ReservationManager: ReservationManager()
,08-29 16:40:48.553  7478  7478 I Mms/ReservationManager: resetAfterConnected()
,08-29 16:40:48.553  1469  1486 D TP/MmsSmsProvider: query,matched:7, calling pid = 7478
,08-29 16:40:48.553  1469  2677 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-29 16:40:48.563  1469  2677 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-29 16:40:48.563  1469  2677 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-29 16:40:48.563  1469  1486 D TP/MmsSmsProvider: match 7:Elapsed time : 2.518 ms
,08-29 16:40:48.563  1469  2677 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-29 16:40:48.563  7478  7478 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-29 16:40:48.563  7478  7478 D Mms/MmsApp: [end]    onCreate() consume time = 11.662136
,08-29 16:40:48.563  7478  7478 D Mms/UIEventReceiver: ui event
,08-29 16:40:48.563  7478  7478 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
08-29 16:40:48.563  7478  7478 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,08-29 16:40:48.563  1015  1497 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-29 16:40:48.573  7478  7478 D Mms/MethodReflector: getSubId is called
08-29 16:40:48.573  7478  7478 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-29 16:40:48.573  1469  2677 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-29 16:40:48.573  1469  2677 D TP/MmsSmsProvider: need read changed broadcast:false
,08-29 16:40:48.573  7478  7478 D Mms/MethodReflector: getTelephonyProperty is called
08-29 16:40:48.573  1015  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:40:48.573  7478  7478 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 16:40:48.573  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 16:40:48.573  7478  7478 D Mms/DownloadManager: auto download without roaming -> true
08-29 16:40:48.573  7478  7478 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 16:40:48.573  7478  7478 D Mms/DownloadManager: mAutoDownload ------> true
,08-29 16:40:48.573  1015  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 16:40:48.573  1015  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-29 16:40:48.573  7420  7420 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-29 16:40:48.573  1015  1497 I ActivityManager: Killing 7116:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-29 16:40:48.583  7478  7501 D Mms/Conversation: [end]    init consume time = 18.347604
,08-29 16:40:48.583  7478  7501 D Mms/MessagingNotification: [start]    init() consume time = 2.65625
,08-29 16:40:48.593  7478  7501 D Mms/MessagingNotification: [end]    init consume time = 3.305833
,08-29 16:40:48.593  7478  7503 D Mms/Synchronizer: [start]    doSync consume time = 6.596146,
,08-29 16:40:48.593  1469  1651 D TP/MmsSmsProvider: query,matched:0, calling pid = 7478
,08-29 16:40:48.603  1469  1651 V TP/MmsSmsProvider: getSimpleConversations entered.,
,08-29 16:40:48.603  1469  1490 D TP/MmsSmsProvider: update, matched:300, calling pid = 7478
08-29 16:40:48.603  1469  1651 D TP/MmsSmsProvider: match 0:Elapsed time : 1.560 ms
08-29 16:40:48.603  1469  1490 V TP/MmsSmsProvider: syncDBData start
,08-29 16:40:48.603  1469  1490 V TP/MmsSmsProvider: syncDBData sms end
08-29 16:40:48.603  1469  1490 V TP/MmsSmsProvider: syncDBData mms end
,08-29 16:40:48.603  7478  7502 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.314115
,08-29 16:40:48.603  1469  1490 V TP/MmsSmsProvider: syncDBData end
08-29 16:40:48.603  7478  7503 D Mms/Synchronizer: [end]    doSync consume time = 0.700521
,08-29 16:40:48.603  1015  1489 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-29 16:40:48.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:48.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.603  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.623  7504  7504 E Zygote  : MountEmulatedStorage()
,08-29 16:40:48.623  7504  7504 E Zygote  : v2
08-29 16:40:48.623  7504  7504 I libpersona: KNOX_SDCARD checking this for 10068
08-29 16:40:48.623  7504  7504 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:48.623  7504  7504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 16:40:48.623  1015  1489 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7504 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 16:40:48.623  1469  1486 D TP/MmsSmsProvider: query,matched:400, calling pid = 7478,
08-29 16:40:48.623  7504  7504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:48.623  7504  7504 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 16:40:48.633  7478  7502 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 26.357395
,08-29 16:40:48.653  7504  7504 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:48.653  7504  7504 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:48.653  1015  1487 I ActivityManager: Killing 7100:com.android.email/u0a141 (adj 15): empty #21
,08-29 16:40:48.683  7504  7504 D BadgeProvider: onCreate
,08-29 16:40:48.683  7504  7504 D BadgeProvider: DatabaseHelper
,08-29 16:40:48.693  7478  7501 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-29 16:40:48.703  1469  1651 D TP/SmsProvider: query,matched:26, calling pid = 7478
,08-29 16:40:48.703  1469  1651 D TP/SmsProvider: match 26:Elapsed time : 0.992 ms
,08-29 16:40:48.703  1469  1490 D TP/MmsSmsProvider: query,matched:6, calling pid = 7478
,08-29 16:40:48.703  1469  1490 D TP/MmsSmsProvider: match 6:Elapsed time : 1.382 ms
,08-29 16:40:48.723  1015  1489 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-29 16:40:48.723  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.723  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 16:40:48.723  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.723  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 16:40:48.733  7519  7519 E Zygote  : MountEmulatedStorage()
08-29 16:40:48.733  7519  7519 E Zygote  : v2
08-29 16:40:48.733  7519  7519 I libpersona: KNOX_SDCARD checking this for 10023
08-29 16:40:48.733  7519  7519 I libpersona: KNOX_SDCARD not a persona
,08-29 16:40:48.743  1015  1489 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7519 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,08-29 16:40:48.743  7519  7519 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 16:40:48.753  7519  7519 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 16:40:48.753  7519  7519 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 16:40:48.763  7519  7519 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 16:40:48.763  7519  7519 D ActivityThread: Added TimaKeyStore provider
,08-29 16:40:48.773   309   309 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 756us total 28.360ms
,08-29 16:40:48.773  1015  1216 I ActivityManager: Killing 7066:com.android.chrome/u0a77 (adj 15): empty #21
,08-29 16:40:48.783   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.843ms
,08-29 16:40:48.803   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.471ms
,08-29 16:40:48.813  7519  7519 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-29 16:40:48.833  7478  7501 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-29 16:40:48.843  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-29 16:40:48.843  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-29 16:40:48.843  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-29 16:40:48.853  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-29 16:40:48.863  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-29 16:40:48.863  7519  7519 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-29 16:40:49.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:49.483   291   291 E SMD     : DCD OFF
,08-29 16:40:50.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:50.573  7478  7478 I Mms/MmsApp:  start initViewCache mms
08-29 16:40:50.573  7478  7478 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1938.424739
08-29 16:40:50.573  7478  7478 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-29 16:40:50.663  7478  7478 D AbsListView: Get MotionRecognitionManager
,08-29 16:40:50.663  1015  2093 D MotionRecognitionService:  ssp status : false
,08-29 16:40:50.673  7478  7478 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 103.57099
,08-29 16:40:50.753  7478  7478 D Mms/BubbleViewCache: fillCache bubble = 1
,08-29 16:40:51.383  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:40:51.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:52.193  1015  2058 V SAMP_SPCM_test: CSC File load.. 
,08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-29 16:40:52.203  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-29 16:40:52.243  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-29 16:40:52.253  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-29 16:40:52.263  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-29 16:40:52.283  1015  2058 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-29 16:40:52.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:40:52.483   291   291 E SMD     : DCD OFF
,08-29 16:40:52.833  1015  3363 D SSRM:n  : SIOP:: AP = 360
,08-29 16:40:53.483   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 16:40:55.483   291   291 E SMD     : DCD OFF,
,08-29 16:40:55.853  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:40:55.853  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
,08-29 16:40:55.853  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:40:55.853  1015  1495 D BatteryService: stay LED for fully charged
,08-29 16:40:55.853  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:40:55.863  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:40:55.863  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:40:55.863  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:40:55.863  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:40:55.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:40:55.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:40:55.873  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:40:55.873  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:40:55.893  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:40:55.893  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:40:55.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:55.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:55.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:40:56.673  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:40:58.493   291   291 E SMD     : DCD OFF
,08-29 16:40:59.993  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 16:41:01.493   291   291 E SMD     : DCD OFF
,08-29 16:41:02.873  1015  3363 D SSRM:n  : SIOP:: AP = 340,
,08-29 16:41:04.503   291   291 E SMD     : DCD OFF
,08-29 16:41:05.903  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:41:07.503   291   291 E SMD     : DCD OFF
,08-29 16:41:08.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:41:09.473   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:41:10.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:41:10.503   291   291 E SMD     : DCD OFF
,08-29 16:41:11.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:41:11.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:41:12.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:41:12.913  1015  3363 D SSRM:n  : SIOP:: AP = 320
,08-29 16:41:13.483   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 16:41:13.503   291   291 E SMD     : DCD OFF,
,08-29 16:41:15.963  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:41:16.503   291   291 E SMD     : DCD OFF
,08-29 16:41:16.693  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:41:17.343  4732  5077 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-29 16:41:17.573  1015  1322 E Watchdog: !@Sync 5
,08-29 16:41:17.633  1015  1048 I PowerManagerService: [PWL] Off : 105s ago
,08-29 16:41:18.253  2001  2660 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-29 16:41:19.503   291   291 E SMD     : DCD OFF,
,08-29 16:41:22.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:22.953  1015  3363 D SSRM:n  : SIOP:: AP = 320
,08-29 16:41:25.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:26.023  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:41:28.513   291   291 E SMD     : DCD OFF
,08-29 16:41:31.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:41:31.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:32.993  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:41:33.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:41:34.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:41:34.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:35.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:41:36.083  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:41:36.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:41:36.713  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:41:37.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:41:37.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:38.493   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-29 16:41:40.523   291   291 E SMD     : DCD OFF,
,08-29 16:41:43.033  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:41:43.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:46.143  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:41:46.523   291   291 E SMD     : DCD OFF
,08-29 16:41:47.573  1015  1322 E Watchdog: !@Sync 6,
,08-29 16:41:47.813  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 16:41:47.813  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 16:41:47.813  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 16:41:47.823  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 16:41:47.833  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 16:41:47.843  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:41:47.843  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-29 16:41:47.843  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 16:41:47.843  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-29 16:41:47.863  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:41:47.863  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:41:47.873  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:41:47.903  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:41:49.513   291   291 E SMD     : DCD OFF,
,08-29 16:41:51.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:41:52.523   291   291 E SMD     : DCD OFF,
,08-29 16:41:52.633  1015  1048 I PowerManagerService: [PWL] Off : 140s ago,
,08-29 16:41:53.073  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:41:55.523   291   291 E SMD     : DCD OFF
,08-29 16:41:56.203  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:41:56.733  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:41:58.533   291   291 E SMD     : DCD OFF,
,08-29 16:41:59.993  1015  1094 V AlarmManager: waitForAlarm result :8,
,08-29 16:42:01.523   291   291 E SMD     : DCD OFF,
,08-29 16:42:03.113  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:42:03.493   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 16:42:03.493   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 16:42:04.533   291   291 E SMD     : DCD OFF,
,08-29 16:42:06.273  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:07.523   291   291 E SMD     : DCD OFF
,08-29 16:42:10.533   291   291 E SMD     : DCD OFF,
,08-29 16:42:11.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:42:13.153  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:42:13.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:13.533   291   291 E SMD     : DCD OFF,
,08-29 16:42:14.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:15.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:16.333  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:16.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:16.533   291   291 E SMD     : DCD OFF
,08-29 16:42:16.753  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:42:17.483   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:17.573  1015  1322 E Watchdog: !@Sync 7,
,08-29 16:42:18.493   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-29 16:42:19.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:22.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:23.183  1015  3363 D SSRM:n  : SIOP:: AP = 310,
,08-29 16:42:23.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:24.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:25.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:25.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:26.393  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:26.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:27.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:28.493   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-29 16:42:28.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:31.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:42:31.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:32.683  1015  1048 I PowerManagerService: [PWL] Off : 180s ago,
,08-29 16:42:33.223  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:42:34.543   291   291 E SMD     : DCD OFF,
,08-29 16:42:36.453  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:36.773  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:42:37.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:38.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:39.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:40.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:40.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:41.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:42.493   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:43.263  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:42:43.503   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-29 16:42:43.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:46.513  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:46.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:47.573  1015  1322 E Watchdog: !@Sync 8,
,08-29 16:42:49.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:51.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:42:52.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:53.303  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:42:55.553   291   291 E SMD     : DCD OFF,
,08-29 16:42:56.573  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:42:56.573  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:42:56.573  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:42:56.573  1015  1134 D BatteryService: stay LED for fully charged
08-29 16:42:56.573  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:42:56.583  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 16:42:56.583  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:42:56.593  1015  1015 I MotionRecognitionService: Plugged
08-29 16:42:56.593  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:42:56.593  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:42:56.593  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:42:56.593  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 16:42:56.593  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:42:56.593  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-29 16:42:56.593  3156  3259 D HeadsetStateMachine: Disconnected process message: 10,
,08-29 16:42:56.603  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:42:56.603  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:42:56.613  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:42:56.803  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:42:58.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:42:58.553   291   291 E SMD     : DCD OFF
,08-29 16:42:59.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:00.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:01.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:01.553   291   291 E SMD     : DCD OFF,
,08-29 16:43:02.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:03.343  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:43:03.503   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-29 16:43:04.553   291   291 E SMD     : DCD OFF
,08-29 16:43:06.633  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:06.643  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:43:06.643  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:43:06.643  1015  1487 D BatteryService: stay LED for fully charged
,08-29 16:43:06.643  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-29 16:43:06.643  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:43:06.643  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:43:06.643  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 16:43:06.643  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:43:06.653  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:43:06.653  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:43:06.663  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:43:06.663  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:43:06.673  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:43:06.673  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:43:06.673  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:06.673  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:06.673  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:07.553   291   291 E SMD     : DCD OFF,
,08-29 16:43:10.563   291   291 E SMD     : DCD OFF
,08-29 16:43:11.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:43:13.383  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:43:13.563   291   291 E SMD     : DCD OFF
,08-29 16:43:16.573   291   291 E SMD     : DCD OFF
,08-29 16:43:16.703  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:16.823  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:43:17.573  1015  1322 E Watchdog: !@Sync 9
,08-29 16:43:17.693  1015  1048 I PowerManagerService: [PWL] Off : 225s ago,
,08-29 16:43:19.563   291   291 E SMD     : DCD OFF
,08-29 16:43:22.573   291   291 E SMD     : DCD OFF,
,08-29 16:43:23.423  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:43:23.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:24.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:43:25.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:43:25.563   291   291 E SMD     : DCD OFF
,08-29 16:43:26.503   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:26.753  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:26.753  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:43:26.763  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:43:26.763  1015  1216 D BatteryService: stay LED for fully charged
,08-29 16:43:26.763  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-29 16:43:26.763  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:43:26.763  1015  1015 I MotionRecognitionService: Plugged
08-29 16:43:26.763  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:43:26.763  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:43:26.763  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:43:26.763  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:43:26.773  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-29 16:43:26.773  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:43:26.783  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:43:26.783  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:43:26.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:26.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:43:26.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:27.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:43:28.513   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-29 16:43:28.573   291   291 E SMD     : DCD OFF
,08-29 16:43:31.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:43:31.573   291   291 E SMD     : DCD OFF
,08-29 16:43:33.463  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:43:34.583   291   291 E SMD     : DCD OFF
,08-29 16:43:36.823  1015  1524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:36.823  1015  1524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:43:36.823  1015  1524 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:43:36.823  1015  1524 D BatteryService: stay LED for fully charged
08-29 16:43:36.823  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:43:36.823  1015  1015 I MotionRecognitionService: Plugged
08-29 16:43:36.823  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:43:36.833  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:43:36.833  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:43:36.833  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 16:43:36.833  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-29 16:43:36.833  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:43:36.833  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:43:36.833  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:43:36.853  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:43:36.853  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:43:36.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:43:36.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:36.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:37.573   291   291 E SMD     : DCD OFF
,08-29 16:43:40.573   291   291 E SMD     : DCD OFF
,08-29 16:43:43.493  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:43:43.573   291   291 E SMD     : DCD OFF
,08-29 16:43:44.553  1015  1085 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-29 16:43:44.553  1015  1084 D TimaService: TimaServiceHandler.handleMessage what =1
,08-29 16:43:44.553  1015  1085 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-29 16:43:44.553  1015  1085 I TLC_TIMA_PKM_initialize: initializing...
,08-29 16:43:44.553  1015  1085 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-29 16:43:44.553  1015  1085 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-29 16:43:44.553  1015  1085 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-29 16:43:44.553  1015  1085 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-29 16:43:44.553  1015  1085 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-29 16:43:44.553  1015  1085 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-29 16:43:44.553  1015  1085 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-29 16:43:44.553  1015  1085 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-29 16:43:44.563  1015  1085 D QSEECOMAPI: : App is not loaded in QSEE
,08-29 16:43:44.583  1015  1085 D QSEECOMAPI: : Loaded image: APP id = 13
,08-29 16:43:44.593  1015  1085 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-29 16:43:44.603  1015  1085 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-29 16:43:46.563  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-29 16:43:46.563  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-29 16:43:46.563  1015  1085 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:43:46.563  1015  1085 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:43:46.583   291   291 E SMD     : DCD OFF
,08-29 16:43:46.883  1015  1524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:47.583  1015  1322 E Watchdog: !@Sync 10
,08-29 16:43:49.583   291   291 E SMD     : DCD OFF
,08-29 16:43:51.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:43:52.593   291   291 E SMD     : DCD OFF
,08-29 16:43:53.513   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 16:43:53.513   318   318 I Atfwd_Daemon: result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 16:43:53.533  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:43:55.593   291   291 E SMD     : DCD OFF,
,08-29 16:43:56.863  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:43:56.943  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:43:56.943  1015  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:43:56.943  1015  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:43:56.943  1015  1496 D BatteryService: stay LED for fully charged
08-29 16:43:56.943  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:43:56.953  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:43:56.953  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:43:56.953  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:43:56.953  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:43:56.953  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:43:56.953  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:43:56.963  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:43:56.963  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:43:56.983  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:43:56.983  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:43:56.983  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:43:56.983  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:56.983  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:43:58.593   291   291 E SMD     : DCD OFF,
,08-29 16:44:01.593   291   291 E SMD     : DCD OFF,
,08-29 16:44:03.573  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:44:04.593   291   291 E SMD     : DCD OFF,
,08-29 16:44:07.003  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:07.003  1015  2093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:44:07.003  1015  2093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:44:07.003  1015  2093 D BatteryService: stay LED for fully charged
08-29 16:44:07.003  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:44:07.003  1015  1015 I MotionRecognitionService: Plugged
08-29 16:44:07.003  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:44:07.013  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:44:07.013  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:44:07.013  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:44:07.013  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:44:07.023  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:44:07.023  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:44:07.033  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:44:07.033  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:44:07.033  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:44:07.033  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:44:07.033  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:44:07.593   291   291 E SMD     : DCD OFF
,08-29 16:44:07.683  1015  1048 I PowerManagerService: [PWL] Off : 275s ago
,08-29 16:44:08.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:09.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:10.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:10.593   291   291 E SMD     : DCD OFF
,08-29 16:44:11.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:44:11.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:12.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:13.513   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 16:44:13.593   291   291 E SMD     : DCD OFF,
,08-29 16:44:13.613  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:44:16.603   291   291 E SMD     : DCD OFF,
,08-29 16:44:16.883  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:44:17.063  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:17.063  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:44:17.063  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:44:17.063  1015  1028 D BatteryService: stay LED for fully charged
,08-29 16:44:17.063  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:44:17.063  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:44:17.063  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:44:17.073  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:44:17.073  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:44:17.073  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:44:17.073  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:44:17.083  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:44:17.083  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:44:17.093  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-29 16:44:17.093  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:44:17.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:44:17.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:44:17.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:44:17.583  1015  1322 E Watchdog: !@Sync 11,
,08-29 16:44:18.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:19.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:19.593   291   291 E SMD     : DCD OFF,
,08-29 16:44:20.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:21.513   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:22.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:22.603   291   291 E SMD     : DCD OFF,
,08-29 16:44:23.523   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 16:44:23.653  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:44:25.603   291   291 E SMD     : DCD OFF,
,08-29 16:44:27.123  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:27.123  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:44:27.123  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:44:27.123  1015  1134 D BatteryService: stay LED for fully charged
,08-29 16:44:27.123  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:44:27.123  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:44:27.123  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:44:27.133  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:44:27.133  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:44:27.133  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:44:27.133  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:44:27.143  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:44:27.143  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:44:27.153  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:44:27.153  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:44:27.153  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:44:27.153  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:44:27.163  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:44:28.603   291   291 E SMD     : DCD OFF
,08-29 16:44:31.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:44:31.613   291   291 E SMD     : DCD OFF
,08-29 16:44:33.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:33.703  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:44:34.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:34.603   291   291 E SMD     : DCD OFF
,08-29 16:44:35.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:36.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:36.903  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:44:37.173  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:37.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:37.603   291   291 E SMD     : DCD OFF,
,08-29 16:44:38.523   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-29 16:44:40.613   291   291 E SMD     : DCD OFF,
,08-29 16:44:43.613   291   291 E SMD     : DCD OFF,
,08-29 16:44:43.743  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:44:46.613   291   291 E SMD     : DCD OFF,
,08-29 16:44:47.243  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:47.583  1015  1322 E Watchdog: !@Sync 12,
,08-29 16:44:49.623   291   291 E SMD     : DCD OFF,
,08-29 16:44:51.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 16:44:52.623   291   291 E SMD     : DCD OFF,
,08-29 16:44:53.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:53.783  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:44:54.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:55.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:55.613   291   291 E SMD     : DCD OFF,
,08-29 16:44:56.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:44:56.923  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:44:57.303  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:44:57.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:44:58.523   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 16:44:58.623   291   291 E SMD     : DCD OFF,
,08-29 16:44:59.993  1015  1094 V AlarmManager: waitForAlarm result :8,
08-29 16:44:59.993  1015  1094 V AlarmManager: No more alarm at this time.nowELAPSED=390550 batch.start=509555
,08-29 16:44:59.993  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
08-29 16:44:59.993  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 16:45:00.003  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,08-29 16:45:00.003  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 16:45:00.013  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
08-29 16:45:00.013  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-29 16:45:00.013  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 16:45:00.013  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-29 16:45:00.033  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:45:00.033  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:45:00.033  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:45:00.073  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:45:01.623   291   291 E SMD     : DCD OFF,
,08-29 16:45:02.693  1015  1048 I PowerManagerService: [PWL] Off : 330s ago,
,08-29 16:45:03.823  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:45:04.623   291   291 E SMD     : DCD OFF,
,08-29 16:45:07.363  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:45:07.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:10.633   291   291 E SMD     : DCD OFF
,08-29 16:45:11.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:45:13.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:13.863  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:45:16.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:16.943  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:45:17.423  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:45:17.583  1015  1322 E Watchdog: !@Sync 13,
,08-29 16:45:18.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:45:19.523   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:45:19.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:20.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:45:21.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:45:22.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:45:22.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:23.533   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-29 16:45:23.903  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:45:25.633   291   291 E SMD     : DCD OFF,
,08-29 16:45:27.483  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:45:27.483  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:45:27.483  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:45:27.483  1015  1495 D BatteryService: stay LED for fully charged
,08-29 16:45:27.483  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:45:27.493  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:45:27.493  1015  1015 I MotionRecognitionService: Plugged
08-29 16:45:27.493  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:45:27.493  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:45:27.493  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:45:27.493  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:45:27.503  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:45:27.503  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:45:27.513  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:45:27.513  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:45:27.513  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:27.513  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:27.523  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:28.643   291   291 E SMD     : DCD OFF
,08-29 16:45:31.393  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:45:31.633   291   291 E SMD     : DCD OFF
,08-29 16:45:33.943  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:45:34.643   291   291 E SMD     : DCD OFF
,08-29 16:45:36.963  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:45:37.543  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:45:37.543  1015  3997 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:45:37.543  1015  3997 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:45:37.543  1015  3997 D BatteryService: stay LED for fully charged
08-29 16:45:37.543  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:45:37.553  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:45:37.553  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:45:37.553  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:45:37.553  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:45:37.563  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:45:37.563  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:45:37.573  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:45:37.573  3156  3259 D HeadsetStateMachine: Disconnected process message: 10,
,08-29 16:45:37.583  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:45:37.583  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:45:37.583  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:37.583  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:37.583  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:37.643   291   291 E SMD     : DCD OFF
,08-29 16:45:40.643   291   291 E SMD     : DCD OFF
,08-29 16:45:43.643   291   291 E SMD     : DCD OFF,
,08-29 16:45:43.983  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:45:46.653   291   291 E SMD     : DCD OFF,
,08-29 16:45:47.573  1015  1322 E Watchdog: !@Sync 14,
,08-29 16:45:47.603  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:45:47.603  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:45:47.603  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:45:47.603  1015  1487 D BatteryService: stay LED for fully charged
08-29 16:45:47.603  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-29 16:45:47.603  1015  1015 I MotionRecognitionService: Plugged
08-29 16:45:47.613  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:45:47.603  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:45:47.613  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:45:47.613  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:45:47.613  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:45:47.613  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:45:47.613  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:45:47.633  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:45:47.633  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:45:47.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:47.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:45:47.633  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:48.533   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 16:45:48.533   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 16:45:49.653   291   291 E SMD     : DCD OFF
,08-29 16:45:51.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:45:52.643   291   291 E SMD     : DCD OFF
,08-29 16:45:54.023  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:45:55.653   291   291 E SMD     : DCD OFF
,08-29 16:45:56.983  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:45:57.663  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:45:57.663  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:45:57.663  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:45:57.663  1015  1489 D BatteryService: stay LED for fully charged
08-29 16:45:57.663  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:45:57.663  1015  1015 I MotionRecognitionService: Plugged
08-29 16:45:57.663  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:45:57.673  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:45:57.673  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:45:57.673  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:45:57.673  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:45:57.683  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:45:57.683  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:45:57.693  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:45:57.693  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:45:57.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:45:57.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:57.693  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:45:58.653   291   291 E SMD     : DCD OFF
,08-29 16:45:59.993  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 16:46:01.653   291   291 E SMD     : DCD OFF,
,08-29 16:46:02.703  1015  1048 I PowerManagerService: [PWL] Off : 390s ago,
,08-29 16:46:04.063  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:46:04.663   291   291 E SMD     : DCD OFF
,08-29 16:46:07.663   291   291 E SMD     : DCD OFF,
,08-29 16:46:07.723  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:46:07.723  1015  3998 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:46:07.723  1015  3998 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:46:07.723  1015  3998 D BatteryService: stay LED for fully charged
08-29 16:46:07.723  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:46:07.733  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:46:07.733  1015  1015 I MotionRecognitionService: Plugged
08-29 16:46:07.733  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:46:07.733  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:46:07.733  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 16:46:07.733  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:46:07.743  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:46:07.743  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:46:07.763  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:46:07.763  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:46:07.763  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:07.763  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:46:07.763  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:08.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:09.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:10.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:10.653   291   291 E SMD     : DCD OFF
,08-29 16:46:11.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:46:11.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:12.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:13.533   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 16:46:13.663   291   291 E SMD     : DCD OFF,
,08-29 16:46:14.113  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:46:16.663   291   291 E SMD     : DCD OFF,
,08-29 16:46:17.003  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:46:17.583  1015  1322 E Watchdog: !@Sync 15,
,08-29 16:46:17.783  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:46:17.783  1015  2093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:46:17.783  1015  2093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:46:17.783  1015  2093 D BatteryService: stay LED for fully charged
08-29 16:46:17.783  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:46:17.793  1015  1015 I MotionRecognitionService: Plugged
08-29 16:46:17.793  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:46:17.793  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:46:17.793  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:46:17.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 16:46:17.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:46:17.803  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:46:17.803  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:46:17.823  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:46:17.823  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:46:17.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:46:17.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:17.823  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:18.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:19.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:19.663   291   291 E SMD     : DCD OFF,
,08-29 16:46:20.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:21.533   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:22.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:22.673   291   291 E SMD     : DCD OFF,
,08-29 16:46:23.543   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 16:46:24.153  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:46:25.673   291   291 E SMD     : DCD OFF,
,08-29 16:46:27.843  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:46:28.673   291   291 E SMD     : DCD OFF
,08-29 16:46:31.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:46:31.673   291   291 E SMD     : DCD OFF
,08-29 16:46:33.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:34.193  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:46:34.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:34.673   291   291 E SMD     : DCD OFF
,08-29 16:46:35.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:36.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:36.653   315   315 I bootchecker: bootchecker wake up!!,
,08-29 16:46:37.023  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:46:37.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:37.673   291   291 E SMD     : DCD OFF,
,08-29 16:46:37.903  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:46:38.553   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-29 16:46:40.673   291   291 E SMD     : DCD OFF,
,08-29 16:46:43.673   291   291 E SMD     : DCD OFF,
,08-29 16:46:44.233  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:46:46.683   291   291 E SMD     : DCD OFF
,08-29 16:46:47.573  1015  1322 E Watchdog: !@Sync 16
,08-29 16:46:47.963  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:46:49.673   291   291 E SMD     : DCD OFF
,08-29 16:46:51.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:46:52.683   291   291 E SMD     : DCD OFF,
,08-29 16:46:53.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:54.283  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:46:54.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:55.543   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:46:55.683   291   291 E SMD     : DCD OFF,
,08-29 16:46:56.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:57.043  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:46:57.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:46:58.023  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:46:58.023  1015  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:46:58.023  1015  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:46:58.023  1015  1484 D BatteryService: stay LED for fully charged
08-29 16:46:58.023  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:46:58.023  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:46:58.023  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:46:58.023  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:46:58.023  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:46:58.033  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:46:58.033  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:46:58.033  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:46:58.033  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:46:58.053  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:46:58.053  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:46:58.053  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:46:58.053  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:58.053  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:46:58.553   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 16:46:58.683   291   291 E SMD     : DCD OFF
,08-29 16:46:59.003  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 16:46:59.003  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 16:46:59.003  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 16:46:59.013  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 16:46:59.013  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 16:46:59.023  1015  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-29 16:46:59.023  1015  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,08-29 16:46:59.023  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:46:59.023  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-29 16:46:59.023  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 16:46:59.023  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-29 16:46:59.053  1015  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,08-29 16:46:59.053  1015  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,08-29 16:46:59.063  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:46:59.073  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:46:59.073  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:46:59.083  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:46:59.353  1015  1524 I art     : Explicit concurrent mark sweep GC freed 56381(4MB) AllocSpace objects, 157(2MB) LOS objects, 33% free, 24MB/36MB, paused 6.099ms total 195.537ms
,08-29 16:46:59.383  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,08-29 16:46:59.463  1015  2093 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 16:46:59.463  1015  2093 W ActivityManager: userId = 0, bbcId = -10000
08-29 16:46:59.463  1015  2093 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 16:46:59.463  1015  2093 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,08-29 16:46:59.993  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 16:47:01.693   291   291 E SMD     : DCD OFF,
,08-29 16:47:04.323  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:47:04.693   291   291 E SMD     : DCD OFF
,08-29 16:47:07.693   291   291 E SMD     : DCD OFF,
,08-29 16:47:07.713  1015  1048 I PowerManagerService: [PWL] Off : 455s ago,
,08-29 16:47:08.083  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:10.693   291   291 E SMD     : DCD OFF,
,08-29 16:47:11.403  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:47:13.693   291   291 E SMD     : DCD OFF,
,08-29 16:47:14.363  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:47:16.693   291   291 E SMD     : DCD OFF,
,08-29 16:47:17.063  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:47:17.573  1015  1322 E Watchdog: !@Sync 17,
,08-29 16:47:18.143  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:18.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 16:47:19.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:47:19.703   291   291 E SMD     : DCD OFF,
,08-29 16:47:20.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:47:21.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:47:22.553   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 16:47:22.703   291   291 E SMD     : DCD OFF,
,08-29 16:47:23.553   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-29 16:47:24.403  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:47:25.703   291   291 E SMD     : DCD OFF,
,08-29 16:47:28.203  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:28.203  1015  3998 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:47:28.203  1015  3998 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:47:28.203  1015  3998 D BatteryService: stay LED for fully charged
08-29 16:47:28.203  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:47:28.213  1015  1015 I MotionRecognitionService: Plugged
08-29 16:47:28.213  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:47:28.213  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:47:28.213  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:47:28.213  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:47:28.213  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:47:28.213  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:47:28.213  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:47:28.233  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:47:28.233  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:47:28.233  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:47:28.233  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:47:28.233  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:28.703   291   291 E SMD     : DCD OFF
,08-29 16:47:29.063  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 16:47:29.073  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 16:47:29.073  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 16:47:29.073  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 16:47:29.083  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 16:47:29.093  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:47:29.093  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-29 16:47:29.093  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 16:47:29.093  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-29 16:47:29.123  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:47:29.133  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:47:29.133  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:47:29.143  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 16:47:31.413  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:47:31.703   291   291 E SMD     : DCD OFF,
,08-29 16:47:34.453  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:47:34.703   291   291 E SMD     : DCD OFF,
,08-29 16:47:37.083  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:47:37.703   291   291 E SMD     : DCD OFF
,08-29 16:47:38.263  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:38.263  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:47:38.263  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:47:38.263  1015  1487 D BatteryService: stay LED for fully charged
08-29 16:47:38.263  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 16:47:38.273  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:47:38.263  1015  1015 I MotionRecognitionService: Plugged
08-29 16:47:38.273  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:47:38.263  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:47:38.273  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:47:38.273  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:47:38.273  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 16:47:38.273  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:47:38.273  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:47:38.283  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:47:38.293  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:38.293  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:47:38.293  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:40.713   291   291 E SMD     : DCD OFF,
,08-29 16:47:43.713   291   291 E SMD     : DCD OFF,
,08-29 16:47:44.493  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:47:46.713   291   291 E SMD     : DCD OFF,
,08-29 16:47:47.583  1015  1322 E Watchdog: !@Sync 18,
,08-29 16:47:48.323  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:48.323  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:47:48.323  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:47:48.323  1015  1027 D BatteryService: stay LED for fully charged
08-29 16:47:48.323  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:47:48.323  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:47:48.323  1015  1015 I MotionRecognitionService: Plugged
08-29 16:47:48.323  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:47:48.323  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:47:48.333  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:47:48.333  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:47:48.333  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:47:48.343  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:47:48.353  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:47:48.353  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:47:48.353  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:47:48.353  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:48.353  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:48.553   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 16:47:48.553   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 16:47:49.713   291   291 E SMD     : DCD OFF
,08-29 16:47:51.413  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:47:52.713   291   291 E SMD     : DCD OFF,
,08-29 16:47:54.533  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:47:55.713   291   291 E SMD     : DCD OFF,
,08-29 16:47:57.103  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:47:58.373  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:47:58.373  1015  3997 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:47:58.373  1015  3997 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:47:58.383  1015  3997 D BatteryService: stay LED for fully charged
08-29 16:47:58.383  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:47:58.383  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:47:58.383  1015  1015 I MotionRecognitionService: Plugged
08-29 16:47:58.383  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 16:47:58.383  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:47:58.383  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:47:58.383  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:47:58.393  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:47:58.393  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:47:58.413  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:47:58.413  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:47:58.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:47:58.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:58.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:47:58.713   291   291 E SMD     : DCD OFF
,08-29 16:47:59.993  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 16:48:01.713   291   291 E SMD     : DCD OFF,
,08-29 16:48:04.583  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:48:04.713   291   291 E SMD     : DCD OFF,
,08-29 16:48:07.713   291   291 E SMD     : DCD OFF,
,08-29 16:48:08.443  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:08.443  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:48:08.443  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:48:08.443  1015  1216 D BatteryService: stay LED for fully charged
08-29 16:48:08.443  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:48:08.443  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:48:08.443  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:48:08.443  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:48:08.443  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:48:08.453  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:48:08.453  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:48:08.453  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:48:08.463  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:48:08.473  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:48:08.473  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:48:08.473  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:48:08.473  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:48:08.473  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:48:10.723   291   291 E SMD     : DCD OFF,
,08-29 16:48:11.413  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:48:13.553   318   318 I Atfwd_Daemon: Stop the daemon....,
,08-29 16:48:13.723   291   291 E SMD     : DCD OFF,
,08-29 16:48:14.623  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:48:16.733   291   291 E SMD     : DCD OFF,
,08-29 16:48:17.123  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:48:17.583  1015  1322 E Watchdog: !@Sync 19,
,08-29 16:48:17.713  1015  1048 I PowerManagerService: [PWL] Off : 525s ago,
,08-29 16:48:18.503  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:19.733   291   291 E SMD     : DCD OFF
,08-29 16:48:22.733   291   291 E SMD     : DCD OFF,
,08-29 16:48:24.673  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:48:25.723   291   291 E SMD     : DCD OFF,
,08-29 16:48:28.563  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:28.563  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:48:28.563  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:48:28.563  1015  1487 D BatteryService: stay LED for fully charged
08-29 16:48:28.563  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:48:28.563  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:48:28.563  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:48:28.563  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:48:28.563  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:48:28.573  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 16:48:28.573  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:48:28.573  1015  1015 I MotionRecognitionService: Plugged
08-29 16:48:28.573  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:48:28.573  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:48:28.573  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:48:28.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-29 16:48:28.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:48:28.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:48:28.733   291   291 E SMD     : DCD OFF,
,08-29 16:48:31.413  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:48:31.733   291   291 E SMD     : DCD OFF,
,08-29 16:48:34.723  1015  3363 D SSRM:n  : SIOP:: AP = 300
,08-29 16:48:34.733   291   291 E SMD     : DCD OFF
,08-29 16:48:37.143  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:48:37.743   291   291 E SMD     : DCD OFF,
,08-29 16:48:38.613  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:40.743   291   291 E SMD     : DCD OFF
,08-29 16:48:43.743   291   291 E SMD     : DCD OFF,
,08-29 16:48:44.553  1015  1085 D TimaService: TIMA: TimaService scheduler is intialized. ,
08-29 16:48:44.553  1015  1085 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-29 16:48:44.553  1015  1084 D TimaService: TimaServiceHandler.handleMessage what =1
,08-29 16:48:44.763  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:48:45.393  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-29 16:48:45.393  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-29 16:48:45.393  1015  1085 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:48:45.393  1015  1085 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:48:46.743   291   291 E SMD     : DCD OFF,
,08-29 16:48:47.583  1015  1322 E Watchdog: !@Sync 20,
,08-29 16:48:48.673  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:49.743   291   291 E SMD     : DCD OFF,
,08-29 16:48:51.413  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:48:52.753   291   291 E SMD     : DCD OFF,
,08-29 16:48:54.783  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:48:55.753   291   291 E SMD     : DCD OFF,
,08-29 16:48:57.163  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:48:58.733  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:48:58.743   291   291 E SMD     : DCD OFF
,08-29 16:49:01.753   291   291 E SMD     : DCD OFF,
,08-29 16:49:04.753   291   291 E SMD     : DCD OFF,
,08-29 16:49:04.813  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:49:07.753   291   291 E SMD     : DCD OFF,
,08-29 16:49:08.803  1015  1524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-29 16:49:08.803  1015  1524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:49:08.803  1015  1524 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:49:08.803  1015  1524 D BatteryService: stay LED for fully charged
,08-29 16:49:08.803  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 16:49:08.803  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:49:08.803  1015  1015 I MotionRecognitionService: Plugged
08-29 16:49:08.803  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:49:08.803  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:49:08.813  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 16:49:08.813  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:49:08.823  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:49:08.823  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:49:08.833  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:49:08.833  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:49:08.833  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:49:08.833  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:49:08.833  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:49:10.753   291   291 E SMD     : DCD OFF
,08-29 16:49:11.423  1015  3392 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 16:49:13.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:14.853  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:49:16.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:17.183  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:49:17.583  1015  1322 E Watchdog: !@Sync 21,
,08-29 16:49:18.853  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 16:49:18.853  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:49:18.853  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:49:18.853  1015  1487 D BatteryService: stay LED for fully charged
08-29 16:49:18.853  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:49:18.863  1015  1015 I MotionRecognitionService: Plugged
08-29 16:49:18.863  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:49:18.863  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:49:18.863  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:49:18.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:49:18.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:49:18.873  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:49:18.873  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:49:18.893  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:49:18.893  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:49:18.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:49:18.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:49:18.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:49:19.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:22.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:24.893  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:49:25.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:28.763   291   291 E SMD     : DCD OFF,
,08-29 16:49:28.923  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:49:31.773   291   291 E SMD     : DCD OFF
,08-29 16:49:32.733  1015  1048 I PowerManagerService: [PWL] Off : 600s ago
,08-29 16:49:34.773   291   291 E SMD     : DCD OFF
,08-29 16:49:34.933  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:49:37.203  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:49:37.773   291   291 E SMD     : DCD OFF,
,08-29 16:49:38.983  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:49:40.773   291   291 E SMD     : DCD OFF,
,08-29 16:49:43.773   291   291 E SMD     : DCD OFF,
,08-29 16:49:44.973  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:49:46.773   291   291 E SMD     : DCD OFF,
,08-29 16:49:47.583  1015  1322 E Watchdog: !@Sync 22,
,08-29 16:49:49.043  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:49:49.783   291   291 E SMD     : DCD OFF,
,08-29 16:49:52.783   291   291 E SMD     : DCD OFF,
,08-29 16:49:55.023  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:49:55.783   291   291 E SMD     : DCD OFF,
,08-29 16:49:57.223  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:49:58.783   291   291 E SMD     : DCD OFF,
,08-29 16:49:59.103  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:01.783   291   291 E SMD     : DCD OFF,
,08-29 16:50:04.783   291   291 E SMD     : DCD OFF,
,08-29 16:50:05.063  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:50:07.793   291   291 E SMD     : DCD OFF,
,08-29 16:50:09.163  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:09.163  1015  2093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:50:09.163  1015  2093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:50:09.163  1015  2093 D BatteryService: stay LED for fully charged
,08-29 16:50:09.163  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:50:09.173  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:50:09.173  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:50:09.173  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:50:09.173  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:50:09.173  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:50:09.173  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:50:09.183  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:50:09.183  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:50:09.193  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:50:09.193  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:50:09.193  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:50:09.193  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:09.193  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:10.793   291   291 E SMD     : DCD OFF,
,08-29 16:50:13.793   291   291 E SMD     : DCD OFF
,08-29 16:50:15.113  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:50:16.793   291   291 E SMD     : DCD OFF,
,08-29 16:50:17.243  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:50:17.583  1015  1322 E Watchdog: !@Sync 23,
,08-29 16:50:19.223  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:19.223  1015  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:50:19.223  1015  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:50:19.223  1015  1496 D BatteryService: stay LED for fully charged
,08-29 16:50:19.223  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:50:19.223  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:50:19.223  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:50:19.233  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:50:19.233  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:50:19.233  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:50:19.233  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:50:19.243  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:50:19.243  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:50:19.253  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-29 16:50:19.253  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:50:19.253  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:50:19.253  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:19.253  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:19.793   291   291 E SMD     : DCD OFF
,08-29 16:50:22.793   291   291 E SMD     : DCD OFF,
,08-29 16:50:25.153  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:50:25.803   291   291 E SMD     : DCD OFF,
,08-29 16:50:28.793   291   291 E SMD     : DCD OFF,
,08-29 16:50:29.273  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:29.283  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:50:29.283  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:50:29.283  1015  1028 D BatteryService: stay LED for fully charged
,08-29 16:50:29.283  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:50:29.283  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:50:29.283  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:50:29.283  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:50:29.283  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:50:29.293  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:50:29.293  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:50:29.293  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:50:29.293  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:50:29.313  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:50:29.313  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:50:29.313  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:29.313  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:50:29.313  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:31.803   291   291 E SMD     : DCD OFF,
,08-29 16:50:34.803   291   291 E SMD     : DCD OFF
,08-29 16:50:35.193  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:50:37.263  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:50:37.803   291   291 E SMD     : DCD OFF,
,08-29 16:50:39.343  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:39.343  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:50:39.343  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:50:39.343  1015  1134 D BatteryService: stay LED for fully charged
,08-29 16:50:39.343  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:50:39.343  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:50:39.343  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:50:39.353  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:50:39.353  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:50:39.353  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:50:39.353  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:50:39.363  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-29 16:50:39.363  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:50:39.373  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:50:39.373  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:50:39.373  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:50:39.373  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:39.373  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:50:40.803   291   291 E SMD     : DCD OFF
,08-29 16:50:43.813   291   291 E SMD     : DCD OFF,
,08-29 16:50:45.243  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:50:46.813   291   291 E SMD     : DCD OFF
,08-29 16:50:47.593  1015  1322 E Watchdog: !@Sync 24
,08-29 16:50:49.403  1015  1524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:50:49.813   291   291 E SMD     : DCD OFF,
,08-29 16:50:52.753  1015  1048 I PowerManagerService: [PWL] Off : 680s ago,
,08-29 16:50:52.813   291   291 E SMD     : DCD OFF,
,08-29 16:50:55.283  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:50:55.813   291   291 E SMD     : DCD OFF,
,08-29 16:50:57.283  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:50:58.813   291   291 E SMD     : DCD OFF,
,08-29 16:50:59.463  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:01.823   291   291 E SMD     : DCD OFF,
,08-29 16:51:04.823   291   291 E SMD     : DCD OFF,
,08-29 16:51:05.333  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:51:07.823   291   291 E SMD     : DCD OFF
,08-29 16:51:09.523  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:10.823   291   291 E SMD     : DCD OFF,
,08-29 16:51:13.823   291   291 E SMD     : DCD OFF,
,08-29 16:51:15.383  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:51:16.833   291   291 E SMD     : DCD OFF,
,08-29 16:51:17.303  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:51:17.583  1015  1322 E Watchdog: !@Sync 25,
,08-29 16:51:19.583  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:19.833   291   291 E SMD     : DCD OFF,
,08-29 16:51:22.833   291   291 E SMD     : DCD OFF,
,08-29 16:51:25.423  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:51:25.823   291   291 E SMD     : DCD OFF,
,08-29 16:51:28.833   291   291 E SMD     : DCD OFF,
,08-29 16:51:29.643  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:31.833   291   291 E SMD     : DCD OFF,
,08-29 16:51:34.843   291   291 E SMD     : DCD OFF,
,08-29 16:51:35.473  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:51:37.323  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:51:37.843   291   291 E SMD     : DCD OFF,
,08-29 16:51:39.703  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:40.843   291   291 E SMD     : DCD OFF,
,08-29 16:51:43.843   291   291 E SMD     : DCD OFF
,08-29 16:51:45.533  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:51:46.843   291   291 E SMD     : DCD OFF
,08-29 16:51:47.593  1015  1322 E Watchdog: !@Sync 26,
,08-29 16:51:49.763  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:51:49.853   291   291 E SMD     : DCD OFF
,08-29 16:51:51.573  1015  1094 V AlarmManager: waitForAlarm result :8,
,08-29 16:51:52.853   291   291 E SMD     : DCD OFF,
,08-29 16:51:55.573  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:51:55.853   291   291 E SMD     : DCD OFF,
,08-29 16:51:57.343  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:51:58.853   291   291 E SMD     : DCD OFF,
,08-29 16:51:59.823  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:01.853   291   291 E SMD     : DCD OFF,
,08-29 16:52:04.853   291   291 E SMD     : DCD OFF,
,08-29 16:52:05.623  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:52:07.853   291   291 E SMD     : DCD OFF
,08-29 16:52:09.883  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:10.863   291   291 E SMD     : DCD OFF
,08-29 16:52:13.863   291   291 E SMD     : DCD OFF
,08-29 16:52:15.673  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:52:16.863   291   291 E SMD     : DCD OFF,
,08-29 16:52:17.373  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:52:17.593  1015  1322 E Watchdog: !@Sync 27,
,08-29 16:52:17.813  1015  1048 I PowerManagerService: [PWL] Off : 765s ago,
,08-29 16:52:19.863   291   291 E SMD     : DCD OFF,
,08-29 16:52:19.953  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:22.863   291   291 E SMD     : DCD OFF
,08-29 16:52:25.723  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:52:25.873   291   291 E SMD     : DCD OFF,
,08-29 16:52:28.873   291   291 E SMD     : DCD OFF,
,08-29 16:52:30.013  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:31.873   291   291 E SMD     : DCD OFF,
,08-29 16:52:34.873   291   291 E SMD     : DCD OFF
,08-29 16:52:35.773  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:52:37.383  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:52:37.873   291   291 E SMD     : DCD OFF,
,08-29 16:52:40.073  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:40.073  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:52:40.073  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:52:40.073  1015  1487 D BatteryService: stay LED for fully charged
,08-29 16:52:40.073  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:52:40.073  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:52:40.083  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:52:40.083  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:52:40.083  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:52:40.083  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:52:40.093  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
08-29 16:52:40.093  1015  1015 I MotionRecognitionService: Plugged
08-29 16:52:40.093  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:52:40.103  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:52:40.103  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:52:40.103  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:52:40.103  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:52:40.103  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:52:40.873   291   291 E SMD     : DCD OFF
,08-29 16:52:43.873   291   291 E SMD     : DCD OFF
,08-29 16:52:45.823  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:52:46.883   291   291 E SMD     : DCD OFF
,08-29 16:52:47.593  1015  1322 E Watchdog: !@Sync 28
,08-29 16:52:49.883   291   291 E SMD     : DCD OFF
,08-29 16:52:50.133  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:52:52.883   291   291 E SMD     : DCD OFF
,08-29 16:52:55.873  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:52:55.883   291   291 E SMD     : DCD OFF,
,08-29 16:52:57.403  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:52:58.883   291   291 E SMD     : DCD OFF,
,08-29 16:53:00.193  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:01.893   291   291 E SMD     : DCD OFF
,08-29 16:53:04.893   291   291 E SMD     : DCD OFF,
,08-29 16:53:05.923  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:53:07.893   291   291 E SMD     : DCD OFF,
,08-29 16:53:10.253  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:10.893   291   291 E SMD     : DCD OFF
,08-29 16:53:13.903   291   291 E SMD     : DCD OFF
,08-29 16:53:15.973  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:53:16.903   291   291 E SMD     : DCD OFF
,08-29 16:53:17.423  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:53:17.593  1015  1322 E Watchdog: !@Sync 29
,08-29 16:53:19.903   291   291 E SMD     : DCD OFF,
,08-29 16:53:20.313  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:22.903   291   291 E SMD     : DCD OFF
,08-29 16:53:25.903   291   291 E SMD     : DCD OFF
,08-29 16:53:26.023  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:53:28.913   291   291 E SMD     : DCD OFF,
,08-29 16:53:30.373  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:31.913   291   291 E SMD     : DCD OFF,
,08-29 16:53:34.913   291   291 E SMD     : DCD OFF,
,08-29 16:53:36.073  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:53:37.443  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:53:37.913   291   291 E SMD     : DCD OFF,
,08-29 16:53:40.433  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:40.913   291   291 E SMD     : DCD OFF
,08-29 16:53:43.913   291   291 E SMD     : DCD OFF,
,08-29 16:53:44.553  1015  1085 D TimaService: TIMA: TimaService scheduler is intialized. ,
08-29 16:53:44.553  1015  1085 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-29 16:53:44.553  1015  1084 D TimaService: TimaServiceHandler.handleMessage what =1
,08-29 16:53:46.123  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:53:46.503  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-29 16:53:46.503  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-29 16:53:46.513  1015  1085 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:53:46.513  1015  1085 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:53:46.923   291   291 E SMD     : DCD OFF
,08-29 16:53:47.593  1015  1322 E Watchdog: !@Sync 30,
,08-29 16:53:47.813  1015  1048 I PowerManagerService: [PWL] Off : 855s ago,
,08-29 16:53:49.923   291   291 E SMD     : DCD OFF,
,08-29 16:53:50.493  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:53:52.923   291   291 E SMD     : DCD OFF,
,08-29 16:53:55.923   291   291 E SMD     : DCD OFF,
,08-29 16:53:56.173  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:53:57.453  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:53:58.923   291   291 E SMD     : DCD OFF,
,08-29 16:54:00.553  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:54:01.923   291   291 E SMD     : DCD OFF
,08-29 16:54:04.933   291   291 E SMD     : DCD OFF
,08-29 16:54:06.193  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:54:07.933   291   291 E SMD     : DCD OFF,
,08-29 16:54:10.613  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:54:10.933   291   291 E SMD     : DCD OFF
,08-29 16:54:13.933   291   291 E SMD     : DCD OFF,
,08-29 16:54:16.253  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:54:16.933   291   291 E SMD     : DCD OFF,
,08-29 16:54:17.473  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:54:17.593  1015  1322 E Watchdog: !@Sync 31,
,08-29 16:54:19.933   291   291 E SMD     : DCD OFF,
,08-29 16:54:20.673  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:54:22.943   291   291 E SMD     : DCD OFF,
,08-29 16:54:25.943   291   291 E SMD     : DCD OFF,
,08-29 16:54:26.293  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:54:28.943   291   291 E SMD     : DCD OFF,
,08-29 16:54:30.733  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:54:31.943   291   291 E SMD     : DCD OFF,
,08-29 16:54:34.943   291   291 E SMD     : DCD OFF
,08-29 16:54:36.323  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:54:37.493  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:54:37.943   291   291 E SMD     : DCD OFF,
,08-29 16:54:40.793  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:54:40.953   291   291 E SMD     : DCD OFF
,08-29 16:54:43.953   291   291 E SMD     : DCD OFF,
,08-29 16:54:46.363  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:54:46.953   291   291 E SMD     : DCD OFF,
,08-29 16:54:47.593  1015  1322 E Watchdog: !@Sync 32,
,08-29 16:54:49.953   291   291 E SMD     : DCD OFF,
,08-29 16:54:50.853  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:54:50.853  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:54:50.853  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:54:50.853  1015  1495 D BatteryService: stay LED for fully charged
,08-29 16:54:50.853  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:54:50.863  1015  1015 I MotionRecognitionService: Plugged
08-29 16:54:50.863  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:54:50.863  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:54:50.863  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:54:50.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:54:50.863  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:54:50.873  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:54:50.873  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:54:50.883  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:54:50.883  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:54:50.883  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:54:50.883  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:54:50.893  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:54:52.953   291   291 E SMD     : DCD OFF,
,08-29 16:54:55.953   291   291 E SMD     : DCD OFF,
,08-29 16:54:56.413  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:54:57.513  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:54:58.963   291   291 E SMD     : DCD OFF,
,08-29 16:55:00.913  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:01.953   291   291 E SMD     : DCD OFF,
,08-29 16:55:04.963   291   291 E SMD     : DCD OFF,
,08-29 16:55:06.433  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:55:07.963   291   291 E SMD     : DCD OFF,
,08-29 16:55:10.963   291   291 E SMD     : DCD OFF
,08-29 16:55:10.973  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:13.963   291   291 E SMD     : DCD OFF,
,08-29 16:55:16.473  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:55:16.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:17.533  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:55:17.593  1015  1322 E Watchdog: !@Sync 33,
,08-29 16:55:19.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:21.033  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:22.853  1015  1048 I PowerManagerService: [PWL] Off : 951s ago,
,08-29 16:55:22.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:25.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:26.533  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:55:28.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:31.093  1015  1524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:31.973   291   291 E SMD     : DCD OFF,
,08-29 16:55:34.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:36.553  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:55:37.553  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:55:37.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:40.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:41.153  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:43.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:46.593  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:55:46.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:47.593  1015  1322 E Watchdog: !@Sync 34,
,08-29 16:55:49.983   291   291 E SMD     : DCD OFF,
,08-29 16:55:51.213  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:55:52.993   291   291 E SMD     : DCD OFF,
,08-29 16:55:55.993   291   291 E SMD     : DCD OFF,
,08-29 16:55:56.653  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:55:57.573  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:55:58.983   291   291 E SMD     : DCD OFF,
,08-29 16:56:01.273  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:01.993   291   291 E SMD     : DCD OFF,
,08-29 16:56:04.993   291   291 E SMD     : DCD OFF,
,08-29 16:56:06.663  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:56:07.993   291   291 E SMD     : DCD OFF,
,08-29 16:56:11.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:11.333  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:14.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:16.713  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:56:17.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:17.593  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
08-29 16:56:17.593  1015  1322 E Watchdog: !@Sync 35
,08-29 16:56:20.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:21.393  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:23.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:26.003   291   291 E SMD     : DCD OFF,
,08-29 16:56:26.763  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:56:29.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:31.453  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:31.453  1015  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:56:31.453  1015  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:56:31.453  1015  1484 D BatteryService: stay LED for fully charged
,08-29 16:56:31.453  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:56:31.463  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:56:31.463  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:56:31.463  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:56:31.463  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:56:31.473  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:56:31.473  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:56:31.473  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:56:31.473  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:56:31.483  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:56:31.483  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:56:31.483  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:56:31.483  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:56:31.493  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:56:32.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:35.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:36.793  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:56:37.613  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:56:38.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:41.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:41.513  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:44.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:46.843  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:56:47.013   291   291 E SMD     : DCD OFF,
,08-29 16:56:47.593  1015  1322 E Watchdog: !@Sync 36,
,08-29 16:56:50.023   291   291 E SMD     : DCD OFF,
,08-29 16:56:51.573  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:56:53.023   291   291 E SMD     : DCD OFF,
,08-29 16:56:56.023   291   291 E SMD     : DCD OFF,
,08-29 16:56:56.893  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:56:57.633  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:56:59.023   291   291 E SMD     : DCD OFF,
,08-29 16:57:01.633  1015  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:02.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:02.883  1015  1048 I PowerManagerService: [PWL] Off : 1051s ago,
,08-29 16:57:05.033   291   291 E SMD     : DCD OFF
,08-29 16:57:06.913  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:57:08.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:11.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:11.693  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:11.693  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 16:57:11.703  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:57:11.703  1015  1495 D BatteryService: stay LED for fully charged
08-29 16:57:11.703  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-29 16:57:11.703  1015  1015 I MotionRecognitionService: Plugged
08-29 16:57:11.703  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:57:11.703  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:57:11.703  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:57:11.703  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:57:11.703  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:57:11.713  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:57:11.713  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:57:11.733  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:57:11.733  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:57:11.733  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:11.733  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:11.733  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:14.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:16.963  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:57:17.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:17.593  1015  1322 E Watchdog: !@Sync 37,
,08-29 16:57:17.653  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:57:20.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:21.753  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:21.753  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:57:21.753  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:57:21.753  1015  1487 D BatteryService: stay LED for fully charged
08-29 16:57:21.753  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:57:21.763  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:57:21.763  1015  1015 I MotionRecognitionService: Plugged,
08-29 16:57:21.763  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 16:57:21.763  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:57:21.763  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:57:21.763  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
08-29 16:57:21.763  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:57:21.763  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:57:21.783  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:57:21.783  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:57:21.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:21.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:21.783  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:23.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:26.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:27.003  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:57:29.033   291   291 E SMD     : DCD OFF,
,08-29 16:57:31.823  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:31.823  1015  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:57:31.823  1015  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:57:31.823  1015  1484 D BatteryService: stay LED for fully charged
,08-29 16:57:31.823  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:57:31.823  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:57:31.823  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:57:31.833  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:57:31.833  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:57:31.833  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:57:31.833  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:57:31.843  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:57:31.843  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:57:31.853  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:57:31.853  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:57:31.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:31.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:31.853  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:32.043   291   291 E SMD     : DCD OFF
,08-29 16:57:35.043   291   291 E SMD     : DCD OFF
,08-29 16:57:37.033  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:57:37.673  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:57:38.053   291   291 E SMD     : DCD OFF,
,08-29 16:57:41.043   291   291 E SMD     : DCD OFF,
,08-29 16:57:41.883  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:41.883  1015  2093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:57:41.883  1015  2093 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:57:41.883  1015  2093 D BatteryService: stay LED for fully charged
08-29 16:57:41.883  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:57:41.883  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:57:41.883  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:57:41.883  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:57:41.893  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:57:41.893  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:57:41.893  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:57:41.903  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:57:41.903  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:57:41.913  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:57:41.913  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:57:41.913  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:41.913  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:41.913  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:44.043   291   291 E SMD     : DCD OFF,
,08-29 16:57:47.043   291   291 E SMD     : DCD OFF,
,08-29 16:57:47.063  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:57:47.593  1015  1322 E Watchdog: !@Sync 38,
,08-29 16:57:50.053   291   291 E SMD     : DCD OFF,
,08-29 16:57:51.943  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:57:51.943  1015  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:57:51.943  1015  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:57:51.943  1015  1496 D BatteryService: stay LED for fully charged
,08-29 16:57:51.943  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:57:51.943  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:57:51.943  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:57:51.953  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:57:51.953  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:57:51.953  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 16:57:51.953  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:57:51.963  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-29 16:57:51.963  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:57:51.973  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:57:51.973  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:57:51.973  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:51.973  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:57:51.983  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:57:53.053   291   291 E SMD     : DCD OFF,
,08-29 16:57:56.053   291   291 E SMD     : DCD OFF,
,08-29 16:57:57.113  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:57:57.693  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:57:59.063   291   291 E SMD     : DCD OFF,
,08-29 16:58:02.003  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:02.003  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:58:02.003  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:58:02.003  1015  1216 D BatteryService: stay LED for fully charged
,08-29 16:58:02.003  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:58:02.003  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:58:02.013  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:58:02.013  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:58:02.013  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:58:02.023  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:58:02.023  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:58:02.023  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:58:02.023  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:58:02.023  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:02.023  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:58:02.023  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:58:02.043  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:02.043  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:02.053   291   291 E SMD     : DCD OFF,
,08-29 16:58:05.063   291   291 E SMD     : DCD OFF,
,08-29 16:58:07.133  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:58:08.063   291   291 E SMD     : DCD OFF
,08-29 16:58:11.063   291   291 E SMD     : DCD OFF
,08-29 16:58:12.063  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:12.063  1015  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:58:12.063  1015  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:58:12.063  1015  1496 D BatteryService: stay LED for fully charged
08-29 16:58:12.063  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:58:12.063  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:58:12.063  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:58:12.073  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 16:58:12.073  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 16:58:12.073  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 16:58:12.073  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:58:12.083  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:58:12.083  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:58:12.093  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-29 16:58:12.093  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:58:12.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:58:12.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:12.093  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:14.063   291   291 E SMD     : DCD OFF,
,08-29 16:58:17.073   291   291 E SMD     : DCD OFF,
,08-29 16:58:17.193  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:58:17.593  1015  1322 E Watchdog: !@Sync 39,
,08-29 16:58:17.713  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:58:20.073   291   291 E SMD     : DCD OFF,
,08-29 16:58:22.123  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:22.123  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:58:22.123  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:58:22.123  1015  1216 D BatteryService: stay LED for fully charged
,08-29 16:58:22.123  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:58:22.133  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:58:22.133  1015  1015 I MotionRecognitionService: Plugged
08-29 16:58:22.133  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:58:22.133  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:58:22.133  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:58:22.133  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:58:22.143  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:58:22.143  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:58:22.153  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:58:22.153  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:58:22.163  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:22.163  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:58:22.163  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:23.063   291   291 E SMD     : DCD OFF
,08-29 16:58:26.073   291   291 E SMD     : DCD OFF
,08-29 16:58:27.233  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:58:29.073   291   291 E SMD     : DCD OFF,
,08-29 16:58:32.073   291   291 E SMD     : DCD OFF,
,08-29 16:58:32.183  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:35.083   291   291 E SMD     : DCD OFF
,08-29 16:58:37.243  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:58:37.733  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:58:38.083   291   291 E SMD     : DCD OFF,
,08-29 16:58:41.083   291   291 E SMD     : DCD OFF,
,08-29 16:58:42.243  1015  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:44.083   291   291 E SMD     : DCD OFF,
,08-29 16:58:44.553  1015  1085 D TimaService: TIMA: TimaService scheduler is intialized. 
08-29 16:58:44.553  1015  1085 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-29 16:58:44.553  1015  1084 D TimaService: TimaServiceHandler.handleMessage what =1
,08-29 16:58:45.173  1015  1040 I UsageStatsService: User[0] Flushing usage stats to disk,
,08-29 16:58:45.233  1015  1100 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,08-29 16:58:45.233  1015  1100 I ApplicationUsage: Updating Usage Statistics in DB @ 1472482725242
,08-29 16:58:45.243  1015  1100 I ApplicationPolicy: updateDataUsageMap
,08-29 16:58:45.383  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-29 16:58:45.383  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-29 16:58:45.393  1015  1085 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:58:45.393  1015  1085 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-29 16:58:45.683  1015  1100 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,08-29 16:58:45.683  1015  1100 I NetworkDataUsageDb: ::isTableExists: Table exists 
,08-29 16:58:45.703  1015  1100 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1472482725717
,08-29 16:58:47.083   291   291 E SMD     : DCD OFF
,08-29 16:58:47.303  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:58:47.603  1015  1322 E Watchdog: !@Sync 40,
,08-29 16:58:47.883  1015  1048 I PowerManagerService: [PWL] Off : 1156s ago,
,08-29 16:58:50.083   291   291 E SMD     : DCD OFF,
,08-29 16:58:52.303  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:58:52.303  1015  3998 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:58:52.303  1015  3998 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 16:58:52.313  1015  3998 D BatteryService: stay LED for fully charged,
08-29 16:58:52.313  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:58:52.323  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:58:52.323  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:58:52.323  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:58:52.323  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:58:52.323  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 16:58:52.323  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:58:52.323  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-29 16:58:52.323  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 16:58:52.333  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:58:52.333  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:58:52.333  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:58:52.333  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:58:52.343  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,08-29 16:58:53.093   291   291 E SMD     : DCD OFF,
,08-29 16:58:56.093   291   291 E SMD     : DCD OFF,
,08-29 16:58:57.343  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:58:57.753  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:58:59.093   291   291 E SMD     : DCD OFF
,08-29 16:59:02.093   291   291 E SMD     : DCD OFF
,08-29 16:59:02.363  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:59:02.363  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:59:02.363  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:59:02.363  1015  1027 D BatteryService: stay LED for fully charged
,08-29 16:59:02.363  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:59:02.373  1015  1015 I MotionRecognitionService: Plugged
,08-29 16:59:02.373  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:59:02.383  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 16:59:02.383  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:59:02.383  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:59:02.383  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:59:02.393  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 16:59:02.393  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:59:02.403  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:59:02.403  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:59:02.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:59:02.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:59:02.413  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:59:05.093   291   291 E SMD     : DCD OFF
,08-29 16:59:07.373  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 16:59:08.093   291   291 E SMD     : DCD OFF
,08-29 16:59:11.103   291   291 E SMD     : DCD OFF
,08-29 16:59:12.433  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 16:59:14.103   291   291 E SMD     : DCD OFF
,08-29 16:59:17.103   291   291 E SMD     : DCD OFF,
,08-29 16:59:17.433  1015  3363 D SSRM:n  : SIOP:: AP = 300,
,08-29 16:59:17.603  1015  1322 E Watchdog: !@Sync 41,
,08-29 16:59:17.773  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 16:59:20.103   291   291 E SMD     : DCD OFF,
,08-29 16:59:22.503  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:59:22.503  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:59:22.503  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:59:22.503  1015  1028 D BatteryService: stay LED for fully charged
,08-29 16:59:22.503  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:59:22.513  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:59:22.513  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:59:22.513  1015  1015 I MotionRecognitionService: Plugged
08-29 16:59:22.513  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:59:22.513  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:59:22.513  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 16:59:22.513  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:59:22.523  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:59:22.533  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:59:22.533  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:59:22.533  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:59:22.533  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:59:22.533  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:59:23.103   291   291 E SMD     : DCD OFF
,08-29 16:59:26.103   291   291 E SMD     : DCD OFF
,08-29 16:59:27.463  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:59:29.103   291   291 E SMD     : DCD OFF
,08-29 16:59:32.113   291   291 E SMD     : DCD OFF,
,08-29 16:59:32.563  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-29 16:59:32.563  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 16:59:32.563  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 16:59:32.563  1015  1028 D BatteryService: stay LED for fully charged
,08-29 16:59:32.563  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 16:59:32.563  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 16:59:32.563  1015  1015 I MotionRecognitionService: Plugged
08-29 16:59:32.563  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 16:59:32.563  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 16:59:32.573  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 16:59:32.573  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-29 16:59:32.583  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 16:59:32.583  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 16:59:32.593  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 16:59:32.593  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 16:59:32.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:59:32.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 16:59:32.593  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 16:59:35.103   291   291 E SMD     : DCD OFF
,08-29 16:59:37.483  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:59:37.793  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:59:38.103   291   291 E SMD     : DCD OFF
,08-29 16:59:41.113   291   291 E SMD     : DCD OFF
,08-29 16:59:42.613  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:59:44.113   291   291 E SMD     : DCD OFF
,08-29 16:59:47.113   291   291 E SMD     : DCD OFF,
,08-29 16:59:47.543  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:59:47.593  1015  1322 E Watchdog: !@Sync 42,
,08-29 16:59:50.123   291   291 E SMD     : DCD OFF,
,08-29 16:59:52.673  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 16:59:53.123   291   291 E SMD     : DCD OFF
,08-29 16:59:56.123   291   291 E SMD     : DCD OFF,
,08-29 16:59:57.593  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 16:59:57.823  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-29 16:59:59.123   291   291 E SMD     : DCD OFF,
,08-29 17:00:02.123   291   291 E SMD     : DCD OFF,
,08-29 17:00:02.733  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:05.123   291   291 E SMD     : DCD OFF
,08-29 17:00:07.613  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:08.133   291   291 E SMD     : DCD OFF,
,08-29 17:00:11.133   291   291 E SMD     : DCD OFF,
,08-29 17:00:12.803  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:14.133   291   291 E SMD     : DCD OFF
,08-29 17:00:17.133   291   291 E SMD     : DCD OFF,
,08-29 17:00:17.603  1015  1322 E Watchdog: !@Sync 43,
,08-29 17:00:17.673  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:17.843  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:00:20.133   291   291 E SMD     : DCD OFF,
,08-29 17:00:22.853  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:23.133   291   291 E SMD     : DCD OFF
,08-29 17:00:26.143   291   291 E SMD     : DCD OFF
,08-29 17:00:27.723  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:29.143   291   291 E SMD     : DCD OFF,
,08-29 17:00:32.143   291   291 E SMD     : DCD OFF,
,08-29 17:00:32.913  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:35.143   291   291 E SMD     : DCD OFF
,08-29 17:00:37.743  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:37.863  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:00:37.953  1015  1048 I PowerManagerService: [PWL] Off : 1266s ago,
,08-29 17:00:38.143   291   291 E SMD     : DCD OFF,
,08-29 17:00:41.143   291   291 E SMD     : DCD OFF,
,08-29 17:00:42.973  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:44.153   291   291 E SMD     : DCD OFF
,08-29 17:00:47.153   291   291 E SMD     : DCD OFF,
,08-29 17:00:47.603  1015  1322 E Watchdog: !@Sync 44,
,08-29 17:00:47.793  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:50.153   291   291 E SMD     : DCD OFF,
,08-29 17:00:53.033  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:00:53.153   291   291 E SMD     : DCD OFF
,08-29 17:00:56.153   291   291 E SMD     : DCD OFF
,08-29 17:00:57.853  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:00:57.873  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:00:59.153   291   291 E SMD     : DCD OFF,
,08-29 17:01:02.153   291   291 E SMD     : DCD OFF,
,08-29 17:01:03.093  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:01:05.163   291   291 E SMD     : DCD OFF
,08-29 17:01:07.873  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:01:08.163   291   291 E SMD     : DCD OFF,
,08-29 17:01:11.163   291   291 E SMD     : DCD OFF,
,08-29 17:01:13.153  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 17:01:14.163   291   291 E SMD     : DCD OFF
,08-29 17:01:17.163   291   291 E SMD     : DCD OFF,
,08-29 17:01:17.603  1015  1322 E Watchdog: !@Sync 45,
,08-29 17:01:17.903  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:01:17.933  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:01:20.163   291   291 E SMD     : DCD OFF
,08-29 17:01:23.163   291   291 E SMD     : DCD OFF
,08-29 17:01:23.213  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:01:26.173   291   291 E SMD     : DCD OFF
,08-29 17:01:27.983  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:01:29.173   291   291 E SMD     : DCD OFF,
,08-29 17:01:32.173   291   291 E SMD     : DCD OFF,
,08-29 17:01:33.283  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:01:35.173   291   291 E SMD     : DCD OFF
,08-29 17:01:37.923  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:01:38.003  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:01:38.173   291   291 E SMD     : DCD OFF,
,08-29 17:01:41.173   291   291 E SMD     : DCD OFF,
,08-29 17:01:43.343  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:01:44.183   291   291 E SMD     : DCD OFF
,08-29 17:01:47.173   291   291 E SMD     : DCD OFF,
,08-29 17:01:47.593  1015  1322 E Watchdog: !@Sync 46,
,08-29 17:01:48.063  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:01:50.183   291   291 E SMD     : DCD OFF,
,08-29 17:01:53.183   291   291 E SMD     : DCD OFF,
,08-29 17:01:53.403  1015  3997 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:01:56.183   291   291 E SMD     : DCD OFF,
,08-29 17:01:57.943  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:01:58.113  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 17:01:59.183   291   291 E SMD     : DCD OFF
,08-29 17:02:02.193   291   291 E SMD     : DCD OFF,
,08-29 17:02:03.463  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:05.193   291   291 E SMD     : DCD OFF,
,08-29 17:02:08.143  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:08.183   291   291 E SMD     : DCD OFF,
,08-29 17:02:11.193   291   291 E SMD     : DCD OFF,
,08-29 17:02:13.523  1015  2093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:14.193   291   291 E SMD     : DCD OFF,
,08-29 17:02:17.193   291   291 E SMD     : DCD OFF,
,08-29 17:02:17.593  1015  1322 E Watchdog: !@Sync 47
,08-29 17:02:17.963  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:02:18.193  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:20.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:23.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:23.583  1015  3998 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:26.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:28.243  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:29.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:32.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:33.053  1015  1048 I PowerManagerService: [PWL] Off : 1381s ago,
,08-29 17:02:33.643  1015  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:35.203   291   291 E SMD     : DCD OFF,
,08-29 17:02:37.983  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:02:38.213   291   291 E SMD     : DCD OFF,
,08-29 17:02:38.263  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:41.213   291   291 E SMD     : DCD OFF,
,08-29 17:02:43.713  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:43.713  1015  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 17:02:43.713  1015  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 17:02:43.713  1015  1487 D BatteryService: stay LED for fully charged
,08-29 17:02:43.713  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 17:02:43.723  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 17:02:43.723  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 17:02:43.723  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 17:02:43.723  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 17:02:43.733  1015  1015 I MotionRecognitionService: Plugged
08-29 17:02:43.733  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 17:02:43.733  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 17:02:43.733  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 17:02:43.743  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 17:02:43.743  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 17:02:43.743  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:02:43.743  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:02:43.743  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:02:44.213   291   291 E SMD     : DCD OFF,
,08-29 17:02:47.213   291   291 E SMD     : DCD OFF
,08-29 17:02:47.603  1015  1322 E Watchdog: !@Sync 48,
,08-29 17:02:48.293  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:50.213   291   291 E SMD     : DCD OFF,
,08-29 17:02:53.213   291   291 E SMD     : DCD OFF,
,08-29 17:02:53.773  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:02:53.773  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 17:02:53.773  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 17:02:53.773  1015  1495 D BatteryService: stay LED for fully charged
08-29 17:02:53.773  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 17:02:53.783  1015  1015 I MotionRecognitionService: Plugged
,08-29 17:02:53.783  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 17:02:53.783  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 17:02:53.783  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 17:02:53.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 17:02:53.793  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 17:02:53.803  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-29 17:02:53.803  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 17:02:53.813  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 17:02:53.813  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 17:02:53.813  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:02:53.813  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:02:53.813  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:02:56.223   291   291 E SMD     : DCD OFF
,08-29 17:02:58.003  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:02:58.323  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:02:59.223   291   291 E SMD     : DCD OFF,
,08-29 17:03:02.213   291   291 E SMD     : DCD OFF,
,08-29 17:03:03.833  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:03:03.833  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 17:03:03.833  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 17:03:03.833  1015  1489 D BatteryService: stay LED for fully charged
,08-29 17:03:03.843  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 17:03:03.843  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 17:03:03.843  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 17:03:03.843  1015  1015 I MotionRecognitionService: Plugged,
08-29 17:03:03.843  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 17:03:03.843  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 17:03:03.843  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 17:03:03.853  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 17:03:03.853  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 17:03:03.863  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 17:03:03.873  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-29 17:03:03.873  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:03.873  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:03:03.873  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:05.223   291   291 E SMD     : DCD OFF,
,08-29 17:03:08.223   291   291 E SMD     : DCD OFF,
,08-29 17:03:08.343  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:03:11.223   291   291 E SMD     : DCD OFF
,08-29 17:03:13.903  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:03:13.903  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 17:03:13.903  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 17:03:13.903  1015  1489 D BatteryService: stay LED for fully charged
,08-29 17:03:13.903  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 17:03:13.903  1015  1015 I MotionRecognitionService: Plugged
,08-29 17:03:13.903  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 17:03:13.913  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 17:03:13.913  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 17:03:13.913  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 17:03:13.913  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 17:03:13.923  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 17:03:13.923  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 17:03:13.933  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 17:03:13.933  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 17:03:13.933  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:13.933  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:03:13.933  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:14.223   291   291 E SMD     : DCD OFF,
,08-29 17:03:17.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:17.603  1015  1322 E Watchdog: !@Sync 49,
,08-29 17:03:18.023  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:03:18.383  1015  3363 D SSRM:n  : SIOP:: AP = 290
,08-29 17:03:20.223   291   291 E SMD     : DCD OFF
,08-29 17:03:23.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:23.953  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-29 17:03:26.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:28.433  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:03:29.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:32.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:34.013  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:03:34.013  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 17:03:34.013  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 17:03:34.013  1015  1216 D BatteryService: stay LED for fully charged
,08-29 17:03:34.013  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 17:03:34.023  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 17:03:34.023  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 17:03:34.023  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 17:03:34.023  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 17:03:34.033  1015  1015 I MotionRecognitionService: Plugged,
08-29 17:03:34.033  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 17:03:34.033  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 17:03:34.033  3156  3259 D HeadsetStateMachine: Disconnected process message: 10
,08-29 17:03:34.043  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 17:03:34.043  1174  1174 D SViewCoverView: level :100 plugged : 2
08-29 17:03:34.043  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:34.043  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 17:03:34.053  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 17:03:35.243   291   291 E SMD     : DCD OFF
,08-29 17:03:38.043  1015  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-29 17:03:38.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:38.463  1015  3363 D SSRM:n  : SIOP:: AP = 290,
,08-29 17:03:41.243   291   291 E SMD     : DCD OFF
,08-29 17:03:44.073  1015  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 17:03:44.233   291   291 E SMD     : DCD OFF,
,08-29 17:03:44.553  1015  1085 D TimaService: TIMA: TimaService scheduler is intialized. 
08-29 17:03:44.553  1015  1085 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-29 17:03:44.553  1015  1084 D TimaService: TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1400000ms),08-29 17:03:46.503  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
08-29 17:03:46.503  1015  1085 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
08-29 17:03:46.503  1015  1085 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-29 17:03:46.503  1015  1085 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
08-29 17:03:46.623  8103  8103 D AndroidRuntime: 
08-29 17:03:46.623  8103  8103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 17:03:46.623  8103  8103 D AndroidRuntime: CheckJNI is OFF
08-29 17:03:46.623  8103  8103 D AndroidRuntime: readGMSProperty: start
08-29 17:03:46.623  8103  8103 D AndroidRuntime: readGMSProperty: already setted!!
08-29 17:03:46.623  8103  8103 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 17:03:46.623  8103  8103 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 17:03:46.623  8103  8103 D AndroidRuntime: readGMSProperty: end
08-29 17:03:46.623  8103  8103 D AndroidRuntime: addProductProperty: start
08-29 17:03:46.753  8103  8103 E AffinityControl: AffinityControl: registerfunction enter
08-29 17:03:46.783  8103  8103 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 17:03:46.793  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-29 17:03:46.793  1015  1028 D PackageManager: START PACKAGE DELETE: observer{110935515}
08-29 17:03:46.793  1015  1028 D PackageManager: pkg{<packageName>}
08-29 17:03:46.793  1015  1028 D PackageManager: user{0}
08-29 17:03:46.793  1015  1028 D PackageManager: caller{2000}
08-29 17:03:46.793  1015  1028 D PackageManager: flags{2}
08-29 17:03:46.793  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 17:03:46.793  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 17:03:46.793  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 17:03:46.793  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 17:03:46.803  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 17:03:46.803  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 17:03:46.803  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 17:03:46.803  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 17:03:46.803  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-29 17:03:46.803  1015  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
08-29 17:03:46.803  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-29 17:03:46.923  1015  1056 W PackageSettings: Skipping PackageSetting{613f660 com.example.hello/10168} due to missing metadata
08-29 17:03:46.943  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-29 17:03:46.963  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-29 17:03:46.983  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 17:03:46.993  2680  2680 I art     : Explicit concurrent mark sweep GC freed 21648(1213KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 831us total 33.262ms
08-29 17:03:47.003  1859  1859 E SamsungIME: mOCRHelper is null
08-29 17:03:47.013  2001  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 17:03:47.033  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 17:03:47.043  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 17:03:47 GMT+02:00 2016
08-29 17:03:47.063  4732  4732 I art     : Explicit concurrent mark sweep GC freed 24496(1449KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/17MB, paused 2.057ms total 99.818ms
08-29 17:03:47.073  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
08-29 17:03:47.083  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-29 17:03:47.083  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 17:03:47.083  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
08-29 17:03:47.083  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 17:03:47.083  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 17:03:47.083  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 17:03:47.083  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-29 17:03:47.083  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-29 17:03:47.083  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 17:03:47.083  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-29 17:03:47.093  1015  1121 V NetworkStats: performPollLocked() took 9ms
08-29 17:03:47.093  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 17:03:47.103  1015  1134 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 17:03:47.103  1456  1456 D RegisteredServicesCache: empty dynamic service
08-29 17:03:47.103  1015  1134 D SecContentProvider2: mCursor = null
08-29 17:03:47.113  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 17:03:47.113  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 17:03:47.123  2933  2933 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-29 17:03:47.123  1015  1028 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-29 17:03:47.123  1015  1028 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-29 17:03:47.123  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-29 17:03:47.133  1015  1015 I art     : Explicit concurrent mark sweep GC freed 26853(2MB) AllocSpace objects, 60(960KB) LOS objects, 33% free, 24MB/36MB, paused 4.203ms total 178.881ms
08-29 17:03:47.133  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.133  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.133  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.133  1015  1056 I art     : WaitForGcToComplete blocked for 75.079ms for cause Explicit
08-29 17:03:47.133  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.153  8115  8115 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.153  8115  8115 E Zygote  : v2
08-29 17:03:47.153  8115  8115 I libpersona: KNOX_SDCARD checking this for 10090
08-29 17:03:47.153  8115  8115 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.153  8115  8115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.153  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-29 17:03:47.153  8115  8115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.163  1015  1028 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8115 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-29 17:03:47.163  8115  8115 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.163  2933  2933 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-29 17:03:47.163  2933  2933 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-29 17:03:47.163  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-29 17:03:47.173  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.173  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.173  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.173  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.193  8130  8130 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.193  8130  8130 E Zygote  : v2
08-29 17:03:47.193  8130  8130 I libpersona: KNOX_SDCARD checking this for 1000
08-29 17:03:47.193  8130  8130 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.193  8130  8130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.193  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 17:03:47.193  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-29 17:03:47.193  8130  8130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.203  8115  8115 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.203  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.203  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.203  8115  8115 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.203  8130  8130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.203  1015  1497 I TactileAssist: enable value -1
08-29 17:03:47.203  1015  1497 I TactileAssist: internal enable value -1
08-29 17:03:47.203  1015  1497 I TactileAssist: intensity value -1
08-29 17:03:47.203  1015  1497 I TactileAssist: saveAppList value true
08-29 17:03:47.203  1015  1015 D RCPManagerService: PackageReceiver onReceive()
08-29 17:03:47.203  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.203  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.213  1015  1497 I TactileAssist: List of disabled apps :
08-29 17:03:47.213  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-29 17:03:47.213  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-29 17:03:47.213  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 17:03:47.213  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 17:03:47.213  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-29 17:03:47.213  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-29 17:03:47.213  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-29 17:03:47.223  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-29 17:03:47.233  8144  8144 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.233  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
08-29 17:03:47.233  8144  8144 E Zygote  : v2
08-29 17:03:47.233  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-29 17:03:47.233  8144  8144 I libpersona: KNOX_SDCARD checking this for 1000
08-29 17:03:47.233  8144  8144 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.233  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=8144 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 17:03:47.233  8144  8144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.233  8144  8144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.243   291   291 E SMD     : DCD OFF
08-29 17:03:47.243  8144  8144 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.253  1456  1456 D RegisteredComponentCache: Collect Tech packages for Knox
08-29 17:03:47.253  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
08-29 17:03:47.253  8130  8130 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.253  8130  8130 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.283  8144  8144 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.283  8144  8144 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.323  8144  8144 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-29 17:03:47.333  1015  2093 D SecContentProvider2: uri = -1 selection = getSealedState
08-29 17:03:47.333  1015  2093 D SecContentProvider2: mCursor = null
08-29 17:03:47.333  8144  8144 I PopupuiReceiver_KNOX: getSealedState : true
08-29 17:03:47.333  1015  1489 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-29 17:03:47.333  1015  1489 D SecContentProvider2: mCursor = null
08-29 17:03:47.333  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-29 17:03:47.333  8144  8144 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-29 17:03:47.333  1015  1524 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-29 17:03:47.333  1015  1524 D SecContentProvider2: mCursor = null
08-29 17:03:47.333  8144  8144 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-29 17:03:47.333  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.333  8144  8144 D PopupuiReceiver: Action package removed
08-29 17:03:47.333  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.333  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.333  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.333  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 17:03:47.343  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 17:03:47.343  8160  8160 I libpersona: KNOX_SDCARD checking this for 10048
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 17:03:47.343  8160  8160 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 17:03:47.343  1015  1027 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8160 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 17:03:47.343  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-29 17:03:47.343  8160  8160 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.343  8160  8160 E Zygote  : v2
08-29 17:03:47.343  8160  8160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.353  8160  8160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.353  8160  8160 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 17:03:47.353  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 17:03:47.363  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-29 17:03:47.363  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-29 17:03:47.363  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.363  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.363  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.363  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.363  1015  3363 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-29 17:03:47.373  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-29 17:03:47.373  8115  8115 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-29 17:03:47.373  8115  8115 D elm:15121: ELMEngine.ELMEngine( context ).
08-29 17:03:47.383  8174  8174 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.383  8174  8174 E Zygote  : v2
08-29 17:03:47.383  8174  8174 I libpersona: KNOX_SDCARD checking this for 10145
08-29 17:03:47.383  8174  8174 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.383  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-29 17:03:47.383  8115  8115 D elm:15121: MDMBridge.setEnterpriseBridge()
08-29 17:03:47.383  1015  1027 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=8174 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 17:03:47.383  1015  1027 I ActivityManager: Killing 7132:com.osp.app.signin/u0a36 (adj 15): empty #21
08-29 17:03:47.383  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-29 17:03:47.383  8174  8174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.393  8174  8174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.393  8174  8174 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.393  1015  1134 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-29 17:03:47.393  8160  8160 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.393  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-29 17:03:47.393  8160  8160 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.393  8130  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-29 17:03:47.393  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 17:03:47.393  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 17:03:47.393  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-29 17:03:47.393  8115  8115 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-29 17:03:47.403  2933  8114 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-29 17:03:47.403  2933  8114 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-29 17:03:47.403  8115  8115 D elm:15121: ElmAgentService : onCreate()
08-29 17:03:47.403  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-29 17:03:47.403  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-29 17:03:47.403  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-29 17:03:47.403  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 17:03:47.403  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-29 17:03:47.413  2933  2933 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-29 17:03:47.413  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-29 17:03:47.413  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.413  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.413  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.413  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.413  8115  8182 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-29 17:03:47.413  8115  8182 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-29 17:03:47.413  8115  8182 D elm:15121: MDMBridge.getInstance()
08-29 17:03:47.413  8115  8182 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-29 17:03:47.423  8115  8182 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-29 17:03:47.433  1015  1056 I art     : Explicit concurrent mark sweep GC freed 13529(1151KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 8.870ms total 298.869ms
08-29 17:03:47.433  8192  8192 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.433  8192  8192 E Zygote  : v2
08-29 17:03:47.433  8192  8192 I libpersona: KNOX_SDCARD checking this for 1000
08-29 17:03:47.433  8192  8192 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.433  8192  8192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.443  8192  8192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.443  8192  8192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.443  1015  1134 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=8192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 17:03:47.453  8174  8174 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.453  8174  8174 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.463  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-29 17:03:47.463  8160  8160 D Compatibility: onReceive() it will make start service
08-29 17:03:47.463  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.463  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.463  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.463  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.473  8192  8192 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.473  8192  8192 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.483  8208  8208 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.483  8208  8208 I libpersona: KNOX_SDCARD checking this for 1000
08-29 17:03:47.483  8208  8208 E Zygote  : v2
08-29 17:03:47.483  8208  8208 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.483  8208  8208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.483  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 17:03:47.483  8208  8208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.483  8208  8208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.483  1015  3997 I ActivityManager: Killing 6971:com.google.android.talk/u0a102 (adj 15): empty #21
08-29 17:03:47.493  8115  8115 D elm:15121: ElmAgentService : onDestroy().
08-29 17:03:47.503  1015  1495 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-29 17:03:47.503  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-29 17:03:47.513  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 17:03:47.513  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 17:03:47.513  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-29 17:03:47.513  1015  2093 I ActivityManager: Killing 7240:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
08-29 17:03:47.523  1015  3997 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-29 17:03:47.523  1015  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.523  1015  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.523  1015  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.523  1015  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.533  8192  8192 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 17:03:47.533  1015  1056 D PackageManager: delete codoeFile: 
08-29 17:03:47.533  8160  8224 D Compatibility: onHandleIntent()
08-29 17:03:47.533  8208  8208 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.533  8208  8208 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.543  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-29 17:03:47.543  1015  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-29 17:03:47.543  8227  8227 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.543  8227  8227 I libpersona: KNOX_SDCARD checking this for 10052
08-29 17:03:47.543  8227  8227 E Zygote  : v2
08-29 17:03:47.543  8227  8227 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.543  8227  8227 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.543  1015  1056 D PackageManager: result of delete: 1{110935515}
08-29 17:03:47.543  8103  8103 D AndroidRuntime: Shutting down VM
08-29 17:03:47.543  8227  8227 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.553  8227  8227 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 17:03:47.553  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 17:03:47.553  1015  1056 D PackageManager: userId{-1}
08-29 17:03:47.553  1015  1056 D PackageManager: andCode{true}
08-29 17:03:47.553  1015  3997 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8227 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-29 17:03:47.553  8160  8224 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-29 17:03:47.553  8160  8224 D Compatibility: found: 2
08-29 17:03:47.553  8192  8192 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-29 17:03:47.563  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-29 17:03:47.563  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.563  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.563  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.563  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.573  8160  8224 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-29 17:03:47.573  8227  8227 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.573  8227  8227 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.583  8160  8224 D Compatibility: skipping ResolveInfo{2e6828c2 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-29 17:03:47.583  8160  8224 D Compatibility: considering ResolveInfo{6d0a6d3 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-29 17:03:47.583  8160  8224 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-29 17:03:47.583  8160  8224 D Compatibility: enabling receiver ResolveInfo{13dd8210 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-29 17:03:47.583  1015  1134 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-29 17:03:47.583  1015  1134 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-29 17:03:47.583  8242  8242 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.583  8242  8242 I libpersona: KNOX_SDCARD checking this for 10003
08-29 17:03:47.583  8242  8242 E Zygote  : v2
08-29 17:03:47.583  8242  8242 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.593  8242  8242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.593  8242  8242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.593  8242  8242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.593  1015  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8242 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 17:03:47.593  8160  8224 D Compatibility: enabling receiver ResolveInfo{1b517109 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-29 17:03:47.603  1015  1322 E Watchdog: !@Sync 50
08-29 17:03:47.603  8208  8208 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-29 17:03:47.603  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-29 17:03:47.603  8208  8208 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 17:03:47.603  8208  8208 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-29 17:03:47.603  8160  8224 D Compatibility: enabling receiver ResolveInfo{28140f0e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-29 17:03:47.603  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.603  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.603  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.603  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.613  8160  8224 D Compatibility: enabling receiver ResolveInfo{1ff4dd2f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-29 17:03:47.623  8258  8258 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.623  8258  8258 I libpersona: KNOX_SDCARD checking this for 10087
08-29 17:03:47.623  8258  8258 E Zygote  : v2
08-29 17:03:47.623  8258  8258 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.623  8160  8224 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-29 17:03:47.623  8258  8258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.623  8258  8258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.623  8242  8242 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.623  1015  1027 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8258 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-29 17:03:47.623  8242  8242 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.623  8258  8258 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 17:03:47.623  1015  1027 I ActivityManager: Killing 7205:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-29 17:03:47.643  8174  8174 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-29 17:03:47.643  8174  8174 D ThemeInfoUtil: isCurrentFestival = false
08-29 17:03:47.643  1015  2093 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-29 17:03:47.643  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.643  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.643  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.643  1015  2093 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.653  8258  8258 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.653  8258  8258 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.653  8208  8208 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 17:03:47.653  8208  8208 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 17:03:47.653  8208  8208 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 17:03:47.653  8208  8208 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-29 17:03:47.673  8274  8274 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.673  8274  8274 I libpersona: KNOX_SDCARD checking this for 10148
08-29 17:03:47.673  8274  8274 E Zygote  : v2
08-29 17:03:47.673  8274  8274 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.673  8274  8274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.683  8274  8274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.683  8274  8274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.693  1015  2093 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=8274 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-29 17:03:47.693  1015  2093 I ActivityManager: Killing 7083:com.sec.spp.push/u0a32 (adj 15): empty #21
08-29 17:03:47.703   309   309 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 20.227ms
08-29 17:03:47.703  1015  2093 I ActivityManager: Killing 6906:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
08-29 17:03:47.713  1015  1524 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-29 17:03:47.713  1015  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.713  1015  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.713  1015  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.713  1015  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 17:03:47.723   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.554ms
08-29 17:03:47.723  8274  8274 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 17:03:47.723  8274  8274 D ActivityThread: Added TimaKeyStore provider
08-29 17:03:47.743   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.999ms
08-29 17:03:47.753  1015  1495 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 17:03:47.753  8103  8103 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-29 17:03:47.753  8290  8290 E Zygote  : MountEmulatedStorage()
08-29 17:03:47.753  8290  8290 E Zygote  : v2
08-29 17:03:47.763  8290  8290 I libpersona: KNOX_SDCARD checking this for 10029
08-29 17:03:47.763  8290  8290 I libpersona: KNOX_SDCARD not a persona
08-29 17:03:47.763  8290  8290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 17:03:47.763  1015  1524 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8290 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-29 17:03:47.763  8290  8290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 17:03:47.763  1015  1524 I ActivityManager: Killing 7222:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
08-29 17:03:47.763  8290  8290 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 17:03:47.773  1015  1487 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-29 17:03:47.773  1015  1524 I ActivityManager: Killing 4732:com.google.android.gms/u0a11 (adj 15): empty #21

```
