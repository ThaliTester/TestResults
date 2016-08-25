#### Test 82728424cc1b7f1_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-25 21:48:55.536  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 21:48:55.536  1018  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 21:48:55.536  1018  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 21:48:55.536  1018  1480 D BatteryService: stay LED for fully charged
08-25 21:48:55.536  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-25 21:48:55.536  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-25 21:48:55.536  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 21:48:55.536  1018  1018 I MotionRecognitionService: Plugged
08-25 21:48:55.536  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-25 21:48:55.546  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 21:48:55.546  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 21:48:55.556  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 21:48:55.556  3161  3269 D HeadsetStateMachine: Disconnected process message: 10
08-25 21:48:55.566  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-25 21:48:55.566  1174  1174 D SViewCoverView: level :100 plugged : 2
08-25 21:48:55.566  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:48:55.566  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:48:55.566  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:48:55.816  6689  6689 D AndroidRuntime: 
08-25 21:48:55.816  6689  6689 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 21:48:55.816  6689  6689 D AndroidRuntime: CheckJNI is OFF
08-25 21:48:55.816  6689  6689 D AndroidRuntime: readGMSProperty: start
08-25 21:48:55.816  6689  6689 D AndroidRuntime: readGMSProperty: already setted!!
08-25 21:48:55.816  6689  6689 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 21:48:55.816  6689  6689 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 21:48:55.816  6689  6689 D AndroidRuntime: readGMSProperty: end
08-25 21:48:55.816  6689  6689 D AndroidRuntime: addProductProperty: start
08-25 21:48:55.956  6689  6689 E AffinityControl: AffinityControl: registerfunction enter
08-25 21:48:55.976  6689  6689 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 21:48:55.986  1018  1478 E PersonaManagerService: inState():  stateMachine is null !!
08-25 21:48:55.996  1018  1478 I PersonaManagerService: PersonaId don't exist
08-25 21:48:55.996  1018  1478 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-25 21:48:55.996  1018  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 21:48:56.016  1018  1478 W ActivityManager: mDVFSHelper.acquire()
08-25 21:48:56.026   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-25 21:48:56.026   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-25 21:48:56.026  1018  1478 D FocusedStackFrame: Set to : 0
08-25 21:48:56.036  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 21:48:56.036  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-25 21:48:56.046  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:48:56.046  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:48:56.046  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:48:56.046  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:48:56.056  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 21:48:56.056  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 21:48:56.056   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-25 21:48:56.066  6702  6702 E Zygote  : MountEmulatedStorage()
08-25 21:48:56.066  6702  6702 E Zygote  : v2
08-25 21:48:56.066  6702  6702 I libpersona: KNOX_SDCARD checking this for 10171
08-25 21:48:56.066  6702  6702 I libpersona: KNOX_SDCARD not a persona
08-25 21:48:56.066  6702  6702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:48:56.066  1018  1478 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6702 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 21:48:56.066  1018  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-25 21:48:56.066  1018  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 21:48:56.066  1018  1478 D InputDispatcher: Focused application set to: xxxx
08-25 21:48:56.066  1018  1478 D InputDispatcher: Focus left window: 1483
08-25 21:48:56.066  6689  6689 D AndroidRuntime: Shutting down VM
08-25 21:48:56.066  6702  6702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:48:56.066  6702  6702 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-25 21:48:56.086  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 21:48:56.086  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 21:48:56.096  6702  6702 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:48:56.096  6702  6702 D ActivityThread: Added TimaKeyStore provider
08-25 21:48:56.096  1018  1137 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-25 21:48:56.106  1018  1018 V ActivityManager: Display changed displayId=0
08-25 21:48:56.106  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 21:48:56.126  1018  1137 D PersonaManager: isKioskContainerExistOnDevice
08-25 21:48:56.146  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-25 21:48:56.166   259  1040 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-25 21:48:56.166   259   441 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-25 21:48:56.176  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{256c21ea token=android.os.BinderProxy@1e231e04 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-25 21:48:56.176  1483  1483 D Launcher: onTrimMemory. Level: 20
08-25 21:48:56.246  6702  6702 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-25 21:48:56.276  6689  6689 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-25 21:48:56.276  6702  6702 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 6902-6909)
,08-25 21:48:56.276  6702  6702 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 21:48:56.306  6702  6702 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a2c7b39}
08-25 21:48:56.306  6702  6702 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 21:48:56.316  6702  6702 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 21:48:56.346   300   300 E SMD     : DCD OFF
08-25 21:48:56.356  6702  6702 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-25 21:48:56.356  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:48:56.366  6702  6702 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 21:48:56.426  6702  6702 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 21:48:56.426  6702  6702 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 21:48:56.426  6702  6702 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 21:48:56.426  6702  6702 I Adreno-EGL: Local Branch: 
08-25 21:48:56.426  6702  6702 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 21:48:56.426  6702  6702 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 21:48:56.426  6702  6702 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-25 21:48:56.516  6702  6702 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 21:48:56.556  6702  6702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 21:48:56.556  6702  6702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 21:48:56.566  6702  6702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 21:48:56.566  6702  6702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 21:48:56.636  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{18185fb6 u0 com.test.thalitest/.MainActivity t2}
08-25 21:48:56.676  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:48:56.686  6702  6702 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 21:48:56.696  6702  6702 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 21:48:56.696  6702  6702 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-25 21:48:56.706  6702  6702 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-25 21:48:56.716  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:48:56.716  6702  6702 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:48:56.756  6702  6741 D OpenGLRenderer: Render dirty regions requested: true
08-25 21:48:56.756  1018  1137 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 21:48:56.756  1018  1137 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 21:48:56.756  1018  1137 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 21:48:56.756  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 21:48:56.756  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 21:48:56.766  6702  6729 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-25 21:48:56.776  6702  6702 V ActivityThread: updateVisibility : ActivityRecord{25740a19 token=android.os.BinderProxy@216e1792 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 21:48:56.776  6702  6702 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 21:48:56.776  6702  6702 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 21:48:56.786   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-25 21:48:56.796  1018  4362 D InputDispatcher: Focus entered window: 6702
08-25 21:48:56.806  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 21:48:56.806  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 21:48:56.806  6702  6702 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-25 21:48:56.806  6702  6741 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 21:48:56.816  6702  6741 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-25 21:48:56.816  6702  6741 D OpenGLRenderer: Enabling debug mode 0
08-25 21:48:56.826  1018  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-25 21:48:56.836  1174  1174 I StatusBar: Icon Only
08-25 21:48:56.836  1174  1174 D PanelView: There is/are notification(s) 
08-25 21:48:56.836  1018  6746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 21:48:56.856  1018  1049 I ActivityManager: Displayed Component not be shown by security: +716ms (total +810ms)
08-25 21:48:56.856  1018  1049 W ActivityManager: mDVFSHelper.release()
08-25 21:48:56.856  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18185fb6 u0 com.test.thalitest/.MainActivity t2} time:107482
08-25 21:48:56.856  6702  6702 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-25 21:48:56.856  6702  6702 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@216e1792 time:107487
08-25 21:48:56.856   259  1040 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-25 21:48:56.866   259  1877 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-25 21:48:56.926  1878  1878 I SamsungIME: getCurrentCandidateView
08-25 21:48:57.006  6702  6702 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6702
08-25 21:48:57.036  1878  1878 D SamsungIME: Dismiss ExpandCandiate
,08-25 21:48:57.196  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 21:48:57.216  6702  6702 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 21:48:57.236  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 21:48:57.246  1878  1878 I SamsungIME: KeybaordView init() : load resources
,08-25 21:48:57.276  1878  1878 I SamsungIME: getCurrentKeyboard
,08-25 21:48:57.276  1878  1878 I SamsungIME: getTextKeyboard
,08-25 21:48:57.296  1878  1878 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-25 21:48:57.306  6702  6748 D jxcore_app_log: JniHelper::setJavaVM(0xb7c232b0), pthread_self() = -1206181944
,08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 21:48:57.306  6702  6748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39650cb7 added. We now have 1 listener(s)
,08-25 21:48:57.316  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-25 21:48:57.316  6702  6748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:48:57.316  6702  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:48:57.316  6702  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 21:48:57.326  6702  6748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26278942 added. We now have 1 listener(s)
,08-25 21:48:57.326  6702  6748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:48:57.336  6702  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-25 21:48:57.346  6702  6748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:48:57.346  6702  6748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:48:57.346  6702  6748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 21:48:57.346  6702  6748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:48:57.346  6702  6748 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 21:48:57.346  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:48:57.356  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:48:57.376  6702  6702 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 21:48:57.386  1018  1307 E Watchdog: !@Sync 3
,08-25 21:48:57.926  6702  6755 W jxcore-log: Initializing JXcore engine
08-25 21:48:57.926  6702  6755 W jxcore-log: JXcore engine is ready
,08-25 21:48:57.986  2012  2012 E audit   : type=1400 msg=audit(1472154537.986:205): avc:  denied  { ioctl } for  pid=6755 comm="Thread-1235" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 21:48:57.986  2012  2012 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:48:57.986  2012  2012 E audit   : type=1300 msg=audit(1472154537.986:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9fc978f8 items=0 ppid=320 ppcomm=main pid=6755 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1235" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-25 21:48:57.986  2012  2012 E audit   : type=1320 msg=audit(1472154537.986:205): 
,08-25 21:48:57.996  6702  6755 W jxcore-log: Starting JXcore engine
,08-25 21:48:58.096  6702  6755 W jxcore-log: Platform android
08-25 21:48:58.096  6702  6755 W jxcore-log: 
08-25 21:48:58.096  6702  6755 W jxcore-log: Process ARCH arm
08-25 21:48:58.096  6702  6755 W jxcore-log: 
,08-25 21:48:58.306  6702  6755 I jxcore-log: JXcore Cordova bridge is ready!
08-25 21:48:58.306  6702  6755 I jxcore-log: 
,08-25 21:48:58.306  6702  6755 W jxcore-log: JXcore engine is started
,08-25 21:48:58.306  6702  6748 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 21:48:58.306  6702  6702 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 21:48:58.396   334   334 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-25 21:48:58.396   334   334 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-25 21:48:59.346   300   300 E SMD     : DCD OFF
,08-25 21:48:59.986  1018  1097 V AlarmManager: waitForAlarm result :8,
,08-25 21:49:02.346   300   300 E SMD     : DCD OFF,
,08-25 21:49:02.486  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,08-25 21:49:02.806  1018  3339 D SSRM:n  : SIOP:: AP = 330
,08-25 21:49:03.396   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:04.396   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:04.836  5618  5618 D FactoryTest: Not factory mode
,08-25 21:49:04.836  5618  5618 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-25 21:49:04.836  5618  5618 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-25 21:49:04.836  5618  5618 D MTPRx   : still no open session command from host, so toast
,08-25 21:49:04.836  5618  5618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-25 21:49:04.836  5618  5618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-25 21:49:04.846  5618  5618 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115470
,08-25 21:49:04.846  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
,08-25 21:49:04.846  1018  1030 I PersonaManagerService: PersonaId don't exist
08-25 21:49:04.846  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-25 21:49:04.846  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-25 21:49:04.846  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:04.846  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:04.846  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-25 21:49:04.856  1018  1030 W ActivityManager: mDVFSHelper.acquire()
,08-25 21:49:04.876  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-25 21:49:04.876  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 21:49:04.876  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 21:49:04.876  1018  1030 D InputDispatcher: Focused application set to: xxxx
08-25 21:49:04.876  1018  1030 D InputDispatcher: Focus left window: 6702
,08-25 21:49:04.876  5618  5618 E MTPRx   : started activity for popup
,08-25 21:49:04.896  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 21:49:04.896  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 21:49:04.906  5618  5618 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 21:49:04.926  5618  5618 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-25 21:49:04.936  1018  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 21:49:04.936  1018  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 21:49:04.936  1018  1481 D InputDispatcher: Focused application set to: xxxx
,08-25 21:49:04.936  1018  1481 D InputDispatcher: Focus entered window: 6702,
,08-25 21:49:04.936  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 21:49:04.946  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 21:49:04.946  1018  1356 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 21:49:04.946  1018  1356 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@391acda1 attribute=null, token = android.os.BinderProxy@1590f631
,08-25 21:49:04.976  5618  5618 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-25 21:49:04.986  5618  5618 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-25 21:49:04.986  5618  5618 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-25 21:49:05.006  6702  6702 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 21:49:05.006  6702  6702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-25 21:49:05.006  6702  6702 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 21:49:05.006  6702  6702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-25 21:49:05.016  1018  1207 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-25 21:49:05.016  1018  1207 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 21:49:05.016  1018  1207 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 21:49:05.016  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-25 21:49:05.016  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 21:49:05.026  6702  6702 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 21:49:05.026  6702  6702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 21:49:05.026  6702  6702 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2908ca2e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@868ffc4, 16908290=android.view.AbsSavedState$1@868ffc4}, android:focusedViewId=100}]}]
08-25 21:49:05.026  6702  6702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 21:49:05.026  6702  6702 V ActivityThread: updateVisibility : ActivityRecord{25740a19 token=android.os.BinderProxy@216e1792 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-25 21:49:05.036  6702  6702 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 21:49:05.036  6702  6702 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-25 21:49:05.036  6702  6702 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@216e1792 time:115661
,08-25 21:49:05.046  1018  1356 D PersonaManager: isKioskContainerExistOnDevice
,08-25 21:49:05.346   300   300 E SMD     : DCD OFF
,08-25 21:49:05.396   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:05.586  1018  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 21:49:05.586  1018  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 21:49:05.586  1018  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 21:49:05.586  1018  1479 D BatteryService: stay LED for fully charged
08-25 21:49:05.586  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 21:49:05.596  1018  1018 I MotionRecognitionService: Plugged
,08-25 21:49:05.596  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 21:49:05.596  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 21:49:05.596  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 21:49:05.596  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 21:49:05.596  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 21:49:05.606  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 21:49:05.616  3161  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-25 21:49:05.626  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 21:49:05.626  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-25 21:49:05.626  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:05.626  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:05.626  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:06.096  1018  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-25 21:49:06.396   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:07.396   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:07.856  1018  1044 W ActivityManager: mDVFSHelper.release()
,08-25 21:49:08.356   300   300 E SMD     : DCD OFF
,08-25 21:49:08.396   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-25 21:49:09.376  1018  1097 V AlarmManager: waitForAlarm result :4
,08-25 21:49:09.376  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-25 21:49:09.386  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-25 21:49:09.396  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-25 21:49:09.396  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-25 21:49:09.396  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-25 21:49:09.396  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 21:49:09.406  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-25 21:49:09.406  1987  1987 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-25 21:49:09.416  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-25 21:49:09.426  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 21:49:09.426  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-25 21:49:09.426  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-25 21:49:09.426  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-25 21:49:09.446  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 21:49:09.466  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
08-25 21:49:09.466  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:09.466  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0,
,08-25 21:49:09.466  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-25 21:49:09.466  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:09.466  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-25 21:49:09.476  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 21:49:09.496  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 21:49:09.536  4774  4774 D ConnectivityManager: CallingUid : 10011, CallingPid : 4774
,08-25 21:49:09.536  1018  1030 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 21:49:09.536  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-25 21:49:09.546  1018  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-25 21:49:09.546  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-25 21:49:09.546  4774  6764 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 21:49:09.596  4774  6765 W DriveInitializer: Background init thread started
,08-25 21:49:09.626   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-25 21:49:09.626   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:09.626  4774  6765 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-25 21:49:09.666  1987  1987 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-25 21:49:09.736  4774  6765 W DriveInitializer: Background init thread ended
,08-25 21:49:09.746  1987  1987 I art     : Explicit concurrent mark sweep GC freed 51744(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 10MB/17MB, paused 1.252ms total 69.902ms
,08-25 21:49:09.786  1018  1356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:09.786  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-25 21:49:09.786  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:09.786  1018  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:09.786  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:09.806  1018  1031 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-25 21:49:09.806  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-25 21:49:09.826  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 21:49:09.826  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-25 21:49:09.826  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:09.826  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:09.826  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:09.896  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 21:49:09.916  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:09.916  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:09.916  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:09.996  1018  1480 I art     : Explicit concurrent mark sweep GC freed 37135(2023KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.587ms total 155.035ms
,08-25 21:49:09.996  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:09.996  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-25 21:49:09.996  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:09.996  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:09.996  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:10.016  4774  6773 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-25 21:49:10.016  4774  6773 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-25 21:49:10.076  1018  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:10.076  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:10.076  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:10.076  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:10.126  1018  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:10.126  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:10.126  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:10.126  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:10.126  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:10.126  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:10.126  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:10.126  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:10.146  6776  6776 E Zygote  : MountEmulatedStorage()
,08-25 21:49:10.146  6776  6776 E Zygote  : v2
08-25 21:49:10.146  6776  6776 I libpersona: KNOX_SDCARD checking this for 10011
08-25 21:49:10.146  6776  6776 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:10.146  6776  6776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 21:49:10.146  6776  6776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:10.146  6776  6776 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 21:49:10.156  1018  1499 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6776 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-25 21:49:10.176   320   320 I art     : Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 21.403ms
,08-25 21:49:10.176  6776  6776 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:10.176  6776  6776 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:10.196   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 643us total 17.500ms
,08-25 21:49:10.196  6776  6776 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 21:49:10.196  6776  6776 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 21:49:10.206   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.833ms
,08-25 21:49:10.246  6776  6776 I MultiDex: VM with version 2.1.0 has multidex support
08-25 21:49:10.246  6776  6776 I MultiDex: install
08-25 21:49:10.246  6776  6776 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 21:49:10.276  6776  6776 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-25 21:49:10.336  6776  6776 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 21:49:10.336  6776  6776 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f9d7745: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-25 21:49:10.336  6776  6776 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 21:49:10.356  6776  6776 D ChimeraCfgMgr: Reading stored module config
,08-25 21:49:10.396  6776  6790 W art     : Suspending all threads took: 5.566ms
,08-25 21:49:10.406  6776  6790 I art     : Background sticky concurrent mark sweep GC freed 27765(1291KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 9.291ms total 41.123ms
,08-25 21:49:10.446  6776  6776 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 21:49:10.446  6776  6776 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 21:49:10.456  6776  6793 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-25 21:49:10.546   290   695 D WVCdm   : Instantiating CDM.
,08-25 21:49:10.546   290   804 I WVCdm   : CdmEngine::OpenSession
,08-25 21:49:10.546   290   804 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-25 21:49:10.566   290   804 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,08-25 21:49:10.586   290   804 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-25 21:49:10.626  6776  6797 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-25 21:49:10.626  6776  6797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 21:49:10.626  6776  6797 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 21:49:10.626  6776  6797 I System.out: (HTTPLog)-Thread-1222-185098302: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-25 21:49:10.626  6776  6797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 21:49:10.626   285   971 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 21:49:10.626   285   971 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 21:49:10.646   290   804 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-25 21:49:10.646   290   290 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-25 21:49:10.646   290   290 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-25 21:49:10.646   290   290 I WVCdm   : CdmEngine::GenerateKeyRequest
08-25 21:49:10.646   290   290 D WVCdm   : PrepareKeyRequest: nonce=1924503322
08-25 21:49:10.676  6776  6797 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 21:49:10.676  6776  6797 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6776, getuid(): 10011
,08-25 21:49:10.786  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 21:49:10.786  6702  6755 I jxcore-log: 
,08-25 21:49:10.796  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 21:49:10.796  6702  6755 I jxcore-log: 
,08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:10.796  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:10.796  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:10.806  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 21:49:10.806  6702  6755 I jxcore-log: 
,08-25 21:49:10.806  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 21:49:10.806  6702  6755 I jxcore-log: 
,08-25 21:49:10.936  6776  6797 I qtaguid : Untagging socket 30
,08-25 21:49:10.956  6776  6790 I art     : Background sticky concurrent mark sweep GC freed 8330(522KB) AllocSpace objects, 74(4MB) LOS objects, 31% free, 8MB/12MB, paused 5.190ms total 38.544ms,
,08-25 21:49:11.286  6800  6800 I dex2oat : ----------------------------------------------------
08-25 21:49:11.286  6800  6800 I dex2oat : <SS>: S T A R T I N G . . .
08-25 21:49:11.286  6800  6800 I dex2oat : <SS>: Zip is absent. Canceled.
,08-25 21:49:11.286  6800  6800 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 21:49:11.336  6800  6800 I dex2oat : dex2oat took 46.386ms (threads: 4)
,08-25 21:49:11.336  1018  3364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 21:49:11.346  6776  6797 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 21:49:11.346  6776  6797 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 21:49:11.346  6776  6797 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 21:49:11.346  6776  6797 I Adreno-EGL: Local Branch: 
08-25 21:49:11.346  6776  6797 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 21:49:11.346  6776  6797 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 21:49:11.346  6776  6797 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 21:49:11.356   300   300 E SMD     : DCD OFF
,08-25 21:49:11.536  6702  6755 D executeNativeTests: Running unit tests,
,08-25 21:49:11.626  6702  6716 I art     : Background sticky concurrent mark sweep GC freed 39386(1920KB) AllocSpace objects, 7(993KB) LOS objects, 19% free, 10MB/13MB, paused 8.876ms total 33.111ms
,08-25 21:49:11.636  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:11.636  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d added. We now have 2 listener(s)
,08-25 21:49:11.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:11.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:11.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:11.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:11.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 added. We now have 2 listener(s)
08-25 21:49:11.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:11.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:11.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:11.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:11.656  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:11.656  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:11.656  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.656  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 21:49:11.666  6702  6755 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 21:49:11.666  6702  6755 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 21:49:11.666  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:11.666  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:11.666  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:11.666  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d removed from the list
08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 removed from the list
08-25 21:49:11.666  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:11.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.666  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:11.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.666  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 21:49:11.676  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:11.676  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:11.676  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.676  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.676  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:11.676  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
,08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:49:11.676  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:11.676  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:11.676  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.676  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:11.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.676  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:11.676  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:11.676  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.686  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:11.686  6702  6755 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:11.686  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:11.686  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:11.686  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:11.686  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:11.686  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:11.686  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:11.696  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:11.696  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.696  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.706  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:11.706  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:11.706  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 21:49:11.716  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 21:49:11.716  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 21:49:11.716  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 21:49:11.716  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:11.726  3161  3271 D BtGatt.GattService: registerClient() - UUID=d5c83209-8e66-4a52-b961-b1b055db7c82
,08-25 21:49:11.776  3161  3261 D BtGatt.GattService: onClientRegistered() - UUID=d5c83209-8e66-4a52-b961-b1b055db7c82, clientIf=6
,08-25 21:49:11.776  6702  6711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 21:49:11.776  3161  3170 D BtGatt.GattService: start scan with filters
,08-25 21:49:11.776  3161  3267 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:11.776  3161  3267 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:11.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:11.786  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:11.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:11.786  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:11.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:11.786  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:11.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 21:49:11.786  3161  3261 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 21:49:11.796  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.796  3161  3267 D BtGatt.ScanManager: allow scan with filters
,08-25 21:49:11.796  3161  3267 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 21:49:11.796  3161  3267 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 21:49:11.796  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:11.796  6702  6755 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:11.796  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 21:49:11.796  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.796  3161  3267 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:11.806  3161  3267 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 21:49:11.806  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:11.806  6702  6755 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:11.806  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:11.806  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:11.806  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.806  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:11.806  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:11.806  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:11.806  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:11.806  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 21:49:11.806  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:11.806  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 21:49:11.806  3161  3261 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 21:49:11.806  3161  3179 D BtGatt.GattService: stopScan() - queue size =1
08-25 21:49:11.806  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.806  3161  3170 D BtGatt.GattService: unregisterClient() - clientIf=6
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:11.816  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 21:49:11.816  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:11.816  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:11.816  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:11.816  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.816  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:11.816  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:11.816  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.816  6702  6755 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:49:11.816  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:11.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:11.816  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:11.826  3161  3267 D BtGatt.ScanManager: filter size is 1
08-25 21:49:11.826  3161  3267 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:11.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:11.826  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:11.826  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:11.826  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:11.826  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:11.826  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:11.826  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:11.826  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:11.826  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 21:49:11.826  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.826  3161  3267 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:11.836  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.836  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:11.836  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 21:49:11.836  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-25 21:49:11.836  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.836  3161  3267 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 21:49:11.836  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:11.846  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:11.846  3161  3261 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 21:49:11.846  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.846  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:11.846  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:11.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:11.846  3161  3179 D BtGatt.GattService: registerClient() - UUID=e4cf27d8-e63e-4fec-8097-4be89be0ba11
,08-25 21:49:11.856  6776  6797 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 21:49:11.856  6776  6797 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 21:49:11.856  6776  6797 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 21:49:11.856  6776  6797 I Adreno-EGL: Local Branch: 
08-25 21:49:11.856  6776  6797 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 21:49:11.856  6776  6797 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 21:49:11.856  6776  6797 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 21:49:11.886  3161  3261 D BtGatt.GattService: onClientRegistered() - UUID=e4cf27d8-e63e-4fec-8097-4be89be0ba11, clientIf=6
,08-25 21:49:11.886  6702  6711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 21:49:11.886  3161  3271 D BtGatt.GattService: start scan with filters
,08-25 21:49:11.896  3161  3267 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:11.896  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:11.896  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:11.896  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:11.896  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:11.896  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:11.896  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:11.896  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 21:49:11.896  6776  6797 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 21:49:11.896  6776  6797 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 21:49:11.896  6776  6797 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 21:49:11.896  6776  6797 I Adreno-EGL: Local Branch: 
08-25 21:49:11.896  6776  6797 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 21:49:11.896  6776  6797 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 21:49:11.896  6776  6797 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 21:49:11.896  3161  3261 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 21:49:11.896  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.896  3161  3267 D BtGatt.ScanManager: allow scan with filters
08-25 21:49:11.896  3161  3267 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 21:49:11.896  3161  3267 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 21:49:11.906  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:11.906  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 21:49:11.906  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.906  3161  3267 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:11.906  3161  3267 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-25 21:49:11.906  6702  6755 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:11.906  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:11.906  6702  6755 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:11.906  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:11.906  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 21:49:11.906  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:11.916  3161  3261 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 21:49:11.916  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.916  3161  3170 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:11.916  3161  3179 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:11.916  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 21:49:11.916  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:11.916  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:11.916  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:11.926  3161  3267 D BtGatt.ScanManager: filter size is 1
,08-25 21:49:11.926  3161  3267 D BtGatt.ScanManager: delete FilterIndex - 4
08-25 21:49:11.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:11.926  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:11.926  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:11.926  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:11.926  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:11.926  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.926  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:11.926  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:11.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.926  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:11.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:11.926  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:11.926  6702  6755 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 21:49:11.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 21:49:11.926  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 21:49:11.926  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.926  3161  3267 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:11.936  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:11.936  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-25 21:49:11.936  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:11.936  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:11.936  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-25 21:49:11.936  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:11.936  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:11.936  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:11.936  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:11.936  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-25 21:49:11.936  3161  3267 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 21:49:11.936  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:49:11.936  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.946  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:11.946  3161  3261 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-25 21:49:11.946  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:11.946  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 21:49:11.946  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:11.956  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 21:49:11.956  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:11.956  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:11.956  3161  3271 D BtGatt.GattService: registerClient() - UUID=2f5e92e9-f2de-4c17-976b-f2b513d3a1a9
,08-25 21:49:11.966  1018  1356 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 21:49:11.966  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-25 21:49:11.976  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:11.976  1018  1356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:11.976  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:11.996  3161  3261 D BtGatt.GattService: onClientRegistered() - UUID=2f5e92e9-f2de-4c17-976b-f2b513d3a1a9, clientIf=6
,08-25 21:49:11.996  6702  6710 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 21:49:11.996  3161  3170 D BtGatt.GattService: start scan with filters
,08-25 21:49:11.996  3161  3267 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:11.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:11.996  1987  6775 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-25 21:49:11.996  1987  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 21:49:11.996  1987  6775 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 21:49:11.996  1987  6775 I System.out: (HTTPLog)-Thread-266-591377127: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-25 21:49:11.996  1987  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 21:49:11.996  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:11.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:11.996  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:12.006   285   971 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 21:49:12.006   285   971 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 21:49:12.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:12.006  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:12.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:12.006  1987  6775 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 21:49:12.006  1987  6775 I qtaguid : Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-25 21:49:12.006  3161  3261 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 21:49:12.006  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:12.006  3161  3267 D BtGatt.ScanManager: allow scan with filters
,08-25 21:49:12.006  3161  3267 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 21:49:12.006  3161  3267 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-25 21:49:12.006  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:12.006  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 21:49:12.006  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:12.006  3161  3267 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:12.016  3161  3267 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 21:49:12.016  6702  6755 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:12.016  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.016  6702  6755 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:12.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.016  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:12.016  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:12.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:12.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:12.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:12.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:12.016  3161  3179 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:12.016  3161  3261 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 21:49:12.016  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:12.016  3161  3271 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:12.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:12.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 21:49:12.026  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 21:49:12.026  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:12.026  3161  3267 D BtGatt.ScanManager: filter size is 1
,08-25 21:49:12.026  3161  3267 D BtGatt.ScanManager: delete FilterIndex - 5
08-25 21:49:12.026  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:12.026  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.026  6702  6755 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:12.026  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.026  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.026  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:12.026  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.026  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.026  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.026  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:12.026  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:12.026  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.026  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.026  3161  3261 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 21:49:12.026  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.026  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.026  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:12.026  3161  3267 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:12.036  6702  6755 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 21:49:12.036  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:12.036  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.036  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:12.036  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.036  3161  3261 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 21:49:12.036  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:12.036  3161  3267 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 21:49:12.036  3161  3261 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list,
08-25 21:49:12.036  3161  3261 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:12.036  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 21:49:12.036  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:12.036  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.036  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.036  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.036  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.036  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.036  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.036  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:12.046  6702  6755 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 21:49:12.046  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 21:49:12.046  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  1987  6775 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:49:12.046  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:12.046  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:49:12.046  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:49:12.046  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.046  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.046  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.046  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.046  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.046  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:12.046  6702  6755 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:49:12.046  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 21:49:12.056  6702  6755 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:12.056  6702  6755 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:12.056  6702  6755 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:12.056  6702  6755 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 21:49:12.056  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.056  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.056  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.056  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.056  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.056  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 21:49:12.056  6702  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1299)
08-25 21:49:12.056  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.056  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.056  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.056  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.056  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.056  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.056  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.056  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1299
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 21:49:12.066  6702  6755 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:12.066  6702  6755 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:49:12.066  6702  6755 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:12.066  6702  6755 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 21:49:12.066  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.066  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.066  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.066  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.066  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.066  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.066  6702  6813 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.076  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
,08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.076  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.076  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.076  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.076  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.076  6702  6813 D BluetoothSocket: connect(): myUserId = 0
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.076  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.076  6702  6813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:12.076  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 21:49:12.076  3161  3179 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 21:49:12.076  6702  6755 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:12.086  6702  6813 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 21:49:12.086  6702  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.086  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.086  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.086  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.086  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.086  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.086  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:12.086  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:12.086  6702  6755 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 21:49:12.086  6702  6755 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:12.086  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:49:12.086  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.086  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.086  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.086  6702  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.086  6702  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.086  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.086  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.086  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.086  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.086  6702  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.096  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.096  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:12.096  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:12.096  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1259bd1d not in the list
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:12.096  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:12.096  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9428b92 not in the list
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:12.096  6702  6755 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:49:12.096  6702  6755 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:49:12.096  6702  6755 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 21:49:12.096  6702  6755 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 21:49:12.096  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:12.096  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3647b024 added. We now have 2 listener(s)
08-25 21:49:12.096  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:12.106  6702  6755 D BluetoothAdapter: enable()
08-25 21:49:12.106  6702  6755 D BluetoothAdapter: enable(): BT is already enabled..!
,08-25 21:49:12.126  1018  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 21:49:12.126  1018  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 21:49:12.126  1018  1478 D SecContentProvider2: mCursor = null
,08-25 21:49:12.126  1018  1478 D WifiService: setWifiEnabled: true pid=6702, uid=10171
,08-25 21:49:12.126  1018  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 21:49:12.126  1018  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-25 21:49:12.126  1018  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:12.126  1018  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 21:49:12.126  1018  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 21:49:12.126  1018  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 21:49:12.126  1018  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 21:49:12.126  1018  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 21:49:12.136  1018  1478 D SettingsProvider: name = wifi_on
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1409278d added. We now have 3 listener(s)
08-25 21:49:12.136  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3600fd42 added. We now have 4 listener(s)
08-25 21:49:12.136  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:12.136  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ea22153 added. We now have 5 listener(s)
08-25 21:49:12.146  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:12.146  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-25 21:49:12.146  1018  1030 D WifiService: setWifiEnabled: false pid=6702, uid=10171
08-25 21:49:12.146  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 21:49:12.146  1018  1030 D SecContentProvider2: mCursor = null
08-25 21:49:12.146  1018  1030 D SettingsProvider: name = wifi_on
,08-25 21:49:12.146  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 21:49:12.156  1378  1378 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 21:49:12.156  1378  1378 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-25 21:49:12.156  6702  6755 D BluetoothAdapter: disable()
,08-25 21:49:12.156  1378  1378 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 21:49:12.156  1378  1378 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 21:49:12.156  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-25 21:49:12.166  1018  1356 D SettingsProvider: name = bluetooth_on,
,08-25 21:49:12.176  3161  3258 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-25 21:49:12.176  3161  3258 D BluetoothAdapterProperties: Setting state to 13
,08-25 21:49:12.176  3161  3258 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 21:49:12.176  1018  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 21:49:12.176  3161  3258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:12.176  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 21:49:12.176  3161  3258 D BluetoothAdapterService: updateAdapterState state is 13
08-25 21:49:12.176  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.176  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-25 21:49:12.176  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.176  3161  3161 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-25 21:49:12.176  3161  3258 D BluetoothAdapterService: Autoconnection is available ,
08-25 21:49:12.176  3161  3258 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 21:49:12.176  3161  3258 D BluetoothAdapterService: terminating service from this receiver
08-25 21:49:12.186  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2476a143, channel: 19, state: LISTENING
08-25 21:49:12.186  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2476a143, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18db83cb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@287743c0mSocket: android.net.LocalSocket@37ec88f9 impl:android.net.LocalSocketImpl@b08603e fd:FileDescriptor[74]
08-25 21:49:12.186  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37ec88f9 impl:android.net.LocalSocketImpl@b08603e fd:FileDescriptor[74]
08-25 21:49:12.186  1018  1127 E WifiNative-wlan0: do suspend true
,08-25 21:49:12.186  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:12.186  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 21:49:12.186  1018  4362 W ActivityManager: userId = 0, bbcId = -10000,
08-25 21:49:12.186  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.186  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.186  3161  3258 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 21:49:12.186  3161  3258 D BluetoothAdapterProperties: mDiscovering is false
,08-25 21:49:12.186  1018  1481 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 21:49:12.186  3161  3258 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 21:49:12.186  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.196  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
08-25 21:49:12.196  1316  1316 D BluetoothPbap: Proxy object disconnected
08-25 21:49:12.196  1316  1316 D PbapServerProfile: Bluetooth service disconnected
,08-25 21:49:12.196  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-25 21:49:12.196  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:12.196  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:12.206  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 21:49:12.206  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.206  1174  1174 D BluetoothTile:  getBluetoothState : 13
08-25 21:49:12.206  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:12.206  1878  1878 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 21:49:12.206  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:12.206  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:12.206  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:12.206  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:12.206  1018  4362 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:12.206  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:12.206  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 21:49:12.206   290   695 I WVCdm   : CdmEngine::CloseSession
08-25 21:49:12.206  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:12.206  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 21:49:12.216  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 21:49:12.216   290   695 I WVCdm   : L3 Terminate.
,08-25 21:49:12.216  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:12.216  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:12.216  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:12.216  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:12.216  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:12.216  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.226  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:12.226  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:12.226  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:12.226  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.226  3161  3261 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 21:49:12.226  3161  3261 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:12.236  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.236  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.236  3161  3258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 21:49:12.236  3161  3258 E bt-btif : HAL bt_hal_cbacks->log_collector_cb
08-25 21:49:12.236  3161  3258 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-25 21:49:12.236  3161  3258 E bt-btif : cmd socket is not created
,08-25 21:49:12.236  3161  3281 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 21:49:12.236  3161  3281 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 21:49:12.236  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 21:49:12.236  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:12.236  3161  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:12.236  3161  5182 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:49:12.236  3161  3258 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 21:49:12.246  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@76cdbec, channel: 5, state: LISTENING
08-25 21:49:12.246  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@76cdbec, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31a127a8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e3bbb5mSocket: android.net.LocalSocket@1f26424a impl:android.net.LocalSocketImpl@3ab8f5bb fd:FileDescriptor[76]
08-25 21:49:12.246  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f26424a impl:android.net.LocalSocketImpl@3ab8f5bb fd:FileDescriptor[76]
,08-25 21:49:12.246  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:12.246  3161  3161 I BtOppRfcommListener: stopping Accept Thread
08-25 21:49:12.246  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2541cad8, channel: 12, state: LISTENING
08-25 21:49:12.246  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2541cad8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18b8c6f2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23e15e31mSocket: android.net.LocalSocket@3c8e3916 impl:android.net.LocalSocketImpl@1af73297 fd:FileDescriptor[80]
08-25 21:49:12.246  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c8e3916 impl:android.net.LocalSocketImpl@1af73297 fd:FileDescriptor[80]
08-25 21:49:12.246  1018  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 21:49:12.246  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:12.246  3161  5182 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 21:49:12.246  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:12.246  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.246  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:12.256  6702  6813 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38edaf89, channel: -1, state: INIT
08-25 21:49:12.256  6702  6813 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38edaf89, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35a5ab8e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fa37fafmSocket: android.net.LocalSocket@29dedfbc impl:android.net.LocalSocketImpl@378bb45 fd:FileDescriptor[106]
08-25 21:49:12.256  6702  6813 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29dedfbc impl:android.net.LocalSocketImpl@378bb45 fd:FileDescriptor[106]
08-25 21:49:12.256  6702  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1299)
,08-25 21:49:12.256  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:12.256  3161  3161 V BluetoothOppManager: cleanUp...
,08-25 21:49:12.266  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:12.266  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.266  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 21:49:12.266  1018  4362 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
,08-25 21:49:12.266  1018  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.266  1018  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.266  1018  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.266  1018  4362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.286  6823  6823 E Zygote  : MountEmulatedStorage()
,08-25 21:49:12.286  6823  6823 E Zygote  : v2,
08-25 21:49:12.286  6823  6823 I libpersona: KNOX_SDCARD checking this for 10055
08-25 21:49:12.286  6823  6823 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:12.286  6823  6823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 21:49:12.286  1018  4362 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6823 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 21:49:12.286  6823  6823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:12.286  6823  6823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:12.316  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:12.316  6823  6823 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:12.346  6823  6823 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 21:49:12.376  6823  6823 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 21:49:12.376  6823  6823 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 21:49:12.376  6823  6823 D UserAnalysis: Create SecureDbHelper
,08-25 21:49:12.386  6823  6823 D IntelligenceServiceApplication: onCreate()
,08-25 21:49:12.386  1018  1491 I ActivityManager: Killing 6409:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-25 21:49:12.396  6823  6823 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 21:49:12.396  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 21:49:12.396  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.396  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.396  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.396  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.416  6841  6841 E Zygote  : MountEmulatedStorage(),
,08-25 21:49:12.416  6841  6841 E Zygote  : v2
08-25 21:49:12.416  6841  6841 I libpersona: KNOX_SDCARD checking this for 10105
08-25 21:49:12.416  6841  6841 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:12.416  6841  6841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:12.416  1018  1491 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6841 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-25 21:49:12.416  6823  6823 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
08-25 21:49:12.416  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-25 21:49:12.416  6841  6841 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:12.416  6841  6841 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 21:49:12.426  6823  6823 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 21:49:12.426  6841  6841 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:12.436  6841  6841 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:12.436  3161  3281 W bt-l2cap: btif_mce_execute_service enable:0
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:12.436  3161  3281 W bt-btif : ag scb idx 1 not allocated
08-25 21:49:12.436  3161  3281 W bt-btif : ag scb idx 2 not allocated
08-25 21:49:12.436  3161  3281 E bt-btif : BTA AG is already disabled, ignoring ...
,08-25 21:49:12.436  3161  3330 I bt_userial_mct: exiting userial_read_thread
08-25 21:49:12.436  3161  3330 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 21:49:12.436  3161  3261 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 21:49:12.436  3161  3283 I bt_vendor: hw_epilog_process
,08-25 21:49:12.436  3161  3261 D bt_userial_mct: userial_close
08-25 21:49:12.436  3161  3261 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 21:49:12.546   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 21:49:12.546   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:12.546  6841  6861 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 21:49:12.556   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 21:49:12.556   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:12.556  6841  6861 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 21:49:12.586  6702  6702 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.736  6841  6841 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:12.736  6841  6841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:12.746  3161  3261 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 21:49:12.746  1018  1491 I ActivityManager: Killing 6303:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-25 21:49:12.746  3161  3261 I bt_vendor: bluetooth satus is on
08-25 21:49:12.746  3161  3261 I bt_vendor: bt-vendor : resetting BT status
08-25 21:49:12.746  3161  3261 I bt_vendor: Starting hciattach daemon
08-25 21:49:12.746  3161  3261 I bt_vendor: try to set false
08-25 21:49:12.746  3161  3261 I bt_vendor: Starting hciattach daemon
08-25 21:49:12.746  3161  3261 I bt_vendor: try to set false
08-25 21:49:12.746  3161  3261 I bt_vendor: cleanup
08-25 21:49:12.746  3161  3281 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 21:49:12.746  3161  3261 I GKI_LINUX: GKI_exit_task 0 done
08-25 21:49:12.746  3161  3261 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 21:49:12.746  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:12.756  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 21:49:12.756  3161  3258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 21:49:12.756  3161  3258 D BtConfig.SecureMode: isSecureModeOn:false
08-25 21:49:12.756  3161  3258 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 21:49:12.756  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 21:49:12.756  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 21:49:12.756  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-25 21:49:12.756  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.756  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-25 21:49:12.756  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.756  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.756  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.756  3161  3161 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:49:12.756  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 21:49:12.756  3161  3161 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 21:49:12.756  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 21:49:12.756  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 21:49:12.756  3161  3161 D BtGatt.GattService: stop()
08-25 21:49:12.756  3161  3161 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 21:49:12.756  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.766  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 21:49:12.766  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.766  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.766  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 21:49:12.766  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 21:49:12.766  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 21:49:12.766  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.766  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 21:49:12.766  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.766  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.766  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 21:49:12.766  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.766  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:12.766  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 21:49:12.766  1018  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.766  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.766  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-25 21:49:12.766  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.766  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 21:49:12.766  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 21:49:12.766  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 21:49:12.776  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.776  1018  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.776  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.776  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 21:49:12.776  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 21:49:12.776  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-25 21:49:12.776  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.776  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 21:49:12.776  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.776  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.776  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:12.776  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.776  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.776  3161  3258 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.776  1018  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.776  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 21:49:12.776  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.776  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.776  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.776  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 21:49:12.776  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 21:49:12.786  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:12.786  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 21:49:12.786  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.786  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.786  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:12.786  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:12.786  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 21:49:12.786  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 21:49:12.786  3161  3258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 21:49:12.786  3161  3258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 21:49:12.796  3161  3258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 21:49:12.796  3161  3258 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 21:49:12.796  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-25 21:49:12.796  3161  3161 D HeadsetService: Received stop request...Stopping profile...
08-25 21:49:12.796  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.796  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 21:49:12.796  3161  3161 D A2dpService: Received stop request...Stopping profile...
08-25 21:49:12.796  3161  3275 D A2dpStateMachine: Exit Disconnected: -1
08-25 21:49:12.796  1316  1316 D HeadsetProfile: Bluetooth service disconnected
08-25 21:49:12.806  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.806  3161  3161 D HidService: Received stop request...Stopping profile...
08-25 21:49:12.806  3161  3161 D HidService: Stopping Bluetooth HidService
08-25 21:49:12.806  3161  3161 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 21:49:12.806  3161  3161 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 21:49:12.806  3161  3161 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:49:12.806  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.806  3161  3161 D HealthService: Received stop request...Stopping profile...
08-25 21:49:12.806  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.806  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:12.806  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 21:49:12.806  3161  3161 D PanService: Received stop request...Stopping profile...
08-25 21:49:12.806  6841  6871 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 21:49:12.806  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:12.806  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:12.816  1316  1316 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:12.816  1316  1316 D A2dpProfile: Bluetooth service disconnected
08-25 21:49:12.816  1316  1316 D BluetoothInputDevice: Proxy object disconnected
08-25 21:49:12.816  1316  1316 D HidProfile: Bluetooth service disconnected
08-25 21:49:12.816  1316  1316 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:12.816  1316  1316 D PanProfile: Bluetooth service disconnected
08-25 21:49:12.816  3161  3161 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 21:49:12.816  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:12.816  3161  3161 D SapService: Received stop request...Stopping profile...
08-25 21:49:12.816  3161  3161 D SapService: Stopping Bluetooth SapService
08-25 21:49:12.816  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:12.826  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 21:49:12.826  1316  1316 D BluetoothMap: Proxy object disconnected
08-25 21:49:12.826  1316  1316 D MapProfile: Bluetooth service disconnected
08-25 21:49:12.826  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 21:49:12.826  1316  1316 D SapProfile: Bluetooth service disconnected
,08-25 21:49:12.826  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 21:49:12.826  3161  3161 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 21:49:12.826  3161  3161 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:49:12.826  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 21:49:12.826  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 21:49:12.826  3161  3161 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 21:49:12.826  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 21:49:12.826  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:12.826  3161  3276 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-25 21:49:12.826  3161  3161 I GKI_LINUX: GKI_exit_task 2 done
08-25 21:49:12.826  3161  3161 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 21:49:12.826  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 21:49:12.826  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:12.826  1018  3339 D SSRM:n  : SIOP:: AP = 350
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:12.826  3161  3161 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 21:49:12.826  3161  3161 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 21:49:12.826  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-25 21:49:12.826  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.826  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:12.826  3161  3161 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 21:49:12.826  3161  3161 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 21:49:12.836  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-25 21:49:12.836  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 21:49:12.836  3161  3161 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-25 21:49:12.836  3161  3161 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-25 21:49:12.836  3161  3161 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 21:49:12.836  3161  3161 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 21:49:12.836  3161  3258 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 21:49:12.836  3161  3258 D BluetoothAdapterProperties: Setting state to 10
08-25 21:49:12.836  3161  3258 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 21:49:12.836  3161  3258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:12.836  3161  3258 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 21:49:12.836  3161  3258 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:12.836  3161  3258 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 21:49:12.836  3161  3258 I BluetoothAdapterState: Entering OffState
,08-25 21:49:12.836  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:12.836  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:12.846  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:12.846  1442  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:12.846  1442  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:12.846  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:12.846  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:12.846  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 21:49:12.846  1316  1326 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 21:49:12.846  1316  1326 D Bluetoothsap: Unbinding service...
,08-25 21:49:12.846  1174  1781 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:12.846  1174  1781 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:12.846  6702  6711 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:12.846  6702  6711 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:12.846  6702  6711 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 21:49:12.846  6702  6711 D BluetoothLeAdvertiser: Exit stop advertising
08-25 21:49:12.846  6702  6711 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 21:49:12.846  6702  6711 D BluetoothLeScanner: Exiting stopAllScan
,08-25 21:49:12.856  1316  1326 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1316  1334 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1316  1326 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1316  1334 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1316  1334 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:12.856  1987  2159 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1987  2159 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:12.856  3161  3271 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1427  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:12.856  1427  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:12.856  3161  3179 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:12.856  3161  3179 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:12.856  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:12.856  1316  1334 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 21:49:12.856  1456  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:12.856  1456  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:12.866  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 21:49:12.866  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 21:49:12.876  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.876  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-25 21:49:12.876  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 21:49:12.876  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:12.876  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 21:49:12.876  1174  1728 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:12.876  3161  3261 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 21:49:12.876  3161  3161 I GKI_LINUX: GKI_exit_task 1 done
08-25 21:49:12.876  3161  3161 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 21:49:12.876  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.876  1174  1174 D BluetoothTile:  getBluetoothState : 10
,08-25 21:49:12.876  3161  3161 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 21:49:12.876  1174  1728 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:12.886  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:12.886  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:12.886  1878  1878 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 21:49:12.886  1018  4362 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:12.886  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:12.886  3161  3161 I art     : System.exit called, status: 0
08-25 21:49:12.886  3161  3161 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 21:49:12.886  1987  2161 D BluetoothAdapter: 470259557: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:12.886  1987  2161 D BluetoothAdapter: 470259557: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:12.886  1018  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 21:49:12.886  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:12.886  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:12.886  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:12.886  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.896  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.896  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:12.896  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:12.896  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:12.896  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:12.896  1018  1491 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 21:49:12.896  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:12.896  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:12.896  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:12.896  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:12.896  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:12.906  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:12.906  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 21:49:12.906  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:12.906  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 21:49:12.916  1018  1491 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 21:49:12.916  1018  1491 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-25 21:49:12.916  1018  1491 W BroadcastQueue: android.os.TransactionTooLargeException
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-25 21:49:12.916  1018  1491 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 21:49:12.916  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 21:49:12.916  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.916  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.916  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:12.916  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:12.936  6878  6878 E Zygote  : MountEmulatedStorage(),
08-25 21:49:12.936  6878  6878 E Zygote  : v2
08-25 21:49:12.936  6878  6878 I libpersona: KNOX_SDCARD checking this for 1002
,08-25 21:49:12.936  6878  6878 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:12.936  1018  1491 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6878 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 21:49:12.936  6878  6878 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:12.936  6878  6878 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:12.946  6878  6878 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-25 21:49:12.946  1378  1378 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,08-25 21:49:12.946  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-25 21:49:12.946  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-25 21:49:12.946  1018  1126 D WifiP2pService: InactiveState{ what=147461 }
08-25 21:49:12.946  1018  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-25 21:49:12.946   285   975 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:12.946  1018  1126 D WifiP2pService: DefaultState{ what=147461 }
08-25 21:49:12.956  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:12.956  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 21:49:12.956  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.956  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.956  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:49:12.956  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.956  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-25 21:49:12.956  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.956  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:12.956  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:12.956  1987  3021 V NativeCrypto: Read error: ssl=0xb8119e58: I/O error during system call, Connection timed out
,08-25 21:49:12.966  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-25 21:49:12.966  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-25 21:49:12.966  1987  3021 V NativeCrypto: SSL shutdown failed: ssl=0xb8119e58: I/O error during system call, Broken pipe
08-25 21:49:12.966  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 21:49:12.966  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 21:49:12.966  1987  3021 E GCM     : Wifi connection closed with errorCode 20
,08-25 21:49:12.976  1018  1137 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-25 21:49:12.976  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:12.976  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:12.976  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.976  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:12.976  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:12.976  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:12.986  6878  6878 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:12.986  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-8ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:12.986  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-8ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:12.986  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 21:49:12.986  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:12.986  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-25 21:49:12.986  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 21:49:12.986  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-25 21:49:12.986  1018  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:12.986  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:12.986  1018  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 21:49:12.986  1018  1761 I qtaguid : Tagging socket 349 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000,
08-25 21:49:12.986  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:49:12.986  6878  6878 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:12.986  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:12.986  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 21:49:13.006  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 21:49:13.006  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 21:49:13.006  1018  1126 D WifiP2pService: P2pDisablingState
,08-25 21:49:13.006  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 21:49:13.006  1018  1126 D WifiP2pService: p2p socket connection lost
,08-25 21:49:13.006  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:13.006  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
08-25 21:49:13.006  1018  1127 E WifiNative-wlan0: do suspend true
08-25 21:49:13.006  1018  1126 D WifiP2pService: P2pDisabledState
,08-25 21:49:13.006  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.006  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:13.006  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.016  6878  6878 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 21:49:13.016  6878  6878 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 21:49:13.016  1018  1761 I qtaguid : Untagging socket 349
,08-25 21:49:13.016  1018  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 21:49:13.026  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:13.026  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 21:49:13.026  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 21:49:13.026  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:13.026  1018  1049 D WifiDisplayController: disconnect
08-25 21:49:13.026  1018  1049 D WifiDisplayController: updateConnection
08-25 21:49:13.026  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:13.026  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 21:49:13.026  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:13.026  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:13.026  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 21:49:13.026  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:13.026  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 21:49:13.046  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-25 21:49:13.046  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-25 21:49:13.046  6878  6878 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink,
,08-25 21:49:13.056  1018  1207 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:13.056  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
,08-25 21:49:13.056  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:13.056  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:13.056  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.056  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.056  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.056  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:13.066   285   975 D CommandListener: Clearing all IP addresses on wlan0,
08-25 21:49:13.066   285   971 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 21:49:13.066  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 21:49:13.066   285   971 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-25 21:49:13.066  1018  1129 V NetworkStats: updateIfacesLocked()
08-25 21:49:13.066  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.066  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:13.066  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:13.066  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:13.066  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 21:49:13.066  1378  1378 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-25 21:49:13.076  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-25 21:49:13.076  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-25 21:49:13.076  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:13.076  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:13.076  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.076  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.076  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.076  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:13.076  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:13.076  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:13.076  1018  1129 V NetworkStats: performPollLocked() took 17ms
08-25 21:49:13.076  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.086  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:13.086  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:13.086  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.086  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.086  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.086  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:13.086  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:13.086  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 21:49:13.086  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:13.086  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:13.086  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:13.086  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:13.086  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:13.086  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:13.086  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-25 21:49:13.086  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:49:13.096  4774  6764 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-25 21:49:13.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.096  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:13.096  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:13.096  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:13.096  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:13.096  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-25 21:49:13.096  1174  1174 D HotspotTile: onReceive : 0, 0
08-25 21:49:13.096  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 21:49:13.096  1174  1203 I art     : Background sticky concurrent mark sweep GC freed 1502(96KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 24MB/24MB, paused 13.410ms total 24.089ms
08-25 21:49:13.096  1174  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding GattService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding A2dpService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding HidService
,08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding HealthService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding PanService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding SapService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding SapClientService
08-25 21:49:13.096  6878  6878 D BtSettings.ProfileConfig: Adding HidDevService
08-25 21:49:13.106  6878  6878 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
08-25 21:49:13.106  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 21:49:13.106  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 21:49:13.106  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-25 21:49:13.106  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 21:49:13.106  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-25 21:49:13.106  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:49:13.106  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 21:49:13.106  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:49:13.106  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-25 21:49:13.106  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.106  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.106  1018  1031 D SettingsProvider: selectionArgs: false
08-25 21:49:13.106  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.106  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.106  1018  1031 D SettingsProvider: ret = -1
08-25 21:49:13.106  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-25 21:49:13.106  1018  1132 D Tethering: MasterInitialState.processMessage what=3
08-25 21:49:13.106  1018  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-25 21:49:13.106  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.106  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.106  1018  1480 D SettingsProvider: selectionArgs: false
08-25 21:49:13.106  1018  1480 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.106  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.106  1018  1480 D SettingsProvider: ret = -1
,08-25 21:49:13.106  1018  1124 V NetworkStats: updateIfacesLocked()
08-25 21:49:13.106  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 21:49:13.106  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:13.106  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.106  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.106  1018  1499 D SettingsProvider: selectionArgs: false
08-25 21:49:13.106  1018  1499 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.106  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.106  1018  1499 D SettingsProvider: ret = -1
08-25 21:49:13.116  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:49:13.106  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.106  1018  4362 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 21:49:13.116  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 21:49:13.106  1018  4362 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-25 21:49:13.106  1018  4362 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.106  1018  4362 D SettingsProvider: selectionArgs: false
08-25 21:49:13.106  1018  4362 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.106  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:13.106  1018  4362 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.106  1018  4362 D SettingsProvider: ret = -1
08-25 21:49:13.106  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:13.116  1018  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 21:49:13.116  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-25 21:49:13.116  1018  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.116  1018  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.116  1018  1478 D SettingsProvider: selectionArgs: false
08-25 21:49:13.116  1018  1478 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.116  1018  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.116  1018  1478 D SettingsProvider: ret = -1
08-25 21:49:13.116  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 21:49:13.116  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 21:49:13.116  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-25 21:49:13.116  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:13.116  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:13.116  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 21:49:13.116  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.116  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.116  1018  1031 D SettingsProvider: selectionArgs: false
08-25 21:49:13.116  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.116  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.116  1018  1031 D SettingsProvider: ret = -1
08-25 21:49:13.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.116  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 21:49:13.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.116  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.116  1018  1207 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 21:49:13.116  1018  1207 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.116  1018  1207 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.116  1018  1207 D SettingsProvider: selectionArgs: false
08-25 21:49:13.116  1018  1207 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.116  1018  1207 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.116  1018  1207 D SettingsProvider: ret = -1
,08-25 21:49:13.116  1018  4362 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 21:49:13.116  1018  4362 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.116  1018  4362 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.116  1018  4362 D SettingsProvider: selectionArgs: false
08-25 21:49:13.116  1018  4362 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.116  1018  4362 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.116  1018  4362 D SettingsProvider: ret = -1
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:13.116  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:13.116  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:13.116  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.116  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.116  1018  1137 D SettingsProvider: selectionArgs: false
08-25 21:49:13.116  1018  1137 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.116  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.116  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.116  1018  1137 D SettingsProvider: ret = -1
08-25 21:49:13.126  1378  1378 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 21:49:13.126  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:13.126  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.126  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.126  1018  1031 D SettingsProvider: selectionArgs: false
08-25 21:49:13.126  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.126  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.126  1018  1031 D SettingsProvider: ret = -1
,08-25 21:49:13.126  1018  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 21:49:13.126  1018  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.126  1018  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.126  1018  1481 D SettingsProvider: selectionArgs: false
08-25 21:49:13.126  1018  1481 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.126  1018  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.126  1018  1481 D SettingsProvider: ret = -1
,08-25 21:49:13.126  1018  1207 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 21:49:13.126  1018  1207 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:13.126  1018  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 21:49:13.126  1018  1207 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:13.126  1018  1207 D SettingsProvider: selectionArgs: false
08-25 21:49:13.126  1018  1207 D SettingsProvider: selectionArgs: 1002
08-25 21:49:13.126  1018  1207 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:13.126  1018  1207 D SettingsProvider: ret = -1
,08-25 21:49:13.126  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.126  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.126  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.126  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.126  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.206  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 21:49:13.206  1378  1378 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 21:49:13.206  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:13.206  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 21:49:13.216  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.216  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.216  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.216  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.216  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.226  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.226  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.226  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.226  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.226  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 21:49:13.226  1378  1378 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 21:49:13.226  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 21:49:13.226  1378  1378 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 21:49:13.226  1378  1378 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 21:49:13.226  1378  1378 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 21:49:13.226  1378  1378 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-25 21:49:13.226  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:13.226  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:13.226  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.236  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.236  1018  1132 D Tethering: InitialState.processMessage what=4
08-25 21:49:13.236  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 21:49:13.236  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:13.236  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:13.236  1018  1132 E Tethering: No numeric data
,08-25 21:49:13.236  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:49:13.236  1018  1132 D Tethering: clearTetheredNotification()
08-25 21:49:13.236  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 21:49:13.236  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.236  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:13.236  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-25 21:49:13.236  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:13.236  1174  1174 D HotspotTile: updateTetherState():false, false
,08-25 21:49:13.236  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.236  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:13.236  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.236  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:13.236  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:13.246  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.246  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:13.246  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:13.246  1018  1124 V NetworkStats: performPollLocked() took 7ms
,08-25 21:49:13.246  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:13.246  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.246  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:13.246  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 21:49:13.246  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.246  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.246  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.246  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:13.246  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 21:49:13.246  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.256  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.256  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.256  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.256  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 21:49:13.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.266  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 21:49:13.266  1987  6914 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 21:49:13.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 21:49:13.276  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 21:49:13.276  1018  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.276  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.276  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.276  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.286   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7afd7c8
08-25 21:49:13.286   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-25 21:49:13.286   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 21:49:13.286   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1213213384)
,08-25 21:49:13.296  1018  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:13.296  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:13.296  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.296  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:13.296  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:13.296  1635  1635 I Hs20UtilService: Starting #8
,08-25 21:49:13.306  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:13.316  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 21:49:13.316  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:13.316  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:13.316  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:13.316  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:13.316  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 21:49:13.316  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:13.326  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 21:49:13.326  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 21:49:13.326  1018  1207 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 21:49:13.326  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:13.326  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.326  1018  1207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.326  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.336  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 21:49:13.336  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:13.336  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 21:49:13.336  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:13.336  1018  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-25 21:49:13.336  1987  6914 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
08-25 21:49:13.336   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-25 21:49:13.336   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-25 21:49:13.336   274   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1213213384) wakelock released: 1, error no: 0
08-25 21:49:13.336   274   299 I rmt_storage: 
,08-25 21:49:13.336   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7afd7c8
08-25 21:49:13.336  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.336  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.336  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.336  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:13.356  6921  6921 E Zygote  : MountEmulatedStorage()
,08-25 21:49:13.356  6921  6921 E Zygote  : v2
08-25 21:49:13.356  6921  6921 I libpersona: KNOX_SDCARD checking this for 10064
08-25 21:49:13.356  6921  6921 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:13.356  1018  1478 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6921 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 21:49:13.356  6921  6921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:13.356  1378  1378 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 21:49:13.356  6921  6921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:13.356  6921  6921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:13.376  6921  6921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:13.376  6921  6921 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:13.386  6921  6921 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 21:49:13.396  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:13.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:13.406  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 21:49:13.426  1378  1378 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 21:49:13.426  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:13.426  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:13.426  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:13.436  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-25 21:49:13.436  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 21:49:13.436  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:13.436  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:13.436  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:13.436  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 21:49:13.436  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.436  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.436  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.436  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:13.436  1987  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:49:13.436  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:13.436  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 21:49:13.446  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:13.446  1174  1174 D HotspotTile: onReceive : 1, 0
,08-25 21:49:13.446  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:13.446  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:13.446  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:13.456  6921  6921 D FileShare-Client: Outbound.stopDelayTimer - 
08-25 21:49:13.456  1018  1356 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-25 21:49:13.456  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.456  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.456  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.456  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.476  4277  4394 I art     : Explicit concurrent mark sweep GC freed 1511(52KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 668us total 24.934ms
08-25 21:49:13.486  6936  6936 E Zygote  : MountEmulatedStorage()
08-25 21:49:13.486  6936  6936 E Zygote  : v2
08-25 21:49:13.486  6936  6936 I libpersona: KNOX_SDCARD checking this for 10065
08-25 21:49:13.486  6936  6936 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:13.486  6936  6936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:13.486  6936  6936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:13.486  1018  1356 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6936 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:49:13.486  6936  6936 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 21:49:13.496  1018  1030 I ActivityManager: Killing 6438:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-25 21:49:13.516  6936  6936 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:13.516  6936  6936 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:13.546  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.546  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.546  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.546  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.546  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-25 21:49:13.566  6936  6936 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:13.566  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.566  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.566  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.566  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.576  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.576  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.576  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-25 21:49:13.576  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-25 21:49:13.576  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:13.576  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:13.576  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:13.576  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:13.596  6954  6954 E Zygote  : MountEmulatedStorage()
,08-25 21:49:13.596  6954  6954 E Zygote  : v2
08-25 21:49:13.596  6954  6954 I libpersona: KNOX_SDCARD checking this for 10102
08-25 21:49:13.596  6954  6954 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:13.596  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 21:49:13.596  1018  1491 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6954 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 21:49:13.596  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:13.596  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 21:49:13.606  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:13.616  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-25 21:49:13.626  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:13.626  6954  6954 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:13.626  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:13.626  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:13.656  6954  6954 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 21:49:13.656  1018  1499 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-25 21:49:13.656  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 21:49:13.656  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.656  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.656  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.666  1987  1987 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=13103508-a0c2-421b-ab99-29e2edee6c50
,08-25 21:49:13.666  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 21:49:13.666  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 21:49:13.676  1018  1478 I ActivityManager: Killing 6484:com.samsung.android.sm/1000 (adj 15): empty #21
,08-25 21:49:13.706  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.716  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:13.716  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.716  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.716  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.806  1987  2152 W GCoreFlp: No location to return for getLastLocation()
,08-25 21:49:13.856  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-25 21:49:13.856  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:13.856  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.856  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.866  1018  1207 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.866  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.866  1018  1207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:13.866  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.866  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:13.866  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:13.866  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:13.866  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:13.906  1987  2155 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 21:49:13.916  4774  6899 D UdcContextInitService: registered all accounts: true
,08-25 21:49:13.916  6954  6975 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 21:49:13.916  6954  6975 I Babel_SMS: MmsConfig.loadMmsSettings
08-25 21:49:13.916  6954  6975 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 21:49:13.916  6954  6975 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 21:49:13.916  1987  2172 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-25 21:49:13.966  6954  6975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-25 21:49:13.966  6954  6975 I Babel_SMS: MmsConfig.loadFromResources
,08-25 21:49:13.966  6954  6975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 21:49:13.966  6954  6975 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 21:49:13.986  6954  6967 W art     : Suspending all threads took: 8.197ms
,08-25 21:49:13.996  1018  1046 D Tethering: interfaceRemoved wlan0
08-25 21:49:13.996  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 21:49:14.036  1018  1207 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-25 21:49:14.036  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-25 21:49:14.036  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:14.036  1018  1207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:14.036  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 21:49:14.056  6954  6954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:49:14.056  6954  6954 I Babel_Crash: startup - clean
,08-25 21:49:14.096  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:14.106  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:14.106  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:14.106  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:14.106  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:14.106  1635  1635 I Hs20UtilService: Starting #9
,08-25 21:49:14.106  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:14.106  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 21:49:14.106  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:14.106  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:14.116  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:14.116  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:14.116  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 21:49:14.116  1018  1046 D Tethering: interfaceRemoved p2p0
08-25 21:49:14.116  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 21:49:14.116  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:14.126  1018  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:14.126  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:14.126  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.126  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.126  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:14.126  1635  1635 I Hs20UtilService: Starting #10
,08-25 21:49:14.126  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:14.136  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 21:49:14.136  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:14.136  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 21:49:14.136  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:14.146  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:14.146  1018  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.146  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.146  6954  6954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 21:49:14.146  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.156  6954  6954 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 21:49:14.156  6954  6954 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 21:49:14.156  1018  1030 I art     : Explicit concurrent mark sweep GC freed 47751(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 3.986ms total 164.280ms
,08-25 21:49:14.156  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.156  6954  6954 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-25 21:49:14.156  6954  6954 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-25 21:49:14.156  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.156  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.166  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:14.166  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.166  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.166  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.166  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.166  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 21:49:14.166  6954  6954 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-25 21:49:14.166  6954  6954 W AudioCapabilities: Unsupported mime audio/x-ima
,08-25 21:49:14.166  6954  6954 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 21:49:14.176  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.176  6954  6954 W AudioCapabilities: Unsupported mime audio/evrc
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.176  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.176  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.176  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.186  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.186  6954  6954 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 21:49:14.186  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.186  6954  6954 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 21:49:14.186  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.186  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.196  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.196  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.196  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.196  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 21:49:14.196  6954  6954 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-25 21:49:14.206  6954  6954 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 21:49:14.206  6954  6954 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 21:49:14.206  1018  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:14.206  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:14.206  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.206  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:14.206  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:14.206  1635  1635 I Hs20UtilService: Starting #11
,08-25 21:49:14.206  6954  6954 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-25 21:49:14.206  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:14.216  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 21:49:14.216  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-25 21:49:14.216  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 21:49:14.216  6954  6954 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
08-25 21:49:14.216  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:14.216  6954  6954 W VideoCapabilities: Unsupported mime video/mp43
,08-25 21:49:14.226  6954  6954 W VideoCapabilities: Unsupported mime video/sorenson
,08-25 21:49:14.226  1018  1499 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 21:49:14.226  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.226  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.226  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.226  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.236  6954  6954 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 21:49:14.236  6979  6979 E Zygote  : MountEmulatedStorage()
,08-25 21:49:14.236  6979  6979 E Zygote  : v2
08-25 21:49:14.236  6979  6979 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:14.236  6979  6979 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.246  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.246  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:14.246  1018  1499 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6979 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 21:49:14.246  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.256  6954  6954 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 21:49:14.266  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:14.266  6979  6979 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.276  1987  2172 I art     : Explicit concurrent mark sweep GC freed 52507(2MB) AllocSpace objects, 9(285KB) LOS objects, 39% free, 11MB/18MB, paused 1.358ms total 76.912ms
,08-25 21:49:14.276  1987  2172 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-25 21:49:14.296  6954  6954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 21:49:14.306  6954  6954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 21:49:14.306  6979  6979 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-25 21:49:14.306  6979  6979 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 21:49:14.306  6979  6979 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 21:49:14.306  6954  6954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 21:49:14.306  6954  6954 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 21:49:14.316  1018  1030 I ActivityManager: Killing 6466:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 21:49:14.316  6954  6954 I vclib   : onServiceConnected
,08-25 21:49:14.316  6979  6979 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-25 21:49:14.316  6979  6979 I PCWCLIENTTRACE_PushUtil: sales region : global
08-25 21:49:14.326  6979  6979 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 21:49:14.326  6979  6979 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:14.326  1987  2172 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-25 21:49:14.326  1018  1491 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-25 21:49:14.326  1018  1491 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-25 21:49:14.326  6979  6995 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-25 21:49:14.326  1018  1491 I ActivityManager: Killing 6521:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 21:49:14.336  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 21:49:14.336  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.336  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.336  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.336  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.336  1782  1782 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,08-25 21:49:14.346  6997  6997 E Zygote  : MountEmulatedStorage()
,08-25 21:49:14.346  1018  1044 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6997 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-25 21:49:14.346  6997  6997 E Zygote  : v2
08-25 21:49:14.346  6997  6997 I libpersona: KNOX_SDCARD checking this for 10121
08-25 21:49:14.346  6997  6997 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.356  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:14.356  1018  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 21:49:14.356  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.356  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.356  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.356  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.356   300   300 E SMD     : DCD OFF,
08-25 21:49:14.356  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 21:49:14.356  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.366  7006  7006 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.366  7006  7006 E Zygote  : v2
08-25 21:49:14.366  7006  7006 I libpersona: KNOX_SDCARD checking this for 10031
08-25 21:49:14.366  7006  7006 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.366  7006  7006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.376  7006  7006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:14.376  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.376  1018  1478 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7006 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-25 21:49:14.376  6997  6997 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.376  7006  7006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 21:49:14.376  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-25 21:49:14.396  2473  2762 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-25 21:49:14.396  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 21:49:14.396  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.396  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.396  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.396  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:14.406  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 21:49:14.406  6997  6997 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 21:49:14.406  6997  6997 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 21:49:14.416  7028  7028 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.416  7028  7028 E Zygote  : v2
08-25 21:49:14.416  7028  7028 I libpersona: KNOX_SDCARD checking this for 10001
08-25 21:49:14.416  7028  7028 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.416  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.426  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:14.426  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7028 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:49:14.426  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.426  7006  7006 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.436  7006  7006 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:14.436  6997  6997 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:14.436  1782  1782 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-25 21:49:14.436  1782  1782 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 21:49:14.436  1782  1782 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-25 21:49:14.436  1782  1782 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-25 21:49:14.446  1018  1043 W libprocessgroup: failed to kill pid 6521: No such process
,08-25 21:49:14.446  6997  6997 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-25 21:49:14.456  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:14.456  1782  1782 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 21:49:14.456  1782  1782 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-25 21:49:14.456  7028  7028 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:14.456  6997  6997 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 21:49:14.456  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-25 21:49:14.456  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.456  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.456  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.456  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.476  7043  7043 E Zygote  : MountEmulatedStorage(),
,08-25 21:49:14.476  7043  7043 E Zygote  : v2
08-25 21:49:14.476  7043  7043 I libpersona: KNOX_SDCARD checking this for 10077
08-25 21:49:14.476  7043  7043 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.476  1018  1480 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7043 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-25 21:49:14.476  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.486  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:14.486  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.496  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-25 21:49:14.496  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.496  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.496  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.496  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.496  7006  7006 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-25 21:49:14.496   320   320 I art     : Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 24.295ms
,08-25 21:49:14.506  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:14.506  7043  7043 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.516   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.440ms
,08-25 21:49:14.536   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.707ms
,08-25 21:49:14.546  7058  7058 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.546  7058  7058 E Zygote  : v2
08-25 21:49:14.546  7058  7058 I libpersona: KNOX_SDCARD checking this for 10141
08-25 21:49:14.546  7058  7058 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.546  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.556  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:14.556  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.556  1018  1480 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7058 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-25 21:49:14.556  1018  1480 I ActivityManager: Killing 6553:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-25 21:49:14.566  1018  1480 I ActivityManager: Killing 6569:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-25 21:49:14.586  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.586  7058  7058 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.596  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-25 21:49:14.606  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.606  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.606  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.606  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.606  2756  7075 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,08-25 21:49:14.606  2756  7075 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-25 21:49:14.606  2756  7075 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-25 21:49:14.616  2756  7075 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-25 21:49:14.616  2756  7075 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-25 21:49:14.616  7058  7058 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-25 21:49:14.616  7058  7058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:49:14.616  7058  7058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 21:49:14.616  7058  7058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-25 21:49:14.626  7076  7076 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.626  7076  7076 E Zygote  : v2
08-25 21:49:14.626  7076  7076 I libpersona: KNOX_SDCARD checking this for 10032
08-25 21:49:14.626  7076  7076 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:14.626  1018  1481 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7076 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:49:14.626  7076  7076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:14.626  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-25 21:49:14.626  7076  7076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:14.626  7076  7076 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-25 21:49:14.626  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.626  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.626  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.626  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.656  7090  7090 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.656  7090  7090 E Zygote  : v2
08-25 21:49:14.656  7090  7090 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:14.656  7090  7090 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:14.656  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:14.656  1018  1481 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 21:49:14.656  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:14.656  1018  1481 I ActivityManager: Killing 6020:com.android.mms/u0a41 (adj 15): empty #21
08-25 21:49:14.656  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.676  7076  7076 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:14.676  7076  7076 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:14.676  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.696  1018  1356 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.696  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.696  7090  7090 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.736  1018  4362 D CountryDetector: No listener is left
,08-25 21:49:14.736  7076  7112 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-25 21:49:14.736  7076  7112 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-25 21:49:14.736  1018  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.746  7090  7090 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-25 21:49:14.746  1018  1137 D RCPManagerService: exchangeData() failure , invalid userId,
08-25 21:49:14.746  7076  7076 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-25 21:49:14.746  1018  1499 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 21:49:14.746  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.746  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.746  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.746  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.756  7076  7112 D SPPClientService: PushLog.txt file is not deleted.
,08-25 21:49:14.756  7076  7112 D SPPClientService: PushLog.txt file is not deleted.
,08-25 21:49:14.756  7076  7112 D SPPClientService: ============PushLog. stop!
,08-25 21:49:14.776  7115  7115 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.776  7115  7115 E Zygote  : v2
08-25 21:49:14.776  7115  7115 I libpersona: KNOX_SDCARD checking this for 10036
08-25 21:49:14.776  7115  7115 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:14.776  7115  7115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.776  1018  1499 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7115 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:49:14.776  1018  1499 I ActivityManager: Killing 6506:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-25 21:49:14.776  1018  1479 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-25 21:49:14.776  7115  7115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:14.776  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-25 21:49:14.776  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:14.776  1018  1479 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-25 21:49:14.776  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-25 21:49:14.776  7115  7115 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.806  7115  7115 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.806  7115  7115 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.816  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 21:49:14.836  7076  7125 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-25 21:49:14.856  1018  1137 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.866  1018  1479 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-25 21:49:14.866  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.866  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.866  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.866  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.866  1018  4362 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.896  7135  7135 E Zygote  : MountEmulatedStorage(),
08-25 21:49:14.896  7135  7135 E Zygote  : v2
08-25 21:49:14.896  7135  7135 I libpersona: KNOX_SDCARD checking this for 10068
08-25 21:49:14.896  7135  7135 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.896  7135  7135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.896  7135  7135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 21:49:14.896  7135  7135 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-25 21:49:14.896  7115  7115 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@35f82d01,
08-25 21:49:14.906  1018  1479 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7135 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-25 21:49:14.916  7090  7090 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-25 21:49:14.916  7115  7115 I SA      : [SSP] onCreated
,08-25 21:49:14.926  7090  7090 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-25 21:49:14.926  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:14.926  7090  7090 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 21:49:14.926  7090  7090 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-25 21:49:14.926  7135  7135 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:14.926  7090  7090 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-25 21:49:14.936  1018  1356 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-25 21:49:14.936  7135  7135 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.936  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.936  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 21:49:14.936  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.936  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.936  7115  7115 I SA      : [TPM] There is no property file
,08-25 21:49:14.946  7115  7115 I SA      : [SCU] isHaveSA() - false
,08-25 21:49:14.946  1018  1207 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 21:49:14.946  7115  7115 I SA      : [TPM] getModelProperty : null
08-25 21:49:14.946  7115  7115 I SA      : [TPM] getCSCProperty : null
,08-25 21:49:14.946  7115  7115 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-25 21:49:14.946  7115  7115 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 21:49:14.946  7115  7115 I SA      : [DM] TFT FEATURE: false
,08-25 21:49:14.946  7153  7153 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.946  7153  7153 I libpersona: KNOX_SDCARD checking this for 10008
08-25 21:49:14.946  7153  7153 E Zygote  : v2
08-25 21:49:14.946  7153  7153 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:14.956  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:14.956  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:14.956  1018  1356 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7153 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 21:49:14.956  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 21:49:14.956  7115  7115 I SA      : [DM] init START
,08-25 21:49:14.956  1018  1356 I ActivityManager: Killing 6591:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-25 21:49:14.966  1018  1499 D RCPManagerService: exchangeData() failure , invalid userId
08-25 21:49:14.966  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-25 21:49:14.966  7115  7115 I SA      : [DM] This device is not a Vodafone
,08-25 21:49:14.986  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.986  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.986  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:14.986  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:14.986  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:14.986  7153  7153 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:14.996  7169  7169 E Zygote  : MountEmulatedStorage()
08-25 21:49:14.996  7169  7169 I libpersona: KNOX_SDCARD checking this for 10009
08-25 21:49:14.996  7169  7169 E Zygote  : v2
08-25 21:49:14.996  7169  7169 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:14.996  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:15.006  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:15.006  1018  1481 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7169 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 21:49:15.006  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 21:49:15.006  7135  7135 D BadgeProvider: onCreate
08-25 21:49:15.006  1018  1481 I ActivityManager: Killing 6630:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-25 21:49:15.006  7135  7135 D BadgeProvider: DatabaseHelper
08-25 21:49:15.006  1018  1481 I ActivityManager: Killing 6613:com.sec.esdk.elm/u0a90 (adj 15): empty #22
,08-25 21:49:15.026  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:15.026  7169  7169 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:15.026  7115  7115 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-25 21:49:15.026  7115  7115 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-25 21:49:15.026  7115  7115 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-25 21:49:15.036  7135  7148 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-25 21:49:15.046  7115  7115 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-25 21:49:15.056  7115  7115 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-25 21:49:15.056  7115  7115 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-25 21:49:15.056  7115  7115 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-25 21:49:15.056  7115  7115 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75),
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-25 21:49:15.066  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-25 21:49:15.066  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-25 21:49:15.066  7115  7115 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-25 21:49:15.066  7135  7148 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-25 21:49:15.066  7135  7148 D BadgeProvider: sendNotify, [notify] : null
08-25 21:49:15.066  7135  7148 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-25 21:49:15.066  7135  7148 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-25 21:49:15.066  7135  7148 D BadgeProvider: update, [UpdateCount] : 1
,08-25 21:49:15.066  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:15.066  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:15.066  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-25 21:49:15.066  7115  7115 I SA      : [SCU] isHaveSA() - false
08-25 21:49:15.066  7115  7115 I SA      : support phone number id : false
08-25 21:49:15.066  7115  7115 I SA      : [DM] Supports Ref Jpn : true
,08-25 21:49:15.066  7115  7115 I SA      : [DM] init END
,08-25 21:49:15.066  7115  7115 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 21:49:15.076  1018  1356 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-25 21:49:15.076  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:15.076  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:15.076  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:15.076  1018  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:15.076  1483  1483 D Launcher.Model: reloadBadges entered.
,08-25 21:49:15.086  7115  7115 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-25 21:49:15.086  7115  7115 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 21:49:15.086  7187  7187 E Zygote  : MountEmulatedStorage()
08-25 21:49:15.086  7187  7187 E Zygote  : v2
08-25 21:49:15.086  7187  7187 I libpersona: KNOX_SDCARD checking this for 10110
08-25 21:49:15.086  7187  7187 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:15.096  7187  7187 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 21:49:15.096  1018  1356 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7187 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 21:49:15.096  7187  7187 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 21:49:15.096  7187  7187 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 21:49:15.096  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 21:49:15.096  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 21:49:15.096  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:15.096  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:15.096  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 21:49:15.106  7115  7115 I SA      : [SLFUCHKMGR] constructor called
,08-25 21:49:15.116  6954  7186 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 21:49:15.126  7187  7187 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:15.126  7187  7187 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:15.126  7115  7115 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-25 21:49:15.126  7115  7115 I SA      : [OR] == isSIMCardReady false ==
,08-25 21:49:15.136  7115  7115 I SA      : [SCU] == networkStateCheck == false
08-25 21:49:15.136  7115  7115 I SA      : [OR] onReceive END
,08-25 21:49:15.146  1018  1030 I ActivityManager: Killing 6453:com.android.calendar/u0a131 (adj 15): empty #21
,08-25 21:49:15.146  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:15.146  1018  1030 I ActivityManager: Killing 6645:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-25 21:49:15.156  1018  1478 I ActivityManager: Killing 5980:com.android.defcontainer/u0a3 (adj 15): empty #21,
,08-25 21:49:15.156  1018  1207 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 21:49:15.156  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 21:49:15.156  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:15.156  1018  1207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:15.156  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:15.176  4774  7205 I iu.SyncManager: SYNC; picasa accounts
,08-25 21:49:15.186  4774  4774 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-25 21:49:15.186  1018  1030 I ActivityManager: Killing 5797:com.android.vending/u0a26 (adj 15): empty #21
,08-25 21:49:15.196  2874  2874 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 21:49:15 GMT+02:00 2016
,08-25 21:49:15.206  1018  1356 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 21:49:15.206  1018  1356 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 21:49:15.206  1018  1356 D SecContentProvider2: mCursor = null
,08-25 21:49:15.206  1018  1356 D WifiService: setWifiEnabled: true pid=6702, uid=10171
08-25 21:49:15.206  1018  1356 W WifiService: Failed getting userId using ActivityManagerNative
08-25 21:49:15.206  1018  1356 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:15.206  1018  1356 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 21:49:15.206  1018  1356 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 21:49:15.206  1018  1356 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 21:49:15.206  1018  1356 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 21:49:15.206  1018  1356 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 21:49:15.206  1018  1356 W ActivityManager: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:15.206  1018  1356 D SettingsProvider: name = wifi_on
,08-25 21:49:15.216  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-25 21:49:15.216  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 21:49:15.216  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:15.216  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:15.216  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 21:49:15.216  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-25 21:49:15.216  1018  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-25 21:49:15.216  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-25 21:49:15.216  2874  2874 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 21:49:15.226  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-25 21:49:15.226  2874  2874 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 21:49:15.226  2874  2874 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 21:49:15.226  2874  2874 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-25 21:49:15.226  2874  7206 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 21:49:15.236  2874  7206 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-25 21:49:15.236  2874  7206 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-25 21:49:15.236  2874  7206 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-25 21:49:15.236  2874  2874 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 21:49:15.306  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 21:49:15.336  1018  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 21:49:15.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:15.456   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 21:49:15.456   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:15.456  7187  7211 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 21:49:15.466   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 21:49:15.466   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:15.466  7187  7211 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 21:49:15.476   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 21:49:15.476   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:15.476  7187  7212 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 21:49:15.486   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 21:49:15.486   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:15.486  7187  7212 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 21:49:15.516  7187  7187 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 21:49:15.516  7187  7187 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 21:49:15.516  7187  7187 I GAv4    :   adb logcat -s GAv4
,08-25 21:49:15.536  7187  7187 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
08-25 21:49:15.536  1018  1499 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 21:49:15.546  7187  7187 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-25 21:49:15.556  7187  7215 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 21:49:15.656  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 21:49:15.656  1018  1137 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 21:49:15.656  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 21:49:15.656  1018  1137 D BatteryService: stay LED for fully charged
,08-25 21:49:15.656  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 21:49:15.656  1018  1018 I MotionRecognitionService: Plugged
,08-25 21:49:15.656  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 21:49:15.666  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 21:49:15.666  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 21:49:15.666  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 21:49:15.676  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 21:49:15.676  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-25 21:49:15.676  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-25 21:49:15.696  1018  1046 D Tethering: interfaceAdded wlan0
,08-25 21:49:15.696  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:15.696  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:49:15.696  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:49:15.696  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:15.696  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:15.706  1018  1132 E Tethering: No numeric data
,08-25 21:49:15.706  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 21:49:15.706  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:15.706  1018  1132 D Tethering: clearTetheredNotification()
08-25 21:49:15.706  1018  1132 D Tethering: InitialState.processMessage what=4
,08-25 21:49:15.706  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:15.706  1174  1174 D HotspotTile: updateTetherState():false, false
,08-25 21:49:15.706  1018  1046 D Tethering: interfaceAdded p2p0
,08-25 21:49:15.716  1018  1132 E Tethering: No numeric data
08-25 21:49:15.716  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:15.716  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-25 21:49:15.716  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-25 21:49:15.716  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 21:49:15.716  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:15.716   285   975 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-25 21:49:15.716  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:49:15.716  1018  1132 D Tethering: clearTetheredNotification()
08-25 21:49:15.716  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:15.716  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:15.716   285   975 D SoftapController: Softap fwReload - Ok
08-25 21:49:15.716  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 21:49:15.716  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 21:49:15.716  1018  1124 V NetworkStats: performPollLocked() took 9ms
08-25 21:49:15.726  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:15.726  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:15.726  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:15.726  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-25 21:49:15.726  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:15.726  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:15.726   285   975 D CommandListener: Setting iface cfg,
08-25 21:49:15.726   285   975 D CommandListener: Trying to bring down wlan0
08-25 21:49:15.726  1018  1124 V NetworkStats: performPollLocked() took 4ms
08-25 21:49:15.726  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:15.726   285   975 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:15.726  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:15.726  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:15.726  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:15.726  1174  1174 D HotspotTile: updateTetherState():false, false
,08-25 21:49:15.726  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 21:49:15.736  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 21:49:15.736  1018  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-25 21:49:15.736  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 21:49:15.736  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:15.736  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 21:49:15.736  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:15.736  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:15.736  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:15.736  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:15.736  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:15.736  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-25 21:49:15.736  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:15.746  1174  1174 D HotspotTile: onReceive : 2, 0
,08-25 21:49:15.746  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:15.746  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:15.746  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:15.786  7226  7226 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 21:49:15.786  7226  7226 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 21:49:15.786  7226  7226 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 21:49:15.806  7226  7226 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-25 21:49:15.806   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7226
08-25 21:49:15.806   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-25 21:49:15.806  7226  7226 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 21:49:15.806  7226  7226 I wpa_supplicant: ssSupport state is = 1
08-25 21:49:15.806  7226  7226 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 21:49:15.806  7226  7226 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 21:49:15.806   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7226
08-25 21:49:15.806   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-25 21:49:15.866  1018  4362 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:15.876  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:15.876  1018  4362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 21:49:15.876  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-25 21:49:15.916  7187  7187 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-25 21:49:15.936  7187  7187 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6558-6561)
,08-25 21:49:15.936  7187  7187 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 21:49:15.946  7187  7187 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {287743c0}
,08-25 21:49:15.946  7187  7187 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 21:49:15.946  7187  7187 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 21:49:15.966  7187  7187 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-25 21:49:15.966  7187  7187 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 21:49:15.966  7187  7187 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 21:49:15.986   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
08-25 21:49:15.986  7187  7187 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 21:49:15.986  7187  7187 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 21:49:15.986  7187  7187 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 21:49:15.986  7187  7187 I Adreno-EGL: Local Branch: 
08-25 21:49:15.986  7187  7187 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 21:49:15.986  7187  7187 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 21:49:15.986  7187  7187 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-25 21:49:15.986  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-25 21:49:16.036  7226  7226 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 21:49:16.036  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 21:49:16.046  7187  7187 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 21:49:16.056  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-25 21:49:16.056   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7226
08-25 21:49:16.056   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 21:49:16.056  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 21:49:16.056  7226  7226 I wpa_supplicant: ssSupport state is = 1
08-25 21:49:16.056  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.056  7226  7226 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:16.056  7226  7226 E wpa_supplicant: SIM READ ERROR
08-25 21:49:16.056  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.056  7226  7226 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:16.056  7226  7226 E wpa_supplicant: SIM READ ERROR
08-25 21:49:16.056  7226  7226 I wpa_supplicant: Blacklist: Clear (all) 
08-25 21:49:16.056  7226  7226 I wpa_supplicant: wpa_default_ap_write_once
08-25 21:49:16.056  7226  7226 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 21:49:16.056  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.056  7226  7226 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 21:49:16.056  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.056  7226  7226 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:16.056  7226  7226 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 21:49:16.056  7187  7253 W cr.media: Requires BLUETOOTH permission
08-25 21:49:16.066  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:16.066  7187  7187 I NSApplication: Starting up...
08-25 21:49:16.066  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:16.066  1018  1481 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-25 21:49:16.066  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:16.066  1018  1137 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-25 21:49:16.066  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-25 21:49:16.076  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:16.076  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:16.076  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:16.076  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:16.086  1018  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7259 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-25 21:49:16.086  1018  1030 I ActivityManager: Killing 6823:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
08-25 21:49:16.086  7259  7259 E Zygote  : MountEmulatedStorage()
08-25 21:49:16.086  7259  7259 I libpersona: KNOX_SDCARD checking this for 10117
08-25 21:49:16.086  7259  7259 E Zygote  : v2
08-25 21:49:16.086  7259  7259 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:16.086  7259  7259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:16.096  7259  7259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:16.096  7259  7259 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 21:49:16.116  7259  7259 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:16.116  7259  7259 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:16.136  7259  7259 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 21:49:16.146  7226  7226 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 21:49:16.316  7226  7226 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 21:49:16.326  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 21:49:16.336  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 21:49:16.336   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7226
08-25 21:49:16.336   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 21:49:16.336  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 21:49:16.336  7226  7226 I wpa_supplicant: ssSupport state is = 1
,08-25 21:49:16.336  7226  7226 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 21:49:16.336  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 21:49:16.346  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-25 21:49:16.346   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7226
08-25 21:49:16.346   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-25 21:49:16.346  7226  7226 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 21:49:16.346  7226  7226 I wpa_supplicant: ssSupport state is = 1
08-25 21:49:16.346  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.346  7226  7226 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:16.346  7226  7226 E wpa_supplicant: SIM READ ERROR
08-25 21:49:16.346  7226  7226 I wpa_supplicant: wpa_default_ap_write_once
08-25 21:49:16.346  7226  7226 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 21:49:16.346  7226  7226 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 21:49:16.356  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 21:49:16.356  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:16.356  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:16.356  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 21:49:16.356  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:16.356  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:16.366  1987  2172 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-25 21:49:16.366  1987  2172 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-25 21:49:16.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:16.426  7226  7226 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-25 21:49:16.426  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 21:49:16.476  1018  1481 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-25 21:49:16.476  1018  1481 I ActivityManager: Killing 6878:com.android.bluetooth/1002 (adj 15): empty #21
,08-25 21:49:16.496  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:16.496  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:16.496  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:16.496  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:16.496  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:16.496  1635  1635 I Hs20UtilService: Starting #12
,08-25 21:49:16.496  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:16.496  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 21:49:16.496  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:16.496  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
08-25 21:49:16.496  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:16.566  7226  7226 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-25 21:49:16.566  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 21:49:16.566  7226  7226 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 21:49:16.696  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 21:49:16.696  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:16.696  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 21:49:16.736  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-25 21:49:16.736  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 21:49:16.746  7226  7226 I wpa_supplicant: HOTSPOT20_ENABLE called
08-25 21:49:16.746  7226  7226 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:16.746  7226  7226 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:16.746  7226  7226 E wpa_supplicant: SIM READ ERROR
08-25 21:49:16.746  7226  7226 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 21:49:16.756  7226  7226 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 21:49:16.766  7226  7226 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-25 21:49:16.766  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:16.766  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:16.766  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:16.766  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:16.766  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:16.766  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:16.766  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:16.766  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:16.766  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 21:49:16.776  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 21:49:16.776  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
08-25 21:49:16.776  1174  1174 D HotspotTile: onReceive : 3, 0
,08-25 21:49:16.776  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:16.776  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:16.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:16.786  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:16.786  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:16.786  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:16.786  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:16.786  1018  1127 E WifiConfigStore: Not a HS20
,08-25 21:49:16.786  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:16.786  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 21:49:16.786  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:16.796  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 21:49:16.796  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:16.796  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:16.796  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:16.796  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:16.796  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:16.796  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 21:49:16.796  7226  7226 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 21:49:16.796  7226  7226 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 21:49:16.796  7226  7226 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 21:49:16.796  7226  7226 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 21:49:16.796  7226  7226 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 21:49:16.796  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 21:49:16.796  7226  7226 I wpa_supplicant: First Scan Start
,08-25 21:49:16.796  7226  7226 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 21:49:16.796  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
08-25 21:49:16.796  1635  1635 I Hs20UtilService: Starting #13
,08-25 21:49:16.796  1635  1698 I Hs20UtilService: Message received 5011
08-25 21:49:16.796  6954  6954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:49:16.806  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:49:16.806  1018  1127 I WifiNative-HAL: startHal
08-25 21:49:16.806  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5b988c
08-25 21:49:16.806  1018  1127 I WifiNative-HAL: Could not start hal
,08-25 21:49:16.806  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 21:49:16.806  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:16.806  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
08-25 21:49:16.806  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:16.806  1018  1127 E WifiNative-wlan0: do suspend true
,08-25 21:49:16.816  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 21:49:16.816   285   975 D CommandListener: Setting iface cfg
08-25 21:49:16.816  1018  1126 D WifiP2pService: P2pEnablingState
08-25 21:49:16.816   285   975 D CommandListener: Trying to bring up p2p0
08-25 21:49:16.816  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 21:49:16.816  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:49:16.816  1018  1126 D WifiP2pService: P2p socket connection successful
08-25 21:49:16.816  1018  1126 D WifiP2pService: P2pEnabledState
,08-25 21:49:16.816  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-25 21:49:16.816  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-25 21:49:16.816  1018  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:16.816  1018  1151 I WifiNative-HAL: startHal
08-25 21:49:16.816  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e9739bc
,08-25 21:49:16.816  1018  1151 I WifiNative-HAL: Could not start hal
08-25 21:49:16.816  1018  1151 E WifiScanningService: could not start HAL
08-25 21:49:16.816  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-25 21:49:16.816  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 21:49:16.816  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-25 21:49:16.816  1018  1018 D RttService: SCAN_AVAILABLE : 3,
08-25 21:49:16.816  1018  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:16.826  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 21:49:16.826  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-25 21:49:16.826  7226  7226 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:16.826  7226  7226 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:16.826  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 21:49:16.826  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 21:49:16.826  7226  7226 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-25 21:49:16.826  1018  1127 E WifiStateMachine: Failed to set frequency band 0
08-25 21:49:16.826  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:16.826  1018  1049 D WifiDisplayController: disconnect
,08-25 21:49:16.826  1018  1049 D WifiDisplayController: updateConnection
08-25 21:49:16.826  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:16.826  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:16.826  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 21:49:16.826  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 21:49:16.826  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-25 21:49:16.826  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:16.826  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:16.836  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-25 21:49:16.836  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-25 21:49:16.836  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 21:49:16.836  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:49:16.836  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:16.836  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:16.836  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 21:49:16.836  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:16.836  1018  1127 D SecContentProvider2: mCursor = null
08-25 21:49:16.836  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 21:49:16.836  1018  1499 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:16.836  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28
08-25 21:49:16.836  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 21:49:16.836  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  secondary type: null
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  wps: 0
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  grpcapab: 0
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  devcapab: 0
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  status: 3
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  wfdInfo: null
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-25 21:49:16.836  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-25 21:49:16.846  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:16.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:16.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 21:49:16.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:16.846  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 21:49:16.846  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:16.856  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:16.856  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 21:49:16.856  6921  6921 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 21:49:16.856  6936  6936 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:16.866  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 21:49:16.866  1018  1126 D WifiP2pService: InactiveState
,08-25 21:49:16.866  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 21:49:16.866  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 21:49:16.866  7226  7226 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:16.866  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 21:49:16.866  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 21:49:16.956  1018  1479 I ActivityManager: Killing 6841:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-25 21:49:17.356   300   300 E SMD     : DCD OFF,
,08-25 21:49:17.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:18.046  7226  7226 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
08-25 21:49:18.046  7226  7226 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 21:49:18.046  7226  7226 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-25 21:49:18.046  7226  7226 I wpa_supplicant: Trying to associate with  'G700'
,08-25 21:49:18.046  7226  7226 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-25 21:49:18.056  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-25 21:49:18.056  1018  7284 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 21:49:18.066  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:18.066  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:18.166  7226  7226 E wpa_supplicant: Cmd 35605 not handled
,08-25 21:49:18.166  7226  7226 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 21:49:18.166  7226  7226 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-25 21:49:18.166  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.166  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:18.166  7226  7226 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 21:49:18.166  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:18.166  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 21:49:18.166  7226  7226 I wpa_supplicant: Associated with F4.99.3E
08-25 21:49:18.166  7226  7226 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 21:49:18.166  7226  7226 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-25 21:49:18.166  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-25 21:49:18.176  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.176  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.176  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:18.176  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 21:49:18.176  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 21:49:18.176  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-25 21:49:18.176  1018  1132 E Tethering: No numeric data
,08-25 21:49:18.176  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:49:18.176  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:18.176  1018  1132 D Tethering: clearTetheredNotification()
08-25 21:49:18.176  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:18.176  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.176  1174  1174 D HotspotTile: updateTetherState():false, false
08-25 21:49:18.186  7226  7226 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 21:49:18.186  7226  7226 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-25 21:49:18.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:18.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:18.186  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:18.186  1018  1127 D SecContentProvider2: mCursor = null
08-25 21:49:18.186  7226  7226 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 21:49:18.186  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 21:49:18.186  7226  7226 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:49:18.186  7226  7226 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 21:49:18.186  7226  7226 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-25 21:49:18.186  7226  7226 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 21:49:18.186  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 21:49:18.186  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 21:49:18.186  1018  1124 V NetworkStats: performPollLocked() took 11ms
08-25 21:49:18.186  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-25 21:49:18.186  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-25 21:49:18.186  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.196  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:18.196  1018  1127 D SecContentProvider2: mCursor = null
08-25 21:49:18.196  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.196  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.196  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 21:49:18.206  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 21:49:18.206  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 21:49:18.206  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 21:49:18.206  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:18.206  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 21:49:18.206  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:18.206  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:18.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.216  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:18.216  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:18.216  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:18.216  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:18.216  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:18.216  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:18.216  1635  1635 I Hs20UtilService: Starting #14
,08-25 21:49:18.216  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:18.226  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 21:49:18.226  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-25 21:49:18.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:18.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 21:49:18.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:18.226  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 21:49:18.226  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:18.236  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:18.246   285   975 D CommandListener: Setting iface cfg
,08-25 21:49:18.246  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 21:49:18.246  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:18.246  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:18.256  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:18.256  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:18.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.266  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:18.266  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:18.266  1018  1127 E WifiNative-wlan0: do suspend false
,08-25 21:49:18.276  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-25 21:49:18.276  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-25 21:49:18.306  1018  4362 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 21:49:18.306  1018  4362 D WifiService: setWifiEnabled: false pid=6702, uid=10171
,08-25 21:49:18.306  1018  4362 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 21:49:18.306  1018  4362 D SecContentProvider2: mCursor = null
08-25 21:49:18.306  1018  4362 D SettingsProvider: name = wifi_on
,08-25 21:49:18.316  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:18.326  1018  1127 E WifiNative-wlan0: do suspend true,
,08-25 21:49:18.346  1018  1480 I ActivityManager: Killing 6979:com.sec.pcw.device/1000 (adj 15): empty #21
,08-25 21:49:18.346  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-25 21:49:18.346  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 21:49:18.346   285   975 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:49:18.356  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:18.356  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:18.356  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.356  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.356  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.356  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.356  1018  1129 E ConnectivityService: updateNetworkInfo(),
08-25 21:49:18.356  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:49:18.356   285   975 E Netd    : no such netId 503
,08-25 21:49:18.356  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-25 21:49:18.366  1018  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-25 21:49:18.366  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 21:49:18.366  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.366  1018  1129 V NetworkStats: updateIfacesLocked()
08-25 21:49:18.366  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-25 21:49:18.366  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:18.366  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-25 21:49:18.366  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 21:49:18.366  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-25 21:49:18.366  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-25 21:49:18.366  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 21:49:18.366  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:18.366  1018  1129 V NetworkStats: performPollLocked() took 6ms
08-25 21:49:18.366  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.376  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:18.376  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 21:49:18.376  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.376  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,08-25 21:49:18.376  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:18.376  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.376  1018  1018 D RttService: SCAN_AVAILABLE : 1
,08-25 21:49:18.376  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:18.376  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.376  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.386  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-25 21:49:18.386  1018  7288 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:18.386  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 21:49:18.386  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 21:49:18.386  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-25 21:49:18.386  1018  7288 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 21:49:18.386  1018  1129 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 21:49:18.386  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-25 21:49:18.386  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:49:18.386  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:18.386  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:18.386  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 21:49:18.386  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.386  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.386  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:18.386  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:18.386  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:18.386  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:18.386  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:18.386  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 21:49:18.386  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:18.386  1635  1635 I Hs20UtilService: Starting #15
,08-25 21:49:18.386  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:18.396  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 21:49:18.396  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-25 21:49:18.396  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:18.396  1018  1049 D WifiDisplayController: disconnect
08-25 21:49:18.396  1018  1049 D WifiDisplayController: updateConnection
08-25 21:49:18.396  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:18.396  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:18.396  1018  1126 D WifiP2pService: P2pDisablingState
,08-25 21:49:18.396  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-25 21:49:18.396  1018  1126 D WifiP2pService: p2p socket connection lost
,08-25 21:49:18.406  1018  1127 E WifiNative-wlan0: do suspend true
,08-25 21:49:18.406  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 21:49:18.406  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:18.406  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:18.406  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 21:49:18.406   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
08-25 21:49:18.406  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 21:49:18.406  1018  1126 D WifiP2pService: P2pDisabledState
08-25 21:49:18.406  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:18.406  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:18.406  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:18.406  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:18.406  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 21:49:18.406  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:18.406  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 21:49:18.406  1018  4362 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:18.406  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 21:49:18.416  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 21:49:18.416  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 21:49:18.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:18.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:18.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 21:49:18.416  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 21:49:18.416  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:18.416  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:18.426  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 21:49:18.426  6921  6921 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 21:49:18.426  6936  6936 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:18.436  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-25 21:49:18.436  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-25 21:49:18.436   285   975 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:49:18.436  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:18.446  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 21:49:18.446  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.446  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.446  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.446  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.446  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 21:49:18.456  7226  7226 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-25 21:49:18.456  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:18.456  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:18.456  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.456  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.456  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.456  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:18.456  1018  4362 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:18.456  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:18.456  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:18.456  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:18.456  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:18.456  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:18.456  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:18.466  1635  1635 I Hs20UtilService: Starting #16
,08-25 21:49:18.466  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:18.466  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:18.466  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:18.466  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.466  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.466  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.466  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:18.466  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:18.466  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 21:49:18.466  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:18.466  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 21:49:18.466  1174  1174 D HotspotTile: onReceive : 0, 0
,08-25 21:49:18.466  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:18.476  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:18.476  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:18.476  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:18.476  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:18.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:18.476  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:18.476  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:18.476  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 21:49:18.476  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:18.476  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:18.476  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 21:49:18.476  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:18.476  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 21:49:18.476  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:18.486  7291  7291 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 21:49:18.486  7291  7291 I dhcpcd  : version 5.5.6 starting
,08-25 21:49:18.486  7291  7291 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 21:49:18.496  1018  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:18.496  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:18.496  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:18.496  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:18.496  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:18.496  1635  1635 I Hs20UtilService: Starting #17
08-25 21:49:18.496  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:18.496  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-25 21:49:18.496  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:18.496  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
08-25 21:49:18.496  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,08-25 21:49:18.536  7291  7291 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-25 21:49:18.536  7291  7291 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 21:49:18.536  7291  7291 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 21:49:18.536  7291  7291 I dhcpcd  : bssid match
,08-25 21:49:18.536  7291  7291 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127,
,08-25 21:49:18.586  7226  7226 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 21:49:18.626  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 21:49:18.626  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:18.626  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-25 21:49:18.626  7226  7226 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 21:49:18.636  7291  7291 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-25 21:49:18.636  7291  7291 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-25 21:49:18.656  7226  7226 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-25 21:49:18.656  7226  7226 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-25 21:49:18.656  7226  7226 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-25 21:49:18.666  7226  7226 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 21:49:18.666  7226  7226 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 21:49:18.666  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.666  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:18.666  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 21:49:18.666  1018  1132 D Tethering: InitialState.processMessage what=4
08-25 21:49:18.666  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:18.666  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:18.676  1018  1132 E Tethering: No numeric data
08-25 21:49:18.676  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.676  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:49:18.676  1018  1132 D Tethering: clearTetheredNotification()
,08-25 21:49:18.686  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.686  1018  1046 D Tethering: interfaceStatusChanged wlan0, false,
,08-25 21:49:18.686  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:18.686  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:18.686  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:18.686  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:18.686  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:18.686  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:18.686  1174  1174 D HotspotTile: updateTetherState():false, false
,08-25 21:49:18.696  1018  1124 V NetworkStats: performPollLocked() took 17ms
08-25 21:49:18.706  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.706  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.706  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:18.936  7226  7226 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 21:49:19.046  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 21:49:19.046  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:19.046  1018  1046 D Tethering: interfaceStatusChanged wlan0, false,
08-25 21:49:19.046  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:19.046  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:19.046  1018  1046 D Tethering: interfaceStatusChanged wlan0, false,
,08-25 21:49:19.056  7226  7226 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-25 21:49:19.156  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-25 21:49:19.156  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-25 21:49:19.166  6954  6954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:49:19.166  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:19.166  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:19.166  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:19.166  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:19.166  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:19.166  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:19.166  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:19.166  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 21:49:19.166  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 21:49:19.166  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:19.176  1174  1174 D HotspotTile: onReceive : 1, 0,
,08-25 21:49:19.176  1987  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-25 21:49:19.176  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:19.176  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:19.176  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:19.176  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:19.176  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:19.176  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:19.176  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:19.176  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:19.186  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 21:49:19.186  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-25 21:49:19.186  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 21:49:19.186  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:19.196  1635  1635 I Hs20UtilService: Starting #18
,08-25 21:49:19.196  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:19.476  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 7218
,08-25 21:49:19.486  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 7219
,08-25 21:49:19.486  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 7220
,08-25 21:49:19.706   285   968 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-25 21:49:19.706  1018  1046 D Tethering: interfaceRemoved wlan0,
08-25 21:49:19.706  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 21:49:19.876  1018  1046 D Tethering: interfaceRemoved p2p0
,08-25 21:49:19.876  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 21:49:20.366   300   300 E SMD     : DCD OFF,
,08-25 21:49:20.676  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 21:49:21.316  6702  6755 D BluetoothAdapter: enable(),
,08-25 21:49:21.316  1018  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 21:49:21.316  1018  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-25 21:49:21.316  1018  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:21.316  1018  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 21:49:21.316  1018  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 21:49:21.316  1018  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
,08-25 21:49:21.316  1018  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 21:49:21.316  1018  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 21:49:21.316  1018  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 21:49:21.316  1018  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:21.326  1018  1480 D SettingsProvider: name = bluetooth_on,
,08-25 21:49:21.326  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-25 21:49:21.326  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 21:49:21.336  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 21:49:21.336  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 21:49:21.336  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 21:49:21.336  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:21.336  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:21.336  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-25 21:49:21.356  7322  7322 E Zygote  : MountEmulatedStorage()
08-25 21:49:21.356  7322  7322 E Zygote  : v2
08-25 21:49:21.356  7322  7322 I libpersona: KNOX_SDCARD checking this for 1002
08-25 21:49:21.356  7322  7322 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:21.356  1018  1048 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7322 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 21:49:21.356  7322  7322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:21.366  7322  7322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:21.366  7322  7322 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:21.406  7322  7322 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:21.406  7322  7322 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:21.436  7322  7322 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 21:49:21.436  7322  7322 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 21:49:21.466  7322  7322 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding GattService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding HeadsetService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding HidService
08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding HealthService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding PanService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding SapService
08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-25 21:49:21.506  7322  7322 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 21:49:21.516  7322  7322 D BtSettings.ProfileConfig: Adding SapClientService
08-25 21:49:21.516  7322  7322 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 21:49:21.516  7322  7322 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 21:49:21.516  1018  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 21:49:21.516  1018  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1479 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1479 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1479 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 21:49:21.516  1018  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1481 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1481 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1481 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.516  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 21:49:21.516  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1030 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1030 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1030 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1207 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 21:49:21.516  1018  1207 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1207 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 21:49:21.516  1018  1207 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1207 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1207 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1207 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  4362 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 21:49:21.516  1018  4362 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 21:49:21.516  1018  4362 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  4362 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  4362 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  4362 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  4362 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 21:49:21.516  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1491 D SettingsProvider: selectionArgs: false
,08-25 21:49:21.516  1018  1491 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1491 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:21.516  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1031 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1031 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1480 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-25 21:49:21.516  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.516  1018  1480 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1480 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.516  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.516  1018  1480 D SettingsProvider: ret = -1
08-25 21:49:21.516  1018  1356 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:21.516  1018  1356 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.516  1018  1356 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 21:49:21.516  1018  1356 D SettingsProvider: selectionArgs: false
08-25 21:49:21.516  1018  1356 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.526  1018  1356 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 21:49:21.526  1018  1356 D SettingsProvider: ret = -1
08-25 21:49:21.526  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-25 21:49:21.526  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.526  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.526  1018  1499 D SettingsProvider: selectionArgs: false
,08-25 21:49:21.526  1018  1499 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.526  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.526  1018  1499 D SettingsProvider: ret = -1
08-25 21:49:21.526  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 21:49:21.526  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.526  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.526  1018  1137 D SettingsProvider: selectionArgs: false
08-25 21:49:21.526  1018  1137 D SettingsProvider: selectionArgs: 1002
,08-25 21:49:21.526  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.526  1018  1137 D SettingsProvider: ret = -1
08-25 21:49:21.526  1018  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 21:49:21.526  1018  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.526  1018  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.526  1018  1478 D SettingsProvider: selectionArgs: false
,08-25 21:49:21.526  1018  1478 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.526  1018  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.526  1018  1478 D SettingsProvider: ret = -1
,08-25 21:49:21.546  7322  7322 D BluetoothAdapterState: make
,08-25 21:49:21.546  7322  7322 I bluedroid: init
,08-25 21:49:21.556  7322  7337 I BluetoothAdapterState: Entering OffState
,08-25 21:49:21.556  7322  7322 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 21:49:21.556  7322  7322 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 21:49:21.556  7322  7322 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 21:49:21.556  7322  7322 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 21:49:21.556  7322  7322 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 21:49:21.556  7322  7322 I bluedroid: get_profile_interface socket
08-25 21:49:21.556  7322  7322 I bluedroid: get_profile_interface map_client
,08-25 21:49:21.556  7322  7322 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-25 21:49:21.566  7322  7340 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 21:49:21.566  7322  7322 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:21.566  1018  1499 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 21:49:21.566  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.566  7322  7340 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-25 21:49:21.566  7322  7340 E BluetoothServiceJni: populateRssiValuesNative
08-25 21:49:21.566  7322  7340 I bluedroid: getModelRssiValues
08-25 21:49:21.566  7322  7340 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 21:49:21.566  7322  7340 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 21:49:21.566  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:21.566  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.566  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:21.576  7322  7340 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 21:49:21.576  1018  1018 D SettingsProvider: name = bluetooth_name
,08-25 21:49:21.576  7322  7333 I bluedroid: config_hci_snoop_log
,08-25 21:49:21.576  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-25 21:49:21.576  1018  1048 D BluetoothManagerService: Ble is always on enable gatt
,08-25 21:49:21.576  1018  1048 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 21:49:21.576  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 21:49:21.576  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 21:49:21.586  7322  7322 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!,
08-25 21:49:21.586  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 21:49:21.586  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:21.586  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 21:49:21.586  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 21:49:21.596  7322  7337 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 21:49:21.596  7322  7337 D BluetoothAdapterProperties: Setting state to 11
08-25 21:49:21.596  7322  7337 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 21:49:21.596  7322  7337 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:21.596  7322  7337 D BluetoothAdapterService: updateAdapterState state is 11
,08-25 21:49:21.596  7322  7337 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:21.596  7322  7337 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 21:49:21.596  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:21.596  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-25 21:49:21.606  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 21:49:21.606  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:21.606  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-25 21:49:21.606  1878  1878 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 21:49:21.606  7322  7337 D BluetoothSecureManager: getInstant: null
,08-25 21:49:21.606  7322  7337 D BluetoothSecureManager: calling getMethod for getService
08-25 21:49:21.606  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 21:49:21.606  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 21:49:21.606  7322  7337 D BluetoothSecureManager: calling getService
08-25 21:49:21.606  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:21.616  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:21.616  7322  7337 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@b7f4656
,08-25 21:49:21.616  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:21.616  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:21.616  1018  4362 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 21:49:21.616  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 21:49:21.616  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:21.616  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.616  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:21.616  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:21.616  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:21.626  1018  1478 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 21:49:21.626  1018  1478 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 21:49:21.626  7322  7337 D BtConfig.SecureMode: isSecureModeOn:false
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 21:49:21.626  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:21.626  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 21:49:21.626  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 21:49:21.636  7322  7337 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 21:49:21.636  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 21:49:21.636  7322  7337 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:21.636  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 21:49:21.636  7322  7337 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:21.636  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 21:49:21.636  7322  7337 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:21.636  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 21:49:21.636  7322  7337 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 21:49:21.646  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:21.646  7322  7337 D BluetoothBondStateMachine: make
08-25 21:49:21.646  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 21:49:21.646  1018  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 21:49:21.646  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 21:49:21.646  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:21.646  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 21:49:21.646  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 21:49:21.646  7322  7343 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 21:49:21.646  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:21.646  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:21.646  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:21.666  7344  7344 E Zygote  : MountEmulatedStorage()
08-25 21:49:21.666  7344  7344 E Zygote  : v2
08-25 21:49:21.666  7344  7344 I libpersona: KNOX_SDCARD checking this for 10055
08-25 21:49:21.666  7344  7344 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:21.666  7344  7344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:21.666  1018  1479 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7344 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 21:49:21.666  7344  7344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:21.666  7344  7344 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 21:49:21.666  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 21:49:21.666  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.666  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-25 21:49:21.666  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.666  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:21.666  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 21:49:21.666  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 21:49:21.666  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 21:49:21.666  7322  7322 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:49:21.676  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.676  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.676  7322  7322 D BtGatt.GattService: Received start request. Starting profile...
08-25 21:49:21.676  7322  7322 D BtGatt.GattService: start()
08-25 21:49:21.676  7322  7322 D BtGatt.GattService: start()
08-25 21:49:21.676  7322  7322 I bluedroid: get_profile_interface gatt
08-25 21:49:21.676  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:21.676  7322  7322 D BtGatt.AdvertiseManager: advertise manager created
,08-25 21:49:21.676  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.676  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.676  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:21.676  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.676  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.676  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 21:49:21.676  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.676  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.676  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.676  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.676  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:21.676  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 21:49:21.676  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:21.676  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 21:49:21.686  1018  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.686  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 21:49:21.686  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.686  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.686  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:21.686  7322  7322 D BtGatt.GattService: mStartError = false
08-25 21:49:21.686  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:21.686   320   320 I art     : Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 24.828ms
,08-25 21:49:21.686  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 21:49:21.686  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 21:49:21.686  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 21:49:21.686  7322  7322 D HeadsetService: Received start request. Starting profile...
08-25 21:49:21.686  1018  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.686  7322  7322 D HeadsetService: start()
08-25 21:49:21.686  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.686  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.686  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.686  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:21.686  7322  7322 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:49:21.686  7322  7322 D HeadsetStateMachine: make
,08-25 21:49:21.696  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 21:49:21.696  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 21:49:21.696  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 21:49:21.696  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.696  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.696  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.696  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.696  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:21.696  7322  7322 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 21:49:21.696  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:21.696  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:21.696  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:21.706  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:21.706  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.706  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.706  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.706  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:21.706   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.845ms
,08-25 21:49:21.716  1018  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 21:49:21.716  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-25 21:49:21.716  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 21:49:21.716  1018  1499 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 21:49:21.716  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.716  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-25 21:49:21.716  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.716  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 21:49:21.716  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 21:49:21.716  7322  7337 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 21:49:21.716  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.716  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.716  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 21:49:21.716  7322  7322 I bluedroid: get_profile_interface handsfree
08-25 21:49:21.716  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:21.716  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 21:49:21.716  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:21.716  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:21.716  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:21.716  7344  7344 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:21.716  7344  7344 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:21.726  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:21.726  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 21:49:21.726  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 21:49:21.726  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 21:49:21.726  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 21:49:21.726   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.406ms
08-25 21:49:21.726  7322  7337 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 21:49:21.736  7322  7322 I DualScoManager: Instantiating Dual Sco Manager
08-25 21:49:21.736  7322  7322 I DualScoManager: Set HeadsetServiceHelper
08-25 21:49:21.746  7322  7322 D BluetoothAtMessage: createCMTIContentObservers
08-25 21:49:21.746  1018  1356 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 21:49:21.746  1018  1356 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:21.746  1018  1356 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:21.746  1018  1356 D SettingsProvider: selectionArgs: false
08-25 21:49:21.746  1018  1356 D SettingsProvider: selectionArgs: 1002
08-25 21:49:21.746  1018  1356 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:21.746  1018  1356 D SettingsProvider: ret = -1
08-25 21:49:21.746  7322  7355 D HeadsetStateMachine: Enter Disconnected: -2
08-25 21:49:21.746  7322  7322 D HeadsetService: mStartError = false
08-25 21:49:21.746  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:21.746  7322  7355 D HeadsetStateMachine: Clear mHeadsetBrsf
08-25 21:49:21.746  7322  7322 D A2dpService: Received start request. Starting profile...
08-25 21:49:21.746  7322  7322 D A2dpService: start()
08-25 21:49:21.756  7322  7355 D HeadsetStateMachine: map size, before remove : 0
08-25 21:49:21.756  7322  7355 D HeadsetStateMachine: map size, after remove: 0
08-25 21:49:21.756  7322  7322 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 21:49:21.756  7344  7344 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-25 21:49:21.756  7322  7322 I bluedroid: get_profile_interface avrcp
08-25 21:49:21.756  7322  7322 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 21:49:21.766  7322  7322 D Avrcp   : Initialize Media Controller
08-25 21:49:21.766  7322  7322 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-25 21:49:21.766  7322  7322 E Avrcp   : getActiveSessions
08-25 21:49:21.766  7322  7322 D Avrcp   : pick active media Controller
08-25 21:49:21.766  7322  7322 D Avrcp   : Get the active Media Controller 
08-25 21:49:21.776  7322  7322 I Avrcp   :  Updating now playing list upon AVRCP Start
08-25 21:49:21.776  7322  7366 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-25 21:49:21.776  7322  7322 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:49:21.776  7322  7322 D A2dpStateMachine: make
08-25 21:49:21.786  7322  7322 I bluedroid: get_profile_interface a2dp
08-25 21:49:21.786  7322  7368 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 21:49:21.786  7322  7322 E bt-btif : warning : media task started media_task_refcnt 1 
08-25 21:49:21.786  7322  7322 D A2dpService: mStartError = false
08-25 21:49:21.786  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:21.786  7344  7344 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-25 21:49:21.786  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-25 21:49:21.786  7322  7367 D A2dpStateMachine: Enter Disconnected: -2
08-25 21:49:21.786  7344  7344 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 21:49:21.786  7344  7344 D UserAnalysis: Create SecureDbHelper
08-25 21:49:21.786  7322  7322 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 21:49:21.796  7322  7322 D HidService: Received start request. Starting profile...
08-25 21:49:21.796  7322  7322 D HidService: start()
08-25 21:49:21.796  7322  7322 I bluedroid: get_profile_interface hidhost
08-25 21:49:21.796  7322  7322 D HidService: setHidService(): set to: null
08-25 21:49:21.796  7322  7322 D HidService: mStartError = false
08-25 21:49:21.796  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:21.796  7322  7322 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:49:21.796  7344  7344 D IntelligenceServiceApplication: onCreate()
08-25 21:49:21.796  7322  7322 D HealthService: Received start request. Starting profile...
08-25 21:49:21.796  7322  7322 D HealthService: start()
,08-25 21:49:21.796  7322  7366 D BluetoothMediaBrowser: no now playing list
,08-25 21:49:21.796  7322  7366 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 21:49:21.796  7322  7322 I bluedroid: get_profile_interface health
08-25 21:49:21.796  7322  7322 D HealthService: mStartError = false
08-25 21:49:21.796  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:21.796  7322  7322 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 21:49:21.806  7322  7322 D PanService: Received start request. Starting profile...
,08-25 21:49:21.806  7322  7322 D PanService: start()
08-25 21:49:21.806  7322  7322 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 21:49:21.806  7322  7322 I bluedroid: get_profile_interface pan
08-25 21:49:21.806  7322  7322 D PanService: mStartError = false
08-25 21:49:21.806  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:21.806  1018  1031 I ActivityManager: Killing 6997:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-25 21:49:21.806  7344  7344 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 21:49:21.816  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 21:49:21.816  7322  7322 D BluetoothMapService: Received start request. Starting profile...
08-25 21:49:21.816  7322  7322 D BluetoothMapService: start()
,08-25 21:49:21.816  7344  7344 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-25 21:49:21.816  7322  7322 D BluetoothMapService: mStartError = false
,08-25 21:49:21.816  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:21.816  7322  7322 D HeadsetStateMachine: Proxy object connected
,08-25 21:49:21.816  7322  7322 D HeadsetStateMachine: Try to query the phonestate on bind
08-25 21:49:21.816  1427  1453 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 21:49:21.816  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 21:49:21.816  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 21:49:21.816  1427  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 21:49:21.816  7322  7322 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 21:49:21.826  7344  7344 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 21:49:21.826  7322  7322 D SapService: Received start request. Starting profile...
,08-25 21:49:21.826  7322  7322 D SapService: start()
08-25 21:49:21.826  7322  7322 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-25 21:49:21.826  7322  7322 I bluedroid: get_profile_interface sap
08-25 21:49:21.826  7322  7322 D SapService: mStartError = false
,08-25 21:49:21.826  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700,
08-25 21:49:21.826  7322  7322 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-25 21:49:21.826  7322  7322 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 21:49:21.826  7322  7322 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 21:49:21.826  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 21:49:21.826  7322  7322 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 21:49:21.826  7322  7322 D BluetoothA2dp: Proxy object connected
08-25 21:49:21.826  7322  7322 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-25 21:49:21.826  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 21:49:21.826  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 21:49:21.836  7322  7355 D HeadsetStateMachine: Disconnected process message: 11
08-25 21:49:21.836  7322  7355 D HeadsetStateMachine: Disconnected process message: 18
08-25 21:49:21.836  7322  7355 D HeadsetStateMachine: Disconnected process message: 10
08-25 21:49:21.836  7322  7355 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 21:49:21.836  7322  7355 D HeadsetStateMachine: Disconnected process message: 11
,08-25 21:49:21.836  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-25 21:49:21.836  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 21:49:21.836  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 21:49:21.836  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:21.836  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:21.836  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:21.836  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:21.856  7373  7373 E Zygote  : MountEmulatedStorage()
08-25 21:49:21.856  7373  7373 I libpersona: KNOX_SDCARD checking this for 10105
08-25 21:49:21.856  7373  7373 E Zygote  : v2
08-25 21:49:21.856  7373  7373 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:21.856  7373  7373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:21.856  1018  1480 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7373 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-25 21:49:21.856  7373  7373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:21.856  7373  7373 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 21:49:21.876  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-25 21:49:21.876  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 21:49:21.886  7322  7337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-25 21:49:21.886  7322  7337 I bluedroid: enable
,08-25 21:49:21.886  7322  7388 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-25 21:49:21.886  7322  7337 I bt_hci_bdroid: init
,08-25 21:49:21.886  7322  7337 I bt_vendor: bt-vendor : init
,08-25 21:49:21.886  7322  7337 I bt_vendor: bt-vendor : get_bt_soc_type
,08-25 21:49:21.886  7322  7337 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 21:49:21.886  7322  7337 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 21:49:21.886  7322  7337 D bt_userial_mct: userial_init
,08-25 21:49:21.886  7322  7337 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 21:49:21.886  7322  7337 I bt_vendor: Starting hciattach daemon
08-25 21:49:21.886  7322  7337 I bt_vendor: try to set false
,08-25 21:49:21.896  7322  7337 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 21:49:21.896  7373  7373 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:21.896  7322  7337 I bt_vendor: Starting hciattach daemon
08-25 21:49:21.896  7322  7337 I bt_vendor: try to set true
,08-25 21:49:21.896  7373  7373 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:21.916  7393  7393 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-25 21:49:21.966  7399  7399 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 21:49:21.976  7400  7400 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 21:49:21.996  7403  7403 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 21:49:22.006  7405  7405 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 21:49:22.016  7406  7406 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 21:49:22.026  7407  7407 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 21:49:22.066   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 21:49:22.066   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:22.076  7373  7412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 21:49:22.076   258   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 21:49:22.076   258   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 21:49:22.076  7373  7412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.236  1018  4362 I ActivityManager: Killing 7006:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-25 21:49:22.226  7373  7373 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 21:49:22.226  7373  7373 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 21:49:22.236  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:22.236  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:22.276  7422  7422 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-25 21:49:22.286  7423  7423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 21:49:22.306  7373  7420 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 21:49:22.346  7322  7337 I bt_vendor: bluetooth satus is on
,08-25 21:49:22.346  7322  7390 D bt_userial_mct: userial_open(port:0)
08-25 21:49:22.346  7322  7390 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 21:49:22.356  7322  7390 I bt_vendor: Done intiailizing UART
,08-25 21:49:22.356  7322  7390 I bt_vendor: Done intiailizing UART
,08-25 21:49:22.356  7322  7390 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-25 21:49:22.356  7322  7390 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 21:49:22.356  7322  7426 D bt_userial_mct: Entering userial_read_thread()
,08-25 21:49:22.466  1018  1479 I art     : Explicit concurrent mark sweep GC freed 68223(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.380ms total 144.306ms
,08-25 21:49:22.466  1018  4362 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:22.466  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.466  1018  4362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:22.466  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 21:49:22.466  7322  7388 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 21:49:22.566  7322  7388 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 21:49:22.576  7322  7388 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42b2ed1 
,08-25 21:49:22.576  7322  7388 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42b2ed1 
,08-25 21:49:22.586  7322  7340 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 21:49:22.586  7322  7340 E bt-btif : Calling BTA_HhEnable
,08-25 21:49:22.596  7322  7340 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 21:49:22.596  7322  7340 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 21:49:22.596  7322  7340 E BluetoothServiceJni: populateRssiValuesNative
08-25 21:49:22.596  7322  7340 I bluedroid: getModelRssiValues
,08-25 21:49:22.596  7322  7340 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 21:49:22.596  7322  7340 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 21:49:22.596  1018  1018 D SettingsProvider: name = bluetooth_name
,08-25 21:49:22.596  7322  7340 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 21:49:22.606  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:22.606  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:22.616  7322  7340 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 21:49:22.616  7322  7340 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:22.616  7322  7340 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 21:49:22.616  7322  7340 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 21:49:22.616  7322  7340 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-25 21:49:22.616  7322  7340 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-25 21:49:22.616  7322  7340 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-25 21:49:22.616  7322  7340 E bt-btif : btif_sock_init: !vhci_init
08-25 21:49:22.616  7322  7340 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-25 21:49:22.616  7322  7340 D IOP_DB_BT: db_open: db_open : handle 3028140048l, read 13894 bytes onto local cache
,08-25 21:49:22.616  7322  7340 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 21:49:22.616  7322  7426 E bt_mct  : hci lib postload completed
,08-25 21:49:22.616  7322  7340 D IOP_DB_BT: db_query: result 1
08-25 21:49:22.616  7322  7340 I         : iop_db_open: iop_db_open status 0
,08-25 21:49:22.626  7322  7340 D bte_conf: Device ID record 1 : primary
,08-25 21:49:22.626  7322  7340 D bte_conf:   vendorId            = 0075
08-25 21:49:22.626  7322  7340 D bte_conf:   vendorIdSource      = 0001
08-25 21:49:22.626  7322  7340 D bte_conf:   product             = 0100
,08-25 21:49:22.626  7322  7340 D bte_conf:   version             = 0200
08-25 21:49:22.626  7322  7340 D bte_conf:   clientExecutableURL = 
08-25 21:49:22.626  7322  7340 D bte_conf:   serviceDescription  = 
,08-25 21:49:22.626  7322  7340 D bte_conf:   documentationURL    = 
08-25 21:49:22.626  7322  7340 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 21:49:22.626  7322  7340 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 21:49:22.626  7322  7337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 21:49:22.626  7322  7337 D BluetoothAdapterProperties: ScanMode =  20
08-25 21:49:22.626  7322  7337 D BluetoothAdapterProperties: State =  11
,08-25 21:49:22.626  1018  1356 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-25 21:49:22.626  7322  7337 D BluetoothAdapterProperties: Setting state to 12
08-25 21:49:22.626  7322  7337 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 21:49:22.626  7322  7340 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 21:49:22.626  7322  7340 D BluetoothAdapterProperties: Scan Mode:21
08-25 21:49:22.626  7322  7340 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:49:22.626  1018  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-25 21:49:22.626  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:22.626  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 21:49:22.626  1018  1030 D SettingsProvider: selectionArgs: false
08-25 21:49:22.626  1018  1030 D SettingsProvider: selectionArgs: 1002
08-25 21:49:22.626  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:22.626  1018  1030 D SettingsProvider: ret = -1
08-25 21:49:22.626  7322  7337 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:22.626  7322  7337 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 21:49:22.636  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:22.636  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.636  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.646  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.646  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.646  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:22.646  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.646  7322  7337 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:22.646  7322  7337 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 21:49:22.646  7322  7337 D BluetoothAdapterService: starting service from this receiver
,08-25 21:49:22.646  1018  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:22.646  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.646  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.646  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.656  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.656  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.656  7322  7333 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.656  7322  7333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.656  1442  1455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:22.656  1442  1455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.656  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 21:49:22.656  7322  7337 I BluetoothAdapterState: Entering On State from state = 11
,08-25 21:49:22.656  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:22.656  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.656  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:22.656  1427  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.666  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.666  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:22.666  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 21:49:22.666  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.676  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:22.676  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.676  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:22.676  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.676  1427  6978 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 21:49:22.676  7322  7322 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 21:49:22.676  1316  1326 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 21:49:22.676  1316  1326 D Bluetoothsap: Binding service...
,08-25 21:49:22.676  1316  1326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 21:49:22.686  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-25 21:49:22.686  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.686  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.686  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.686  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.686  1316  1326 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 21:49:22.686  1174  1193 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.686  1174  1193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.696  1316  6874 D BluetoothPan: Binding service...
,08-25 21:49:22.696  7322  7322 I BluetoothPbapService: Handler(): got msg=1
,08-25 21:49:22.696  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 21:49:22.696  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 21:49:22.696  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.696  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.696  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.696  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.696  7322  7432 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 21:49:22.706  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object connected,
08-25 21:49:22.706  1316  1316 D SapProfile: Bluetooth service connected
08-25 21:49:22.706  1316  1316 D Bluetoothsap: getConnectedDevices()
,08-25 21:49:22.706  6702  6711 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.706  6702  6711 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.706  1456  2455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.706  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:22.706  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.706  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.716  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:22.716  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-25 21:49:22.716  1316  1316 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:22.716  1316  1316 D PanProfile: Bluetooth service connected
08-25 21:49:22.716  1456  2455 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:22.716  1316  6874 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 21:49:22.716  7322  7432 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 21:49:22.716  7322  7432 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:22.716  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-25 21:49:22.716  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.716  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.716  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.716  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.716  7322  7432 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-25 21:49:22.716  1316  1326 D BluetoothMap: onBluetoothStateChange: up=true
08-25 21:49:22.716  7322  7432 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:22.716  1316  1316 D BluetoothInputDevice: Proxy object connected
08-25 21:49:22.716  7322  7432 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 21:49:22.716  7322  7432 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c0fe9a
08-25 21:49:22.716  7322  7432 D BluetoothSocket: channel: 19
,08-25 21:49:22.716  1316  1316 D HidProfile: Bluetooth service connected
08-25 21:49:22.716  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-25 21:49:22.716  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 21:49:22.716  7322  7432 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 21:49:22.716  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.726  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.726  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.726  7373  7384 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.726  7373  7384 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.726  1316  1334 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 21:49:22.726  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-25 21:49:22.726  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.726  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.726  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.726  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 21:49:22.726  1316  1316 D BluetoothMap: Proxy object connected
,08-25 21:49:22.726  1316  1316 D MapProfile: Bluetooth service connected
08-25 21:49:22.726  1316  1316 D BluetoothMap: getConnectedDevices()
,08-25 21:49:22.736  1316  1326 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.736  1316  1326 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.736  1987  2010 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:22.736  1987  2010 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.736  1427  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:22.736  1427  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:22.736  1427  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.736  1316  1316 D BluetoothPbap: Proxy object connected
08-25 21:49:22.736  1316  1316 D PbapServerProfile: Bluetooth service connected
,08-25 21:49:22.736  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 21:49:22.736  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.736  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.736  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:22.736  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.736  1427  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:22.746  1427  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.746  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:22.746  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.746  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.746  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.746  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.746  1427  6978 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:22.746  1316  1334 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.746  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:22.746  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:22.756  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.756  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.756  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.756  1316  1316 D HeadsetProfile: Bluetooth service connected
,08-25 21:49:22.756  1316  1334 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 21:49:22.756  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:22.756  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 21:49:22.756  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 21:49:22.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 21:49:22.756  1316  1326 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:49:22.756  1018  1018 D BluetoothA2dp: Proxy object connected
,08-25 21:49:22.756  1316  1326 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:22.756  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 21:49:22.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 21:49:22.756  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.756  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.756  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.756  7322  7341 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:49:22.756  1018  1048 D BluetoothPan: Binding service...
08-25 21:49:22.756  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 21:49:22.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.756  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:22.756  1456  2455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:22.756  1456  2455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 21:49:22.756  1316  1316 D BluetoothA2dp: Proxy object connected
08-25 21:49:22.756  1316  1316 D A2dpProfile: Bluetooth service connected
,08-25 21:49:22.756  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 21:49:22.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 21:49:22.766  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:22.766  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-25 21:49:22.766  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 21:49:22.766  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3640a7b6, true
,08-25 21:49:22.766  1174  1174 D BluetoothTile:  onBluetoothStateChange:
08-25 21:49:22.766  1427  1427 D BluetoothHeadset: registerMessageListener
08-25 21:49:22.766  1878  1878 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 21:49:22.766  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:22.766  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 21:49:22.766  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-25 21:49:22.776  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null,
,08-25 21:49:22.776  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:22.776  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:22.776  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:22.776  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:22.776  7322  7431 D HeadsetService: registerMessageListener
,08-25 21:49:22.776  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:22.776  7322  7431 D HeadsetService: registerMessageListener
08-25 21:49:22.776  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.776  7322  7355 D HeadsetStateMachine: Disconnected process message: 70
08-25 21:49:22.786  7322  7355 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@18db83cb
08-25 21:49:22.786  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 21:49:22.786  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 21:49:22.786  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:22.786  1018  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 21:49:22.786  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 21:49:22.786  1018  1356 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-25 21:49:22.786  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.786  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:22.786  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:22.786  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-25 21:49:22.786  1316  1316 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 21:49:22.786  1316  1316 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 21:49:22.786  1316  1316 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 21:49:22.786  1316  1316 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-25 21:49:22.786  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 21:49:22.786  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-25 21:49:22.786  7322  7434 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 21:49:22.796  7322  7355 D HeadsetStateMachine: Disconnected process message: 9
,08-25 21:49:22.796  7322  7355 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 21:49:22.796  7322  7434 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 21:49:22.796  7322  7434 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:22.796  7322  7434 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-25 21:49:22.796  7322  7434 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:22.796  7322  7434 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 21:49:22.796  7322  7434 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31a127a8
08-25 21:49:22.796  7322  7434 D BluetoothSocket: channel: 5
,08-25 21:49:22.806  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:22.806  1018  4362 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 21:49:22.806  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.806   290   804 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-25 21:49:22.806   290   804 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 21:49:22.806   290   804 V voice   : voice_set_parameters: exit with code(-2)
,08-25 21:49:22.806   290   804 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 21:49:22.806   290   804 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 21:49:22.806   290   804 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 21:49:22.806   290   804 V audio_hw_primary: adev_set_parameters: exit
,08-25 21:49:22.816  7322  7355 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 21:49:22.816  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.816  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.816  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:22.826  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:22.826  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:22.826  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:22.826  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 21:49:22.836  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:22.836  7322  7322 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 21:49:22.836  1018  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:22.836  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.836  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.836  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:22.836  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:22.856  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:22.856  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:22.856  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 21:49:22.856  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:22.856  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:22.856  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:22.866  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:22.866  1987  7440 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 21:49:22.866  1018  3339 D SSRM:n  : SIOP:: AP = 340
,08-25 21:49:22.866  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:22.866  1018  1207 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 21:49:22.866  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.866  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:22.866  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:22.886  7322  7444 D BluetoothSocket: bindListen(): myUserId = 0
08-25 21:49:22.886  7322  7444 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:22.886  7322  7444 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-25 21:49:22.886  7322  7444 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:22.886  7322  7444 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-25 21:49:22.886  7322  7444 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18b8c6f2
,08-25 21:49:22.886  7322  7444 D BluetoothSocket: channel: 12
08-25 21:49:22.886  7322  7444 I BtOppRfcommListener: Accept thread started.
,08-25 21:49:22.896  1018  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:22.896  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:22.896  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:22.896  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:22.906  1987  7440 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 21:49:23.366   300   300 E SMD     : DCD OFF,
,08-25 21:49:24.336  6702  6755 D BluetoothAdapter: disable()
,08-25 21:49:24.336  1018  1499 D SettingsProvider: name = bluetooth_on
,08-25 21:49:24.346  7322  7337 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-25 21:49:24.346  7322  7337 D BluetoothAdapterProperties: Setting state to 13
08-25 21:49:24.346  7322  7337 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 21:49:24.346  7322  7337 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:24.346  7322  7337 D BluetoothAdapterService: updateAdapterState state is 13
08-25 21:49:24.346  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:24.346  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 21:49:24.346  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:24.346  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:24.346  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:24.346  7322  7322 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-25 21:49:24.346  7322  7322 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2476a143, channel: 19, state: LISTENING
08-25 21:49:24.346  7322  7322 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2476a143, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c0fe9a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@287743c0mSocket: android.net.LocalSocket@37ec88f9 impl:android.net.LocalSocketImpl@b08603e fd:FileDescriptor[74]
08-25 21:49:24.346  7322  7322 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37ec88f9 impl:android.net.LocalSocketImpl@b08603e fd:FileDescriptor[74]
,08-25 21:49:24.346  7322  7337 D BluetoothAdapterService: Autoconnection is available 
,08-25 21:49:24.346  7322  7337 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 21:49:24.346  7322  7337 D BluetoothAdapterService: terminating service from this receiver
,08-25 21:49:24.356  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 21:49:24.356  1316  1316 D BluetoothPbap: Proxy object disconnected
08-25 21:49:24.356  1316  1316 D PbapServerProfile: Bluetooth service disconnected
,08-25 21:49:24.356  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:24.356  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:24.356  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:24.356  7322  7337 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 21:49:24.356  7322  7337 D BluetoothAdapterProperties: mDiscovering is false
,08-25 21:49:24.356  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 21:49:24.356  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:24.356  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-25 21:49:24.366  7322  7337 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 21:49:24.366  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-25 21:49:24.366  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 21:49:24.366  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:24.376  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-25 21:49:24.376  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-25 21:49:24.376  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null,
08-25 21:49:24.376  1878  1878 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-25 21:49:24.376  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 21:49:24.376  1018  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:24.376  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:24.376  1018  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 21:49:24.386  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:24.386  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 21:49:24.386  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:24.386  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:24.386  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:24.386  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:24.386  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:24.386  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:24.386  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:24.386  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:24.386  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:24.386  6702  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:24.386  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:24.386  7322  7340 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 21:49:24.386  7322  7340 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:24.396  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:24.396  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:24.396  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:24.406  1018  1479 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 21:49:24.406  7322  7337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 21:49:24.406  7322  7337 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 21:49:24.406  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:24.406  7322  7337 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-25 21:49:24.406  7322  7337 E bt-btif : cmd socket is not created
,08-25 21:49:24.406  7322  7444 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:49:24.406  7322  7337 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 21:49:24.406  7322  7388 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 21:49:24.406  7322  7388 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 21:49:24.406  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:24.406  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:24.406  7322  7388 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 21:49:24.406  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:24.406  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:24.406  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:24.426  7322  7322 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@76cdbec, channel: 5, state: LISTENING
08-25 21:49:24.426  7322  7322 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@76cdbec, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31a127a8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e3bbb5mSocket: android.net.LocalSocket@1f26424a impl:android.net.LocalSocketImpl@3ab8f5bb fd:FileDescriptor[76]
08-25 21:49:24.426  7322  7322 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f26424a impl:android.net.LocalSocketImpl@3ab8f5bb fd:FileDescriptor[76]
08-25 21:49:24.426  7322  7322 I BtOppRfcommListener: stopping Accept Thread
08-25 21:49:24.426  7322  7322 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2541cad8, channel: 12, state: LISTENING
08-25 21:49:24.426  7322  7322 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2541cad8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18b8c6f2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23e15e31mSocket: android.net.LocalSocket@3c8e3916 impl:android.net.LocalSocketImpl@1af73297 fd:FileDescriptor[79]
08-25 21:49:24.426  7322  7322 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c8e3916 impl:android.net.LocalSocketImpl@1af73297 fd:FileDescriptor[79]
,08-25 21:49:24.426  1316  1316 D DockEventReceiver: finishStartingService: stopping service
08-25 21:49:24.426  7322  7444 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 21:49:24.426  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:24.436  7322  7322 V BluetoothOppManager: cleanUp...,
08-25 21:49:24.436  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:24.436  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 21:49:24.456  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:24.466  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:49:24.606  7322  7388 W bt-btif : ag scb idx 1 not allocated
08-25 21:49:24.606  7322  7388 W bt-btif : ag scb idx 2 not allocated
08-25 21:49:24.606  7322  7388 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 21:49:24.606  7322  7426 I bt_userial_mct: exiting userial_read_thread
08-25 21:49:24.606  7322  7426 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 21:49:24.606  7322  7340 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 21:49:24.606  7322  7390 I bt_vendor: hw_epilog_process
08-25 21:49:24.606  7322  7340 D bt_userial_mct: userial_close
08-25 21:49:24.606  7322  7340 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 21:49:25.046  7322  7340 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 21:49:25.046  7322  7340 I bt_vendor: bluetooth satus is on
08-25 21:49:25.046  7322  7340 I bt_vendor: bt-vendor : resetting BT status
08-25 21:49:25.046  7322  7340 I bt_vendor: Starting hciattach daemon
08-25 21:49:25.046  7322  7340 I bt_vendor: try to set false
,08-25 21:49:25.046  7322  7340 I bt_vendor: Starting hciattach daemon
08-25 21:49:25.046  7322  7340 I bt_vendor: try to set false
,08-25 21:49:25.046  7322  7340 I bt_vendor: cleanup
,08-25 21:49:25.046  7322  7388 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 21:49:25.046  7322  7340 I GKI_LINUX: GKI_exit_task 0 done
,08-25 21:49:25.046  7322  7340 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 21:49:25.046  7322  7337 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 21:49:25.046  7322  7337 D BtConfig.SecureMode: isSecureModeOn:false
08-25 21:49:25.046  7322  7337 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 21:49:25.046  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 21:49:25.046  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 21:49:25.046  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 21:49:25.046  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:25.046  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.056  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:25.056  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.056  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.056  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-25 21:49:25.056  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 21:49:25.056  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 21:49:25.056  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:25.056  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.056  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.056  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:25.056  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.056  7322  7322 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:49:25.056  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 21:49:25.056  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 21:49:25.056  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 21:49:25.056  7322  7322 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 21:49:25.056  7322  7322 D BtGatt.GattService: stop()
08-25 21:49:25.066  7322  7322 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 21:49:25.066  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 21:49:25.066  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.066  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.066  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.066  1018  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:25.066  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:25.066  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 21:49:25.066  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:25.066  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 21:49:25.066  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:25.066  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 21:49:25.066  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.066  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.066  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.066  7322  7322 D HeadsetService: Received stop request...Stopping profile...
08-25 21:49:25.066  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 21:49:25.066  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 21:49:25.066  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 21:49:25.066  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.066  1018  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:25.066  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 21:49:25.066  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-25 21:49:25.066  1316  1316 D HeadsetProfile: Bluetooth service disconnected
,08-25 21:49:25.066  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.066  1018  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.066  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 21:49:25.076  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 21:49:25.076  1018  4362 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:25.076  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.076  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.076  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.076  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:25.076  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:25.076  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:25.076  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.076  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:25.076  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.076  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 21:49:25.076  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 21:49:25.076  7322  7337 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 21:49:25.076  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:25.086  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.086  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:25.086  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.086  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
08-25 21:49:25.086  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:25.086  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 21:49:25.086  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 21:49:25.086  7322  7337 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 21:49:25.086  7322  7337 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 21:49:25.086  7322  7337 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 21:49:25.086  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-25 21:49:25.086  7322  7322 D A2dpService: Received stop request...Stopping profile...
08-25 21:49:25.086  7322  7367 D A2dpStateMachine: Exit Disconnected: -1
,08-25 21:49:25.086  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.096  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-25 21:49:25.096  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 21:49:25.096  7322  7322 D HidService: Received stop request...Stopping profile...
08-25 21:49:25.096  7322  7322 D HidService: Stopping Bluetooth HidService
08-25 21:49:25.096  7322  7322 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 21:49:25.096  7322  7322 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 21:49:25.096  7322  7322 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:49:25.096  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.096  1316  1316 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:25.096  1316  1316 D A2dpProfile: Bluetooth service disconnected
,08-25 21:49:25.096  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 21:49:25.096  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 21:49:25.096  7322  7322 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 21:49:25.096  1316  1316 D BluetoothInputDevice: Proxy object disconnected
08-25 21:49:25.096  1316  1316 D HidProfile: Bluetooth service disconnected
,08-25 21:49:25.096  7322  7322 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 21:49:25.096  7322  7322 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 21:49:25.096  7322  7322 D HealthService: Received stop request...Stopping profile...
,08-25 21:49:25.096  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.096  7322  7322 D PanService: Received stop request...Stopping profile...
,08-25 21:49:25.096  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.106  7322  7322 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 21:49:25.106  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.106  7322  7322 D SapService: Received stop request...Stopping profile...
08-25 21:49:25.106  7322  7322 D SapService: Stopping Bluetooth SapService
08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:25.106  1316  1316 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:25.106  1316  1316 D PanProfile: Bluetooth service disconnected
08-25 21:49:25.106  1316  1316 D BluetoothMap: Proxy object disconnected
,08-25 21:49:25.106  1316  1316 D MapProfile: Bluetooth service disconnected
08-25 21:49:25.106  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 21:49:25.106  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 21:49:25.106  7322  7322 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 21:49:25.106  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 21:49:25.106  7322  7368 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 21:49:25.106  1316  1316 D SapProfile: Bluetooth service disconnected
08-25 21:49:25.106  7322  7322 I GKI_LINUX: GKI_exit_task 2 done
08-25 21:49:25.106  7322  7322 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 21:49:25.106  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 21:49:25.106  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:25.106  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 21:49:25.106  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:25.106  7322  7322 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:25.106  7322  7322 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 21:49:25.106  7322  7322 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 21:49:25.116  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-25 21:49:25.116  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:25.116  7322  7322 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:25.116  7322  7322 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 21:49:25.116  7322  7322 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 21:49:25.116  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-25 21:49:25.116  7322  7322 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 21:49:25.116  7322  7322 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-25 21:49:25.116  7322  7322 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-25 21:49:25.116  7322  7322 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##,
08-25 21:49:25.116  7322  7322 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-25 21:49:25.116  7322  7337 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 21:49:25.116  7322  7337 D BluetoothAdapterProperties: Setting state to 10
08-25 21:49:25.116  7322  7337 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 21:49:25.116  7322  7337 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:25.116  7322  7337 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 21:49:25.116  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.116  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:25.116  7322  7337 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:25.116  7322  7337 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 21:49:25.116  7322  7337 I BluetoothAdapterState: Entering OffState
,08-25 21:49:25.116  7322  7341 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.116  7322  7341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 21:49:25.116  1442  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.116  1442  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.116  1316  1334 D Bluetoothsap: onBluetoothStateChange: up=false
,08-25 21:49:25.116  1316  1334 D Bluetoothsap: Unbinding service...
,08-25 21:49:25.126  1174  2370 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.126  1174  2370 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.126  6702  6711 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.126  6702  6711 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.126  6702  6711 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 21:49:25.126  6702  6711 D BluetoothLeAdvertiser: Exit stop advertising
08-25 21:49:25.126  6702  6711 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 21:49:25.126  6702  6711 D BluetoothLeScanner: Exiting stopAllScan
,08-25 21:49:25.126  1316  6874 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 21:49:25.126  1316  1334 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 21:49:25.126  7373  7391 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:25.126  7373  7391 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.126  1316  1326 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 21:49:25.126  1316  6874 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.126  1316  6874 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.126  1987  2008 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:25.126  1987  2008 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.126  1427  6978 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 21:49:25.126  1427  6978 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.136  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 21:49:25.136  1316  1326 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 21:49:25.136  7322  7336 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 21:49:25.136  1456  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 21:49:25.136  1456  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 21:49:25.136  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 21:49:25.136  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 21:49:25.146  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:25.146  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-25 21:49:25.146  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 21:49:25.146  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:25.146  1174  1728 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:25.146  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 21:49:25.146  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-25 21:49:25.146  1174  1728 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:25.146  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-25 21:49:25.146  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF,
08-25 21:49:25.146  1174  1174 D BluetoothAdapter: 1031433123: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:25.146  1018  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 21:49:25.146  1878  1878 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 21:49:25.146  1018  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 21:49:25.156  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 21:49:25.156  1987  2161 D BluetoothAdapter: 470259557: getState() :  mService = null. Returning STATE_OFF
08-25 21:49:25.156  1987  2161 D BluetoothAdapter: 470259557: getState() :  mService = null. Returning STATE_OFF
,08-25 21:49:25.156  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:25.156  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:25.156  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:25.156  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:25.156  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.156  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.156  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:25.156  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:25.166  7322  7340 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 21:49:25.166  7322  7322 I GKI_LINUX: GKI_exit_task 1 done
08-25 21:49:25.166  7322  7322 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 21:49:25.166  7322  7322 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 21:49:25.166  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:25.166  1018  1207 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 21:49:25.166  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:25.166  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:25.166  1018  1207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:25.166  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:25.166  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:25.166  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:25.176  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:25.176  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 21:49:25.186  7322  7322 I art     : System.exit called, status: 0
,08-25 21:49:25.186  7322  7322 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 21:49:25.276  1018  1030 I ActivityManager: Process com.android.bluetooth (pid 7322)(adj 0) has died(44,719)
,08-25 21:49:25.286  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:25.296  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-25 21:49:25.296  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:25.296  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-25 21:49:25.296  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:25.296  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:25.296  1987  7459 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 21:49:25.306  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:25.306  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:25.316  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:25.316  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:25.316  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:25.326  1987  7459 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 21:49:25.716  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 21:49:25.716  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 21:49:25.716  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 21:49:25.716  1018  1030 D BatteryService: stay LED for fully charged
,08-25 21:49:25.716  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 21:49:25.716  1018  1018 I MotionRecognitionService: Plugged
,08-25 21:49:25.716  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 21:49:25.726  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 21:49:25.726  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 21:49:25.726  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 21:49:25.726  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 21:49:25.746  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 21:49:25.746  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-25 21:49:25.746  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:25.746  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:25.746  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:26.366   300   300 E SMD     : DCD OFF
,08-25 21:49:27.336  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:27.346  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:27.386  1018  1307 E Watchdog: !@Sync 4
,08-25 21:49:27.496  1018  1051 I PowerManagerService: [PWL] Off : 75s ago
,08-25 21:49:27.496  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-25 21:49:27.496  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-25 21:49:27.496  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=14380)
,08-25 21:49:28.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 21:49:29.366   300   300 E SMD     : DCD OFF,
,08-25 21:49:29.416   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:30.346  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:30.346  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fd4f29a added. We now have 6 listener(s)
08-25 21:49:30.346  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:30.346  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:30.346  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cb267cb added. We now have 7 listener(s)
08-25 21:49:30.346  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:30.346  6702  6755 I System.out: IsBluetoothEnabled
,08-25 21:49:30.356  6702  6755 D BluetoothAdapter: disable()
,08-25 21:49:30.356  1018  1491 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-25 21:49:30.356  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:30.356  6702  6755 D BluetoothAdapter: enable()
,08-25 21:49:30.366  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 21:49:30.366  1018  1030 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 21:49:30.366  1018  1030 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 21:49:30.366  1018  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 21:49:30.366  1018  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:30.366  1018  1030 D SettingsProvider: name = bluetooth_on
,08-25 21:49:30.366  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 21:49:30.366  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:30.366  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 21:49:30.366  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 21:49:30.376  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:30.376  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:30.376  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:30.376  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:30.386  7465  7465 E Zygote  : MountEmulatedStorage()
,08-25 21:49:30.386  7465  7465 I libpersona: KNOX_SDCARD checking this for 1002
08-25 21:49:30.386  7465  7465 E Zygote  : v2
08-25 21:49:30.386  7465  7465 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:30.386  7465  7465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:30.386  1018  1048 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7465 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 21:49:30.386  7465  7465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 21:49:30.396  7465  7465 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 21:49:30.406   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:30.416  7465  7465 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:30.416  7465  7465 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:30.436  7465  7465 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 21:49:30.436  7465  7465 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 21:49:30.466  7465  7465 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding GattService
,08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding A2dpService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding HidService
,08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding HealthService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding PanService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding SapService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding SapClientService
08-25 21:49:30.506  7465  7465 D BtSettings.ProfileConfig: Adding HidDevService
08-25 21:49:30.506  7465  7465 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 21:49:30.506  1018  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 21:49:30.506  1018  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.506  1018  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.506  1018  1478 D SettingsProvider: selectionArgs: false
08-25 21:49:30.506  1018  1478 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.506  1018  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.506  1018  1478 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-25 21:49:30.516  1018  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1481 D SettingsProvider: selectionArgs: false
08-25 21:49:30.516  1018  1481 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  1481 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 21:49:30.516  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1480 D SettingsProvider: selectionArgs: false
08-25 21:49:30.516  1018  1480 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  1480 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 21:49:30.516  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1491 D SettingsProvider: selectionArgs: false
08-25 21:49:30.516  1018  1491 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  1491 D SettingsProvider: ret = -1
08-25 21:49:30.516  1018  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-25 21:49:30.516  1018  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1479 D SettingsProvider: selectionArgs: false
08-25 21:49:30.516  1018  1479 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  1479 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  4362 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 21:49:30.516  1018  4362 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  4362 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  4362 D SettingsProvider: selectionArgs: false
,08-25 21:49:30.516  1018  4362 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  4362 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  4362 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:30.516  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1499 D SettingsProvider: selectionArgs: false
,08-25 21:49:30.516  1018  1499 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.516  1018  1499 D SettingsProvider: ret = -1
,08-25 21:49:30.516  1018  1030 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
08-25 21:49:30.516  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1030 D SettingsProvider: selectionArgs: false
08-25 21:49:30.516  1018  1030 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.516  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 21:49:30.516  1018  1030 D SettingsProvider: ret = -1
08-25 21:49:30.516  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.516  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.516  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.516  1018  1031 D SettingsProvider: selectionArgs: false
,08-25 21:49:30.516  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.526  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.526  1018  1031 D SettingsProvider: ret = -1
08-25 21:49:30.526  1018  1207 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-25 21:49:30.526  1018  1207 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.526  1018  1207 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.526  1018  1207 D SettingsProvider: selectionArgs: false
08-25 21:49:30.526  1018  1207 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.526  1018  1207 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:30.526  1018  1207 D SettingsProvider: ret = -1
,08-25 21:49:30.526  1018  1356 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 21:49:30.526  1018  1356 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.526  1018  1356 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 21:49:30.526  1018  1356 D SettingsProvider: selectionArgs: false
08-25 21:49:30.526  1018  1356 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.526  1018  1356 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-25 21:49:30.526  1018  1356 D SettingsProvider: ret = -1
08-25 21:49:30.526  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 21:49:30.526  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 21:49:30.526  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.526  1018  1137 D SettingsProvider: selectionArgs: false
08-25 21:49:30.526  1018  1137 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.526  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 21:49:30.526  1018  1137 D SettingsProvider: ret = -1
,08-25 21:49:30.536  7465  7465 D BluetoothAdapterState: make,
,08-25 21:49:30.536  7465  7465 I bluedroid: init
08-25 21:49:30.536  7465  7480 I BluetoothAdapterState: Entering OffState
,08-25 21:49:30.546  7465  7465 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 21:49:30.546  7465  7465 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 21:49:30.546  7465  7465 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 21:49:30.546  7465  7465 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 21:49:30.546  7465  7465 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 21:49:30.546  7465  7465 I bluedroid: get_profile_interface socket
,08-25 21:49:30.546  7465  7465 I bluedroid: get_profile_interface map_client
,08-25 21:49:30.546  7465  7483 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 21:49:30.546  7465  7465 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-25 21:49:30.546  7465  7483 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 21:49:30.556  7465  7483 E BluetoothServiceJni: populateRssiValuesNative
,08-25 21:49:30.556  7465  7483 I bluedroid: getModelRssiValues
08-25 21:49:30.556  7465  7483 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 21:49:30.556  7465  7465 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 21:49:30.556  7465  7483 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 21:49:30.556  1018  1207 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 21:49:30.556  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.556  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.556  1018  1207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.556  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.556  1018  1018 D SettingsProvider: name = bluetooth_name
,08-25 21:49:30.556  7465  7473 I bluedroid: config_hci_snoop_log,
08-25 21:49:30.556  7465  7483 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-25 21:49:30.556  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 21:49:30.566  1018  1048 D BluetoothManagerService: Ble is always on enable gatt
,08-25 21:49:30.566  1018  1048 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 21:49:30.566  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 21:49:30.566  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 21:49:30.566  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:30.566  7465  7465 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-25 21:49:30.566  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 21:49:30.586  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 21:49:30.586  7465  7480 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 21:49:30.586  7465  7480 D BluetoothAdapterProperties: Setting state to 11
08-25 21:49:30.586  7465  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-25 21:49:30.586  7465  7480 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 21:49:30.586  7465  7480 D BluetoothAdapterService: updateAdapterState state is 11
08-25 21:49:30.586  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 21:49:30.586  7465  7480 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:30.586  7465  7480 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 21:49:30.586  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:30.586  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-25 21:49:30.596  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 21:49:30.596  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:30.596  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-25 21:49:30.596  7465  7480 D BluetoothSecureManager: getInstant: null
,08-25 21:49:30.596  7465  7480 D BluetoothSecureManager: calling getMethod for getService
08-25 21:49:30.596  7465  7480 D BluetoothSecureManager: calling getService
,08-25 21:49:30.596  1878  1878 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 21:49:30.596  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 21:49:30.596  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 21:49:30.606  1018  4362 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:30.606  7465  7480 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@b7f4656
08-25 21:49:30.606  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:30.606  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:30.606  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.606  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:30.606  1018  1356 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 21:49:30.606  1018  1356 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 21:49:30.606  1018  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 21:49:30.606  7465  7480 D BtConfig.SecureMode: isSecureModeOn:false
08-25 21:49:30.606  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 21:49:30.606  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 21:49:30.606  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 21:49:30.606  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.606  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:30.606  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 21:49:30.606  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 21:49:30.606  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 21:49:30.606  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 21:49:30.606  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 21:49:30.606  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:30.616  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 21:49:30.616  7465  7480 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 21:49:30.626  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:30.626  7465  7480 D BluetoothBondStateMachine: make
,08-25 21:49:30.626  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:30.626  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 21:49:30.626  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 21:49:30.626  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 21:49:30.626  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 21:49:30.626  7465  7488 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 21:49:30.626  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:30.626  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-25 21:49:30.636  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.636  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.636  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.636  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 21:49:30.636  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 21:49:30.636  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 21:49:30.636  7465  7465 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 21:49:30.636  7465  7465 D BtGatt.GattService: Received start request. Starting profile...
08-25 21:49:30.636  7465  7465 D BtGatt.GattService: start()
08-25 21:49:30.636  7465  7465 D BtGatt.GattService: start()
08-25 21:49:30.636  7465  7465 I bluedroid: get_profile_interface gatt
,08-25 21:49:30.636  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:30.636  7465  7465 D BtGatt.AdvertiseManager: advertise manager created
,08-25 21:49:30.636  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.636  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.636  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.636  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.636  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.646  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-25 21:49:30.646  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 21:49:30.646  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 21:49:30.646  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.646  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.646  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.646  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.646  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.656  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 21:49:30.656  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 21:49:30.656  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 21:49:30.656  7465  7465 D BtGatt.GattService: mStartError = false
08-25 21:49:30.656  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.656  1018  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.656  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.656  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.656  1018  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:30.656  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.656  7465  7465 D HeadsetService: Received start request. Starting profile...
08-25 21:49:30.656  7465  7465 D HeadsetService: start()
,08-25 21:49:30.656  7465  7465 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 21:49:30.656  7465  7465 D HeadsetStateMachine: make
,08-25 21:49:30.656  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 21:49:30.656  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 21:49:30.656  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 21:49:30.666  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.666  7465  7465 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 21:49:30.666  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.666  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.666  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:30.666  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.666  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService,
08-25 21:49:30.666  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 21:49:30.666  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-25 21:49:30.666  1018  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.666  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 21:49:30.676  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.676  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:30.676  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.676  1018  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 21:49:30.676  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.676  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:30.676  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 21:49:30.676  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.676  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 21:49:30.676  7465  7480 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 21:49:30.676  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 21:49:30.686  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:30.686  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:30.686  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.686  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.686  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.686  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.686  1018  1499 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-25 21:49:30.686  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.686  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.686  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.686  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 21:49:30.696  7465  7465 I bluedroid: get_profile_interface handsfree
,08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 21:49:30.696  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 21:49:30.696  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:30.696  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 21:49:30.696  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:30.696  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:30.696  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.696  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:30.696  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 21:49:30.696  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 21:49:30.696  7465  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 21:49:30.696  7465  7480 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 21:49:30.696  7465  7480 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 21:49:30.706  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:30.716  7465  7465 I DualScoManager: Instantiating Dual Sco Manager
,08-25 21:49:30.716  7465  7465 I DualScoManager: Set HeadsetServiceHelper
,08-25 21:49:30.716  7465  7465 D BluetoothAtMessage: createCMTIContentObservers
,08-25 21:49:30.716  1018  1031 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-25 21:49:30.716  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:30.716  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:30.716  1018  1031 D SettingsProvider: selectionArgs: false
,08-25 21:49:30.716  1018  1031 D SettingsProvider: selectionArgs: 1002
08-25 21:49:30.716  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 21:49:30.716  1018  1031 D SettingsProvider: ret = -1
,08-25 21:49:30.726  7465  7492 D HeadsetStateMachine: Enter Disconnected: -2,
,08-25 21:49:30.726  7465  7465 D HeadsetService: mStartError = false
08-25 21:49:30.726  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.726  7465  7465 D A2dpService: Received start request. Starting profile...
08-25 21:49:30.726  7465  7465 D A2dpService: start()
,08-25 21:49:30.726  7465  7492 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-25 21:49:30.726  7465  7492 D HeadsetStateMachine: map size, before remove : 0
08-25 21:49:30.726  7465  7492 D HeadsetStateMachine: map size, after remove: 0
,08-25 21:49:30.726  7465  7465 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 21:49:30.726  7465  7465 I bluedroid: get_profile_interface avrcp
,08-25 21:49:30.736  7465  7465 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 21:49:30.736  7465  7465 D Avrcp   : Initialize Media Controller
,08-25 21:49:30.736  7465  7465 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 21:49:30.736  7465  7465 E Avrcp   : getActiveSessions
,08-25 21:49:30.736  7465  7465 D Avrcp   : pick active media Controller
08-25 21:49:30.736  7465  7465 D Avrcp   : Get the active Media Controller 
,08-25 21:49:30.756  7465  7465 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 21:49:30.756  7465  7495 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 21:49:30.756  7465  7465 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:49:30.756  7465  7465 D A2dpStateMachine: make
,08-25 21:49:30.756  7465  7465 I bluedroid: get_profile_interface a2dp
,08-25 21:49:30.756  7465  7497 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 21:49:30.756  7465  7465 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 21:49:30.766  7465  7465 D A2dpService: mStartError = false
08-25 21:49:30.766  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.766  7465  7496 D A2dpStateMachine: Enter Disconnected: -2
,08-25 21:49:30.766  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-25 21:49:30.766  7465  7465 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 21:49:30.766  7465  7465 D HidService: Received start request. Starting profile...
08-25 21:49:30.766  7465  7465 D HidService: start()
08-25 21:49:30.766  7465  7465 I bluedroid: get_profile_interface hidhost
08-25 21:49:30.766  7465  7465 D HidService: setHidService(): set to: null
08-25 21:49:30.766  7465  7465 D HidService: mStartError = false
08-25 21:49:30.766  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.776  7465  7465 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 21:49:30.776  7465  7465 D HealthService: Received start request. Starting profile...
08-25 21:49:30.776  7465  7465 D HealthService: start()
,08-25 21:49:30.776  7465  7465 I bluedroid: get_profile_interface health
08-25 21:49:30.776  7465  7465 D HealthService: mStartError = false
08-25 21:49:30.776  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.776  7465  7465 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 21:49:30.776  7465  7465 D PanService: Received start request. Starting profile...
08-25 21:49:30.776  7465  7465 D PanService: start()
08-25 21:49:30.776  7465  7465 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 21:49:30.776  7465  7465 I bluedroid: get_profile_interface pan
,08-25 21:49:30.786  7465  7495 D BluetoothMediaBrowser: no now playing list
08-25 21:49:30.786  7465  7495 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 21:49:30.786  7465  7465 D PanService: mStartError = false
,08-25 21:49:30.786  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:30.786  7465  7465 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 21:49:30.786  1427  1453 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 21:49:30.786  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 21:49:30.786  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 21:49:30.786  1427  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 21:49:30.796  7465  7465 D BluetoothMapService: Received start request. Starting profile...
,08-25 21:49:30.796  7465  7465 D BluetoothMapService: start()
,08-25 21:49:30.796  7465  7465 D BluetoothMapService: mStartError = false
,08-25 21:49:30.796  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:30.796  7465  7465 D HeadsetStateMachine: Proxy object connected
08-25 21:49:30.796  7465  7465 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 21:49:30.796  7465  7492 D HeadsetStateMachine: Disconnected process message: 11
08-25 21:49:30.796  7465  7465 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 21:49:30.796  7465  7465 D SapService: Received start request. Starting profile...
08-25 21:49:30.796  7465  7465 D SapService: start()
08-25 21:49:30.796  7465  7465 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 21:49:30.796  7465  7465 I bluedroid: get_profile_interface sap
08-25 21:49:30.796  7465  7465 D SapService: mStartError = false
08-25 21:49:30.796  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:30.796  7465  7465 D HeadsetPhoneState: sendDeviceDataStateChanged
08-25 21:49:30.796  7465  7465 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 21:49:30.796  7465  7492 D HeadsetStateMachine: Disconnected process message: 18
08-25 21:49:30.796  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 21:49:30.796  7465  7465 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 21:49:30.796  7465  7465 D BluetoothA2dp: Proxy object connected
,08-25 21:49:30.806  7465  7492 D HeadsetStateMachine: Disconnected process message: 10
08-25 21:49:30.806  7465  7465 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 21:49:30.806  7465  7492 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 21:49:30.806  7465  7492 D HeadsetStateMachine: Disconnected process message: 11
,08-25 21:49:30.806  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 21:49:30.806  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-25 21:49:30.806  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-25 21:49:30.806  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 21:49:30.826  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 21:49:30.826  7465  7465 E BluetoothAdapterService(793941760): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 21:49:30.836  7465  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-25 21:49:30.836  7465  7480 I bluedroid: enable
,08-25 21:49:30.836  7465  7480 I bt_hci_bdroid: init
,08-25 21:49:30.836  7465  7480 I bt_vendor: bt-vendor : init
,08-25 21:49:30.836  7465  7480 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 21:49:30.836  7465  7480 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-25 21:49:30.836  7465  7480 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 21:49:30.836  7465  7480 D bt_userial_mct: userial_init
,08-25 21:49:30.836  7465  7501 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 21:49:30.836  7465  7480 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 21:49:30.836  7465  7480 I bt_vendor: Starting hciattach daemon
,08-25 21:49:30.836  7465  7480 I bt_vendor: try to set false
,08-25 21:49:30.846  7465  7480 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-25 21:49:30.846  7465  7480 I bt_vendor: Starting hciattach daemon
08-25 21:49:30.846  7465  7480 I bt_vendor: try to set true
,08-25 21:49:30.856  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-25 21:49:30.906  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 21:49:30.916  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 21:49:30.936  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 21:49:30.946  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 21:49:30.956  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 21:49:30.966  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 21:49:31.256  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-25 21:49:31.266  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 21:49:31.296  7465  7480 I bt_vendor: bluetooth satus is on,
08-25 21:49:31.296  7465  7503 D bt_userial_mct: userial_open(port:0)
08-25 21:49:31.296  7465  7503 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 21:49:31.296  7465  7503 I bt_vendor: Done intiailizing UART,
08-25 21:49:31.296  7465  7503 I bt_vendor: Done intiailizing UART
08-25 21:49:31.296  7465  7503 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-25 21:49:31.296  7465  7503 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 21:49:31.306  7465  7523 D bt_userial_mct: Entering userial_read_thread()
,08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_BTM,
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 21:49:31.306  7465  7501 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,08-25 21:49:31.336  1018  3364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-25 21:49:31.396  7465  7501 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 21:49:31.406  7465  7501 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42b2ed1 
,08-25 21:49:31.406  7465  7501 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42b2ed1 
,08-25 21:49:31.416   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:31.426  7465  7483 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 21:49:31.426  7465  7483 E bt-btif : Calling BTA_HhEnable
,08-25 21:49:31.426  7465  7483 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 21:49:31.426  7465  7483 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 21:49:31.426  7465  7483 E BluetoothServiceJni: populateRssiValuesNative
,08-25 21:49:31.426  7465  7483 I bluedroid: getModelRssiValues
08-25 21:49:31.426  7465  7483 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 21:49:31.426  7465  7483 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 21:49:31.436  1018  1018 D SettingsProvider: name = bluetooth_name,
08-25 21:49:31.436  7465  7483 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 21:49:31.436  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:31.436  7465  7483 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 21:49:31.436  7465  7483 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:31.446  7465  7483 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 21:49:31.446  7465  7483 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 21:49:31.446  7465  7483 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-25 21:49:31.446  7465  7483 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-25 21:49:31.446  7465  7483 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-25 21:49:31.446  7465  7483 E bt-btif : btif_sock_init: !vhci_init
,08-25 21:49:31.446  7465  7483 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-25 21:49:31.446  7465  7483 D IOP_DB_BT: db_open: db_open : handle 3023773712l, read 13894 bytes onto local cache
08-25 21:49:31.446  7465  7483 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 21:49:31.446  7465  7483 D IOP_DB_BT: db_query: result 1
,08-25 21:49:31.446  7465  7483 I         : iop_db_open: iop_db_open status 0
,08-25 21:49:31.446  7465  7483 D bte_conf: Device ID record 1 : primary
08-25 21:49:31.446  7465  7483 D bte_conf:   vendorId            = 0075
08-25 21:49:31.446  7465  7483 D bte_conf:   vendorIdSource      = 0001
08-25 21:49:31.446  7465  7483 D bte_conf:   product             = 0100
08-25 21:49:31.446  7465  7483 D bte_conf:   version             = 0200
08-25 21:49:31.446  7465  7483 D bte_conf:   clientExecutableURL = 
08-25 21:49:31.446  7465  7483 D bte_conf:   serviceDescription  = 
08-25 21:49:31.446  7465  7483 D bte_conf:   documentationURL    = 
08-25 21:49:31.446  7465  7483 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 21:49:31.446  7465  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 21:49:31.446  7465  7480 D BluetoothAdapterProperties: ScanMode =  20
08-25 21:49:31.446  7465  7480 D BluetoothAdapterProperties: State =  11
08-25 21:49:31.446  7465  7483 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 21:49:31.446  1018  4362 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-25 21:49:31.446  7465  7523 E bt_mct  : hci lib postload completed
08-25 21:49:31.446  7465  7480 D BluetoothAdapterProperties: Setting state to 12
,08-25 21:49:31.446  7465  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 21:49:31.456  7465  7483 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 21:49:31.456  7465  7483 D BluetoothAdapterProperties: Scan Mode:21
,08-25 21:49:31.456  7465  7483 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 21:49:31.456  1018  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-25 21:49:31.456  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:31.456  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 21:49:31.456  1018  1480 D SettingsProvider: selectionArgs: false
08-25 21:49:31.456  1018  1480 D SettingsProvider: selectionArgs: 1002
,08-25 21:49:31.456  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:31.456  1018  1480 D SettingsProvider: ret = -1
,08-25 21:49:31.456  7465  7480 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 21:49:31.456  7465  7480 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 21:49:31.466  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 21:49:31.466  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.466  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.466  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:31.466  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.466  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.466  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.476  1442  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.476  1442  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.476  7465  7480 D BluetoothAdapterService: Autoconnection is available 
08-25 21:49:31.476  7465  7480 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 21:49:31.476  7465  7480 D BluetoothAdapterService: starting service from this receiver
,08-25 21:49:31.476  1018  1207 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:31.476  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 21:49:31.476  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:31.476  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:31.476  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.476  1018  1207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.476  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.486  7465  7480 I BluetoothAdapterState: Entering On State from state = 11
,08-25 21:49:31.486  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:31.486  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.486  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.486  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:31.486  1427  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.486  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:31.486  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.496  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.496  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.496  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.496  1427  6978 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.496  1316  1326 D Bluetoothsap: onBluetoothStateChange: up=true
,08-25 21:49:31.496  1316  1326 D Bluetoothsap: Binding service...
,08-25 21:49:31.496  1316  1326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 21:49:31.506  7465  7465 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 21:49:31.506  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-25 21:49:31.506  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.506  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.506  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.506  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.506  1316  1326 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 21:49:31.506  1174  1781 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:31.506  1174  1781 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.506  1316  1334 D BluetoothPan: Binding service...
,08-25 21:49:31.506  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-25 21:49:31.516  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.516  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.516  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.516  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.516  6702  6710 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.516  6702  6710 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.516  1456  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.516  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:31.516  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.516  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.516  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.516  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-25 21:49:31.516  1456  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.516  1316  6874 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 21:49:31.516  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-25 21:49:31.516  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 21:49:31.516  7465  7465 I BluetoothPbapService: Handler(): got msg=1
,08-25 21:49:31.526  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.526  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.526  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.526  1018  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 21:49:31.526  1316  1326 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 21:49:31.526  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap,
08-25 21:49:31.526  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.526  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.526  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.526  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.526  7373  7384 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.526  7373  7384 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.526  7465  7527 V BluetoothPbapService: PBAP Service initSocket try: 0
08-25 21:49:31.526  1316  1334 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 21:49:31.536  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 21:49:31.536  1316  1316 D SapProfile: Bluetooth service connected
08-25 21:49:31.536  1316  1316 D Bluetoothsap: getConnectedDevices()
,08-25 21:49:31.536  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 21:49:31.536  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.536  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.536  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.536  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.536  1316  6874 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:31.536  1316  1316 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:31.536  1316  1316 D PanProfile: Bluetooth service connected
,08-25 21:49:31.536  1316  6874 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.536  1987  2159 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.536  1987  2159 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.536  7465  7486 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:31.536  7465  7527 D BluetoothSocket: bindListen(): myUserId = 0
08-25 21:49:31.536  7465  7527 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:31.536  1427  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.536  1427  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 21:49:31.546  1316  1316 D BluetoothInputDevice: Proxy object connected
08-25 21:49:31.546  1316  1316 D HidProfile: Bluetooth service connected
,08-25 21:49:31.546  7465  7527 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-25 21:49:31.546  7465  7527 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:31.546  7465  7527 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 21:49:31.546  7465  7527 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c0fe9a
08-25 21:49:31.546  7465  7527 D BluetoothSocket: channel: 19
08-25 21:49:31.546  7465  7527 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-25 21:49:31.546  1427  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.546  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 21:49:31.546  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.546  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.546  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.546  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.546  1427  6978 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.546  1427  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.546  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 21:49:31.546  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.556  1316  1316 D BluetoothMap: Proxy object connected
08-25 21:49:31.556  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.556  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.556  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.556  1316  1316 D MapProfile: Bluetooth service connected
08-25 21:49:31.556  1316  1316 D BluetoothMap: getConnectedDevices()
08-25 21:49:31.556  1427  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.556  1316  1326 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.556  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 21:49:31.556  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 21:49:31.556  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.556  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:31.556  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.556  1316  1326 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 21:49:31.556  7465  7473 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 21:49:31.556  7465  7473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 21:49:31.556  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:31.556  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.556  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 21:49:31.556  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.566  1018  1018 D BluetoothA2dp: Proxy object connected
,08-25 21:49:31.566  1316  1334 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:31.566  1316  1334 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 21:49:31.566  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 21:49:31.566  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.566  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.566  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.566  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.566  1316  1316 D BluetoothPbap: Proxy object connected
08-25 21:49:31.566  1316  1316 D PbapServerProfile: Bluetooth service connected
08-25 21:49:31.566  1316  1316 D HeadsetProfile: Bluetooth service connected
08-25 21:49:31.566  1018  1048 D BluetoothPan: Binding service...
,08-25 21:49:31.566  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 21:49:31.566  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.566  1456  2455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 21:49:31.566  1456  2455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 21:49:31.566  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 21:49:31.566  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 21:49:31.566  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 21:49:31.576  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:31.576  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-25 21:49:31.576  1316  1316 D BluetoothA2dp: Proxy object connected
08-25 21:49:31.576  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-25 21:49:31.576  1316  1316 D A2dpProfile: Bluetooth service connected
,08-25 21:49:31.576  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@39650cb7, true
,08-25 21:49:31.576  1427  1427 D BluetoothHeadset: registerMessageListener
,08-25 21:49:31.576  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-25 21:49:31.586  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 21:49:31.586  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:31.586  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-25 21:49:31.586  1878  1878 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 21:49:31.586  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:31.596  1018  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:31.596  1018  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 21:49:31.596  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 21:49:31.596  7465  7486 D HeadsetService: registerMessageListener
08-25 21:49:31.596  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:31.596  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.596  7465  7486 D HeadsetService: registerMessageListener
,08-25 21:49:31.596  7465  7492 D HeadsetStateMachine: Disconnected process message: 70
08-25 21:49:31.596  7465  7492 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@18db83cb
08-25 21:49:31.596  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 21:49:31.596  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:31.596  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 21:49:31.606  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 21:49:31.606  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.606  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:31.606  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:31.606  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 21:49:31.606  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 21:49:31.606  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 21:49:31.606  7465  7530 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 21:49:31.616  1316  1316 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 21:49:31.616  1316  1316 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 21:49:31.616  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 21:49:31.616  1316  1316 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 21:49:31.616  1316  1316 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 21:49:31.616  7465  7492 D HeadsetStateMachine: Disconnected process message: 9
08-25 21:49:31.616  7465  7492 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 21:49:31.616  7465  7530 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 21:49:31.616  7465  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:31.616  7465  7530 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-25 21:49:31.616  7465  7530 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:31.616  7465  7530 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 21:49:31.616  1174  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 21:49:31.616  7465  7530 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31a127a8
,08-25 21:49:31.616  7465  7530 D BluetoothSocket: channel: 5
,08-25 21:49:31.616   290   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-25 21:49:31.616   290   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 21:49:31.616   290   695 V voice   : voice_set_parameters: exit with code(-2)
08-25 21:49:31.616   290   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 21:49:31.616   290   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 21:49:31.626   290   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 21:49:31.626   290   695 V audio_hw_primary: adev_set_parameters: exit
08-25 21:49:31.626  7465  7492 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 21:49:31.626  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:31.626  1018  1491 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 21:49:31.626  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.626  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.626  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:31.626  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 21:49:31.636  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:31.636  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 21:49:31.646  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:49:31.646  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 21:49:31.656  7465  7465 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
,08-25 21:49:31.656  7465  7465 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 21:49:31.656  1018  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 21:49:31.656  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.656  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.656  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:31.656  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 21:49:31.676  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:31.676  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 21:49:31.676  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 21:49:31.676  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.676  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:31.676  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:31.686  1987  7536 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-25 21:49:31.686  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 21:49:31.796  1018  2056 V SAMP_SPCM_test: CSC File load.. 
,08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-25 21:49:31.806  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-25 21:49:31.836  1018  4362 I art     : Explicit concurrent mark sweep GC freed 22986(1333KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 4.209ms total 143.804ms
,08-25 21:49:31.836  1018  1481 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 21:49:31.846  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-25 21:49:31.856  1018  2056 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 21:49:31.856  1018  2056 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-25 21:49:31.856  1018  4362 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 21:49:31.866  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:31.866  1018  4362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:31.866  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 21:49:31.866  1018  2056 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-25 21:49:31.866  7465  7540 D BluetoothSocket: bindListen(): myUserId = 0
08-25 21:49:31.866  7465  7540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:31.866  1018  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:31.866  1018  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:31.866  1018  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:31.866  1018  2056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:31.886  7542  7542 E Zygote  : MountEmulatedStorage()
08-25 21:49:31.886  7542  7542 E Zygote  : v2
08-25 21:49:31.886  7542  7542 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:31.886  7542  7542 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:31.886  7542  7542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:31.886  1018  2056 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7542 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 21:49:31.886  7542  7542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:31.896  7542  7542 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 21:49:31.896  7465  7540 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-25 21:49:31.896  7465  7540 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 21:49:31.896  7465  7540 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 21:49:31.896  7465  7540 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18b8c6f2
08-25 21:49:31.896  7465  7540 D BluetoothSocket: channel: 12
08-25 21:49:31.896  7465  7540 I BtOppRfcommListener: Accept thread started.
,08-25 21:49:31.896  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 21:49:31.896  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:31.896  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 21:49:31.896  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 21:49:31.916  1987  7536 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 21:49:31.916  7542  7542 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:31.916  7542  7542 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:31.926  7542  7542 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 21:49:31.966  1018  2056 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-25 21:49:32.366   300   300 E SMD     : DCD OFF
,08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:32.376  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:32.376  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:32.386  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:32.386  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35983ba8 added. We now have 8 listener(s)
,08-25 21:49:32.386  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:32.386  1018  1207 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 21:49:32.386  1018  1207 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 21:49:32.386  1018  1207 D SecContentProvider2: mCursor = null
,08-25 21:49:32.386  1018  1207 D WifiService: setWifiEnabled: false pid=6702, uid=10171
,08-25 21:49:32.386  1018  1207 D SettingsProvider: name = wifi_on
,08-25 21:49:32.396  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.396  1018  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-25 21:49:32.396  1018  1491 D WifiService: setWifiEnabled: true pid=6702, uid=10171,
,08-25 21:49:32.396  1018  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 21:49:32.396  1018  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:32.396  1018  1491 D SecContentProvider2: mCursor = null
08-25 21:49:32.396  1018  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-25 21:49:32.396  1018  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6702, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 21:49:32.396  1018  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 21:49:32.396  1018  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 21:49:32.396  1018  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
,08-25 21:49:32.396  1018  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 21:49:32.396  1018  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 21:49:32.396  1018  1491 D SettingsProvider: name = wifi_on
08-25 21:49:32.406  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
08-25 21:49:32.416   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 21:49:32.756  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:32.756  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:32.756  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 21:49:32.756  1018  1046 D Tethering: interfaceAdded wlan0
,08-25 21:49:32.766  1018  1046 D Tethering: interfaceAdded p2p0
,08-25 21:49:32.766  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:32.766  1018  1132 E Tethering: No numeric data
08-25 21:49:32.766  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:49:32.766  1018  1132 D Tethering: clearTetheredNotification()
,08-25 21:49:32.766  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:32.776  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
08-25 21:49:32.776   285   975 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-25 21:49:32.776   285   975 D SoftapController: Softap fwReload - Ok
,08-25 21:49:32.776  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:32.776  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:32.776  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:32.776  1174  1174 D HotspotTile: updateTetherState():false, false
08-25 21:49:32.786  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 21:49:32.786  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-25 21:49:32.786   285   975 D CommandListener: Setting iface cfg
08-25 21:49:32.786   285   975 D CommandListener: Trying to bring down wlan0
08-25 21:49:32.786  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 21:49:32.786   285   975 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:32.786  1018  1124 V NetworkStats: performPollLocked() took 20ms,
08-25 21:49:32.786  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:32.786  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:32.796  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:32.796  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 21:49:32.846  7569  7569 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-25 21:49:32.846  7569  7569 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 21:49:32.846  7569  7569 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-25 21:49:32.856  7569  7569 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-25 21:49:32.866   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7569
,08-25 21:49:32.866   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 21:49:32.866  7569  7569 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 21:49:32.866  7569  7569 I wpa_supplicant: ssSupport state is = 1
,08-25 21:49:32.866  7569  7569 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-25 21:49:32.866  7569  7569 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 21:49:32.866   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7569
08-25 21:49:32.866   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-25 21:49:32.896  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 21:49:32.906  1018  3339 D SSRM:n  : SIOP:: AP = 330
,08-25 21:49:32.906  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:32.906  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 21:49:32.906  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:32.906  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:32.906  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:32.906  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:32.906  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:32.906  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:32.906  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-25 21:49:32.906  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 21:49:32.906  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:32.906  1174  1174 D HotspotTile: onReceive : 2, 0
,08-25 21:49:32.916  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.916  1018  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:32.916  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:32.916  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:32.916  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:32.916  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:32.916  1635  1635 I Hs20UtilService: Starting #19
,08-25 21:49:32.926  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 21:49:32.926  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:32.926  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
08-25 21:49:32.926  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 21:49:32.926  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:33.026   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-25 21:49:33.026  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-25 21:49:33.076  7569  7569 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 21:49:33.076  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 21:49:33.076  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 21:49:33.086   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7569
08-25 21:49:33.086   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 21:49:33.086  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 21:49:33.086  7569  7569 I wpa_supplicant: ssSupport state is = 1
,08-25 21:49:33.086  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.086  7569  7569 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:33.086  7569  7569 E wpa_supplicant: SIM READ ERROR
08-25 21:49:33.086  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.086  7569  7569 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 21:49:33.086  7569  7569 E wpa_supplicant: SIM READ ERROR
08-25 21:49:33.086  7569  7569 I wpa_supplicant: Blacklist: Clear (all) ,
08-25 21:49:33.086  7569  7569 I wpa_supplicant: wpa_default_ap_write_once
08-25 21:49:33.086  7569  7569 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 21:49:33.086  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.086  7569  7569 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 21:49:33.086  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.086  7569  7569 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 21:49:33.086  7569  7569 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 21:49:33.086  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:33.086  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:33.086  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-25 21:49:33.086  1018  1132 D Tethering: InitialState.processMessage what=4
,08-25 21:49:33.086  1018  1132 E Tethering: No numeric data
08-25 21:49:33.096  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:33.086  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:49:33.096  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:33.086  1018  1132 D Tethering: clearTetheredNotification()
08-25 21:49:33.096  1174  1174 D HotspotTile: updateTetherState():false, false
08-25 21:49:33.096  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:33.096  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:33.096  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:33.096  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 21:49:33.096  1018  1124 V NetworkStats: performPollLocked() took 4ms
,08-25 21:49:33.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:33.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:33.146  7569  7569 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 21:49:33.416   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-25 21:49:33.536  7569  7569 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-25 21:49:33.536  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 21:49:33.546  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 21:49:33.556   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7569,
08-25 21:49:33.556   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-25 21:49:33.556  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 21:49:33.556  7569  7569 I wpa_supplicant: ssSupport state is = 1
08-25 21:49:33.556  7569  7569 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 21:49:33.556  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 21:49:33.566  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 21:49:33.566   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7569,
08-25 21:49:33.566   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-25 21:49:33.566  7569  7569 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 21:49:33.566  7569  7569 I wpa_supplicant: ssSupport state is = 1
08-25 21:49:33.566  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.566  7569  7569 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-25 21:49:33.566  7569  7569 E wpa_supplicant: SIM READ ERROR
08-25 21:49:33.566  7569  7569 I wpa_supplicant: wpa_default_ap_write_once
08-25 21:49:33.566  7569  7569 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-25 21:49:33.576  7569  7569 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 21:49:33.576  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 21:49:33.576  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:33.576  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:33.576  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 21:49:33.576  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:33.576  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-25 21:49:33.676  7569  7569 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 21:49:33.676  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 21:49:33.716  7569  7569 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-25 21:49:33.716  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 21:49:33.716  7569  7569 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-25 21:49:33.726  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-25 21:49:33.726  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 21:49:33.726  7569  7569 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-25 21:49:33.736  7569  7569 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 21:49:33.736  7569  7569 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-25 21:49:33.736  7569  7569 E wpa_supplicant: SIM READ ERROR
08-25 21:49:33.736  7569  7569 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 21:49:33.746  7569  7569 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 21:49:33.756  7569  7569 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 21:49:33.756  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 21:49:33.756  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 21:49:33.756  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-25 21:49:33.756  1174  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-25 21:49:33.756  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-25 21:49:33.756  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:33.756  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:33.756  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:33.756  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:33.756  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:33.756  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:33.756  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 21:49:33.756  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-25 21:49:33.766  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-25 21:49:33.766  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:49:33.766  1174  1174 D HotspotTile: onReceive : 3, 0
,08-25 21:49:33.776  1018  1207 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:33.776  1018  1207 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:33.776  1018  1207 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:33.776  1018  1207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:33.776  1018  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:33.776  6702  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:33.786  1635  1635 I Hs20UtilService: Starting #20
,08-25 21:49:33.786  1635  1698 I Hs20UtilService: Message received 5011
,08-25 21:49:33.786  1018  1127 E WifiConfigStore: Not a HS20
,08-25 21:49:33.786  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 21:49:33.786  6702  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:33.796  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 21:49:33.796  6530  6530 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 21:49:33.796  6530  6530 D SecurityLogAgent: StateMachine : Current State = 1
08-25 21:49:33.796  6530  6530 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 21:49:33.796  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 21:49:33.796  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 21:49:33.796  7569  7569 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 21:49:33.796  7569  7569 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 21:49:33.796  7569  7569 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 21:49:33.796  7569  7569 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 21:49:33.796  7569  7569 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 21:49:33.796  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
08-25 21:49:33.796  7569  7569 I wpa_supplicant: First Scan Start
08-25 21:49:33.796  7569  7569 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 21:49:33.806  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
08-25 21:49:33.806  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:49:33.806  1018  1127 I WifiNative-HAL: startHal
08-25 21:49:33.806  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5b988c
08-25 21:49:33.806  1018  1127 I WifiNative-HAL: Could not start hal
08-25 21:49:33.806  6954  6954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:49:33.806  1018  1127 E WifiNative-wlan0: do suspend true
,08-25 21:49:33.816  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 21:49:33.816  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-25 21:49:33.816   285   975 D CommandListener: Setting iface cfg
08-25 21:49:33.816   285   975 D CommandListener: Trying to bring up p2p0
,08-25 21:49:33.816  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 21:49:33.816  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:49:33.816  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 21:49:33.816  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 21:49:33.816  1018  1126 D WifiP2pService: P2pEnablingState
08-25 21:49:33.816  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-25 21:49:33.816  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:33.816  1018  1151 I WifiNative-HAL: startHal
08-25 21:49:33.816  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e9739bc
08-25 21:49:33.816  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 21:49:33.816  1018  1151 I WifiNative-HAL: Could not start hal
08-25 21:49:33.816  1018  1151 E WifiScanningService: could not start HAL
08-25 21:49:33.816  1018  1126 D WifiP2pService: P2p socket connection successful
,08-25 21:49:33.816  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-25 21:49:33.816  1018  1126 D WifiP2pService: P2pEnabledState
08-25 21:49:33.816  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 21:49:33.816  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 21:49:33.816  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 21:49:33.816  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-25 21:49:33.816  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:33.816  1018  1152 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:49:33.826  7569  7569 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:33.826  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 21:49:33.826  7569  7569 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:33.826  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-25 21:49:33.826  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:33.826  1018  1049 D WifiDisplayController: disconnect
08-25 21:49:33.826  1018  1049 D WifiDisplayController: updateConnection
08-25 21:49:33.826  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 21:49:33.826  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 21:49:33.826  7569  7569 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 21:49:33.826  1018  1127 E WifiStateMachine: Failed to set frequency band 0
,08-25 21:49:33.826  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:33.826  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:33.826  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:49:33.826  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-25 21:49:33.826  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 21:49:33.826  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 21:49:33.826  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-25 21:49:33.836  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 21:49:33.836  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-25 21:49:33.836  1018  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 21:49:33.836  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 21:49:33.836  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 21:49:33.836  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 21:49:33.836  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:33.836  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:33.836  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28,
08-25 21:49:33.836  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  secondary type: null
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  wps: 0
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  grpcapab: 0
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  devcapab: 0
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  status: 3
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  wfdInfo: null
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-25 21:49:33.836  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-25 21:49:33.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:33.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 21:49:33.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:33.846  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 21:49:33.846  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 21:49:33.846  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:33.846  6921  6921 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 21:49:33.846  6921  6921 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 21:49:33.856  6936  6936 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 21:49:33.866  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 21:49:33.866  1018  1126 D WifiP2pService: InactiveState
,08-25 21:49:33.866  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 21:49:33.866  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 21:49:33.866  7569  7569 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 21:49:33.866  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 21:49:33.866  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:34.436  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:34.436  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:34.446  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 21:49:34.446  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 21:49:34.446  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2908ca2e Bundle[{}]
,08-25 21:49:34.446  6702  6755 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 21:49:34.446  6702  6755 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 21:49:34.446  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 21:49:34.456  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 21:49:34.456  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 21:49:34.456  6702  6755 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 21:49:34.456  6702  6755 I System.out: Running OutgoingSocketThread
,08-25 21:49:34.466  6702  7576 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1329),
,08-25 21:49:34.466  6702  7576 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47889
,08-25 21:49:34.466  6702  7576 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 21:49:35.046  7569  7569 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
08-25 21:49:35.046  7569  7569 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 21:49:35.046  7569  7569 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-25 21:49:35.046  7569  7569 I wpa_supplicant: Trying to associate with  'G700',
08-25 21:49:35.046  7569  7569 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 21:49:35.046  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-25 21:49:35.056  1018  7574 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 21:49:35.066  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:35.066  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:35.176  7569  7569 E wpa_supplicant: Cmd 35605 not handled
,08-25 21:49:35.176  7569  7569 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 21:49:35.176  7569  7569 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-25 21:49:35.176  7569  7569 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 21:49:35.176  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 21:49:35.176  7569  7569 I wpa_supplicant: Associated with F4.99.3E
08-25 21:49:35.176  7569  7569 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 21:49:35.176  7569  7569 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-25 21:49:35.176  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-25 21:49:35.176  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 21:49:35.176  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:35.186  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-25 21:49:35.186  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 21:49:35.186  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 21:49:35.186  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-25 21:49:35.186  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 21:49:35.186  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-25 21:49:35.186  1018  1132 E Tethering: No numeric data
08-25 21:49:35.186  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:49:35.186  1018  1132 D Tethering: clearTetheredNotification()
,08-25 21:49:35.186  7569  7569 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 21:49:35.186  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 21:49:35.186  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 21:49:35.186  1018  1127 D SecContentProvider2: mCursor = null
08-25 21:49:35.186  7569  7569 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
08-25 21:49:35.186  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 21:49:35.186  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:35.186  7569  7569 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 21:49:35.186  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-25 21:49:35.186  7569  7569 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 21:49:35.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:35.186  7569  7569 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 21:49:35.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-25 21:49:35.196  7569  7569 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-25 21:49:35.196  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 21:49:35.196  7569  7569 I wpa_supplicant: Blacklist: Clear (temp) 
,08-25 21:49:35.196  1174  1174 D HotspotTile: updateTetherState():false, false
08-25 21:49:35.196  7569  7569 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 21:49:35.196  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-25 21:49:35.196  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 21:49:35.196  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-25 21:49:35.196  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 21:49:35.196  1018  1127 D SecContentProvider2: mCursor = null
08-25 21:49:35.196  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-25 21:49:35.196  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:35.196  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:35.196  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:35.196  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 21:49:35.206  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 21:49:35.206  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:35.206  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:35.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:35.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:35.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:35.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:35.206  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 21:49:35.206  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 21:49:35.206  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:35.216  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 21:49:35.216  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:35.216  1018  4362 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 21:49:35.216  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:35.216  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:35.216  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:35.216  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 21:49:35.216  1635  1635 I Hs20UtilService: Starting #21
,08-25 21:49:35.226  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 21:49:35.226  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:35.226  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:35.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:35.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:35.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:35.226  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off,
08-25 21:49:35.226  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 21:49:35.226  1635  1698 I Hs20UtilService: Message received 5007
,08-25 21:49:35.236   285   975 D CommandListener: Setting iface cfg
,08-25 21:49:35.236  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 21:49:35.236  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:35.236  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:35.246  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 21:49:35.246  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 21:49:35.246  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:35.246  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:35.246  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:35.246  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:35.256  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 21:49:35.256  1018  1127 D SecContentProvider2: mCursor = null
,08-25 21:49:35.266  1018  1127 E WifiNative-wlan0: do suspend false
,08-25 21:49:35.266  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-25 21:49:35.266  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 21:49:35.366   300   300 E SMD     : DCD OFF,
,08-25 21:49:35.466  6702  6755 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1330)
,08-25 21:49:35.466  6702  6755 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1330)
,08-25 21:49:35.466  6702  6755 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1335)
,08-25 21:49:35.466  6702  6755 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-25 21:49:35.466  6702  6755 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1336)
,08-25 21:49:35.476  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.476  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3feec6c1 added. We now have 2 listener(s)
,08-25 21:49:35.476  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 21:49:35.476  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.476  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:35.476  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.476  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337f9e66 added. We now have 9 listener(s)
08-25 21:49:35.476  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 21:49:35.486  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:35.486  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:35.496  7581  7581 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:35.506  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:35.506  7581  7581 I dhcpcd  : version 5.5.6 starting
,08-25 21:49:35.506  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:35.506  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:35.506  7581  7581 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 21:49:35.506  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:35.506  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1096a54 added. We now have 3 listener(s)
,08-25 21:49:35.506  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.506  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20600dfd added. We now have 10 listener(s)
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:35.516  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:35.516  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:35.516  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.516  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3feec6c1 removed from the list
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337f9e66 removed from the list
08-25 21:49:35.516  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.516  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.516  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337f9e66 not in the list
08-25 21:49:35.516  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20600dfd removed from the list
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.516  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.516  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.516  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1096a54 removed from the list
08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:35.516  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd73af2 added. We now have 2 listener(s)
08-25 21:49:35.526  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 21:49:35.526  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.526  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:35.526  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:35.526  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37c60543 added. We now have 9 listener(s),
08-25 21:49:35.526  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:35.526  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:49:35.526  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:35.536  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:35.536  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-25 21:49:35.536  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:35.536  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.536  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da48cf9 added. We now have 3 listener(s)
08-25 21:49:35.536  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.536  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.536  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:35.536  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.536  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:35.536  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.536  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139a143e added. We now have 10 listener(s)
08-25 21:49:35.536  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:35.536  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:35.536  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 21:49:35.536  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:35.536  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:35.536  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:35.546  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:35.556  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:35.556  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:49:35.556  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 21:49:35.556  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:35.556  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:35.566  7465  7478 D BtGatt.GattService: registerClient() - UUID=10bd78bd-c79f-4a87-abe8-1d154e560b67,
,08-25 21:49:35.576  7581  7581 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-25 21:49:35.576  7581  7581 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 21:49:35.576  7581  7581 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 21:49:35.576  7581  7581 I dhcpcd  : bssid match
08-25 21:49:35.576  7581  7581 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 21:49:35.606  7465  7483 D BtGatt.GattService: onClientRegistered() - UUID=10bd78bd-c79f-4a87-abe8-1d154e560b67, clientIf=6,
,08-25 21:49:35.606  6702  6710 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 21:49:35.606  7465  7486 D BtGatt.GattService: start scan with filters
08-25 21:49:35.606  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:35.606  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:35.606  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:35.606  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 21:49:35.606  7465  7491 D BtGatt.ScanManager: handling starting scan
08-25 21:49:35.606  7465  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f529700
08-25 21:49:35.606  7465  7483 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 21:49:35.606  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.616  7465  7491 D BtGatt.ScanManager: allow scan with filters
08-25 21:49:35.616  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:35.616  7465  7491 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 21:49:35.616  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:35.616  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:35.616  7465  7491 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 21:49:35.616  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-25 21:49:35.616  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.616  7465  7491 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:35.616  7465  7491 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 21:49:35.616  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:35.616  7465  7483 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 21:49:35.616  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.616  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 21:49:35.626  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.626  6702  6755 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:35.626  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:35.626  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:35.626  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.626  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:35.626  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:35.626  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:35.626  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:35.626  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:35.626  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:35.626  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:35.626  7465  7529 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:35.626  7465  7491 D BtGatt.ScanManager: filter size is 1
,08-25 21:49:35.626  7465  7491 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 21:49:35.626  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 21:49:35.626  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.626  7465  7491 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:35.636  7465  7478 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 21:49:35.636  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 21:49:35.636  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:35.636  7465  7491 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 21:49:35.636  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:35.636  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:35.636  7465  7483 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 21:49:35.636  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:35.636  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:35.636  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:35.636  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:35.636  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:35.636  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:35.646  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:35.646  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:35.646  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.646  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bd73af2 removed from the list
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37c60543 removed from the list
08-25 21:49:35.646  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:35.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.646  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.646  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37c60543 not in the list
08-25 21:49:35.646  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139a143e removed from the list
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:35.646  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.646  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.646  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da48cf9 removed from the list
,08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.646  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@311f364a added. We now have 2 listener(s)
,08-25 21:49:35.656  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:35.656  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.656  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:35.656  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.656  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3410d9bb added. We now have 9 listener(s)
08-25 21:49:35.656  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:35.656  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:35.656  7581  7581 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-25 21:49:35.656  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:35.656  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:35.666  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:35.666  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:35.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1015e231 added. We now have 3 listener(s)
,08-25 21:49:35.666  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.666  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:35.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:35.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:35.666  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27226d16 added. We now have 10 listener(s)
08-25 21:49:35.666  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:35.666  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:35.666  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:35.666  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:35.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 21:49:35.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:35.666  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:35.676  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:35.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:35.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:35.676  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:35.676  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:35.676  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:35.686  7465  7486 D BtGatt.GattService: registerClient() - UUID=4435ec8b-de78-4f65-8290-6de2daca4ff1
,08-25 21:49:35.726  7581  7581 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-25 21:49:35.726  7465  7483 D BtGatt.GattService: onClientRegistered() - UUID=4435ec8b-de78-4f65-8290-6de2daca4ff1, clientIf=6
08-25 21:49:35.726  6702  6711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 21:49:35.726  7465  7473 D BtGatt.GattService: start scan with filters
08-25 21:49:35.726  7465  7491 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:35.726  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-25 21:49:35.726  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:35.726  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:35.726  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:35.736  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:35.736  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:35.736  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:35.736  7465  7483 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 21:49:35.736  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.736  7465  7491 D BtGatt.ScanManager: allow scan with filters
08-25 21:49:35.736  7465  7491 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 21:49:35.736  7465  7491 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 21:49:35.746  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 21:49:35.746  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 21:49:35.746  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.746  7465  7491 D BtGatt.ScanManager: Starting BLE batch scan,
08-25 21:49:35.746  7465  7491 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 21:49:35.746  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-25 21:49:35.746  6702  6755 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 21:49:35.746  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:35.746  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:35.746  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:35.746  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.746  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.746  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:35.746  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.746  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@311f364a removed from the list
08-25 21:49:35.746  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.746  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3410d9bb removed from the list
08-25 21:49:35.746  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:35.746  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:35.746  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.746  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 21:49:35.746  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.746  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.756  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3410d9bb not in the list
08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:35.756  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:35.756  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:35.756  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:35.756  7465  7483 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 21:49:35.756  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.756  7465  7478 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:35.756  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 21:49:35.756  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.766  7465  7486 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 21:49:35.766  7465  7491 D BtGatt.ScanManager: filter size is 1
,08-25 21:49:35.766  7465  7491 D BtGatt.ScanManager: delete FilterIndex - 4
,08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:35.766  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 21:49:35.766  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.766  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 21:49:35.766  7465  7491 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:35.766  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:35.766  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:35.766  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:35.776  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.776  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:35.776  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.776  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.776  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27226d16 removed from the list
08-25 21:49:35.776  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.776  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.776  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.776  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.776  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1015e231 removed from the list
08-25 21:49:35.776  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.776  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65044a2 added. We now have 2 listener(s)
08-25 21:49:35.776  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:35.776  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:35.776  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:35.776  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 21:49:35.776  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.776  7465  7491 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 21:49:35.776  7465  7483 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 21:49:35.776  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.786  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 21:49:35.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 21:49:35.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:35.786  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.786  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c62c533 added. We now have 9 listener(s)
08-25 21:49:35.786  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:35.786  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:49:35.786  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 21:49:35.786  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 21:49:35.786  1018  1030 D BatteryService: stay LED for fully charged
08-25 21:49:35.786  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 21:49:35.786  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 21:49:35.786  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 21:49:35.786  1018  1018 I MotionRecognitionService: Plugged
08-25 21:49:35.786  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 21:49:35.796  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-25 21:49:35.796  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 21:49:35.796  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 21:49:35.796  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-25 21:49:35.806  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:49:35.806  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 21:49:35.806  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 21:49:35.816  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:35.816  7465  7465 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 21:49:35.816  7465  7492 D HeadsetStateMachine: Disconnected process message: 10
,08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:35.826  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:35.836  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:35.846  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:35.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1345a669 added. We now have 3 listener(s)
,08-25 21:49:35.846  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.846  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 21:49:35.846  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.846  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:35.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9208ee added. We now have 10 listener(s)
08-25 21:49:35.846  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:35.846  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:35.846  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:35.846  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:35.846  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:35.846  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:35.846  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:35.846  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:35.856  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-25 21:49:35.856  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:35.866  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-25 21:49:35.876  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:35.876  6702  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:35.886  7465  7486 D BtGatt.GattService: registerClient() - UUID=cc0f2f5d-0f70-41c8-a956-246ed09fbe1e
,08-25 21:49:35.926  7465  7483 D BtGatt.GattService: onClientRegistered() - UUID=cc0f2f5d-0f70-41c8-a956-246ed09fbe1e, clientIf=6
08-25 21:49:35.926  6702  6710 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 21:49:35.926  7465  7473 D BtGatt.GattService: start scan with filters
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: handling starting scan
08-25 21:49:35.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-25 21:49:35.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:35.926  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:35.926  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 21:49:35.926  7465  7483 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 21:49:35.926  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: allow scan with filters
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-25 21:49:35.926  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 21:49:35.926  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:35.926  7465  7491 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 21:49:35.936  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:35.936  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-25 21:49:35.936  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:35.936  7465  7483 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 21:49:35.936  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.936  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 21:49:35.936  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.946  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:35.956  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:35.966  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:35.966  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.966  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.966  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65044a2 removed from the list
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.966  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c62c533 removed from the list
08-25 21:49:35.966  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:35.966  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 21:49:35.966  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.966  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c62c533 not in the list
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:35.966  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:35.966  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:35.966  7465  7528 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:35.966  7465  7491 D BtGatt.ScanManager: filter size is 1
,08-25 21:49:35.966  7465  7491 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 21:49:35.966  7465  7483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 21:49:35.966  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.966  7465  7491 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:35.966  7465  7529 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 21:49:35.976  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:35.976  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 21:49:35.976  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:35.976  7465  7483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 21:49:35.976  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.976  7465  7491 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 21:49:35.976  7465  7483 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 21:49:35.976  7465  7483 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 21:49:35.976  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 21:49:35.976  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:35.986  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:35.986  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 21:49:35.986  6702  6755 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:35.986  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:35.986  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:35.986  6702  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:35.986  6702  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:35.986  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9208ee removed from the list
08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:35.986  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:35.986  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:35.986  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:35.986  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1345a669 removed from the list
,08-25 21:49:35.986  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:35.986  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@719c5fa added. We now have 2 listener(s)
,08-25 21:49:35.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:35.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:35.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:35.996  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:35.996  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a7a7ab added. We now have 9 listener(s)
,08-25 21:49:35.996  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:35.996  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:35.996  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:35.996  6702  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:36.006  6702  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:36.006  6702  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b2b9a1 added. We now have 3 listener(s)
,08-25 21:49:36.006  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:36.006  6702  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282e47c6 added. We now have 10 listener(s)
08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:36.006  6702  6755 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:36.006  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:36.006  6702  6755 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:36.006  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:36.006  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:36.006  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@719c5fa removed from the list
08-25 21:49:36.006  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:36.006  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a7a7ab removed from the list
08-25 21:49:36.006  6702  6755 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:36.006  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:36.006  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:36.016  6702  6755 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a7a7ab not in the list
08-25 21:49:36.016  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:36.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:36.016  6702  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282e47c6 removed from the list
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:36.016  6702  6755 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:36.016  6702  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:36.016  6702  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:36.016  6702  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b2b9a1 removed from the list
,08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 21:49:36.016  6702  6755 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:36.016  6702  7612 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1343, name: My test thread name)
,08-25 21:49:36.026  6702  7612 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1343, thread name: My test thread name)
08-25 21:49:36.026  6702  7612 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1343, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 21:49:36.026  6702  7613 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1345, name: My test thread name)
,08-25 21:49:36.026  6702  7613 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1345, thread name: My test thread name)
,08-25 21:49:36.026  6702  7613 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1345, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 21:49:36.026  6702  6755 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-25 21:49:36.026  6702  6755 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 21:49:36.026  6702  6755 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-25 21:49:36.026  6702  6755 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 21:49:36.026  6702  6755 D com.test.thalitest.ThaliTestRunner: Total duration: 24391 ms
,08-25 21:49:36.026  6702  6755 I jxcore-log: *Native tests were executed*
08-25 21:49:36.026  6702  6755 I jxcore-log: 
08-25 21:49:36.026  6702  6755 I jxcore-log: Total number of executed tests:  80
08-25 21:49:36.026  6702  6755 I jxcore-log: 
,08-25 21:49:36.026  6702  6755 I jxcore-log: Number of passed tests:  80
08-25 21:49:36.026  6702  6755 I jxcore-log: 
08-25 21:49:36.026  6702  6755 I jxcore-log: Number of failed tests:  0
08-25 21:49:36.026  6702  6755 I jxcore-log: 
08-25 21:49:36.026  6702  6755 I jxcore-log: Number of ignored tests:  0
08-25 21:49:36.026  6702  6755 I jxcore-log: 
,08-25 21:49:36.036  6702  6755 I jxcore-log: Total duration:  24391
08-25 21:49:36.036  6702  6755 I jxcore-log: 
08-25 21:49:36.036  6702  6755 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 21:49:36.036  6702  6755 I jxcore-log: 
,08-25 21:49:36.036  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.036  6702  6755 I jxcore-log: 
08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
08-25 21:49:36.046  6702  6702 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
,08-25 21:49:36.046  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:36.046  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-25 21:49:36.056  6702  6755 I jxcore-log: 
08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
,08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
08-25 21:49:36.056  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.056  6702  6755 I jxcore-log: 
08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-25 21:49:36.066  6702  6755 I jxcore-log: 
08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-25 21:49:36.066  6702  6755 I jxcore-log: 
08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.066  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:36.066  6702  6755 I jxcore-log: 
,08-25 21:49:36.076  1018  1127 E WifiNative-wlan0: do suspend true
,08-25 21:49:36.106  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-25 21:49:36.106  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 21:49:36.116  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-25 21:49:36.116  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,08-25 21:49:36.126  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:36.126  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:36.126  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.126  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.126  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.126  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.126  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-25 21:49:36.126  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-25 21:49:36.136  1018  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-25 21:49:36.136  1018  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-25 21:49:36.136  1018  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 21:49:36.136  1018  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 21:49:36.136  1018  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 21:49:36.136  1018  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 21:49:36.136  6702  6702 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 21:49:36.146  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:36.146  6702  6755 I jxcore-log: 
,08-25 21:49:36.156  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:36.156  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 21:49:36.156  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.156  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.156  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.156  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.156  1018  1356 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:36.156  1018  1356 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:36.156  1018  1356 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:36.156  1018  1356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:36.156  1018  1356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 21:49:36.156  1635  1635 I Hs20UtilService: Starting #22
08-25 21:49:36.166  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-25 21:49:36.166  1635  1698 I Hs20UtilService: Message received 5007
08-25 21:49:36.166  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 21:49:36.166  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 21:49:36.176  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-25 21:49:36.176  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-25 21:49:36.186  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504,
,08-25 21:49:36.186  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 21:49:36.186  1018  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-25 21:49:36.186  1018  1129 D ConnectivityService: LTETest block dns file not exists,
,08-25 21:49:36.196  1018  1129 V NetworkStats: updateIfacesLocked()
,08-25 21:49:36.196  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.196  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:36.196  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:36.196  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:36.196  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 21:49:36.196  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 21:49:36.196  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:36.196  1018  1129 V NetworkStats: performPollLocked() took 7ms
,08-25 21:49:36.206  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 21:49:36.206  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 21:49:36.206  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 21:49:36.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 21:49:36.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.206  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.206  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 21:49:36.206  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-25 21:49:36.206  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-25 21:49:36.216  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 21:49:36.216  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 21:49:36.216  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 21:49:36.216  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.216  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.216  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.226  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:36.226  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-25 21:49:36.226  1018  1129 E ConnectivityService: updateNetworkInfo()
08-25 21:49:36.226  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:49:36.226  1018  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:36.226  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:36.226  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.226  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.226  1018  1129 V NetworkStats: updateIfacesLocked()
08-25 21:49:36.226  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:36.226  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:36.226  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:36.226  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 21:49:36.226  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.226  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:36.226  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:36.226  1635  1635 I Hs20UtilService: Starting #23
,08-25 21:49:36.226  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.226  1018  1129 V NetworkStats: performPollLocked() took 4ms
,08-25 21:49:36.226  1635  1698 I Hs20UtilService: Message received 5007
08-25 21:49:36.226  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 21:49:36.226  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 21:49:36.226  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 21:49:36.226  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.236  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-25 21:49:36.236  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.236  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 21:49:36.236  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:36.236  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-25 21:49:36.236  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:49:36.236  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-25 21:49:36.236  1018  7577 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 21:49:36.236   285   971 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 21:49:36.236  1018  1129 D ConnectivityService:    accepting network in place of null
08-25 21:49:36.236   285   971 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-25 21:49:36.236  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 21:49:36.236  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 21:49:36.236  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 21:49:36.236  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 21:49:36.236  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 21:49:36.236  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-25 21:49:36.236  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 21:49:36.236  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:49:36.236  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 21:49:36.236  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 21:49:36.236  1316  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 21:49:36.236  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
08-25 21:49:36.236  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 21:49:36.236  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:49:36.236  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-25 21:49:36.246  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 21:49:36.246  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 21:49:36.246  1018  1124 V NetworkStats: updateIfacesLocked()
08-25 21:49:36.246  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:36.246  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 21:49:36.246  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 21:49:36.246  1018  1124 V NetworkStats: performPollLocked() took 3ms
08-25 21:49:36.246  1174  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:49:36.246  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 21:49:36.246  4774  6764 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:49:36.246  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 21:49:36.246  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-25 21:49:36.246  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 21:49:36.246  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 21:49:36.246  1174  1174 D StatusBar.NetworkController: updateDataNetType()
,08-25 21:49:36.246  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 21:49:36.246  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-25 21:49:36.256  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.256  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:36.256  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.256  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.256  1018  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 21:49:36.266  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 21:49:36.266  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:36.266  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:36.266  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 21:49:36.266  1635  1635 I Hs20UtilService: Starting #24
08-25 21:49:36.266  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 21:49:36.266  1635  1698 I Hs20UtilService: Message received 5007
08-25 21:49:36.266  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 21:49:36.276  1018  1479 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-25 21:49:36.276  1018  4362 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-25 21:49:36.276  1018  4362 D SecContentProvider2: mCursor = null
,08-25 21:49:36.276  6702  6702 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 21:49:36.276  1018  1356 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-25 21:49:36.276  1018  1356 D SecContentProvider2: mCursor = null
08-25 21:49:36.276  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:36.276  6702  6755 I jxcore-log: 
,08-25 21:49:36.276  1018  1481 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-25 21:49:36.276  1018  1481 D SecContentProvider2: mCursor = null
08-25 21:49:36.276  1018  1499 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-25 21:49:36.276  1018  1499 D SecContentProvider2: mCursor = null
,08-25 21:49:36.286  1018  1031 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-25 21:49:36.286  1018  1031 D SecContentProvider2: mCursor = null
08-25 21:49:36.286  1018  1491 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-25 21:49:36.286  1018  1491 D SecContentProvider2: mCursor = null
,08-25 21:49:36.306   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-25 21:49:36.316  1018  1481 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-25 21:49:36.326  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 21:49:36.336  1018  7577 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 21:49:36.356  7614  7614 D AndroidRuntime: 
08-25 21:49:36.356  7614  7614 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 21:49:36.366  7614  7614 D AndroidRuntime: CheckJNI is OFF
,08-25 21:49:36.366  7614  7614 D AndroidRuntime: readGMSProperty: start
08-25 21:49:36.366  7614  7614 D AndroidRuntime: readGMSProperty: already setted!!
08-25 21:49:36.366  7614  7614 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 21:49:36.366  7614  7614 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 21:49:36.366  7614  7614 D AndroidRuntime: readGMSProperty: end
08-25 21:49:36.366  7614  7614 D AndroidRuntime: addProductProperty: start
,08-25 21:49:36.406  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 19:49:36 GMT], X-Android-Received-Millis=[1472154576415], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472154576379]},
08-25 21:49:36.406  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 21:49:36.406  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
08-25 21:49:36.406  1018  7577 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated,
08-25 21:49:36.406  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 21:49:36.406  1174  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:49:36.406  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,08-25 21:49:36.406  4774  6764 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:49:36.406  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-25 21:49:36.406  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-25 21:49:36.406  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 21:49:36.406  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 21:49:36.406  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-25 21:49:36.406  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-25 21:49:36.406  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 21:49:36.406  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 21:49:36.416  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 21:49:36.416  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 21:49:36.486  6702  6702 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-25 21:49:36.486  6702  6755 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:36.486  6702  6755 I jxcore-log: 
,08-25 21:49:36.496  7614  7614 E AffinityControl: AffinityControl: registerfunction enter,
,08-25 21:49:36.516  7614  7614 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 21:49:36.536  1018  1356 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-25 21:49:36.536  1018  1356 D PackageManager: START PACKAGE DELETE: observer{232528299}
08-25 21:49:36.536  1018  1356 D PackageManager: pkg{<packageName>}
08-25 21:49:36.536  1018  1356 D PackageManager: user{0}
08-25 21:49:36.536  1018  1356 D PackageManager: caller{2000}
08-25 21:49:36.536  1018  1356 D PackageManager: flags{2}
08-25 21:49:36.536  1018  1356 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-25 21:49:36.536  1018  1356 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-25 21:49:36.536  1018  1356 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-25 21:49:36.536  1018  1356 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-25 21:49:36.536  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-25 21:49:36.536  1018  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-25 21:49:36.536  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-25 21:49:36.536  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-25 21:49:36.536  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,08-25 21:49:36.536  1018  1059 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-25 21:49:36.546  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
,08-25 21:49:36.546  1018  1044 I ActivityManager: Killing 6702:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-25 21:49:36.556  1018  1044 I ActivityManager:   Force finishing activity ActivityRecord{18185fb6 u0 com.test.thalitest/.MainActivity t2}
,08-25 21:49:36.556  1018  1044 D InputDispatcher: Focus left window: 6702
,08-25 21:49:36.556   259   441 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-25 21:49:36.556   259   438 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-25 21:49:36.576  1018  1044 D InputDispatcher: Focused application released,
08-25 21:49:36.576  1018  1044 D FocusedStackFrame: Set to : 0
,08-25 21:49:36.576  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 21:49:36.576  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 21:49:36.576  1018  1044 W ActivityManager: mDVFSHelper.acquire(),
,08-25 21:49:36.666  1018  1059 W PackageSettings: Skipping PackageSetting{1acad549 com.example.hello/10168} due to missing metadata
,08-25 21:49:36.716  1018  1044 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-25 21:49:36.726  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-25 21:49:36.736  1018  1059 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-25 21:49:36.736  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:36.746  1018  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-25 21:49:36.756  1483  1483 D Launcher: onRestart, Launcher: 1036657452
,08-25 21:49:36.766  1483  1483 D Launcher: onStart, Launcher: 1036657452
08-25 21:49:36.766  1483  1483 D Launcher.HomeView: onStart
,08-25 21:49:36.766  1483  1483 D Launcher: onResume, Launcher: 1036657452
,08-25 21:49:36.766  1018  4362 D SettingsProvider: name = kids_home_mode
,08-25 21:49:36.766  1018  4362 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 21:49:36.766  1018  4362 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 21:49:36.786  2642  2642 I art     : Explicit concurrent mark sweep GC freed 19558(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 792us total 36.529ms
,08-25 21:49:36.796  1018  4362 D SettingsProvider: selectionArgs: false
,08-25 21:49:36.796  1018  4362 D SettingsProvider: selectionArgs: 10006
08-25 21:49:36.796  1018  4362 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 21:49:36.796  1018  4362 D SettingsProvider: ret = -1
,08-25 21:49:36.796  1483  1483 D Launcher.HomeView: onResume
,08-25 21:49:36.806  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 21:49:36.806  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-25 21:49:36.816  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-25 21:49:36.816  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-25 21:49:36.816  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-25 21:49:36.816  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-25 21:49:36.826  4774  4774 I art     : Explicit concurrent mark sweep GC freed 22356(1368KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.659ms total 86.752ms
,08-25 21:49:36.826  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-25 21:49:36.836  1878  1878 E SamsungIME: mOCRHelper is null
,08-25 21:49:36.836  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-25 21:49:36.836  1987  2155 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 21:49:36.846  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 21:49:36.856  1456  1456 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 21:49:36.876  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-25 21:49:36.876  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.876  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-25 21:49:36.876  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 21:49:36.876  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 21:49:36.886  1018  1124 V NetworkStats: performPollLocked() took 12ms
08-25 21:49:36.886  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:36.896  2874  2874 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 21:49:36 GMT+02:00 2016
08-25 21:49:36.896  1483  1483 D MenuAppsGridFragment: onResume
,08-25 21:49:36.896  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 21:49:36.896  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-25 21:49:36.896  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-25 21:49:36.896  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 21:49:36.896  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:36.896  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:36.896  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 21:49:36.906  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-25 21:49:36.916  1442  1442 D RegisteredServicesCache: empty dynamic service
,08-25 21:49:36.916  1018  1207 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-25 21:49:36.916  1018  1207 D SecContentProvider2: mCursor = null
,08-25 21:49:36.916  2874  2874 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 21:49:36.916  1018  1478 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-25 21:49:36.916  1018  1478 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-25 21:49:36.916  1018  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-25 21:49:36.926  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.926  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.926  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.926  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:36.936  7633  7633 E Zygote  : MountEmulatedStorage(),
,08-25 21:49:36.946  7633  7633 E Zygote  : v2,
08-25 21:49:36.946  1018  1478 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7633 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-25 21:49:36.946  7633  7633 I libpersona: KNOX_SDCARD checking this for 10090
,08-25 21:49:36.946  7633  7633 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:36.946  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
08-25 21:49:36.946  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-25 21:49:36.946  7633  7633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:36.946  2874  2874 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 21:49:36.946  7633  7633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:36.956  7633  7633 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:36.956  1018  1043 W TextServicesManagerService: no available spell checker services found,
,08-25 21:49:36.966  2874  2874 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 21:49:36.966  2874  2874 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-25 21:49:36.966  1018  1030 D ActivityManager: handle home activity for 0
08-25 21:49:36.966  1018  1030 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-25 21:49:36.966  1018  1030 D KnoxTimeoutHandler: post home show event for user 0
08-25 21:49:36.966  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-25 21:49:36.966  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 21:49:36.966  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 21:49:36.966  1483  1483 D Launcher.HomeView: onPause
,08-25 21:49:36.966  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 21:49:36.966  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,08-25 21:49:36.976  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-25 21:49:36.976  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 21:49:36.996  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 21:49:36.996  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 21:49:36.996  7633  7633 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:36.996  7633  7633 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:36.996  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-25 21:49:36.996   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-25 21:49:36.996  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-25 21:49:36.996  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.996  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.996  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:36.996  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.006  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-25 21:49:37.006  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.016  1018  1479 I TactileAssist: enable value -1,
,08-25 21:49:37.016  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 21:49:37.016  1018  1479 I TactileAssist: internal enable value -1
08-25 21:49:37.016  7648  7648 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:37.016  1018  1479 I TactileAssist: intensity value -1
08-25 21:49:37.016  7648  7648 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:37.016  1018  1479 I TactileAssist: saveAppList value true
08-25 21:49:37.016  7648  7648 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.016  7648  7648 E Zygote  : v2
,08-25 21:49:37.016  7648  7648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.016  7648  7648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:37.016  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 21:49:37.016  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-25 21:49:37.016  7648  7648 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.016  1018  1044 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 21:49:37.026  1018  1481 D InputDispatcher: Focus entered window: 1483
08-25 21:49:37.026  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 21:49:37.026  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 21:49:37.026  1483  1483 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 21:49:37.036  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 21:49:37.036  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-25 21:49:37.036  1018  1479 I TactileAssist: List of disabled apps :
,08-25 21:49:37.036  1018  1356 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 21:49:37.046  1018  1356 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6702 uid 10171
,08-25 21:49:37.046  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 21:49:37.056  1878  1878 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-25 21:49:37.056  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-25 21:49:37.056  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.056  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.056  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.056  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.056  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.056  1018  1059 I art     : Explicit concurrent mark sweep GC freed 78460(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/37MB, paused 12.403ms total 294.379ms
08-25 21:49:37.056  1018  7658 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 21:49:37.066  7648  7648 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.066  7648  7648 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.076  7666  7666 E Zygote  : MountEmulatedStorage()
,08-25 21:49:37.076  7666  7666 E Zygote  : v2
08-25 21:49:37.076  7666  7666 I libpersona: KNOX_SDCARD checking this for 1000
,08-25 21:49:37.076  7666  7666 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.076  7666  7666 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 21:49:37.076  7666  7666 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:37.076  1018  1044 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 21:49:37.076  7666  7666 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 21:49:37.096  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 21:49:37.116  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-25 21:49:37.126  1018  1059 D PackageManager: delete codoeFile: 
,08-25 21:49:37.126  2874  7632 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-25 21:49:37.136  7666  7666 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.136  7666  7666 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.136  1018  1044 W ActivityManager: mDVFSHelper.release()
,08-25 21:49:37.146  2874  7632 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-25 21:49:37.146  7633  7633 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-25 21:49:37.146  7633  7633 D elm:15121: ELMEngine.ELMEngine( context ).
,08-25 21:49:37.156  7633  7633 D elm:15121: MDMBridge.setEnterpriseBridge()
08-25 21:49:37.156  1018  1059 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-25 21:49:37.156  1018  1059 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-25 21:49:37.156  1018  1059 D PackageManager: result of delete: 1{232528299}
,08-25 21:49:37.156  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 21:49:37.156  1018  3339 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-25 21:49:37.156  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-25 21:49:37.156  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-25 21:49:37.156  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 21:49:37.156  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 21:49:37.156  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 21:49:37.166  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 21:49:37.166  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 21:49:37.166  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 21:49:37.166  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 21:49:37.166  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-25 21:49:37.166  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-25 21:49:37.166  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 21:49:37.166  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 21:49:37.166  7614  7614 D AndroidRuntime: Shutting down VM
,08-25 21:49:37.166  1174  1174 I StatusBar: Icon Only
,08-25 21:49:37.166  1174  1174 D PanelView: There is/are notification(s) 
,08-25 21:49:37.166  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.166  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32b5679d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147798
,08-25 21:49:37.176  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-25 21:49:37.176  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.176  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.176  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.176  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.176  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.176  2874  2874 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 21:49:37.186  7681  7681 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.186  7681  7681 I libpersona: KNOX_SDCARD checking this for 10048
,08-25 21:49:37.186  7681  7681 E Zygote  : v2
08-25 21:49:37.186  7681  7681 I libpersona: KNOX_SDCARD not a persona
08-25 21:49:37.186  7681  7681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.196  7681  7681 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:37.196  1018  1481 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7681 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-25 21:49:37.196  7681  7681 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.196  1018  1162 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-25 21:49:37.196  1018  1480 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-25 21:49:37.196  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-25 21:49:37.196  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:37.196  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:37.196  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-25 21:49:37.196  7633  7633 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-25 21:49:37.206  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 21:49:37.206  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.206  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.206  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.206  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.216  7633  7633 D elm:15121: ElmAgentService : onCreate()
,08-25 21:49:37.216  7633  7688 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-25 21:49:37.216  7633  7688 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-25 21:49:37.216  7633  7688 D elm:15121: MDMBridge.getInstance()
08-25 21:49:37.216  7633  7688 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-25 21:49:37.216  7633  7688 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-25 21:49:37.216  7690  7690 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.216  7690  7690 E Zygote  : v2
08-25 21:49:37.216  7690  7690 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:37.216  7690  7690 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.216  7690  7690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.226  7690  7690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:37.226  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 21:49:37.226  7690  7690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.226  7648  7648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-25 21:49:37.236  1018  1491 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-25 21:49:37.236  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-25 21:49:37.236  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 21:49:37.236  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 21:49:37.236  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-25 21:49:37.236  7666  7666 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-25 21:49:37.246  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-25 21:49:37.246  7681  7681 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.246  7681  7681 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:37.246  7690  7690 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.256  7690  7690 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.256  1018  1137 D SecContentProvider2: uri = -1 selection = getSealedState
08-25 21:49:37.256  1018  1137 D SecContentProvider2: mCursor = null
,08-25 21:49:37.256  1018  1356 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-25 21:49:37.256  1018  1356 D SecContentProvider2: mCursor = null
,08-25 21:49:37.256  7666  7666 I PopupuiReceiver_KNOX: getSealedState : true
08-25 21:49:37.256  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-25 21:49:37.256  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.256  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.256  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.256  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.266  1018  1481 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-25 21:49:37.266  1018  1481 D SecContentProvider2: mCursor = null
,08-25 21:49:37.266  7666  7666 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-25 21:49:37.266  1018  1499 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,08-25 21:49:37.266  1018  1499 D SecContentProvider2: mCursor = null
,08-25 21:49:37.266  7666  7666 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-25 21:49:37.266  7666  7666 D PopupuiReceiver: Action package removed
,08-25 21:49:37.276  7715  7715 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.276  7715  7715 I libpersona: KNOX_SDCARD checking this for 1000
08-25 21:49:37.276  7715  7715 E Zygote  : v2
08-25 21:49:37.276  7715  7715 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.276  7715  7715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.276  7715  7715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:37.276  1018  1031 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 21:49:37.276  7715  7715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 21:49:37.276  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-25 21:49:37.276  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.276  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.276  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.276  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.296  7730  7730 E Zygote  : MountEmulatedStorage(),
08-25 21:49:37.296  7730  7730 E Zygote  : v2
08-25 21:49:37.296  7730  7730 I libpersona: KNOX_SDCARD checking this for 10145
08-25 21:49:37.296  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:37.296  7730  7730 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.306  1018  1031 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7730 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 21:49:37.306  7715  7715 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 21:49:37.306  1018  1031 I ActivityManager: Killing 7028:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-25 21:49:37.306  7715  7715 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.306  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:37.306  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.316  1018  1031 I ActivityManager: Killing 7090:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-25 21:49:37.316  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-25 21:49:37.316  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.316  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.326  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.326  7730  7730 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.336  7633  7633 D elm:15121: ElmAgentService : onDestroy().
,08-25 21:49:37.336  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.336  7681  7681 D Compatibility: onReceive() it will make start service
,08-25 21:49:37.346  1018  1031 I ActivityManager: Killing 7076:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-25 21:49:37.346  1018  4362 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-25 21:49:37.346  1018  4362 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-25 21:49:37.346  1018  4362 W ActivityManager: userId = 0, bbcId = -10000
,08-25 21:49:37.356  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 21:49:37.356  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:49:37.356  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 21:49:37.356  1018  4362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 21:49:37.356  1018  4362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-25 21:49:37.356  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.356  7715  7715 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 21:49:37.366  7690  7690 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-25 21:49:37.366  7690  7690 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 21:49:37.366  7690  7690 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 21:49:37.366  1018  1207 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-25 21:49:37.366  1018  1207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.366  1018  1207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.366  1018  1207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.366  1018  1207 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.376  7681  7746 D Compatibility: onHandleIntent(),
08-25 21:49:37.376  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 21:49:37.376  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.386  7681  7746 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}],
08-25 21:49:37.386  7681  7746 D Compatibility: found: 2
,08-25 21:49:37.386  7614  7614 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
08-25 21:49:37.386  7747  7747 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.386  7747  7747 E Zygote  : v2
08-25 21:49:37.386  7747  7747 I libpersona: KNOX_SDCARD checking this for 10052
08-25 21:49:37.386  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 21:49:37.386  7747  7747 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.386  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:37.386  7681  7746 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-25 21:49:37.396  7715  7715 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-25 21:49:37.396  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 21:49:37.396  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 21:49:37.396  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 21:49:37.396  7681  7746 D Compatibility: skipping ResolveInfo{3e5b25e7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-25 21:49:37.396  7681  7746 D Compatibility: considering ResolveInfo{a05b594 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-25 21:49:37.396  7681  7746 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-25 21:49:37.396  1018  1207 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7747 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-25 21:49:37.396  7681  7746 D Compatibility: enabling receiver ResolveInfo{639983d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-25 21:49:37.406  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.406  1018  4362 D PersonaManager: isKioskContainerExistOnDevice
,08-25 21:49:37.406  1018  1478 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,08-25 21:49:37.406  1018  1478 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-25 21:49:37.406  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 21:49:37.406  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 21:49:37.416  7681  7746 D Compatibility: enabling receiver ResolveInfo{2f169832 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-25 21:49:37.416   320   320 I art     : Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 21.364ms
,08-25 21:49:37.426  7681  7746 D Compatibility: enabling receiver ResolveInfo{17aa3983 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-25 21:49:37.436  7730  7730 D ThemeInfoUtil: getCurrentFestivalName is [null]
,08-25 21:49:37.436  7730  7730 D ThemeInfoUtil: isCurrentFestival = false
,08-25 21:49:37.436  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.436  7747  7747 D ActivityThread: Added TimaKeyStore provider
08-25 21:49:37.436  7681  7746 D Compatibility: enabling receiver ResolveInfo{2f529700 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-25 21:49:37.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 21:49:37.436  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-25 21:49:37.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 21:49:37.436   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.544ms
08-25 21:49:37.436  1018  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-25 21:49:37.436  1018  1059 D PackageManager: userId{-1}
08-25 21:49:37.436  1018  1059 D PackageManager: andCode{true}
,08-25 21:49:37.446  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 21:49:37.446  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.446  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.446  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.446  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.446  7681  7746 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-25 21:49:37.456  7465  7481 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 21:49:37.456   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.840ms
,08-25 21:49:37.466  7764  7764 E Zygote  : MountEmulatedStorage()
,08-25 21:49:37.466  7764  7764 E Zygote  : v2
08-25 21:49:37.466  7764  7764 I libpersona: KNOX_SDCARD checking this for 10087
08-25 21:49:37.466  7764  7764 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.466  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.476  1018  1480 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7764 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
08-25 21:49:37.476  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:37.476  1018  1480 I ActivityManager: Killing 7115:com.osp.app.signin/u0a36 (adj 15): empty #21
08-25 21:49:37.476  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-25 21:49:37.476  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-25 21:49:37.476  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.476  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.476  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.476  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.496  7775  7775 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.496  7775  7775 I libpersona: KNOX_SDCARD checking this for 10148
08-25 21:49:37.496  7775  7775 E Zygote  : v2
08-25 21:49:37.496  7775  7775 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.496  7775  7775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.496  7775  7775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 21:49:37.496  7775  7775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.506  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.506  7764  7764 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.506  1018  1480 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7775 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-25 21:49:37.506  1018  1480 I ActivityManager: Killing 7135:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-25 21:49:37.506  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-25 21:49:37.516  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-25 21:49:37.516  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:37.526  1018  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-25 21:49:37.526  7690  7690 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-25 21:49:37.526  7690  7690 I PCWCLIENTTRACE_PushUtil: sales region : global
08-25 21:49:37.526  7690  7690 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 21:49:37.526  7690  7690 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-25 21:49:37.526  7775  7775 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.526  7775  7775 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.536  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.536  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.536  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.536  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.556  7794  7794 E Zygote  : MountEmulatedStorage()
,08-25 21:49:37.556  7794  7794 E Zygote  : v2
08-25 21:49:37.556  7794  7794 I libpersona: KNOX_SDCARD checking this for 10003
08-25 21:49:37.556  7794  7794 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.566  1018  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7794 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
08-25 21:49:37.566  7794  7794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.566  1018  1030 I ActivityManager: Killing 7169:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-25 21:49:37.566  7794  7794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 21:49:37.576  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-25 21:49:37.576  7794  7794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 21:49:37.576  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.576  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.576  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 21:49:37.576  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 21:49:37.586  7804  7804 E Zygote  : MountEmulatedStorage()
08-25 21:49:37.586  7804  7804 I libpersona: KNOX_SDCARD checking this for 10029
08-25 21:49:37.586  7804  7804 E Zygote  : v2
08-25 21:49:37.586  7804  7804 I libpersona: KNOX_SDCARD not a persona
,08-25 21:49:37.596  7804  7804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 21:49:37.596  7794  7794 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-25 21:49:37.596  7804  7804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 21:49:37.596  7794  7794 D ActivityThread: Added TimaKeyStore provider
,08-25 21:49:37.596  7804  7804 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 21:49:37.596  1018  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7804 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-25 21:49:37.596  1018  1030 I ActivityManager: Killing 7043:com.android.chrome/u0a77 (adj 15): empty #21
,08-25 21:49:37.616  7804  7804 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 21:49:37.616  7804  7804 D ActivityThread: Added TimaKeyStore provider

```
