#### Test 829140730a15ac0_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
,09-07 13:15:46.429  1014  1438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 13:15:46.429  1014  1438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 13:15:46.429  1014  1438 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 13:15:46.429  1014  1438 D BatteryService: stay LED for fully charged
09-07 13:15:46.429  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
09-07 13:15:46.429  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 13:15:46.429  1014  1014 I MotionRecognitionService: Plugged
09-07 13:15:46.429  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-07 13:15:46.429  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-07 13:15:46.429  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-07 13:15:46.429  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-07 13:15:46.439  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 13:15:46.439  3174  3278 D HeadsetStateMachine: Disconnected process message: 10
09-07 13:15:46.459  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 13:15:46.459  1174  1174 D SViewCoverView: level :100 plugged : 2
09-07 13:15:46.459  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:15:46.459  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:15:46.459  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:15:46.689  6766  6766 D AndroidRuntime: 
09-07 13:15:46.689  6766  6766 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 13:15:46.689  6766  6766 D AndroidRuntime: CheckJNI is OFF
09-07 13:15:46.689  6766  6766 D AndroidRuntime: readGMSProperty: start
09-07 13:15:46.689  6766  6766 D AndroidRuntime: readGMSProperty: already setted!!
09-07 13:15:46.689  6766  6766 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 13:15:46.689  6766  6766 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 13:15:46.689  6766  6766 D AndroidRuntime: readGMSProperty: end
09-07 13:15:46.689  6766  6766 D AndroidRuntime: addProductProperty: start
09-07 13:15:46.819  6766  6766 E AffinityControl: AffinityControl: registerfunction enter
09-07 13:15:46.849  6766  6766 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 13:15:46.869  1014  1095 E PersonaManagerService: inState():  stateMachine is null !!
09-07 13:15:46.869  1014  1095 I PersonaManagerService: PersonaId don't exist
09-07 13:15:46.869  1014  1095 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-07 13:15:46.869  1014  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 13:15:46.889  1014  1095 W ActivityManager: mDVFSHelper.acquire()
09-07 13:15:46.899   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-07 13:15:46.899   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-07 13:15:46.909  1014  1095 D FocusedStackFrame: Set to : 0
09-07 13:15:46.909  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:15:46.909  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:15:46.909  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:15:46.909  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:15:46.919  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 13:15:46.919  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-07 13:15:46.929  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 13:15:46.929  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-07 13:15:46.929   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-07 13:15:46.929  6777  6777 E Zygote  : MountEmulatedStorage()
09-07 13:15:46.939  6777  6777 E Zygote  : v2
09-07 13:15:46.939  1014  1095 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6777 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 13:15:46.939  1014  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-07 13:15:46.939  6777  6777 I libpersona: KNOX_SDCARD checking this for 10171
09-07 13:15:46.939  1014  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 13:15:46.939  6777  6777 I libpersona: KNOX_SDCARD not a persona
09-07 13:15:46.939  1014  1095 D InputDispatcher: Focused application set to: xxxx
09-07 13:15:46.939  1014  1095 D InputDispatcher: Focus left window: 1481
09-07 13:15:46.939  6766  6766 D AndroidRuntime: Shutting down VM
09-07 13:15:46.939  6777  6777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:15:46.939  6777  6777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:15:46.939  6777  6777 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-07 13:15:46.959  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 13:15:46.959  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 13:15:46.969  6777  6777 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:15:46.969  6777  6777 D ActivityThread: Added TimaKeyStore provider
09-07 13:15:46.969  1014  1496 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-07 13:15:46.969  1014  1014 V ActivityManager: Display changed displayId=0
09-07 13:15:46.979  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 13:15:46.999  1014  1496 D PersonaManager: isKioskContainerExistOnDevice
09-07 13:15:47.009  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-07 13:15:47.019   257  1036 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-07 13:15:47.019   257   447 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-07 13:15:47.029  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{3397f423 token=android.os.BinderProxy@15d004d0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-07 13:15:47.029  1481  1481 D Launcher: onTrimMemory. Level: 20
09-07 13:15:47.119  6777  6777 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-07 13:15:47.129  6777  6777 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6875-6877)
09-07 13:15:47.129  6777  6777 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 13:15:47.139  6766  6766 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-07 13:15:47.159  6777  6777 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {304dc5db}
09-07 13:15:47.159  6777  6777 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 13:15:47.159  6777  6777 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 13:15:47.199  6777  6777 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-07 13:15:47.199  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:15:47.199  6777  6777 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 13:15:47.239  6777  6777 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 13:15:47.239  6777  6777 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 13:15:47.239  6777  6777 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 13:15:47.239  6777  6777 I Adreno-EGL: Local Branch: 
09-07 13:15:47.239  6777  6777 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 13:15:47.239  6777  6777 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 13:15:47.239  6777  6777 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 13:15:47.319  6777  6777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 13:15:47.329  6777  6777 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-07 13:15:47.329  6777  6777 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>,
,09-07 13:15:47.339  6777  6777 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-07 13:15:47.339  6777  6777 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-07 13:15:47.369   290   290 E SMD     : DCD OFF
,09-07 13:15:47.469  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:15:47.489  6777  6777 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 13:15:47.499  6777  6777 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-07 13:15:47.499  6777  6777 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-07 13:15:47.499  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{1618787f u0 com.test.thalitest/.MainActivity t2}
,09-07 13:15:47.499  6777  6777 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-07 13:15:47.509  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:15:47.509  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 13:15:47.569  6777  6818 D OpenGLRenderer: Render dirty regions requested: true
,09-07 13:15:47.569  1014  1436 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-07 13:15:47.569  1014  1436 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 13:15:47.569  1014  1436 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 13:15:47.569  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 13:15:47.569  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 13:15:47.579  6777  6805 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-07 13:15:47.589  6777  6777 V ActivityThread: updateVisibility : ActivityRecord{52b4dbb token=android.os.BinderProxy@2d64d3ec {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-07 13:15:47.589  6777  6777 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 13:15:47.589  6777  6777 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-07 13:15:47.599   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-07 13:15:47.609  1014  1496 D InputDispatcher: Focus entered window: 6777
,09-07 13:15:47.609  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 13:15:47.619  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 13:15:47.619  6777  6777 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-07 13:15:47.619  6777  6818 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 13:15:47.619  6777  6818 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-07 13:15:47.629  6777  6818 D OpenGLRenderer: Enabling debug mode 0
,09-07 13:15:47.649  1014  1436 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 13:15:47.659  1014  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 13:15:47.659  1174  1174 I StatusBar: Icon Only
,09-07 13:15:47.659  1174  1174 D PanelView: There is/are notification(s) 
,09-07 13:15:47.669  1014  1045 I ActivityManager: Displayed Component not be shown by security: +665ms (total +756ms)
09-07 13:15:47.669  1014  1045 W ActivityManager: mDVFSHelper.release()
09-07 13:15:47.669  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1618787f u0 com.test.thalitest/.MainActivity t2} time:107412
,09-07 13:15:47.669   257   447 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-07 13:15:47.679  6777  6777 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-07 13:15:47.679  6777  6777 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d64d3ec time:107420
,09-07 13:15:47.739  1874  1874 I SamsungIME: getCurrentCandidateView
,09-07 13:15:47.779  6777  6777 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6777
,09-07 13:15:47.829  1874  1874 D SamsungIME: Dismiss ExpandCandiate
,09-07 13:15:47.919  6777  6777 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 13:15:47.989  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 13:15:48.029  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 13:15:48.039  1874  1874 I SamsungIME: KeybaordView init() : load resources
,09-07 13:15:48.049  6777  6825 D jxcore_app_log: JniHelper::setJavaVM(0xb8b412b0), pthread_self() = -1190269024
,09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 13:15:48.059  6777  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2105ba69 added. We now have 1 listener(s)
,09-07 13:15:48.069  1874  1874 I SamsungIME: getCurrentKeyboard
09-07 13:15:48.069  1874  1874 I SamsungIME: getTextKeyboard
,09-07 13:15:48.069  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-07 13:15:48.069  6777  6825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 13:15:48.069  6777  6825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 13:15:48.069  6777  6825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 13:15:48.079  6777  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a3b101c added. We now have 1 listener(s)
,09-07 13:15:48.079  6777  6825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:15:48.089  6777  6825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-07 13:15:48.099  6777  6825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:15:48.099  6777  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:15:48.099  6777  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 13:15:48.099  6777  6825 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:15:48.099  6777  6825 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 13:15:48.099  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:15:48.109  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:15:48.109  1874  1874 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-07 13:15:48.129  6777  6777 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 13:15:48.399  1014  1322 E Watchdog: !@Sync 3
,09-07 13:15:48.659  6777  6833 W jxcore-log: Initializing JXcore engine
09-07 13:15:48.659  6777  6833 W jxcore-log: JXcore engine is ready
,09-07 13:15:48.719  2025  2025 E audit   : type=1400 msg=audit(1473246948.719:205): avc:  denied  { ioctl } for  pid=6833 comm="Thread-1251" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 13:15:48.719  2025  2025 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:15:48.719  2025  2025 E audit   : type=1300 msg=audit(1473246948.719:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f4fd8f8 items=0 ppid=307 ppcomm=main pid=6833 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1251" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-07 13:15:48.719  2025  2025 E audit   : type=1320 msg=audit(1473246948.719:205): 
,09-07 13:15:48.729  6777  6833 W jxcore-log: Starting JXcore engine
,09-07 13:15:48.839  6777  6833 W jxcore-log: Platform android
09-07 13:15:48.839  6777  6833 W jxcore-log: 
09-07 13:15:48.839  6777  6833 W jxcore-log: Process ARCH arm
09-07 13:15:48.839  6777  6833 W jxcore-log: 
,09-07 13:15:49.039  6777  6833 I jxcore-log: JXcore Cordova bridge is ready!
09-07 13:15:49.039  6777  6833 I jxcore-log: 
,09-07 13:15:49.039  6777  6833 W jxcore-log: JXcore engine is started
,09-07 13:15:49.049  6777  6825 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,09-07 13:15:49.049  6777  6777 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 13:15:49.379   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-07 13:15:49.379   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-07 13:15:50.369   290   290 E SMD     : DCD OFF
,09-07 13:15:52.139  1014  3356 D SSRM:n  : SIOP:: AP = 320
,09-07 13:15:52.149  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
,09-07 13:15:53.369   290   290 E SMD     : DCD OFF,
,09-07 13:15:54.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:15:55.199  5676  5676 D FactoryTest: Not factory mode
,09-07 13:15:55.199  5676  5676 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-07 13:15:55.199  5676  5676 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-07 13:15:55.199  5676  5676 D MTPRx   : still no open session command from host, so toast
,09-07 13:15:55.199  5676  5676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-07 13:15:55.209  5676  5676 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-07 13:15:55.209  5676  5676 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114952
,09-07 13:15:55.209  1014  1027 E PersonaManagerService: inState():  stateMachine is null !!
,09-07 13:15:55.209  1014  1027 I PersonaManagerService: PersonaId don't exist
09-07 13:15:55.209  1014  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-07 13:15:55.209  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 13:15:55.209  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:15:55.209  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:15:55.209  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-07 13:15:55.219  1014  1027 W ActivityManager: mDVFSHelper.acquire()
,09-07 13:15:55.239  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,09-07 13:15:55.249  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 13:15:55.249  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 13:15:55.249  1014  1027 D InputDispatcher: Focused application set to: xxxx
,09-07 13:15:55.249  1014  1027 D InputDispatcher: Focus left window: 6777
,09-07 13:15:55.249  5676  5676 E MTPRx   : started activity for popup
,09-07 13:15:55.259  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-07 13:15:55.259  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:15:55.279  5676  5676 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:15:55.299  5676  5676 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-07 13:15:55.299  1014  1438 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 13:15:55.299  1014  1438 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 13:15:55.309  1014  1438 D InputDispatcher: Focused application set to: xxxx
,09-07 13:15:55.309  1014  1438 D InputDispatcher: Focus entered window: 6777
,09-07 13:15:55.309  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 13:15:55.309  1014  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 13:15:55.309  1014  1496 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@15c08fae attribute=null, token = android.os.BinderProxy@39e56afe
09-07 13:15:55.309  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 13:15:55.359  5676  5676 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-07 13:15:55.359  5676  5676 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-07 13:15:55.359  5676  5676 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-07 13:15:55.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:15:55.389  6777  6777 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 13:15:55.389  6777  6777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-07 13:15:55.389  6777  6777 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 13:15:55.389  6777  6777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-07 13:15:55.389  1014  1480 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-07 13:15:55.389  1014  1480 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 13:15:55.389  1014  1480 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 13:15:55.389  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 13:15:55.389  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 13:15:55.409  6777  6777 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 13:15:55.409  6777  6777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 13:15:55.409  6777  6777 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fd29fa8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2a82c789, 16908290=android.view.AbsSavedState$1@2a82c789}, android:focusedViewId=100}]}]
09-07 13:15:55.409  6777  6777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-07 13:15:55.409  6777  6777 V ActivityThread: updateVisibility : ActivityRecord{52b4dbb token=android.os.BinderProxy@2d64d3ec {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-07 13:15:55.409  6777  6777 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 13:15:55.409  6777  6777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 13:15:55.409  6777  6777 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d64d3ec time:115153
,09-07 13:15:55.419  1014  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-07 13:15:56.369   290   290 E SMD     : DCD OFF
,09-07 13:15:56.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:15:56.489  1014  1330 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 13:15:56.489  1014  1330 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 13:15:56.489  1014  1330 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-07 13:15:56.489  1014  1330 D BatteryService: stay LED for fully charged
09-07 13:15:56.489  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 13:15:56.489  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 13:15:56.489  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 13:15:56.489  1014  1014 I MotionRecognitionService: Plugged
,09-07 13:15:56.499  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 13:15:56.499  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 13:15:56.499  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 13:15:56.499  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 13:15:56.499  3174  3278 D HeadsetStateMachine: Disconnected process message: 10
,09-07 13:15:56.519  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
09-07 13:15:56.519  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-07 13:15:56.519  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:15:56.519  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-07 13:15:56.519  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:15:56.959  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-07 13:15:57.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 13:15:58.219  1014  1040 W ActivityManager: mDVFSHelper.release(),
,09-07 13:15:58.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 13:15:59.369   290   290 E SMD     : DCD OFF
,09-07 13:15:59.379   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-07 13:15:59.989  1014  1093 V AlarmManager: waitForAlarm result :8
,09-07 13:16:00.259  1014  1093 V AlarmManager: waitForAlarm result :4
,09-07 13:16:00.269  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.279  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-07 13:16:00.279  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-07 13:16:00.279  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-07 13:16:00.279  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-07 13:16:00.289  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 13:16:00.299  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-07 13:16:00.299  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,09-07 13:16:00.299  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 13:16:00.309  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-07 13:16:00.309  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,09-07 13:16:00.309  1975  1975 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
09-07 13:16:00.309  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-07 13:16:00.349  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 13:16:00.359  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 13:16:00.369  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:00.369  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
09-07 13:16:00.369  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-07 13:16:00.369  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:00.369  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:00.369  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 13:16:00.389  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 13:16:00.429  4802  4802 D ConnectivityManager: CallingUid : 10011, CallingPid : 4802
,09-07 13:16:00.439  1014  1476 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 13:16:00.439  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-07 13:16:00.439  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,09-07 13:16:00.439  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-07 13:16:00.439  4802  6843 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 13:16:00.489  4802  6844 W DriveInitializer: Background init thread started
,09-07 13:16:00.519   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-07 13:16:00.519   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:00.519  4802  6844 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-07 13:16:00.589  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:00.589  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.599  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.599  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:00.599  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.609  1014  1027 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-07 13:16:00.609  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.639  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:00.639  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.639  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.639  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:00.639  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.679  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 13:16:00.689  1014  1476 I art     : Explicit concurrent mark sweep GC freed 35355(1919KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 4.200ms total 159.487ms
,09-07 13:16:00.709  4802  6847 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-07 13:16:00.709  4802  6847 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-07 13:16:00.719  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.719  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:00.719  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.789  4802  6844 W DriveInitializer: Background init thread ended
,09-07 13:16:00.819  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:00.819  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.819  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.819  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:00.819  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.869  1014  1438 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:00.869  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-07 13:16:00.869  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.869  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:00.869  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.949  1014  1095 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:00.949  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.949  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:00.949  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:00.989  1014  1095 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:00.989  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:00.989  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:00.989  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.049  1014  1095 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.049  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.049  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.049  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-07 13:16:01.049  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 13:16:01.049  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:01.049  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:01.049  1014  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:01.069  6868  6868 E Zygote  : MountEmulatedStorage()
09-07 13:16:01.069  6868  6868 E Zygote  : v2
09-07 13:16:01.069  6868  6868 I libpersona: KNOX_SDCARD checking this for 10011
09-07 13:16:01.069  6868  6868 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:01.069  1014  1095 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6868 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-07 13:16:01.069  6868  6868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:01.079  6868  6868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:01.079  6868  6868 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-07 13:16:01.099  6868  6868 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:01.109  6868  6868 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:01.129  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-07 13:16:01.129  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-07 13:16:01.169  6868  6868 I MultiDex: VM with version 2.1.0 has multidex support
09-07 13:16:01.169  6868  6868 I MultiDex: install
09-07 13:16:01.169  6868  6868 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 13:16:01.199  6868  6868 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-07 13:16:01.269  6868  6868 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-07 13:16:01.269  6868  6868 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11d9c787: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-07 13:16:01.269  6868  6868 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-07 13:16:01.279  6868  6868 D ChimeraCfgMgr: Reading stored module config
,09-07 13:16:01.289  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-07 13:16:01.299  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.309  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.309  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.309  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.309  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.309  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.309  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:01.309  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.369  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-07 13:16:01.369  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-07 13:16:01.369  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.369  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:01.369  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.379  1975  1975 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=76a7730c-3722-4351-8634-98efe7f758f6
,09-07 13:16:01.399  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 13:16:01.399  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 13:16:01.409  6868  6886 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-07 13:16:01.429  6868  6868 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-07 13:16:01.429  6868  6868 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-07 13:16:01.439  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.439  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.439  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:01.439  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.519   282   699 D WVCdm   : Instantiating CDM.
,09-07 13:16:01.519   282   282 I WVCdm   : CdmEngine::OpenSession
09-07 13:16:01.519   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-07 13:16:01.539   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-07 13:16:01.559   282   282 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-07 13:16:01.599  4320  4333 I art     : Explicit concurrent mark sweep GC freed 1423(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 677us total 21.819ms
,09-07 13:16:01.619   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-07 13:16:01.619   282   699 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-07 13:16:01.619   282   699 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-07 13:16:01.619   282   699 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-07 13:16:01.629   282   699 D WVCdm   : PrepareKeyRequest: nonce=155737092
,09-07 13:16:01.639  1014  3373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 13:16:01.669  6868  6877 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-07 13:16:01.669  6868  6877 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 13:16:01.669  6868  6877 I System.out: (HTTPLog)-Static: isShipBuild true
09-07 13:16:01.669  6868  6877 I System.out: (HTTPLog)-Thread-1226-664210744: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-07 13:16:01.669  6868  6877 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:01.669   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:01.669   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-07 13:16:01.679  1975  2149 W GCoreFlp: No location to return for getLastLocation()
,09-07 13:16:01.709  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 13:16:01.709  6777  6833 I jxcore-log: 
,09-07 13:16:01.709  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 13:16:01.709  6777  6833 I jxcore-log: 
,09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:01.719  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:01.719  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:01.719  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 13:16:01.719  6777  6833 I jxcore-log: 
,09-07 13:16:01.729  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 13:16:01.729  6777  6833 I jxcore-log: 
,09-07 13:16:01.729  1014  1429 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.729  6868  6877 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-07 13:16:01.729  6868  6877 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6868, getuid(): 10011
,09-07 13:16:01.729  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.739  1014  1429 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.739  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.739  1975  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 13:16:01.739  1014  1095 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.749  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.749  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.749  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 13:16:01.749  1014  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:01.759  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.759  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.759  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.759  4802  6864 D UdcContextInitService: registered all accounts: true
,09-07 13:16:01.769  1975  2167 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-07 13:16:01.899  1014  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:01.899  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-07 13:16:01.899  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.899  1014  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.899  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:01.969  1014  1429 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-07 13:16:01.969  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-07 13:16:01.969  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:01.969  1014  1429 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:01.969  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.049  1975  6896 I art     : Explicit concurrent mark sweep GC freed 56974(3MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.418ms total 82.476ms
,09-07 13:16:02.079  1014  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.079  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.079  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.079  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.089  6868  6877 I qtaguid : Untagging socket 30
,09-07 13:16:02.099  1014  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.099  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.099  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.099  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.149  1014  3356 D SSRM:n  : SIOP:: AP = 330
,09-07 13:16:02.159  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.159  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.159  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.159  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.159  1975  6898 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-07 13:16:02.159  1975  6896 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 13:16:02.159  1014  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.159  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.159  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.169  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.259  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.259  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:02.259  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.259  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.259  1975  6898 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-07 13:16:02.259  1975  6896 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 13:16:02.259  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.259  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:02.259  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.259  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.289  1014  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:02.289  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.289  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.289  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.289  1975  6898 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-07 13:16:02.289  1975  6896 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-07 13:16:02.289  1975  6896 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-07 13:16:02.299  1975  6896 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 13:16:02.339  1014  1429 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 13:16:02.379   290   290 E SMD     : DCD OFF
,09-07 13:16:02.399  1014  1496 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-07 13:16:02.399  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-07 13:16:02.399  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:02.399  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:02.399  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:02.439  1975  6896 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-07 13:16:02.439  1975  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 13:16:02.439  1975  6896 I System.out: (HTTPLog)-Static: isShipBuild true
09-07 13:16:02.439  1975  6896 I System.out: (HTTPLog)-Thread-277-320949950: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-07 13:16:02.439  1975  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:02.439   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:02.439   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-07 13:16:02.439  1975  6896 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-07 13:16:02.439  1975  6896 I qtaguid : Tagging socket 69 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1975, getuid(): 10011
,09-07 13:16:02.489  1975  6896 I qtaguid : Tagging socket 72 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1975, getuid(): 10011
,09-07 13:16:02.519  6777  6833 D executeNativeTests: Running unit tests
,09-07 13:16:02.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:02.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e added. We now have 2 listener(s)
,09-07 13:16:02.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 13:16:02.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:02.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:02.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:02.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f added. We now have 2 listener(s)
09-07 13:16:02.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:02.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:02.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:02.629  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:02.629  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:02.629  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:02.629  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.639  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 13:16:02.639  6777  6833 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 13:16:02.639  6777  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 13:16:02.639  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:02.639  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:02.639  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:02.639  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e removed from the list
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f removed from the list
09-07 13:16:02.639  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:02.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.639  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:02.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.639  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 13:16:02.649  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:02.649  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:02.649  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:02.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:02.649  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:02.649  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:02.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.649  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:02.649  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:02.649  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:02.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:02.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.649  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 13:16:02.649  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 13:16:02.649  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:02.659  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:02.659  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:02.659  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.659  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:02.659  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:02.659  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:02.659  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:02.659  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.659  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:02.659  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.659  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.659  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:02.659  6777  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 13:16:02.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:02.659  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:02.669  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-07 13:16:02.669  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:16:02.669  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:02.669  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:02.669  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 13:16:02.669  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:02.669  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:02.669  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 13:16:02.669  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.669  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.679  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:16:02.689  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:16:02.689  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-07 13:16:02.689  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 13:16:02.689  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 13:16:02.689  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 13:16:02.689  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:02.719  3174  3182 D BtGatt.GattService: registerClient() - UUID=ce0e881b-898f-4fe5-832a-4222b014e8b8
,09-07 13:16:02.769  3174  3270 D BtGatt.GattService: onClientRegistered() - UUID=ce0e881b-898f-4fe5-832a-4222b014e8b8, clientIf=6
,09-07 13:16:02.779  6777  6785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,09-07 13:16:02.779  3174  3185 D BtGatt.GattService: start scan with filters
,09-07 13:16:02.779  3174  3276 D BtGatt.ScanManager: handling starting scan
,09-07 13:16:02.779  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 13:16:02.779  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 13:16:02.779  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 13:16:02.779  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:02.789  3174  3276 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:02.789  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:02.789  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 13:16:02.789  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:02.789  3174  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 13:16:02.789  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:02.789  3174  3276 D BtGatt.ScanManager: allow scan with filters
09-07 13:16:02.789  3174  3276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 13:16:02.799  3174  3276 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-07 13:16:02.799  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 13:16:02.799  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.799  3174  3276 D BtGatt.ScanManager: Starting BLE batch scan
09-07 13:16:02.799  3174  3276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:02.799  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:02.799  3174  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 13:16:02.799  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.809  6777  6833 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 13:16:02.809  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-07 13:16:02.809  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.809  1014  1476 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 13:16:02.809  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:02.809  6777  6833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:02.809  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:02.809  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:02.809  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.809  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:02.809  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:02.809  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:02.809  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:02.809  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 13:16:02.809  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:02.809  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 13:16:02.819  3174  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-07 13:16:02.819  3174  3276 D BtGatt.ScanManager: filter size is 1
09-07 13:16:02.819  3174  3276 D BtGatt.ScanManager: delete FilterIndex - 3
,09-07 13:16:02.819  3174  3182 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 13:16:02.819  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 13:16:02.819  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.819  3174  3276 D BtGatt.ScanManager: stopping BLe Batch
,09-07 13:16:02.819  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:02.819  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 13:16:02.819  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 13:16:02.819  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:02.819  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 13:16:02.819  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-07 13:16:02.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:02.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:16:02.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 13:16:02.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:02.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:02.829  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:02.829  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:02.829  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:02.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.829  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:02.829  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:02.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:02.829  6777  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 13:16:02.829  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 13:16:02.829  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.829  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:02.829  3174  3276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 13:16:02.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:02.829  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:02.829  3174  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 13:16:02.829  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:02.839  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:02.839  1975  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:02.839  1975  6896 I qtaguid : Tagging socket 69 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1975, getuid(): 10011
,09-07 13:16:02.839  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:02.839  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:16:02.839  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:02.839  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:02.839  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:02.839  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:02.839  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:02.839  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.849  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 13:16:02.849  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.849  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:16:02.849  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:16:02.849  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 13:16:02.849  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 13:16:02.849  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:02.859  3174  3182 D BtGatt.GattService: registerClient() - UUID=75262fb8-3ce1-42f4-a29b-2f94dcadcfc0
,09-07 13:16:02.899  3174  3270 D BtGatt.GattService: onClientRegistered() - UUID=75262fb8-3ce1-42f4-a29b-2f94dcadcfc0, clientIf=6
,09-07 13:16:02.899  6777  6785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 13:16:02.899  6904  6904 I dex2oat : ----------------------------------------------------
09-07 13:16:02.899  6904  6904 I dex2oat : <SS>: S T A R T I N G . . .
09-07 13:16:02.899  6904  6904 I dex2oat : <SS>: Zip is absent. Canceled.
09-07 13:16:02.899  6904  6904 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-07 13:16:02.899  3174  3358 D BtGatt.GattService: start scan with filters
,09-07 13:16:02.899  3174  3276 D BtGatt.ScanManager: handling starting scan
,09-07 13:16:02.899  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 13:16:02.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 13:16:02.899  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 13:16:02.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:02.909  3174  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 13:16:02.909  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.909  3174  3276 D BtGatt.ScanManager: allow scan with filters
09-07 13:16:02.909  3174  3276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 13:16:02.909  3174  3276 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-07 13:16:02.909  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 13:16:02.909  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:02.909  3174  3276 D BtGatt.ScanManager: Starting BLE batch scan
09-07 13:16:02.909  3174  3276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:02.909  3174  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 13:16:02.909  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.919  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:02.919  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:02.919  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 13:16:02.919  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:02.919  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 13:16:02.919  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:02.929  6777  6833 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 13:16:02.929  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:02.929  6777  6833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:02.929  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:02.929  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:02.929  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 13:16:02.929  3174  3182 D BtGatt.GattService: stopScan() - queue size =1
,09-07 13:16:02.929  3174  3276 D BtGatt.ScanManager: filter size is 1
09-07 13:16:02.929  3174  3276 D BtGatt.ScanManager: delete FilterIndex - 4
,09-07 13:16:02.929  3174  3358 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 13:16:02.929  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 13:16:02.929  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:02.929  3174  3276 D BtGatt.ScanManager: stopping BLe Batch
09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 13:16:02.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:02.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:16:02.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:02.939  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 13:16:02.939  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.939  3174  3276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 13:16:02.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:02.939  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:02.939  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:02.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.939  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:02.939  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.939  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:02.939  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:02.939  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:02.939  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:02.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:02.939  3174  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 13:16:02.939  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:02.949  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:02.949  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:02.949  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:02.949  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:02.949  6777  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 13:16:02.949  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:02.949  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:02.959  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:02.959  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:02.959  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:02.959  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:02.959  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:02.959  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:02.959  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:02.959  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.959  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 13:16:02.959  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:02.969  6904  6904 I dex2oat : dex2oat took 66.066ms (threads: 4)
,09-07 13:16:02.969  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:16:02.969  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:16:02.969  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 13:16:02.979  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 13:16:02.979  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:02.979  1014  1479 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-07 13:16:02.979  3174  3182 D BtGatt.GattService: registerClient() - UUID=7dbab401-375b-43bd-b066-69476b73e67b
,09-07 13:16:02.979  6868  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 13:16:02.979  6868  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 13:16:02.979  6868  6877 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 13:16:02.979  6868  6877 I Adreno-EGL: Local Branch: 
09-07 13:16:02.979  6868  6877 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 13:16:02.979  6868  6877 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 13:16:02.979  6868  6877 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 13:16:02.989  1975  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:02.989  1975  6896 I qtaguid : Tagging socket 69 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1975, getuid(): 10011
,09-07 13:16:03.019  3174  3270 D BtGatt.GattService: onClientRegistered() - UUID=7dbab401-375b-43bd-b066-69476b73e67b, clientIf=6,
09-07 13:16:03.019  6777  6785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-07 13:16:03.019  3174  3358 D BtGatt.GattService: start scan with filters
09-07 13:16:03.019  3174  3276 D BtGatt.ScanManager: handling starting scan
,09-07 13:16:03.019  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 13:16:03.019  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 13:16:03.019  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 13:16:03.019  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:03.029  3174  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 13:16:03.029  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:03.029  3174  3276 D BtGatt.ScanManager: allow scan with filters
,09-07 13:16:03.029  3174  3276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 13:16:03.029  3174  3276 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-07 13:16:03.029  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 13:16:03.029  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 13:16:03.029  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:03.029  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 13:16:03.029  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:03.029  3174  3276 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 13:16:03.029  3174  3276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:03.039  3174  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 13:16:03.039  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:03.039  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:03.039  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 13:16:03.039  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:03.039  6777  6833 I io.jxcore.node.ConnectionHelper: start: OK
09-07 13:16:03.039  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.039  6777  6833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:03.039  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.039  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:03.039  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.039  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:03.039  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:03.039  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:03.039  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:03.039  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:03.039  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:03.039  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 13:16:03.039  3174  3185 D BtGatt.GattService: stopScan() - queue size =1
,09-07 13:16:03.039  3174  3276 D BtGatt.ScanManager: filter size is 1
,09-07 13:16:03.049  3174  3276 D BtGatt.ScanManager: delete FilterIndex - 5
,09-07 13:16:03.049  3174  3182 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 13:16:03.049  3174  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 13:16:03.049  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 13:16:03.049  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:03.049  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 13:16:03.049  3174  3276 D BtGatt.ScanManager: stopping BLe Batch
,09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 13:16:03.049  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 13:16:03.049  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:03.049  3174  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-07 13:16:03.049  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:03.049  3174  3276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 13:16:03.049  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 13:16:03.049  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:03.049  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:03.049  3174  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 13:16:03.049  3174  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:03.049  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.049  6777  6833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.059  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.059  6777  6833 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 13:16:03.059  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
,09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.059  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.059  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-07 13:16:03.059  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.059  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
,09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.059  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.059  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.059  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.059  6868  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 13:16:03.059  6868  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 13:16:03.059  6868  6877 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 13:16:03.059  6868  6877 I Adreno-EGL: Local Branch: 
09-07 13:16:03.059  6868  6877 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 13:16:03.059  6868  6877 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 13:16:03.059  6868  6877 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.059  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.059  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.069  6777  6833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
09-07 13:16:03.069  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.069  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.069  6777  6833 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 13:16:03.069  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.069  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:16:03.069  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:03.069  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:16:03.069  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:03.069  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.069  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.069  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:03.069  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.069  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.069  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.069  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.079  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.079  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.079  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:03.079  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.079  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:03.079  6777  6833 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 13:16:03.079  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:03.079  6777  6833 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 13:16:03.079  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 13:16:03.079  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 13:16:03.079  6777  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:16:03.079  6777  6833 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 13:16:03.079  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:03.079  6777  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:16:03.079  6777  6833 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-07 13:16:03.079  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:03.079  6777  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:16:03.079  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 13:16:03.089  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 13:16:03.089  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 13:16:03.089  6777  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:03.089  6777  6833 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 13:16:03.089  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.089  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:03.089  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.089  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.089  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.089  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 13:16:03.089  6777  6913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1315)
09-07 13:16:03.089  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.089  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.089  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.089  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.089  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.089  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.089  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.089  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.089  6777  6833 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-07 13:16:03.089  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.089  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.089  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.089  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:03.089  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.099  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.099  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.099  6777  6833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-07 13:16:03.099  6777  6914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1315
09-07 13:16:03.099  6777  6914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1315)
09-07 13:16:03.099  6777  6914 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@546be69, channel: -1, state: INIT
09-07 13:16:03.099  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.099  6777  6914 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@546be69, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
,09-07 13:16:03.099  6777  6914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1315)
09-07 13:16:03.099  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.099  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.099  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.099  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.099  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.099  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.099  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:03.099  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.099  6777  6913 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 13:16:03.099  6777  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:03.099  6777  6833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:16:03.099  6777  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:03.099  6777  6833 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:16:03.099  6777  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 13:16:03.099  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:03.099  6777  6833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 13:16:03.099  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.099  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.099  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.109  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6913 D BluetoothSocket: connect(): myUserId = 0
09-07 13:16:03.109  6777  6913 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@546be69, channel: -1, state: CLOSED
09-07 13:16:03.109  6777  6913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1315)
,09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
,09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.109  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.109  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.109  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.109  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.109  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.109  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.1,09  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.109  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.109  6868  6877 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 13:16:03.109  6868  6877 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 13:16:03.109  6868  6877 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 13:16:03.109  6868  6877 I Adreno-EGL: Local Branch: 
09-07 13:16:03.109  6868  6877 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 13:16:03.109  6868  6877 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 13:16:03.109  6868  6877 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.109  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.109  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 13:16:03.119  6777  6777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 13:16:03.119  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.119  6777  6777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 13:16:03.119  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:03.119  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.119  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.119  6777  6915 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:03.119  6777  6915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:16:03.129  6777  6915 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-07 13:16:03.129  6777  6915 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:03.129  6777  6915 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:03.129  6777  6915 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b5940ee
09-07 13:16:03.129  6777  6915 D BluetoothSocket: channel: 6
09-07 13:16:03.129  6777  6915 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cdd598f, channel: 6, state: LISTENING
09-07 13:16:03.129  6777  6915 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cdd598f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b5940ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f22e41cmSocket: android.net.LocalSocket@1d03d825 impl:android.net.LocalSocketImpl@181c7dfa fd:FileDescriptor[105]
09-07 13:16:03.129  6777  6915 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d03d825 impl:android.net.LocalSocketImpl@181c7dfa fd:FileDescriptor[105]
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.139  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:03.139  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.139  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:03.139  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:03.139  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.139  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.139  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.139  6777  6833 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 13:16:03.139  6777  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:03.139  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:16:03.139  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.139  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.139  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.139  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.139  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.139  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.139  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.139  6777  6915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 13:16:03.139  6777  6915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 13:16:03.139  6777  6915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 13:16:03.139  6777  6777 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.149  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.149  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:03.149  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:03.149  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a34c3e not in the list
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:03.149  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:03.149  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:03.149  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b68a9f not in the list
09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:03.149  6777  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 13:16:03.149  6777  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 13:16:03.149  6777  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 13:16:03.149  6777  6833 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 13:16:03.159  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:03.159  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bdfffab added. We now have 2 listener(s)
09-07 13:16:03.159  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:03.159  1014  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 13:16:03.159  6777  6833 D BluetoothAdapter: enable()
09-07 13:16:03.159  6777  6833 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 13:16:03.169  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 13:16:03.169  1014  1026 D WifiService: setWifiEnabled: true pid=6777, uid=10171
09-07 13:16:03.169  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 13:16:03.169  1014  1026 D SecContentProvider2: mCursor = null
09-07 13:16:03.169  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 13:16:03.169  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
09-07 13:16:03.169  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 13:16:03.169  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 13:16:03.169  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 13:16:03.169  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 13:16:03.169  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 13:16:03.169  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 13:16:03.169  1014  1026 D SettingsProvider: name = wifi_on
09-07 13:16:03.169  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:03.169  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7882608 added. We now have 3 listener(s)
09-07 13:16:03.169  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:03.179  1975  6896 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 13:16:03.179  1975  6896 I qtaguid : Tagging socket 69 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1975, getuid(): 10011
09-07 13:16:03.179  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:03.179  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22bed1a1 added. We now have 4 listener(s)
09-07 13:16:03.179  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:03.189  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:03.189  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a47fc6 added. We now have 5 listener(s)
09-07 13:16:03.189  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:03.189  1014  1496 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 13:16:03.189  1014  1496 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 13:16:03.189  1014  1496 D SecContentProvider2: mCursor = null
,09-07 13:16:03.189  1014  1496 D WifiService: setWifiEnabled: false pid=6777, uid=10171
09-07 13:16:03.189  1014  1496 D SettingsProvider: name = wifi_on
,09-07 13:16:03.189   282   680 I WVCdm   : CdmEngine::CloseSession
,09-07 13:16:03.199  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 13:16:03.199  6777  6833 D BluetoothAdapter: disable(),
09-07 13:16:03.199  1376  1376 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 13:16:03.199  1376  1376 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-07 13:16:03.199  1014  1480 D SettingsProvider: name = bluetooth_on
,09-07 13:16:03.199  1376  1376 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 13:16:03.199  1376  1376 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 13:16:03.199   282   680 I WVCdm   : L3 Terminate.
,09-07 13:16:03.209  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:03.209  3174  3267 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-07 13:16:03.209  3174  3267 D BluetoothAdapterProperties: Setting state to 13
09-07 13:16:03.209  3174  3267 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 13:16:03.209  3174  3267 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:03.209  3174  3267 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 13:16:03.209  1014  1429 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:03.209  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.219  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:03.219  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.219  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.219  3174  3174 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 13:16:03.219  3174  3267 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:03.219  3174  3267 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 13:16:03.219  3174  3267 D BluetoothAdapterService: terminating service from this receiver
09-07 13:16:03.219  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.219  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:03.219  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.219  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.219  3174  3267 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 13:16:03.219  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:03.219  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:03.219  3174  3267 D BluetoothAdapterProperties: mDiscovering is false
09-07 13:16:03.219  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16dd095, channel: 19, state: LISTENING
09-07 13:16:03.219  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16dd095, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39a422dd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@398d65aamSocket: android.net.LocalSocket@21aa459b impl:android.net.LocalSocketImpl@27970d38 fd:FileDescriptor[74]
09-07 13:16:03.219  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21aa459b impl:android.net.LocalSocketImpl@27970d38 fd:FileDescriptor[74]
09-07 13:16:03.219  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-07 13:16:03.219  3174  3267 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 13:16:03.219  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:16:03.219  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:03.219  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:03.229  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:03.229  3174  3270 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 13:16:03.229  3174  3270 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:03.229  1975  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 13:16:03.229  3063  3063 D BluetoothPbap: Proxy object disconnected
09-07 13:16:03.229  3063  3063 D PbapServerProfile: Bluetooth service disconnected
,09-07 13:16:03.229   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:03.229   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-07 13:16:03.229  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:03.229  1975  6866 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-07 13:16:03.229  1975  6866 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1975, getuid(): 10011
,09-07 13:16:03.239  3174  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-07 13:16:03.239  3174  3267 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-07 13:16:03.239  3174  3267 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-07 13:16:03.239  3174  3267 E bt-btif : BTA got event 0x1a12
,09-07 13:16:03.239  3174  3291 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-07 13:16:03.239  3174  3291 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 13:16:03.239  3174  3267 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:16:03.239  1014  1125 E WifiNative-wlan0: do suspend true
09-07 13:16:03.239  3174  5233 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:16:03.239  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-07 13:16:03.239  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:03.239  3174  3291 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 13:16:03.239  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.249  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:03.249  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:03.249  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:03.249  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.269  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:03.269  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-07 13:16:03.269  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-07 13:16:03.269  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:03.279  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:03.279  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:03.279  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-07 13:16:03.279  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:03.279  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 13:16:03.279  1014  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:03.279  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 13:16:03.279  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c343276, channel: 5, state: LISTENING
,09-07 13:16:03.289  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c343276, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21705e52, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6dda077mSocket: android.net.LocalSocket@64bc4e4 impl:android.net.LocalSocketImpl@30987d4d fd:FileDescriptor[76],
09-07 13:16:03.289  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@64bc4e4 impl:android.net.LocalSocketImpl@30987d4d fd:FileDescriptor[76]
09-07 13:16:03.289  1014  1330 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 13:16:03.289  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:03.289  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 13:16:03.289  3174  3174 I BtOppRfcommListener: stopping Accept Thread
,09-07 13:16:03.289  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1da90002, channel: 12, state: LISTENING
09-07 13:16:03.289  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1da90002, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf0b84c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2281cd13mSocket: android.net.LocalSocket@2d724b50 impl:android.net.LocalSocketImpl@3c7ca149 fd:FileDescriptor[80]
,09-07 13:16:03.289  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d724b50 impl:android.net.LocalSocketImpl@3c7ca149 fd:FileDescriptor[80]
,09-07 13:16:03.289  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:03.299  3174  5233 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 13:16:03.299  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.299  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.299  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.299  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:03.299  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:03.299  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.299  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:03.299  1014  1429 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 13:16:03.299  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.309  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.309  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:03.309  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:03.309  3174  3174 V BluetoothOppManager: cleanUp...
,09-07 13:16:03.319  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:03.319  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:03.329  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:03.329  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 13:16:03.329  1014  1436 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 13:16:03.329  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.329  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.329  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.329  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.349  6924  6924 E Zygote  : MountEmulatedStorage()
09-07 13:16:03.349  6924  6924 E Zygote  : v2
09-07 13:16:03.349  6924  6924 I libpersona: KNOX_SDCARD checking this for 10055
,09-07 13:16:03.349  6924  6924 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:03.349  1014  1436 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6924 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,09-07 13:16:03.349  6924  6924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:03.359  6924  6924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:03.359  6924  6924 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:03.389  6924  6924 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:03.389  6924  6924 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:03.419  6924  6924 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:03.439  3174  3291 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 13:16:03.439  3174  3291 W bt-btif : ag scb idx 1 not allocated
09-07 13:16:03.439  3174  3291 W bt-btif : ag scb idx 2 not allocated
09-07 13:16:03.439  3174  3291 E bt-btif : BTA AG is already disabled, ignoring ...
,09-07 13:16:03.439  3174  3348 I bt_userial_mct: exiting userial_read_thread
09-07 13:16:03.439  3174  3348 D bt_userial_mct: Leaving userial_evt_read_thread(),
09-07 13:16:03.439  3174  3270 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 13:16:03.439  3174  3293 I bt_vendor: hw_epilog_process
,09-07 13:16:03.439  3174  3270 D bt_userial_mct: userial_close
09-07 13:16:03.439  3174  3270 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-07 13:16:03.449  6924  6924 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,09-07 13:16:03.449  6924  6924 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
09-07 13:16:03.449  6924  6924 D UserAnalysis: Create SecureDbHelper
,09-07 13:16:03.459  6924  6924 D IntelligenceServiceApplication: onCreate()
,09-07 13:16:03.459  1014  1476 I ActivityManager: Killing 6479:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-07 13:16:03.469  6924  6924 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-07 13:16:03.469  1014  1436 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-07 13:16:03.469  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.469  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.469  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.469  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.489  6943  6943 E Zygote  : MountEmulatedStorage(),
09-07 13:16:03.489  6943  6943 E Zygote  : v2
09-07 13:16:03.489  6943  6943 I libpersona: KNOX_SDCARD checking this for 10105
,09-07 13:16:03.489  6943  6943 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:03.489  6943  6943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:03.489  1014  1436 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6943 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-07 13:16:03.489  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-07 13:16:03.489  6943  6943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:03.489  6924  6924 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-07 13:16:03.489  6943  6943 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 13:16:03.499  6924  6924 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 13:16:03.509  6943  6943 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:03.509  6943  6943 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:03.619   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 13:16:03.619   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:03.619  6943  6962 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 13:16:03.629   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 13:16:03.629   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:03.629  6943  6962 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 13:16:03.639  6777  6777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 13:16:03.659  3174  3270 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 13:16:03.659  3174  3270 I bt_vendor: bluetooth satus is on,
09-07 13:16:03.659  3174  3270 I bt_vendor: bt-vendor : resetting BT status
09-07 13:16:03.659  3174  3270 I bt_vendor: Starting hciattach daemon
09-07 13:16:03.659  3174  3270 I bt_vendor: try to set false
09-07 13:16:03.659  3174  3270 I bt_vendor: Starting hciattach daemon
09-07 13:16:03.659  3174  3270 I bt_vendor: try to set false
,09-07 13:16:03.659  3174  3270 I bt_vendor: cleanup
,09-07 13:16:03.659  3174  3291 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-07 13:16:03.659  3174  3270 I GKI_LINUX: GKI_exit_task 0 done
09-07 13:16:03.659  3174  3270 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-07 13:16:03.669  3174  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-07 13:16:03.669  3174  3267 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 13:16:03.669  3174  3267 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-07 13:16:03.669  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-07 13:16:03.669  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 13:16:03.669  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-07 13:16:03.679  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:03.679  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.679  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.679  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:03.679  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.679  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 13:16:03.679  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:03.679  3174  3174 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:03.689  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:03.689  3174  3174 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 13:16:03.689  3174  3174 D BtGatt.GattService: stop()
09-07 13:16:03.689  3174  3174 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 13:16:03.689  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:03.689  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.689  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.689  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.689  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.689  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:03.689  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 13:16:03.689  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:03.689  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:03.689  1014  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:03.689  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.699  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.699  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.699  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.699  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-07 13:16:03.699  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 13:16:03.699  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 13:16:03.699  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:03.699  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.699  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
09-07 13:16:03.699  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:03.699  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.699  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 13:16:03.699  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 13:16:03.709  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 13:16:03.709  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:03.709  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.709  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:03.709  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.709  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.709  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-07 13:16:03.709  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 13:16:03.709  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 13:16:03.709  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:03.709  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.709  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.719  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:03.719  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-07 13:16:03.719  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.719  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:03.719  3174  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:03.719  1014  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:03.719  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.719  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.719  1014  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.719  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:03.719  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 13:16:03.719  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 13:16:03.719  3174  3267 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 13:16:03.719  1014  1429 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:03.719  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.729  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.729  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:03.729  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:03.729  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:03.729  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 13:16:03.729  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 13:16:03.729  3174  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 13:16:03.729  3174  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 13:16:03.729  3174  3267 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 13:16:03.729  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-07 13:16:03.729  3174  3174 D HeadsetService: Received stop request...Stopping profile...
,09-07 13:16:03.729  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea,
,09-07 13:16:03.739  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 13:16:03.739  3174  3174 D A2dpService: Received stop request...Stopping profile...
09-07 13:16:03.739  3063  3063 D HeadsetProfile: Bluetooth service disconnected
,09-07 13:16:03.739  3174  3282 D A2dpStateMachine: Exit Disconnected: -1
,09-07 13:16:03.739  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:03.739  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:03.739  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 13:16:03.739  3174  3174 D HidService: Received stop request...Stopping profile...
09-07 13:16:03.739  3174  3174 D HidService: Stopping Bluetooth HidService
09-07 13:16:03.739  3174  3174 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 13:16:03.739  3174  3174 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 13:16:03.739  3174  3174 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 13:16:03.739  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:03.749  3063  3063 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:03.749  3063  3063 D A2dpProfile: Bluetooth service disconnected
,09-07 13:16:03.749  3174  3174 D HealthService: Received stop request...Stopping profile...
09-07 13:16:03.749  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:03.749  3063  3063 D BluetoothInputDevice: Proxy object disconnected
09-07 13:16:03.749  3063  3063 D HidProfile: Bluetooth service disconnected
,09-07 13:16:03.749  3174  3174 D PanService: Received stop request...Stopping profile...
09-07 13:16:03.749  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:03.749  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:16:03.749  3063  3063 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:16:03.749  3063  3063 D PanProfile: Bluetooth service disconnected
09-07 13:16:03.749  3174  3174 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 13:16:03.749  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:03.749  3063  3063 D BluetoothMap: Proxy object disconnected
09-07 13:16:03.749  3063  3063 D MapProfile: Bluetooth service disconnected
,09-07 13:16:03.749  3174  3174 D SapService: Received stop request...Stopping profile...
09-07 13:16:03.749  3174  3174 D SapService: Stopping Bluetooth SapService
09-07 13:16:03.749  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 13:16:03.759  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 13:16:03.759  3063  3063 D SapProfile: Bluetooth service disconnected
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 13:16:03.759  3174  3174 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 13:16:03.759  3174  3174 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 13:16:03.759  3174  3174 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 13:16:03.759  3174  3283 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-07 13:16:03.759  3174  3174 I GKI_LINUX: GKI_exit_task 2 done
09-07 13:16:03.759  3174  3174 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 13:16:03.759  3174  3174 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:03.759  3174  3174 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 13:16:03.759  3174  3174 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:03.759  3174  3174 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-07 13:16:03.759  3174  3174 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 13:16:03.759  3174  3174 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 13:16:03.759  3174  3174 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 13:16:03.769  3174  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-07 13:16:03.769  3174  3267 D BluetoothAdapterProperties: Setting state to 10
09-07 13:16:03.769  3174  3267 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 13:16:03.769  3174  3267 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:03.769  3174  3267 D BluetoothAdapterService: updateAdapterState state is 10
09-07 13:16:03.769  3174  3267 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:03.769  3174  3267 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 13:16:03.769  3174  3267 I BluetoothAdapterState: Entering OffState
09-07 13:16:03.769  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 13:16:03.769  1441  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:03.769  1441  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.779  1174  4448 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:03.779  1174  4448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.779  1975  2156 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:03.779  1975  2156 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.779  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:03.779  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.779  1452  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:03.779  1452  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.779  3063  3071 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 13:16:03.779  3063  3072 D Bluetoothsap: onBluetoothStateChange: up=false
09-07 13:16:03.779  3063  3072 D Bluetoothsap: Unbinding service...
,09-07 13:16:03.789  3063  3072 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 13:16:03.789  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 13:16:03.789  1430  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:03.789  1430  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.789  6777  6785 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:03.789  6777  6785 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:03.789  6777  6785 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 13:16:03.789  6777  6785 D BluetoothLeAdvertiser: Exit stop advertising
09-07 13:16:03.789  6777  6785 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 13:16:03.789  6777  6785 D BluetoothLeScanner: Exiting stopAllScan
,09-07 13:16:03.789  3174  3358 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 13:16:03.789  3063  3072 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:03.789  3063  3072 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.789  3174  3185 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:03.789  3174  3185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 13:16:03.799  3063  3071 D BluetoothA2dp: onBluetoothStateChange: up=false,
09-07 13:16:03.799  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-07 13:16:03.799  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 13:16:03.809  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:03.809  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-07 13:16:03.809  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 13:16:03.819  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
09-07 13:16:03.819  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 13:16:03.819  1174  1710 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:03.819  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:03.819  1174  1174 D BluetoothTile:  getBluetoothState : 10
,09-07 13:16:03.819  1174  1710 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:03.819  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
09-07 13:16:03.819  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:03.819  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 13:16:03.819  1014  1438 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:03.829  1014  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 13:16:03.829  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-07 13:16:03.829  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:03.829  1975  2158 D BluetoothAdapter: 743654442: getState() :  mService = null. Returning STATE_OFF
09-07 13:16:03.829  1975  2158 D BluetoothAdapter: 743654442: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:03.829  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.839  1014  1429 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:03.839  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.839  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:03.839  1014  1429 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:03.839  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 13:16:03.839  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:03.839  3174  3270 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 13:16:03.849  3174  3174 I GKI_LINUX: GKI_exit_task 1 done
09-07 13:16:03.849  3174  3174 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-07 13:16:03.849  3174  3174 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 13:16:03.849  3174  3174 I art     : System.exit called, status: 0
,09-07 13:16:03.849  3174  3174 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 13:16:03.899  1376  1376 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,09-07 13:16:03.899  1014  1124 D WifiP2pService: InactiveState{ what=147461 },
09-07 13:16:03.899   277   996 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:16:03.899  1014  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
09-07 13:16:03.899  1014  1124 D WifiP2pService: DefaultState{ what=147461 }
09-07 13:16:03.909  1975  3018 V NativeCrypto: Read error: ssl=0xb90480a8: I/O error during system call, Connection timed out
09-07 13:16:03.899  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
09-07 13:16:03.899  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=268 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:03.909  6943  6943 D StrictMode: ,	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145),
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=267 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 13:16:03.909  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=266 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=264 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.DataInp,utStream.read(DataInputStream.java:63)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  1014  1095 I ActivityManager: Killing 6381:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-07 13:16:03.909  1975  3018 V NativeCrypto: SSL shutdown failed: ssl=0xb90480a8: I/O error during system call, Broken pipe
09-07 13:16:03.919  1014  1476 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=261 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 13:16:03.909  6943  6943 D StrictMode: 	,at com.google.q.k.c(PG:18147)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=220 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  69,43 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  6943  6943 D StrictMode: StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:03.909  6943  6943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:03.909  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:03.909  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-07 13:16:03.909  1975  3018 E GCM     : Wifi connection closed with errorCode 20
09-07 13:16:03.909  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:03.909  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 13:16:03.909  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.909  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.909  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.909  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.919  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:03.919  1975  6866 I qtaguid : Untagging socket 68
09-07 13:16:03.919  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-07 13:16:03.929  1975  6896 D Uploader: Network request failed class javax.net.ssl.SSLException(Read error: ssl=0xb91a6f58: I/O error during system call, Connection timed out)
,09-07 13:16:03.929  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:03.929  1014  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 13:16:03.929  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:03.939  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:03.939  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:03.939  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:03.939  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:03.939  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:03.949  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:03.949  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 13:16:03.949  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-30ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
09-07 13:16:03.949  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-30ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:03.949  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation,
09-07 13:16:03.949  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:03.949  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-07 13:16:03.949  1014  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 13:16:03.949  1014  1757 I qtaguid : Tagging socket 343 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,09-07 13:16:03.949  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 13:16:03.949  1014  1757 I qtaguid : Untagging socket 343
,09-07 13:16:03.949  1014  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:03.959  1975  6866 W GLSUser : [AppCertManager] IOException while requesting key: 
09-07 13:16:03.959  1975  6866 W GLSUser : java.net.SocketTimeoutException: failed to connect to android.clients.google.com/216.58.214.238 (port 443) after 30000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:236)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dja.a(:com.google.android.gms:233)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at jch.run(:com.google.android.gms:17)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
09-07 13:16:03.959  1975  6866 W GLSUser : Caused by: android.system.ErrnoException: isConnected fail,ed: ETIMEDOUT (Connection timed out)
09-07 13:16:03.959  1975  6866 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
09-07 13:16:03.959  1975  6866 W GLSUser : 	... 32 more
09-07 13:16:03.959  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:03.959  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:03.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:03.959  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-07 13:16:03.959  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 13:16:03.959  1014  1438 I ActivityManager: Process com.android.bluetooth (pid 3174)(adj 0) has died(31,708)
,09-07 13:16:03.969  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-07 13:16:03.969  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,09-07 13:16:03.969  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:03.979  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-07 13:16:03.979  1014  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:16:03.979  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 13:16:03.979  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:16:03.979  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-07 13:16:03.989  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-07 13:16:03.989  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.989  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.989  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:03.989  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:03.989  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 13:16:03.989  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 13:16:04.009  6984  6984 E Zygote  : MountEmulatedStorage()
09-07 13:16:04.009  6984  6984 E Zygote  : v2
,09-07 13:16:04.009  6984  6984 I libpersona: KNOX_SDCARD checking this for 1002
09-07 13:16:04.009  6984  6984 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:04.009  1014  1479 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6984 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-07 13:16:04.009  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:04.019  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:04.019  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:04.019  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
09-07 13:16:04.019  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 13:16:04.019  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 13:16:04.019  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:04.019  1014  1045 D WifiDisplayController: disconnect
09-07 13:16:04.019  1014  1045 D WifiDisplayController: updateConnection
09-07 13:16:04.019  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:04.019  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 13:16:04.019  1014  1124 D WifiP2pService: P2pDisablingState
09-07 13:16:04.019  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 13:16:04.019  1014  1124 D WifiP2pService: p2p socket connection lost
,09-07 13:16:04.019  1014  1124 D WifiP2pService: P2pDisabledState
09-07 13:16:04.019  1014  1125 E WifiNative-wlan0: do suspend true
,09-07 13:16:04.029  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 13:16:04.029  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 13:16:04.029  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 13:16:04.029  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 13:16:04.029  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 13:16:04.049  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:04.049  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 13:16:04.049  1975  2167 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-07 13:16:04.049  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 13:16:04.049  6984  6984 D ActivityThread: Added TimaKeyStore provider
09-07 13:16:04.049  1975  2167 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-07 13:16:04.059  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-07 13:16:04.059  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-07 13:16:04.059  6943  6970 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 13:16:04.069  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:04.069  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:04.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:04.069  1975  2167 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-07 13:16:01.866+0200, stopTime=2016-09-07 13:16:04.074+0200, duration=2208ms
,09-07 13:16:04.069   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:04.069   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-07 13:16:04.069   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:04.069  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 13:16:04.069  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.069  1014  1127 V NetworkStats: updateIfacesLocked()
09-07 13:16:04.069  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-07 13:16:04.069  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:04.069  6984  6984 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 13:16:04.069  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:04.069  6984  6984 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 13:16:04.069  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-07 13:16:04.069  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-07 13:16:04.079  1376  1376 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-07 13:16:04.079  1975  7001 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:04.079  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 13:16:04.079  1014  1127 V NetworkStats: performPollLocked() took 10ms
09-07 13:16:04.079  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.079   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:04.079   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 13:16:04.089  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:04.089  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:04.089  1174  1673 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 13:16:04.089  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:04.089  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:04.089  1014  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:16:04.089  4802  6843 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 13:16:04.089  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 13:16:04.089  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 13:16:04.089  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-07 13:16:04.089  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-07 13:16:04.089  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 13:16:04.089  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 13:16:04.099  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:04.089  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.089  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:04.089  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 13:16:04.099  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-07 13:16:04.099  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 13:16:04.099  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:04.099  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:04.099  1174  1174 D HotspotTile: onReceive : 0, 0
,09-07 13:16:04.109  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.109  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.109  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:04.109  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:04.109  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:04.109  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:04.109  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:04.109  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:04.109  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:04.109  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-07 13:16:04.109  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-07 13:16:04.109  1014  1122 V NetworkStats: updateIfacesLocked()
09-07 13:16:04.109  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.109  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:04.109  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:04.109  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:04.119  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.119  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 13:16:04.119  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.119  1014  1330 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 13:16:04.119  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.119  1014  1122 V NetworkStats: performPollLocked() took 5ms
09-07 13:16:04.119  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-07 13:16:04.119  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-07 13:16:04.119  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.119  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:04.119  1014  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:04.119  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-07 13:16:04.119  6984  6984 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
09-07 13:16:04.119  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:04.119  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.129  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 13:16:04.129  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 13:16:04.129  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:04.129  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:04.129  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:04.129  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 13:16:04.129  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.129  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.159  6984  6984 D BtSettings.ProfileConfig: Adding GattService
,09-07 13:16:04.159  6984  6984 D BtSettings.ProfileConfig: Adding HeadsetService
,09-07 13:16:04.159  6984  6984 D BtSettings.ProfileConfig: Adding A2dpService
09-07 13:16:04.169  1376  1376 I wpa_supplicant: Blacklist: Clear (all) 
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding HidService
,09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding HealthService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding PanService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding SapService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding SapClientService
09-07 13:16:04.169  6984  6984 D BtSettings.ProfileConfig: Adding HidDevService
09-07 13:16:04.169  6984  6984 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 13:16:04.169  1975  1975 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
09-07 13:16:04.169  1014  1429 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 13:16:04.169  1014  1429 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 13:16:04.169  1014  1429 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.169  1014  1429 D SettingsProvider: selectionArgs: false
09-07 13:16:04.169  1014  1429 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.169  1014  1429 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.169  1014  1429 D SettingsProvider: ret = -1
,09-07 13:16:04.169  1014  1095 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-07 13:16:04.169  1014  1095 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.169  1014  1095 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.169  1014  1095 D SettingsProvider: selectionArgs: false
09-07 13:16:04.169  1014  1095 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.169  1014  1095 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.169  1014  1095 D SettingsProvider: ret = -1
,09-07 13:16:04.169  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-07 13:16:04.169  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.169  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.169  1014  1479 D SettingsProvider: selectionArgs: false
09-07 13:16:04.169  1014  1479 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.169  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.169  1014  1479 D SettingsProvider: ret = -1
09-07 13:16:04.179  1014  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-07 13:16:04.179  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1480 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1480 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1480 D SettingsProvider: ret = -1
,09-07 13:16:04.179  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-07 13:16:04.179  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1026 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1026 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1026 D SettingsProvider: ret = -1
09-07 13:16:04.179  1014  1429 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-07 13:16:04.179  1014  1429 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1429 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1429 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1429 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1429 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1429 D SettingsProvider: ret = -1
09-07 13:16:04.179  1014  1095 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-07 13:16:04.179  1014  1095 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1095 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1095 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1095 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1095 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1095 D SettingsProvider: ret = -1
,09-07 13:16:04.179  1014  1027 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-07 13:16:04.179  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1027 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1027 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1027 D SettingsProvider: ret = -1
,09-07 13:16:04.179  1014  1436 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:04.179  1014  1436 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1436 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1436 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1436 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1436 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1436 D SettingsProvider: ret = -1
,09-07 13:16:04.179  1014  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:04.179  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1480 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1480 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1480 D SettingsProvider: ret = -1
,09-07 13:16:04.179  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-07 13:16:04.179  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1026 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1026 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1026 D SettingsProvider: ret = -1
09-07 13:16:04.179  1014  1438 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 13:16:04.179  1014  1438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:04.179  1014  1438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:04.179  1014  1438 D SettingsProvider: selectionArgs: false
09-07 13:16:04.179  1014  1438 D SettingsProvider: selectionArgs: 1002
09-07 13:16:04.179  1014  1438 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:04.179  1014  1438 D SettingsProvider: ret = -1
,09-07 13:16:04.209  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-07 13:16:04.209  1376  1376 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 13:16:04.209  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 13:16:04.209  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:04.209  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:04.209  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.219  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.219  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.219  1975  2167 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-07 13:16:04.219  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.219  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.229  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.229  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
09-07 13:16:04.229  1376  1376 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-07 13:16:04.229  1376  1376 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 13:16:04.229  1376  1376 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
09-07 13:16:04.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-07 13:16:04.229  1376  1376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 13:16:04.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.229  1376  1376 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 13:16:04.239  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 13:16:04.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 13:16:04.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:04.239  1014  1128 D Tethering: InitialState.processMessage what=4
09-07 13:16:04.239  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 13:16:04.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:04.239  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.249  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.249  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.249  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.249  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.249  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.249  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.249  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.259  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.259  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.259  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 13:16:04.259  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.259  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-07 13:16:04.259  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.259  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-07 13:16:04.259  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.269  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.269  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.269  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.269  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 13:16:04.269  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 13:16:04.289   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75917c8
09-07 13:16:04.289   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-07 13:16:04.289   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
09-07 13:16:04.289   270   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218898632)
,09-07 13:16:04.329   270   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
,09-07 13:16:04.329   270   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-07 13:16:04.329   270   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218898632) wakelock released: 1, error no: 0
09-07 13:16:04.329   270   325 I rmt_storage: 
,09-07 13:16:04.329   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75917c8
,09-07 13:16:04.369  1014  1479 I art     : Explicit concurrent mark sweep GC freed 44871(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.545ms total 155.917ms,
09-07 13:16:04.379  1014  1128 E Tethering: No numeric data
,09-07 13:16:04.379  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:16:04.379  1014  1128 D Tethering: clearTetheredNotification()
,09-07 13:16:04.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
09-07 13:16:04.379  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.379  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:04.379  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:04.379  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:04.379  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:04.379  1174  1174 D HotspotTile: updateTetherState():false, false
09-07 13:16:04.379  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:04.389  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.389  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.389  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:04.389  1014  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:04.389  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-07 13:16:04.389  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-07 13:16:04.389  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.389  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:04.389  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:04.389  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:04.389  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:04.389  1014  1026 I ActivityManager: Killing 6511:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
09-07 13:16:04.389  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:04.399  1975  7027 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-07 13:16:04.399  1014  1330 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-07 13:16:04.399  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-07 13:16:04.399  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.399  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:04.399  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.399  1014  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:04.399  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.399  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-07 13:16:04.399  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:04.409  7028  7028 E Zygote  : MountEmulatedStorage()
,09-07 13:16:04.409  7028  7028 I libpersona: KNOX_SDCARD checking this for 10102
09-07 13:16:04.409  7028  7028 E Zygote  : v2
09-07 13:16:04.409  7028  7028 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:04.419  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:04.419  1014  1330 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7028 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-07 13:16:04.419  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 13:16:04.419  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:04.419  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 13:16:04.419  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:04.419  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:04.419  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:04.429  1014  1436 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:04.439  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:04.439  1014  1436 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:04.439  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:04.439  1975  7027 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-07 13:16:04.439  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:04.439  7028  7028 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:04.459  7028  7028 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 13:16:04.499  1376  1376 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 13:16:04.589  1376  1376 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-07 13:16:04.589  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.589  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:04.589  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:04.599  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-07 13:16:04.599  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 13:16:04.609  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:04.609  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 13:16:04.609  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-07 13:16:04.609  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.609  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:04.609  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.609  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 13:16:04.609  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:04.609  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:04.609  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-07 13:16:04.609  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-07 13:16:04.609  1174  1174 D HotspotTile: onReceive : 1, 0
,09-07 13:16:04.619  1975  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:04.619  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:04.619  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:04.619  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:04.629  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:04.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:04.629  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-07 13:16:04.639  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:04.649  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 13:16:04.649  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:04.689  7028  7048 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-07 13:16:04.689  7028  7048 I Babel_SMS: MmsConfig.loadMmsSettings
09-07 13:16:04.689  7028  7048 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-07 13:16:04.689  7028  7048 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 13:16:04.719  7028  7048 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 13:16:04.719  7028  7048 I Babel_SMS: MmsConfig.loadFromResources
,09-07 13:16:04.729  7028  7048 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 13:16:04.729  7028  7048 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-07 13:16:04.749  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-07 13:16:04.749  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-07 13:16:04.749  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:04.749  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:04.749  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 13:16:04.769  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:04.769  7028  7028 I Babel_Crash: startup - clean
,09-07 13:16:04.799  1014  1436 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:04.809  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:04.809  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:04.809  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:04.809  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:04.809  1624  1624 I Hs20UtilService: Starting #8
,09-07 13:16:04.809  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:04.809  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:04.819  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:04.819  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:04.819  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:04.819  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:04.819  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:04.819  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:04.819  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:16:04.819  7028  7028 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 13:16:04.829  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 13:16:04.829  7028  7028 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 13:16:04.829  7028  7028 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-07 13:16:04.829  7028  7028 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-07 13:16:04.829  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:04.829  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:04.829  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:04.839  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:04.839  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:04.839  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:04.839  1014  1436 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-07 13:16:04.839  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:04.839  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.839  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.839  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:04.839  7028  7028 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-07 13:16:04.849  7051  7051 E Zygote  : MountEmulatedStorage()
09-07 13:16:04.849  7051  7051 E Zygote  : v2
09-07 13:16:04.849  7051  7051 I libpersona: KNOX_SDCARD checking this for 10064
09-07 13:16:04.849  7051  7051 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:04.849  7051  7051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:04.849  7028  7028 W AudioCapabilities: Unsupported mime audio/x-ima
,09-07 13:16:04.849  1014  1436 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7051 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:16:04.859  7028  7028 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 13:16:04.859  7051  7051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:04.859  7051  7051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:04.859  7028  7028 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 13:16:04.889  7051  7051 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:04.889  7051  7051 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:04.889  7028  7028 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 13:16:04.889  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 13:16:04.899  7028  7028 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-07 13:16:04.899  7028  7028 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 13:16:04.899  7051  7051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 13:16:04.899  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 13:16:04.909  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-07 13:16:04.909  7028  7028 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-07 13:16:04.909  7028  7028 W VideoCapabilities: Unsupported mime video/mp43
,09-07 13:16:04.909  7028  7028 W VideoCapabilities: Unsupported mime video/sorenson
,09-07 13:16:04.919  7028  7028 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-07 13:16:04.919  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:04.929  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 13:16:04.929  7028  7028 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 13:16:04.959  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:16:04.959  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:16:04.959  7051  7051 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 13:16:04.959  1014  1429 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-07 13:16:04.959  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:16:04.959  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.959  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.959  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:04.959  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:04.969  7028  7028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 13:16:04.979  7028  7028 I vclib   : onServiceConnected
,09-07 13:16:04.979  1014  1429 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7066 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:16:04.979  1014  1429 I ActivityManager: Killing 6561:com.samsung.android.sm/1000 (adj 15): empty #21
,09-07 13:16:04.989  7066  7066 E Zygote  : MountEmulatedStorage()
09-07 13:16:04.989  7066  7066 I libpersona: KNOX_SDCARD checking this for 10065
09-07 13:16:04.989  7066  7066 E Zygote  : v2
09-07 13:16:04.989  7066  7066 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:04.989  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:04.989  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:04.989  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:04.999  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.009  7066  7066 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.029  7066  7066 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:05.029  1014  1496 I ActivityManager: Killing 6541:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-07 13:16:05.039  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:05.039  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:05.039  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.039  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.039  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:05.049  1624  1624 I Hs20UtilService: Starting #9
,09-07 13:16:05.049  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 13:16:05.049  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 13:16:05.049  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:05.049  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:05.049  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:05.049  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:05.049  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:05.049  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:05.059  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:05.059  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:05.059  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.059  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.059  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:05.059  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 13:16:05.059  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:05.059  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 13:16:05.059  1624  1624 I Hs20UtilService: Starting #10
09-07 13:16:05.069  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:05.069  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:05.069  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.069  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.069  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.099  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.099  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.099  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.109  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.109  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.109  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.109  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.119  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.119  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.119  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.119  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.119  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.129  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.129  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.129  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.129  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.129  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.139  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.139  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.139  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.139  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.139  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:05.139  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 13:16:05.149  1014  1330 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:05.149  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:05.149  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.149  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:05.149  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:05.149  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 13:16:05.149  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:05.149  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:05.149  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:05.149  1624  1624 I Hs20UtilService: Starting #11
09-07 13:16:05.149  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:05.159  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 13:16:05.159  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.159  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.159  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.159  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.169  7082  7082 E Zygote  : MountEmulatedStorage(),
09-07 13:16:05.169  1014  1479 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 13:16:05.169  7082  7082 E Zygote  : v2
09-07 13:16:05.169  7082  7082 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:05.169  7082  7082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:05.169  7082  7082 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.179  7082  7082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:05.179  7082  7082 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 13:16:05.189  1014  1042 D Tethering: interfaceRemoved wlan0
09-07 13:16:05.189  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 13:16:05.199  7082  7082 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.199  7082  7082 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.219  7082  7082 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-07 13:16:05.219  7082  7082 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-07 13:16:05.219  7082  7082 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 13:16:05.229  7082  7082 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-07 13:16:05.229  7082  7082 I PCWCLIENTTRACE_PushUtil: sales region : global
09-07 13:16:05.229  7082  7082 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-07 13:16:05.229  7082  7082 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:05.239  1014  1330 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-07 13:16:05.239  7082  7097 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-07 13:16:05.239  1014  1330 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-07 13:16:05.239  1014  1330 I ActivityManager: Killing 6612:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-07 13:16:05.249  1014  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-07 13:16:05.249  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.249  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.249  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.249  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.269  7099  7099 E Zygote  : MountEmulatedStorage()
,09-07 13:16:05.269  7099  7099 E Zygote  : v2
09-07 13:16:05.269  7099  7099 I libpersona: KNOX_SDCARD checking this for 10031
09-07 13:16:05.269  7099  7099 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.269  7099  7099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.269  1014  1496 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7099 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-07 13:16:05.269  7099  7099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:05.269  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-07 13:16:05.279  7099  7099 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 13:16:05.279  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.279  1801  1801 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-07 13:16:05.279  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.279  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.279  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.289  7099  7099 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.289  7099  7099 D ActivityThread: Added TimaKeyStore provider,
,09-07 13:16:05.299   307   307 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 31.066ms
,09-07 13:16:05.319   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 19.564ms
,09-07 13:16:05.339   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 17.641ms
,09-07 13:16:05.349  1014  1042 D Tethering: interfaceRemoved p2p0
,09-07 13:16:05.349  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 13:16:05.349  7114  7114 E Zygote  : MountEmulatedStorage()
,09-07 13:16:05.349  7114  7114 E Zygote  : v2
09-07 13:16:05.349  7114  7114 I libpersona: KNOX_SDCARD checking this for 10121
09-07 13:16:05.349  7114  7114 I libpersona: KNOX_SDCARD not a persona,
09-07 13:16:05.349  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.359  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:05.359  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 13:16:05.359  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7114 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 13:16:05.379  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
09-07 13:16:05.379   290   290 E SMD     : DCD OFF
,09-07 13:16:05.379  2604  6662 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-07 13:16:05.379  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.379  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.379  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.379  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.379   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:16:05.389  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.389  7114  7114 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.399  7129  7129 E Zygote  : MountEmulatedStorage(),
09-07 13:16:05.399  7129  7129 I libpersona: KNOX_SDCARD checking this for 10001
09-07 13:16:05.399  7129  7129 E Zygote  : v2
09-07 13:16:05.399  7129  7129 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:05.399  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.399  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7129 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:16:05.399  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:05.399  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 13:16:05.409  1801  1801 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-07 13:16:05.409  1801  1801 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-07 13:16:05.409  1801  1801 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-07 13:16:05.409  1801  1801 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-07 13:16:05.419  1801  1801 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 13:16:05.429  1801  1801 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-07 13:16:05.429  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-07 13:16:05.429  7114  7114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:16:05.429  7114  7114 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 13:16:05.429  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.429  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.429  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.429  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.439  7114  7114 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:16:05.439  7099  7099 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-07 13:16:05.439  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.439  7129  7129 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.449  7144  7144 E Zygote  : MountEmulatedStorage(),
09-07 13:16:05.449  7144  7144 E Zygote  : v2
09-07 13:16:05.449  7144  7144 I libpersona: KNOX_SDCARD checking this for 10077,
,09-07 13:16:05.449  7144  7144 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:05.449  1014  1026 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7144 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:16:05.449  7144  7144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.459  7114  7114 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
09-07 13:16:05.459  1014  1026 I ActivityManager: Killing 6627:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-07 13:16:05.459  7144  7144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:05.459  7144  7144 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
09-07 13:16:05.459  7114  7114 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-07 13:16:05.469  7114  7114 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-07 13:16:05.469  1014  1438 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-07 13:16:05.469  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.469  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.469  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.469  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.479  7155  7155 E Zygote  : MountEmulatedStorage()
09-07 13:16:05.479  7155  7155 E Zygote  : v2
09-07 13:16:05.479  7155  7155 I libpersona: KNOX_SDCARD checking this for 10141
09-07 13:16:05.479  7155  7155 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.479  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.489  1014  1438 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7155 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-07 13:16:05.489  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:05.489  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:05.489  1014  1438 I ActivityManager: Killing 6644:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-07 13:16:05.499  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 13:16:05.499  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.499  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.499  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.499  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.499  7144  7144 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.499  2755  7168 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-07 13:16:05.499  7144  7144 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.499  2755  7168 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-07 13:16:05.509  2755  7168 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-07 13:16:05.509  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.509  2755  7168 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-07 13:16:05.509  2755  7168 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-07 13:16:05.509  7155  7155 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.519  7175  7175 E Zygote  : MountEmulatedStorage(),
09-07 13:16:05.519  7175  7175 I libpersona: KNOX_SDCARD checking this for 10032
09-07 13:16:05.519  7175  7175 E Zygote  : v2
09-07 13:16:05.519  7175  7175 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:05.519  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.519  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 13:16:05.519  1014  1027 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7175 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-07 13:16:05.519  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,09-07 13:16:05.539  7155  7155 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-07 13:16:05.539  7155  7155 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:05.539  7155  7155 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 13:16:05.539  7155  7155 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 13:16:05.559  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.559  7175  7175 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.579  1014  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-07 13:16:05.589  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.589  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.589  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.589  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.599  7192  7192 E Zygote  : MountEmulatedStorage()
09-07 13:16:05.599  7192  7192 E Zygote  : v2
09-07 13:16:05.599  7192  7192 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:05.599  7192  7192 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.599  1014  1496 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 13:16:05.599  1014  1496 I ActivityManager: Killing 6587:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-07 13:16:05.609  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.609  1014  1476 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.609  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:05.609  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:05.629  7175  7202 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-07 13:16:05.629  7175  7202 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-07 13:16:05.639  7175  7175 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-07 13:16:05.639  1014  1095 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.639  7175  7202 D SPPClientService: PushLog.txt file is not deleted.
09-07 13:16:05.639  1014  1436 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
09-07 13:16:05.639  7175  7202 D SPPClientService: PushLog.txt file is not deleted.
09-07 13:16:05.639  7175  7202 D SPPClientService: ============PushLog. stop!
,09-07 13:16:05.639  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 13:16:05.639  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.639  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.639  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 13:16:05.649  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.649  7192  7192 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.669  7211  7211 E Zygote  : MountEmulatedStorage()
09-07 13:16:05.669  1014  1436 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7211 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:16:05.669  7211  7211 E Zygote  : v2
09-07 13:16:05.669  1014  1436 I ActivityManager: Killing 6667:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-07 13:16:05.669  7211  7211 I libpersona: KNOX_SDCARD checking this for 10036
09-07 13:16:05.669  7211  7211 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.669  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.679  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:05.679  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-07 13:16:05.679  1014  1026 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-07 13:16:05.679  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-07 13:16:05.679  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.679  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-07 13:16:05.679  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-07 13:16:05.689  1014  1330 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.699  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:05.699  7211  7211 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.719  1014  1479 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.739  7175  7225 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-07 13:16:05.759  7192  7192 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 13:16:05.779  7211  7211 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@4e0d63
,09-07 13:16:05.799  7211  7211 I SA      : [SSP] onCreated
,09-07 13:16:05.799  1014  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-07 13:16:05.799  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.799  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.799  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.799  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.819  7235  7235 E Zygote  : MountEmulatedStorage()
09-07 13:16:05.819  7235  7235 I libpersona: KNOX_SDCARD checking this for 10068
09-07 13:16:05.819  7235  7235 E Zygote  : v2
09-07 13:16:05.819  7235  7235 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.829  1014  1095 D RCPManagerService: exchangeData() failure , invalid userId
09-07 13:16:05.829  1014  1480 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7235 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-07 13:16:05.829  7235  7235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.839  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
09-07 13:16:05.839  7235  7235 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:05.839  7235  7235 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 13:16:05.859  7235  7235 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.859  7211  7211 I SA      : [TPM] There is no property file
09-07 13:16:05.859  7235  7235 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.869  7211  7211 I SA      : [SCU] isHaveSA() - false
,09-07 13:16:05.879  7211  7211 I SA      : [TPM] getModelProperty : null
09-07 13:16:05.879  7211  7211 I SA      : [TPM] getCSCProperty : null
,09-07 13:16:05.879  1014  1095 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.879  7211  7211 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-07 13:16:05.879  7211  7211 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-07 13:16:05.879  7211  7211 I SA      : [DM] TFT FEATURE: false
,09-07 13:16:05.889  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-07 13:16:05.889  7235  7235 D BadgeProvider: onCreate
09-07 13:16:05.889  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-07 13:16:05.889  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.889  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:05.889  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-07 13:16:05.889  7235  7235 D BadgeProvider: DatabaseHelper
,09-07 13:16:05.899  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-07 13:16:05.899  7211  7211 I SA      : [DM] init START
09-07 13:16:05.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.899  7211  7211 I SA      : [DM] This device is not a Vodafone
09-07 13:16:05.899  1014  1438 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 13:16:05.909  7255  7255 E Zygote  : MountEmulatedStorage(),
09-07 13:16:05.919  7235  7247 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-07 13:16:05.919  7255  7255 E Zygote  : v2
09-07 13:16:05.919  7255  7255 I libpersona: KNOX_SDCARD checking this for 10110,
09-07 13:16:05.919  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:05.919  7255  7255 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:05.919  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:05.919  1014  1026 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7255 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 13:16:05.919  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-07 13:16:05.919  1014  1095 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-07 13:16:05.919  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:05.919  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-07 13:16:05.919  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:05.919  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 13:16:05.919  7028  7254 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-07 13:16:05.919  1014  1438 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-07 13:16:05.929  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.929  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.929  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.929  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:05.939  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.939  7255  7255 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.949  7270  7270 E Zygote  : MountEmulatedStorage()
,09-07 13:16:05.949  7270  7270 E Zygote  : v2
,09-07 13:16:05.949  7192  7192 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
09-07 13:16:05.949  7270  7270 I libpersona: KNOX_SDCARD checking this for 10009
09-07 13:16:05.949  7270  7270 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:05.949  7270  7270 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:05.949  7270  7270 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 13:16:05.959  7270  7270 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-07 13:16:05.959  1014  1438 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7270 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-07 13:16:05.959  1014  1438 I ActivityManager: Killing 6687:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-07 13:16:05.959  1014  1438 I ActivityManager: Killing 6087:com.android.mms/u0a41 (adj 15): empty #22
,09-07 13:16:05.959  7192  7192 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
09-07 13:16:05.959  7192  7192 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-07 13:16:05.979  1014  1480 I ActivityManager: Killing 6706:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-07 13:16:05.979  7211  7211 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-07 13:16:05.979  7211  7211 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-07 13:16:05.989  7235  7245 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-07 13:16:05.989  7235  7245 D BadgeProvider: sendNotify, [notify] : null
09-07 13:16:05.989  7235  7245 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-07 13:16:05.989  7235  7245 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-07 13:16:05.989  7270  7270 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:05.989  7235  7245 D BadgeProvider: update, [UpdateCount] : 1
09-07 13:16:05.989  1481  1481 D Launcher.Model: reloadBadges entered.
09-07 13:16:05.989  7270  7270 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-07 13:16:05.989  7192  7192 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 13:16:05.989  7192  7192 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-07 13:16:05.989  7211  7211 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-07 13:16:05.999  7192  7192 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 13:16:05.999  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-07 13:16:05.999  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.999  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.999  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:05.999  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:06.019  7286  7286 E Zygote  : MountEmulatedStorage()
,09-07 13:16:06.019  7286  7286 E Zygote  : v2
09-07 13:16:06.019  7286  7286 I libpersona: KNOX_SDCARD checking this for 10008
09-07 13:16:06.019  7286  7286 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:06.019  7286  7286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:06.019  7211  7211 I SA      : [SCU] isHaveSA() - false
09-07 13:16:06.019  7211  7211 I SA      : support phone number id : false
09-07 13:16:06.019  7211  7211 I SA      : [DM] Supports Ref Jpn : true
09-07 13:16:06.019  7211  7211 I SA      : [DM] init END
09-07 13:16:06.019  7211  7211 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
09-07 13:16:06.019  7286  7286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:06.019  7286  7286 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-07 13:16:06.019  7211  7211 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-07 13:16:06.019  7211  7211 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 13:16:06.019  1014  1476 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7286 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:16:06.029  1014  1480 I ActivityManager: Killing 6526:com.android.calendar/u0a131 (adj 15): empty #21
,09-07 13:16:06.039  7211  7211 I SA      : [SLFUCHKMGR] constructor called
09-07 13:16:06.039  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 13:16:06.049   307   307 I art     : Explicit concurrent mark sweep GC freed 8671(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 636us total 25.202ms
,09-07 13:16:06.049  1014  1476 D CountryDetector: No listener is left
,09-07 13:16:06.049  7286  7286 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:06.059  7286  7286 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:06.069  7211  7211 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-07 13:16:06.069  7211  7211 I SA      : [OR] == isSIMCardReady false ==
,09-07 13:16:06.079   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 24.773ms
,09-07 13:16:06.079  7211  7211 I SA      : [SCU] == networkStateCheck == false
09-07 13:16:06.079  7211  7211 I SA      : [OR] onReceive END
,09-07 13:16:06.079  1014  1027 I ActivityManager: Killing 6722:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-07 13:16:06.089  1219  1219 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:06.089   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 17.060ms
,09-07 13:16:06.159  1014  1480 I ActivityManager: Killing 6050:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-07 13:16:06.159  2855  2855 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 13:16:06 GMT+02:00 2016
,09-07 13:16:06.159  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-07 13:16:06.159  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-07 13:16:06.159  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:06.159  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:06.159  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 13:16:06.169  2855  2855 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 13:16:06.169  2855  2855 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-07 13:16:06.169  2855  2855 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 13:16:06.179  2855  2855 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 13:16:06.179  2855  7304 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 13:16:06.179  1014  1027 I ActivityManager: Killing 5869:com.android.vending/u0a26 (adj 15): empty #21
,09-07 13:16:06.179  2855  7304 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-07 13:16:06.189  2855  7304 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-07 13:16:06.189  1014  1095 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:06.189  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-07 13:16:06.189  2855  7304 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-07 13:16:06.189  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:06.189  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:06.189  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:06.199  2855  2855 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 13:16:06.199  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-07 13:16:06.199  1014  1026 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-07 13:16:06.209  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-07 13:16:06.209  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-07 13:16:06.209  4802  7305 I iu.SyncManager: SYNC; picasa accounts
,09-07 13:16:06.229  1014  1476 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 13:16:06.229  1014  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
09-07 13:16:06.229  1014  1476 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 13:16:06.229  1014  1476 D SecContentProvider2: mCursor = null
,09-07 13:16:06.229  1014  1476 D WifiService: setWifiEnabled: true pid=6777, uid=10171
,09-07 13:16:06.229  1014  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-07 13:16:06.229  1014  1476 W WifiService: Failed getting userId using ActivityManagerNative
09-07 13:16:06.229  1014  1476 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 13:16:06.229  1014  1476 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 13:16:06.229  1014  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 13:16:06.229  1014  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 13:16:06.229  1014  1476 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 13:16:06.229  1014  1476 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 13:16:06.229  1014  1476 D SettingsProvider: name = wifi_on
,09-07 13:16:06.279  4802  4802 D NetworkLogImpl: Loaded NetworkSpeedPredictor,
09-07 13:16:06.279  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 13:16:06.379   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 13:16:06.379   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:06.379  7255  7311 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
09-07 13:16:06.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:16:06.389   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 13:16:06.389   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:06.389  7255  7311 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 13:16:06.409  7255  7255 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 13:16:06.409  7255  7255 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 13:16:06.409  7255  7255 I GAv4    :   adb logcat -s GAv4
,09-07 13:16:06.409   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 13:16:06.409   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:06.409  7255  7312 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 13:16:06.409   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 13:16:06.409   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:06.409  7255  7312 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 13:16:06.419  1975  2167 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-07 13:16:06.419  1975  2167 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-07 13:16:06.439  7255  7255 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:06.439  1014  1095 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 13:16:06.449  7255  7255 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:06.459  7255  7314 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:06.549  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 13:16:06.549  1014  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 13:16:06.549  1014  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 13:16:06.549  1014  1476 D BatteryService: stay LED for fully charged
,09-07 13:16:06.549  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 13:16:06.549  1014  1014 I MotionRecognitionService: Plugged,
09-07 13:16:06.549  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 13:16:06.559  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-07 13:16:06.559  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-07 13:16:06.559  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-07 13:16:06.559  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 13:16:06.579  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-07 13:16:06.579  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-07 13:16:06.589  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:06.589  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:16:06.589  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:06.669  1014  1042 D Tethering: interfaceAdded wlan0
,09-07 13:16:06.679  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:06.679  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:06.679  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:06.679  1014  1429 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:06.679  1014  1128 E Tethering: No numeric data
,09-07 13:16:06.679  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:06.689  1014  1429 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:06.689  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-07 13:16:06.689   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 13:16:06.689  1014  1042 D Tethering: interfaceAdded p2p0
,09-07 13:16:06.689   277   996 D SoftapController: Softap fwReload - Ok
,09-07 13:16:06.689  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
09-07 13:16:06.689  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 13:16:06.689  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 13:16:06.689  1014  1128 D Tethering: clearTetheredNotification()
09-07 13:16:06.689  1014  1128 D Tethering: InitialState.processMessage what=4
09-07 13:16:06.689  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 13:16:06.689  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
09-07 13:16:06.689   277   996 D CommandListener: Setting iface cfg
09-07 13:16:06.689   277   996 D CommandListener: Trying to bring down wlan0
,09-07 13:16:06.689  1014  1128 E Tethering: No numeric data
09-07 13:16:06.699   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:06.699  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:06.699  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-07 13:16:06.699  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-07 13:16:06.699  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:06.699  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:16:06.699  1174  1174 D HotspotTile: updateTetherState():false, false
09-07 13:16:06.699  1014  1128 D Tethering: clearTetheredNotification()
09-07 13:16:06.699  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:06.699  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:06.699  1174  1174 D HotspotTile: updateTetherState():false, false
,09-07 13:16:06.699  1014  1122 V NetworkStats: performPollLocked() took 7ms
,09-07 13:16:06.699  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
09-07 13:16:06.699  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:06.709  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:06.709  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:06.709  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:06.709  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:06.709  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 13:16:06.709  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:06.709  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:06.709  1014  1122 V NetworkStats: performPollLocked() took 8ms
,09-07 13:16:06.709  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:06.709  7255  7255 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-07 13:16:06.709  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:06.739  7255  7255 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 6473-6487)
09-07 13:16:06.739  7255  7255 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 13:16:06.749  7255  7255 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {398d65aa}
,09-07 13:16:06.749  7255  7255 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 13:16:06.749  7255  7255 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 13:16:06.769  7255  7255 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-07 13:16:06.769  7255  7255 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-07 13:16:06.769  7255  7255 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 13:16:06.779  7336  7336 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-07 13:16:06.779  7336  7336 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 13:16:06.779  7336  7336 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-07 13:16:06.789  7255  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 13:16:06.789  7255  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 13:16:06.789  7255  7255 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 13:16:06.789  7255  7255 I Adreno-EGL: Local Branch: 
09-07 13:16:06.789  7255  7255 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 13:16:06.789  7255  7255 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 13:16:06.789  7255  7255 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 13:16:06.799  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 13:16:06.809  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:06.809  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 13:16:06.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:06.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:06.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:06.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:06.809  7336  7336 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-07 13:16:06.809   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7336
09-07 13:16:06.809   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-07 13:16:06.809  7336  7336 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 13:16:06.809  7336  7336 I wpa_supplicant: ssSupport state is = 1
09-07 13:16:06.809  7336  7336 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 13:16:06.809  7336  7336 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 13:16:06.809   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7336
09-07 13:16:06.809   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
09-07 13:16:06.819  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:06.819  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 13:16:06.819  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 13:16:06.819  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:06.819  1174  1174 D HotspotTile: onReceive : 2, 0
,09-07 13:16:06.819  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:06.819  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:06.829  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 13:16:06.859  7255  7255 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 13:16:06.879  7255  7351 W cr.media: Requires BLUETOOTH permission
,09-07 13:16:06.879  7255  7255 I NSApplication: Starting up...
,09-07 13:16:06.879  1014  1476 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 13:16:06.889  1014  1479 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 13:16:06.899  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-07 13:16:06.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:06.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:06.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:06.899  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:06.919  7356  7356 E Zygote  : MountEmulatedStorage()
,09-07 13:16:06.919  7356  7356 E Zygote  : v2
09-07 13:16:06.919  7356  7356 I libpersona: KNOX_SDCARD checking this for 10117
09-07 13:16:06.919  7356  7356 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:06.919  7356  7356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:06.919  1014  1026 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7356 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
09-07 13:16:06.919  7356  7356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:06.919  7356  7356 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-07 13:16:06.929  1014  1026 I ActivityManager: Killing 6924:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-07 13:16:06.949  7356  7356 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:06.949  7356  7356 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:06.969  7356  7356 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 13:16:06.999   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-07 13:16:07.009  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-07 13:16:07.059  7336  7336 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 13:16:07.059  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 13:16:07.069  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-07 13:16:07.069   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7336
09-07 13:16:07.069   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 13:16:07.069  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 13:16:07.069  7336  7336 I wpa_supplicant: ssSupport state is = 1
,09-07 13:16:07.069  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 13:16:07.069  7336  7336 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:07.069  7336  7336 E wpa_supplicant: SIM READ ERROR
09-07 13:16:07.069  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:07.069  7336  7336 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:07.069  7336  7336 E wpa_supplicant: SIM READ ERROR
09-07 13:16:07.069  7336  7336 I wpa_supplicant: Blacklist: Clear (all) 
09-07 13:16:07.069  7336  7336 I wpa_supplicant: wpa_default_ap_write_once
09-07 13:16:07.069  7336  7336 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 13:16:07.069  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:07.069  7336  7336 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 13:16:07.069  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:07.069  7336  7336 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 13:16:07.079  7336  7336 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 13:16:07.079  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:07.079  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:07.079  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:07.139  7336  7336 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-07 13:16:07.299  7336  7336 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-07 13:16:07.299  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 13:16:07.319  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 13:16:07.319   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7336
09-07 13:16:07.319   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 13:16:07.319  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 13:16:07.319  7336  7336 I wpa_supplicant: ssSupport state is = 1
,09-07 13:16:07.319  1014  1026 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-07 13:16:07.319  1014  1026 I ActivityManager: Killing 6984:com.android.bluetooth/1002 (adj 15): empty #21
,09-07 13:16:07.329  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:07.329  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:07.329  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:07.329  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:07.329  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:07.329  1624  1624 I Hs20UtilService: Starting #12
,09-07 13:16:07.329  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:07.339  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 13:16:07.339  7336  7336 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 13:16:07.339  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 13:16:07.339  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:07.339  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:07.339  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:07.349  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 13:16:07.349   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7336
09-07 13:16:07.349   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-07 13:16:07.349  7336  7336 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 13:16:07.349  7336  7336 I wpa_supplicant: ssSupport state is = 1
09-07 13:16:07.349  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:07.349  7336  7336 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:07.349  7336  7336 E wpa_supplicant: SIM READ ERROR
09-07 13:16:07.349  7336  7336 I wpa_supplicant: wpa_default_ap_write_once
09-07 13:16:07.349  7336  7336 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 13:16:07.349  7336  7336 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 13:16:07.349  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:07.349  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 13:16:07.349  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:07.359  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 13:16:07.359  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:07.359  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:07.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:16:07.439  7336  7336 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-07 13:16:07.439  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 13:16:07.559  7336  7336 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-07 13:16:07.559  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 13:16:07.559  7336  7336 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 13:16:07.569  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-07 13:16:07.569  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 13:16:07.569  7336  7336 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-07 13:16:07.569  7336  7336 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 13:16:07.569  7336  7336 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:07.569  7336  7336 E wpa_supplicant: SIM READ ERROR,
09-07 13:16:07.579  7336  7336 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 13:16:07.599  7336  7336 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-07 13:16:07.609  7336  7336 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 13:16:07.609  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-07 13:16:07.609  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:07.609  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-07 13:16:07.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:07.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:07.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 13:16:07.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:07.619  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:07.619  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 13:16:07.619  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:07.619  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 13:16:07.619  1174  1174 D HotspotTile: onReceive : 3, 0
,09-07 13:16:07.629  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:07.629  1014  1125 E WifiConfigStore: Not a HS20
09-07 13:16:07.629  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:07.629  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:07.629  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:07.629  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:07.629  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 13:16:07.629  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:07.629  1014  1436 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:07.629  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 13:16:07.629  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:07.629  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:07.629  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:07.639  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:07.639  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:07.639  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:07.639  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
09-07 13:16:07.639  1624  1624 I Hs20UtilService: Starting #13,
,09-07 13:16:07.639  1624  1651 I Hs20UtilService: Message received 5011
09-07 13:16:07.639  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 13:16:07.639  7336  7336 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 13:16:07.639  7336  7336 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 13:16:07.639  7336  7336 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 13:16:07.639  7336  7336 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-07 13:16:07.639  7336  7336 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 13:16:07.639  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 13:16:07.639  7336  7336 I wpa_supplicant: First Scan Start
09-07 13:16:07.639  7336  7336 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 13:16:07.639  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 13:16:07.639  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:07.639  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:07.639  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-07 13:16:07.639  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
09-07 13:16:07.639  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 13:16:07.639  1014  1125 I WifiNative-HAL: startHal
09-07 13:16:07.639  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d5bf88c
09-07 13:16:07.639  1014  1125 I WifiNative-HAL: Could not start hal
09-07 13:16:07.649  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:07.649  1014  1125 E WifiNative-wlan0: do suspend true
,09-07 13:16:07.649  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-07 13:16:07.649  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-07 13:16:07.649  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 13:16:07.649  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler },
09-07 13:16:07.649  1014  1147 I WifiNative-HAL: startHal
09-07 13:16:07.649  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e6679bc
09-07 13:16:07.649  1014  1147 I WifiNative-HAL: Could not start hal
09-07 13:16:07.649  1014  1147 E WifiScanningService: could not start HAL
,09-07 13:16:07.649  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 13:16:07.649  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 13:16:07.649  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-07 13:16:07.649   277   996 D CommandListener: Setting iface cfg
09-07 13:16:07.649   277   996 D CommandListener: Trying to bring up p2p0
09-07 13:16:07.649  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-07 13:16:07.649  1014  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:07.649  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 13:16:07.649  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 13:16:07.649  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-07 13:16:07.649  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 13:16:07.659  1014  1124 D WifiP2pService: P2pEnablingState
09-07 13:16:07.659  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 13:16:07.659  7336  7336 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 13:16:07.659  1014  1124 D WifiP2pService: P2p socket connection successful
09-07 13:16:07.659  1014  1124 D WifiP2pService: P2pEnabledState
,09-07 13:16:07.659  7336  7336 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-07 13:16:07.659  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 13:16:07.659  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:07.659  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 13:16:07.659  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 13:16:07.659  7336  7336 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 13:16:07.659  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:07.659  1014  1045 D WifiDisplayController: disconnect
09-07 13:16:07.659  1014  1045 D WifiDisplayController: updateConnection
09-07 13:16:07.659  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:07.659  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 13:16:07.659  1014  1125 E WifiStateMachine: Failed to set frequency band 0
09-07 13:16:07.659  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:07.659  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:07.659  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:16:07.669  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 13:16:07.669  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 13:16:07.669  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 13:16:07.669  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 13:16:07.669  1014  1429 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 13:16:07.669  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 13:16:07.669  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 13:16:07.669  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28,
09-07 13:16:07.669  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 13:16:07.669  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
09-07 13:16:07.669  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,09-07 13:16:07.669  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:07.669  1014  1125 D SecContentProvider2: mCursor = null
09-07 13:16:07.669  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  secondary type: null
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  wps: 0
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  grpcapab: 0
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  devcapab: 0
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  status: 3
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  wfdInfo: null
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  groupownerAddress: null
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  GOdeviceName: null
09-07 13:16:07.669  1014  1045 D WifiDisplayController:  interfaceAddress: 
,09-07 13:16:07.669  1014  1045 D WifiDisplayController:  SConnectInfo : null
,09-07 13:16:07.679  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 13:16:07.679  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:07.679  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:07.679  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:07.679  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 13:16:07.679  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:07.679  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:07.679  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:07.679  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:07.679  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 13:16:07.679  7051  7051 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 13:16:07.689  7066  7066 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:07.699  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 13:16:07.699  1014  1124 D WifiP2pService: InactiveState
,09-07 13:16:07.699  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-07 13:16:07.699  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 13:16:07.699  7336  7336 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 13:16:07.699  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-07 13:16:07.699  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 13:16:08.189  1014  1026 I ActivityManager: Killing 6943:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-07 13:16:08.379   290   290 E SMD     : DCD OFF,
,09-07 13:16:08.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 13:16:08.809  7336  7336 I wpa_supplicant: nl80211: Received scan results (33 BSSes)
09-07 13:16:08.809  7336  7336 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 13:16:08.809  7336  7336 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 13:16:08.809  7336  7336 I wpa_supplicant: Trying to associate with  'G700'
09-07 13:16:08.809  7336  7336 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 13:16:08.809  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 13:16:08.809  1014  7382 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 13:16:08.829  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:08.829  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:08.939  7336  7336 E wpa_supplicant: Cmd 35605 not handled
,09-07 13:16:08.939  7336  7336 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:08.939  7336  7336 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-07 13:16:08.939  7336  7336 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 13:16:08.939  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:08.939  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:08.939  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 13:16:08.939  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:08.939  7336  7336 I wpa_supplicant: Associated with F4.99.3E
09-07 13:16:08.939  7336  7336 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:08.939  7336  7336 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 13:16:08.939  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-07 13:16:08.939  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-07 13:16:08.939  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:08.939  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:08.949  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 13:16:08.949  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
,09-07 13:16:08.949  1014  1042 D Tethering: interfaceStatusChanged wlan0, true,
09-07 13:16:08.949  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-07 13:16:08.949  1014  1128 E Tethering: No numeric data
09-07 13:16:08.949  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-07 13:16:08.949  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 13:16:08.949  1174  1174 D HotspotTile: updateTetherState():false, false
09-07 13:16:08.949  1014  1128 D Tethering: clearTetheredNotification()
09-07 13:16:08.959  1014  1122 V NetworkStats: performPollLocked() took 5ms
,09-07 13:16:08.949  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:08.949  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:08.949  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:08.959  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:08.959  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:08.959  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:08.959  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:08.959  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:08.959  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:08.959  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:08.989  7336  7336 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:08.989  7336  7336 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-07 13:16:08.989  7336  7336 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 13:16:08.989  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-07 13:16:08.989  7336  7336 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 13:16:08.989  7336  7336 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 13:16:08.989  7336  7336 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 13:16:08.989  7336  7336 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 13:16:08.989  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-07 13:16:08.999  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 13:16:08.999  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 13:16:08.999  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-07 13:16:08.999  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 13:16:08.999  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-07 13:16:09.009  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:09.009  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-07 13:16:09.009  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.009  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.009  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 13:16:09.009  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.009  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-07 13:16:09.009  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-07 13:16:09.009  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:09.009  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:09.019  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:09.019  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:09.019  1014  1095 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:09.019  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-07 13:16:09.019  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 13:16:09.019  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 13:16:09.019  1624  1624 I Hs20UtilService: Starting #14
,09-07 13:16:09.029  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:09.029  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:09.029  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:09.029  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:09.029  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:09.029  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-07 13:16:09.029  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:09.029  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:09.039  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:09.049   277   996 D CommandListener: Setting iface cfg,
,09-07 13:16:09.049  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-07 13:16:09.059  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:09.059  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:09.069  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 13:16:09.069  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:09.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.069  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.069  1014  1125 E WifiNative-wlan0: do suspend false
,09-07 13:16:09.079  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-07 13:16:09.079  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 13:16:09.079  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:09.079  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:09.289  1014  1436 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 13:16:09.289  1014  1436 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 13:16:09.289  1014  1436 D SecContentProvider2: mCursor = null
,09-07 13:16:09.289  1014  1436 D WifiService: setWifiEnabled: false pid=6777, uid=10171,
09-07 13:16:09.289  1014  1436 D SettingsProvider: name = wifi_on
,09-07 13:16:09.299  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-07 13:16:09.309  7389  7389 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 13:16:09.309  7389  7389 I dhcpcd  : version 5.5.6 starting,
,09-07 13:16:09.309  7389  7389 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 13:16:09.319  1014  1125 E WifiNative-wlan0: do suspend true
,09-07 13:16:09.339  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-07 13:16:09.339  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-07 13:16:09.349   277   996 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:16:09.349  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:09.349  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:09.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.349  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:09.349  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:09.349   277   996 E Netd    : no such netId 503
09-07 13:16:09.349  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
09-07 13:16:09.349  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:09.349  1014  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-07 13:16:09.349  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 13:16:09.349  1014  1127 V NetworkStats: updateIfacesLocked(),
09-07 13:16:09.349  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:09.359  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:09.359  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:09.359  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 13:16:09.359  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:09.359  1014  1127 V NetworkStats: performPollLocked() took 9ms
,09-07 13:16:09.369  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:09.369  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:09.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.369  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-07 13:16:09.369  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 13:16:09.379  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 13:16:09.379  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 13:16:09.379  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:09.379  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-07 13:16:09.379  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 13:16:09.379  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
09-07 13:16:09.379  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 13:16:09.379  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-07 13:16:09.379  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:09.379  1014  1127 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 13:16:09.379  1014  1014 D RttService: SCAN_AVAILABLE : 1
,09-07 13:16:09.379  1014  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 13:16:09.379  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 13:16:09.379  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:09.379  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:09.379  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 13:16:09.379  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:09.379  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:09.379  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:09.379  1624  1624 I Hs20UtilService: Starting #15
09-07 13:16:09.379  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:09.379  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 13:16:09.379  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-07 13:16:09.379  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 13:16:09.379  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 13:16:09.389  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 13:16:09.389  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-07 13:16:09.389   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-07 13:16:09.389  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 13:16:09.389  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 13:16:09.389  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:09.389  1014  1045 D WifiDisplayController: disconnect
09-07 13:16:09.389  1014  1045 D WifiDisplayController: updateConnection
09-07 13:16:09.389  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:09.389  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 13:16:09.389  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:09.389  1014  1124 D WifiP2pService: P2pDisablingState
09-07 13:16:09.389  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 13:16:09.389  1014  1125 E WifiNative-wlan0: do suspend true
09-07 13:16:09.389  1014  1124 D WifiP2pService: p2p socket connection lost
09-07 13:16:09.389  1014  1124 D WifiP2pService: P2pDisabledState
09-07 13:16:09.399  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:09.399  7389  7389 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-07 13:16:09.399  7389  7389 E dhcpcd  : wlan0: sendmsg: Network is unreachable
,09-07 13:16:09.399  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:09.399  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 13:16:09.399  1014  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 13:16:09.399  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 13:16:09.399  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 13:16:09.399  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:09.399  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:09.399  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 13:16:09.399  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 13:16:09.399  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 13:16:09.399  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 13:16:09.399  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:09.399  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 13:16:09.409  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:09.409  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:09.409  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:09.409  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:09.409  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:09.409  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:09.409  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:09.409  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 13:16:09.409  7051  7051 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 13:16:09.419  7066  7066 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:09.419  7389  7389 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-07 13:16:09.429  7389  7389 I dhcpcd  : bssid match
,09-07 13:16:09.429  7389  7389 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
09-07 13:16:09.429  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-07 13:16:09.429  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
09-07 13:16:09.429   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:09.429  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:09.429  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.429  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 13:16:09.429  7336  7336 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 13:16:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 13:16:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.439  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:09.439  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 13:16:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:09.449  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 13:16:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 13:16:09.449  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:09.449  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 13:16:09.449  1174  1174 D HotspotTile: onReceive : 0, 0
,09-07 13:16:09.459  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:09.459  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:09.459  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:09.459  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:09.459  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:09.459  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:09.459  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:09.459  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 13:16:09.459  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:09.459  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:09.459  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:09.459  1624  1624 I Hs20UtilService: Starting #16
,09-07 13:16:09.459  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:09.459  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:09.459  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:09.459  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:09.459  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:09.459  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 13:16:09.459  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:09.459  1014  1436 I ActivityManager: Killing 7082:com.sec.pcw.device/1000 (adj 15): empty #21
,09-07 13:16:09.459  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:09.459  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 13:16:09.459  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:09.459  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:09.469  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:09.469  1014  1429 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:09.469  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:09.469  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:09.469  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:09.469  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:09.469  1624  1624 I Hs20UtilService: Starting #17
,09-07 13:16:09.469  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:09.479  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 13:16:09.479  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 13:16:09.479  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:09.479  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:09.519  7389  7389 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-07 13:16:09.559  7336  7336 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 13:16:09.609  7389  7389 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-07 13:16:09.629  7336  7336 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 13:16:09.629  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:09.629  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 13:16:09.629  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:09.659  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.659  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.659  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:09.659  1014  1128 D Tethering: InitialState.processMessage what=4
09-07 13:16:09.659  7336  7336 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-07 13:16:09.669  1014  1128 E Tethering: No numeric data
,09-07 13:16:09.669  7336  7336 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 13:16:09.669  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 13:16:09.669  1014  1128 D Tethering: clearTetheredNotification()
09-07 13:16:09.669  7336  7336 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 13:16:09.669  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.669  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.669  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:09.669  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:09.669  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-07 13:16:09.669  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:09.669  1174  1174 D HotspotTile: updateTetherState():false, false
09-07 13:16:09.669  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:09.669  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:09.669  7336  7336 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 13:16:09.669  7336  7336 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-07 13:16:09.679  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.679  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.679  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:09.679  1014  1122 V NetworkStats: performPollLocked() took 8ms
09-07 13:16:09.679  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:09.679  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:09.679  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:09.849  7336  7336 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 13:16:09.939  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 13:16:09.939  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.939  1014  1042 D Tethering: interfaceStatusChanged wlan0, false,
,09-07 13:16:09.979  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 13:16:09.979  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:09.979  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:09.989  7336  7336 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-07 13:16:10.089  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-07 13:16:10.089  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,09-07 13:16:10.089  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:10.099  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:10.099  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-07 13:16:10.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:10.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:10.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:10.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:10.099  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:10.099  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-07 13:16:10.109  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 13:16:10.109  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:10.109  1975  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:10.109  1174  1174 D HotspotTile: onReceive : 1, 0
,09-07 13:16:10.119  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:10.119  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:10.119  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:10.119  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:10.129  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:10.129  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:10.129  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:10.129  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:10.129  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 13:16:10.129  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 13:16:10.139  1624  1624 I Hs20UtilService: Starting #18
,09-07 13:16:10.139  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:10.139  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 13:16:10.139  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:10.729   277   990 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-07 13:16:10.729  1014  1042 D Tethering: interfaceRemoved wlan0
,09-07 13:16:10.729  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 13:16:10.889  1014  1042 D Tethering: interfaceRemoved p2p0
,09-07 13:16:10.889  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 13:16:11.389   290   290 E SMD     : DCD OFF,
,09-07 13:16:11.709  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 13:16:12.189  1014  3356 D SSRM:n  : SIOP:: AP = 340
,09-07 13:16:12.299  6777  6833 D BluetoothAdapter: enable(),
,09-07 13:16:12.299  1014  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-07 13:16:12.299  1014  1476 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 13:16:12.299  1014  1476 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 13:16:12.299  1014  1476 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 13:16:12.299  1014  1476 D SettingsProvider: name = bluetooth_on
,09-07 13:16:12.299  1014  1476 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:12.309  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 13:16:12.309  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 13:16:12.309  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-07 13:16:12.309  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-07 13:16:12.319  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 13:16:12.319  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:12.319  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:12.319  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 13:16:12.339  7421  7421 E Zygote  : MountEmulatedStorage()
,09-07 13:16:12.339  7421  7421 E Zygote  : v2
09-07 13:16:12.339  7421  7421 I libpersona: KNOX_SDCARD checking this for 1002
,09-07 13:16:12.339  7421  7421 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:12.339  7421  7421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:12.349  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7421 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-07 13:16:12.349  7421  7421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:12.349  7421  7421 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 13:16:12.389  7421  7421 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:12.389  7421  7421 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:12.409  7421  7421 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 13:16:12.409  7421  7421 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:16:12.439  7421  7421 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding GattService
,09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding HeadsetService,
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding A2dpService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding HidService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding HealthService,
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding PanService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding SapService,
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding SapClientService
,09-07 13:16:12.479  7421  7421 D BtSettings.ProfileConfig: Adding HidDevService
09-07 13:16:12.479  7421  7421 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 13:16:12.489  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 13:16:12.489  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:12.489  1014  1479 D SettingsProvider: selectionArgs: false
09-07 13:16:12.489  1014  1479 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:12.489  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1479 D SettingsProvider: ret = -1
,09-07 13:16:12.489  1014  1095 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-07 13:16:12.489  1014  1095 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 13:16:12.489  1014  1095 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.489  1014  1095 D SettingsProvider: selectionArgs: false
09-07 13:16:12.489  1014  1095 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.489  1014  1095 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1095 D SettingsProvider: ret = -1
,09-07 13:16:12.489  1014  1436 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
09-07 13:16:12.489  1014  1436 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1436 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.489  1014  1436 D SettingsProvider: selectionArgs: false
,09-07 13:16:12.489  1014  1436 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.489  1014  1436 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1436 D SettingsProvider: ret = -1
09-07 13:16:12.489  1014  1438 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-07 13:16:12.489  1014  1438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.489  1014  1438 D SettingsProvider: selectionArgs: false
09-07 13:16:12.489  1014  1438 D SettingsProvider: selectionArgs: 1002,
09-07 13:16:12.489  1014  1438 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1438 D SettingsProvider: ret = -1
09-07 13:16:12.489  1014  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-07 13:16:12.489  1014  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:12.489  1014  1476 D SettingsProvider: selectionArgs: false
,09-07 13:16:12.489  1014  1476 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.489  1014  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1476 D SettingsProvider: ret = -1
09-07 13:16:12.489  1014  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-07 13:16:12.489  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.489  1014  1496 D SettingsProvider: selectionArgs: false
,09-07 13:16:12.489  1014  1496 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.489  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1496 D SettingsProvider: ret = -1
09-07 13:16:12.489  1014  1429 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-07 13:16:12.489  1014  1429 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1429 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-07 13:16:12.489  1014  1429 D SettingsProvider: selectionArgs: false,
09-07 13:16:12.489  1014  1429 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.489  1014  1429 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.489  1014  1429 D SettingsProvider: ret = -1
09-07 13:16:12.489  1014  1480 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-07 13:16:12.489  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.489  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.489  1014  1480 D SettingsProvider: selectionArgs: false
09-07 13:16:12.489  1014  1480 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.499  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.499  1014  1480 D SettingsProvider: ret = -1
09-07 13:16:12.499  1014  1330 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:12.499  1014  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.499  1014  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.499  1014  1330 D SettingsProvider: selectionArgs: false
09-07 13:16:12.499  1014  1330 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.499  1014  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-07 13:16:12.499  1014  1330 D SettingsProvider: ret = -1
09-07 13:16:12.499  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.499  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 13:16:12.499  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.499  1014  1027 D SettingsProvider: selectionArgs: false
09-07 13:16:12.499  1014  1027 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.499  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.499  1014  1027 D SettingsProvider: ret = -1
,09-07 13:16:12.499  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.499  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.499  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:12.499  1014  1026 D SettingsProvider: selectionArgs: false
09-07 13:16:12.499  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:12.499  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.499  1014  1026 D SettingsProvider: ret = -1
09-07 13:16:12.499  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 13:16:12.499  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.499  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:12.499  1014  1479 D SettingsProvider: selectionArgs: false
09-07 13:16:12.499  1014  1479 D SettingsProvider: selectionArgs: 1002
09-07 13:16:12.499  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.499  1014  1479 D SettingsProvider: ret = -1
,09-07 13:16:12.509  7421  7421 D BluetoothAdapterState: make,
,09-07 13:16:12.519  7421  7421 I bluedroid: init,
09-07 13:16:12.519  7421  7436 I BluetoothAdapterState: Entering OffState
,09-07 13:16:12.519  7421  7421 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-07 13:16:12.519  7421  7421 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 13:16:12.519  7421  7421 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 13:16:12.519  7421  7421 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 13:16:12.529  7421  7421 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-07 13:16:12.529  7421  7421 I bluedroid: get_profile_interface socket
09-07 13:16:12.529  7421  7421 I bluedroid: get_profile_interface map_client
,09-07 13:16:12.529  7421  7421 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-07 13:16:12.529  7421  7439 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-07 13:16:12.529  7421  7439 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 13:16:12.529  7421  7439 E BluetoothServiceJni: populateRssiValuesNative
09-07 13:16:12.529  7421  7439 I bluedroid: getModelRssiValues
09-07 13:16:12.529  7421  7439 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 13:16:12.529  7421  7439 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 13:16:12.529  1014  1014 D SettingsProvider: name = bluetooth_name
,09-07 13:16:12.529  7421  7421 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:12.539  7421  7439 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
09-07 13:16:12.539  1014  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 13:16:12.539  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.539  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.539  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.539  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.539  7421  7434 I bluedroid: config_hci_snoop_log
,09-07 13:16:12.539  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-07 13:16:12.539  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-07 13:16:12.539  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-07 13:16:12.539  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 13:16:12.539  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 13:16:12.549  7421  7421 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-07 13:16:12.559  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:12.559  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:12.559  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 13:16:12.559  7421  7436 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 13:16:12.559  7421  7436 D BluetoothAdapterProperties: Setting state to 11
,09-07 13:16:12.559  7421  7436 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 13:16:12.559  7421  7436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 13:16:12.559  7421  7436 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 13:16:12.559  7421  7436 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:12.559  7421  7436 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-07 13:16:12.569  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 13:16:12.569  7421  7436 D BluetoothSecureManager: getInstant: null
,09-07 13:16:12.569  7421  7436 D BluetoothSecureManager: calling getMethod for getService,
09-07 13:16:12.569  7421  7436 D BluetoothSecureManager: calling getService
,09-07 13:16:12.569  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:12.569  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
09-07 13:16:12.569  7421  7436 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@298d1553
,09-07 13:16:12.569  1014  1330 D BluetoothSecureManagerService: isSecureModeEnabled
09-07 13:16:12.569  1014  1330 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-07 13:16:12.569  7421  7436 D BtConfig.SecureMode: isSecureModeOn:false
09-07 13:16:12.569  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService,
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 13:16:12.579  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 13:16:12.579  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:12.579  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:12.579  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 13:16:12.579  7421  7436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:12.579  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.579  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
09-07 13:16:12.579  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-07 13:16:12.589  7421  7436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.589  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.589  7421  7436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.589  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 13:16:12.589  7421  7436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-07 13:16:12.589  1014  1330 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:12.589  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 13:16:12.589  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:12.599  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 13:16:12.599  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:12.599  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:12.599  7421  7436 D BluetoothBondStateMachine: make
,09-07 13:16:12.609  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-07 13:16:12.609  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 13:16:12.609  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-07 13:16:12.609  7421  7441 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 13:16:12.739  1014  1026 I art     : Explicit concurrent mark sweep GC freed 74638(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.388ms total 156.103ms
,09-07 13:16:12.749  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:12.749  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:12.749  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.749  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.749  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:12.749  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:12.749  1014  1429 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.749  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.749  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:12.749  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.749  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.749  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 13:16:12.749  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 13:16:12.749  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:12.759  7421  7421 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:12.759  7421  7421 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:16:12.759  7421  7421 D BtGatt.GattService: start()
09-07 13:16:12.759  7421  7421 D BtGatt.GattService: start()
09-07 13:16:12.759  7421  7421 I bluedroid: get_profile_interface gatt
,09-07 13:16:12.759  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:12.759  7421  7421 D BtGatt.AdvertiseManager: advertise manager created
,09-07 13:16:12.759  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:12.759  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 13:16:12.759  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.759  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.759  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:12.759  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.759  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.759  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 13:16:12.759  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 13:16:12.759  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 13:16:12.759  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:12.769  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:12.769  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:12.769  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:12.769  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:12.779  7444  7444 E Zygote  : MountEmulatedStorage()
,09-07 13:16:12.779  7444  7444 I libpersona: KNOX_SDCARD checking this for 10055
09-07 13:16:12.779  7444  7444 E Zygote  : v2
09-07 13:16:12.779  7444  7444 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:12.779  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:12.779  1014  1476 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7444 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-07 13:16:12.779  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:12.779  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:12.779  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.779  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.779  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.779  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.779  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.789  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-07 13:16:12.789  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 13:16:12.789  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 13:16:12.789  1014  1095 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:12.789  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.789  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.789  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:12.789  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.799  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 13:16:12.799  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 13:16:12.799  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 13:16:12.799  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.799  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.799  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.799  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.799  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.799  7421  7421 D BtGatt.GattService: mStartError = false
09-07 13:16:12.799  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.799  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-07 13:16:12.799  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 13:16:12.799  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 13:16:12.799  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.799  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.799  7421  7421 D HeadsetService: Received start request. Starting profile...
09-07 13:16:12.799  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:12.799  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.799  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.809  7421  7421 D HeadsetService: start()
,09-07 13:16:12.809  7421  7421 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 13:16:12.809  7421  7421 D HeadsetStateMachine: make
09-07 13:16:12.809  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 13:16:12.809  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:12.809  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:12.809  1014  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:12.809  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.809  7421  7421 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 13:16:12.809  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:12.809  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:12.809  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.809  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.809  7444  7444 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:12.809  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 13:16:12.809  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:12.809  7421  7436 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 13:16:12.819  1014  1429 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:12.819  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.819  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.819  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:12.819  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:12.829  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:12.829  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.829  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.829  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 13:16:12.829  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 13:16:12.829  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 13:16:12.829  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-07 13:16:12.829  7421  7436 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 13:16:12.829  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:12.829  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:12.829  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 13:16:12.829  1014  1330 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-07 13:16:12.829  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 13:16:12.829  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:12.829  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:12.829  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 13:16:12.839  7421  7421 I bluedroid: get_profile_interface handsfree
,09-07 13:16:12.849  7444  7444 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,09-07 13:16:12.859  7421  7421 I DualScoManager: Instantiating Dual Sco Manager
,09-07 13:16:12.859  7421  7421 I DualScoManager: Set HeadsetServiceHelper
,09-07 13:16:12.859  7421  7421 D BluetoothAtMessage: createCMTIContentObservers
,09-07 13:16:12.859  1014  1479 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-07 13:16:12.859  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:12.859  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:12.859  1014  1479 D SettingsProvider: selectionArgs: false
09-07 13:16:12.859  1014  1479 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:12.859  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:12.859  1014  1479 D SettingsProvider: ret = -1
,09-07 13:16:12.859  7421  7454 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 13:16:12.859  7421  7421 D HeadsetService: mStartError = false
,09-07 13:16:12.859  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.869  7421  7421 D A2dpService: Received start request. Starting profile...
09-07 13:16:12.869  7421  7454 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 13:16:12.869  7421  7421 D A2dpService: start()
,09-07 13:16:12.869  7421  7454 D HeadsetStateMachine: map size, before remove : 0
,09-07 13:16:12.869  7421  7454 D HeadsetStateMachine: map size, after remove: 0
,09-07 13:16:12.869  7421  7421 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 13:16:12.869  7421  7421 I bluedroid: get_profile_interface avrcp
,09-07 13:16:12.879  7444  7444 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 13:16:12.879  7444  7444 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-07 13:16:12.879  7444  7444 D UserAnalysis: Create SecureDbHelper
,09-07 13:16:12.879  7421  7421 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 13:16:12.879  7421  7421 D Avrcp   : Initialize Media Controller
,09-07 13:16:12.879  7421  7421 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 13:16:12.879  7421  7421 E Avrcp   : getActiveSessions
,09-07 13:16:12.879  7421  7421 D Avrcp   : pick active media Controller
,09-07 13:16:12.879  7421  7421 D Avrcp   : Get the active Media Controller 
,09-07 13:16:12.879  7444  7444 D IntelligenceServiceApplication: onCreate()
,09-07 13:16:12.889  1014  1026 I ActivityManager: Killing 7099:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-07 13:16:12.899  7444  7444 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-07 13:16:12.899  7421  7421 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 13:16:12.899  7421  7464 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 13:16:12.899  7421  7421 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:16:12.899  7421  7421 D A2dpStateMachine: make
,09-07 13:16:12.899  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 13:16:12.899  7421  7421 I bluedroid: get_profile_interface a2dp
09-07 13:16:12.909  7421  7466 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-07 13:16:12.909  7421  7421 E bt-btif : warning : media task started media_task_refcnt 1 
09-07 13:16:12.909  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-07 13:16:12.909  7421  7421 D A2dpService: mStartError = false
09-07 13:16:12.909  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:12.909  7421  7465 D A2dpStateMachine: Enter Disconnected: -2
,09-07 13:16:12.909  7421  7421 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 13:16:12.909  7421  7421 D HidService: Received start request. Starting profile...
09-07 13:16:12.909  7421  7421 D HidService: start()
09-07 13:16:12.909  7421  7421 I bluedroid: get_profile_interface hidhost
09-07 13:16:12.909  7421  7421 D HidService: setHidService(): set to: null
09-07 13:16:12.909  7421  7421 D HidService: mStartError = false
09-07 13:16:12.909  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.909  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-07 13:16:12.909  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-07 13:16:12.909  7421  7421 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 13:16:12.919  7421  7421 D HealthService: Received start request. Starting profile...
09-07 13:16:12.919  7421  7421 D HealthService: start()
,09-07 13:16:12.919  7421  7421 I bluedroid: get_profile_interface health
,09-07 13:16:12.919  7421  7421 D HealthService: mStartError = false
09-07 13:16:12.919  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.919  7421  7421 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 13:16:12.919  7421  7421 D PanService: Received start request. Starting profile...
09-07 13:16:12.919  7421  7421 D PanService: start()
09-07 13:16:12.919  7421  7421 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 13:16:12.919  7421  7421 I bluedroid: get_profile_interface pan
,09-07 13:16:12.919  7421  7421 D PanService: mStartError = false
09-07 13:16:12.919  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.919  7421  7464 D BluetoothMediaBrowser: no now playing list
,09-07 13:16:12.919  7421  7464 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-07 13:16:12.919  7421  7421 D BluetoothMapService: Received start request. Starting profile...
09-07 13:16:12.919  7421  7421 D BluetoothMapService: start()
,09-07 13:16:12.929  7421  7421 D BluetoothMapService: mStartError = false
,09-07 13:16:12.929  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea,
09-07 13:16:12.929  7421  7421 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-07 13:16:12.929  7421  7421 D SapService: Received start request. Starting profile...
09-07 13:16:12.929  7421  7421 D SapService: start()
09-07 13:16:12.929  7421  7421 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 13:16:12.929  7421  7421 I bluedroid: get_profile_interface sap
09-07 13:16:12.929  7421  7421 D SapService: mStartError = false
09-07 13:16:12.929  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:12.929  7421  7421 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 13:16:12.929  1430  1453 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 13:16:12.929  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-07 13:16:12.929  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 13:16:12.939  1430  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,09-07 13:16:12.939  7421  7421 D HeadsetStateMachine: Proxy object connected
,09-07 13:16:12.939  7421  7421 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-07 13:16:12.939  7421  7421 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-07 13:16:12.939  7421  7421 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-07 13:16:12.939  7421  7421 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 13:16:12.939  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 13:16:12.939  7421  7421 D BluetoothA2dp: Proxy object connected
,09-07 13:16:12.939  7421  7421 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-07 13:16:12.939  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 13:16:12.939  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-07 13:16:12.939  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 13:16:12.939  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-07 13:16:12.939  7421  7454 D HeadsetStateMachine: Disconnected process message: 11
09-07 13:16:12.939  7421  7454 D HeadsetStateMachine: Disconnected process message: 18
,09-07 13:16:12.939  7421  7454 D HeadsetStateMachine: Disconnected process message: 10
,09-07 13:16:12.939  7421  7454 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 13:16:12.939  7421  7454 D HeadsetStateMachine: Disconnected process message: 11
,09-07 13:16:12.939  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-07 13:16:12.939  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:12.939  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:12.939  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:12.939  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:12.959  7471  7471 E Zygote  : MountEmulatedStorage()
,09-07 13:16:12.959  7471  7471 E Zygote  : v2
09-07 13:16:12.959  7471  7471 I libpersona: KNOX_SDCARD checking this for 10105
09-07 13:16:12.959  7471  7471 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:12.959  7471  7471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:12.959  1014  1026 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7471 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
09-07 13:16:12.959  7471  7471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:12.959  7471  7471 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 13:16:12.979  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-07 13:16:12.979  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 13:16:12.979  7421  7436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-07 13:16:12.979  7421  7436 I bluedroid: enable
09-07 13:16:12.979  7421  7436 I bt_hci_bdroid: init
,09-07 13:16:12.979  7421  7483 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-07 13:16:12.989  7421  7436 I bt_vendor: bt-vendor : init
09-07 13:16:12.989  7421  7436 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 13:16:12.989  7421  7436 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 13:16:12.989  7421  7436 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-07 13:16:12.989  7421  7436 D bt_userial_mct: userial_init
09-07 13:16:12.989  7421  7436 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 13:16:12.989  7421  7436 I bt_vendor: Starting hciattach daemon
09-07 13:16:12.989  7421  7436 I bt_vendor: try to set false
,09-07 13:16:12.989  7471  7471 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:12.989  7471  7471 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:12.989  7421  7436 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 13:16:12.989  7421  7436 I bt_vendor: Starting hciattach daemon
09-07 13:16:12.989  7421  7436 I bt_vendor: try to set true
,09-07 13:16:13.009  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 13:16:13.069  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-07 13:16:13.079  7497  7497 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 13:16:13.099  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 13:16:13.109  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 13:16:13.109  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 13:16:13.119  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 13:16:13.159   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 13:16:13.159   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:13.159  7471  7508 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 13:16:13.169   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 13:16:13.169   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 13:16:13.169  7471  7508 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 13:16:13.309  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,09-07 13:16:13.309  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 13:16:13.349  7421  7436 I bt_vendor: bluetooth satus is on
,09-07 13:16:13.349  7421  7487 D bt_userial_mct: userial_open(port:0)
09-07 13:16:13.349  7421  7487 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 13:16:13.349  7421  7487 I bt_vendor: Done intiailizing UART
,09-07 13:16:13.349  7421  7487 I bt_vendor: Done intiailizing UART
,09-07 13:16:13.349  7421  7487 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-07 13:16:13.349  7421  7487 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_SAP
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.j,ava:1332)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
,09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
,09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
,09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.359  7471  7471 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:13.359  7471  7471 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:13.369  1014  1480 I ActivityManager: Killing 7114:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 13:16:13.359  7421  7483 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-07 13:16:13.369  7421  7522 D bt_userial_mct: Entering userial_read_thread()
,09-07 13:16:13.369  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:13.379  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:13.419  7471  7507 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 13:16:13.449  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:13.449  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.449  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:13.449  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 13:16:13.459  7421  7483 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-07 13:16:13.469  7421  7483 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42f0ed1 
09-07 13:16:13.469  7421  7483 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42f0ed1 
,09-07 13:16:13.479  7421  7439 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0,
,09-07 13:16:13.479  7421  7439 E bt-btif : Calling BTA_HhEnable
,09-07 13:16:13.479  7421  7439 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 13:16:13.489  7421  7439 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 13:16:13.489  7421  7439 E BluetoothServiceJni: populateRssiValuesNative
09-07 13:16:13.489  7421  7439 I bluedroid: getModelRssiValues
,09-07 13:16:13.489  7421  7439 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 13:16:13.489  7421  7439 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 13:16:13.489  1014  1014 D SettingsProvider: name = bluetooth_name
,09-07 13:16:13.489  7421  7439 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 13:16:13.499  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.499  7421  7439 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 13:16:13.499  7421  7439 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:16:13.499  7421  7439 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:13.499  7421  7439 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-07 13:16:13.499  7421  7439 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-07 13:16:13.499  7421  7439 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-07 13:16:13.499  7421  7439 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 13:16:13.499  7421  7439 E bt-btif : btif_sock_init: !vhci_init
09-07 13:16:13.499  7421  7439 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-07 13:16:13.499  7421  7439 D IOP_DB_BT: db_open: db_open : handle 2965917712l, read 13894 bytes onto local cache
09-07 13:16:13.499  7421  7439 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-07 13:16:13.499  7421  7439 D IOP_DB_BT: db_query: result 1
09-07 13:16:13.499  7421  7439 I         : iop_db_open: iop_db_open status 0
,09-07 13:16:13.499  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.499  7421  7439 D bte_conf: Device ID record 1 : primary
09-07 13:16:13.499  7421  7522 E bt_mct  : hci lib postload completed
09-07 13:16:13.499  7421  7439 D bte_conf:   vendorId            = 0075
09-07 13:16:13.499  7421  7439 D bte_conf:   vendorIdSource      = 0001
09-07 13:16:13.499  7421  7439 D bte_conf:   product             = 0100
09-07 13:16:13.499  7421  7439 D bte_conf:   version             = 0200
09-07 13:16:13.499  7421  7439 D bte_conf:   clientExecutableURL = 
09-07 13:16:13.499  7421  7439 D bte_conf:   serviceDescription  = 
09-07 13:16:13.499  7421  7439 D bte_conf:   documentationURL    = 
09-07 13:16:13.499  7421  7439 D bte_conf: bte_load_did_conf no section named DID2.
,09-07 13:16:13.509  7421  7439 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 13:16:13.509  7421  7436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 13:16:13.509  7421  7436 D BluetoothAdapterProperties: ScanMode =  20
09-07 13:16:13.509  7421  7436 D BluetoothAdapterProperties: State =  11
,09-07 13:16:13.509  1014  1438 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 13:16:13.509  7421  7439 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 13:16:13.509  7421  7439 D BluetoothAdapterProperties: Scan Mode:21
09-07 13:16:13.509  7421  7439 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:13.509  7421  7436 D BluetoothAdapterProperties: Setting state to 12
09-07 13:16:13.509  7421  7436 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 13:16:13.509  1014  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-07 13:16:13.509  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:13.509  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:13.509  1014  1480 D SettingsProvider: selectionArgs: false
09-07 13:16:13.509  1014  1480 D SettingsProvider: selectionArgs: 1002
09-07 13:16:13.509  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:13.509  1014  1480 D SettingsProvider: ret = -1
,09-07 13:16:13.509  7421  7436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:13.509  7421  7436 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 13:16:13.519  1014  1429 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:13.519  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.519  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.519  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.519  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.519  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:13.519  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 13:16:13.529  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 13:16:13.529  7421  7436 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:13.529  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 13:16:13.529  7421  7436 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 13:16:13.529  7421  7436 D BluetoothAdapterService: starting service from this receiver
,09-07 13:16:13.529  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:13.529  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 13:16:13.529  1014  1014 D BluetoothA2dp: Proxy object connected
,09-07 13:16:13.529  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.529  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.529  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:13.529  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:13.529  3063  3072 D BluetoothPan: Binding service...
,09-07 13:16:13.529  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 13:16:13.529  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.529  7421  7436 I BluetoothAdapterState: Entering On State from state = 11
,09-07 13:16:13.529  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.529  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.529  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.529  1441  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.529  1441  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.529  1174  4438 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.539  1174  4438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.539  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:13.539  1430  6968 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.539  7421  7421 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 13:16:13.539  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:13.539  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:13.539  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.539  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.539  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:13.549  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:13.549  1430  6968 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:13.549  1975  1991 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 13:16:13.549  1975  1991 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 13:16:13.549  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.549  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 13:16:13.549  1452  1724 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.549  1452  1724 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.549  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:13.549  3063  3071 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 13:16:13.549  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-07 13:16:13.549  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.549  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.549  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.549  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.559  7421  7435 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.559  7421  7435 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.559  3063  3072 D Bluetoothsap: onBluetoothStateChange: up=true
09-07 13:16:13.559  3063  3072 D Bluetoothsap: Binding service...
,09-07 13:16:13.559  7421  7421 I BluetoothPbapService: Handler(): got msg=1
,09-07 13:16:13.559  1014  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 13:16:13.559  3063  3063 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:13.559  3063  3063 D PanProfile: Bluetooth service connected
,09-07 13:16:13.569  7421  7529 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 13:16:13.569  3063  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 13:16:13.569  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 13:16:13.569  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.569  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.569  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.569  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-07 13:16:13.569  3063  3072 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 13:16:13.569  7421  7529 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 13:16:13.569  7421  7529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:13.569  3063  7528 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.569  7421  7529 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-07 13:16:13.569  7421  7529 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:13.569  7421  7529 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:13.569  7421  7529 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@def46b4
09-07 13:16:13.569  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:13.569  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:13.569  7421  7529 D BluetoothSocket: channel: 19
09-07 13:16:13.569  7421  7529 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-07 13:16:13.569  3063  3063 D BluetoothInputDevice: Proxy object connected
09-07 13:16:13.569  3063  3063 D HidProfile: Bluetooth service connected
,09-07 13:16:13.569  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.569  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.569  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.579  3063  7528 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:13.579  1430  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.579  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:13.579  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:13.579  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.579  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:13.579  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-07 13:16:13.579  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 13:16:13.579  3063  3063 D SapProfile: Bluetooth service connected
09-07 13:16:13.579  3063  3063 D Bluetoothsap: getConnectedDevices()
,09-07 13:16:13.579  1430  1453 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 13:16:13.579  3063  3071 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 13:16:13.579  3063  3063 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:13.579  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-07 13:16:13.579  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.579  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.579  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.579  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.579  3063  3072 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 13:16:13.589  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-07 13:16:13.589  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.589  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.589  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.589  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.589  3063  3063 D BluetoothMap: Proxy object connected
09-07 13:16:13.589  3063  3063 D MapProfile: Bluetooth service connected
09-07 13:16:13.589  3063  3063 D BluetoothMap: getConnectedDevices()
,09-07 13:16:13.589  1014  1044 D BluetoothPan: Binding service...
09-07 13:16:13.589  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 13:16:13.589  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.589  1430  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.589  1430  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.589  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:13.589  3063  3063 D BluetoothPbap: Proxy object connected
09-07 13:16:13.589  3063  3063 D PbapServerProfile: Bluetooth service connected
,09-07 13:16:13.589  1452  1957 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.589  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:13.589  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:13.589  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.589  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.589  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-07 13:16:13.589  1452  1957 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:13.589  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-07 13:16:13.589  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 13:16:13.589  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-07 13:16:13.589  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 13:16:13.589  6777  6791 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.589  6777  6791 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.589  7421  7434 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:16:13.599  3063  7528 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.599  3063  7528 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.599  7471  7479 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:13.599  7471  7479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:13.599  3063  3071 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:13.599  3063  3071 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.599  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 13:16:13.599  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.599  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.599  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.599  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.599  3063  3063 D BluetoothA2dp: Proxy object connected
09-07 13:16:13.599  3063  3063 D A2dpProfile: Bluetooth service connected
,09-07 13:16:13.599  1430  6968 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:13.599  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:13.599  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:13.599  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.599  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.599  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.609  1430  6968 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:13.609  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 13:16:13.609  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 13:16:13.609  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:13.609  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-07 13:16:13.609  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 13:16:13.609  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-07 13:16:13.619  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:13.619  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:13.619  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-07 13:16:13.619  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:13.619  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:13.619  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:13.619  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19b994f0, true
,09-07 13:16:13.629  1430  1430 D BluetoothHeadset: registerMessageListener
,09-07 13:16:13.629  1014  1438 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:13.629  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 13:16:13.629  1014  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 13:16:13.629  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:13.629  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:13.629  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.629  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.639  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:13.639  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.639  7421  7434 D HeadsetService: registerMessageListener
,09-07 13:16:13.639  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.639  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:13.639  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 13:16:13.639  7421  7434 D HeadsetService: registerMessageListener
,09-07 13:16:13.639  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-07 13:16:13.639  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 13:16:13.639  7421  7454 D HeadsetStateMachine: Disconnected process message: 70
,09-07 13:16:13.639  7421  7454 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@39a422dd
,09-07 13:16:13.639  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-07 13:16:13.639  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-07 13:16:13.639  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 13:16:13.639  3063  3063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-07 13:16:13.639  3063  3063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 13:16:13.639  3063  3063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-07 13:16:13.649  3063  3063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 13:16:13.649  7421  7454 D HeadsetStateMachine: Disconnected process message: 9
,09-07 13:16:13.649  7421  7454 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 13:16:13.649  7421  7531 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 13:16:13.659   282   680 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-07 13:16:13.659  7421  7531 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:13.659  7421  7531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:13.659   282   680 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 13:16:13.659  7421  7531 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-07 13:16:13.659  7421  7531 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:13.659  7421  7531 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:13.659  7421  7531 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21705e52
,09-07 13:16:13.659  7421  7531 D BluetoothSocket: channel: 5
09-07 13:16:13.659  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 13:16:13.659   282   680 V voice   : voice_set_parameters: exit with code(-2)
09-07 13:16:13.659   282   680 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-07 13:16:13.659   282   680 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 13:16:13.659   282   680 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 13:16:13.659   282   680 V audio_hw_primary: adev_set_parameters: exit
,09-07 13:16:13.659  7421  7454 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 13:16:13.659  1014  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 13:16:13.659  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.659  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.659  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.659  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:13.679  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:13.679  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:13.679  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:13.679  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 13:16:13.689  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:13.689  7421  7421 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 13:16:13.689  1014  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:13.699  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.699  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.699  1014  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:13.699  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:13.709  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:13.709  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:13.709  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 13:16:13.719  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.719  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:13.719  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:13.729  1975  7537 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 13:16:13.729  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:13.729  1014  1496 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 13:16:13.739  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:13.739  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:13.739  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:13.739  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:13.749  7421  7541 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:13.749  7421  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:13.749  7421  7541 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-07 13:16:13.759  7421  7541 D BluetoothSocket: bindListen(), new LocalSocket ,
09-07 13:16:13.759  7421  7541 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:13.759  7421  7541 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf0b84c
09-07 13:16:13.759  7421  7541 D BluetoothSocket: channel: 12
09-07 13:16:13.759  7421  7541 I BtOppRfcommListener: Accept thread started.
,09-07 13:16:13.759  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:13.759  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:13.759  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:13.769  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:13.769  1975  7537 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-07 13:16:14.389   290   290 E SMD     : DCD OFF
,09-07 13:16:15.309  6777  6833 D BluetoothAdapter: disable()
,09-07 13:16:15.309  1014  1095 D SettingsProvider: name = bluetooth_on
,09-07 13:16:15.329  7421  7436 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-07 13:16:15.329  7421  7436 D BluetoothAdapterProperties: Setting state to 13
09-07 13:16:15.329  7421  7436 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 13:16:15.329  7421  7436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:15.329  7421  7436 D BluetoothAdapterService: updateAdapterState state is 13
09-07 13:16:15.329  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:15.329  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.329  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.329  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:15.329  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.329  7421  7436 D BluetoothAdapterService: Autoconnection is available 
,09-07 13:16:15.329  7421  7436 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-07 13:16:15.329  7421  7436 D BluetoothAdapterService: terminating service from this receiver
,09-07 13:16:15.329  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.329  7421  7421 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 13:16:15.329  7421  7421 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16dd095, channel: 19, state: LISTENING
09-07 13:16:15.339  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.339  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.339  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.339  7421  7421 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16dd095, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@def46b4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@398d65aamSocket: android.net.LocalSocket@21aa459b impl:android.net.LocalSocketImpl@27970d38 fd:FileDescriptor[74]
09-07 13:16:15.339  7421  7421 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21aa459b impl:android.net.LocalSocketImpl@27970d38 fd:FileDescriptor[74]
,09-07 13:16:15.339  7421  7436 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 13:16:15.339  7421  7436 D BluetoothAdapterProperties: mDiscovering is false
,09-07 13:16:15.339  1014  1330 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 13:16:15.339  3063  3063 D BluetoothPbap: Proxy object disconnected
09-07 13:16:15.339  3063  3063 D PbapServerProfile: Bluetooth service disconnected
,09-07 13:16:15.339  7421  7436 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,09-07 13:16:15.349  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:15.349  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:15.349  7421  7439 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 13:16:15.349  7421  7439 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:15.349  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:15.349  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:15.349  7421  7436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-07 13:16:15.349  7421  7436 E bt-btif : btif_dm_generic_evtnup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 13:16:15.359  7421  7436 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-07 13:16:15.359  7421  7436 E bt-btif : cmd socket is not created
09-07 13:16:15.359  7421  7541 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:16:15.359  7421  7436 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 13:16:15.359  7421  7483 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-07 13:16:15.359  7421  7483 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-07 13:16:15.359  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-07 13:16:15.359  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:15.359  7421  7483 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 13:16:15.369  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:15.369  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:15.369  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:15.369  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:15.379  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:15.379  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-07 13:16:15.389  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-07 13:16:15.389  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:15.389  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:15.389  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:15.389  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:15.389  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-07 13:16:15.389  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 13:16:15.399  1014  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:15.399  1014  1095 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 13:16:15.399  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 13:16:15.399  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 13:16:15.399  7421  7421 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c343276, channel: 5, state: LISTENING
09-07 13:16:15.399  7421  7421 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c343276, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21705e52, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6dda077mSocket: android.net.LocalSocket@64bc4e4 impl:android.net.LocalSocketImpl@30987d4d fd:FileDescriptor[76]
09-07 13:16:15.399  7421  7421 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@64bc4e4 impl:android.net.LocalSocketImpl@30987d4d fd:FileDescriptor[76]
,09-07 13:16:15.399  7421  7421 I BtOppRfcommListener: stopping Accept Thread
09-07 13:16:15.399  7421  7421 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1da90002, channel: 12, state: LISTENING
09-07 13:16:15.399  7421  7421 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1da90002, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf0b84c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2281cd13mSocket: android.net.LocalSocket@2d724b50 impl:android.net.LocalSocketImpl@3c7ca149 fd:FileDescriptor[80]
09-07 13:16:15.399  7421  7421 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d724b50 impl:android.net.LocalSocketImpl@3c7ca149 fd:FileDescriptor[80]
,09-07 13:16:15.409  7421  7541 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 13:16:15.409  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:15.409  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:15.409  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:15.409  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.409  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.409  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:15.409  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:15.409  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:15.419  7421  7421 V BluetoothOppManager: cleanUp...
,09-07 13:16:15.419  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:15.419  1014  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 13:16:15.419  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.419  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:15.419  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.419  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:15.429  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:15.429  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:15.429  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:15.429  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 13:16:15.459  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:15.459  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 13:16:15.559  7421  7483 W bt-btif : ag scb idx 1 not allocated
09-07 13:16:15.559  7421  7483 W bt-btif : ag scb idx 2 not allocated
09-07 13:16:15.559  7421  7483 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 13:16:15.559  7421  7522 I bt_userial_mct: exiting userial_read_thread
09-07 13:16:15.559  7421  7522 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 13:16:15.559  7421  7439 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 13:16:15.559  7421  7487 I bt_vendor: hw_epilog_process
09-07 13:16:15.559  7421  7439 D bt_userial_mct: userial_close
09-07 13:16:15.559  7421  7439 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-07 13:16:15.929  7421  7439 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-07 13:16:15.929  7421  7439 I bt_vendor: bluetooth satus is on
09-07 13:16:15.929  7421  7439 I bt_vendor: bt-vendor : resetting BT status
09-07 13:16:15.929  7421  7439 I bt_vendor: Starting hciattach daemon
09-07 13:16:15.929  7421  7439 I bt_vendor: try to set false
,09-07 13:16:15.929  7421  7439 I bt_vendor: Starting hciattach daemon
09-07 13:16:15.929  7421  7439 I bt_vendor: try to set false
,09-07 13:16:15.929  7421  7439 I bt_vendor: cleanup
,09-07 13:16:15.929  7421  7483 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 13:16:15.929  7421  7439 I GKI_LINUX: GKI_exit_task 0 done,
09-07 13:16:15.929  7421  7439 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-07 13:16:15.929  7421  7436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,09-07 13:16:15.929  7421  7436 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 13:16:15.929  7421  7436 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-07 13:16:15.929  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-07 13:16:15.929  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 13:16:15.929  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
,09-07 13:16:15.929  1014  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:15.929  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
,09-07 13:16:15.939  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:15.939  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-07 13:16:15.939  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 13:16:15.939  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 13:16:15.939  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 13:16:15.939  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:15.939  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:15.939  7421  7421 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:15.939  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.939  7421  7421 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 13:16:15.939  7421  7421 D BtGatt.GattService: stop()
09-07 13:16:15.939  7421  7421 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 13:16:15.939  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.939  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.939  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.939  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 13:16:15.939  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:15.939  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:15.939  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:15.939  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 13:16:15.949  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:15.949  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:15.949  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.949  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.949  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-07 13:16:15.949  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 13:16:15.949  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 13:16:15.949  1014  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:15.949  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.949  7421  7421 D HeadsetService: Received stop request...Stopping profile...
09-07 13:16:15.949  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.949  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:15.949  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.959  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-07 13:16:15.959  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 13:16:15.959  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 13:16:15.959  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:15.959  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:15.959  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.959  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.959  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.959  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.959  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-07 13:16:15.959  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 13:16:15.959  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 13:16:15.959  1014  1095 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:15.969  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.969  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 13:16:15.969  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.969  3063  3063 D HeadsetProfile: Bluetooth service disconnected
09-07 13:16:15.969  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.969  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.969  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 13:16:15.969  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:15.969  7421  7436 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:15.969  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:15.969  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.969  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:15.969  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.969  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.969  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 13:16:15.969  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:15.969  7421  7436 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 13:16:15.969  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:15.979  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:15.979  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:15.979  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:15.979  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:15.979  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:15.979  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 13:16:15.979  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 13:16:15.979  7421  7436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 13:16:15.979  7421  7436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
09-07 13:16:15.979  7421  7436 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 13:16:15.979  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-07 13:16:15.979  7421  7421 D A2dpService: Received stop request...Stopping profile...
,09-07 13:16:15.979  7421  7465 D A2dpStateMachine: Exit Disconnected: -1
,09-07 13:16:15.989  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:15.989  1014  1014 D BluetoothA2dp: Proxy object disconnected
,09-07 13:16:15.989  7421  7421 D HidService: Received stop request...Stopping profile...
09-07 13:16:15.989  7421  7421 D HidService: Stopping Bluetooth HidService
09-07 13:16:15.989  7421  7421 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 13:16:15.989  7421  7421 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 13:16:15.989  7421  7421 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 13:16:15.989  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:15.989  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 13:16:15.989  3063  3063 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:15.989  3063  3063 D A2dpProfile: Bluetooth service disconnected
09-07 13:16:15.989  3063  3063 D BluetoothInputDevice: Proxy object disconnected
09-07 13:16:15.989  3063  3063 D HidProfile: Bluetooth service disconnected
,09-07 13:16:15.989  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-07 13:16:15.989  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 13:16:15.989  7421  7421 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 13:16:15.989  7421  7421 D HealthService: Received stop request...Stopping profile...
,09-07 13:16:15.989  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:15.999  7421  7421 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
09-07 13:16:15.999  7421  7421 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:16:15.999  7421  7421 D PanService: Received stop request...Stopping profile...
09-07 13:16:15.999  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:15.999  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 13:16:15.999  3063  3063 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:16:15.999  3063  3063 D PanProfile: Bluetooth service disconnected
,09-07 13:16:15.999  7421  7421 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 13:16:15.999  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:16.009  7421  7421 D SapService: Received stop request...Stopping profile...
09-07 13:16:16.009  7421  7421 D SapService: Stopping Bluetooth SapService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-07 13:16:16.009  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 13:16:16.009  7421  7421 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-07 13:16:16.009  3063  3063 D BluetoothMap: Proxy object disconnected
,09-07 13:16:16.009  7421  7466 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 13:16:16.009  7421  7421 I GKI_LINUX: GKI_exit_task 2 done
,09-07 13:16:16.009  7421  7421 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 13:16:16.009  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 13:16:16.009  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 13:16:16.009  7421  7421 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 13:16:16.009  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 13:16:16.009  7421  7421 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 13:16:16.009  7421  7421 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 13:16:16.009  3063  3063 D MapProfile: Bluetooth service disconnected
,09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-07 13:16:16.009  7421  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:16.009  7421  7421 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 13:16:16.009  7421  7421 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-07 13:16:16.009  7421  7421 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 13:16:16.009  7421  7421 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 13:16:16.009  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 13:16:16.009  7421  7436 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-07 13:16:16.009  7421  7436 D BluetoothAdapterProperties: Setting state to 10
09-07 13:16:16.009  7421  7436 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 13:16:16.009  7421  7436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:16.009  7421  7436 D BluetoothAdapterService: updateAdapterState state is 10
09-07 13:16:16.019  3063  3063 D SapProfile: Bluetooth service disconnected
09-07 13:16:16.019  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:16.019  7421  7436 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:16.019  7421  7436 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 13:16:16.019  7421  7436 I BluetoothAdapterState: Entering OffState
,09-07 13:16:16.019  1441  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  1441  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  1174  4448 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  1174  4448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  1975  1985 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-07 13:16:16.019  1975  1985 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  1452  1957 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  1452  1957 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  3063  7528 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:16:16.019  7421  7440 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-07 13:16:16.019  7421  7440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  3063  3071 D Bluetoothsap: onBluetoothStateChange: up=false
09-07 13:16:16.019  3063  3071 D Bluetoothsap: Unbinding service...
09-07 13:16:16.019  3063  7528 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:16:16.019  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:16:16.019  1430  1447 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:16.019  1430  1447 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  6777  6791 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  6777  6791 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  6777  6791 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 13:16:16.019  6777  6791 D BluetoothLeAdvertiser: Exit stop advertising
09-07 13:16:16.019  6777  6791 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-07 13:16:16.019  6777  6791 D BluetoothLeScanner: Exiting stopAllScan
09-07 13:16:16.019  7421  7530 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:16.019  3063  3072 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 13:16:16.019  3063  3072 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  7471  7486 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 13:16:16.019  7471  7486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 13:16:16.019  3063  7528 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:16.019  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 13:16:16.029  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 13:16:16.039  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:16.039  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-07 13:16:16.039  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 13:16:16.039  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.039  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:16.039  1174  1710 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.039  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:16.039  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-07 13:16:16.039  1174  1710 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.039  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.039  1174  1174 D BluetoothAdapter: 74414069: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.039  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 13:16:16.049  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 13:16:16.049  1014  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 13:16:16.049  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:16.049  1975  2158 D BluetoothAdapter: 743654442: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.049  1975  2158 D BluetoothAdapter: 743654442: getState() :  mService = null. Returning STATE_OFF
,09-07 13:16:16.049  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 13:16:16.049  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:16.059  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:16.059  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:16.059  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:16.059  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:16.059  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:16.059  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:16.059  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:16.059  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:16.059  7421  7439 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 13:16:16.059  7421  7421 I GKI_LINUX: GKI_exit_task 1 done
09-07 13:16:16.059  7421  7421 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-07 13:16:16.069  7421  7421 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 13:16:16.069  1014  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 13:16:16.069  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:16.069  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:16.069  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:16.069  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:16.069  7421  7421 I art     : System.exit called, status: 0
09-07 13:16:16.069  7421  7421 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 13:16:16.079  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:16.079  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:16.079  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:16.079  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 13:16:16.159  1014  1438 I ActivityManager: Process com.android.bluetooth (pid 7421)(adj 0) has died(40,710)
,09-07 13:16:16.169  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:16.169  1014  1436 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:16.169  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 13:16:16.169  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:16.169  1014  1436 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:16.169  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:16.179  1975  7556 D EasyUnlockInitService: Handling intent for initializer IntentService.,
,09-07 13:16:16.179  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:16.189  1014  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:16.189  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:16.189  1014  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:16.189  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:16.199  1975  7556 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-07 13:16:16.609  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 13:16:16.609  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 13:16:16.609  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-07 13:16:16.619  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 13:16:16.619  1014  1026 D BatteryService: stay LED for fully charged
,09-07 13:16:16.619  1014  1014 I MotionRecognitionService: Plugged
,09-07 13:16:16.619  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 13:16:16.619  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 13:16:16.619  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 13:16:16.629  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 13:16:16.629  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 13:16:16.649  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-07 13:16:16.649  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-07 13:16:16.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:16.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:16.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:17.149  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,09-07 13:16:17.149  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-07 13:16:17.149  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-07 13:16:17.149  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=13022)
,09-07 13:16:17.389   290   290 E SMD     : DCD OFF,
,09-07 13:16:18.329  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 13:16:18.329  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:18.409  1014  1322 E Watchdog: !@Sync 4
,09-07 13:16:19.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 13:16:20.389   290   290 E SMD     : DCD OFF
,09-07 13:16:20.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 13:16:21.329  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:21.329  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@357d9ab4 added. We now have 6 listener(s)
09-07 13:16:21.329  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:21.329  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:21.329  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26d5e6dd added. We now have 7 listener(s)
09-07 13:16:21.329  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:21.329  6777  6833 I System.out: IsBluetoothEnabled
,09-07 13:16:21.329  6777  6833 D BluetoothAdapter: disable()
,09-07 13:16:21.329  1014  1479 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-07 13:16:21.339  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:21.339  6777  6833 D BluetoothAdapter: enable()
,09-07 13:16:21.339  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-07 13:16:21.339  1014  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 13:16:21.339  1014  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 13:16:21.339  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 13:16:21.339  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:21.349  1014  1027 D SettingsProvider: name = bluetooth_on
,09-07 13:16:21.349  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 13:16:21.349  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 13:16:21.349  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-07 13:16:21.349  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-07 13:16:21.349  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:21.349  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:21.349  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 13:16:21.349  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:21.369  7563  7563 E Zygote  : MountEmulatedStorage()
09-07 13:16:21.369  7563  7563 E Zygote  : v2
09-07 13:16:21.369  7563  7563 I libpersona: KNOX_SDCARD checking this for 1002
09-07 13:16:21.369  7563  7563 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:21.369  7563  7563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:21.369  7563  7563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:21.369  7563  7563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:21.369  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7563 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-07 13:16:21.389  7563  7563 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:21.389  7563  7563 D ActivityThread: Added TimaKeyStore provider
09-07 13:16:21.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:16:21.409  7563  7563 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 13:16:21.409  7563  7563 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:16:21.439  7563  7563 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-07 13:16:21.469  7563  7563 D BtSettings.ProfileConfig: Adding GattService
,09-07 13:16:21.469  7563  7563 D BtSettings.ProfileConfig: Adding HeadsetService
,09-07 13:16:21.469  7563  7563 D BtSettings.ProfileConfig: Adding A2dpService
,09-07 13:16:21.469  7563  7563 D BtSettings.ProfileConfig: Adding HidService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding HealthService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding PanService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding SapService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding SapClientService
,09-07 13:16:21.479  7563  7563 D BtSettings.ProfileConfig: Adding HidDevService
,09-07 13:16:21.479  7563  7563 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 13:16:21.479  1014  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 13:16:21.479  1014  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 13:16:21.479  1014  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.489  1014  1476 D SettingsProvider: selectionArgs: false
,09-07 13:16:21.489  1014  1476 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:21.489  1014  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.489  1014  1476 D SettingsProvider: ret = -1
,09-07 13:16:21.489  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:21.489  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.489  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.489  1014  1479 D SettingsProvider: selectionArgs: false
,09-07 13:16:21.489  1014  1479 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.489  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.489  1014  1479 D SettingsProvider: ret = -1
,09-07 13:16:21.489  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:21.489  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.489  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:21.489  1014  1026 D SettingsProvider: selectionArgs: false
09-07 13:16:21.489  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:21.489  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.489  1014  1026 D SettingsProvider: ret = -1
,09-07 13:16:21.489  1014  1429 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-07 13:16:21.489  1014  1429 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.489  1014  1429 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:21.489  1014  1429 D SettingsProvider: selectionArgs: false
09-07 13:16:21.489  1014  1429 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.489  1014  1429 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 13:16:21.489  1014  1429 D SettingsProvider: ret = -1
,09-07 13:16:21.499  1014  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-07 13:16:21.499  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1480 D SettingsProvider: selectionArgs: false
,09-07 13:16:21.499  1014  1480 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 13:16:21.499  1014  1480 D SettingsProvider: ret = -1
,09-07 13:16:21.499  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-07 13:16:21.499  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1027 D SettingsProvider: selectionArgs: false
09-07 13:16:21.499  1014  1027 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1027 D SettingsProvider: ret = -1
,09-07 13:16:21.499  1014  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
09-07 13:16:21.499  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1496 D SettingsProvider: selectionArgs: false,
09-07 13:16:21.499  1014  1496 D SettingsProvider: selectionArgs: 1002,
09-07 13:16:21.499  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 13:16:21.499  1014  1496 D SettingsProvider: ret = -1
,09-07 13:16:21.499  1014  1330 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-07 13:16:21.499  1014  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1330 D SettingsProvider: selectionArgs: false,
09-07 13:16:21.499  1014  1330 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1330 D SettingsProvider: ret = -1
09-07 13:16:21.499  1014  1095 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:21.499  1014  1095 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1095 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1095 D SettingsProvider: selectionArgs: false
09-07 13:16:21.499  1014  1095 D SettingsProvider: selectionArgs: 1002
,09-07 13:16:21.499  1014  1095 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1095 D SettingsProvider: ret = -1
09-07 13:16:21.499  1014  1436 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:21.499  1014  1436 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1436 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 13:16:21.499  1014  1436 D SettingsProvider: selectionArgs: false
09-07 13:16:21.499  1014  1436 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1436 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1436 D SettingsProvider: ret = -1
09-07 13:16:21.499  1014  1438 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-07 13:16:21.499  1014  1438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1438 D SettingsProvider: selectionArgs: false
09-07 13:16:21.499  1014  1438 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1438 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1438 D SettingsProvider: ret = -1
09-07 13:16:21.499  1014  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 13:16:21.499  1014  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.499  1014  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.499  1014  1476 D SettingsProvider: selectionArgs: false
09-07 13:16:21.499  1014  1476 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.499  1014  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.499  1014  1476 D SettingsProvider: ret = -1
,09-07 13:16:21.519  7563  7563 D BluetoothAdapterState: make,
,09-07 13:16:21.519  7563  7563 I bluedroid: init,
09-07 13:16:21.519  7563  7578 I BluetoothAdapterState: Entering OffState
,09-07 13:16:21.519  7563  7563 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-07 13:16:21.519  7563  7563 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 13:16:21.519  7563  7563 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 13:16:21.519  7563  7563 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 13:16:21.519  7563  7563 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-07 13:16:21.519  7563  7563 I bluedroid: get_profile_interface socket
09-07 13:16:21.519  7563  7563 I bluedroid: get_profile_interface map_client
09-07 13:16:21.519  7563  7581 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-07 13:16:21.519  7563  7563 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-07 13:16:21.529  7563  7581 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 13:16:21.529  7563  7563 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 13:16:21.529  7563  7581 E BluetoothServiceJni: populateRssiValuesNative
09-07 13:16:21.529  7563  7581 I bluedroid: getModelRssiValues
,09-07 13:16:21.529  7563  7581 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 13:16:21.529  7563  7581 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 13:16:21.529  1014  1438 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 13:16:21.529  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.529  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:21.539  1014  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.539  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.539  7563  7581 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 13:16:21.539  1014  1014 D SettingsProvider: name = bluetooth_name
,09-07 13:16:21.539  7563  7572 I bluedroid: config_hci_snoop_log,
,09-07 13:16:21.539  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 13:16:21.539  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-07 13:16:21.539  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-07 13:16:21.549  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 13:16:21.549  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 13:16:21.549  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:21.549  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 13:16:21.549  7563  7563 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-07 13:16:21.549  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 13:16:21.559  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 13:16:21.559  7563  7578 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 13:16:21.559  7563  7578 D BluetoothAdapterProperties: Setting state to 11
,09-07 13:16:21.559  7563  7578 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 13:16:21.559  7563  7578 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 13:16:21.559  7563  7578 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 13:16:21.559  7563  7578 D BluetoothAdapterService: Autoconnection is available 
,09-07 13:16:21.559  7563  7578 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-07 13:16:21.559  7563  7578 D BluetoothSecureManager: getInstant: null
,09-07 13:16:21.559  7563  7578 D BluetoothSecureManager: calling getMethod for getService
,09-07 13:16:21.559  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:21.559  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-07 13:16:21.569  7563  7578 D BluetoothSecureManager: calling getService
,09-07 13:16:21.569  7563  7578 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@298d1553
,09-07 13:16:21.569  1014  1436 D BluetoothSecureManagerService: isSecureModeEnabled
,09-07 13:16:21.569  1014  1436 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-07 13:16:21.569  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:21.569  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:21.569  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-07 13:16:21.579  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:21.579  7563  7578 D BtConfig.SecureMode: isSecureModeOn:false
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 13:16:21.579  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:21.579  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:21.579  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:21.579  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:21.579  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-07 13:16:21.579  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 13:16:21.589  1014  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 13:16:21.589  7563  7578 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-07 13:16:21.589  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:21.589  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 13:16:21.589  7563  7578 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:21.589  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-07 13:16:21.589  7563  7578 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:21.589  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 13:16:21.589  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:21.589  7563  7578 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 13:16:21.589  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 13:16:21.589  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:21.589  7563  7578 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-07 13:16:21.589  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.589  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:21.589  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:21.589  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:21.599  7563  7578 D BluetoothBondStateMachine: make
,09-07 13:16:21.599  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:21.599  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-07 13:16:21.599  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 13:16:21.599  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-07 13:16:21.599  7563  7583 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 13:16:21.599  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.599  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.599  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.599  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.599  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.599  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 13:16:21.599  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 13:16:21.599  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 13:16:21.609  7563  7563 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:21.609  7563  7563 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:16:21.609  7563  7563 D BtGatt.GattService: start()
09-07 13:16:21.609  7563  7563 D BtGatt.GattService: start()
09-07 13:16:21.609  7563  7563 I bluedroid: get_profile_interface gatt
09-07 13:16:21.609  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:21.609  7563  7563 D BtGatt.AdvertiseManager: advertise manager created
,09-07 13:16:21.609  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:21.609  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.609  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-07 13:16:21.609  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.609  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.609  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:21.609  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.619  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 13:16:21.619  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 13:16:21.619  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 13:16:21.619  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.619  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.619  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:21.619  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.619  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.619  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-07 13:16:21.619  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 13:16:21.619  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 13:16:21.619  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.619  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.619  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.619  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.619  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.629  7563  7563 D BtGatt.GattService: mStartError = false
,09-07 13:16:21.629  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.629  7563  7563 D HeadsetService: Received start request. Starting profile...
,09-07 13:16:21.629  7563  7563 D HeadsetService: start()
,09-07 13:16:21.629  7563  7563 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 13:16:21.629  7563  7563 D HeadsetStateMachine: make
,09-07 13:16:21.629  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 13:16:21.629  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 13:16:21.629  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 13:16:21.629  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.629  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.639  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.639  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.639  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.639  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-07 13:16:21.639  7563  7563 E HeadsetStateMachine: # of Max HF connection is 2
09-07 13:16:21.639  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 13:16:21.639  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 13:16:21.639  1014  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:21.639  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.639  1014  3373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 13:16:21.639  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:21.649  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.649  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.649  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-07 13:16:21.649  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.649  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:21.649  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.649  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-07 13:16:21.649  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 13:16:21.649  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 13:16:21.649  7563  7578 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-07 13:16:21.649  1014  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-07 13:16:21.649  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.649  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.649  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.649  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 13:16:21.649  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:21.649  7563  7563 I bluedroid: get_profile_interface handsfree
09-07 13:16:21.649  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.649  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.659  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.659  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.659  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-07 13:16:21.659  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 13:16:21.659  7563  7578 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 13:16:21.659  1014  1095 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:21.659  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:21.659  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:21.659  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:21.659  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 13:16:21.669  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:21.669  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 13:16:21.669  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 13:16:21.669  7563  7578 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 13:16:21.669  7563  7578 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 13:16:21.669  7563  7578 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 13:16:21.669  7563  7563 I DualScoManager: Instantiating Dual Sco Manager
09-07 13:16:21.669  7563  7563 I DualScoManager: Set HeadsetServiceHelper
,09-07 13:16:21.679  7563  7563 D BluetoothAtMessage: createCMTIContentObservers
,09-07 13:16:21.679  1014  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-07 13:16:21.679  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:21.679  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:21.679  1014  1027 D SettingsProvider: selectionArgs: false
09-07 13:16:21.679  1014  1027 D SettingsProvider: selectionArgs: 1002
09-07 13:16:21.679  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:21.679  1014  1027 D SettingsProvider: ret = -1
,09-07 13:16:21.679  7563  7587 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 13:16:21.679  7563  7563 D HeadsetService: mStartError = false
09-07 13:16:21.679  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.679  7563  7563 D A2dpService: Received start request. Starting profile...
09-07 13:16:21.679  7563  7563 D A2dpService: start()
,09-07 13:16:21.679  7563  7587 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-07 13:16:21.679  7563  7563 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 13:16:21.679  7563  7587 D HeadsetStateMachine: map size, before remove : 0
09-07 13:16:21.679  7563  7587 D HeadsetStateMachine: map size, after remove: 0
,09-07 13:16:21.679  7563  7563 I bluedroid: get_profile_interface avrcp
,09-07 13:16:21.689  7563  7563 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 13:16:21.689  7563  7563 D Avrcp   : Initialize Media Controller
,09-07 13:16:21.689  7563  7563 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 13:16:21.689  7563  7563 E Avrcp   : getActiveSessions
,09-07 13:16:21.689  7563  7563 D Avrcp   : pick active media Controller
,09-07 13:16:21.689  7563  7563 D Avrcp   : Get the active Media Controller 
,09-07 13:16:21.709  7563  7563 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 13:16:21.709  7563  7592 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 13:16:21.709  7563  7563 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:16:21.709  7563  7563 D A2dpStateMachine: make
,09-07 13:16:21.709  7563  7563 I bluedroid: get_profile_interface a2dp
09-07 13:16:21.709  7563  7594 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 13:16:21.709  7563  7563 E bt-btif : warning : media task started media_task_refcnt 1 
,09-07 13:16:21.719  7563  7563 D A2dpService: mStartError = false
09-07 13:16:21.719  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.719  7563  7593 D A2dpStateMachine: Enter Disconnected: -2
09-07 13:16:21.719  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-07 13:16:21.719  7563  7563 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 13:16:21.719  7563  7563 D HidService: Received start request. Starting profile...
09-07 13:16:21.719  7563  7563 D HidService: start()
09-07 13:16:21.719  7563  7563 I bluedroid: get_profile_interface hidhost
09-07 13:16:21.719  7563  7563 D HidService: setHidService(): set to: null
09-07 13:16:21.719  7563  7563 D HidService: mStartError = false
09-07 13:16:21.719  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.719  7563  7563 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 13:16:21.719  7563  7563 D HealthService: Received start request. Starting profile...
09-07 13:16:21.719  7563  7563 D HealthService: start()
,09-07 13:16:21.729  7563  7563 I bluedroid: get_profile_interface health
,09-07 13:16:21.729  7563  7563 D HealthService: mStartError = false
09-07 13:16:21.729  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.729  7563  7563 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 13:16:21.729  7563  7563 D PanService: Received start request. Starting profile...
09-07 13:16:21.729  7563  7563 D PanService: start()
09-07 13:16:21.729  7563  7563 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 13:16:21.729  7563  7563 I bluedroid: get_profile_interface pan
,09-07 13:16:21.729  7563  7563 D PanService: mStartError = false
09-07 13:16:21.729  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.729  7563  7563 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 13:16:21.729  1430  6968 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 13:16:21.729  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-07 13:16:21.729  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 13:16:21.729  1430  6968 I Telecom : BluetoothPhoneService: Result of Message : true
09-07 13:16:21.729  7563  7563 D HeadsetStateMachine: Proxy object connected
,09-07 13:16:21.729  7563  7592 D BluetoothMediaBrowser: no now playing list
,09-07 13:16:21.729  7563  7592 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-07 13:16:21.739  7563  7563 D BluetoothMapService: Received start request. Starting profile...
09-07 13:16:21.739  7563  7563 D BluetoothMapService: start()
,09-07 13:16:21.739  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:21.739  7563  7563 D BluetoothMapService: mStartError = false
,09-07 13:16:21.739  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:21.749  7563  7563 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-07 13:16:21.749  7563  7563 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-07 13:16:21.749  7563  7587 D HeadsetStateMachine: Disconnected process message: 11
09-07 13:16:21.749  7563  7563 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-07 13:16:21.749  7563  7563 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
09-07 13:16:21.749  7563  7587 D HeadsetStateMachine: Disconnected process message: 18
,09-07 13:16:21.749  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:21.749  7563  7563 D SapService: Received start request. Starting profile...
09-07 13:16:21.749  7563  7563 D SapService: start()
09-07 13:16:21.749  7563  7563 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 13:16:21.749  7563  7563 I bluedroid: get_profile_interface sap
09-07 13:16:21.749  7563  7563 D SapService: mStartError = false
09-07 13:16:21.749  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:21.749  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 13:16:21.749  7563  7563 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 13:16:21.749  7563  7563 D BluetoothA2dp: Proxy object connected
09-07 13:16:21.749  7563  7563 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-07 13:16:21.749  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 13:16:21.749  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-07 13:16:21.749  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 13:16:21.749  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 13:16:21.749  7563  7587 D HeadsetStateMachine: Disconnected process message: 10
,09-07 13:16:21.749  7563  7587 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 13:16:21.749  7563  7587 D HeadsetStateMachine: Disconnected process message: 11
,09-07 13:16:21.769  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-07 13:16:21.769  7563  7563 E BluetoothAdapterService(84524778): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 13:16:21.779  7563  7578 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-07 13:16:21.779  7563  7578 I bluedroid: enable
,09-07 13:16:21.779  7563  7578 I bt_hci_bdroid: init
09-07 13:16:21.779  7563  7598 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-07 13:16:21.779  7563  7578 I bt_vendor: bt-vendor : init
,09-07 13:16:21.779  7563  7578 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 13:16:21.779  7563  7578 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 13:16:21.779  7563  7578 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-07 13:16:21.779  7563  7578 D bt_userial_mct: userial_init
09-07 13:16:21.779  7563  7578 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 13:16:21.779  7563  7578 I bt_vendor: Starting hciattach daemon
09-07 13:16:21.779  7563  7578 I bt_vendor: try to set false
,09-07 13:16:21.779  7563  7578 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 13:16:21.779  7563  7578 I bt_vendor: Starting hciattach daemon
09-07 13:16:21.779  7563  7578 I bt_vendor: try to set true
,09-07 13:16:21.799  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-07 13:16:21.839  7608  7608 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-07 13:16:21.849  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 13:16:21.869  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 13:16:21.879  7612  7612 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-07 13:16:21.889  7613  7613 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 13:16:21.889  7614  7614 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-07 13:16:22.169  7617  7617 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-07 13:16:22.179  7618  7618 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 13:16:22.219  1014  3356 D SSRM:n  : SIOP:: AP = 320
,09-07 13:16:22.239  7563  7578 I bt_vendor: bluetooth satus is on
,09-07 13:16:22.239  7563  7600 D bt_userial_mct: userial_open(port:0)
,09-07 13:16:22.239  7563  7600 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 13:16:22.239  7563  7600 I bt_vendor: Done intiailizing UART
,09-07 13:16:22.249  7563  7600 I bt_vendor: Done intiailizing UART
,09-07 13:16:22.249  7563  7600 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,09-07 13:16:22.249  7563  7600 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-07 13:16:22.249  7563  7620 D bt_userial_mct: Entering userial_read_thread()
,09-07 13:16:22.249  7563  7598 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 13:16:22.249  7563  7598 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 13:16:22.249  7563  7598 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 13:16:22.249  7563  7598 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_SAP
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 13:16:22.259  7563  7598 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-07 13:16:22.359  7563  7598 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-07 13:16:22.359  7563  7598 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41e6ed1 
,09-07 13:16:22.359  7563  7598 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41e6ed1 
,09-07 13:16:22.379  7563  7581 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-07 13:16:22.379  7563  7581 E bt-btif : Calling BTA_HhEnable
,09-07 13:16:22.379  7563  7581 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 13:16:22.379  7563  7581 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 13:16:22.379  7563  7581 E BluetoothServiceJni: populateRssiValuesNative
,09-07 13:16:22.379  7563  7581 I bluedroid: getModelRssiValues
09-07 13:16:22.379  7563  7581 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 13:16:22.379  7563  7581 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 13:16:22.389  7563  7581 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
09-07 13:16:22.389  1014  1014 D SettingsProvider: name = bluetooth_name
,09-07 13:16:22.389  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:22.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
09-07 13:16:22.389  7563  7581 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 13:16:22.389  7563  7581 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:22.389  7563  7581 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:16:22.389  7563  7581 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-07 13:16:22.389  7563  7581 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1,
,09-07 13:16:22.389  7563  7581 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-07 13:16:22.389  7563  7581 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 13:16:22.389  7563  7581 E bt-btif : btif_sock_init: !vhci_init
09-07 13:16:22.399  7563  7581 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-07 13:16:22.399  7563  7581 D IOP_DB_BT: db_open: db_open : handle 3028348944l, read 13894 bytes onto local cache
09-07 13:16:22.399  7563  7581 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-07 13:16:22.399  7563  7581 D IOP_DB_BT: db_query: result 1
,09-07 13:16:22.399  7563  7581 I         : iop_db_open: iop_db_open status 0
09-07 13:16:22.399  7563  7581 D bte_conf: Device ID record 1 : primary
09-07 13:16:22.399  7563  7581 D bte_conf:   vendorId            = 0075
09-07 13:16:22.399  7563  7581 D bte_conf:   vendorIdSource      = 0001,
09-07 13:16:22.399  7563  7581 D bte_conf:   product             = 0100
09-07 13:16:22.399  7563  7581 D bte_conf:   version             = 0200
09-07 13:16:22.399  7563  7581 D bte_conf:   clientExecutableURL = 
09-07 13:16:22.399  7563  7581 D bte_conf:   serviceDescription  = 
09-07 13:16:22.399  7563  7581 D bte_conf:   documentationURL    = ,
09-07 13:16:22.399  7563  7581 D bte_conf: bte_load_did_conf no section named DID2.
09-07 13:16:22.399  7563  7581 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 13:16:22.399  7563  7620 E bt_mct  : hci lib postload completed
,09-07 13:16:22.399  7563  7578 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-07 13:16:22.399  7563  7578 D BluetoothAdapterProperties: ScanMode =  20
,09-07 13:16:22.399  7563  7578 D BluetoothAdapterProperties: State =  11
,09-07 13:16:22.399  1014  1429 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 13:16:22.409  7563  7578 D BluetoothAdapterProperties: Setting state to 12,
09-07 13:16:22.409  7563  7578 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 13:16:22.409  7563  7581 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 13:16:22.409  7563  7581 D BluetoothAdapterProperties: Scan Mode:21
,09-07 13:16:22.409  7563  7581 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:22.409  1014  1330 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-07 13:16:22.409  1014  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 13:16:22.409  1014  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:22.409  1014  1330 D SettingsProvider: selectionArgs: false
09-07 13:16:22.409  1014  1330 D SettingsProvider: selectionArgs: 1002
09-07 13:16:22.409  1014  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:22.409  1014  1330 D SettingsProvider: ret = -1
,09-07 13:16:22.409  7563  7578 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 13:16:22.409  7563  7578 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 13:16:22.409  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 13:16:22.409  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.419  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.419  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.419  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.419  7563  7578 D BluetoothAdapterService: Autoconnection is available 
09-07 13:16:22.419  7563  7578 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 13:16:22.419  7563  7578 D BluetoothAdapterService: starting service from this receiver
,09-07 13:16:22.419  1014  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:22.419  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 13:16:22.419  7563  7588 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 13:16:22.419  7563  7588 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 13:16:22.419  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:22.419  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 13:16:22.429  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.429  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.429  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:22.429  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:22.429  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 13:16:22.429  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.429  7563  7578 I BluetoothAdapterState: Entering On State from state = 11
,09-07 13:16:22.429  1014  1014 D BluetoothA2dp: Proxy object connected
,09-07 13:16:22.429  3063  7528 D BluetoothPan: Binding service...
,09-07 13:16:22.439  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:22.449  7563  7563 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 13:16:22.599  1014  1044 I art     : Explicit concurrent mark sweep GC freed 21839(1269KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.457ms total 159.366ms
,09-07 13:16:22.599  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 13:16:22.599  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.599  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.599  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.599  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.599  1441  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.599  1441  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.599  1174  4448 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 13:16:22.599  1174  4448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.599  1430  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.599  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:22.599  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.599  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.599  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.599  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.599  1430  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.609  1975  2156 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 13:16:22.609  1975  2156 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.609  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.609  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 13:16:22.609  1452  1957 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.609  1452  1957 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
,09-07 13:16:22.609  7563  7563 I BluetoothPbapService: Handler(): got msg=1
09-07 13:16:22.609  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-07 13:16:22.609  3063  3072 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 13:16:22.609  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-07 13:16:22.609  1014  1429 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-07 13:16:22.609  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.609  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.609  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.609  3063  3071 D Bluetoothsap: onBluetoothStateChange: up=true
,09-07 13:16:22.609  3063  3071 D Bluetoothsap: Binding service...
,09-07 13:16:22.609  3063  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 13:16:22.609  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 13:16:22.609  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.619  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.619  3063  3071 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 13:16:22.619  3063  3063 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 13:16:22.619  3063  3063 D PanProfile: Bluetooth service connected
,09-07 13:16:22.619  3063  7528 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.619  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:22.619  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.619  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-07 13:16:22.619  7563  7624 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 13:16:22.619  3063  7528 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.619  3063  3063 D BluetoothInputDevice: Proxy object connected
09-07 13:16:22.619  3063  3063 D HidProfile: Bluetooth service connected
,09-07 13:16:22.619  1430  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.619  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:22.619  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.619  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.619  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.619  1430  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.619  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 13:16:22.619  3063  3063 D SapProfile: Bluetooth service connected
09-07 13:16:22.619  3063  3063 D Bluetoothsap: getConnectedDevices()
,09-07 13:16:22.629  3063  7528 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 13:16:22.629  7563  7624 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:22.629  3063  3063 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:22.629  7563  7624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:16:22.629  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-07 13:16:22.629  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.629  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.629  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.629  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.629  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 13:16:22.629  7563  7624 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,09-07 13:16:22.629  7563  7624 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:22.629  7563  7624 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:22.629  7563  7624 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@def46b4
09-07 13:16:22.629  7563  7624 D BluetoothSocket: channel: 19
09-07 13:16:22.629  7563  7624 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 13:16:22.629  3063  3063 D BluetoothMap: Proxy object connected
,09-07 13:16:22.629  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-07 13:16:22.629  3063  3063 D MapProfile: Bluetooth service connected
09-07 13:16:22.629  3063  3063 D BluetoothMap: getConnectedDevices()
,09-07 13:16:22.629  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.629  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.629  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.629  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.639  1014  1044 D BluetoothPan: Binding service...
,09-07 13:16:22.639  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-07 13:16:22.639  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.639  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:22.639  1430  6968 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.639  1430  6968 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.639  3063  3063 D BluetoothPbap: Proxy object connected
09-07 13:16:22.639  3063  3063 D PbapServerProfile: Bluetooth service connected
,09-07 13:16:22.639  1452  1869 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.639  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 13:16:22.639  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.639  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.649  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.649  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.649  1452  1869 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.649  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.649  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 13:16:22.649  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.649  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.649  6777  6785 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 13:16:22.649  6777  6785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.649  7563  7571 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:16:22.649  3063  7528 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.649  3063  7528 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.649  7471  7479 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 13:16:22.649  7471  7479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 13:16:22.649  3063  3071 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:22.649  3063  3071 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.659  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 13:16:22.659  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.659  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.659  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.659  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.659  3063  3063 D BluetoothA2dp: Proxy object connected
,09-07 13:16:22.659  1430  1447 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 13:16:22.659  3063  3063 D A2dpProfile: Bluetooth service connected
09-07 13:16:22.659  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 13:16:22.659  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 13:16:22.659  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.659  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.659  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.659  1430  1447 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 13:16:22.659  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 13:16:22.659  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 13:16:22.659  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:22.659  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-07 13:16:22.659  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 13:16:22.669  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2105ba69, true
,09-07 13:16:22.669  1430  1430 D BluetoothHeadset: registerMessageListener
,09-07 13:16:22.669  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-07 13:16:22.669  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 13:16:22.669  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:22.669  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:22.679  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:22.679  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-07 13:16:22.679  1174  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 13:16:22.679  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 13:16:22.679  1014  1438 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 13:16:22.679  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:22.689  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 13:16:22.689  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:22.689  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 13:16:22.689  1014  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 13:16:22.689  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.689  7563  7572 D HeadsetService: registerMessageListener
,09-07 13:16:22.699  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.699  7563  7572 D HeadsetService: registerMessageListener
09-07 13:16:22.699  7563  7587 D HeadsetStateMachine: Disconnected process message: 70
,09-07 13:16:22.699  7563  7587 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@39a422dd
09-07 13:16:22.699  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-07 13:16:22.699  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 13:16:22.699  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:22.699  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:22.699  7563  7625 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 13:16:22.699  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-07 13:16:22.699  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-07 13:16:22.699  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 13:16:22.699  3063  3063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-07 13:16:22.709  3063  3063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 13:16:22.709  3063  3063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 13:16:22.709  3063  3063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 13:16:22.709  7563  7587 D HeadsetStateMachine: Disconnected process message: 9
,09-07 13:16:22.709  7563  7587 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 13:16:22.709  7563  7625 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:22.709  7563  7625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:22.719   282   699 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-07 13:16:22.719   282   699 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 13:16:22.719   282   699 V voice   : voice_set_parameters: exit with code(-2)
09-07 13:16:22.719   282   699 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-07 13:16:22.719   282   699 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 13:16:22.719   282   699 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 13:16:22.719   282   699 V audio_hw_primary: adev_set_parameters: exit
,09-07 13:16:22.719  7563  7587 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 13:16:22.719  7563  7625 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-07 13:16:22.719  7563  7625 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:22.719  7563  7625 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:22.719  7563  7625 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21705e52
09-07 13:16:22.719  7563  7625 D BluetoothSocket: channel: 5
,09-07 13:16:22.719  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:22.719  1014  1438 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 13:16:22.719  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.719  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.719  1014  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.719  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 13:16:22.729  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:22.739  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 13:16:22.739  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:22.739  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 13:16:22.749  7563  7563 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
,09-07 13:16:22.749  7563  7563 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 13:16:22.749  1014  1436 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 13:16:22.749  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.749  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.749  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:22.749  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 13:16:22.769  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:22.769  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:22.769  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 13:16:22.769  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.769  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:22.779  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:22.779  1014  1436 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 13:16:22.789  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 13:16:22.789  1975  7633 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 13:16:22.789  1014  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:22.799  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:22.799  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:22.799  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:22.799  7563  7635 D BluetoothSocket: bindListen(): myUserId = 0
09-07 13:16:22.799  7563  7635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:22.809  7563  7635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-07 13:16:22.809  7563  7635 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 13:16:22.809  7563  7635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 13:16:22.809  7563  7635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf0b84c
,09-07 13:16:22.809  7563  7635 D BluetoothSocket: channel: 12
09-07 13:16:22.809  7563  7635 I BtOppRfcommListener: Accept thread started.
,09-07 13:16:22.809  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 13:16:22.809  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:22.809  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 13:16:22.809  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 13:16:22.819  1975  7633 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-07 13:16:22.949  1014  2056 V SAMP_SPCM_test: CSC File load.. 
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,09-07 13:16:22.969  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-07 13:16:22.979  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-07 13:16:23.019  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-07 13:16:23.029  1014  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-07 13:16:23.039  1014  2056 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-07 13:16:23.039  1014  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:23.039  1014  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:23.039  1014  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:23.039  1014  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:23.059  7636  7636 E Zygote  : MountEmulatedStorage()
09-07 13:16:23.059  7636  7636 E Zygote  : v2
09-07 13:16:23.059  7636  7636 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:23.059  7636  7636 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:23.059  7636  7636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:23.059  7636  7636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:23.059  1014  2056 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7636 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 13:16:23.059  7636  7636 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:23.089  7636  7636 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:23.089  7636  7636 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:23.099  7636  7636 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:16:23.139  1014  2056 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:23.359  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:23.359  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:23.359  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:23.359  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2158d252 added. We now have 8 listener(s)
,09-07 13:16:23.359  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:23.369  1014  1438 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 13:16:23.369  1014  1438 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-07 13:16:23.369  1014  1438 D SecContentProvider2: mCursor = null
,09-07 13:16:23.369  1014  1438 D WifiService: setWifiEnabled: false pid=6777, uid=10171
,09-07 13:16:23.369  1014  1438 D SettingsProvider: name = wifi_on
09-07 13:16:23.369  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:23.379  1014  1476 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 13:16:23.379  1014  1476 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
09-07 13:16:23.379  1014  1476 D SecContentProvider2: mCursor = null
,09-07 13:16:23.379  1014  1476 D WifiService: setWifiEnabled: true pid=6777, uid=10171
09-07 13:16:23.379  1014  1476 W WifiService: Failed getting userId using ActivityManagerNative
09-07 13:16:23.379  1014  1476 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
09-07 13:16:23.379  1014  1476 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 13:16:23.379  1014  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 13:16:23.379  1014  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 13:16:23.379  1014  1476 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
,09-07 13:16:23.379  1014  1476 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 13:16:23.379  1014  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=6777, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-07 13:16:23.379  1014  1476 D SettingsProvider: name = wifi_on
,09-07 13:16:23.389  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
09-07 13:16:23.389   290   290 E SMD     : DCD OFF
,09-07 13:16:23.389   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 13:16:23.729  1014  1042 D Tethering: interfaceAdded wlan0
,09-07 13:16:23.739  1014  1128 E Tethering: No numeric data,
09-07 13:16:23.739  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 13:16:23.739  1014  1128 D Tethering: clearTetheredNotification()
,09-07 13:16:23.739  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:23.739  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:23.739  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:23.739  1174  1174 D HotspotTile: updateTetherState():false, false
,09-07 13:16:23.739  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 13:16:23.739  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:23.749  1014  1122 V NetworkStats: performPollLocked() took 7ms
,09-07 13:16:23.749  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:23.749  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:23.749  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:23.749  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:23.749  1014  1128 D Tethering: InitialState.processMessage what=4
,09-07 13:16:23.749  1014  1128 E Tethering: No numeric data
,09-07 13:16:23.759  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 13:16:23.759  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,09-07 13:16:23.759  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:23.759  1174  1174 D HotspotTile: updateTetherState():false, false
09-07 13:16:23.759  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-07 13:16:23.759  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:23.759  1014  1128 D Tethering: clearTetheredNotification()
09-07 13:16:23.759  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 13:16:23.759  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:23.759  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:23.759  1014  1042 D Tethering: interfaceAdded p2p0,
09-07 13:16:23.759  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 13:16:23.769  1014  1122 V NetworkStats: performPollLocked() took 9ms
,09-07 13:16:23.769  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:23.769  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:23.769  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 13:16:23.769  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 13:16:23.769  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
09-07 13:16:23.769  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:23.779   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-07 13:16:23.779   277   996 D SoftapController: Softap fwReload - Ok
,09-07 13:16:23.779   277   996 D CommandListener: Setting iface cfg,
,09-07 13:16:23.779   277   996 D CommandListener: Trying to bring down wlan0
,09-07 13:16:23.779   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:23.789  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant,
,09-07 13:16:23.789  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 13:16:23.789  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-07 13:16:23.799  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:23.799  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 13:16:23.799  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:23.799  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:23.799  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:23.799  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-07 13:16:23.799  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-07 13:16:23.799  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 13:16:23.799  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:23.799  1174  1174 D HotspotTile: onReceive : 2, 0
,09-07 13:16:23.809  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 13:16:23.809  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:23.819  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:23.819  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:23.819  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:23.819  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-07 13:16:23.819  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:23.819  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:23.819  1624  1624 I Hs20UtilService: Starting #19
,09-07 13:16:23.819  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:23.829  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 13:16:23.829  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:23.829  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:23.829  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:23.839  7664  7664 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-07 13:16:23.839  7664  7664 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 13:16:23.839  7664  7664 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 13:16:23.849  7664  7664 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-07 13:16:23.859   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7664
09-07 13:16:23.859   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-07 13:16:23.859  7664  7664 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 13:16:23.859  7664  7664 I wpa_supplicant: ssSupport state is = 1
09-07 13:16:23.859  7664  7664 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 13:16:23.859  7664  7664 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 13:16:23.859   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7664
09-07 13:16:23.859   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-07 13:16:24.009   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-07 13:16:24.009  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-07 13:16:24.059  7664  7664 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-07 13:16:24.059  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 13:16:24.069  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-07 13:16:24.069   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7664
09-07 13:16:24.069   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 13:16:24.069  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 13:16:24.069  7664  7664 I wpa_supplicant: ssSupport state is = 1
09-07 13:16:24.069  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,09-07 13:16:24.069  7664  7664 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:24.069  7664  7664 E wpa_supplicant: SIM READ ERROR
09-07 13:16:24.069  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:24.069  7664  7664 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:24.069  7664  7664 E wpa_supplicant: SIM READ ERROR
09-07 13:16:24.069  7664  7664 I wpa_supplicant: Blacklist: Clear (all) 
09-07 13:16:24.069  7664  7664 I wpa_supplicant: wpa_default_ap_write_once
09-07 13:16:24.069  7664  7664 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 13:16:24.069  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:24.069  7664  7664 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 13:16:24.069  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:24.069  7664  7664 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:24.069  7664  7664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 13:16:24.079  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:24.079  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:24.079  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 13:16:24.159  7664  7664 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-07 13:16:24.339  7664  7664 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-07 13:16:24.339  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 13:16:24.349  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 13:16:24.349   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7664,
09-07 13:16:24.349   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-07 13:16:24.349  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 13:16:24.349  7664  7664 I wpa_supplicant: ssSupport state is = 1
,09-07 13:16:24.349  7664  7664 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 13:16:24.349  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 13:16:24.369  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 13:16:24.369   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7664
09-07 13:16:24.369   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 13:16:24.369  7664  7664 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 13:16:24.369  7664  7664 I wpa_supplicant: ssSupport state is = 1
09-07 13:16:24.369  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-07 13:16:24.369  7664  7664 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:24.369  7664  7664 E wpa_supplicant: SIM READ ERROR
09-07 13:16:24.369  7664  7664 I wpa_supplicant: wpa_default_ap_write_once
09-07 13:16:24.369  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-07 13:16:24.369  7664  7664 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 13:16:24.369  7664  7664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 13:16:24.369  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 13:16:24.369  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:24.369  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 13:16:24.369  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 13:16:24.369  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:24.389   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-07 13:16:24.419  7664  7664 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-07 13:16:24.419  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 13:16:24.479  7664  7664 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-07 13:16:24.479  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-07 13:16:24.479  7664  7664 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 13:16:24.749  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 13:16:24.749  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-07 13:16:24.749  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 13:16:24.799  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-07 13:16:24.799  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-07 13:16:24.799  7664  7664 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-07 13:16:24.799  7664  7664 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 13:16:24.799  7664  7664 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 13:16:24.799  7664  7664 E wpa_supplicant: SIM READ ERROR
09-07 13:16:24.799  7664  7664 I wpa_supplicant: Blacklist: Clear (all) ,
,09-07 13:16:24.819  7664  7664 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 13:16:24.829  7664  7664 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 13:16:24.829  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-07 13:16:24.839  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 13:16:24.839  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-07 13:16:24.839  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:24.839  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 13:16:24.839  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:24.839  1174  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-07 13:16:24.839  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:24.839  1174  1174 D HotspotTile: onReceive : 3, 0
09-07 13:16:24.839  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:24.839  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:24.839  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 13:16:24.839  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 13:16:24.839  1014  1125 E WifiConfigStore: Not a HS20
,09-07 13:16:24.849  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:24.849  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:24.849  1014  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:24.849  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:24.849  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-07 13:16:24.849  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:24.849  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:24.849  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 13:16:24.849  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65],
09-07 13:16:24.849  1624  1624 I Hs20UtilService: Starting #20
09-07 13:16:24.849  1624  1651 I Hs20UtilService: Message received 5011
,09-07 13:16:24.859  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 13:16:24.859  7664  7664 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 13:16:24.859  7664  7664 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 13:16:24.859  7664  7664 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 13:16:24.859  7664  7664 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 13:16:24.859  7664  7664 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 13:16:24.859  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 13:16:24.859  7664  7664 I wpa_supplicant: First Scan Start
,09-07 13:16:24.859  7664  7664 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 13:16:24.859  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-07 13:16:24.859  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 13:16:24.859  1014  1125 I WifiNative-HAL: startHal
09-07 13:16:24.859  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d5bf88c
09-07 13:16:24.859  1014  1125 I WifiNative-HAL: Could not start hal
09-07 13:16:24.859  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 13:16:24.859  6578  6578 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 13:16:24.859  6578  6578 D SecurityLogAgent: StateMachine : Current State = 1
09-07 13:16:24.859  6578  6578 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 13:16:24.859  7028  7028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:24.869  1014  1125 E WifiNative-wlan0: do suspend true
,09-07 13:16:24.869  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-07 13:16:24.869  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-07 13:16:24.869  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 13:16:24.869   277   996 D CommandListener: Setting iface cfg
09-07 13:16:24.869   277   996 D CommandListener: Trying to bring up p2p0
,09-07 13:16:24.869  1014  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:24.869  1014  1147 I WifiNative-HAL: startHal
09-07 13:16:24.869  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e6679bc
09-07 13:16:24.869  1014  1147 I WifiNative-HAL: Could not start hal
09-07 13:16:24.869  1014  1147 E WifiScanningService: could not start HAL
09-07 13:16:24.869  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 13:16:24.869  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 13:16:24.869  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-07 13:16:24.869  1014  1014 D RttService: SCAN_AVAILABLE : 3
,09-07 13:16:24.869  1014  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:24.869  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 13:16:24.869  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 13:16:24.869  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-07 13:16:24.869  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 13:16:24.879  7664  7664 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 13:16:24.879  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 13:16:24.879  1014  1124 D WifiP2pService: P2pEnablingState
09-07 13:16:24.879  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-07 13:16:24.879  1014  1124 D WifiP2pService: P2p socket connection successful
09-07 13:16:24.879  1014  1124 D WifiP2pService: P2pEnabledState
,09-07 13:16:24.879  1014  1127 E ConnectivityService: updateNetworkInfo(),
09-07 13:16:24.879  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 13:16:24.879  7664  7664 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 13:16:24.879  1014  1125 E WifiStateMachine: Failed to set frequency band 0
09-07 13:16:24.879  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:24.879  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 13:16:24.879  1014  1125 D SecContentProvider2: mCursor = null
09-07 13:16:24.879  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:24.879  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 13:16:24.879  1014  1045 D WifiDisplayController: disconnect
09-07 13:16:24.879  1014  1045 D WifiDisplayController: updateConnection
09-07 13:16:24.879  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 13:16:24.879  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 13:16:24.879  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:24.879  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:24.889  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-07 13:16:24.889  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 13:16:24.889  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-07 13:16:24.889  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 13:16:24.889  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-07 13:16:24.889  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 13:16:24.889  1014  1496 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 13:16:24.889  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 13:16:24.889  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-07 13:16:24.889  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-07 13:16:24.889  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:24.899  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 13:16:24.899  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,09-07 13:16:24.899  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 13:16:24.899  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  secondary type: null
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  wps: 0
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  grpcapab: 0
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  devcapab: 0
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  status: 3
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  wfdInfo: null
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  groupownerAddress: null
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  GOdeviceName: null
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  interfaceAddress: 
09-07 13:16:24.899  1014  1045 D WifiDisplayController:  SConnectInfo : null
,09-07 13:16:24.899  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-07 13:16:24.899  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:24.899  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:24.899  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:24.909  7051  7051 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 13:16:24.909  7051  7051 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 13:16:24.909  7066  7066 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 13:16:24.919  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 13:16:24.919  1014  1124 D WifiP2pService: InactiveState
,09-07 13:16:24.919  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-07 13:16:24.919  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 13:16:24.919  7664  7664 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-07 13:16:24.919  1014  1124 D WifiP2pService: InactiveState{ what=143376 },
,09-07 13:16:24.929  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:25.399  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:25.399  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:25.409  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 13:16:25.409  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 13:16:25.409  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fd29fa8 Bundle[{}]
,09-07 13:16:25.409  6777  6833 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 13:16:25.409  6777  6833 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 13:16:25.419  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 13:16:25.419  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 13:16:25.419  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 13:16:25.419  6777  6833 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 13:16:25.419  6777  6833 I System.out: Running OutgoingSocketThread
,09-07 13:16:25.429  6777  7671 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1345)
,09-07 13:16:25.429  6777  7671 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58619
,09-07 13:16:25.429  6777  7671 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 13:16:26.109  7664  7664 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
09-07 13:16:26.109  7664  7664 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 13:16:26.109  7664  7664 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-07 13:16:26.109  7664  7664 I wpa_supplicant: Trying to associate with  'G700'
09-07 13:16:26.109  7664  7664 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 13:16:26.109  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 13:16:26.109  1014  7669 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 13:16:26.129  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:26.129  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:26.239  7664  7664 E wpa_supplicant: Cmd 35605 not handled
,09-07 13:16:26.239  7664  7664 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:26.239  7664  7664 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-07 13:16:26.239  7664  7664 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-07 13:16:26.239  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 13:16:26.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  7664  7664 I wpa_supplicant: Associated with F4.99.3E
09-07 13:16:26.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:26.239  7664  7664 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:26.239  7664  7664 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 13:16:26.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-07 13:16:26.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:26.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 13:16:26.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 13:16:26.239  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 13:16:26.239  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 13:16:26.239  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-07 13:16:26.249  1014  1128 E Tethering: No numeric data
09-07 13:16:26.249  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 13:16:26.249  1014  1128 D Tethering: clearTetheredNotification()
,09-07 13:16:26.249  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:26.249  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-07 13:16:26.249  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:26.249  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:26.249  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:26.249  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:26.259  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 13:16:26.259  1174  1174 D HotspotTile: updateTetherState():false, false
,09-07 13:16:26.259  1014  1122 V NetworkStats: performPollLocked() took 9ms
09-07 13:16:26.259  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:26.259  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 13:16:26.259  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:26.259  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:26.259  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:26.269  7664  7664 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 13:16:26.269  7664  7664 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-07 13:16:26.269  7664  7664 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-07 13:16:26.269  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-07 13:16:26.269  7664  7664 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 13:16:26.269  7664  7664 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 13:16:26.269  7664  7664 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-07 13:16:26.279  7664  7664 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 13:16:26.279  7664  7664 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-07 13:16:26.279  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 13:16:26.279  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 13:16:26.279  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-07 13:16:26.279  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 13:16:26.279  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
09-07 13:16:26.289  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 13:16:26.289  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-07 13:16:26.289  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:26.289  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:26.289  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:26.289  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:26.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:26.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 13:16:26.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:26.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:26.299  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:26.299  1014  1436 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 13:16:26.299  1014  1436 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 13:16:26.299  1014  1436 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:26.299  1014  1436 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:26.299  1014  1436 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:26.299  1624  1624 I Hs20UtilService: Starting #21
09-07 13:16:26.309  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:26.309  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,09-07 13:16:26.309  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 13:16:26.309  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:26.309  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 13:16:26.309  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:26.309  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 13:16:26.319  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 13:16:26.319  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:26.329   277   996 D CommandListener: Setting iface cfg
,09-07 13:16:26.339  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,09-07 13:16:26.339  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:26.339  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:26.349  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 13:16:26.349  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 13:16:26.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:26.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:26.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:26.349  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:26.359  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 13:16:26.359  1014  1125 D SecContentProvider2: mCursor = null
,09-07 13:16:26.359  1014  1125 E WifiNative-wlan0: do suspend false
,09-07 13:16:26.359  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-07 13:16:26.359  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 13:16:26.389   290   290 E SMD     : DCD OFF,
,09-07 13:16:26.429  6777  6833 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1346)
,09-07 13:16:26.429  6777  6833 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1346)
,09-07 13:16:26.429  6777  6833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,09-07 13:16:26.429  6777  6833 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 13:16:26.429  6777  6833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1352)
,09-07 13:16:26.439  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 13:16:26.439  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52b923 added. We now have 2 listener(s)
,09-07 13:16:26.439  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 13:16:26.439  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 13:16:26.439  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 13:16:26.439  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:26.449  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb3ae20 added. We now have 9 listener(s)
,09-07 13:16:26.449  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:26.449  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:26.449  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:26.459  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:26.459  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:26.459  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:26.459  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.459  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-07 13:16:26.459  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78dc19e added. We now have 3 listener(s)
09-07 13:16:26.459  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68dc47f added. We now have 10 listener(s)
,09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.469  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:26.469  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:26.469  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.469  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52b923 removed from the list
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb3ae20 removed from the list
09-07 13:16:26.469  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.469  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.469  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb3ae20 not in the list
09-07 13:16:26.469  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68dc47f removed from the list
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.469  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.469  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.469  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78dc19e removed from the list
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.469  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35758c4c added. We now have 2 listener(s)
,09-07 13:16:26.479  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.479  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-07 13:16:26.479  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.479  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.479  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22941495 added. We now have 9 listener(s)
09-07 13:16:26.479  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.479  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:26.479  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:26.489  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:26.489  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:26.489  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:26.489  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.489  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744299b added. We now have 3 listener(s)
,09-07 13:16:26.489  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.489  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.499  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 13:16:26.499  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 13:16:26.499  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.499  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:26.499  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25952138 added. We now have 10 listener(s)
09-07 13:16:26.499  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.499  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:26.499  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-07 13:16:26.499  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:26.499  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:26.499  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:26.499  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 13:16:26.509  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:16:26.509  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:16:26.509  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 13:16:26.509  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 13:16:26.509  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:26.519  7563  7572 D BtGatt.GattService: registerClient() - UUID=ea720f98-d105-4cfd-b2a3-12a94d9c7cf9
,09-07 13:16:26.559  7563  7581 D BtGatt.GattService: onClientRegistered() - UUID=ea720f98-d105-4cfd-b2a3-12a94d9c7cf9, clientIf=6
,09-07 13:16:26.559  6777  6791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
09-07 13:16:26.559  7563  7588 D BtGatt.GattService: start scan with filters
,09-07 13:16:26.559  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-07 13:16:26.559  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 13:16:26.559  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-07 13:16:26.559  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:26.559  7563  7586 D BtGatt.ScanManager: handling starting scan
09-07 13:16:26.569  7563  7586 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509beea
09-07 13:16:26.569  7563  7581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 13:16:26.569  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.569  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 13:16:26.569  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 13:16:26.569  7563  7586 D BtGatt.ScanManager: allow scan with filters
09-07 13:16:26.569  7563  7586 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 13:16:26.569  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 13:16:26.569  7563  7586 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-07 13:16:26.579  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 13:16:26.579  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.579  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:26.579  7563  7586 D BtGatt.ScanManager: Starting BLE batch scan
09-07 13:16:26.579  7563  7586 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:26.589  7563  7581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 13:16:26.589  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.589  7676  7676 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-07 13:16:26.589  6777  6833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:26.589  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:26.589  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:26.589  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 13:16:26.589  7676  7676 I dhcpcd  : version 5.5.6 starting
09-07 13:16:26.589  7563  7571 D BtGatt.GattService: stopScan() - queue size =1,
09-07 13:16:26.589  7563  7572 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 13:16:26.589  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-07 13:16:26.589  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 13:16:26.589  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:26.589  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 13:16:26.599  7676  7676 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-07 13:16:26.599  7563  7586 D BtGatt.ScanManager: filter size is 1
09-07 13:16:26.599  7563  7586 D BtGatt.ScanManager: delete FilterIndex - 3
09-07 13:16:26.599  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:26.599  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:26.599  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:16:26.599  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:16:26.599  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:26.599  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:26.599  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:26.599  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:26.609  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 13:16:26.609  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.609  7563  7586 D BtGatt.ScanManager: stopping BLe Batch
09-07 13:16:26.609  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 13:16:26.609  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.619  7563  7586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 13:16:26.619  7563  7581 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-07 13:16:26.619  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.619  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:26.619  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:26.619  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.619  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35758c4c removed from the list
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22941495 removed from the list
09-07 13:16:26.619  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:26.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.619  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.619  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22941495 not in the list
09-07 13:16:26.619  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25952138 removed from the list
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.619  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.619  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.619  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.619  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@744299b removed from the list
09-07 13:16:26.629  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-07 13:16:26.629  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281718e4 added. We now have 2 listener(s)
,09-07 13:16:26.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 13:16:26.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.639  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc3414d added. We now have 9 listener(s)
09-07 13:16:26.639  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:26.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:26.639  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:26.639  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:26.649  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:26.649  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:16:26.649  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.649  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf43113 added. We now have 3 listener(s)
,09-07 13:16:26.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.649  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.649  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29edf50 added. We now have 10 listener(s)
09-07 13:16:26.649  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.649  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:26.649  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:26.649  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:26.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:26.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:26.649  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:26.649  7676  7676 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-07 13:16:26.649  7676  7676 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-07 13:16:26.649  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:26.659  7676  7676 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-07 13:16:26.659  7676  7676 I dhcpcd  : bssid match
09-07 13:16:26.659  7676  7676 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-07 13:16:26.659  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.659  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 13:16:26.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 13:16:26.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 13:16:26.659  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 13:16:26.659  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 13:16:26.659  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:26.669  7563  7572 D BtGatt.GattService: registerClient() - UUID=b9eb9e2a-3220-4a13-b6b5-3700ce000f22
,09-07 13:16:26.679  1014  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 13:16:26.679  1014  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 13:16:26.679  1014  1429 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 13:16:26.679  1014  1429 D BatteryService: stay LED for fully charged
,09-07 13:16:26.679  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 13:16:26.679  1014  1014 I MotionRecognitionService: Plugged
09-07 13:16:26.679  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 13:16:26.679  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 13:16:26.679  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 13:16:26.689  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 13:16:26.689  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 13:16:26.699  7563  7563 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-07 13:16:26.699  7563  7587 D HeadsetStateMachine: Disconnected process message: 10
,09-07 13:16:26.709  7563  7581 D BtGatt.GattService: onClientRegistered() - UUID=b9eb9e2a-3220-4a13-b6b5-3700ce000f22, clientIf=6
,09-07 13:16:26.709  6777  6785 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 13:16:26.709  7563  7571 D BtGatt.GattService: start scan with filters
,09-07 13:16:26.709  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 13:16:26.709  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-07 13:16:26.709  7563  7586 D BtGatt.ScanManager: handling starting scan
,09-07 13:16:26.709  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 13:16:26.709  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 13:16:26.709  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 13:16:26.709  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:26.709  7563  7581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 13:16:26.709  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.709  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 13:16:26.719  7563  7586 D BtGatt.ScanManager: allow scan with filters
09-07 13:16:26.719  7563  7586 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 13:16:26.719  7563  7586 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-07 13:16:26.719  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:26.719  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 13:16:26.719  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 13:16:26.719  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.719  7563  7586 D BtGatt.ScanManager: Starting BLE batch scan
09-07 13:16:26.719  7563  7586 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:26.719  7563  7581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 13:16:26.719  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.719  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:26.719  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:26.719  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 13:16:26.719  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.729  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 13:16:26.729  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:26.729  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 13:16:26.729  6777  6833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 13:16:26.729  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:26.729  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:26.729  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:26.729  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.729  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.729  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:26.729  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 13:16:26.729  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281718e4 removed from the list
09-07 13:16:26.729  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.729  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc3414d removed from the list
09-07 13:16:26.729  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:26.729  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:26.739  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 13:16:26.739  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.739  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc3414d not in the list
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 13:16:26.739  7563  7588 D BtGatt.GattService: stopScan() - queue size =1
09-07 13:16:26.739  7563  7586 D BtGatt.ScanManager: filter size is 1
09-07 13:16:26.739  7563  7586 D BtGatt.ScanManager: delete FilterIndex - 4
09-07 13:16:26.739  7563  7571 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 13:16:26.739  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 13:16:26.739  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.739  7563  7586 D BtGatt.ScanManager: stopping BLe Batch
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:26.739  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 13:16:26.739  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:26.749  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:26.749  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:16:26.749  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 13:16:26.749  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.749  7563  7586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 13:16:26.749  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.749  7563  7581 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 13:16:26.749  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.749  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 13:16:26.749  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:26.749  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:26.749  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29edf50 removed from the list
09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.749  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.749  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:26.749  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.749  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf43113 removed from the list
09-07 13:16:26.749  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.749  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9aa07c added. We now have 2 listener(s)
,09-07 13:16:26.759  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.759  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.759  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.759  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.759  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da44d05 added. We now have 9 listener(s)
09-07 13:16:26.759  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:26.759  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:26.759  7676  7676 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-07 13:16:26.759  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:26.759  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:26.759  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:26.759  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:26.759  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.759  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39beaf8b added. We now have 3 listener(s)
,09-07 13:16:26.769  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.769  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:26.769  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.769  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.769  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.769  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.769  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f4868 added. We now have 10 listener(s)
09-07 13:16:26.769  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.769  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:26.769  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:26.769  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:26.769  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:26.769  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:26.779  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 13:16:26.779  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 13:16:26.779  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 13:16:26.779  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 13:16:26.779  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 13:16:26.779  6777  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 13:16:26.789  7563  7572 D BtGatt.GattService: registerClient() - UUID=7687af5b-08e1-4b36-929d-e2c3f39f3740
,09-07 13:16:26.829  7563  7581 D BtGatt.GattService: onClientRegistered() - UUID=7687af5b-08e1-4b36-929d-e2c3f39f3740, clientIf=6
,09-07 13:16:26.829  6777  6791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 13:16:26.829  7563  7588 D BtGatt.GattService: start scan with filters
,09-07 13:16:26.829  7563  7586 D BtGatt.ScanManager: handling starting scan
,09-07 13:16:26.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 13:16:26.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 13:16:26.829  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 13:16:26.829  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 13:16:26.839  7563  7581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 13:16:26.839  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.839  7563  7586 D BtGatt.ScanManager: allow scan with filters
,09-07 13:16:26.839  7563  7586 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 13:16:26.839  7563  7586 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-07 13:16:26.839  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 13:16:26.839  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.839  7563  7586 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 13:16:26.839  7563  7586 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 13:16:26.849  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 13:16:26.849  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 13:16:26.849  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 13:16:26.849  7563  7581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 13:16:26.849  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.849  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 13:16:26.849  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 13:16:26.849  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.859  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:26.859  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:26.859  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:26.859  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:26.859  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 13:16:26.869  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9aa07c removed from the list
,09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.869  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da44d05 removed from the list
,09-07 13:16:26.869  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:26.869  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-07 13:16:26.869  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:26.869  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da44d05 not in the list
09-07 13:16:26.869  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 13:16:26.869  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 13:16:26.879  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 13:16:26.879  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-07 13:16:26.879  7563  7572 D BtGatt.GattService: stopScan() - queue size =1
,09-07 13:16:26.879  7563  7586 D BtGatt.ScanManager: filter size is 1
09-07 13:16:26.879  7563  7586 D BtGatt.ScanManager: delete FilterIndex - 5
,09-07 13:16:26.879  7563  7581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 13:16:26.879  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.879  7563  7588 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 13:16:26.879  7563  7586 D BtGatt.ScanManager: stopping BLe Batch
,09-07 13:16:26.879  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 13:16:26.879  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 13:16:26.879  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 13:16:26.879  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 13:16:26.879  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 13:16:26.889  7676  7676 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-07 13:16:26.889  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 13:16:26.889  7563  7581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 13:16:26.889  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 13:16:26.889  6777  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 13:16:26.889  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 13:16:26.889  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 13:16:26.889  7563  7586 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 13:16:26.899  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.899  7563  7581 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 13:16:26.899  7563  7581 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 13:16:26.899  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:26.899  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:26.899  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:26.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.899  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f4868 removed from the list
09-07 13:16:26.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.899  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.899  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.899  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.899  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39beaf8b removed from the list
,09-07 13:16:26.899  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.899  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e48314 added. We now have 2 listener(s)
,09-07 13:16:26.909  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.909  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:26.909  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.909  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.909  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b417bd added. We now have 9 listener(s)
,09-07 13:16:26.909  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.909  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:26.909  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:26.919  6777  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:26.929  6777  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-07 13:16:26.929  6777  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99b8503 added. We now have 3 listener(s)
09-07 13:16:26.929  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d10bc80 added. We now have 10 listener(s)
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:26.929  6777  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:26.929  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:26.929  6777  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:26.929  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.929  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e48314 removed from the list
09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.929  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b417bd removed from the list,
09-07 13:16:26.929  6777  6833 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.929  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.929  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:26.929  6777  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b417bd not in the list
09-07 13:16:26.929  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:26.929  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:26.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:26.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:26.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:26.939  6777  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d10bc80 removed from the list
09-07 13:16:26.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:26.939  6777  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:26.939  6777  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:26.939  6777  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:26.939  6777  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99b8503 removed from the list
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 13:16:26.939  6777  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:26.949  6777  7690 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1359, name: My test thread name)
09-07 13:16:26.949  6777  7690 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1359, thread name: My test thread name)
09-07 13:16:26.949  6777  7690 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1359, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 13:16:26.949  6777  7692 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1361, name: My test thread name)
,09-07 13:16:26.949  6777  7692 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1361, thread name: My test thread name),
09-07 13:16:26.949  6777  7692 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1361, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 13:16:26.959  6777  6833 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-07 13:16:26.959  6777  6833 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 13:16:26.959  6777  6833 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 13:16:26.959  6777  6833 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 13:16:26.959  6777  6833 D com.test.thalitest.ThaliTestRunner: Total duration: 24342 ms
,09-07 13:16:26.959  6777  6833 I jxcore-log: *Native tests were executed*
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: Total number of executed tests:  80,
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: Number of passed tests:  80
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: Number of failed tests:  0,
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: Number of ignored tests:  0
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: Total duration:  24342,
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.959  6777  6833 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 13:16:26.959  6777  6833 I jxcore-log: 
,09-07 13:16:26.959  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.959  6777  6833 I jxcore-log: 
09-07 13:16:26.969  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.969  6777  6833 I jxcore-log: 
09-07 13:16:26.969  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.969  6777  6833 I jxcore-log: 
09-07 13:16:26.969  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.969  6777  6833 I jxcore-log: 
09-07 13:16:26.969  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.969  6777  6833 I jxcore-log: 
09-07 13:16:26.969  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,09-07 13:16:26.969  6777  6833 I jxcore-log: 
,09-07 13:16:26.979  6777  6777 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 13:16:26.979  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 13:16:26.979  6777  6833 I jxcore-log: 
09-07 13:16:26.979  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 13:16:26.979  6777  6833 I jxcore-log: 
09-07 13:16:26.979  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.979  6777  6833 I jxcore-log: 
09-07 13:16:26.979  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.979  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
,09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.989  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.989  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.999  6777  6833 I jxcore-log: ,
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:26.999  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-07 13:16:26.999  6777  6833 I jxcore-log: 
,09-07 13:16:27.099  6777  6777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 13:16:27.109  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 13:16:27.109  6777  6833 I jxcore-log: 
,09-07 13:16:27.169  1014  1125 E WifiNative-wlan0: do suspend true,
,09-07 13:16:27.199  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-07 13:16:27.199  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 13:16:27.199  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:27.199  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-07 13:16:27.199  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.199  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.199  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.199  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.199  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 13:16:27.199  1014  1125 E WifiStateMachine: VerifyingLinkState enter
09-07 13:16:27.209  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-07 13:16:27.209  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-07 13:16:27.209  1014  1127 D ConnectivityService: Adding iface wlan0 to network 504
09-07 13:16:27.209  1014  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-07 13:16:27.209  1014  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 13:16:27.209  1014  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 13:16:27.219  1014  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 13:16:27.219  1014  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 13:16:27.219  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 13:16:27.219  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:27.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.219  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:27.219  1014  1095 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:27.219  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:27.219  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 13:16:27.219  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 13:16:27.219  1624  1624 I Hs20UtilService: Starting #22
,09-07 13:16:27.229  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:27.229  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:27.229  3063  3063 I NearbySettings: MountReceiver.onReceive - Keep current state
09-07 13:16:27.229  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-07 13:16:27.249  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 13:16:27.249  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
,09-07 13:16:27.249  6777  6777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-07 13:16:27.249  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-07 13:16:27.249  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 13:16:27.249  6777  6833 I jxcore-log: 
09-07 13:16:27.249  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504,
09-07 13:16:27.249  7700  7700 D AndroidRuntime: 
09-07 13:16:27.249  7700  7700 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 13:16:27.249  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0,
,09-07 13:16:27.249  1014  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-07 13:16:27.259  7700  7700 D AndroidRuntime: CheckJNI is OFF
09-07 13:16:27.249  1014  1127 D ConnectivityService: LTETest block dns file not exists
09-07 13:16:27.259  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:27.259  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 13:16:27.259  7700  7700 D AndroidRuntime: readGMSProperty: start
09-07 13:16:27.259  7700  7700 D AndroidRuntime: readGMSProperty: already setted!!
09-07 13:16:27.259  7700  7700 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 13:16:27.259  7700  7700 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 13:16:27.259  7700  7700 D AndroidRuntime: readGMSProperty: end
09-07 13:16:27.259  7700  7700 D AndroidRuntime: addProductProperty: start
,09-07 13:16:27.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.259  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 13:16:27.259  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-07 13:16:27.259  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
09-07 13:16:27.259  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 13:16:27.269  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 13:16:27.269  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.269  1014  1127 V NetworkStats: updateIfacesLocked()
09-07 13:16:27.269  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:27.279  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:27.279  1014  1330 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:27.279  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:27.279  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:27.279  1014  1127 V NetworkStats: performPollLocked() took 5ms
,09-07 13:16:27.279  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.279  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:27.279  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:27.279  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:27.279  1624  1624 I Hs20UtilService: Starting #23
09-07 13:16:27.279  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.279  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:27.279  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 13:16:27.279  1014  1127 E ConnectivityService: updateNetworkInfo()
09-07 13:16:27.279  1014  1127 V NetworkStats: updateIfacesLocked()
09-07 13:16:27.279  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.279  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:27.279  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.279  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.279  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:27.279  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 13:16:27.279  1624  1651 I Hs20UtilService: Message received 5007
,09-07 13:16:27.289  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:27.289  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 13:16:27.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.289  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:27.289  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 13:16:27.289  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 13:16:27.289  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.289  1014  1127 V NetworkStats: performPollLocked() took 7ms
09-07 13:16:27.289  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 13:16:27.289  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.289  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 13:16:27.289  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.289  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 13:16:27.289  3063  3906 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 13:16:27.289  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.289  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.289  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:27.289  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-07 13:16:27.289  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 13:16:27.289  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-07 13:16:27.289  1014  7672 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 13:16:27.289   277   992 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 13:16:27.289   277   992 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-07 13:16:27.299  1014  1127 D ConnectivityService:    accepting network in place of null
09-07 13:16:27.299  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 13:16:27.299  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 13:16:27.299  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 13:16:27.299  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 13:16:27.299  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 13:16:27.299  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-07 13:16:27.299  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-07 13:16:27.299  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-07 13:16:27.299  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-07 13:16:27.299  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-07 13:16:27.299  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:27.299  1014  1122 V NetworkStats: updateIfacesLocked()
09-07 13:16:27.299  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-07 13:16:27.309  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:27.309  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:27.309  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.309  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-07 13:16:27.309  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 13:16:27.309  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 13:16:27.309  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-07 13:16:27.309  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-07 13:16:27.309  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-07 13:16:27.309  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-07 13:16:27.309  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.309  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.309  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 13:16:27.309  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.309  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 13:16:27.309  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.309  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:27.309  1174  1673 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 13:16:27.319  4802  6843 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 13:16:27.319  1014  1330 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 13:16:27.319  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 13:16:27.319  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:27.319  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:27.319  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 13:16:27.319  1624  1624 I Hs20UtilService: Starting #24
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-07 13:16:27.319  1624  1651 I Hs20UtilService: Message received 5007
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:27.319  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.319  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 13:16:27.319  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.319  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.319  3063  3063 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-07 13:16:27.329  1014  1476 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,09-07 13:16:27.329  1014  1330 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-07 13:16:27.329  1014  1330 D SecContentProvider2: mCursor = null
,09-07 13:16:27.329  1014  1429 D SecContentProvider2: uri = 15 selection = getToastGravity
09-07 13:16:27.329  1014  1429 D SecContentProvider2: mCursor = null
,09-07 13:16:27.329  1014  1480 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-07 13:16:27.329  1014  1480 D SecContentProvider2: mCursor = null
,09-07 13:16:27.339  1014  1095 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-07 13:16:27.339  1014  1095 D SecContentProvider2: mCursor = null
,09-07 13:16:27.339  1014  1436 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-07 13:16:27.339  1014  1436 D SecContentProvider2: mCursor = null,
,09-07 13:16:27.339  1014  1438 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-07 13:16:27.339  1014  1438 D SecContentProvider2: mCursor = null
,09-07 13:16:27.369   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,09-07 13:16:27.379  1014  1480 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014,
,09-07 13:16:27.389  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-07 13:16:27.399  6777  6777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 13:16:27.399  6777  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 13:16:27.399  6777  6833 I jxcore-log: 
,09-07 13:16:27.409  7700  7700 E AffinityControl: AffinityControl: registerfunction enter
,09-07 13:16:27.419  1014  7672 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-07 13:16:27.439  7700  7700 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 13:16:27.449  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-07 13:16:27.449  1014  1027 D PackageManager: START PACKAGE DELETE: observer{861796060}
09-07 13:16:27.449  1014  1027 D PackageManager: pkg{<packageName>}
09-07 13:16:27.449  1014  1027 D PackageManager: user{0}
09-07 13:16:27.449  1014  1027 D PackageManager: caller{2000}
09-07 13:16:27.449  1014  1027 D PackageManager: flags{2}
09-07 13:16:27.449  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-07 13:16:27.449  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-07 13:16:27.449  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 13:16:27.449  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,09-07 13:16:27.459  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
09-07 13:16:27.459  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-07 13:16:27.459  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-07 13:16:27.459  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-07 13:16:27.459  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-07 13:16:27.459  1014  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-07 13:16:27.469  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-07 13:16:27.469  1014  1040 I ActivityManager: Killing 6777:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-07 13:16:27.479  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 11:16:27 GMT], X-Android-Received-Millis=[1473246987484], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473246987457]}
09-07 13:16:27.479  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 13:16:27.479  1014  7672 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-07 13:16:27.479  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.479  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-07 13:16:27.479  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-07 13:16:27.479  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-07 13:16:27.479  1174  1673 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 13:16:27.479  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 13:16:27.479  4802  6843 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 13:16:27.559  1014  1054 W PackageSettings: Skipping PackageSetting{284f7f47 com.example.hello/10168} due to missing metadata
,09-07 13:16:27.589  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{1618787f u0 com.test.thalitest/.MainActivity t2}
,09-07 13:16:27.599  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-07 13:16:27.599  1014  1040 D InputDispatcher: Focus left window: 6777
,09-07 13:16:27.599   257   444 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-07 13:16:27.609   257  1036 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-07 13:16:27.619  1014  1040 D InputDispatcher: Focused application released
09-07 13:16:27.619  1014  1040 D FocusedStackFrame: Set to : 0
09-07 13:16:27.619  1014  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-07 13:16:27.619  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 13:16:27.619  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 13:16:27.619  1014  1040 W ActivityManager: mDVFSHelper.acquire(),
,09-07 13:16:27.629  1014  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-07 13:16:27.629  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-07 13:16:27.629  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-07 13:16:27.629  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-07 13:16:27.639  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-07 13:16:27.639  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 13:16:27.639  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 13:16:27.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 13:16:27.639  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-07 13:16:27.649  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-07 13:16:27.679  2639  2639 I art     : Explicit concurrent mark sweep GC freed 19553(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 790us total 33.918ms
,09-07 13:16:27.689  1481  1481 D Launcher: onRestart, Launcher: 121429942
,09-07 13:16:27.709  1481  1481 D Launcher: onStart, Launcher: 121429942
09-07 13:16:27.709  1481  1481 D Launcher.HomeView: onStart
,09-07 13:16:27.709  1481  1481 D Launcher: onResume, Launcher: 121429942
,09-07 13:16:27.709  1014  1480 D SettingsProvider: name = kids_home_mode
,09-07 13:16:27.709  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 13:16:27.709  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 13:16:27.709  1014  1480 D SettingsProvider: selectionArgs: false
09-07 13:16:27.709  1014  1480 D SettingsProvider: selectionArgs: 10006
09-07 13:16:27.709  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 13:16:27.709  1014  1480 D SettingsProvider: ret = -1
,09-07 13:16:27.709  1481  1481 D Launcher.HomeView: onResume
,09-07 13:16:27.719  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-07 13:16:27.749  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 13:16:27.759  1874  1874 E SamsungIME: mOCRHelper is null
09-07 13:16:27.759  1975  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 13:16:27.759  1452  1452 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 13:16:27.769  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.769  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-07 13:16:27.769  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-07 13:16:27.779  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 13:16:27.779  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 13:16:27.779  1014  1122 V NetworkStats: performPollLocked() took 8ms
09-07 13:16:27.779  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:27.789  2855  2855 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 13:16:27 GMT+02:00 2016
,09-07 13:16:27.789  4802  4802 I art     : Explicit concurrent mark sweep GC freed 23419(1408KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 3.530ms total 148.001ms
,09-07 13:16:27.789  1481  1481 D MenuAppsGridFragment: onResume
,09-07 13:16:27.799  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-07 13:16:27.799  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-07 13:16:27.799  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:27.809  1441  1441 D RegisteredServicesCache: empty dynamic service
,09-07 13:16:27.809  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-07 13:16:27.809  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 13:16:27.809  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 13:16:27.809  1014  1330 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-07 13:16:27.809  1014  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-07 13:16:27.809  1014  1330 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:27.809  1014  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 13:16:27.819  1014  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 13:16:27.829  2855  2855 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 13:16:27.849  1014  1429 D ActivityManager: handle home activity for 0
,09-07 13:16:27.849  1014  1429 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,09-07 13:16:27.849  1014  1429 D KnoxTimeoutHandler: post home show event for user 0
09-07 13:16:27.849  1014  1429 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-07 13:16:27.849  1014  1429 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 13:16:27.849  1014  1429 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-07 13:16:27.849  1481  1481 D Launcher.HomeView: onPause
,09-07 13:16:27.849  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
09-07 13:16:27.849  1014  1438 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-07 13:16:27.849  1014  1438 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-07 13:16:27.849  1014  1438 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-07 13:16:27.849  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:27.859  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:27.859  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:27.859  1014  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:27.859  2855  2855 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-07 13:16:27.859  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
09-07 13:16:27.859  1014  1039 W TextServicesManagerService: no available spell checker services found
09-07 13:16:27.859  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-07 13:16:27.869  2855  2855 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 13:16:27.869  7728  7728 I libpersona: KNOX_SDCARD checking this for 10090
09-07 13:16:27.869  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 13:16:27.869  7728  7728 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:27.869  7728  7728 E Zygote  : MountEmulatedStorage()
09-07 13:16:27.869  7728  7728 E Zygote  : v2
09-07 13:16:27.869  2855  2855 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-07 13:16:27.869  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:27.869  7728  7728 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:27.879  7728  7728 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:27.879  1014  1438 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7728 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-07 13:16:27.879  7728  7728 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:27.889  1014  1438 I ActivityManager: Killing 7129:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-07 13:16:27.889  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-07 13:16:27.889  1014  1027 I TactileAssist: enable value -1
09-07 13:16:27.889  1014  1027 I TactileAssist: internal enable value -1
09-07 13:16:27.889  1014  1027 I TactileAssist: intensity value -1
09-07 13:16:27.889  1014  1027 I TactileAssist: saveAppList value true
,09-07 13:16:27.919  7728  7728 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:27.919  7728  7728 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:27.919  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:27.919  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 13:16:27.919   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
09-07 13:16:27.919  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:27.919  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:27.919  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:27.919  1014  1027 I TactileAssist: List of disabled apps :
,09-07 13:16:27.929  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-07 13:16:27.929  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-07 13:16:27.929  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:27.929  2484  2505 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:27.929  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-07 13:16:27.939  7744  7744 E Zygote  : MountEmulatedStorage()
09-07 13:16:27.939  7744  7744 E Zygote  : v2
09-07 13:16:27.939  7744  7744 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:27.939  7744  7744 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:27.939  7744  7744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:27.939  1014  1095 D InputDispatcher: Focus entered window: 1481
,09-07 13:16:27.939  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-07 13:16:27.939  7744  7744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:27.939  7744  7744 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:27.949  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 13:16:27.949  1014  1436 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-07 13:16:27.949  1014  1436 D SecContentProvider2: mCursor = null
,09-07 13:16:27.949  1014  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7744 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 13:16:27.949  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 13:16:27.949  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 13:16:27.949  1014  1014 I art     : Explicit concurrent mark sweep GC freed 78770(5MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 16.884ms total 298.655ms
09-07 13:16:27.949  1014  1054 I art     : WaitForGcToComplete blocked for 182.379ms for cause Explicit
,09-07 13:16:27.949  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-07 13:16:27.949  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-07 13:16:27.979  1014  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 13:16:27.979  7744  7744 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:27.979  7744  7744 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:27.979  1014  7761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 13:16:27.989  1014  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-07 13:16:27.989  1014  1496 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6777 uid 10171
,09-07 13:16:27.999  1874  1874 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-07 13:16:28.009  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-07 13:16:28.009  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-07 13:16:28.009  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.009  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.009  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.009  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.009  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-07 13:16:28.019  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-07 13:16:28.019  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-07 13:16:28.019  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-07 13:16:28.039  7763  7763 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.039  7763  7763 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:28.039  7763  7763 E Zygote  : v2
09-07 13:16:28.039  7763  7763 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.039  7763  7763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.039  7763  7763 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:28.039  1014  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7763 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 13:16:28.039  7763  7763 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.049  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-07 13:16:28.059  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-07 13:16:28.059  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-07 13:16:28.069  1014  1045 W ActivityManager: mDVFSHelper.release()
,09-07 13:16:28.069  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{448416e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147815
,09-07 13:16:28.079  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,09-07 13:16:28.089  7763  7763 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.089  7763  7763 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.089  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-07 13:16:28.099  2855  7727 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-07 13:16:28.099  2855  7727 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-07 13:16:28.099  1014  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-07 13:16:28.109  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.109  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.109  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.109  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.119  1014  1330 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7778 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-07 13:16:28.119  7778  7778 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.119  7778  7778 I libpersona: KNOX_SDCARD checking this for 10048
09-07 13:16:28.119  7778  7778 E Zygote  : v2
09-07 13:16:28.119  7778  7778 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.119  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.129  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:28.129  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.149  2855  2855 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 13:16:28.149  7744  7744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-07 13:16:28.149  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-07 13:16:28.149  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.149  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.149  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:28.149  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-07 13:16:28.159  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-07 13:16:28.159  7763  7763 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-07 13:16:28.169  1014  1429 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-07 13:16:28.179  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.179  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.189  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.189  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.189  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.189  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.189  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.189  7778  7778 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.199  7794  7794 E Zygote  : MountEmulatedStorage(),
,09-07 13:16:28.199  1014  1429 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7794 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-07 13:16:28.199  7794  7794 E Zygote  : v2
09-07 13:16:28.199  7794  7794 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:28.199  7794  7794 I libpersona: KNOX_SDCARD not a persona,
09-07 13:16:28.209  7794  7794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:28.209  7728  7728 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-07 13:16:28.209  7794  7794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 13:16:28.209  7794  7794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 13:16:28.209  7728  7728 D elm:15121: ELMEngine.ELMEngine( context ).
09-07 13:16:28.209  7728  7728 D elm:15121: MDMBridge.setEnterpriseBridge(),
09-07 13:16:28.209  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 13:16:28.209  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 13:16:28.229   307   307 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 30.060ms
,09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED,
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicy: uID is 10171
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 13:16:28.229  1014  1429 I ActivityManager: Killing 7192:com.sec.android.diagmonagent/1000 (adj 15): empty #21
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 13:16:28.229  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-07 13:16:28.239  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 13:16:28.239  1014  1095 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-07 13:16:28.239  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.239  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.239  1014  1095 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:28.239  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-07 13:16:28.239  7728  7728 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-07 13:16:28.239  7794  7794 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:28.239  7794  7794 D ActivityThread: Added TimaKeyStore provider
09-07 13:16:28.239  7728  7728 D elm:15121: ElmAgentService : onCreate()
,09-07 13:16:28.239  7728  7809 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-07 13:16:28.239  7728  7809 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-07 13:16:28.239  7728  7809 D elm:15121: MDMBridge.getInstance()
09-07 13:16:28.239  7728  7809 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-07 13:16:28.249  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.249  7728  7809 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-07 13:16:28.259  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicy: uID is 10171
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-07 13:16:28.259   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 25.295ms
09-07 13:16:28.259  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 13:16:28.259  1014  1496 D SecContentProvider2: uri = -1 selection = getSealedState
,09-07 13:16:28.259  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-07 13:16:28.259  1014  1496 D SecContentProvider2: mCursor = null
09-07 13:16:28.259  1014  3356 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-07 13:16:28.259  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-07 13:16:28.259  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-07 13:16:28.259  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-07 13:16:28.259  1014  1014 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-07 13:16:28.259  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 13:16:28.259  7763  7763 I PopupuiReceiver_KNOX: getSealedState : true
09-07 13:16:28.259  1014  1027 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-07 13:16:28.259  1014  1027 D SecContentProvider2: mCursor = null
09-07 13:16:28.259  7763  7763 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,09-07 13:16:28.269  1014  1095 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-07 13:16:28.269  1014  1095 D SecContentProvider2: mCursor = null
,09-07 13:16:28.269  7763  7763 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-07 13:16:28.269  7763  7763 D PopupuiReceiver: Action package removed
,09-07 13:16:28.269  1014  1429 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-07 13:16:28.269  1014  1054 I art     : Explicit concurrent mark sweep GC freed 10455(546KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 9.226ms total 318.192ms
,09-07 13:16:28.269  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.269  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.269  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.269  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.279   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 19.866ms
,09-07 13:16:28.279  1174  1174 I StatusBar: Icon Only
09-07 13:16:28.279  1174  1174 D PanelView: There is/are notification(s) 
,09-07 13:16:28.289  7794  7794 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:16:28.289  7811  7811 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.289  7811  7811 E Zygote  : v2
09-07 13:16:28.289  7811  7811 I libpersona: KNOX_SDCARD checking this for 10145
09-07 13:16:28.289  7811  7811 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:28.299  7811  7811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.299  7811  7811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:28.299  7811  7811 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 13:16:28.299  1014  1429 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7811 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:16:28.309  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-07 13:16:28.309  1014  1429 I ActivityManager: Killing 7175:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-07 13:16:28.309  7728  7728 D elm:15121: ElmAgentService : onDestroy().
,09-07 13:16:28.309  1014  1095 I ActivityManager: Killing 7211:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-07 13:16:28.309  7778  7778 D Compatibility: onReceive() it will make start service
,09-07 13:16:28.319  1014  1429 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-07 13:16:28.319  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-07 13:16:28.319  7811  7811 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.329  7811  7811 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.329  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.329  1014  1429 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:28.329  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-07 13:16:28.329  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-07 13:16:28.339  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.339  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.339  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.339  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.339  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 13:16:28.339  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:28.339  7778  7826 D Compatibility: onHandleIntent()
09-07 13:16:28.339  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:16:28.339  7778  7826 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-07 13:16:28.349  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.349  7778  7826 D Compatibility: found: 2
,09-07 13:16:28.349  7827  7827 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.349  7827  7827 E Zygote  : v2
09-07 13:16:28.349  7827  7827 I libpersona: KNOX_SDCARD checking this for 10052
09-07 13:16:28.349  7827  7827 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:28.349  7827  7827 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.359  7827  7827 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:28.359  7827  7827 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-07 13:16:28.359  7794  7794 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-07 13:16:28.359  1014  1480 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7827 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
09-07 13:16:28.359  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 13:16:28.369  7778  7826 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-07 13:16:28.369  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.369  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.369  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.369  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.379  1014  1480 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-07 13:16:28.379  1014  1480 D SecContentProvider2: mCursor = null
,09-07 13:16:28.379  1014  1476 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-07 13:16:28.379  1014  1476 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-07 13:16:28.379  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.379  7778  7826 D Compatibility: skipping ResolveInfo{26932219 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-07 13:16:28.379  7778  7826 D Compatibility: considering ResolveInfo{395f52de com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-07 13:16:28.379  7778  7826 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-07 13:16:28.379  7778  7826 D Compatibility: enabling receiver ResolveInfo{2e8a1cbf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,09-07 13:16:28.389  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.389  7778  7826 D Compatibility: enabling receiver ResolveInfo{204a9f8c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-07 13:16:28.389  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 13:16:28.389  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 13:16:28.389  1014  1054 D PackageManager: delete codoeFile: 
,09-07 13:16:28.399  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.399  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-07 13:16:28.399  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 13:16:28.409  7778  7826 D Compatibility: enabling receiver ResolveInfo{2eaac6d5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-07 13:16:28.409  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 13:16:28.409  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-07 13:16:28.409  7563  7579 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 13:16:28.409  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 13:16:28.409  7827  7827 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:28.409  7827  7827 D ActivityThread: Added TimaKeyStore provider
09-07 13:16:28.409  7843  7843 I libpersona: KNOX_SDCARD checking this for 1000
09-07 13:16:28.409  7843  7843 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.409  7843  7843 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.409  7843  7843 E Zygote  : v2
,09-07 13:16:28.409  7843  7843 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.409  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-07 13:16:28.419  7778  7826 D Compatibility: enabling receiver ResolveInfo{509beea com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-07 13:16:28.419  7843  7843 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:28.419  7843  7843 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.419  1014  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-07 13:16:28.419  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 13:16:28.429  7778  7826 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-07 13:16:28.429  1014  1054 D PackageManager: result of delete: 1{861796060}
,09-07 13:16:28.429  1014  1429 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-07 13:16:28.429  7700  7700 D AndroidRuntime: Shutting down VM
,09-07 13:16:28.429  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.429  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.429  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.429  1014  1429 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.429  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-07 13:16:28.429  1014  1054 D PackageManager: userId{-1}
09-07 13:16:28.429  1014  1054 D PackageManager: andCode{true}
,09-07 13:16:28.439  7843  7843 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.439  7843  7843 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.449  7858  7858 E Zygote  : MountEmulatedStorage()
,09-07 13:16:28.449  7858  7858 I libpersona: KNOX_SDCARD checking this for 10087
09-07 13:16:28.449  7858  7858 E Zygote  : v2,
,09-07 13:16:28.449  7858  7858 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.449  7858  7858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.449  1014  1429 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7858 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,09-07 13:16:28.449  7858  7858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:28.459  7858  7858 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.459  1014  1429 I ActivityManager: Killing 7235:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-07 13:16:28.459  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-07 13:16:28.469  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-07 13:16:28.469  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:28.479  1014  1436 I ActivityManager: Killing 7144:com.android.chrome/u0a77 (adj 15): empty #21
,09-07 13:16:28.479  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.479  7858  7858 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.479  7858  7858 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.499  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.499  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.499  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.499  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.499  7843  7843 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-07 13:16:28.499  7843  7843 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-07 13:16:28.499  7843  7843 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 13:16:28.509  7874  7874 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.509  7874  7874 I libpersona: KNOX_SDCARD checking this for 10003
,09-07 13:16:28.509  7874  7874 E Zygote  : v2
09-07 13:16:28.509  7874  7874 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.509  7874  7874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:28.509  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7874 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 13:16:28.519  7874  7874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:28.519  7874  7874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.529  7811  7811 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-07 13:16:28.529  7811  7811 D ThemeInfoUtil: isCurrentFestival = false
,09-07 13:16:28.529  1014  1330 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-07 13:16:28.529  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.529  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.529  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.529  1014  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.539  7843  7843 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-07 13:16:28.539  7843  7843 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-07 13:16:28.539  7843  7843 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-07 13:16:28.539  7843  7843 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-07 13:16:28.539  7883  7883 E Zygote  : MountEmulatedStorage(),
09-07 13:16:28.549  7883  7883 E Zygote  : v2
09-07 13:16:28.549  7883  7883 I libpersona: KNOX_SDCARD checking this for 10148
,09-07 13:16:28.549  7883  7883 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:28.549  7883  7883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.549  7883  7883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:28.549  1014  1330 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7883 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-07 13:16:28.549  1014  1330 I ActivityManager: Killing 7028:com.google.android.talk/u0a102 (adj 15): empty #21
09-07 13:16:28.549  7883  7883 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.569  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-07 13:16:28.569  7874  7874 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:28.569  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.569  7874  7874 D ActivityThread: Added TimaKeyStore provider
09-07 13:16:28.569  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.569  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.569  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.579  7883  7883 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.579  7883  7883 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.589  7904  7904 E Zygote  : MountEmulatedStorage(),
09-07 13:16:28.589  7904  7904 I libpersona: KNOX_SDCARD checking this for 10029
09-07 13:16:28.589  7904  7904 E Zygote  : v2,
09-07 13:16:28.589  7904  7904 I libpersona: KNOX_SDCARD not a persona
09-07 13:16:28.589  7904  7904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 13:16:28.589  1014  1480 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-07 13:16:28.589  7904  7904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 13:16:28.589  7904  7904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-07 13:16:28.589  1014  1479 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7904 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-07 13:16:28.599  1014  7745 I ActivityManager: Killing 7255:com.google.android.apps.magazines/u0a110 (adj 15): empty #21,
,09-07 13:16:28.609  1014  1026 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-07 13:16:28.609  7904  7904 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.609  7904  7904 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.619  1014  1429 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-07 13:16:28.619  1014  1429 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.629  1014  1429 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.629  1014  1429 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:28.629  1014  1429 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-07 13:16:28.639  7700  7700 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-07 13:16:28.639  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-07 13:16:28.639  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.639  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.639  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:28.639  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-07 13:16:28.649  1014  1026 I ActivityManager: Killing 7270:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-07 13:16:28.659  1014  1480 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-07 13:16:28.669  1481  1481 I Choreographer: Skipped 39 frames!  The application may be doing too much work on its main thread.
,09-07 13:16:28.669  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{3397f423 token=android.os.BinderProxy@15d004d0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-07 13:16:28.669  1481  1481 D Launcher.HomeView: onStop
,09-07 13:16:28.669  7444  7444 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-07 13:16:28.669  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 13:16:28.669  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15d004d0 time:148419
,09-07 13:16:28.679  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.679  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.679  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.679  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.679  7904  7922 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-07 13:16:28.679  7883  7883 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-07 13:16:28.689  7924  7924 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.689  7924  7924 E Zygote  : v2
09-07 13:16:28.689  7924  7924 I libpersona: KNOX_SDCARD checking this for 10032
09-07 13:16:28.689  7924  7924 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:28.689  7924  7924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 13:16:28.689  1014  1476 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7924 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 13:16:28.699  7924  7924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 13:16:28.699  7924  7924 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 13:16:28.709  7904  7922 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-07 13:16:28.709  7904  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:28.709  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:16:28.709  7904  7922 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-07 13:16:28.709  7904  7922 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-07 13:16:28.709  1014  1438 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-07 13:16:28.709  1014  1438 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.709  1014  1438 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.709  1014  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 13:16:28.709  1014  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 13:16:28.719  7904  7922 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 13:16:28.719  1014  7745 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-07 13:16:28.719  1014  7745 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.719  1014  7745 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.719  1014  7745 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 13:16:28.719  1014  7745 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 13:16:28.749  7924  7924 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 13:16:28.749  7924  7924 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.759  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-07 13:16:28.759  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
09-07 13:16:28.759  7944  7944 E Zygote  : MountEmulatedStorage()
09-07 13:16:28.759  7944  7944 E Zygote  : v2
09-07 13:16:28.759  7944  7944 I libpersona: KNOX_SDCARD checking this for 10152
09-07 13:16:28.759  7944  7944 I libpersona: KNOX_SDCARD not a persona
,09-07 13:16:28.769  1014  7745 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7944 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,09-07 13:16:28.769  7944  7944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 13:16:28.769  7944  7944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 13:16:28.769  7944  7944 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 13:16:28.769  1014  7745 I ActivityManager: Killing 7286:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 13:16:28.779  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-07 13:16:28.789  7904  7922 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-07 13:16:28.789  7904  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:28.789  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
09-07 13:16:28.789  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 13:16:28.799  7636  7636 W FileUtils: Failed to chmod(/data/user/0/com.samsung.android.sm/databases/history.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-07 13:16:28.809  7636  7636 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,09-07 13:16:28.809  7944  7944 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 13:16:28.809  7944  7944 D ActivityThread: Added TimaKeyStore provider
,09-07 13:16:28.809  7636  7636 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM app_history WHERE package_name=?] disk I/O error
,09-07 13:16:28.809  7444  7444 D BluetoothAdapter: cancelDiscovery
,09-07 13:16:28.809  7636  7636 D AndroidRuntime: Shutting down VM
,09-07 13:16:28.829  7563  7588 D BluetoothAdapterProperties: mDiscovering is false
,09-07 13:16:28.829  7563  7588 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,09-07 13:16:28.829  7444  7444 D BluetoothAdapter: cancelDiscovery = true
,09-07 13:16:28.829  7444  7444 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-07 13:16:28.829  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 13:16:28.829  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-07 13:16:28.829  7636  7636 E AndroidRuntime: FATAL EXCEPTION: main
09-07 13:16:28.829  7636  7636 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7636
09-07 13:16:28.829  7636  7636 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.b(ScanHistoryHelper.java:222)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:161)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-07 13:16:28.829  7636  7636 E AndroidRuntime: 	... 9 more
,09-07 13:16:28.839  7444  7444 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-07 13:16:28.839  7904  7922 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 13:16:28.839  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 13:16:28.839  7904  7922 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-07 13:16:28.839  7444  7444 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-07 13:16:28.839  7444  7444 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,09-07 13:16:28.839  7444  7444 E SQLiteDatabase: Error inserting timestamp=1473246988840 message=Predictor: service stopped by removePlaceCategories()
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 13:16:28.839  7444  7444 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 13:16:28.839  7444  7444 E UserAnalysis: It failed to insert to dump_log table
,09-07 13:16:28.839  1014  1436 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,09-07 13:16:28.849  7904  7922 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 13:16:28.849  7904  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 13:16:28.849  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 13:16:28.849  7904  7922 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-07 13:16:28.849  7904  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 13:16:28.859  7904  7922 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 13:16:28.859  7904  7922 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 13:16:28.859  1014  1330 I ActivityManager: Killing 7356:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-07 13:16:28.859  1014  7959 E DropBoxManagerService: Can't write: system_app_crash
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 13:16:28.859  1014  7959 E DropBoxManagerService: 	... 5 more
,09-07 13:16:28.869  7636  7636 I Process : Sending signal. PID: 7636 SIG: 9
,09-07 13:16:28.869  7944  7944 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-07 13:16:28.869  7944  7944 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-07 13:16:28.879  7944  7944 I TapandpayWidget:Utils: Clear T&P info.
,09-07 13:16:28.889  7944  7944 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-07 13:16:28.889  7904  7922 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 13:16:28.889  7904  7922 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 13:16:28.889  1014  1480 I ActivityManager: Killing 6868:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
09-07 13:16:28.889  7904  7922 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 13:16:28.889  1014  1095 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 13:16:28.889  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-07 13:16:28.889  1014  1095 W ActivityManager: userId = 0, bbcId = -10000
09-07 13:16:28.889  1014  1095 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 13:16:28.889  1014  1095 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms

```
