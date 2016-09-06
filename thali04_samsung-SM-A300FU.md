#### Test 82894682e70646c_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
09-06 19:03:07.259  1017  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:03:07.259  1017  1494 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:03:07.259  1017  1494 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:03:07.259  1017  1494 D BatteryService: stay LED for fully charged
09-06 19:03:07.259  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-06 19:03:07.259  1017  1017 I MotionRecognitionService: Plugged
09-06 19:03:07.259  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
09-06 19:03:07.269  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:03:07.269  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:03:07.269  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:03:07.269  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-06 19:03:07.279  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:03:07.279  3156  3266 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:03:07.289  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:07.289  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:07.289  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:07.759  6730  6730 D AndroidRuntime: 
09-06 19:03:07.759  6730  6730 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:03:07.759  6730  6730 D AndroidRuntime: CheckJNI is OFF
09-06 19:03:07.759  6730  6730 D AndroidRuntime: readGMSProperty: start
09-06 19:03:07.759  6730  6730 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:03:07.759  6730  6730 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:03:07.759  6730  6730 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:03:07.759  6730  6730 D AndroidRuntime: readGMSProperty: end
09-06 19:03:07.759  6730  6730 D AndroidRuntime: addProductProperty: start
09-06 19:03:07.899  6730  6730 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:03:07.929  6730  6730 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:03:07.949  1017  1135 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:03:07.949  1017  1135 I PersonaManagerService: PersonaId don't exist
09-06 19:03:07.949  1017  1135 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:03:07.949  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:03:07.969  1017  1135 W ActivityManager: mDVFSHelper.acquire()
09-06 19:03:07.969   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-06 19:03:07.969   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-06 19:03:07.979  1017  1135 D FocusedStackFrame: Set to : 0
09-06 19:03:07.989  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:07.989  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:07.989  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:07.989  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:07.989  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:03:07.989  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:03:07.999  6743  6743 E Zygote  : MountEmulatedStorage()
09-06 19:03:07.999  6743  6743 E Zygote  : v2
09-06 19:03:07.999  6743  6743 I libpersona: KNOX_SDCARD checking this for 10171
09-06 19:03:07.999  6743  6743 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:07.999  1017  1135 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6743 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:03:07.999  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 19:03:07.999  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:03:07.999  1017  1135 D InputDispatcher: Focused application set to: xxxx
09-06 19:03:07.999  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:03:07.999  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:03:07.999  1017  1135 D InputDispatcher: Focus left window: 1496
09-06 19:03:08.009  6730  6730 D AndroidRuntime: Shutting down VM
09-06 19:03:08.009   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-06 19:03:08.009  6743  6743 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:08.009  6743  6743 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:08.009  6743  6743 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:03:08.029  6743  6743 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:03:08.029  6743  6743 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:08.029  1017  1494 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 19:03:08.039  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:03:08.039  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:03:08.039  1017  1017 V ActivityManager: Display changed displayId=0
09-06 19:03:08.039  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:03:08.049   289   289 E SMD     : DCD OFF
09-06 19:03:08.049  1017  1494 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:03:08.069  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 19:03:08.089   259   448 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-06 19:03:08.089   259   444 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-06 19:03:08.099  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{11c6850 token=android.os.BinderProxy@23e77efb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 19:03:08.099  1496  1496 D Launcher: onTrimMemory. Level: 20
09-06 19:03:08.189  6743  6743 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-06 19:03:08.219  6730  6730 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:03:08.249  6743  6743 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 7127-7141)
09-06 19:03:08.249  6743  6743 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:03:08.269  6743  6743 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2abf89a8}
,09-06 19:03:08.269  6743  6743 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:03:08.279  6743  6743 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:03:08.319  6743  6743 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:03:08.319  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:03:08.329  6743  6743 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:03:08.369  6743  6743 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:03:08.369  6743  6743 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:03:08.369  6743  6743 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:03:08.369  6743  6743 I Adreno-EGL: Local Branch: 
09-06 19:03:08.369  6743  6743 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:03:08.369  6743  6743 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:03:08.369  6743  6743 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:03:08.449  6743  6743 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:03:08.479  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-06 19:03:08.479  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-06 19:03:08.489  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-06 19:03:08.489  6743  6743 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-06 19:03:08.559  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{1b2d15ec u0 com.test.thalitest/.MainActivity t2}
,09-06 19:03:08.589  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:03:08.609  6743  6743 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 19:03:08.619  6743  6743 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-06 19:03:08.619  6743  6743 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-06 19:03:08.629  6743  6743 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-06 19:03:08.629  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:03:08.629  6743  6743 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:03:08.669  6743  6781 D OpenGLRenderer: Render dirty regions requested: true
,09-06 19:03:08.669  1017  1492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
,09-06 19:03:08.669  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:03:08.669  1017  1492 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:03:08.669  1017  1492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:03:08.669  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
09-06 19:03:08.679  6743  6770 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-06 19:03:08.679  6743  6743 V ActivityThread: updateVisibility : ActivityRecord{19a0fc08 token=android.os.BinderProxy@35f51625 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-06 19:03:08.679  6743  6743 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:03:08.689  6743  6743 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-06 19:03:08.699   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-06 19:03:08.709  1017  4235 D InputDispatcher: Focus entered window: 6743
,09-06 19:03:08.709  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:03:08.709  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:03:08.709  6743  6743 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:03:08.709  6743  6781 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 19:03:08.719  6743  6781 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-06 19:03:08.719  6743  6781 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:03:08.739  1017  1486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:03:08.739  1171  1171 I StatusBar: Icon Only,
09-06 19:03:08.739  1017  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 19:03:08.739  1171  1171 D PanelView: There is/are notification(s) 
,09-06 19:03:08.759  1017  1047 I ActivityManager: Displayed Component not be shown by security: +703ms (total +775ms)
,09-06 19:03:08.759  1017  1047 W ActivityManager: mDVFSHelper.release()
,09-06 19:03:08.759  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b2d15ec u0 com.test.thalitest/.MainActivity t2} time:107658
,09-06 19:03:08.769  6743  6743 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 19:03:08.769  6743  6743 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35f51625 time:107662
,09-06 19:03:08.769   259   444 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-06 19:03:08.769   259   697 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-06 19:03:08.799  1868  1868 I SamsungIME: getCurrentCandidateView
,09-06 19:03:08.919  1868  1868 D SamsungIME: Dismiss ExpandCandiate
,09-06 19:03:08.939  6743  6743 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6743
,09-06 19:03:09.069  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:03:09.119  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:03:09.129  1868  1868 I SamsungIME: KeybaordView init() : load resources
,09-06 19:03:09.139  6743  6743 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:03:09.159  1868  1868 I SamsungIME: getCurrentKeyboard
09-06 19:03:09.159  1868  1868 I SamsungIME: getTextKeyboard
,09-06 19:03:09.179  1868  1868 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:03:09.229  6743  6789 D jxcore_app_log: JniHelper::setJavaVM(0xb75822b0), pthread_self() = -1213142664,
,09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:03:09.229  6743  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d6c479e added. We now have 1 listener(s)
09-06 19:03:09.239  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-06 19:03:09.239  6743  6789 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:09.239  6743  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:09.239  6743  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:03:09.249  6743  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1150d295 added. We now have 1 listener(s)
,09-06 19:03:09.249  6743  6789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:09.249  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:09.249  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:03:09.259  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:03:09.259  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:03:09.259  6743  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:03:09.259  6743  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:09.259  6743  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27,
,09-06 19:03:09.269  6743  6789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:09.269  6743  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:09.269  6743  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:03:09.269  6743  6789 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:09.269  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:09.279  6743  6789 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:03:09.279  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:09.299  6743  6743 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:03:09.349  1017  1313 E Watchdog: !@Sync 3
,09-06 19:03:09.849  6743  6796 W jxcore-log: Initializing JXcore engine
09-06 19:03:09.849  6743  6796 W jxcore-log: JXcore engine is ready
,09-06 19:03:09.909  1986  1986 E audit   : type=1400 msg=audit(1473181389.909:205): avc:  denied  { ioctl } for  pid=6796 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 19:03:09.909  1986  1986 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:09.909  1986  1986 E audit   : type=1300 msg=audit(1473181389.909:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eafb8f8 items=0 ppid=305 ppcomm=main pid=6796 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:03:09.909  1986  1986 E audit   : type=1320 msg=audit(1473181389.909:205): 
,09-06 19:03:09.919  6743  6796 W jxcore-log: Starting JXcore engine
,09-06 19:03:10.029  6743  6796 W jxcore-log: Platform android
09-06 19:03:10.029  6743  6796 W jxcore-log: 
09-06 19:03:10.029  6743  6796 W jxcore-log: Process ARCH arm
09-06 19:03:10.029  6743  6796 W jxcore-log: 
,09-06 19:03:10.039   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 19:03:10.039   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 19:03:10.229  6743  6796 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:03:10.229  6743  6796 I jxcore-log: 
,09-06 19:03:10.229  6743  6796 W jxcore-log: JXcore engine is started
,09-06 19:03:10.239  6743  6789 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:03:10.239  6743  6743 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:03:11.049   289   289 E SMD     : DCD OFF,
,09-06 19:03:14.049   289   289 E SMD     : DCD OFF,
,09-06 19:03:14.329  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,09-06 19:03:14.619  1017  3321 D SSRM:n  : SIOP:: AP = 330
,09-06 19:03:15.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:15.589  5608  5608 D FactoryTest: Not factory mode
,09-06 19:03:15.589  5608  5608 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:03:15.599  5608  5608 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 19:03:15.599  5608  5608 D MTPRx   : still no open session command from host, so toast
,09-06 19:03:15.599  5608  5608 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
09-06 19:03:15.599  5608  5608 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 19:03:15.599  5608  5608 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114496
09-06 19:03:15.599  1017  4235 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:03:15.599  1017  4235 I PersonaManagerService: PersonaId don't exist
09-06 19:03:15.599  1017  4235 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:03:15.609  1017  4235 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-06 19:03:15.609  1017  4235 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:15.609  1017  4235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:15.609  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 19:03:15.609  1017  4235 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:03:15.629  1017  4235 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:03:15.639  1017  4235 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:03:15.639  1017  4235 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:03:15.639  1017  4235 D InputDispatcher: Focused application set to: xxxx
09-06 19:03:15.639  1017  4235 D InputDispatcher: Focus left window: 6743
,09-06 19:03:15.639  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:03:15.639  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:03:15.659  5608  5608 E MTPRx   : started activity for popup
,09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:03:15.689  5608  5608 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:03:15.709  5608  5608 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:03:15.709  1017  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:03:15.719  1017  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:03:15.719  1017  1492 D InputDispatcher: Focused application set to: xxxx
,09-06 19:03:15.719  1017  1492 D InputDispatcher: Focus entered window: 6743
,09-06 19:03:15.719  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:03:15.719  1017  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:03:15.719  1017  1494 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3dedb16f attribute=null, token = android.os.BinderProxy@6ef2a7f
,09-06 19:03:15.719  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:03:15.759  5608  5608 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:03:15.769  5608  5608 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 19:03:15.769  5608  5608 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:03:15.789  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:03:15.789  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 19:03:15.789  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:03:15.789  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:03:15.799  1017  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:03:15.799  1017  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:03:15.799  1017  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:03:15.799  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:03:15.799  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:03:15.809  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:03:15.809  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:03:15.809  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@330f9831 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29b8863e, 16908290=android.view.AbsSavedState$1@29b8863e}, android:focusedViewId=100}]}]
09-06 19:03:15.809  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:03:15.809  6743  6743 V ActivityThread: updateVisibility : ActivityRecord{19a0fc08 token=android.os.BinderProxy@35f51625 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-06 19:03:15.809  6743  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:03:15.809  6743  6743 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-06 19:03:15.809  6743  6743 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35f51625 time:114708
,09-06 19:03:15.829  1017  1461 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:03:16.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:17.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:17.049   289   289 E SMD     : DCD OFF,
,09-06 19:03:17.319  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:03:17.319  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:03:17.319  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:03:17.319  1017  1030 D BatteryService: stay LED for fully charged
,09-06 19:03:17.319  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:03:17.319  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:03:17.319  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:03:17.319  1017  1017 I MotionRecognitionService: Plugged
,09-06 19:03:17.319  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:03:17.329  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:03:17.329  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:03:17.339  3156  3156 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:03:17.339  3156  3266 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:03:17.349  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:17.349  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:17.349  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:18.039  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-06 19:03:18.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:18.609  1017  1042 W ActivityManager: mDVFSHelper.release()
,09-06 19:03:19.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:20.049   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-06 19:03:20.049   289   289 E SMD     : DCD OFF,
,09-06 19:03:21.109  1017  1095 V AlarmManager: waitForAlarm result :4
,09-06 19:03:21.119  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,09-06 19:03:21.139  2002  2002 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-06 19:03:21.169  1017  4970 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:21.169  1017  4970 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.169  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.169  1017  4970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:21.169  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.229  4799  4799 D ConnectivityManager: CallingUid : 10011, CallingPid : 4799
,09-06 19:03:21.229  1017  4970 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:03:21.229  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-06 19:03:21.229  1017  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 19:03:21.239  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-06 19:03:21.239  4799  6805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:03:21.289  4799  6806 W DriveInitializer: Background init thread started
,09-06 19:03:21.319   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 19:03:21.319   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:21.319  4799  6806 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-06 19:03:21.389  1017  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:21.389  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.389  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.399  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:21.399  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.409  1017  1494 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-06 19:03:21.409  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.439  1017  4235 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:21.439  1017  4235 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.439  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:21.439  1017  4235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:21.439  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.479  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:03:21.499  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.499  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:21.499  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.509  1017  1486 I art     : Explicit concurrent mark sweep GC freed 36118(2030KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 3.647ms total 163.611ms
,09-06 19:03:21.529  4799  6809 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-06 19:03:21.529  4799  6809 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-06 19:03:21.579  4799  6806 W DriveInitializer: Background init thread ended
,09-06 19:03:21.659  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:21.659  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.659  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.659  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:21.659  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.689  2002  2010 I art     : Explicit concurrent mark sweep GC freed 69685(4MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 10MB/17MB, paused 1.310ms total 72.172ms
,09-06 19:03:21.699  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:21.699  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 19:03:21.699  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:21.699  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:21.699  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.779  1017  4970 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:21.789  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.789  1017  4970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:21.789  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.789  1017  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:21.799  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.799  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:21.799  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.879  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:21.879  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:21.879  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:21.879  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:21.879  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:21.879  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:21.879  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:21.879  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:21.899  6819  6819 E Zygote  : MountEmulatedStorage(),
09-06 19:03:21.899  6819  6819 E Zygote  : v2
09-06 19:03:21.899  6819  6819 I libpersona: KNOX_SDCARD checking this for 10011
09-06 19:03:21.899  6819  6819 I libpersona: KNOX_SDCARD not a persona,
09-06 19:03:21.899  6819  6819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:21.899  6819  6819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:21.899  1017  1492 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6819 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
09-06 19:03:21.909  6819  6819 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:03:21.939  6819  6819 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:21.939  6819  6819 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:21.959  6819  6819 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:03:21.959  6819  6819 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:03:21.999  6819  6819 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:03:21.999  6819  6819 I MultiDex: install
09-06 19:03:21.999  6819  6819 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:03:22.029  6819  6819 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 19:03:22.089  6819  6819 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:03:22.089  6819  6819 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1960cee4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:03:22.089  6819  6819 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:03:22.119  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 19:03:22.119  6819  6819 D ChimeraCfgMgr: Reading stored module config
,09-06 19:03:22.129  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:22.129  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:22.129  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.129  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.159  1017  3357 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:22.159  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:22.159  1017  3357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.159  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.219  1017  1331 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:03:22.219  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:03:22.219  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:22.219  1017  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.219  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.229  6819  6836 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-06 19:03:22.229  2002  2002 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5ee78a43-b17a-4abd-8270-9a8770569151
,09-06 19:03:22.249  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:03:22.249  2002  2002 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:03:22.259  6819  6819 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:03:22.259  6819  6819 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:03:22.269  1017  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:03:22.269  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:22.269  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.269  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.339   284   685 D WVCdm   : Instantiating CDM.
,09-06 19:03:22.349   284   678 I WVCdm   : CdmEngine::OpenSession
,09-06 19:03:22.349   284   678 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-06 19:03:22.369   284   678 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-06 19:03:22.389   284   678 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-06 19:03:22.419  4317  4383 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 1.400ms total 25.534ms
,09-06 19:03:22.439   284   678 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-06 19:03:22.439   284   685 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-06 19:03:22.439   284   685 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-06 19:03:22.439   284   685 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-06 19:03:22.449   284   685 D WVCdm   : PrepareKeyRequest: nonce=1911854094
,09-06 19:03:22.459  6819  6827 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 19:03:22.459  6819  6827 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:22.459  6819  6827 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:03:22.459  6819  6827 I System.out: (HTTPLog)-Thread-1225-72340097: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:03:22.459  6819  6827 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:22.459   279   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:03:22.459   279   999 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:03:22.509  6819  6827 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:03:22.509  6819  6827 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6819, getuid(): 10011
,09-06 19:03:22.509  2002  2146 W GCoreFlp: No location to return for getLastLocation()
,09-06 19:03:22.549  1017  4970 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:22.559  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:22.559  1017  4970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.559  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.559  1017  4970 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:22.559  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:22.559  1017  4970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.559  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.569  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:22.569  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:22.569  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.569  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.579  4799  6815 D UdcContextInitService: registered all accounts: true
,09-06 19:03:22.589  2002  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:03:22.599  2002  2164 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 19:03:22.719  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:03:22.719  6743  6796 I jxcore-log: 
,09-06 19:03:22.719  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:03:22.719  6743  6796 I jxcore-log: 
,09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:22.729  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:22.729  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:22.729  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:03:22.729  6743  6796 I jxcore-log: 
,09-06 19:03:22.739  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:03:22.739  6743  6796 I jxcore-log: 
,09-06 19:03:22.749  1017  1135 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:03:22.759  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:03:22.759  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:22.759  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:22.759  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:22.859  1017  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 19:03:22.899  6819  6827 I qtaguid : Untagging socket 33
,09-06 19:03:23.049   289   289 E SMD     : DCD OFF,
,09-06 19:03:23.229  6848  6848 I dex2oat : ----------------------------------------------------
09-06 19:03:23.229  6848  6848 I dex2oat : <SS>: S T A R T I N G . . .
09-06 19:03:23.229  6848  6848 I dex2oat : <SS>: Zip is absent. Canceled.
,09-06 19:03:23.229  6848  6848 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:03:23.269  6848  6848 I dex2oat : dex2oat took 43.246ms (threads: 4)
,09-06 19:03:23.289  6819  6827 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:03:23.289  6819  6827 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:03:23.289  6819  6827 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:03:23.289  6819  6827 I Adreno-EGL: Local Branch: 
09-06 19:03:23.289  6819  6827 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:03:23.289  6819  6827 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:03:23.289  6819  6827 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:03:23.359  6819  6827 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:03:23.359  6819  6827 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:03:23.359  6819  6827 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:03:23.359  6819  6827 I Adreno-EGL: Local Branch: 
09-06 19:03:23.359  6819  6827 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:03:23.359  6819  6827 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:03:23.359  6819  6827 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:03:23.399  6819  6827 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:03:23.399  6819  6827 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:03:23.399  6819  6827 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:03:23.399  6819  6827 I Adreno-EGL: Local Branch: 
09-06 19:03:23.399  6819  6827 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:03:23.399  6819  6827 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:03:23.399  6819  6827 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:03:23.449  6743  6796 D executeNativeTests: Running unit tests
,09-06 19:03:23.529  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:23.539  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f added. We now have 2 listener(s)
,09-06 19:03:23.539  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:23.539  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:23.539  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:23.539  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:23.539  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c added. We now have 2 listener(s)
09-06 19:03:23.539  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:23.539  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:23.539  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:23.539  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:23.549  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:23.549  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:23.549  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.549  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:23.549  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:03:23.549  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:23.549  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:03:23.549  6743  6796 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:03:23.559  6743  6796 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:03:23.559  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:23.559  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:03:23.559  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.559  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:23.559  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.559  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:23.559  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f removed from the list
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.559  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c removed from the list
09-06 19:03:23.559  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.559  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:23.559  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.559  6743  6796 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:03:23.559  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.559  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.559  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:23.559  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.559  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.559  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.559  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.559  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.559  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.559  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:03:23.569  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.569  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:23.569  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.569  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list,
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.569  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.569  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.569  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.569  6743  6796 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:03:23.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:23.579  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:23.579  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.579  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:23.579  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:23.579  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:23.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:23.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:23.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:23.579  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:23.579  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:03:23.589  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:23.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:03:23.599  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:03:23.609  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:03:23.609  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-06 19:03:23.609  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:23.609  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:23.609  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:03:23.629  3156  3165 D BtGatt.GattService: registerClient() - UUID=011c5dc5-2f58-44a8-a51d-6a650189ac5e
,09-06 19:03:23.669  3156  3254 D BtGatt.GattService: onClientRegistered() - UUID=011c5dc5-2f58-44a8-a51d-6a650189ac5e, clientIf=6
,09-06 19:03:23.679  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:03:23.679  3156  3358 D BtGatt.GattService: start scan with filters
,09-06 19:03:23.679  3156  3262 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:23.679  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:03:23.679  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:23.679  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:23.679  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:23.679  3156  3262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:23.679  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:23.679  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:03:23.679  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:23.689  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:23.689  3156  3254 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:03:23.689  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.689  3156  3262 D BtGatt.ScanManager: allow scan with filters
09-06 19:03:23.689  3156  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:03:23.689  6743  6796 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:03:23.689  3156  3262 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:03:23.699  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:23.699  6743  6796 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:23.699  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:23.699  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:23.699  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:23.699  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:03:23.699  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:23.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:23.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:23.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:23.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:23.699  3156  3262 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:03:23.699  3156  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:03:23.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:23.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:23.699  3156  3168 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:23.709  3156  3165 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:03:23.709  3156  3254 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:03:23.709  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:23.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:23.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:23.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:23.709  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.709  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:23.709  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.709  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.709  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.709  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.709  6743  6796 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:03:23.709  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.709  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:23.719  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:23.719  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:03:23.719  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:23.719  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:23.719  3156  3262 D BtGatt.ScanManager: filter size is 1
09-06 19:03:23.719  3156  3262 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:03:23.719  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-06 19:03:23.719  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:23.719  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:23.719  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:23.719  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:03:23.719  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:23.719  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:23.729  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:23.729  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:03:23.729  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.729  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.729  3156  3262 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:23.729  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:23.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:23.739  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:03:23.739  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.739  3156  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:03:23.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:23.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:23.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:23.739  3156  3358 D BtGatt.GattService: registerClient() - UUID=1559cd5a-55b0-4ae1-bd41-a4da721520dc
,09-06 19:03:23.739  3156  3254 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:03:23.739  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.789  3156  3254 D BtGatt.GattService: onClientRegistered() - UUID=1559cd5a-55b0-4ae1-bd41-a4da721520dc, clientIf=6,
09-06 19:03:23.789  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:03:23.789  3156  3256 D BtGatt.GattService: start scan with filters,
09-06 19:03:23.789  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:23.789  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:23.789  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:23.789  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-06 19:03:23.789  3156  3262 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:23.789  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:23.789  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:23.789  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:23.799  3156  3254 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:03:23.799  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.799  3156  3262 D BtGatt.ScanManager: allow scan with filters
,09-06 19:03:23.799  3156  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:03:23.799  3156  3262 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:03:23.799  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:23.799  6743  6796 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:03:23.799  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-06 19:03:23.799  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.799  3156  3262 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:23.799  3156  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:03:23.799  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:23.809  6743  6796 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:23.809  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:23.809  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:23.809  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:03:23.809  3156  3254 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:03:23.809  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:23.809  3156  3165 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:23.809  3156  3358 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:23.809  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:03:23.809  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:23.809  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:23.809  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:23.819  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.819  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.819  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:23.819  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.819  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.819  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.819  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.819  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:23.819  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:23.819  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.819  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.819  3156  3262 D BtGatt.ScanManager: filter size is 1
09-06 19:03:23.819  3156  3262 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.819  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.819  6743  6796 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:03:23.819  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:23.819  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:03:23.819  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.819  3156  3262 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:23.829  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:23.829  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.829  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:23.829  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:23.829  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:23.829  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:23.829  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:23.829  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:23.829  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:03:23.829  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.829  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.829  3156  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:03:23.829  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.839  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:23.839  3156  3254 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:03:23.839  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.849  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:23.849  1017  1461 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 19:03:23.849  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 19:03:23.849  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:23.849  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:23.849  1017  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:23.849  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:23.859  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:23.859  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:03:23.859  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:23.869  3156  3358 D BtGatt.GattService: registerClient() - UUID=177e0cce-0f53-456d-ab28-18221eb6ce15
,09-06 19:03:23.879  2002  6817 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-06 19:03:23.879  2002  6817 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:23.879  2002  6817 I System.out: (HTTPLog)-Static: isShipBuild true
,09-06 19:03:23.879  2002  6817 I System.out: (HTTPLog)-Thread-266-5626484: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:03:23.879  2002  6817 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:23.889   279   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:03:23.889   279   999 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:03:23.899  2002  6817 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:03:23.899  2002  6817 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2002, getuid(): 10011
,09-06 19:03:23.909  3156  3254 D BtGatt.GattService: onClientRegistered() - UUID=177e0cce-0f53-456d-ab28-18221eb6ce15, clientIf=6
,09-06 19:03:23.909  6743  6752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:03:23.909  3156  3168 D BtGatt.GattService: start scan with filters
09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: handling starting scan
09-06 19:03:23.909  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:03:23.909  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:23.909  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:03:23.909  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:23.909  3156  3254 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:03:23.909  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: allow scan with filters
09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:03:23.909  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:03:23.909  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:23.909  3156  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 19:03:23.909  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:23.909  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:03:23.909  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:23.919  3156  3254 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:03:23.919  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.919  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:23.919  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:03:23.919  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.919  6743  6796 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:03:23.919  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.919  6743  6796 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:03:23.929  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:23.929  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:23.929  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:23.929  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:23.929  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 19:03:23.929  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:23.929  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:23.929  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:03:23.929  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:23.929  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:23.929  3156  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:23.929  3156  3262 D BtGatt.ScanManager: filter size is 1
,09-06 19:03:23.929  3156  3262 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:03:23.929  3156  3168 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:03:23.929  3156  3254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:03:23.929  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.929  3156  3262 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:23.939  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:23.939  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:23.939  3156  3254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:03:23.939  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:23.939  3156  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:03:23.939  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:23.939  3156  3254 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:03:23.939  3156  3254 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:23.939  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.939  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.939  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.939  6743  6796 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:23.939  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.939  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.939  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.939  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:23.939  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.939  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.939  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.939  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.939  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:23.939  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.939  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:03:23.949  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:03:23.949  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.949  6743  6796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:03:23.949  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.949  6743  6796 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:03:23.949  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.949  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.949  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.949  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.949  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.949  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.949  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.959  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:03:23.959  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:03:23.959  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:03:23.959  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.959  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.959  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.959  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.959  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.959  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.959  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.959  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.959  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.959  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.959  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.959  2002  6817 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2002, getuid(): 10011
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.959  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
,09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:03:23.959  6743  6796 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-06 19:03:23.959  6743  6796 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:03:23.959  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:03:23.959  6743  6796 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:23.959  6743  6796 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:23.959  6743  6796 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:23.959  6743  6796 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:03:23.959  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:23.959  6743  6796 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:23.959  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:03:23.969  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:03:23.969  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:03:23.969  6743  6796 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:23.969  6743  6796 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:03:23.969  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.969  6743  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
09-06 19:03:23.969  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.969  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.969  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.969  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.969  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:03:23.969  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.969  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.969  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.969  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.969  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.969  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.969  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.969  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.969  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6859 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:03:23.979  6743  6796 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:23.979  6743  6796 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:03:23.979  6743  6796 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:03:23.979  6743  6796 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.979  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.979  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.979  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.979  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.979  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.979  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:23.989  6743  6743 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:03:23.989  6743  6743 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.989  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.989  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.989  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:23.989  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.989  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:23.989  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.989  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.989  6743  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:03:23.989  6743  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:03:23.989  6743  6796 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:03:23.989  6743  6796 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:03:23.989  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:23.989  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.989  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.989  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.989  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.989  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.989  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.989  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.999  6743  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:03:23.999  6743  6859 D BluetoothSocket: connect(): myUserId = 0
09-06 19:03:23.999  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.999  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.999  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.999  6743  6859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.999  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:23.999  3156  3358 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.999  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:23.999  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:23.999  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e638b8f not in the list
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:23.999  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.999  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:23.999  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:23.999  6743  6859 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:23.999  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:23.999  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24822e1c not in the list
09-06 19:03:24.009  6743  6796 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:24.009  6743  6796 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:24.009  6743  6796 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:03:24.009  6743  6796 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:03:24.009  6743  6796 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:03:24.009  6743  6796 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:03:24.009  6743  6796 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:03:24.009  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:24.009  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dc7fb9e added. We now have 2 listener(s)
09-06 19:03:24.009  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:24.009  6743  6796 D BluetoothAdapter: enable()
09-06 19:03:24.019  6743  6796 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:03:24.019  1017  1463 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:03:24.019  1017  1463 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:03:24.019  1017  1463 D SecContentProvider2: mCursor = null
09-06 19:03:24.019  1017  1463 D WifiService: setWifiEnabled: true pid=6743, uid=10171
09-06 19:03:24.019  1017  1463 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:24.019   284   284 I WVCdm   : CdmEngine::CloseSession
09-06 19:03:24.029  1017  1463 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:03:24.029  1017  1463 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:24.029  1017  1463 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:03:24.029  1017  1463 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:03:24.029  1017  1463 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:03:24.029  1017  1463 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:03:24.029  1017  1463 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:03:24.029  1017  1463 D SettingsProvider: name = wifi_on
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1704767f added. We now have 3 listener(s)
09-06 19:03:24.029  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:24.029   284   284 I WVCdm   : L3 Terminate.
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3b564c added. We now have 4 listener(s)
09-06 19:03:24.029  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:24.029  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e571695 added. We now have 5 listener(s)
09-06 19:03:24.029  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:24.039  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:03:24.039  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:03:24.039  1017  1029 D SecContentProvider2: mCursor = null
09-06 19:03:24.039  1017  1029 D WifiService: setWifiEnabled: false pid=6743, uid=10171
09-06 19:03:24.039  1017  1029 D SettingsProvider: name = wifi_on
,09-06 19:03:24.039  1017  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
09-06 19:03:24.039  6743  6796 D BluetoothAdapter: disable()
,09-06 19:03:24.039  1383  1383 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:03:24.039  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:03:24.049  1383  1383 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:03:24.049  1017  1486 D SettingsProvider: name = bluetooth_on
09-06 19:03:24.049  1383  1383 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:03:24.049  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:24.059  3156  3249 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:03:24.059  3156  3249 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:03:24.059  3156  3249 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:03:24.059  1017  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:24.059  3156  3249 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:24.059  1017  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 19:03:24.059  3156  3249 D BluetoothAdapterService: updateAdapterState state is 13
09-06 19:03:24.059  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.059  1017  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-06 19:03:24.059  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:24.069  3156  3249 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:24.069  3156  3249 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:03:24.069  3156  3249 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:03:24.069  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:24.069  3156  3156 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:03:24.069  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:24.069  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.069  3156  3156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e90e75a, channel: 19, state: LISTENING
09-06 19:03:24.069  3156  3156 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e90e75a, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35b9df13, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13cc1d8bmSocket: android.net.LocalSocket@36b1e68 impl:android.net.LocalSocketImpl@44fd281 fd:FileDescriptor[76]
09-06 19:03:24.069  3156  3156 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36b1e68 impl:android.net.LocalSocketImpl@44fd281 fd:FileDescriptor[76]
,09-06 19:03:24.069  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.069  1017  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.069  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:24.069  3156  3249 D BluetoothAdapterProperties: onBluetoothDisable(),
09-06 19:03:24.069  3156  3249 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:03:24.069  1017  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:03:24.069  3156  3249 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:03:24.069  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:24.079  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:24.079  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:03:24.079  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.079  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:24.079  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
09-06 19:03:24.079  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:24.079  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:24.079  3156  3254 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:03:24.079  3156  3254 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:24.079  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:24.089  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:03:24.089  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:03:24.089  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.089  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-06 19:03:24.089  1868  1868 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:03:24.089  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:03:24.089  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:24.099  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:24.099  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:03:24.099  1017  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:24.099  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:03:24.099  3156  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:03:24.099  3156  3249 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:03:24.099  3156  3249 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-06 19:03:24.099  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.099  1017  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.099  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:03:24.099  3156  3249 E bt-btif : cmd socket is not created
09-06 19:03:24.099  3156  3284 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,09-06 19:03:24.099  3156  3284 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:03:24.099  3156  5122 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:03:24.099  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:24.099  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:24.099  3156  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:24.109  3156  3249 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:03:24.109  6743  6859 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d73fb9b, channel: -1, state: INIT
09-06 19:03:24.109  6743  6859 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d73fb9b, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ed8b38, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bdf8711mSocket: android.net.LocalSocket@1179e076 impl:android.net.LocalSocketImpl@248cb677 fd:FileDescriptor[106]
09-06 19:03:24.109  6743  6859 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1179e076 impl:android.net.LocalSocketImpl@248cb677 fd:FileDescriptor[106]
09-06 19:03:24.109  6743  6859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
,09-06 19:03:24.109  1017  1486 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:24.109  1017  4970 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
09-06 19:03:24.109  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:24.109  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:24.119  3156  3156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38e61f26, channel: 5, state: LISTENING
09-06 19:03:24.119  3156  3156 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38e61f26, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d4e1a02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14dd0767mSocket: android.net.LocalSocket@1b07b914 impl:android.net.LocalSocketImpl@162615bd fd:FileDescriptor[74]
09-06 19:03:24.119  3156  3156 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b07b914 impl:android.net.LocalSocketImpl@162615bd fd:FileDescriptor[74]
,09-06 19:03:24.119  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:24.119  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:24.119  3156  3156 I BtOppRfcommListener: stopping Accept Thread
09-06 19:03:24.119  3156  3156 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@160507b2, channel: 12, state: LISTENING
09-06 19:03:24.119  3156  3156 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@160507b2, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c0c8b05, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e28b303mSocket: android.net.LocalSocket@25315280 impl:android.net.LocalSocketImpl@2c2350b9 fd:FileDescriptor[79]
09-06 19:03:24.119  3156  3156 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25315280 impl:android.net.LocalSocketImpl@2c2350b9 fd:FileDescriptor[79]
09-06 19:03:24.119  3156  5122 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:03:24.119  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:24.119  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:03:24.119  1017  1494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:03:24.119  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.129  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.129  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.129  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:03:24.129  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:24.129  3156  3156 V BluetoothOppManager: cleanUp...
,09-06 19:03:24.129  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:24.129  3859  3859 D BluetoothPbap: Proxy object disconnected
09-06 19:03:24.129  3859  3859 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:03:24.129  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:24.139  3859  3859 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:24.139  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:24.149  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:24.149  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:03:24.149  1017  1463 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:03:24.149  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:24.149  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:03:24.149  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:24.149  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:24.159  6868  6868 E Zygote  : MountEmulatedStorage()
09-06 19:03:24.159  6868  6868 E Zygote  : v2
09-06 19:03:24.159  6868  6868 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:03:24.159  6868  6868 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:24.159  6868  6868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:24.159  1017  1463 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6868 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:03:24.169  6868  6868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:24.169  6868  6868 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:24.199  6868  6868 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:24.199  6868  6868 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:24.229  6868  6868 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:03:24.269  6868  6868 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:03:24.269  6868  6868 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-06 19:03:24.269  6868  6868 D UserAnalysis: Create SecureDbHelper
,09-06 19:03:24.269  6868  6868 D IntelligenceServiceApplication: onCreate()
,09-06 19:03:24.279  1017  1494 I ActivityManager: Killing 6445:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-06 19:03:24.279  6868  6868 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:03:24.279  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:03:24.289  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:24.289  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:24.289  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:24.289  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:24.299  6886  6886 E Zygote  : MountEmulatedStorage()
09-06 19:03:24.299  1017  1135 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6886 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:03:24.299  6886  6886 E Zygote  : v2
09-06 19:03:24.299  6886  6886 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:03:24.299  6886  6886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:24.299  6886  6886 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:24.299  3156  3284 W bt-btif : ag scb idx 1 not allocated
09-06 19:03:24.299  3156  3284 W bt-btif : ag scb idx 2 not allocated
09-06 19:03:24.299  3156  3284 E bt-btif : BTA AG is already disabled, ignoring ...
,09-06 19:03:24.309  6886  6886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:24.309  3156  3340 I bt_userial_mct: exiting userial_read_thread
09-06 19:03:24.309  3156  3340 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:03:24.309  3156  3254 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:03:24.309  3156  3286 I bt_vendor: hw_epilog_process
,09-06 19:03:24.309  3156  3254 D bt_userial_mct: userial_close
09-06 19:03:24.309  3156  3254 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:03:24.309  6886  6886 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:03:24.309  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-06 19:03:24.309  6868  6868 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:03:24.319  6868  6868 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:03:24.319  6886  6886 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:24.329  6886  6886 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:24.439   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:03:24.439   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:24.439  6886  6906 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:03:24.449   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:03:24.449   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:24.449  6886  6906 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:03:24.489  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:03:24.549  3156  3254 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:03:24.549  3156  3254 I bt_vendor: bluetooth satus is on
09-06 19:03:24.549  3156  3254 I bt_vendor: bt-vendor : resetting BT status
09-06 19:03:24.549  3156  3254 I bt_vendor: Starting hciattach daemon
09-06 19:03:24.549  3156  3254 I bt_vendor: try to set false
,09-06 19:03:24.549  3156  3254 I bt_vendor: Starting hciattach daemon
,09-06 19:03:24.549  3156  3254 I bt_vendor: try to set false
,09-06 19:03:24.549  3156  3254 I bt_vendor: cleanup
,09-06 19:03:24.559  3156  3284 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 19:03:24.559  3156  3254 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:03:24.559  3156  3254 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 19:03:24.559  3156  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:03:24.559  3156  3249 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:03:24.559  3156  3249 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:03:24.559  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:03:24.559  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:03:24.559  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:03:24.559  1017  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.559  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.559  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.559  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.559  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.559  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:03:24.559  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:24.559  3156  3156 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:24.559  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:24.559  3156  3156 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 19:03:24.559  3156  3156 D BtGatt.GattService: stop()
09-06 19:03:24.559  3156  3156 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:03:24.559  1017  4970 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:24.559  1017  4970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.569  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.569  1017  4970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.569  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.569  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.569  3156  3156 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:03:24.569  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:03:24.569  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:24.569  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:24.569  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.569  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:24.569  3859  3859 D HeadsetProfile: Bluetooth service disconnected
09-06 19:03:24.569  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:03:24.569  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:03:24.569  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.569  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.569  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:24.569  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 19:03:24.569  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:03:24.579  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:03:24.579  1017  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.579  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.579  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.579  1017  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:24.579  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.579  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:03:24.579  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:03:24.579  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:03:24.579  1017  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.579  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.579  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.579  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.579  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.589  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:03:24.589  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:03:24.589  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:03:24.589  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.589  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.589  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.589  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.589  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.589  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:24.589  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:24.589  3156  3249 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:24.589  1017  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.599  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.599  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.599  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.599  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.599  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:03:24.599  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:03:24.599  3156  3249 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:03:24.599  1017  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:24.599  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.599  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.599  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.599  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:24.599  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:24.599  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:24.599  3156  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:24.599  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:24.609  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:03:24.609  3156  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:03:24.609  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:03:24.609  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:03:24.609  3156  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-06 19:03:24.609  3156  3249 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:03:24.609  3156  3249 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:03:24.609  3156  3249 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-06 19:03:24.609  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 19:03:24.609  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:03:24.609  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:03:24.609  3156  3156 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:03:24.609  3156  3249 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 19:03:24.619  3156  3156 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:03:24.619  3156  3156 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:03:24.619  3156  3156 D A2dpService: Received stop request...Stopping profile...
,09-06 19:03:24.619  3156  3275 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:03:24.619  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.619  1017  1017 D BluetoothA2dp: Proxy object disconnected,
09-06 19:03:24.619  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:03:24.619  3859  3859 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:24.619  3859  3859 D A2dpProfile: Bluetooth service disconnected
,09-06 19:03:24.629  3156  3156 D HidService: Received stop request...Stopping profile...
09-06 19:03:24.629  3156  3156 D HidService: Stopping Bluetooth HidService
09-06 19:03:24.629  3156  3156 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:03:24.629  3156  3156 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:03:24.629  3156  3156 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:03:24.629  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.629  3156  3156 D HealthService: Received stop request...Stopping profile...
09-06 19:03:24.629  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.629  3859  3859 D BluetoothInputDevice: Proxy object disconnected
09-06 19:03:24.629  3859  3859 D HidProfile: Bluetooth service disconnected
09-06 19:03:24.629  3156  3156 D PanService: Received stop request...Stopping profile...
09-06 19:03:24.629  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.629  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:03:24.629  3156  3156 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:03:24.629  3859  3859 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:03:24.629  3859  3859 D PanProfile: Bluetooth service disconnected
,09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.639  3859  3859 D BluetoothMap: Proxy object disconnected
09-06 19:03:24.639  3859  3859 D MapProfile: Bluetooth service disconnected
,09-06 19:03:24.639  3156  3156 D SapService: Received stop request...Stopping profile...
09-06 19:03:24.639  3156  3156 D SapService: Stopping Bluetooth SapService
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:03:24.639  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:03:24.639  3156  3156 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:03:24.639  3156  3276 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:03:24.639  3156  3156 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:03:24.639  3156  3156 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-06 19:03:24.639  3859  3859 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:03:24.639  3859  3859 D SapProfile: Bluetooth service disconnected
09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:03:24.639  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-06 19:03:24.639  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
09-06 19:03:24.639  3156  3156 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:24.639  6886  6886 D StrictMode: ,	at java.io.File.exists(File.java:363)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:2,09)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$Me,thodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  3156  3156 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:03:24.649  1017  4235 I ActivityManager: Killing 6339:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:24.639  6886  6886 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:24.639  6886  6886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:24.639  3156  3156 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:03:24.639  3156  3156 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:03:24.639  3156  3156 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:03:24.639  3156  3156 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 19:03:24.639  3156  3156 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 19:03:24.639  3156  3156 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:03:24.639  3156  3156 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 19:03:24.649  3156  3249 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:03:24.649  3156  3249 D BluetoothAdapterProperties: Setting state to 10
09-06 19:03:24.649  3156  3249 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:03:24.649  3156  3249 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:24.649  3156  3249 D BluetoothAdapterService: updateAdapterState state is 10
09-06 19:03:24.649  3156  3249 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:24.649  3156  3249 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:03:24.649  3156  3249 I BluetoothAdapterState: Entering OffState
09-06 19:03:24.649  1464  1487 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.649  1464  1487 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.649  3156  3168 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.649  3156  3168 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.649  3859  3872 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.649  3859  3872 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.649  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:24.659  3859  3879 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:03:24.659  2002  2153 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.659  2002  2153 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.659  1017  3321 D SSRM:n  : SIOP:: AP = 350
09-06 19:03:24.659  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.659  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.659  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 19:03:24.659  3156  3358 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:24.659  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:24.659  1432  1472 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.659  1432  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.669  3859  3872 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:03:24.669  1171  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.669  1171  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.669  3859  3879 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:03:24.669  3859  3879 D Bluetoothsap: Unbinding service...
09-06 19:03:24.669  3859  3946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:24.669  3859  3872 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:03:24.669  6743  6751 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.669  6743  6751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.669  6743  6751 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:03:24.669  6743  6751 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:03:24.669  6743  6751 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:03:24.669  6743  6751 D BluetoothLeScanner: Exiting stopAllScan
09-06 19:03:24.669  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:24.669  1450  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:24.669  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-06 19:03:24.669  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:03:24.679  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.679  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:03:24.679  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-06 19:03:24.689  3156  3254 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:03:24.689  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:03:24.689  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.689  1171  1171 D BluetoothTile:  getBluetoothState : 10
09-06 19:03:24.689  1171  1739 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  1171  1739 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  1868  1868 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:03:24.689  3156  3156 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:03:24.689  3156  3156 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:03:24.689  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:03:24.689  2002  2154 D BluetoothAdapter: 907799592: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  2002  2154 D BluetoothAdapter: 907799592: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:24.689  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.689  1017  1331 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:03:24.689  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:03:24.699  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:24.699  3156  3156 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:03:24.699  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:24.699  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:03:24.699  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:24.699  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.699  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.699  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:03:24.699  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:03:24.699  1017  1331 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:03:24.699  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:03:24.699  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.699  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.699  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-06 19:03:24.699  3156  3156 I art     : System.exit called, status: 0
09-06 19:03:24.699  3156  3156 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:03:24.709  3859  3859 D DockEventReceiver: finishStartingService: stopping service
09-06 19:03:24.709  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
09-06 19:03:24.719  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:24.719  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-06 19:03:24.719  6886  6910 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:03:24.749  1017  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:24.749  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.749  1017  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.749  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:03:24.819  1017  1029 I ActivityManager: Process com.android.bluetooth (pid 3156)(adj 0) has died(33,715)
,09-06 19:03:24.829  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:24.829  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:24.829  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:03:24.829  1383  1383 I wpa_supplicant: nl80211: Received scan results (7 BSSes),
,09-06 19:03:24.829  1017  1126 D WifiP2pService: InactiveState{ what=147461 }
,09-06 19:03:24.829  1017  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-06 19:03:24.829  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.829  1017  1126 D WifiP2pService: DefaultState{ what=147461 }
09-06 19:03:24.829  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:03:24.829  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 19:03:24.829  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.829  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:24.839   279  1003 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:24.839  2002  6817 V NativeCrypto: SSL handshake aborted: ssl=0xb7b98568: I/O error during system call, Connection timed out
09-06 19:03:24.839  2002  6817 I qtaguid : Untagging socket 61
09-06 19:03:24.849  2002  3000 V NativeCrypto: Read error: ssl=0xb7a79ac0: I/O error during system call, Connection timed out
,09-06 19:03:24.849  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:24.849  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:03:24.849  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:24.849  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-06 19:03:24.849  2002  6817 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-06 19:03:24.859  2002  3000 V NativeCrypto: SSL shutdown failed: ssl=0xb7a79ac0: I/O error during system call, Broken pipe,
09-06 19:03:24.859  2002  6925 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-06 19:03:24.859  2002  6817 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:03:24.859  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:24.859  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:03:24.859  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.869  1017  1486 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-06 19:03:24.859  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.859  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.859  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.859  2002  3000 E GCM     : Wifi connection closed with errorCode 20
09-06 19:03:24.869  2002  6817 I qtaguid : Tagging socket 47 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2002, getuid(): 10011
,09-06 19:03:24.869  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:24.879  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:24.879  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.879  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.879  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:24.889  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
,09-06 19:03:24.889  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:03:24.889  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 19:03:24.889  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:03:24.899  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-20ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:24.899  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-20ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:24.899  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:03:24.899  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:24.899  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 19:03:24.899  1017  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:03:24.899  1017  1761 I qtaguid : Tagging socket 372 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,09-06 19:03:24.899  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:03:24.899  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:24.899  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-06 19:03:24.899  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.909  1017  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:24.909  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.909  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.909  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.909  1017  1761 I qtaguid : Untagging socket 372
09-06 19:03:24.909  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-06 19:03:24.909  1017  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:24.909  1017  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:03:24.919  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,09-06 19:03:24.919  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:03:24.919  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:03:24.919  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:24.919  1017  3357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:24.919  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:24.919  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:03:24.919  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:03:24.929  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:24.929  1616  1616 I Hs20UtilService: Starting #8
09-06 19:03:24.929  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:03:24.929  1616  1643 I Hs20UtilService: Message received 5007
09-06 19:03:24.929  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:03:24.929  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:03:24.929  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:03:24.929  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:24.929  1017  1047 D WifiDisplayController: disconnect
09-06 19:03:24.929  1017  1047 D WifiDisplayController: updateConnection
09-06 19:03:24.929  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:24.929  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:03:24.929  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:03:24.939  1017  1126 D WifiP2pService: P2pDisablingState
,09-06 19:03:24.939  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:03:24.939  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:03:24.939  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:03:24.939  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:24.939  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:03:24.939  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:03:24.939  1017  1127 E WifiNative-wlan0: do suspend true
09-06 19:03:24.939  1017  1126 D WifiP2pService: p2p socket connection lost
09-06 19:03:24.939  1017  1126 D WifiP2pService: P2pDisabledState
,09-06 19:03:24.939  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 19:03:24.939  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:03:24.949  1017  1494 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-06 19:03:24.949  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:03:24.949  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:03:24.949  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:24.949  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.949  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.949  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.949  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:24.969   279   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:03:24.969   279   999 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-06 19:03:24.969   279  1003 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:03:24.969  2002  6817 I qtaguid : Untagging socket 47
,09-06 19:03:24.969  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:03:24.969  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:03:24.969  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:24.969  1017  1129 V NetworkStats: updateIfacesLocked()
09-06 19:03:24.969  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:24.969  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:24.969  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:24.969  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:03:24.969  1383  1383 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 19:03:24.969  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:03:24.969  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:24.979  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:24.979  1017  1129 V NetworkStats: performPollLocked() took 9ms
,09-06 19:03:24.979  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:24.979  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:03:24.979  1017  1127 D SecContentProvider2: mCursor = null
09-06 19:03:24.979  2002  6817 W GLSUser : [AppCertManager] IOException while requesting key: 
09-06 19:03:24.979  2002  6817 W GLSUser : java.net.ConnectException: failed to connect to android.clients.google.com/172.217.16.206 (port 443) after 30000ms: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dja.a(:com.google.android.gms:233)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at jch.run(:com.google.android.gms:17)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
09-06 19:03:24.979  2002  6817 W GLSUser : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at libcore.io.Posix.connect(Native Method)
09-06 19:,03:24.979  2002  6817 W GLSUser : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
09-06 19:03:24.979  2002  6817 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-06 19:03:24.979  2002  6817 W GLSUser : 	... 30 more
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:24.979  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:24.979  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:24.979  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 19:03:24.989  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:03:24.989  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-06 19:03:24.989  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:24.989  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:03:24.989  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:24.989  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:24.989  1171  1171 D HotspotTile: onReceive : 0, 0
,09-06 19:03:24.989  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-06 19:03:24.989  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:24.989  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:24.989  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:24.989  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:24.989  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:24.989  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:24.989  1171  1710 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:03:24.999  1017  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:24.999  4799  6805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:03:24.999  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:03:24.999  1017  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:03:24.999  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:24.999  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:24.999  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:03:24.999  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:24.999  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:03:24.999  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:03:24.999  1017  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-06 19:03:24.999  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:03:24.999  1464  1464 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:03:24.999  1464  1464 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:03:24.999  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:24.999  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:03:24.999  1017  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:24.999  1017  1331 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-06 19:03:24.999  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-06 19:03:25.009  1017  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.009  1017  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.009  1017  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.009  1017  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.019  6932  6932 E Zygote  : MountEmulatedStorage()
09-06 19:03:25.019  1017  1331 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6932 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-06 19:03:25.019  6932  6932 E Zygote  : v2
09-06 19:03:25.019  6932  6932 I libpersona: KNOX_SDCARD checking this for 10102,
,09-06 19:03:25.019  6932  6932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:25.019  6932  6932 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:25.019  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:03:25.029  6932  6932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:25.029  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:03:25.029  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:03:25.029  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:03:25.029  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:25.029  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:25.029  6932  6932 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:03:25.029  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:03:25.029  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:03:25.029  1017  1130 D Tethering: MasterInitialState.processMessage what=3
09-06 19:03:25.029  1017  1124 V NetworkStats: updateIfacesLocked()
09-06 19:03:25.029  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.029  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:25.039  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:03:25.039  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:25.039  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:03:25.039  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:03:25.039  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:03:25.039  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-06 19:03:25.039  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:03:25.039  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:03:25.039  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.039  1017  1124 V NetworkStats: performPollLocked() took 7ms
,09-06 19:03:25.039  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:03:25.039  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.039  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:03:25.039  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.039  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:25.039  2002  2002 I art     : Explicit concurrent mark sweep GC freed 42889(2MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 11MB/18MB, paused 1.733ms total 131.198ms
,09-06 19:03:25.049  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:03:25.049  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:25.049  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.049  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:25.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:25.069  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:03:25.069  6932  6932 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:25.069  6932  6932 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:25.079  2002  2164 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:03:25.079  2002  2164 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-06 19:03:25.089  2002  2164 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-06 19:03:22.682+0200, stopTime=2016-09-06 19:03:25.099+0200, duration=2417ms
09-06 19:03:25.089  6932  6932 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:03:25.119  1383  1383 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:03:25.119  2002  6950 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:25.119  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:03:25.119  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:25.119  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:25.119  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.129   279   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:03:25.129   279   999 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-06 19:03:25.129  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.129  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.139  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.139  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.139  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:03:25.139  1383  1383 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:03:25.139  1383  1383 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:03:25.139  1383  1383 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:03:25.139  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.139  1383  1383 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:25.139  1383  1383 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:03:25.139  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.139  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:25.139  1017  1130 D Tethering: InitialState.processMessage what=4
,09-06 19:03:25.139  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.139  1017  1130 E Tethering: No numeric data
09-06 19:03:25.149  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:03:25.149  1017  1130 D Tethering: clearTetheredNotification()
09-06 19:03:25.149  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.149  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
09-06 19:03:25.149  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.149  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:03:25.149  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:25.149  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:03:25.149  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.149  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:03:25.149  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:25.149  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:25.149  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:03:25.149  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.149  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.149  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:25.149  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.149  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.149  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.149  1017  1124 V NetworkStats: performPollLocked() took 5ms
,09-06 19:03:25.149  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:03:25.159  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.159  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:25.159  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:25.159  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:03:25.159  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.159  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.159  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.159  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.159  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.169  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.169  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.169  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.169  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.169  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.169  1017  4235 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-06 19:03:25.179  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.179  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.179  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.179  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.179  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:03:25.179  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:03:25.189  2002  2002 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
,09-06 19:03:25.189  1017  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:25.199  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:25.199  1017  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:25.199  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:03:25.199   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bae7c8
09-06 19:03:25.199   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-06 19:03:25.199   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:03:25.199   272   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212487544)
09-06 19:03:25.199  2002  2164 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-06 19:03:25.209  2002  6925 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:03:25.239   272   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-06 19:03:25.239   272   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:03:25.249   272   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212487544) wakelock released: 1, error no: 0
09-06 19:03:25.249   272   362 I rmt_storage: 
,09-06 19:03:25.249   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7bae7c8
,09-06 19:03:25.289  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:03:25.319  6932  6974 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-06 19:03:25.319  6932  6974 I Babel_SMS: MmsConfig.loadMmsSettings
09-06 19:03:25.319  6932  6974 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-06 19:03:25.319  6932  6974 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:03:25.329  6932  6974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 19:03:25.329  6932  6974 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:03:25.339  6932  6974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-06 19:03:25.339  6932  6974 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:03:25.349  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.349  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:25.349  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:25.359  1383  1383 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 19:03:25.369  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:03:25.369  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:03:25.369  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:25.369  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:03:25.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:25.369  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:25.379  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:25.379  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:03:25.379  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:03:25.379  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:25.379  2002  2154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:25.379  1171  1171 D HotspotTile: onReceive : 1, 0
,09-06 19:03:25.379  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:25.379  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.379  1017  1492 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-06 19:03:25.379  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:25.379  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
09-06 19:03:25.379  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:03:25.379  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:25.379  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
09-06 19:03:25.389  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-06 19:03:25.389  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:25.399  6932  6932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:25.399  6932  6932 I Babel_Crash: startup - clean
,09-06 19:03:25.429  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:03:25.439  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:25.439  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:25.439  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:25.439  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:25.439  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:03:25.439  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:25.439  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 19:03:25.439  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.439  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.439  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.439  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.449  6932  6932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:25.449  6932  6932 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:03:25.449  6932  6932 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:03:25.449  6977  6977 E Zygote  : MountEmulatedStorage()
,09-06 19:03:25.449  6977  6977 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:03:25.449  6977  6977 E Zygote  : v2
09-06 19:03:25.449  6977  6977 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:25.459  6932  6932 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:03:25.459  6932  6932 W AudioCapabilities: Unsupported mime audio/mpeg-L2
09-06 19:03:25.459  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:25.459  1017  1135 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6977 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:03:25.459  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:25.459  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:03:25.469  6932  6932 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 19:03:25.469  6932  6932 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:03:25.469  6932  6932 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:03:25.469  6932  6932 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:03:25.479  6932  6932 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:03:25.479  6932  6932 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:03:25.479  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:25.489  6977  6977 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:25.499  6977  6977 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:03:25.499  6932  6932 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:03:25.499  6932  6932 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:03:25.499  6932  6932 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:03:25.509  6932  6932 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 19:03:25.509  6932  6932 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:03:25.509  6932  6932 W VideoCapabilities: Unsupported mime video/mp43
,09-06 19:03:25.519  6932  6932 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:03:25.519  6932  6932 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:03:25.519  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:25.519  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:25.529  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:03:25.529  1017  1017 I ApplicationPolicy: updateDataUsageMap
,09-06 19:03:25.539  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:25.539  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:25.539  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:25.549  6932  6932 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:03:25.559  6977  6977 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:03:25.559  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:03:25.559  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.559  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.559  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.559  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.579  6992  6992 E Zygote  : MountEmulatedStorage(),
09-06 19:03:25.579  6992  6992 E Zygote  : v2
09-06 19:03:25.579  6992  6992 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:03:25.579  6992  6992 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:25.579  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:25.579  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:25.579  1017  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6992 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:03:25.579  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:25.589  6932  6932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:25.589  6932  6932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 19:03:25.589  6932  6932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:25.599  6932  6932 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,09-06 19:03:25.599  1017  1511 I ActivityManager: Killing 6475:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-06 19:03:25.599  6932  6932 I vclib   : onServiceConnected
,09-06 19:03:25.609  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:25.609  6992  6992 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:25.629  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:25.639  1017  4235 I ActivityManager: Killing 6490:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:03:25.649  1017  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:25.649  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:25.649  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.649  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.649  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:25.649  1616  1616 I Hs20UtilService: Starting #9
,09-06 19:03:25.649  1616  1643 I Hs20UtilService: Message received 5007
,09-06 19:03:25.649  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:03:25.649  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:25.649  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:25.659  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:25.659  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:25.659  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:03:25.659  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:25.659  1017  3357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:25.659  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:25.659  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.659  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.659  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:25.669  1616  1616 I Hs20UtilService: Starting #10
,09-06 19:03:25.669  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:25.669  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:03:25.669  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:25.669  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:03:25.669  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:25.679  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:25.679  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.679  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.849  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:25.849  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.849  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.849  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:25.849  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.849  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.859  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.859  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.859  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.859  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.869  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.869  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.869  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.869  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.869  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.879  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.879  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.879  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.879  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.879  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.889  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.889  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:25.889  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:03:25.889  1017  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:25.889  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:25.889  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:25.889  1017  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:25.889  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:25.899  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:03:25.899  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:03:25.899  1616  1616 I Hs20UtilService: Starting #11
09-06 19:03:25.899  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:03:25.899  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:25.899  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:25.909  1017  1463 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:03:25.909  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.909  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:25.909  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.909  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:25.929  1017  1463 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-06 19:03:25.929  7007  7007 E Zygote  : MountEmulatedStorage()
09-06 19:03:25.929  7007  7007 I libpersona: KNOX_SDCARD checking this for 1000
,09-06 19:03:25.929  7007  7007 E Zygote  : v2
09-06 19:03:25.929  7007  7007 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:25.929  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:25.929  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:25.939  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:25.959  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:25.959  7007  7007 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:25.979  7007  7007 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 19:03:25.979  7007  7007 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-06 19:03:25.989  7007  7007 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance,
,09-06 19:03:25.989  1017  1044 D Tethering: interfaceRemoved wlan0
,09-06 19:03:25.989  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:03:26.009  7007  7007 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 19:03:26.009  7007  7007 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-06 19:03:26.009  7007  7007 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:03:26.009  7007  7007 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:26.009  1017  4970 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-06 19:03:26.009  1017  4970 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:03:26.009  7007  7022 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 19:03:26.009  1017  4970 I ActivityManager: Killing 6524:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 19:03:26.019  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:03:26.019  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.019  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.019  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.019  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.039  7024  7024 E Zygote  : MountEmulatedStorage()
,09-06 19:03:26.039  7024  7024 E Zygote  : v2
09-06 19:03:26.039  7024  7024 I libpersona: KNOX_SDCARD checking this for 10001,
09-06 19:03:26.039  7024  7024 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.039  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:26.039  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:26.049  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7024 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:03:26.049  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.049  1017  1511 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 19:03:26.049  1017  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.049  1017  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.049  1017  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.049  1017  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:26.059   289   289 E SMD     : DCD OFF
,09-06 19:03:26.069  7039  7039 E Zygote  : MountEmulatedStorage()
09-06 19:03:26.069  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:03:26.069  7039  7039 I libpersona: KNOX_SDCARD checking this for 10031
09-06 19:03:26.069  7039  7039 E Zygote  : v2
09-06 19:03:26.069  7039  7039 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.069  7024  7024 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.079  1017  1511 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7039 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
09-06 19:03:26.079  7039  7039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.079  7039  7039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.079  7039  7039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:03:26.079  1773  1773 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:03:26.089  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:03:26.089  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.089  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.089  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.089  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.109  7039  7039 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.109  7039  7039 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:26.109   305   305 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 789us total 38.348ms
,09-06 19:03:26.139   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 679us total 22.099ms
,09-06 19:03:26.149   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.072ms
,09-06 19:03:26.159  7056  7056 E Zygote  : MountEmulatedStorage(),
,09-06 19:03:26.159  7056  7056 E Zygote  : v2
09-06 19:03:26.159  7056  7056 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:03:26.159  7056  7056 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.159  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.169  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7056 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,09-06 19:03:26.169  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.169  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.179  2595  2604 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
09-06 19:03:26.179  1773  1773 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
09-06 19:03:26.179  1773  1773 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-06 19:03:26.179  1773  1773 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-06 19:03:26.179  1773  1773 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:03:26.189  1017  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:03:26.189  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.189  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.189  1773  1773 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-06 19:03:26.189  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.189  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.189  1773  1773 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:03:26.199  1017  1044 D Tethering: interfaceRemoved p2p0
09-06 19:03:26.199  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:03:26.199  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.199  7056  7056 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:26.199  7071  7071 E Zygote  : MountEmulatedStorage()
,09-06 19:03:26.199  7071  7071 E Zygote  : v2
09-06 19:03:26.199  7071  7071 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:03:26.199  7071  7071 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.199  1017  1216 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:03:26.209  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.209  1017  1216 I ActivityManager: Killing 6575:com.osp.app.signin/u0a36 (adj 15): empty #21
09-06 19:03:26.209  1017  1216 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 19:03:26.209  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:26.209  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:03:26.209  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:03:26.209  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.209  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.209  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.229  7084  7084 E Zygote  : MountEmulatedStorage()
,09-06 19:03:26.229  7084  7084 E Zygote  : v2
09-06 19:03:26.229  7084  7084 I libpersona: KNOX_SDCARD checking this for 10077
09-06 19:03:26.229  7084  7084 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.229  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.229  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:03:26.229  1017  1216 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7084 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:03:26.229  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:26.229  7071  7071 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:26.239  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.249  7056  7056 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:03:26.249  7056  7056 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:03:26.249  7056  7056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:03:26.259  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.259  7039  7039 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 19:03:26.259  7084  7084 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.259  1017  1029 I ActivityManager: Killing 6592:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 19:03:26.279  7056  7056 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:26.279  1017  1463 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:03:26.289  2748  7101 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-06 19:03:26.289  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.289  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.289  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.289  1017  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.289  2748  7101 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:03:26.289  2748  7101 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:03:26.289  2748  7101 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 19:03:26.289  2748  7101 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:03:26.299  7102  7102 E Zygote  : MountEmulatedStorage(),
09-06 19:03:26.299  7102  7102 E Zygote  : v2
09-06 19:03:26.299  7102  7102 I libpersona: KNOX_SDCARD checking this for 10032
09-06 19:03:26.299  7102  7102 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.299  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:26.309  1017  1463 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7102 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 19:03:26.309  7056  7056 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:03:26.309  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.309  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.319  7056  7056 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:03:26.319  1017  4235 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
,09-06 19:03:26.319  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.319  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.319  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.319  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.319  7071  7071 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:03:26.339  7117  7117 E Zygote  : MountEmulatedStorage()
09-06 19:03:26.339  7117  7117 I libpersona: KNOX_SDCARD checking this for 10141
09-06 19:03:26.339  7117  7117 E Zygote  : v2
09-06 19:03:26.339  7117  7117 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.339  7117  7117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.339  1017  4235 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7117 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-06 19:03:26.339  1017  4235 I ActivityManager: Killing 6608:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-06 19:03:26.339  7117  7117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.339  7117  7117 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.359  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.359  7102  7102 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.369  7117  7117 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.369  7117  7117 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.389  7117  7117 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:03:26.389  7117  7117 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:03:26.389  7117  7117 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:03:26.389  7117  7117 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:03:26.419  7102  7132 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:03:26.419  7102  7132 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:03:26.429  7102  7132 D SPPClientService: PushLog.txt file is not deleted.
,09-06 19:03:26.429  7102  7132 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:03:26.429  7102  7132 D SPPClientService: ============PushLog. stop!
,09-06 19:03:26.439  7102  7102 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-06 19:03:26.439  1017  1461 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 19:03:26.439  1017  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.439  1017  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.439  1017  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.439  1017  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.449  1017  3357 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.459  1017  1461 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7135 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:03:26.459  1017  1461 I ActivityManager: Killing 6543:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-06 19:03:26.459  1017  1029 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-06 19:03:26.459  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-06 19:03:26.459  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:26.459  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:03:26.459  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-06 19:03:26.469  7135  7135 E Zygote  : MountEmulatedStorage()
09-06 19:03:26.469  7135  7135 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:03:26.469  7135  7135 E Zygote  : v2
09-06 19:03:26.469  7135  7135 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.469  7135  7135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:26.469  7071  7071 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
09-06 19:03:26.469  7135  7135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:26.469  7135  7135 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:03:26.469  1017  1216 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.479  7071  7071 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 19:03:26.479  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:26.479  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:03:26.479  7071  7071 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 19:03:26.479  7071  7071 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-06 19:03:26.479  1017  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 19:03:26.489  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.489  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.489  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.489  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.489  7135  7135 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.489  7135  7135 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.499  7153  7153 E Zygote  : MountEmulatedStorage(),
09-06 19:03:26.499  7153  7153 E Zygote  : v2
09-06 19:03:26.499  7153  7153 I libpersona: KNOX_SDCARD checking this for 10008
,09-06 19:03:26.499  7153  7153 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:26.499  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:03:26.499  1017  1492 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7153 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:03:26.509  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.509  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-06 19:03:26.519  7102  7147 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 19:03:26.529  1017  1461 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.539  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.539  7153  7153 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.539  1017  1135 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.549  1017  1463 I ActivityManager: Killing 6626:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-06 19:03:26.579  7135  7135 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@20653890
,09-06 19:03:26.589  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 19:03:26.589  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:03:26.589  7135  7135 I SA      : [SSP] onCreated
,09-06 19:03:26.589  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:26.589  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:26.589  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:03:26.599  1017  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 19:03:26.599  1017  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.599  1017  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.599  1017  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.599  1017  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.619  7178  7178 E Zygote  : MountEmulatedStorage()
,09-06 19:03:26.619  7178  7178 E Zygote  : v2
09-06 19:03:26.619  7178  7178 I libpersona: KNOX_SDCARD checking this for 10110
09-06 19:03:26.619  7178  7178 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.619  1017  1494 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7178 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:03:26.619  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:26.619  7135  7135 I SA      : [TPM] There is no property file
,09-06 19:03:26.619  1017  4234 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-06 19:03:26.619  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.629  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.629  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.629  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.629  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.629  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:03:26.629  7135  7135 I SA      : [SCU] isHaveSA() - false
,09-06 19:03:26.629  1017  1511 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.629  7135  7135 I SA      : [TPM] getModelProperty : null
,09-06 19:03:26.629  7135  7135 I SA      : [TPM] getCSCProperty : null
,09-06 19:03:26.639  7135  7135 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-06 19:03:26.639  7135  7135 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-06 19:03:26.639  1017  1492 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.639  7135  7135 I SA      : [DM] TFT FEATURE: false
,09-06 19:03:26.639  7190  7190 E Zygote  : MountEmulatedStorage()
09-06 19:03:26.639  7190  7190 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:03:26.639  7190  7190 E Zygote  : v2
09-06 19:03:26.639  7190  7190 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.639  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:26.639  1017  4234 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7190 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-06 19:03:26.649  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 19:03:26.649  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:03:26.649  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:26.649  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:26.649  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:03:26.649  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.649  6932  7175 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-06 19:03:26.649  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.659  7135  7135 I SA      : [DM] init START
,09-06 19:03:26.659  1017  3357 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.669  7135  7135 I SA      : [DM] This device is not a Vodafone
09-06 19:03:26.669  1017  3357 I ActivityManager: Killing 6054:com.android.mms/u0a41 (adj 15): empty #21
09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-06 19:03:26.669  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 19:03:26.669  7178  7178 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:26.669  7135  7135 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-06 19:03:26.679  7135  7135 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-06 19:03:26.679  1017  4970 I ActivityManager: Killing 6652:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-06 19:03:26.679  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:03:26 GMT+02:00 2016
,09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-06 19:03:26.679  7135  7135 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
09-06 19:03:26.689  1017  1461 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:03:26.689  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:03:26.689  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:26.689  1017  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:26.689  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:03:26.689  1017  1216 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:03:26.699  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.699  1017  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-06 19:03:26.699  7190  7190 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.699  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.699  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:03:26.699  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.699  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:26.699  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:26.699  7135  7135 I SA      : [SCU] isHaveSA() - false
09-06 19:03:26.699  7135  7135 I SA      : support phone number id : false
09-06 19:03:26.699  7135  7135 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:03:26.699  7135  7135 I SA      : [DM] init END
09-06 19:03:26.699  7135  7135 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 19:03:26.709  2912  2912 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:03:26.709  7135  7135 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 19:03:26.709  7135  7135 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:03:26.709  2912  2912 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:03:26.709  2912  2912 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:03:26.709  2912  7211 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:03:26.719  2912  7211 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:03:26.719  7212  7212 E Zygote  : MountEmulatedStorage()
09-06 19:03:26.719  7212  7212 E Zygote  : v2
09-06 19:03:26.719  7212  7212 I libpersona: KNOX_SDCARD checking this for 10009
09-06 19:03:26.719  7212  7212 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:26.719  7135  7135 I SA      : [SLFUCHKMGR] constructor called
09-06 19:03:26.719  7212  7212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:26.719  1017  1492 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7212 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-06 19:03:26.719  7212  7212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:26.729  7212  7212 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:03:26.729  1017  1492 I ActivityManager: Killing 6669:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-06 19:03:26.729  2912  7211 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
09-06 19:03:26.729  1017  1331 I ActivityManager: Killing 6505:com.android.calendar/u0a131 (adj 15): empty #21
,09-06 19:03:26.739  2912  7211 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 19:03:26.739  7135  7135 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:03:26.739  7135  7135 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:03:26.829  7135  7135 I SA      : [SCU] == networkStateCheck == false
09-06 19:03:26.829  7135  7135 I SA      : [OR] onReceive END
,09-06 19:03:26.829  1017  1492 D CountryDetector: No listener is left
,09-06 19:03:26.829  2912  2912 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:03:26.829  7212  7212 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:26.829  7212  7212 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:26.849  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:03:26.869  1017  1331 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:26.969  1017  1030 I art     : Explicit concurrent mark sweep GC freed 54916(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.577ms total 234.126ms
,09-06 19:03:26.979  1017  1463 I ActivityManager: Killing 6684:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-06 19:03:26.979  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:27.009  7190  7190 D BadgeProvider: onCreate
,09-06 19:03:27.009  7190  7190 D BadgeProvider: DatabaseHelper
,09-06 19:03:27.019  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-06 19:03:27.019  1017  1029 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 19:03:27.019  1017  4970 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 19:03:27.029  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:03:27.039  7190  7207 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 19:03:27.049  7190  7207 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 19:03:27.049  7190  7207 D BadgeProvider: sendNotify, [notify] : null
09-06 19:03:27.049  7190  7207 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:03:27.049  7190  7207 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:03:27.049  7190  7207 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:03:27.049  1496  1496 D Launcher.Model: reloadBadges entered.
,09-06 19:03:27.049   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:27.059  1017  1511 I ActivityManager: Killing 5975:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-06 19:03:27.069  1017  4234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:27.069  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:03:27.069  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:27.069  1017  4234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:27.069  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:27.079  1017  1492 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:03:27.079  1017  1492 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:03:27.079  1017  1492 D SecContentProvider2: mCursor = null
,09-06 19:03:27.079  1017  1492 D WifiService: setWifiEnabled: true pid=6743, uid=10171
,09-06 19:03:27.079  1017  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:03:27.079  1017  1492 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:03:27.079  1017  1492 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:27.079  1017  1492 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:03:27.079  1017  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:03:27.079  1017  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:03:27.079  1017  1492 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:03:27.079  1017  1492 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:03:27.089  1017  1492 D SettingsProvider: name = wifi_on
,09-06 19:03:27.089  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:03:27.089  4799  7235 I iu.SyncManager: SYNC; picasa accounts
,09-06 19:03:27.099  4799  4799 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-06 19:03:27.149  7178  7178 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:03:27.149  7178  7178 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:03:27.149  7178  7178 I GAv4    :   adb logcat -s GAv4
,09-06 19:03:27.159   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:03:27.159   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:27.159  7178  7236 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:03:27.169   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:03:27.169   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:27.169  7178  7236 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:03:27.179  7178  7178 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:27.179  1017  1331 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:27.179   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:03:27.179   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:27.179  7178  7238 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:03:27.179   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:03:27.179   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:27.179  7178  7238 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:03:27.199  7178  7178 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:27.209  7178  7239 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:27.209  2002  2164 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-06 19:03:27.209  2002  2164 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-06 19:03:27.369  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:03:27.369  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:03:27.369  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:03:27.369  1017  1029 D BatteryService: stay LED for fully charged
09-06 19:03:27.369  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:03:27.379  1017  1017 I MotionRecognitionService: Plugged
,09-06 19:03:27.379  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:03:27.379  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:03:27.379  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:03:27.379  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:03:27.389  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:03:27.409  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:27.409  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:27.409  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:27.419  1017  4235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:27.429  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:27.429  1017  4235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:27.429  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:03:27.439  7178  7178 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:03:27.459  7178  7178 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6354-6357)
,09-06 19:03:27.459  7178  7178 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:03:27.479  7178  7178 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13cc1d8b}
,09-06 19:03:27.479  7178  7178 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:03:27.479  7178  7178 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:03:27.499  1017  1044 D Tethering: interfaceAdded wlan0
,09-06 19:03:27.499  1017  1130 E Tethering: No numeric data
09-06 19:03:27.499  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:27.499  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:27.499  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:27.499  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:03:27.499  1017  1130 D Tethering: clearTetheredNotification()
,09-06 19:03:27.499  7178  7178 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:03:27.499  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.499  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:27.509   279  1003 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:03:27.509  7178  7178 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:03:27.509   279  1003 D SoftapController: Softap fwReload - Ok
09-06 19:03:27.509  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:27.509  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:27.509  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:03:27.509  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:27.509  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:27.509  1017  1130 D Tethering: InitialState.processMessage what=4
,09-06 19:03:27.509   279  1003 D CommandListener: Setting iface cfg,
09-06 19:03:27.509   279  1003 D CommandListener: Trying to bring down wlan0
09-06 19:03:27.509  1017  1124 V NetworkStats: performPollLocked() took 10ms
09-06 19:03:27.509  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.519  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:27.519  1017  1044 D Tethering: interfaceAdded p2p0
09-06 19:03:27.519  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:03:27.519   279  1003 D CommandListener: Clearing all IP addresses on wlan0,
,09-06 19:03:27.519  7178  7178 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:03:27.519  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:27.519  1017  1130 E Tethering: No numeric data
09-06 19:03:27.519  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:03:27.519  1017  1130 D Tethering: clearTetheredNotification()
09-06 19:03:27.519  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring,
,09-06 19:03:27.519  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
09-06 19:03:27.529  1017  1124 V NetworkStats: performPollLocked() took 3ms
09-06 19:03:27.519  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.529  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:27.519  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.529  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:03:27.519  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:27.529  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:27.529  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:27.529  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.529  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:27.529  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:27.539  7178  7178 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-06 19:03:27.539  7178  7178 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:03:27.539  7178  7178 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:03:27.539  7178  7178 I Adreno-EGL: Local Branch: 
09-06 19:03:27.539  7178  7178 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:03:27.539  7178  7178 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:03:27.539  7178  7178 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:03:27.579  7265  7265 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:03:27.579  7265  7265 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:03:27.579  7265  7265 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:03:27.589  7178  7277 W cr.media: Requires BLUETOOTH permission
,09-06 19:03:27.599  7178  7178 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,09-06 19:03:27.609  7178  7178 I NSApplication: Starting up...
,09-06 19:03:27.609  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:27.609  1017  1494 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:27.619  7265  7265 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:03:27.619   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7265
09-06 19:03:27.619   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-06 19:03:27.619  7265  7265 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:03:27.619  7265  7265 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:27.619  7265  7265 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:03:27.619  7265  7265 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:03:27.619   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7265
09-06 19:03:27.619   351   351 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
09-06 19:03:27.619  1017  4234 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:03:27.619  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:27.619  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:27.619  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:27.629  1017  4234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:27.639  7283  7283 E Zygote  : MountEmulatedStorage()
09-06 19:03:27.639  7283  7283 E Zygote  : v2
09-06 19:03:27.639  7283  7283 I libpersona: KNOX_SDCARD checking this for 10117
,09-06 19:03:27.639  7283  7283 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:27.639  7283  7283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:27.639  1017  4234 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7283 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,09-06 19:03:27.639  7283  7283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:27.639  1017  4234 I ActivityManager: Killing 5817:com.android.vending/u0a26 (adj 15): empty #21
09-06 19:03:27.649  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:03:27.649  7283  7283 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:03:27.659  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:27.659  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-06 19:03:27.659  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:27.659  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:27.659  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:27.659  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:27.659  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:27.659  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:27.659  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:03:27.659  1171  1171 D HotspotTile: onReceive : 2, 0
,09-06 19:03:27.659   305   305 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 21.187ms
09-06 19:03:27.659  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:27.659  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:03:27.669  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:27.669  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:27.679   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.646ms
,09-06 19:03:27.679  7283  7283 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:03:27.679  7283  7283 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:27.699   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 17.276ms
,09-06 19:03:27.699  7283  7283 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:03:27.819   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-06 19:03:27.819  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-06 19:03:27.869  7265  7265 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:03:27.869  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:03:27.879  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-06 19:03:27.879   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7265,
09-06 19:03:27.879   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:03:27.879  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:03:27.879  7265  7265 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:27.879  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:03:27.879  7265  7265 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:27.879  7265  7265 E wpa_supplicant: SIM READ ERROR
09-06 19:03:27.879  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:27.879  7265  7265 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-06 19:03:27.879  7265  7265 E wpa_supplicant: SIM READ ERROR
09-06 19:03:27.879  7265  7265 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:03:27.879  7265  7265 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:03:27.879  7265  7265 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:03:27.879  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:03:27.879  7265  7265 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:03:27.879  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:27.879  7265  7265 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:03:27.889  7265  7265 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:03:27.889  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:03:27.889  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:27.889  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:27.969  7265  7265 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 19:03:28.059  7265  7265 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
09-06 19:03:28.059   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:28.059  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,09-06 19:03:28.079  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-06 19:03:28.079   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7265
09-06 19:03:28.079   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:03:28.079  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-06 19:03:28.079  7265  7265 I wpa_supplicant: ssSupport state is = 1
,09-06 19:03:28.079  7265  7265 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-06 19:03:28.079  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:03:28.089  1017  1135 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 19:03:28.089  1017  1135 I ActivityManager: Killing 6868:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-06 19:03:28.089  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 19:03:28.089   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7265
09-06 19:03:28.089   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:03:28.089  7265  7265 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:03:28.089  7265  7265 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:28.089  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:28.089  7265  7265 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:28.089  7265  7265 E wpa_supplicant: SIM READ ERROR
09-06 19:03:28.089  7265  7265 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:03:28.089  7265  7265 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:03:28.089  7265  7265 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:03:28.099  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-06 19:03:28.099  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:28.099  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:28.099  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:03:28.099  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:28.099  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:28.099  1017  4235 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:28.099  1017  4235 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:28.099  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:28.099  1017  4235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:28.099  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:28.109  1616  1616 I Hs20UtilService: Starting #12
,09-06 19:03:28.109  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:28.109  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:03:28.109  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:28.109  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:03:28.109  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:28.219  7265  7265 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 19:03:28.219  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:03:28.299  7265  7265 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 19:03:28.299  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:03:28.299  7265  7265 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-06 19:03:28.309  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:03:28.309  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 19:03:28.309  7265  7265 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-06 19:03:28.309  7265  7265 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:28.309  7265  7265 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-06 19:03:28.309  7265  7265 E wpa_supplicant: SIM READ ERROR
09-06 19:03:28.319  7265  7265 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:03:28.349  7265  7265 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:03:28.349  7265  7265 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:03:28.349  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:03:28.349  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:28.349  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:03:28.349  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:28.349  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:28.349  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:28.349  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:28.349  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:28.359  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:03:28.359  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:28.359  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:03:28.359  1171  1171 D HotspotTile: onReceive : 3, 0
09-06 19:03:28.359  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:28.359  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:28.359  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:28.359  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:28.359  1017  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:28.359  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:28.359  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:28.359  1017  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:28.359  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:03:28.359  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:28.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:28.359  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:28.359  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:28.369  1616  1616 I Hs20UtilService: Starting #13
,09-06 19:03:28.369  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:28.369  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:03:28.369  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:28.369  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:03:28.369  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:28.369  1017  1127 E WifiConfigStore: Not a HS20
,09-06 19:03:28.369  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:03:28.369  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:03:28.379  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:03:28.379  7265  7265 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:03:28.379  7265  7265 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:03:28.379  7265  7265 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:03:28.379  7265  7265 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:03:28.379  7265  7265 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:03:28.379  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:03:28.379  7265  7265 I wpa_supplicant: First Scan Start
,09-06 19:03:28.379  7265  7265 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:03:28.379  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:03:28.379  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:03:28.379  1017  1127 I WifiNative-HAL: startHal
09-06 19:03:28.379  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d52d88c
09-06 19:03:28.379  1017  1127 I WifiNative-HAL: Could not start hal
,09-06 19:03:28.379  6932  6932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:28.389  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:28.389  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:03:28.389  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:03:28.389  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:03:28.389  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:28.389  1017  1149 I WifiNative-HAL: startHal
,09-06 19:03:28.389  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e8e79bc
09-06 19:03:28.389  1017  1149 I WifiNative-HAL: Could not start hal
09-06 19:03:28.389  1017  1149 E WifiScanningService: could not start HAL
09-06 19:03:28.389  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-06 19:03:28.389  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:03:28.389  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:03:28.389  1017  1127 E WifiNative-wlan0: invaild command id : 215
,09-06 19:03:28.389   279  1003 D CommandListener: Setting iface cfg
09-06 19:03:28.389   279  1003 D CommandListener: Trying to bring up p2p0
,09-06 19:03:28.389  1017  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:28.389  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:03:28.389  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:03:28.389  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-06 19:03:28.389  1017  1127 E WifiNative-wlan0: invaild command id : 215
09-06 19:03:28.389  1017  1126 D WifiP2pService: P2pEnablingState
09-06 19:03:28.399  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:03:28.399  1017  1126 D WifiP2pService: P2p socket connection successful
09-06 19:03:28.399  1017  1126 D WifiP2pService: P2pEnabledState
,09-06 19:03:28.399  7265  7265 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:03:28.399  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:03:28.399  7265  7265 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:03:28.399  1017  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:03:28.399  7265  7265 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:03:28.399  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:03:28.399  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:28.399  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:28.399  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:03:28.399  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:03:28.399  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:28.399  1017  1047 D WifiDisplayController: disconnect
09-06 19:03:28.399  1017  1047 D WifiDisplayController: updateConnection
09-06 19:03:28.399  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:28.399  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:03:28.399  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:28.399  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:28.399  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:03:28.409  1017  1331 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:03:28.409  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:03:28.409  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:03:28.409  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:03:28.409  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:28.409  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:03:28.409  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-06 19:03:28.409  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-06 19:03:28.409  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:03:28.409  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:28.419  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  secondary type: null
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  wps: 0
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  grpcapab: 0
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  devcapab: 0
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  status: 3
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  wfdInfo: null
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-06 19:03:28.419  1017  1047 D WifiDisplayController:  SConnectInfo : null
09-06 19:03:28.419  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:03:28.419  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 19:03:28.419  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:03:28.419  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:28.419  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:28.419  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:28.419  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:28.419  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:03:28.419  6977  6977 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:03:28.429  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:28.439  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:03:28.439  1017  1126 D WifiP2pService: InactiveState
,09-06 19:03:28.439  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:03:28.439  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:03:28.439  7265  7265 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-06 19:03:28.439  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:03:28.439  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:03:28.489  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:03:28.489  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:28.489  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:28.829  1017  1135 I ActivityManager: Killing 6886:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-06 19:03:29.059   316   316 I ServiceManager: Waiting for service AtCmdFwd...
09-06 19:03:29.059   289   289 E SMD     : DCD OFF
,09-06 19:03:29.569  7265  7265 I wpa_supplicant: nl80211: Received scan results (19 BSSes),
09-06 19:03:29.569  7265  7265 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:03:29.569  7265  7265 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:03:29.569  7265  7265 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:03:29.569  7265  7265 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:03:29.569  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 19:03:29.569  1017  7309 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:03:29.579  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:03:29.579  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:29.689  7265  7265 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:03:29.689  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:03:29.689  7265  7265 I wpa_supplicant: Associated with F4.99.3E
09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:03:29.689  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:03:29.689  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:03:29.689  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:29.689  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:29.689  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:29.689  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:29.689  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:29.689  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:03:29.689  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:29.689  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
09-06 19:03:29.689  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:03:29.689  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:03:29.689  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:03:29.689  1017  1130 E Tethering: No numeric data
09-06 19:03:29.689  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:03:29.689  7265  7265 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:03:29.689  1017  1130 D Tethering: clearTetheredNotification()
09-06 19:03:29.699  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:29.699  7265  7265 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:03:29.699  7265  7265 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:03:29.699  7265  7265 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:03:29.699  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:29.699  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:29.699  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:29.699  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:29.699  7265  7265 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:03:29.699  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:03:29.699  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:29.699  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:03:29.699  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:03:29.699  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:29.699  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:03:29.699  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:29.699  1017  1127 D SecContentProvider2: mCursor = null,
,09-06 19:03:29.709  1017  1124 V NetworkStats: performPollLocked() took 12ms
,09-06 19:03:29.709  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:29.709  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:29.709  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:29.709  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:03:29.709  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:03:29.719  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:03:29.719  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:03:29.719  1017  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:03:29.719  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:03:29.719  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:29.719  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:29.729  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:29.729  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:29.729  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:29.729  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:29.729  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:29.729  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:29.729  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:29.729  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:29.729  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:29.729  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:03:29.739  1616  1616 I Hs20UtilService: Starting #14
,09-06 19:03:29.739  1616  1643 I Hs20UtilService: Message received 5007
,09-06 19:03:29.739  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:03:29.749  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:29.749  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:29.749  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:29.749  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:29.749  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:29.749  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:29.749  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:29.759   279  1003 D CommandListener: Setting iface cfg
,09-06 19:03:29.769  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:03:29.769  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:03:29.769  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:29.769  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:03:29.769  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:29.779  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:29.779  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:03:29.779  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:29.779  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:29.779  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:29.779  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:29.789  1017  1127 E WifiNative-wlan0: do suspend false
,09-06 19:03:29.789  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:03:29.799  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:29.799  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:29.799  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:03:30.009  7315  7315 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:03:30.019  7315  7315 I dhcpcd  : version 5.5.6 starting,
,09-06 19:03:30.019  7315  7315 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:03:30.059   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-06 19:03:30.089  7315  7315 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:03:30.089  7315  7315 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:03:30.089  7315  7315 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-06 19:03:30.089  7315  7315 I dhcpcd  : bssid match
,09-06 19:03:30.089  7315  7315 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127,
,09-06 19:03:30.089  1017  1486 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:03:30.089  1017  1486 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:03:30.089  1017  1486 D SecContentProvider2: mCursor = null
,09-06 19:03:30.099  1017  1486 D WifiService: setWifiEnabled: false pid=6743, uid=10171
,09-06 19:03:30.099  1017  1486 D SettingsProvider: name = wifi_on
,09-06 19:03:30.099  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:30.119  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:30.139  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
09-06 19:03:30.139  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:03:30.149   279  1003 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:30.149  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:30.149  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:30.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.149  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:30.149  1017  1129 E ConnectivityService: updateNetworkInfo(),
09-06 19:03:30.149  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:03:30.149  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:30.149  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-06 19:03:30.149   279  1003 E Netd    : no such netId 503
09-06 19:03:30.159  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:03:30.159  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:03:30.159  1017  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
09-06 19:03:30.159  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:30.159  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:03:30.159  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:30.159  1017  1129 V NetworkStats: updateIfacesLocked()
,09-06 19:03:30.159  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:03:30.169  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:30.179  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:03:30.179  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:03:30.179  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:03:30.179  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:03:30.179  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:03:30.179  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
,09-06 19:03:30.179  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:30.179  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-06 19:03:30.179  1017  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler },
,09-06 19:03:30.179  1017  1129 V NetworkStats: performPollLocked() took 21ms
09-06 19:03:30.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.179  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:30.179  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:03:30.179  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:03:30.179  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:30.179  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:03:30.179  1017  1511 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:30.179  1017  1511 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:30.179  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:30.179  1017  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:30.179  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:30.189  1616  1616 I Hs20UtilService: Starting #15
,09-06 19:03:30.189  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-06 19:03:30.189  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:03:30.189  1017  7313 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:30.189  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:03:30.189  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:03:30.189  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:03:30.189  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:30.189  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:30.189  1017  7313 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:03:30.189  1017  1126 D WifiP2pService: P2pDisablingState
09-06 19:03:30.189  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:03:30.189  1017  1126 D WifiP2pService: p2p socket connection lost
09-06 19:03:30.189  1017  1126 D WifiP2pService: P2pDisabledState
09-06 19:03:30.189  1616  1643 I Hs20UtilService: Message received 5007
09-06 19:03:30.189  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:30.189  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:30.189  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:30.189  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:03:30.189  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-06 19:03:30.189  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:30.189  1017  1047 D WifiDisplayController: disconnect
09-06 19:03:30.189  1017  1047 D WifiDisplayController: updateConnection
09-06 19:03:30.189  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:30.189  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:03:30.199  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:03:30.199  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:03:30.199  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:03:30.199  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:30.199  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:03:30.199  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:30.199  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:30.199  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:30.199  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:30.199  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:30.199  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:30.199  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:03:30.199  1017  4235 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:03:30.199  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:03:30.209  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:03:30.209  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:30.209  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:30.209  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:30.209  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:30.209  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:30.209  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:30.219  7315  7315 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-06 19:03:30.219  7315  7315 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-06 19:03:30.229  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:30.229   279  1003 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:30.229  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:03:30.229  6977  6977 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:03:30.229  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:30.229  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:30.229  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.229  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.229  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.229  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.229  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 19:03:30.229  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:03:30.239  7265  7265 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:03:30.239  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:03:30.249  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:30.249  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:30.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.249  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:30.259  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:30.259  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:30.259  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:03:30.259  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.259  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.259  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.259  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:30.259  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:30.259  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:03:30.259  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:03:30.259  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:03:30.259  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:30.269  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:03:30.269  1171  1171 D HotspotTile: onReceive : 0, 0
09-06 19:03:30.269  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:30.269  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:30.269  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:30.269  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:30.269  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:30.269  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:30.269  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:30.269  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:30.279  1017  1135 I ActivityManager: Killing 7007:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:03:30.289  1017  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:30.289  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:03:30.289  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:30.289  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:30.289  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:30.289  1616  1616 I Hs20UtilService: Starting #16
,09-06 19:03:30.289  1616  1643 I Hs20UtilService: Message received 5007
,09-06 19:03:30.299  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:03:30.299  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:03:30.299  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:30.299  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:30.299  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:30.299  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:03:30.299  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:30.309  1017  1511 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:30.309  1017  1511 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:30.309  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:30.309  1017  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:30.309  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:03:30.309  1616  1616 I Hs20UtilService: Starting #17
,09-06 19:03:30.309  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:30.319  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
09-06 19:03:30.319  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:30.319  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:03:30.319  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:30.399  7265  7265 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:03:30.529  7265  7265 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:03:30.529  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:03:30.529  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:30.529  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:30.569  7265  7265 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-06 19:03:30.569  7265  7265 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:03:30.569  7265  7265 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-06 19:03:30.569  7265  7265 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:30.569  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.569  7265  7265 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:03:30.579  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.569  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.569  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:03:30.569  1017  1130 D Tethering: InitialState.processMessage what=4
09-06 19:03:30.579  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.579  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:30.579  1017  1130 E Tethering: No numeric data,
09-06 19:03:30.579  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
,09-06 19:03:30.579  1017  1130 D Tethering: clearTetheredNotification()
,09-06 19:03:30.579  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:30.579  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:30.579  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:03:30.579  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:30.579  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:03:30.579  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:30.579  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.579  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.579  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:30.589  1017  1124 V NetworkStats: performPollLocked() took 6ms
09-06 19:03:30.589  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 19:03:30.589  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:30.589  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:30.679  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:03:30.679  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:30.679  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:30.859  7265  7265 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:03:30.939  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:03:30.939  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-06 19:03:30.939  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:03:30.949  7265  7265 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-06 19:03:31.049  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:03:31.049  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 19:03:31.059  6932  6932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:31.059  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,09-06 19:03:31.059  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
,09-06 19:03:31.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:31.059  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:31.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:31.059  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:03:31.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:31.059  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:31.059  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:31.059  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:03:31.069  1171  1171 D HotspotTile: onReceive : 1, 0
09-06 19:03:31.069  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:31.069  2002  2154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:31.069  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:31.079  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:31.079  1017  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:31.079  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:31.079  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:31.079  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:31.079  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:31.089  1616  1616 I Hs20UtilService: Starting #18
09-06 19:03:31.089  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:31.089  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:03:31.089  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:31.089  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:03:31.089  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:31.739  1017  1044 D Tethering: interfaceRemoved wlan0
09-06 19:03:31.739  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:03:31.889  1017  1044 D Tethering: interfaceRemoved p2p0
09-06 19:03:31.889  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:03:32.059   289   289 E SMD     : DCD OFF,
,09-06 19:03:32.689  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:03:33.099  6743  6796 D BluetoothAdapter: enable()
,09-06 19:03:33.099  1017  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-06 19:03:33.109  1017  1494 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:03:33.109  1017  1494 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:03:33.109  1017  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:03:33.109  1017  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:33.109  1017  1494 D SettingsProvider: name = bluetooth_on
,09-06 19:03:33.119  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:33.119  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:33.119  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 19:03:33.119  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,09-06 19:03:33.119  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:03:33.119  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:33.119  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.119  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.139  7347  7347 E Zygote  : MountEmulatedStorage(),
,09-06 19:03:33.139  7347  7347 E Zygote  : v2,
09-06 19:03:33.139  7347  7347 I libpersona: KNOX_SDCARD checking this for 1002
,09-06 19:03:33.139  7347  7347 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:33.139  7347  7347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:33.139  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7347 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:03:33.149  7347  7347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:33.149  7347  7347 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:33.179  7347  7347 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:03:33.179  7347  7347 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:03:33.189  7347  7347 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:03:33.189  7347  7347 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:03:33.219  7347  7347 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding HidService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding HealthService
,09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding PanService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding SapService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding SapClientService
09-06 19:03:33.249  7347  7347 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:03:33.249  7347  7347 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:03:33.249  1017  1511 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-06 19:03:33.249  1017  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.249  1017  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.249  1017  1511 D SettingsProvider: selectionArgs: false
09-06 19:03:33.249  1017  1511 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.249  1017  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.249  1017  1511 D SettingsProvider: ret = -1
,09-06 19:03:33.249  1017  4234 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 19:03:33.249  1017  4234 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.249  1017  4234 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.249  1017  4234 D SettingsProvider: selectionArgs: false
09-06 19:03:33.249  1017  4234 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.249  1017  4234 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.249  1017  4234 D SettingsProvider: ret = -1
,09-06 19:03:33.249  1017  3357 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:03:33.249  1017  3357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.249  1017  3357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.249  1017  3357 D SettingsProvider: selectionArgs: false
,09-06 19:03:33.249  1017  3357 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.249  1017  3357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.249  1017  3357 D SettingsProvider: ret = -1
,09-06 19:03:33.259  1017  1331 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:03:33.259  1017  1331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:03:33.259  1017  1331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  1331 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  1331 D SettingsProvider: selectionArgs: 1002
,09-06 19:03:33.259  1017  1331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  1331 D SettingsProvider: ret = -1
,09-06 19:03:33.259  1017  4235 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:03:33.259  1017  4235 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  4235 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  4235 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  4235 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  4235 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  4235 D SettingsProvider: ret = -1
,09-06 19:03:33.259  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:03:33.259  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  1029 D SettingsProvider: selectionArgs: false
,09-06 19:03:33.259  1017  1029 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  1029 D SettingsProvider: ret = -1
,09-06 19:03:33.259  1017  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:03:33.259  1017  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  1492 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  1492 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:03:33.259  1017  1492 D SettingsProvider: ret = -1
09-06 19:03:33.259  1017  4970 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:03:33.259  1017  4970 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  4970 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  4970 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  4970 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  4970 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:03:33.259  1017  4970 D SettingsProvider: ret = -1
09-06 19:03:33.259  1017  1463 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.259  1017  1463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  1463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:03:33.259  1017  1463 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  1463 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  1463 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  1463 D SettingsProvider: ret = -1
,09-06 19:03:33.259  1017  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.259  1017  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  1486 D SettingsProvider: selectionArgs: false
09-06 19:03:33.259  1017  1486 D SettingsProvider: selectionArgs: 1002
,09-06 19:03:33.259  1017  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  1486 D SettingsProvider: ret = -1
09-06 19:03:33.259  1017  7228 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:03:33.259  1017  7228 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  7228 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  7228 D SettingsProvider: selectionArgs: false
,09-06 19:03:33.259  1017  7228 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  7228 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  7228 D SettingsProvider: ret = -1
09-06 19:03:33.259  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:03:33.259  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.259  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.259  1017  1030 D SettingsProvider: selectionArgs: false
,09-06 19:03:33.259  1017  1030 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.259  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.259  1017  1030 D SettingsProvider: ret = -1
,09-06 19:03:33.279  7347  7347 D BluetoothAdapterState: make
,09-06 19:03:33.279  7347  7347 I bluedroid: init
,09-06 19:03:33.279  7347  7362 I BluetoothAdapterState: Entering OffState
,09-06 19:03:33.289  7347  7347 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:03:33.289  7347  7347 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:03:33.289  7347  7347 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:03:33.289  7347  7347 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:03:33.289  7347  7347 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 19:03:33.289  7347  7347 I bluedroid: get_profile_interface socket
09-06 19:03:33.289  7347  7347 I bluedroid: get_profile_interface map_client
,09-06 19:03:33.289  7347  7347 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:03:33.299  7347  7347 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:33.299  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:03:33.299  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.299  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:33.299  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.299  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.309  7347  7365 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:03:33.309  7347  7355 I bluedroid: config_hci_snoop_log
,09-06 19:03:33.309  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-06 19:03:33.309  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:03:33.309  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:03:33.309  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:03:33.309  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:03:33.309  7347  7365 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:03:33.309  7347  7365 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:03:33.309  7347  7365 I bluedroid: getModelRssiValues
09-06 19:03:33.309  7347  7365 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:03:33.309  7347  7365 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:03:33.319  7347  7347 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:03:33.319  7347  7365 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:03:33.319  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:03:33.319  1017  1017 D SettingsProvider: name = bluetooth_name
09-06 19:03:33.319  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:33.319  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:03:33.329  7347  7362 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:03:33.329  7347  7362 D BluetoothAdapterProperties: Setting state to 11
09-06 19:03:33.329  7347  7362 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:03:33.329  7347  7362 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:33.329  7347  7362 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:03:33.329  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:03:33.329  7347  7362 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:33.329  7347  7362 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:03:33.329  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:33.329  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:03:33.339  7347  7362 D BluetoothSecureManager: getInstant: null
09-06 19:03:33.339  7347  7362 D BluetoothSecureManager: calling getMethod for getService
09-06 19:03:33.339  7347  7362 D BluetoothSecureManager: calling getService
,09-06 19:03:33.339  7347  7362 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1a3582f9
09-06 19:03:33.339  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:03:33.339  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:33.339  1171  1171 D BluetoothTile:  getBluetoothState : 11
,09-06 19:03:33.339  1017  4234 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:03:33.339  1017  4234 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-06 19:03:33.339  7347  7362 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:03:33.339  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:03:33.339  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:03:33.339  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:33.339  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:03:33.339  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:03:33.339  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:03:33.339  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:33.349  1868  1868 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:03:33.349  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:33.349  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.349  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:33.349  1017  4970 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.349  1017  1135 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:03:33.349  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:03:33.349  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:03:33.349  7347  7362 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-06 19:03:33.349  1017  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:33.349  1017  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.349  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:33.359  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.359  1017  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:33.359  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:33.359  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:33.359  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:33.369  7347  7362 D BluetoothBondStateMachine: make
,09-06 19:03:33.369  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:03:33.369  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:03:33.369  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:03:33.369  7347  7367 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:03:33.369  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:33.369  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:03:33.369  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.369  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.369  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:33.369  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.369  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.369  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:03:33.369  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:03:33.369  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:33.379  7347  7347 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:33.379  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:03:33.379  7347  7347 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:03:33.379  7347  7347 D BtGatt.GattService: start()
09-06 19:03:33.379  7347  7347 D BtGatt.GattService: start()
09-06 19:03:33.379  7347  7347 I bluedroid: get_profile_interface gatt
,09-06 19:03:33.379  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:33.379  7347  7347 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:03:33.379  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.379  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:03:33.379  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:33.379  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.399  7369  7369 E Zygote  : MountEmulatedStorage(),
09-06 19:03:33.399  7369  7369 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:03:33.399  7369  7369 E Zygote  : v2
09-06 19:03:33.399  7369  7369 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:33.399  7369  7369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:33.399  1017  1029 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7369 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-06 19:03:33.399  1017  3357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.399  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.399  7369  7369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:33.399  7369  7369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:03:33.399  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.399  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.399  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:33.409  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:03:33.409  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:03:33.409  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:33.409  1017  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:33.409  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.409  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.409  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.409  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.419  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:03:33.419  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:33.419  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.419  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 19:03:33.419  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.419  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.419  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.419  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.419  7347  7347 D BtGatt.GattService: mStartError = false
09-06 19:03:33.419  1017  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.419  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:33.419  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-06 19:03:33.419  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:03:33.419  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:03:33.419  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:03:33.419  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.419  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.419  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.429  7347  7347 D HeadsetService: Received start request. Starting profile...
,09-06 19:03:33.429  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:03:33.429  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
09-06 19:03:33.429  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-06 19:03:33.429  1017  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.429  7347  7347 D HeadsetService: start()
,09-06 19:03:33.429  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:03:33.429  7347  7347 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:03:33.429  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:33.429  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.429  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:33.429  7347  7347 D HeadsetStateMachine: make
,09-06 19:03:33.439  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:03:33.439  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:33.439  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:33.439  7347  7347 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:03:33.439  1017  4234 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.439  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.439  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.439  1017  4234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.439  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:33.439  1017  3357 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:03:33.439  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.449  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.449  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.449  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:03:33.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:03:33.449  1017  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:33.449  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:33.449  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:33.449  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.449  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.449  1017  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:03:33.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.449  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:03:33.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:03:33.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:03:33.449  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:03:33.449  7347  7362 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:03:33.449  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:33.449  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:33.449  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:03:33.449  7347  7347 I bluedroid: get_profile_interface handsfree
,09-06 19:03:33.459  7369  7369 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:33.459  7369  7369 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:03:33.479  7347  7347 I DualScoManager: Instantiating Dual Sco Manager
,09-06 19:03:33.479  7347  7347 I DualScoManager: Set HeadsetServiceHelper
,09-06 19:03:33.489  7347  7347 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:03:33.489  1017  3357 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:03:33.489  1017  3357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:33.489  1017  3357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:33.489  1017  3357 D SettingsProvider: selectionArgs: false
09-06 19:03:33.489  1017  3357 D SettingsProvider: selectionArgs: 1002
09-06 19:03:33.489  1017  3357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:33.489  1017  3357 D SettingsProvider: ret = -1
,09-06 19:03:33.489  7347  7382 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:03:33.489  7347  7347 D HeadsetService: mStartError = false
09-06 19:03:33.489  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.489  7347  7347 D A2dpService: Received start request. Starting profile...
09-06 19:03:33.489  7347  7347 D A2dpService: start()
,09-06 19:03:33.499  7347  7382 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-06 19:03:33.499  7347  7382 D HeadsetStateMachine: map size, before remove : 0
,09-06 19:03:33.499  7347  7382 D HeadsetStateMachine: map size, after remove: 0
09-06 19:03:33.499  7347  7347 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:03:33.499  7347  7347 I bluedroid: get_profile_interface avrcp
,09-06 19:03:33.509  7347  7347 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:03:33.509  7347  7347 D Avrcp   : Initialize Media Controller
,09-06 19:03:33.509  7347  7347 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:03:33.509  7347  7347 E Avrcp   : getActiveSessions
,09-06 19:03:33.509  7347  7347 D Avrcp   : pick active media Controller
09-06 19:03:33.509  7347  7347 D Avrcp   : Get the active Media Controller 
,09-06 19:03:33.519  7369  7369 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:03:33.529  7347  7347 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:03:33.539  7347  7390 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:03:33.539  7347  7347 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:03:33.539  7347  7347 D A2dpStateMachine: make
,09-06 19:03:33.539  7347  7347 I bluedroid: get_profile_interface a2dp
,09-06 19:03:33.539  7347  7392 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:03:33.539  7347  7347 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:03:33.539  7347  7347 D A2dpService: mStartError = false
09-06 19:03:33.539  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.549  7347  7347 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:03:33.549  7347  7391 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:03:33.549  7347  7347 D HidService: Received start request. Starting profile...
09-06 19:03:33.549  7347  7347 D HidService: start()
09-06 19:03:33.549  7347  7347 I bluedroid: get_profile_interface hidhost
09-06 19:03:33.549  7347  7347 D HidService: setHidService(): set to: null
09-06 19:03:33.549  7347  7347 D HidService: mStartError = false
09-06 19:03:33.549  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.549  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-06 19:03:33.549  7347  7347 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:03:33.549  7347  7347 D HealthService: Received start request. Starting profile...
09-06 19:03:33.549  7347  7347 D HealthService: start()
,09-06 19:03:33.549  7369  7369 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:03:33.559  7347  7347 I bluedroid: get_profile_interface health
,09-06 19:03:33.559  7347  7347 D HealthService: mStartError = false
09-06 19:03:33.559  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:33.559  7369  7369 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:03:33.559  7369  7369 D UserAnalysis: Create SecureDbHelper
,09-06 19:03:33.559  7347  7390 D BluetoothMediaBrowser: no now playing list
09-06 19:03:33.559  7347  7390 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:03:33.559  7347  7347 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:03:33.559  7347  7347 D PanService: Received start request. Starting profile...
,09-06 19:03:33.559  7347  7347 D PanService: start()
09-06 19:03:33.559  7347  7347 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:03:33.559  7347  7347 I bluedroid: get_profile_interface pan
,09-06 19:03:33.559  7347  7347 D PanService: mStartError = false
09-06 19:03:33.559  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.569  7369  7369 D IntelligenceServiceApplication: onCreate()
,09-06 19:03:33.569  7347  7347 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:03:33.569  7347  7347 D BluetoothMapService: start()
,09-06 19:03:33.579  1017  1331 I ActivityManager: Killing 7024:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-06 19:03:33.579  7369  7369 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:03:33.579  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:03:33.579  7347  7347 D BluetoothMapService: mStartError = false
09-06 19:03:33.579  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.579  7347  7347 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:03:33.579  7369  7369 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:03:33.589  1432  1459 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:03:33.589  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:03:33.589  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:03:33.589  1432  1459 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:03:33.589  7347  7347 D HeadsetStateMachine: Proxy object connected
,09-06 19:03:33.589  7347  7347 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:03:33.589  7369  7369 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:03:33.589  7347  7347 D SapService: Received start request. Starting profile...
,09-06 19:03:33.589  7347  7347 D SapService: start()
09-06 19:03:33.589  7347  7347 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-06 19:03:33.589  7347  7347 I bluedroid: get_profile_interface sap
09-06 19:03:33.589  7347  7347 D SapService: mStartError = false
,09-06 19:03:33.589  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:33.589  7347  7347 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:03:33.599  7347  7347 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:03:33.599  7347  7347 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:03:33.599  7347  7382 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:03:33.599  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-06 19:03:33.599  7347  7347 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:03:33.599  7347  7347 D BluetoothA2dp: Proxy object connected
09-06 19:03:33.599  7347  7347 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:03:33.599  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:03:33.599  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:03:33.599  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-06 19:03:33.599  7347  7382 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:03:33.599  7347  7382 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:03:33.599  7347  7382 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:03:33.599  7347  7382 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:03:33.599  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:03:33.599  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:03:33.599  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.599  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:33.599  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:33.599  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:33.619  7397  7397 E Zygote  : MountEmulatedStorage()
09-06 19:03:33.619  1017  1029 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7397 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:03:33.619  7397  7397 E Zygote  : v2
09-06 19:03:33.619  7397  7397 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:03:33.619  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:33.619  7397  7397 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:33.619  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:33.629  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:03:33.639  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-06 19:03:33.639  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:03:33.649  7347  7362 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:03:33.649  7347  7362 I bluedroid: enable
,09-06 19:03:33.649  7347  7413 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 19:03:33.649  7347  7362 I bt_hci_bdroid: init
,09-06 19:03:33.649  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:33.649  7397  7397 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:33.659  7347  7362 I bt_vendor: bt-vendor : init
09-06 19:03:33.659  7347  7362 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:03:33.659  7347  7362 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:03:33.659  7347  7362 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 19:03:33.659  7347  7362 D bt_userial_mct: userial_init
,09-06 19:03:33.659  7347  7362 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 19:03:33.659  7347  7362 I bt_vendor: Starting hciattach daemon
09-06 19:03:33.659  7347  7362 I bt_vendor: try to set false
,09-06 19:03:33.659  7347  7362 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:03:33.659  7347  7362 I bt_vendor: Starting hciattach daemon
09-06 19:03:33.659  7347  7362 I bt_vendor: try to set true
,09-06 19:03:33.679  7417  7417 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:03:33.729  7423  7423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 19:03:33.739  7424  7424 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:03:33.759  7428  7428 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:03:33.759  7429  7429 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:03:33.769  7430  7430 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:03:33.779  7431  7431 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:03:33.809   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:03:33.809   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:33.809  7397  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:03:33.809   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:03:33.809   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:03:33.819  7397  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:03:33.999  7397  7397 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:03:33.999  7397  7397 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:33.999  7397  7397 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:33.999  7397  7397 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:33.999  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:34.009  7397  7397 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:34.009  7397  7397 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:34.009  7397  7397 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:34.009  7397  7397 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:34.009  7397  7397 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:34.009  1017  4235 I ActivityManager: Killing 7039:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-06 19:03:34.009  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:34.019  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:34.079  7397  7445 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:03:34.099  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:34.099  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.099  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:34.099  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:03:34.099  7447  7447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,09-06 19:03:34.109  7449  7449 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:03:34.129  7347  7362 I bt_vendor: bluetooth satus is on
,09-06 19:03:34.129  7347  7415 D bt_userial_mct: userial_open(port:0)
09-06 19:03:34.129  7347  7415 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:03:34.129  7347  7415 I bt_vendor: Done intiailizing UART
,09-06 19:03:34.129  7347  7415 I bt_vendor: Done intiailizing UART
,09-06 19:03:34.129  7347  7415 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-06 19:03:34.129  7347  7415 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:03:34.139  7347  7413 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-06 19:03:34.139  7347  7451 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:03:34.229  7347  7413 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:03:34.239  7347  7413 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa411fed1 
,09-06 19:03:34.239  7347  7413 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa411fed1 
,09-06 19:03:34.249  7347  7365 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:03:34.259  7347  7365 E bt-btif : Calling BTA_HhEnable
,09-06 19:03:34.259  7347  7365 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:03:34.259  7347  7365 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:03:34.259  7347  7365 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:03:34.259  7347  7365 I bluedroid: getModelRssiValues
,09-06 19:03:34.259  7347  7365 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:03:34.259  7347  7365 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:03:34.259  1017  1017 D SettingsProvider: name = bluetooth_name
,09-06 19:03:34.259  7347  7365 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:03:34.269  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:34.269  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:34.269  7347  7365 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:03:34.279  7347  7365 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:34.279  7347  7365 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:03:34.279  7347  7365 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-06 19:03:34.279  7347  7365 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 19:03:34.279  7347  7365 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:03:34.279  7347  7365 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:03:34.279  7347  7365 E bt-btif : btif_sock_init: !vhci_init
09-06 19:03:34.279  7347  7365 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 19:03:34.279  7347  7365 D IOP_DB_BT: db_open: db_open : handle 3027693584l, read 13894 bytes onto local cache
,09-06 19:03:34.279  7347  7365 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 19:03:34.279  7347  7365 D IOP_DB_BT: db_query: result 1
,09-06 19:03:34.279  7347  7365 I         : iop_db_open: iop_db_open status 0
,09-06 19:03:34.279  7347  7365 D bte_conf: Device ID record 1 : primary
,09-06 19:03:34.279  7347  7365 D bte_conf:   vendorId            = 0075
09-06 19:03:34.279  7347  7365 D bte_conf:   vendorIdSource      = 0001
09-06 19:03:34.279  7347  7365 D bte_conf:   product             = 0100,
09-06 19:03:34.279  7347  7365 D bte_conf:   version             = 0200
09-06 19:03:34.279  7347  7365 D bte_conf:   clientExecutableURL = 
09-06 19:03:34.279  7347  7365 D bte_conf:   serviceDescription  = 
09-06 19:03:34.279  7347  7365 D bte_conf:   documentationURL    = 
,09-06 19:03:34.279  7347  7365 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:03:34.289  7347  7365 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:03:34.289  7347  7362 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:03:34.289  7347  7362 D BluetoothAdapterProperties: ScanMode =  20
,09-06 19:03:34.289  7347  7362 D BluetoothAdapterProperties: State =  11
,09-06 19:03:34.289  1017  4234 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:03:34.289  7347  7362 D BluetoothAdapterProperties: Setting state to 12
09-06 19:03:34.289  7347  7362 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:03:34.289  7347  7451 E bt_mct  : hci lib postload completed
,09-06 19:03:34.299  7347  7365 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:03:34.299  7347  7365 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:03:34.299  7347  7365 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:03:34.299  1017  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:03:34.299  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:34.299  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:34.299  1017  1030 D SettingsProvider: selectionArgs: false
,09-06 19:03:34.299  1017  1030 D SettingsProvider: selectionArgs: 1002
,09-06 19:03:34.299  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:34.299  1017  1030 D SettingsProvider: ret = -1
,09-06 19:03:34.299  7347  7362 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:34.299  7347  7362 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:03:34.299  1017  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:34.299  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.299  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:34.299  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:34.309  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:34.309  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:34.309  7347  7362 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:34.309  7347  7362 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:03:34.309  7347  7362 D BluetoothAdapterService: starting service from this receiver
,09-06 19:03:34.309  1017  7228 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:34.309  1017  7228 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.309  1017  7228 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.319  1017  7228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.319  1464  2450 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.319  1464  2450 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:34.319  1017  7228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.319  7397  7409 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.319  7397  7409 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:34.319  7347  7362 I BluetoothAdapterState: Entering On State from state = 11
09-06 19:03:34.319  7347  7389 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:03:34.319  3859  3879 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.319  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:34.319  3859  3879 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:34.319  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.329  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:03:34.329  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.329  3859  3946 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:03:34.329  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:34.329  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:03:34.329  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.339  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.339  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.339  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.339  2002  2010 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.339  2002  2010 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:34.339  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.339  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:34.339  7347  7347 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-06 19:03:34.339  7347  7389 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.339  7347  7389 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:34.339  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:34.339  3859  3872 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.339  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:34.339  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.349  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.349  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.349  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.349  3859  3872 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:34.349  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:34.349  1432  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.349  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:03:34.349  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.349  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:34.349  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.349  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.349  1432  1472 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:03:34.349  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:34.349  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:03:34.349  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:03:34.349  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:03:34.359  1017  1017 D BluetoothA2dp: Proxy object connected
09-06 19:03:34.359  1432  3265 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.359  1432  3265 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:34.359  3859  3879 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:03:34.359  3859  3859 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:34.359  7347  7347 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:03:34.369  1017  1494 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-06 19:03:34.369  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:03:34.369  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.369  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.369  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.369  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.369  1171  3248 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.369  1171  3248 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:34.369  3859  3946 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:03:34.369  3859  3946 D Bluetoothsap: Binding service...
09-06 19:03:34.369  3859  3859 D BluetoothPbap: Proxy object connected
09-06 19:03:34.369  3859  3859 D PbapServerProfile: Bluetooth service connected
09-06 19:03:34.369  3859  3859 D BluetoothMap: Proxy object connected
09-06 19:03:34.369  3859  3859 D MapProfile: Bluetooth service connected
09-06 19:03:34.369  3859  3859 D BluetoothMap: getConnectedDevices()
,09-06 19:03:34.369  7347  7457 V BluetoothPbapService: PBAP Service initSocket try: 0
09-06 19:03:34.369  3859  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:03:34.379  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:03:34.379  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.379  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.379  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:34.379  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:03:34.379  3859  3946 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:03:34.379  3859  3879 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:34.379  3859  3879 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.379  3859  3859 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:03:34.379  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:03:34.379  3859  3859 D SapProfile: Bluetooth service connected
09-06 19:03:34.379  3859  3859 D Bluetoothsap: getConnectedDevices()
09-06 19:03:34.379  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.379  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.379  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.379  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.379  3859  3872 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:03:34.379  3859  3859 D BluetoothA2dp: Proxy object connected
09-06 19:03:34.379  3859  3859 D A2dpProfile: Bluetooth service connected
,09-06 19:03:34.379  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:03:34.379  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:03:34.379  7347  7457 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:03:34.379  7347  7457 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:34.389  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.389  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.389  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.389  7347  7457 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 19:03:34.389  7347  7457 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:34.389  7347  7457 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:34.389  7347  7457 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3599bf4d
09-06 19:03:34.389  7347  7457 D BluetoothSocket: channel: 19
09-06 19:03:34.389  7347  7457 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:03:34.389  3859  3859 D BluetoothInputDevice: Proxy object connected
09-06 19:03:34.389  3859  3859 D HidProfile: Bluetooth service connected
,09-06 19:03:34.389  1432  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.389  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:34.389  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.389  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.389  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.389  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.389  1432  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:34.389  1464  1672 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.389  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:03:34.389  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.399  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:34.399  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.399  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.399  1464  1672 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:03:34.399  3859  3879 D BluetoothPan: Binding service...
,09-06 19:03:34.399  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:03:34.399  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.399  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.399  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.399  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.399  6743  6751 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:03:34.399  3859  3859 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:03:34.399  3859  3859 D PanProfile: Bluetooth service connected
09-06 19:03:34.399  6743  6751 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:34.399  1017  1046 D BluetoothPan: Binding service...
,09-06 19:03:34.399  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:03:34.399  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.399  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:03:34.399  1432  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:34.399  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:34.399  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:34.409  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.409  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.409  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-06 19:03:34.409  1432  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:34.409  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:34.409  1450  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:34.409  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:03:34.409  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:03:34.409  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:34.409  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:03:34.409  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:03:34.419  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@31bf1d9, true
,09-06 19:03:34.419  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:03:34.419  1868  1868 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:03:34.419  1432  1432 D BluetoothHeadset: registerMessageListener
,09-06 19:03:34.419  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:34.419  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:03:34.419  1171  1171 D BluetoothTile:  getBluetoothState : 12
,09-06 19:03:34.429  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:34.429  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:34.429  1017  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:34.429  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.429  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:34.429  1017  1486 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:34.429  1017  1511 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-06 19:03:34.429  7347  7456 D HeadsetService: registerMessageListener
09-06 19:03:34.429  7347  7456 D HeadsetService: registerMessageListener
,09-06 19:03:34.429  7347  7382 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:03:34.429  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.429  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:03:34.429  1017  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:34.429  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:03:34.429  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:03:34.429  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:03:34.439  7347  7382 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d4e1a02
09-06 19:03:34.439  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:34.439  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:34.439  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:03:34.439  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:03:34.439  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:03:34.439  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:34.449  7347  7382 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:03:34.449  7347  7382 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:03:34.449  3859  3859 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 19:03:34.449  3859  3859 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:03:34.449  3859  3859 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-06 19:03:34.449  3859  3859 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:03:34.449  7347  7458 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:03:34.449   284   678 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:03:34.449   284   678 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:03:34.449   284   678 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:03:34.449   284   678 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:03:34.449   284   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:03:34.449   284   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:03:34.449   284   678 V audio_hw_primary: adev_set_parameters: exit
09-06 19:03:34.449  7347  7382 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:03:34.459  7347  7458 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:03:34.459  7347  7458 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:34.459  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:03:34.459  7347  7458 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 19:03:34.459  7347  7458 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:34.459  7347  7458 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:34.459  1017  3357 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:03:34.459  7347  7458 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35b9df13
09-06 19:03:34.459  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:03:34.459  7347  7458 D BluetoothSocket: channel: 5
09-06 19:03:34.459  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.459  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:34.459  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:03:34.469  3859  3859 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:34.469  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:34.469  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:34.479  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:03:34.479  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:34.479  7347  7347 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:03:34.479  1017  4234 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:34.479  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.479  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.479  1017  4234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:34.479  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:34.499  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:34.499  1017  7228 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:34.499  1017  7228 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:03:34.499  1017  7228 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:34.499  1017  7228 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:34.499  1017  7228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:34.509  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:34.509  2002  7465 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:03:34.519  1017  1463 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-06 19:03:34.519  1017  4235 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:34.519  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:34.519  1017  4235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:34.519  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:34.529  1017  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:34.539  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:34.539  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:34.539  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:34.539  7347  7468 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:03:34.539  7347  7468 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:34.549  2002  7465 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:03:34.549  7347  7468 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-06 19:03:34.549  7347  7468 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:34.549  7347  7468 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:34.549  7347  7468 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c0c8b05
09-06 19:03:34.549  7347  7468 D BluetoothSocket: channel: 12
09-06 19:03:34.549  7347  7468 I BtOppRfcommListener: Accept thread started.
,09-06 19:03:34.679  1017  3321 D SSRM:n  : SIOP:: AP = 340
,09-06 19:03:35.069   289   289 E SMD     : DCD OFF,
,09-06 19:03:36.119  6743  6796 D BluetoothAdapter: disable()
,09-06 19:03:36.119  1017  7228 D SettingsProvider: name = bluetooth_on,
,09-06 19:03:36.129  7347  7362 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:03:36.129  7347  7362 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:03:36.129  7347  7362 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:03:36.129  7347  7362 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 19:03:36.129  7347  7362 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:03:36.129  1017  4234 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:36.129  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:03:36.129  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:36.129  1017  4234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:36.129  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:36.139  7347  7347 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:03:36.139  7347  7362 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:36.139  7347  7347 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e90e75a, channel: 19, state: LISTENING
09-06 19:03:36.139  7347  7347 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e90e75a, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3599bf4d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13cc1d8bmSocket: android.net.LocalSocket@36b1e68 impl:android.net.LocalSocketImpl@44fd281 fd:FileDescriptor[74]
09-06 19:03:36.139  7347  7347 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36b1e68 impl:android.net.LocalSocketImpl@44fd281 fd:FileDescriptor[74]
,09-06 19:03:36.139  7347  7362 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:03:36.139  7347  7362 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:03:36.139  1017  4970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:03:36.139  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:36.139  1017  4970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:36.139  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:36.149  7347  7362 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:03:36.149  7347  7362 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:03:36.149  3859  3859 D BluetoothPbap: Proxy object disconnected
09-06 19:03:36.149  1017  3357 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:03:36.149  3859  3859 D PbapServerProfile: Bluetooth service disconnected
09-06 19:03:36.149  7347  7362 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:03:36.149  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:36.149  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:03:36.159  1171  1171 D BluetoothTile:  onBluetoothStateChange:,
09-06 19:03:36.159  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:03:36.159  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:03:36.159  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:36.159  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:36.159  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-06 19:03:36.159  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:03:36.169  1868  1868 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:03:36.169  1017  1463 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:36.169  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:36.179  1017  1461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:03:36.179  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:03:36.179  1017  1331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:36.179  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:03:36.179  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:36.179  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:36.179  7347  7365 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:03:36.179  7347  7365 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:36.179  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:36.179  1017  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:36.179  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:36.179  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:36.179  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:36.189  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:36.189  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:36.189  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:36.189  6743  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:36.189  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:36.189  7347  7362 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:03:36.189  7347  7362 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:03:36.189  7347  7362 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 19:03:36.189  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:03:36.189  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:03:36.199  7347  7362 E bt-btif : BTM_SEC_CLR[17]: id 
09-06 19:03:36.199  7347  7362 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:03:36.199  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:36.199  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:36.199  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-06 19:03:36.199  7347  7468 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:03:36.199  7347  7413 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:03:36.199  7347  7413 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:03:36.199  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:36.199  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:36.199  7347  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:03:36.199  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:36.199  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:36.209  3859  3859 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:36.209  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:36.219  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:36.219  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:03:36.219  7347  7347 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14dd0767, channel: 5, state: LISTENING
09-06 19:03:36.219  7347  7347 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14dd0767, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35b9df13, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b07b914mSocket: android.net.LocalSocket@162615bd impl:android.net.LocalSocketImpl@160507b2 fd:FileDescriptor[76]
09-06 19:03:36.219  7347  7347 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@162615bd impl:android.net.LocalSocketImpl@160507b2 fd:FileDescriptor[76]
,09-06 19:03:36.219  7347  7347 I BtOppRfcommListener: stopping Accept Thread
09-06 19:03:36.219  7347  7347 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e28b303, channel: 12, state: LISTENING
09-06 19:03:36.219  7347  7347 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e28b303, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c0c8b05, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25315280mSocket: android.net.LocalSocket@2c2350b9 impl:android.net.LocalSocketImpl@35b7ecfe fd:FileDescriptor[79]
09-06 19:03:36.219  7347  7347 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c2350b9 impl:android.net.LocalSocketImpl@35b7ecfe fd:FileDescriptor[79]
09-06 19:03:36.219  7347  7468 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:03:36.219  7347  7347 V BluetoothOppManager: cleanUp...
,09-06 19:03:36.239  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:36.249  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:03:36.409  7347  7413 W bt-btif : ag scb idx 1 not allocated
09-06 19:03:36.409  7347  7413 W bt-btif : ag scb idx 2 not allocated
09-06 19:03:36.409  7347  7413 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:03:36.409  7347  7451 I bt_userial_mct: exiting userial_read_thread
09-06 19:03:36.409  7347  7451 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:03:36.409  7347  7365 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:03:36.409  7347  7415 I bt_vendor: hw_epilog_process
09-06 19:03:36.409  7347  7365 D bt_userial_mct: userial_close
09-06 19:03:36.409  7347  7365 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:03:37.409  7347  7365 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:03:37.409  7347  7365 I bt_vendor: bluetooth satus is on
09-06 19:03:37.409  7347  7365 I bt_vendor: bt-vendor : resetting BT status
09-06 19:03:37.409  7347  7365 I bt_vendor: Starting hciattach daemon
09-06 19:03:37.409  7347  7365 I bt_vendor: try to set false
,09-06 19:03:37.409  7347  7365 I bt_vendor: Starting hciattach daemon
09-06 19:03:37.409  7347  7365 I bt_vendor: try to set false
,09-06 19:03:37.409  7347  7365 I bt_vendor: cleanup
,09-06 19:03:37.409  7347  7413 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 19:03:37.409  7347  7365 I GKI_LINUX: GKI_exit_task 0 done
,09-06 19:03:37.419  7347  7365 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
,09-06 19:03:37.419  7347  7362 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:03:37.419  7347  7362 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:03:37.419  7347  7362 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:03:37.419  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:03:37.419  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:03:37.419  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:03:37.419  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:37.419  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:37.419  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.419  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:03:37.419  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.419  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:37.419  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:03:37.419  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:03:37.419  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:37.419  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:03:37.419  7347  7347 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:37.419  7347  7347 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:03:37.419  7347  7347 D BtGatt.GattService: stop()
09-06 19:03:37.419  7347  7347 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:03:37.419  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.419  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.419  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.429  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.429  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:03:37.429  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:37.429  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:37.429  7347  7347 D HeadsetService: Received stop request...Stopping profile...
09-06 19:03:37.429  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:37.429  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.429  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:37.429  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.429  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.429  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:03:37.429  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:37.429  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:03:37.429  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.439  1017  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:37.439  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.439  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:03:37.439  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.439  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.439  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:03:37.439  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:03:37.439  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:03:37.439  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:03:37.439  1017  4234 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:37.439  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.439  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.439  1017  4234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.439  3859  3859 D HeadsetProfile: Bluetooth service disconnected
09-06 19:03:37.439  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.439  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:03:37.439  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:03:37.439  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:03:37.439  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:37.439  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.449  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.449  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.449  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:37.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.449  7347  7362 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:37.449  1017  3357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:37.449  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.449  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.449  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.449  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.449  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:03:37.449  1017  7228 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:03:37.449  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:03:37.449  1017  7228 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:03:37.449  7347  7362 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:03:37.449  1017  7228 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:03:37.449  1017  7228 D BatteryService: stay LED for fully charged
09-06 19:03:37.449  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:03:37.449  1017  1017 I MotionRecognitionService: Plugged
09-06 19:03:37.449  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:03:37.459  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:03:37.459  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:03:37.459  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:03:37.459  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:03:37.469  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:37.469  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.469  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.469  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:37.469  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:37.469  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:37.469  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:03:37.469  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:03:37.469  7347  7362 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:03:37.469  7347  7362 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:03:37.469  7347  7362 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:03:37.469  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 19:03:37.469  7347  7347 D A2dpService: Received stop request...Stopping profile...
09-06 19:03:37.469  7347  7391 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:03:37.479  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.479  1017  1017 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:37.479  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:03:37.479  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-06 19:03:37.479  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:37.479  7347  7347 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:03:37.479  7347  7347 D HidService: Received stop request...Stopping profile...
09-06 19:03:37.479  7347  7347 D HidService: Stopping Bluetooth HidService
09-06 19:03:37.479  7347  7347 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:03:37.479  7347  7347 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:03:37.479  7347  7347 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:03:37.479  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.479  7347  7347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:03:37.479  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:37.479  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:37.479  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:37.479  7347  7347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:03:37.479  3859  3859 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:37.479  3859  3859 D A2dpProfile: Bluetooth service disconnected
09-06 19:03:37.479  3859  3859 D BluetoothInputDevice: Proxy object disconnected
09-06 19:03:37.479  3859  3859 D HidProfile: Bluetooth service disconnected
,09-06 19:03:37.479  7347  7347 D HealthService: Received stop request...Stopping profile...
,09-06 19:03:37.479  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.489  7347  7347 D PanService: Received stop request...Stopping profile...
,09-06 19:03:37.489  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:37.489  7347  7347 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:03:37.489  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:03:37.489  3859  3859 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:03:37.489  3859  3859 D PanProfile: Bluetooth service disconnected
,09-06 19:03:37.489  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb,
,09-06 19:03:37.489  7347  7347 D SapService: Received stop request...Stopping profile...
09-06 19:03:37.489  7347  7347 D SapService: Stopping Bluetooth SapService
09-06 19:03:37.489  7347  7347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:37.489  3859  3859 D BluetoothMap: Proxy object disconnected
09-06 19:03:37.489  3859  3859 D MapProfile: Bluetooth service disconnected
,09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:03:37.499  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:03:37.499  7347  7347 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:03:37.499  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:37.499  7347  7392 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:03:37.499  7347  7347 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:03:37.499  7347  7347 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-06 19:03:37.499  3859  3859 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:03:37.499  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.499  7347  7347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:03:37.499  7347  7347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:03:37.499  3859  3859 D SapProfile: Bluetooth service disconnected
,09-06 19:03:37.499  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:37.499  7347  7347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:03:37.499  7347  7347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:03:37.499  7347  7347 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:03:37.499  7347  7347 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 19:03:37.499  7347  7347 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:03:37.499  7347  7347 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:03:37.499  7347  7347 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:03:37.499  7347  7362 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:03:37.499  7347  7362 D BluetoothAdapterProperties: Setting state to 10
09-06 19:03:37.499  7347  7362 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-06 19:03:37.499  7347  7362 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:37.509  7347  7362 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:03:37.509  7347  7362 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:03:37.509  1464  1479 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:37.509  1464  1479 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:37.509  7347  7362 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:03:37.509  7347  7362 I BluetoothAdapterState: Entering OffState
,09-06 19:03:37.509  7397  7407 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:03:37.509  7397  7407 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:37.509  7347  7355 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:03:37.509  3859  3946 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.509  3859  3946 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:03:37.509  3859  3872 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:03:37.509  2002  2153 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.509  2002  2153 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:37.509  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.509  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:37.509  7347  7456 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 19:03:37.509  7347  7456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:03:37.509  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:03:37.519  1432  1472 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 19:03:37.519  1432  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:03:37.519  3859  3946 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:03:37.519  1171  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.519  1171  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:03:37.519  3859  3872 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:03:37.519  3859  3872 D Bluetoothsap: Unbinding service...
,09-06 19:03:37.519  3859  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:03:37.519  3859  3946 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:03:37.519  6743  6751 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.519  6743  6751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:03:37.519  6743  6751 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 19:03:37.519  6743  6751 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:03:37.519  6743  6751 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-06 19:03:37.519  6743  6751 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:03:37.529  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:03:37.529  1450  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:03:37.529  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:03:37.529  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:03:37.539  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:37.539  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,09-06 19:03:37.539  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:03:37.539  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
,09-06 19:03:37.549  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:03:37.549  1171  1739 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
,09-06 19:03:37.549  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:37.549  1171  1171 D BluetoothTile:  getBluetoothState : 10
09-06 19:03:37.549  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:37.549  1171  1171 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:37.549  1171  1739 D BluetoothAdapter: 102554603: getState() :  mService = null. Returning STATE_OFF
,09-06 19:03:37.549  1017  1511 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:37.549  1868  1868 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:03:37.549  1017  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:03:37.549  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:03:37.549  2002  2154 D BluetoothAdapter: 907799592: getState() :  mService = null. Returning STATE_OFF
09-06 19:03:37.549  2002  2154 D BluetoothAdapter: 907799592: getState() :  mService = null. Returning STATE_OFF
,09-06 19:03:37.549  1017  4970 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:37.549  1017  4970 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.559  1017  4970 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:37.559  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:37.559  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:37.559  1017  4970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:37.559  1017  4970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:37.559  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:37.559  1017  1511 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:03:37.559  1017  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.559  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:37.559  1017  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:37.559  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:03:37.559  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:37.559  7347  7365 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:03:37.559  7347  7347 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:03:37.559  7347  7347 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:03:37.559  7347  7347 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:03:37.559  7347  7362 W art     : No such thread id for suspend: 11
,09-06 19:03:37.569  3859  3859 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:37.569  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:37.569  7347  7347 I art     : System.exit called, status: 0
09-06 19:03:37.569  7347  7347 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:03:37.569  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:37.569  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:03:37.719  1017  3357 I ActivityManager: Process com.android.bluetooth (pid 7347)(adj 0) has died(38,719)
,09-06 19:03:37.729  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:37.729  1017  1331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:37.729  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:03:37.729  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:37.739  1017  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:37.739  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:37.739  2002  7485 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:03:37.749  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:37.759  1017  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:37.759  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:37.759  1017  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:37.759  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:37.769  2002  7485 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:03:38.069   289   289 E SMD     : DCD OFF
,09-06 19:03:39.139  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop,
09-06 19:03:39.139  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:39.339  1017  1049 I PowerManagerService: [PWL] Off : 75s ago
,09-06 19:03:39.339  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-06 19:03:39.339  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-06 19:03:39.339  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=14310)
,09-06 19:03:39.359  1017  1313 E Watchdog: !@Sync 4
,09-06 19:03:40.059   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:41.059   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:41.059   289   289 E SMD     : DCD OFF
,09-06 19:03:42.069   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:42.139  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:42.139  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68c22e4 added. We now have 6 listener(s)
09-06 19:03:42.139  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:42.149  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:42.149  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ca4834d added. We now have 7 listener(s)
09-06 19:03:42.149  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:42.149  6743  6796 I System.out: IsBluetoothEnabled
,09-06 19:03:42.149  6743  6796 D BluetoothAdapter: disable()
,09-06 19:03:42.149  1017  1511 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 19:03:42.149  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:42.149  6743  6796 D BluetoothAdapter: enable()
,09-06 19:03:42.159  1017  1494 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-06 19:03:42.159  1017  1494 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:42.159  1017  1494 W BluetoothManagerService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:03:42.159  1017  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,09-06 19:03:42.159  1017  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:03:42.159  1017  1494 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:03:42.159  1017  1494 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:03:42.159  1017  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:42.159  1017  1494 D SettingsProvider: name = bluetooth_on
,09-06 19:03:42.159  1017  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:03:42.159  1017  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-06 19:03:42.179  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-06 19:03:42.179  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:03:42.179  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 19:03:42.179  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-06 19:03:42.179  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:42.179  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:42.179  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:42.179  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:42.199  7491  7491 E Zygote  : MountEmulatedStorage()
09-06 19:03:42.199  7491  7491 E Zygote  : v2
09-06 19:03:42.199  7491  7491 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:03:42.199  7491  7491 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:42.199  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:42.209  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7491 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:03:42.209  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:42.209  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:03:42.239  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:42.239  7491  7491 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:03:42.279  7491  7491 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:03:42.279  7491  7491 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:03:42.299  7491  7491 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding HidService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding PanService
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding SapService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 19:03:42.339  7491  7491 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:03:42.339  7491  7491 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:03:42.339  1017  4234 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-06 19:03:42.339  1017  4234 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.339  1017  4234 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.339  1017  4234 D SettingsProvider: selectionArgs: false
09-06 19:03:42.339  1017  4234 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.339  1017  4234 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.339  1017  4234 D SettingsProvider: ret = -1
,09-06 19:03:42.339  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 19:03:42.339  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.339  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.339  1017  1135 D SettingsProvider: selectionArgs: false
09-06 19:03:42.339  1017  1135 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  1135 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:03:42.349  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.349  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.349  1017  1029 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  1029 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  1029 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  4235 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:03:42.349  1017  4235 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.349  1017  4235 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.349  1017  4235 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  4235 D SettingsProvider: selectionArgs: 1002
,09-06 19:03:42.349  1017  4235 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  4235 D SettingsProvider: ret = -1
09-06 19:03:42.349  1017  1463 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:03:42.349  1017  1463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:03:42.349  1017  1463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.349  1017  1463 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  1463 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  1463 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  1463 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  1331 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:03:42.349  1017  1331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:03:42.349  1017  1331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.349  1017  1331 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  1331 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  1331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  1331 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:03:42.349  1017  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:03:42.349  1017  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.349  1017  1216 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  1216 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  1216 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  7228 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:03:42.349  1017  7228 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.349  1017  7228 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:03:42.349  1017  7228 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  7228 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  7228 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  7228 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  3357 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:42.349  1017  3357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.349  1017  3357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:03:42.349  1017  3357 D SettingsProvider: selectionArgs: false
09-06 19:03:42.349  1017  3357 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.349  1017  3357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.349  1017  3357 D SettingsProvider: ret = -1
,09-06 19:03:42.349  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:42.349  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.359  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:03:42.359  1017  1030 D SettingsProvider: selectionArgs: false
09-06 19:03:42.359  1017  1030 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.359  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:03:42.359  1017  1030 D SettingsProvider: ret = -1
09-06 19:03:42.359  1017  4970 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:03:42.359  1017  4970 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.359  1017  4970 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.359  1017  4970 D SettingsProvider: selectionArgs: false
09-06 19:03:42.359  1017  4970 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.359  1017  4970 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.359  1017  4970 D SettingsProvider: ret = -1
09-06 19:03:42.359  1017  1511 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:03:42.359  1017  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.359  1017  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:42.359  1017  1511 D SettingsProvider: selectionArgs: false
09-06 19:03:42.359  1017  1511 D SettingsProvider: selectionArgs: 1002
09-06 19:03:42.359  1017  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:42.359  1017  1511 D SettingsProvider: ret = -1
,09-06 19:03:42.369  7491  7491 D BluetoothAdapterState: make,
,09-06 19:03:42.379  7491  7491 I bluedroid: init,
,09-06 19:03:42.379  7491  7506 I BluetoothAdapterState: Entering OffState,
09-06 19:03:42.379  7491  7491 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:03:42.379  7491  7491 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:03:42.379  7491  7491 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:03:42.379  7491  7491 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:03:42.379  7491  7491 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 19:03:42.379  7491  7509 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:03:42.379  7491  7491 I bluedroid: get_profile_interface socket
09-06 19:03:42.379  7491  7491 I bluedroid: get_profile_interface map_client
09-06 19:03:42.389  7491  7509 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:03:42.389  7491  7509 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:03:42.389  7491  7509 I bluedroid: getModelRssiValues
09-06 19:03:42.389  7491  7509 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:03:42.389  7491  7509 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-06 19:03:42.389  7491  7491 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:03:42.389  1017  1017 D SettingsProvider: name = bluetooth_name
,09-06 19:03:42.389  7491  7509 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:03:42.399  7491  7491 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:42.399  1017  7228 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:03:42.399  1017  7228 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.399  1017  7228 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.399  1017  7228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:42.399  1017  7228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.399  7491  7499 I bluedroid: config_hci_snoop_log
,09-06 19:03:42.399  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:03:42.409  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:03:42.409  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:03:42.409  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:03:42.409  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:03:42.409  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:42.409  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:03:42.419  7491  7491 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:03:42.419  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:03:42.419  7491  7506 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-06 19:03:42.419  7491  7506 D BluetoothAdapterProperties: Setting state to 11
09-06 19:03:42.419  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:03:42.419  7491  7506 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:03:42.419  7491  7506 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:42.419  7491  7506 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:03:42.419  7491  7506 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:03:42.419  7491  7506 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:03:42.419  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:42.429  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:03:42.429  7491  7506 D BluetoothSecureManager: getInstant: null
09-06 19:03:42.429  7491  7506 D BluetoothSecureManager: calling getMethod for getService
09-06 19:03:42.429  7491  7506 D BluetoothSecureManager: calling getService
,09-06 19:03:42.429  7491  7506 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@16bfe5c0
,09-06 19:03:42.429  1017  1494 D BluetoothSecureManagerService: isSecureModeEnabled
,09-06 19:03:42.429  1017  1494 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 19:03:42.429  7491  7506 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:03:42.429  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:03:42.429  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:03:42.429  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:03:42.429  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:42.439  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:42.439  1171  1171 D BluetoothTile:  getBluetoothState : 11
,09-06 19:03:42.439  1868  1868 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:03:42.439  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:03:42.439  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:03:42.439  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:03:42.449  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:03:42.449  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-06 19:03:42.449  7491  7506 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,09-06 19:03:42.449  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:42.449  7491  7506 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:03:42.449  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:03:42.449  1017  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:03:42.449  7491  7506 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:42.449  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:03:42.449  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:03:42.449  1017  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:42.449  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:42.449  1017  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:42.449  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:42.449  1017  1331 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:03:42.459  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:03:42.459  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:42.459  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
09-06 19:03:42.459  7491  7506 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:03:42.459  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:03:42.459  7491  7506 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:03:42.459  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:42.459  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:03:42.469  7491  7506 D BluetoothBondStateMachine: make
,09-06 19:03:42.469  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:03:42.469  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:03:42.469  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:03:42.469  7491  7513 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:03:42.479  1017  7228 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:42.479  1017  7228 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.479  1017  7228 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.479  1017  7228 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.479  1017  7228 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.479  7491  7491 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:42.479  7491  7491 D BtGatt.GattService: Received start request. Starting profile...,
09-06 19:03:42.479  7491  7491 D BtGatt.GattService: start()
09-06 19:03:42.479  7491  7491 D BtGatt.GattService: start()
,09-06 19:03:42.479  7491  7491 I bluedroid: get_profile_interface gatt
09-06 19:03:42.479  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:42.479  7491  7491 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:03:42.489  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:03:42.489  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:03:42.489  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:03:42.489  1017  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:42.489  1017  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.489  1017  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.489  1017  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.489  1017  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.499  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:03:42.499  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:03:42.499  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:03:42.499  7491  7491 D BtGatt.GattService: mStartError = false
09-06 19:03:42.499  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.499  7491  7491 D HeadsetService: Received start request. Starting profile...
,09-06 19:03:42.499  7491  7491 D HeadsetService: start()
,09-06 19:03:42.509  7491  7491 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:03:42.509  7491  7491 D HeadsetStateMachine: make
,09-06 19:03:42.509  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:42.509  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.509  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:42.509  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.509  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.509  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:03:42.509  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:03:42.509  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:03:42.519  7491  7491 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:03:42.519  1017  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:42.519  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.519  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:42.519  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.519  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.519  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.529  1017  4235 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:03:42.529  1017  4235 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.529  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.529  1017  4235 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.529  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:03:42.529  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:03:42.529  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:03:42.529  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:03:42.529  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:03:42.529  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.529  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:42.529  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.529  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:03:42.529  7491  7491 I bluedroid: get_profile_interface handsfree
,09-06 19:03:42.539  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:42.539  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.539  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.539  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.539  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.539  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:42.539  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:03:42.539  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:03:42.539  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:03:42.549  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:42.549  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.549  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.549  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.549  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.559  7491  7491 I DualScoManager: Instantiating Dual Sco Manager
,09-06 19:03:42.559  7491  7491 I DualScoManager: Set HeadsetServiceHelper
,09-06 19:03:42.559  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:03:42.559  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:03:42.559  7491  7506 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-06 19:03:42.559  1017  3357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:42.559  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.559  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.559  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.569  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.569  7491  7491 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:03:42.569  1017  7228 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 19:03:42.569  1017  7228 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:42.569  1017  7228 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:03:42.569  1017  7228 D SettingsProvider: selectionArgs: false
09-06 19:03:42.569  1017  7228 D SettingsProvider: selectionArgs: 1002
,09-06 19:03:42.569  1017  7228 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:03:42.569  1017  7228 D SettingsProvider: ret = -1
,09-06 19:03:42.569  7491  7516 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:03:42.579  7491  7491 D HeadsetService: mStartError = false
,09-06 19:03:42.579  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.579  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:03:42.579  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:03:42.579  7491  7506 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:03:42.579  7491  7516 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-06 19:03:42.579  7491  7516 D HeadsetStateMachine: map size, before remove : 0
09-06 19:03:42.579  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:42.579  7491  7516 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:03:42.579  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:42.579  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:42.579  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:42.579  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:42.579  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:42.589  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:42.589  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-06 19:03:42.589  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-06 19:03:42.589  7491  7506 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:03:42.589  7491  7506 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
09-06 19:03:42.589  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 19:03:42.589  7491  7491 D A2dpService: Received start request. Starting profile...
,09-06 19:03:42.589  7491  7491 D A2dpService: start()
,09-06 19:03:42.599  7491  7506 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,09-06 19:03:42.599  7491  7491 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:03:42.599  7491  7491 I bluedroid: get_profile_interface avrcp
,09-06 19:03:42.609  7491  7491 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
09-06 19:03:42.609  7491  7491 D Avrcp   : Initialize Media Controller
09-06 19:03:42.609  7491  7491 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:03:42.609  7491  7491 E Avrcp   : getActiveSessions
09-06 19:03:42.609  7491  7491 D Avrcp   : pick active media Controller,
09-06 19:03:42.609  7491  7491 D Avrcp   : Get the active Media Controller 
,09-06 19:03:42.629  7491  7491 I Avrcp   :  Updating now playing list upon AVRCP Start,
,09-06 19:03:42.629  7491  7520 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-06 19:03:42.629  7491  7491 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:03:42.629  7491  7491 D A2dpStateMachine: make
,09-06 19:03:42.629  7491  7491 I bluedroid: get_profile_interface a2dp
09-06 19:03:42.629  7491  7522 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:03:42.629  7491  7491 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:03:42.639  7491  7491 D A2dpService: mStartError = false
09-06 19:03:42.639  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.639  7491  7491 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:03:42.639  7491  7491 D HidService: Received start request. Starting profile...
09-06 19:03:42.639  7491  7491 D HidService: start()
09-06 19:03:42.639  7491  7491 I bluedroid: get_profile_interface hidhost
09-06 19:03:42.639  7491  7491 D HidService: setHidService(): set to: null
09-06 19:03:42.639  7491  7491 D HidService: mStartError = false
09-06 19:03:42.639  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.639  7491  7491 D HeadsetStateMachine: Try to query the phonestate on bind
09-06 19:03:42.639  7491  7521 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:03:42.639  1432  1459 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:03:42.639  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:03:42.639  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:03:42.649  1432  1459 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:03:42.649  7491  7491 D HeadsetStateMachine: Proxy object connected
,09-06 19:03:42.649  7491  7491 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:03:42.649  7491  7491 D HealthService: Received start request. Starting profile...
09-06 19:03:42.649  7491  7491 D HealthService: start()
,09-06 19:03:42.649  7491  7491 I bluedroid: get_profile_interface health
09-06 19:03:42.649  7491  7491 D HealthService: mStartError = false
09-06 19:03:42.649  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.649  7491  7491 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:03:42.649  7491  7491 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:03:42.649  7491  7516 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:03:42.649  7491  7516 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:03:42.649  7491  7491 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-06 19:03:42.649  7491  7491 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:03:42.659  7491  7520 D BluetoothMediaBrowser: no now playing list
,09-06 19:03:42.659  7491  7520 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:03:42.659  7491  7491 D PanService: Received start request. Starting profile...
09-06 19:03:42.659  7491  7491 D PanService: start()
09-06 19:03:42.659  7491  7491 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:03:42.659  7491  7491 I bluedroid: get_profile_interface pan
,09-06 19:03:42.659  7491  7491 D PanService: mStartError = false
,09-06 19:03:42.659  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.659  7491  7491 D BluetoothMapService: Received start request. Starting profile...
09-06 19:03:42.659  7491  7491 D BluetoothMapService: start()
,09-06 19:03:42.659  7491  7491 D BluetoothMapService: mStartError = false
,09-06 19:03:42.659  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:42.659  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-06 19:03:42.659  7491  7491 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:03:42.669  7491  7491 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:03:42.669  7491  7516 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:03:42.669  7491  7516 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:03:42.669  7491  7516 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:03:42.669  7491  7491 D SapService: Received start request. Starting profile...
,09-06 19:03:42.669  7491  7491 D SapService: start()
09-06 19:03:42.669  7491  7491 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-06 19:03:42.669  7491  7491 I bluedroid: get_profile_interface sap
09-06 19:03:42.669  7491  7491 D SapService: mStartError = false
,09-06 19:03:42.669  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:42.669  7491  7491 D BluetoothA2dp: Proxy object connected
,09-06 19:03:42.669  7491  7491 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:03:42.669  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-06 19:03:42.669  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:03:42.669  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-06 19:03:42.679  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:03:42.699  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:03:42.699  7491  7491 E BluetoothAdapterService(399388107): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:03:42.709  7491  7506 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 19:03:42.709  7491  7506 I bluedroid: enable
,09-06 19:03:42.709  7491  7506 I bt_hci_bdroid: init
,09-06 19:03:42.709  7491  7506 I bt_vendor: bt-vendor : init
,09-06 19:03:42.709  7491  7506 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:03:42.709  7491  7506 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-06 19:03:42.709  7491  7506 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 19:03:42.709  7491  7506 D bt_userial_mct: userial_init
,09-06 19:03:42.709  7491  7526 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:03:42.709  7491  7506 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:03:42.709  7491  7506 I bt_vendor: Starting hciattach daemon
09-06 19:03:42.709  7491  7506 I bt_vendor: try to set false
,09-06 19:03:42.709  7491  7506 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:03:42.709  7491  7506 I bt_vendor: Starting hciattach daemon
09-06 19:03:42.709  7491  7506 I bt_vendor: try to set true
,09-06 19:03:42.729  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:03:42.789  7536  7536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:03:42.799  7537  7537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:03:42.819  7539  7539 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:03:42.819  7540  7540 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:03:42.829  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:03:42.839  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:03:42.859  1017  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 19:03:43.059   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:03:43.109  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-06 19:03:43.119  7546  7546 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:03:43.169  7491  7506 I bt_vendor: bluetooth satus is on,
09-06 19:03:43.169  7491  7528 D bt_userial_mct: userial_open(port:0)
,09-06 19:03:43.169  7491  7528 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 19:03:43.169  7491  7528 I bt_vendor: Done intiailizing UART
,09-06 19:03:43.169  7491  7528 I bt_vendor: Done intiailizing UART
09-06 19:03:43.169  7491  7528 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-06 19:03:43.169  7491  7528 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
09-06 19:03:43.179  7491  7548 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_SAP
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:03:43.179  7491  7526 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:03:43.189  7491  7526 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 19:03:43.279  7491  7526 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:03:43.279  7491  7526 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4125ed1 
,09-06 19:03:43.279  7491  7526 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4125ed1 
,09-06 19:03:43.299  7491  7509 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:03:43.299  7491  7509 E bt-btif : Calling BTA_HhEnable
,09-06 19:03:43.299  7491  7509 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:03:43.309  7491  7509 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:03:43.309  7491  7509 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:03:43.309  7491  7509 I bluedroid: getModelRssiValues
09-06 19:03:43.309  7491  7509 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:03:43.309  7491  7509 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:03:43.309  1017  1017 D SettingsProvider: name = bluetooth_name
,09-06 19:03:43.309  7491  7509 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:03:43.309  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:43.319  7491  7509 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:03:43.319  7491  7509 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:43.319  7491  7509 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:03:43.319  7491  7509 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-06 19:03:43.319  7491  7509 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1,
09-06 19:03:43.319  7491  7509 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:03:43.319  7491  7509 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:03:43.319  7491  7509 E bt-btif : btif_sock_init: !vhci_init
09-06 19:03:43.319  7491  7509 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 19:03:43.319  7491  7509 D IOP_DB_BT: db_open: db_open : handle 3025489936l, read 13894 bytes onto local cache
09-06 19:03:43.319  7491  7509 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 19:03:43.319  7491  7509 D IOP_DB_BT: db_query: result 1
,09-06 19:03:43.319  7491  7509 I         : iop_db_open: iop_db_open status 0
,09-06 19:03:43.319  7491  7509 D bte_conf: Device ID record 1 : primary
09-06 19:03:43.329  7491  7509 D bte_conf:   vendorId            = 0075
09-06 19:03:43.329  7491  7509 D bte_conf:   vendorIdSource      = 0001
09-06 19:03:43.329  7491  7509 D bte_conf:   product             = 0100
09-06 19:03:43.329  7491  7509 D bte_conf:   version             = 0200
09-06 19:03:43.329  7491  7509 D bte_conf:   clientExecutableURL = 
09-06 19:03:43.329  7491  7548 E bt_mct  : hci lib postload completed
09-06 19:03:43.329  7491  7509 D bte_conf:   serviceDescription  = 
09-06 19:03:43.329  7491  7509 D bte_conf:   documentationURL    = 
09-06 19:03:43.329  7491  7509 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:03:43.329  7491  7506 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:03:43.329  7491  7506 D BluetoothAdapterProperties: ScanMode =  20
,09-06 19:03:43.329  7491  7506 D BluetoothAdapterProperties: State =  11
,09-06 19:03:43.329  7491  7509 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:03:43.329  1017  4970 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:03:43.329  7491  7506 D BluetoothAdapterProperties: Setting state to 12
09-06 19:03:43.329  7491  7506 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:03:43.339  7491  7509 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:03:43.339  7491  7509 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:03:43.339  7491  7509 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:03:43.339  1017  1511 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:03:43.339  1017  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:43.339  1017  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:43.339  1017  1511 D SettingsProvider: selectionArgs: false
09-06 19:03:43.339  1017  1511 D SettingsProvider: selectionArgs: 1002
09-06 19:03:43.339  1017  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:43.339  1017  1511 D SettingsProvider: ret = -1
,09-06 19:03:43.339  7491  7506 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:03:43.339  7491  7506 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:03:43.339  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:03:43.339  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.339  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.339  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.339  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.349  7491  7506 D BluetoothAdapterService: Autoconnection is available 
09-06 19:03:43.349  7491  7506 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:03:43.349  7491  7506 D BluetoothAdapterService: starting service from this receiver
,09-06 19:03:43.349  1017  3357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:43.349  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.349  1464  1672 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:03:43.349  1464  1672 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.349  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.349  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.349  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:43.349  7397  7409 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.349  7397  7409 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.349  3859  3946 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:03:43.359  3859  3946 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.359  7491  7506 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:03:43.359  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:03:43.359  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:43.359  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:43.359  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:43.359  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:03:43.359  3859  3872 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:03:43.369  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:43.379  7491  7491 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:03:43.549  1017  1046 I art     : Explicit concurrent mark sweep GC freed 76389(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 24MB/36MB, paused 2.477ms total 180.856ms
09-06 19:03:43.549  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:03:43.549  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.549  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.549  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.549  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.549  2002  5669 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.549  2002  5669 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:43.549  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.549  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.549  3859  3879 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.549  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:43.549  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.549  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.549  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.549  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.549  3859  3879 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:43.549  1432  3265 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.559  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:43.559  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.559  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.559  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.559  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.559  1432  3265 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:43.559  7491  7491 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:03:43.559  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:43.559  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.559  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:03:43.559  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.559  1432  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.559  1432  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.559  1017  1511 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:03:43.559  3859  3946 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:03:43.559  3859  3859 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:43.559  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:03:43.559  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.569  1017  1017 D BluetoothA2dp: Proxy object connected
09-06 19:03:43.569  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.569  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.569  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.569  7491  7552 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:03:43.569  7491  7511 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:03:43.569  7491  7503 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.569  7491  7503 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.569  1171  1959 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.569  3859  3859 D BluetoothPbap: Proxy object connected
09-06 19:03:43.569  3859  3859 D PbapServerProfile: Bluetooth service connected
09-06 19:03:43.569  3859  3859 D BluetoothMap: Proxy object connected
09-06 19:03:43.569  3859  3859 D MapProfile: Bluetooth service connected
09-06 19:03:43.569  3859  3859 D BluetoothMap: getConnectedDevices()
,09-06 19:03:43.569  1171  1959 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.569  3859  3946 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:03:43.569  3859  3946 D Bluetoothsap: Binding service...
,09-06 19:03:43.569  7491  7552 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:03:43.569  7491  7552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:43.569  3859  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:03:43.569  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:03:43.569  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.579  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:43.579  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.579  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.579  3859  3946 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:03:43.579  3859  3879 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:03:43.579  3859  3859 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-06 19:03:43.579  7491  7552 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 19:03:43.579  7491  7552 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:43.579  7491  7552 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:43.579  7491  7552 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3599bf4d
09-06 19:03:43.579  3859  3859 D SapProfile: Bluetooth service connected
09-06 19:03:43.579  3859  3859 D Bluetoothsap: getConnectedDevices()
,09-06 19:03:43.579  7491  7552 D BluetoothSocket: channel: 19
09-06 19:03:43.579  7491  7552 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:03:43.579  3859  3879 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.579  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:03:43.579  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:03:43.579  1017  1046 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:43.579  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.579  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.579  3859  3946 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:03:43.579  3859  3859 D BluetoothA2dp: Proxy object connected
09-06 19:03:43.579  3859  3859 D A2dpProfile: Bluetooth service connected
,09-06 19:03:43.589  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:03:43.589  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.589  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.589  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.589  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.589  3859  3859 D BluetoothInputDevice: Proxy object connected
,09-06 19:03:43.589  3859  3859 D HidProfile: Bluetooth service connected
,09-06 19:03:43.589  1432  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.589  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:03:43.589  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.589  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:43.589  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.589  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.599  1432  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:43.599  1464  1672 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.599  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:03:43.599  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.599  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:43.599  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.599  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.599  1464  1672 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:43.599  3859  3872 D BluetoothPan: Binding service...
,09-06 19:03:43.599  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:03:43.599  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.609  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:43.609  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.609  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.609  3859  3859 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:03:43.609  6743  6752 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:03:43.609  6743  6752 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:03:43.609  3859  3859 D PanProfile: Bluetooth service connected
09-06 19:03:43.609  1017  1046 D BluetoothPan: Binding service...
,09-06 19:03:43.609  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:03:43.609  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.609  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:03:43.609  1432  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:03:43.609  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:03:43.609  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:03:43.609  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.609  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.609  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:03:43.609  1432  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:03:43.619  1450  1766 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:03:43.619  1450  1766 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:03:43.619  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:03:43.619  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:03:43.619  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:43.619  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:03:43.619  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:03:43.619  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3d6c479e, true
,09-06 19:03:43.619  1432  1432 D BluetoothHeadset: registerMessageListener
,09-06 19:03:43.629  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:03:43.629  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:03:43.629  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:43.629  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:43.629  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:43.629  1171  1171 D BluetoothTile:  getBluetoothState : 12
,09-06 19:03:43.639  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:03:43.639  1017  1511 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:43.639  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:03:43.639  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:03:43.639  1868  1868 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:03:43.639  3859  3859 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:43.649  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:43.649  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:43.649  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:03:43.649  7491  7503 D HeadsetService: registerMessageListener
,09-06 19:03:43.649  7491  7503 D HeadsetService: registerMessageListener
,09-06 19:03:43.649  7491  7516 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:03:43.649  7491  7516 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d4e1a02
,09-06 19:03:43.649  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-06 19:03:43.649  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:03:43.649  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:43.649  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:03:43.649  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:43.659  7491  7553 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:03:43.659  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-06 19:03:43.659  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 19:03:43.659  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:03:43.659  3859  3859 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:03:43.659  3859  3859 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:03:43.659  3859  3859 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:03:43.659  3859  3859 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:03:43.659  7491  7553 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:03:43.659  7491  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:43.669  7491  7553 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 19:03:43.669  7491  7553 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:43.669  7491  7553 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:43.669  7491  7553 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35b9df13
09-06 19:03:43.669  7491  7553 D BluetoothSocket: channel: 5
09-06 19:03:43.669  7491  7516 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:03:43.669  7491  7516 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:03:43.669   284   678 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:03:43.669   284   678 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:03:43.669   284   678 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:03:43.669   284   678 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:03:43.669   284   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:03:43.669   284   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:03:43.669   284   678 V audio_hw_primary: adev_set_parameters: exit
09-06 19:03:43.669  7491  7516 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:03:43.669  3859  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:43.679  1017  1331 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:03:43.679  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.679  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.679  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.679  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:03:43.679  3859  3859 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:43.679  3859  3859 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:03:43.689  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:43.689  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:03:43.689  1017  2074 V SAMP_SPCM_test: CSC File load.. 
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,09-06 19:03:43.699  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 19:03:43.729  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-06 19:03:43.739  1017  2074 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:03:43.739  1017  2074 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-06 19:03:43.749  7491  7491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
09-06 19:03:43.749  7491  7491 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:03:43.759  1017  2074 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-06 19:03:43.759  1017  2074 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:43.759  1017  2074 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:43.759  1017  2074 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:43.759  1017  2074 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:43.779  7559  7559 E Zygote  : MountEmulatedStorage()
09-06 19:03:43.779  7559  7559 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:03:43.779  7559  7559 E Zygote  : v2
09-06 19:03:43.779  7559  7559 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:43.779  1017  2074 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7559 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:03:43.779  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:03:43.779  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:03:43.779  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:03:43.779  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:43.779  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:03:43.779  7559  7559 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:43.789  7559  7559 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:43.789  7559  7559 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:43.799  2002  2002 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:43.799  1017  3357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:03:43.799  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-06 19:03:43.799  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.799  1017  3357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:43.799  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:43.809  2002  2002 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:03:43.809  2002  7569 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:03:43.819  1017  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:43.819  1017  1216 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:03:43.819  1017  1461 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.819  1017  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:03:43.819  1017  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:43.829  7559  7559 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:43.829  7559  7559 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:43.839  7491  7578 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:03:43.839  7491  7578 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:43.839  7491  7578 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-06 19:03:43.839  7491  7578 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:03:43.839  7491  7578 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:03:43.839  7491  7578 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c0c8b05
,09-06 19:03:43.839  7491  7578 D BluetoothSocket: channel: 12
09-06 19:03:43.839  7491  7578 I BtOppRfcommListener: Accept thread started.
,09-06 19:03:43.849  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:03:43.849  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:43.849  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:43.849  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:03:43.849  7559  7559 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:03:43.859  2002  7569 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:03:43.889  1017  2074 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 19:03:44.069   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:03:44.079   289   289 E SMD     : DCD OFF,
,09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:44.189  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:44.189  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:44.189  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:44.189  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c9b8e02 added. We now have 8 listener(s)
,09-06 19:03:44.199  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:44.199  1017  4970 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:03:44.199  1017  4970 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:03:44.199  1017  4970 D SecContentProvider2: mCursor = null
,09-06 19:03:44.199  1017  4970 D WifiService: setWifiEnabled: false pid=6743, uid=10171
,09-06 19:03:44.199  1017  4970 D SettingsProvider: name = wifi_on
,09-06 19:03:44.209  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:44.209  1017  1216 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:03:44.209  1017  1216 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:03:44.209  1017  1216 D SecContentProvider2: mCursor = null
,09-06 19:03:44.209  1017  1216 D WifiService: setWifiEnabled: true pid=6743, uid=10171
,09-06 19:03:44.209  1017  1216 W ActivityManager: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:03:44.209  1017  1216 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:03:44.209  1017  1216 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6743, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:03:44.209  1017  1216 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:03:44.209  1017  1216 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:03:44.209  1017  1216 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:03:44.209  1017  1216 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:03:44.209  1017  1216 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:03:44.219  1017  1216 D SettingsProvider: name = wifi_on
,09-06 19:03:44.219  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:03:44.549  1017  1044 D Tethering: interfaceAdded wlan0
,09-06 19:03:44.559  1017  1130 E Tethering: No numeric data
,09-06 19:03:44.559  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:03:44.559  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:03:44.559  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:03:44.559  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:44.559  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:03:44.569  1017  1124 V NetworkStats: performPollLocked() took 8ms,
09-06 19:03:44.559  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:44.569  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:44.559  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:44.569  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:03:44.559  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:03:44.559  1017  1130 D Tethering: clearTetheredNotification(),
09-06 19:03:44.559  1017  1130 D Tethering: InitialState.processMessage what=4,
09-06 19:03:44.569  1017  1130 E Tethering: No numeric data
09-06 19:03:44.569  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 19:03:44.569  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:03:44.569  1017  1130 D Tethering: clearTetheredNotification()
09-06 19:03:44.569  1017  1044 D Tethering: interfaceAdded p2p0
,09-06 19:03:44.569  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
09-06 19:03:44.579  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:44.579  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:03:44.579  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:03:44.579   279  1003 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:03:44.579  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:44.579   279  1003 D SoftapController: Softap fwReload - Ok
,09-06 19:03:44.579  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:03:44.589  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:44.589  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:44.589  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:44.589  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:44.589   279  1003 D CommandListener: Setting iface cfg
09-06 19:03:44.589   279  1003 D CommandListener: Trying to bring down wlan0
,09-06 19:03:44.589   279  1003 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:44.589  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:03:44.599  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:44.599  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
09-06 19:03:44.599  1017  1124 V NetworkStats: performPollLocked() took 9ms
09-06 19:03:44.599  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:44.609  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:03:44.609  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:44.609  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-06 19:03:44.609  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:44.609  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:03:44.609  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:44.619  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:03:44.609  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:44.609  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:44.609  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:44.619  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:44.619  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:44.619  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:03:44.619  1171  1171 D HotspotTile: onReceive : 2, 0
,09-06 19:03:44.629  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:44.629  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:44.629  1017  3357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:44.629  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:44.629  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:44.629  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:44.629  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:44.639  1616  1616 I Hs20UtilService: Starting #19
09-06 19:03:44.639  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:44.639  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:03:44.639  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:44.639  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:03:44.639  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:44.659  7591  7591 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 19:03:44.659  7591  7591 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 19:03:44.659  7591  7591 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:03:44.669  7591  7591 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:03:44.679   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7591
,09-06 19:03:44.679   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:03:44.679  7591  7591 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:03:44.679  7591  7591 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:44.679  7591  7591 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:03:44.679  7591  7591 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:03:44.679   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7591
09-06 19:03:44.679   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:03:44.699  1017  3321 D SSRM:n  : SIOP:: AP = 320,
,09-06 19:03:44.839   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-06 19:03:44.839  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 19:03:44.889  7591  7591 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:03:44.889  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:03:44.899  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-06 19:03:44.899   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7591
09-06 19:03:44.899   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:03:44.899  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:03:44.899  7591  7591 I wpa_supplicant: ssSupport state is = 1,
09-06 19:03:44.899  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:44.899  7591  7591 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:44.899  7591  7591 E wpa_supplicant: SIM READ ERROR
09-06 19:03:44.899  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:44.899  7591  7591 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:44.899  7591  7591 E wpa_supplicant: SIM READ ERROR
,09-06 19:03:44.899  7591  7591 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:03:44.899  7591  7591 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:03:44.899  7591  7591 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:03:44.899  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:44.899  7591  7591 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:03:44.899  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:44.899  7591  7591 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-06 19:03:44.909  7591  7591 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 19:03:44.909  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:03:44.909  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:44.909  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:44.959  7591  7591 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 19:03:45.069   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-06 19:03:45.969  7591  7591 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:03:45.969  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:03:45.979  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:03:45.979   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7591
09-06 19:03:45.979   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-06 19:03:45.979  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:03:45.979  7591  7591 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:45.979  7591  7591 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:03:45.989  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:03:45.999  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:03:45.999   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7591
09-06 19:03:45.999   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-06 19:03:45.999  7591  7591 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:03:45.999  7591  7591 I wpa_supplicant: ssSupport state is = 1
09-06 19:03:45.999  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:45.999  7591  7591 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:45.999  7591  7591 E wpa_supplicant: SIM READ ERROR
09-06 19:03:45.999  7591  7591 I wpa_supplicant: wpa_default_ap_write_once
,09-06 19:03:45.999  7591  7591 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-06 19:03:45.999  7591  7591 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:03:46.009  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:03:46.009  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:03:46.009  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:03:46.079  7591  7591 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:03:46.079  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:03:46.139  7591  7591 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:03:46.139  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:03:46.139  7591  7591 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:03:46.149  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:03:46.149  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 19:03:46.149  7591  7591 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:03:46.149  7591  7591 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:03:46.149  7591  7591 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:03:46.149  7591  7591 E wpa_supplicant: SIM READ ERROR
09-06 19:03:46.149  7591  7591 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:03:46.169  7591  7591 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:03:46.179  7591  7591 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-06 19:03:46.179  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:46.179  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:46.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:46.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:03:46.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:46.179  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:46.189  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:03:46.189  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:03:46.189  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:03:46.189  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:46.189  1171  1171 D HotspotTile: onReceive : 3, 0
,09-06 19:03:46.189  3859  3859 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:03:46.189  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:46.199  6743  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:46.199  6743  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:46.199  1017  1127 E WifiConfigStore: Not a HS20
,09-06 19:03:46.209  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:03:46.209  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65],
09-06 19:03:46.209  1017  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:46.209  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:46.209  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:46.209  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:46.209  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:46.209  1616  1616 I Hs20UtilService: Starting #20
09-06 19:03:46.209  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:03:46.209  7591  7591 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:03:46.209  7591  7591 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:03:46.209  1616  1643 I Hs20UtilService: Message received 5011
,09-06 19:03:46.219  7591  7591 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:03:46.219  7591  7591 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:03:46.219  7591  7591 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:03:46.219  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:03:46.219  7591  7591 I wpa_supplicant: First Scan Start
09-06 19:03:46.219  7591  7591 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:03:46.219  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:03:46.219  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:03:46.219  1017  1127 I WifiNative-HAL: startHal
09-06 19:03:46.219  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d52d88c
09-06 19:03:46.219  1017  1127 I WifiNative-HAL: Could not start hal
,09-06 19:03:46.229  6932  6932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:46.229  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:46.229  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:03:46.239  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:03:46.239   279  1003 D CommandListener: Setting iface cfg
09-06 19:03:46.239   279  1003 D CommandListener: Trying to bring up p2p0
,09-06 19:03:46.239  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:03:46.239  1017  1017 D RttService: SCAN_AVAILABLE : 3
,09-06 19:03:46.239  1017  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:03:46.239  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:03:46.239  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:03:46.239  1017  1127 E WifiNative-wlan0: invaild command id : 215
,09-06 19:03:46.239  1017  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:46.239  1017  1149 I WifiNative-HAL: startHal
09-06 19:03:46.239  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e8e79bc
09-06 19:03:46.239  1017  1149 I WifiNative-HAL: Could not start hal
09-06 19:03:46.239  1017  1149 E WifiScanningService: could not start HAL
,09-06 19:03:46.239  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:03:46.239  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:03:46.239  1017  1127 E WifiNative-wlan0: invaild command id : 215
09-06 19:03:46.239  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:03:46.239  7591  7591 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-06 19:03:46.239  7591  7591 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:03:46.249  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:03:46.249  6552  6552 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:03:46.249  7591  7591 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:03:46.249  1017  1127 E WifiStateMachine: Failed to set frequency band 0
09-06 19:03:46.249  1017  1126 D WifiP2pService: P2pEnablingState
09-06 19:03:46.249  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:03:46.249  1017  1126 D WifiP2pService: P2p socket connection successful
09-06 19:03:46.249  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:46.249  1017  1126 D WifiP2pService: P2pEnabledState
09-06 19:03:46.249  1017  1127 D SecContentProvider2: mCursor = null
09-06 19:03:46.249  6552  6552 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:03:46.249  6552  6552 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:03:46.249  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:03:46.249  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:46.249  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:46.249  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:46.249  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:03:46.249  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:46.249  1017  1047 D WifiDisplayController: disconnect
09-06 19:03:46.249  1017  1047 D WifiDisplayController: updateConnection
09-06 19:03:46.249  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:03:46.249  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:03:46.249  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:46.249  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:46.259  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:46.259  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress,
09-06 19:03:46.259  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-06 19:03:46.259  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:03:46.259  1017  1047 D WifiDisplayAdapter: onP2pDisconnected,
09-06 19:03:46.259  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:03:46.259  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:03:46.259  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:03:46.259  1017  1331 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:03:46.259  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:03:46.259  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:03:46.259  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:03:46.269  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@330f9831 Bundle[{}]
,09-06 19:03:46.269  6743  6796 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:03:46.269  6743  6796 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:03:46.269  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:03:46.269  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:03:46.269  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:03:46.269  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 19:03:46.269  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  secondary type: null
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  wps: 0
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  grpcapab: 0
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  devcapab: 0
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  status: 3
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  wfdInfo: null
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-06 19:03:46.269  1017  1047 D WifiDisplayController:  SConnectInfo : null
09-06 19:03:46.269  6743  6796 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:03:46.279  6743  6796 I System.out: Running OutgoingSocketThread
,09-06 19:03:46.279  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:03:46.279  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:03:46.279  6743  7599 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1344)
,09-06 19:03:46.279  6743  7599 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35545
,09-06 19:03:46.279  6743  7599 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:03:46.279  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:46.279  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:46.279  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:46.279  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:46.289  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:46.289  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:03:46.289  1017  1126 D WifiP2pService: InactiveState
,09-06 19:03:46.289  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:03:46.289  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:03:46.289  7591  7591 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-06 19:03:46.289  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:03:46.289  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:03:46.299  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:46.299  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:03:46.299  6977  6977 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:03:46.299  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:03:47.069   289   289 E SMD     : DCD OFF
,09-06 19:03:47.279  6743  6796 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1345)
,09-06 19:03:47.279  6743  6796 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1345)
,09-06 19:03:47.279  6743  6796 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1350)
,09-06 19:03:47.279  6743  6796 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:03:47.279  6743  6796 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,09-06 19:03:47.289  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:47.289  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0c4313 added. We now have 2 listener(s)
,09-06 19:03:47.289  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
,09-06 19:03:47.289  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.289  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.289  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 19:03:47.289  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a8950 added. We now have 9 listener(s)
,09-06 19:03:47.289  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:47.289  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:47.299  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.299  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.299  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:47.299  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:47.299  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2838884e added. We now have 3 listener(s)
,09-06 19:03:47.309  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13edfd6f added. We now have 10 listener(s)
09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.309  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:47.309  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:47.309  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.309  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0c4313 removed from the list
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a8950 removed from the list
09-06 19:03:47.309  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.309  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.309  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a8950 not in the list
09-06 19:03:47.309  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13edfd6f removed from the list
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.309  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.309  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.309  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:03:47.309  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2838884e removed from the list
09-06 19:03:47.319  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.319  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3266ea7c added. We now have 2 listener(s)
,09-06 19:03:47.319  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:03:47.319  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.319  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.319  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.319  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292bcf05 added. We now have 9 listener(s)
09-06 19:03:47.319  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.319  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:47.319  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.329  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.329  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:47.329  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:47.329  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.329  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c87018b added. We now have 3 listener(s)
,09-06 19:03:47.329  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.329  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:03:47.329  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:47.329  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.329  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.329  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.329  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4763268 added. We now have 10 listener(s)
09-06 19:03:47.329  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.329  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:47.329  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:47.329  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:47.329  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:47.329  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:47.339  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:47.339  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:47.339  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:47.349  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:47.349  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:47.349  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:47.349  7491  7499 D BtGatt.GattService: registerClient() - UUID=fad77b79-c829-408a-9c97-467b13825015
,09-06 19:03:47.389  7491  7509 D BtGatt.GattService: onClientRegistered() - UUID=fad77b79-c829-408a-9c97-467b13825015, clientIf=6
,09-06 19:03:47.389  6743  6752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:03:47.399  7491  7510 D BtGatt.GattService: start scan with filters
,09-06 19:03:47.399  7491  7515 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:47.399  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:47.399  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:03:47.399  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:03:47.399  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:47.399  7491  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ce2dcb
,09-06 19:03:47.409  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:47.409  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:47.409  7491  7509 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:03:47.409  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.409  7491  7515 D BtGatt.ScanManager: allow scan with filters
,09-06 19:03:47.409  7491  7515 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:03:47.409  7491  7515 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:03:47.419  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:47.419  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:03:47.419  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.419  7491  7515 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:03:47.419  7491  7515 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:03:47.419  7491  7509 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:03:47.429  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.429  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:47.429  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:03:47.429  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.429  6743  6796 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:47.429  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:47.429  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:47.429  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.429  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:47.429  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:47.429  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:47.429  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:47.429  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:47.429  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:47.429  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:47.429  7491  7499 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:47.439  7491  7510 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:47.439  7491  7515 D BtGatt.ScanManager: filter size is 1
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:03:47.439  7491  7515 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:47.439  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:47.439  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:47.439  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.439  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.439  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3266ea7c removed from the list
09-06 19:03:47.439  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.439  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292bcf05 removed from the list
09-06 19:03:47.439  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.439  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.439  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.449  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:47.449  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:47.449  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:47.449  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:03:47.449  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.449  7491  7515 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.459  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292bcf05 not in the list
09-06 19:03:47.459  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4763268 removed from the list
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.459  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.459  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c87018b removed from the list
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b00d14 added. We now have 2 listener(s)
,09-06 19:03:47.459  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:03:47.459  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:47.459  7491  7515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:03:47.459  7491  7509 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:03:47.459  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.459  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769d9bd added. We now have 9 listener(s)
09-06 19:03:47.459  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.469  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:47.469  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.469  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.469  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:47.479  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:47.479  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.479  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc1703 added. We now have 3 listener(s)
,09-06 19:03:47.479  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:47.479  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:47.479  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.479  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.479  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320ae680 added. We now have 10 listener(s)
09-06 19:03:47.479  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.479  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:47.479  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:47.479  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:47.479  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:47.479  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:47.479  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:47.479  7591  7591 I wpa_supplicant: nl80211: Received scan results (32 BSSes)
,09-06 19:03:47.479  7591  7591 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:03:47.479  7591  7591 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:03:47.479  7591  7591 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:03:47.479  7591  7591 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:03:47.479  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 19:03:47.489  1017  7597 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:03:47.489  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:47.489  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:47.499  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:47.499  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:47.499  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:47.499  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:47.499  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:47.499  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:47.499  7491  7503 D BtGatt.GattService: registerClient() - UUID=20e2a020-c91c-44a5-9687-90c87205e25e
,09-06 19:03:47.509  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.509  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:03:47.509  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:03:47.509  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:03:47.509  1017  1030 D BatteryService: stay LED for fully charged
,09-06 19:03:47.509  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:03:47.509  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.519  1017  1017 I MotionRecognitionService: Plugged
,09-06 19:03:47.519  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:03:47.519  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:03:47.519  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:03:47.529  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:03:47.529  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:03:47.539  7491  7491 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:03:47.539  7491  7516 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:03:47.549  7491  7509 D BtGatt.GattService: onClientRegistered() - UUID=20e2a020-c91c-44a5-9687-90c87205e25e, clientIf=6
,09-06 19:03:47.549  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:03:47.549  7491  7499 D BtGatt.GattService: start scan with filters
,09-06 19:03:47.549  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:03:47.549  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:47.549  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:47.549  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:47.549  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:47.549  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:03:47.549  7491  7509 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:03:47.549  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:03:47.549  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: allow scan with filters
09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:03:47.549  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:03:47.549  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:47.549  7491  7515 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:03:47.549  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:47.559  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:47.559  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:47.559  7491  7509 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:03:47.559  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.559  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:03:47.559  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-06 19:03:47.559  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:47.569  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:03:47.569  6743  6796 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-06 19:03:47.569  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:47.569  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:47.569  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:47.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:47.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:47.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.569  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b00d14 removed from the list
,09-06 19:03:47.569  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.569  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769d9bd removed from the list
,09-06 19:03:47.569  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:47.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:47.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:47.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:03:47.569  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:47.569  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:47.579  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769d9bd not in the list
09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:03:47.579  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:47.579  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:47.579  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:47.579  7491  7499 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:47.579  7491  7515 D BtGatt.ScanManager: filter size is 1
09-06 19:03:47.579  7491  7515 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:03:47.579  7491  7510 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:03:47.579  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:03:47.579  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.579  7491  7515 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:47.589  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:03:47.589  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:47.589  7491  7515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.589  7491  7509 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:03:47.589  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.589  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:47.589  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:47.589  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.589  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320ae680 removed from the list
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.589  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.589  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.589  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.589  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc1703 removed from the list
,09-06 19:03:47.589  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.589  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3877eaac added. We now have 2 listener(s)
,09-06 19:03:47.599  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:47.599  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.599  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.599  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:47.599  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1978375 added. We now have 9 listener(s)
09-06 19:03:47.599  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.599  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:47.599  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:47.599  7591  7591 E wpa_supplicant: Cmd 35605 not handled
09-06 19:03:47.599  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.599  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.599  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:47.599  7591  7591 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-06 19:03:47.609  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:03:47.609  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.609  7591  7591 I wpa_supplicant: Associated with F4.99.3E
09-06 19:03:47.609  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.609  7591  7591 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:03:47.609  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.609  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:03:47.609  7591  7591 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:03:47.609  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:47.609  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:03:47.609  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.609  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.609  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true,
,09-06 19:03:47.609  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-06 19:03:47.609  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:03:47.609  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:47.609  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:47.609  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.609  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1f637b added. We now have 3 listener(s)
,09-06 19:03:47.609  1017  1130 E Tethering: No numeric data
09-06 19:03:47.609  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:47.609  7591  7591 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:03:47.609  7591  7591 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:03:47.609  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:03:47.609  1017  1130 D Tethering: clearTetheredNotification()
,09-06 19:03:47.619  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:47.619  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:47.619  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:03:47.619  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:47.619  7591  7591 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:03:47.619  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:47.619  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:03:47.619  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:47.619  7591  7591 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:03:47.619  7591  7591 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:03:47.619  7591  7591 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:03:47.619  7591  7591 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:03:47.619  7591  7591 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:03:47.619  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:03:47.619  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.619  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.619  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:03:47.619  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.619  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:03:47.619  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bcf0598 added. We now have 10 listener(s)
09-06 19:03:47.619  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.619  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:47.619  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:47.619  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:47.619  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:47.619  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:47.619  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:47.619  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:03:47.619  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:03:47.619  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:03:47.629  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:47.629  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:47.629  1017  1124 V NetworkStats: performPollLocked() took 10ms
09-06 19:03:47.629  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:47.629  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:47.629  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:03:47.629  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:47.639  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50],
09-06 19:03:47.639  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:47.639  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:03:47.639  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:03:47.639  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:03:47.639  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:03:47.639  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:47.639  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:03:47.649  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:47.649  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:47.649  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.649  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.649  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.649  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:47.649  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:47.649  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:47.649  6743  6796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:47.649  7491  7510 D BtGatt.GattService: registerClient() - UUID=87f1fd9d-8599-41c9-80b4-60dbc4ba2cd9
,09-06 19:03:47.649  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:47.649  1017  1331 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:03:47.649  1017  1331 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:47.649  1017  1331 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:47.649  1017  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:03:47.649  1017  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:47.649  1616  1616 I Hs20UtilService: Starting #21,
,09-06 19:03:47.649  1616  1643 I Hs20UtilService: Message received 5007,
,09-06 19:03:47.659  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:03:47.659  3859  3859 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:03:47.659  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:03:47.659  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:03:47.659  3859  3859 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:03:47.659  3859  3859 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:03:47.659  3859  3932 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:03:47.669  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:47.679   279  1003 D CommandListener: Setting iface cfg,
,09-06 19:03:47.679  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,09-06 19:03:47.679  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:47.679  1017  1127 D SecContentProvider2: mCursor = null
,09-06 19:03:47.689  7491  7509 D BtGatt.GattService: onClientRegistered() - UUID=87f1fd9d-8599-41c9-80b4-60dbc4ba2cd9, clientIf=6
,09-06 19:03:47.689  6743  6751 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:03:47.689  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:47.689  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:47.689  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.689  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.689  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.689  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:47.689  7491  7511 D BtGatt.GattService: start scan with filters
,09-06 19:03:47.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-06 19:03:47.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:47.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:47.699  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:47.699  7491  7515 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:47.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:47.699  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:47.699  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:47.699  7491  7509 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:03:47.699  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:47.709  7491  7515 D BtGatt.ScanManager: allow scan with filters
09-06 19:03:47.709  7491  7515 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:03:47.709  7491  7515 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-06 19:03:47.709  1017  1127 E WifiNative-wlan0: do suspend false
09-06 19:03:47.709  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:03:47.709  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:03:47.709  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.709  7491  7515 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:47.709  7491  7515 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:03:47.709  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:03:47.709  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:03:47.709  1017  1127 D SecContentProvider2: mCursor = null
09-06 19:03:47.709  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:03:47.719  7491  7509 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:03:47.719  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.719  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:03:47.719  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.729  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:47.729  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:47.729  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.729  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.729  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3877eaac removed from the list
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.729  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1978375 removed from the list
09-06 19:03:47.729  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:47.729  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:03:47.729  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.729  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1978375 not in the list
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:47.729  7491  7511 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:03:47.729  7491  7499 D BtGatt.GattService: unregisterClient() - clientIf=6
09-06 19:03:47.729  7491  7515 D BtGatt.ScanManager: filter size is 1
09-06 19:03:47.729  7491  7515 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:03:47.729  7491  7509 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:03:47.729  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:03:47.729  7491  7515 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:47.729  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:47.729  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.739  7491  7509 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:03:47.739  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.739  7491  7515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bcf0598 removed from the list
09-06 19:03:47.739  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.739  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1f637b removed from the list
09-06 19:03:47.739  6743  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:47.739  6743  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@347ae344 added. We now have 2 listener(s)
09-06 19:03:47.739  7491  7509 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:03:47.739  7491  7509 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:03:47.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:03:47.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:47.739  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1429ac2d added. We now have 9 listener(s)
09-06 19:03:47.739  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:47.739  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.749  6743  6796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.749  6743  6796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:47.749  6743  6796 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:47.749  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.749  6743  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.749  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:47.749  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3900c6f3 added. We now have 3 listener(s)
,09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e4efb0 added. We now have 10 listener(s)
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:47.759  6743  6796 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:47.759  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@347ae344 removed from the list
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1429ac2d removed from the list
09-06 19:03:47.759  6743  6796 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.759  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.759  6743  6796 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1429ac2d not in the list
09-06 19:03:47.759  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e4efb0 removed from the list
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:47.759  6743  6796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:47.759  6743  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:47.759  6743  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:47.759  6743  6796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3900c6f3 removed from the list
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:03:47.759  6743  6796 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:47.769  6743  7607 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1358, name: My test thread name),
09-06 19:03:47.769  6743  7607 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1358, thread name: My test thread name)
09-06 19:03:47.769  6743  7607 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1358, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:03:47.769  6743  7608 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1360, name: My test thread name)
,09-06 19:03:47.769  6743  7608 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1360, thread name: My test thread name)
09-06 19:03:47.769  6743  7608 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1360, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:03:47.769  6743  6796 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:03:47.769  6743  6796 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:03:47.769  6743  6796 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:03:47.769  6743  6796 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:03:47.769  6743  6796 D com.test.thalitest.ThaliTestRunner: Total duration: 24240 ms
,09-06 19:03:47.769  6743  6796 I jxcore-log: *Native tests were executed*,
09-06 19:03:47.769  6743  6796 I jxcore-log: 
09-06 19:03:47.769  6743  6796 I jxcore-log: Total number of executed tests:  80
09-06 19:03:47.769  6743  6796 I jxcore-log: 
09-06 19:03:47.769  6743  6796 I jxcore-log: Number of passed tests:  80
09-06 19:03:47.769  6743  6796 I jxcore-log: 
,09-06 19:03:47.769  6743  6796 I jxcore-log: Number of failed tests:  0
09-06 19:03:47.769  6743  6796 I jxcore-log: 
09-06 19:03:47.769  6743  6796 I jxcore-log: Number of ignored tests:  0
09-06 19:03:47.769  6743  6796 I jxcore-log: 
,09-06 19:03:47.779  6743  6796 I jxcore-log: Total duration:  24240
09-06 19:03:47.779  6743  6796 I jxcore-log: 
09-06 19:03:47.779  6743  6796 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:03:47.779  6743  6796 I jxcore-log: 
,09-06 19:03:47.779  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.779  6743  6796 I jxcore-log: 
09-06 19:03:47.779  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.779  6743  6796 I jxcore-log: 
09-06 19:03:47.779  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.779  6743  6796 I jxcore-log: 
09-06 19:03:47.779  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.779  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6743 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
,09-06 19:03:47.789  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.789  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
,09-06 19:03:47.799  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.799  6743  6796 I jxcore-log: 
09-06 19:03:47.809  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:47.809  6743  6796 I jxcore-log: 
,09-06 19:03:47.929  7611  7611 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:03:47.929  7611  7611 I dhcpcd  : version 5.5.6 starting,
,09-06 19:03:47.939  7611  7611 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:03:47.949  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:03:47.949  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:47.949  6743  6796 I jxcore-log: 
,09-06 19:03:47.979  7611  7611 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:03:47.979  7611  7611 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:03:47.979  7611  7611 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 19:03:47.979  7611  7611 I dhcpcd  : bssid match
09-06 19:03:47.979  7611  7611 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-06 19:03:48.039  7611  7611 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,09-06 19:03:48.059  7609  7609 D AndroidRuntime: ,
09-06 19:03:48.059  7609  7609 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:03:48.059  7609  7609 D AndroidRuntime: CheckJNI is OFF,
09-06 19:03:48.059  7609  7609 D AndroidRuntime: readGMSProperty: start
09-06 19:03:48.059  7609  7609 D AndroidRuntime: readGMSProperty: already setted!!,
09-06 19:03:48.059  7609  7609 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:03:48.059  7609  7609 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:03:48.059  7609  7609 D AndroidRuntime: readGMSProperty: end
09-06 19:03:48.059  7609  7609 D AndroidRuntime: addProductProperty: start
,09-06 19:03:48.089  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:03:48.089  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:48.089  6743  6796 I jxcore-log: 
,09-06 19:03:48.119  7611  7611 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-06 19:03:48.189  7609  7609 E AffinityControl: AffinityControl: registerfunction enter,
,09-06 19:03:48.219  7609  7609 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-06 19:03:48.239  6743  6743 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:03:48.239  6743  6796 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:48.239  6743  6796 I jxcore-log: 
,09-06 19:03:48.239  1017  4234 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-06 19:03:48.239  1017  4234 D PackageManager: START PACKAGE DELETE: observer{506055908}
,09-06 19:03:48.239  1017  4234 D PackageManager: pkg{<packageName>}
09-06 19:03:48.239  1017  4234 D PackageManager: user{0}
09-06 19:03:48.239  1017  4234 D PackageManager: caller{2000}
09-06 19:03:48.239  1017  4234 D PackageManager: flags{2}
09-06 19:03:48.239  1017  4234 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-06 19:03:48.239  1017  4234 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-06 19:03:48.239  1017  4234 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:03:48.239  1017  4234 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 19:03:48.249  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-06 19:03:48.249  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 19:03:48.249  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 19:03:48.249  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-06 19:03:48.249  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:03:48.249  1017  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-06 19:03:48.259  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
09-06 19:03:48.259  1017  1042 I ActivityManager: Killing 6743:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:03:48.269  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{1b2d15ec u0 com.test.thalitest/.MainActivity t2}
,09-06 19:03:48.279  1017  1042 D InputDispatcher: Focus left window: 6743
09-06 19:03:48.279   259   448 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
09-06 19:03:48.279   259   444 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-06 19:03:48.309  1017  1042 D InputDispatcher: Focused application released
,09-06 19:03:48.309  1017  1042 D FocusedStackFrame: Set to : 0
,09-06 19:03:48.309  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:03:48.309  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:03:48.309  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:03:48.319  1017  1127 E WifiNative-wlan0: do suspend true
,09-06 19:03:48.349  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
09-06 19:03:48.349  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:03:48.369  1017  1057 W PackageSettings: Skipping PackageSetting{11ca74d1 com.example.hello/10168} due to missing metadata
,09-06 19:03:48.389  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,09-06 19:03:48.399  1017  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:03:48.399  1017  1127 E WifiStateMachine: VerifyingLinkState enter
,09-06 19:03:48.399  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:48.409  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-06 19:03:48.409  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:48.409  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:48.409  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.409  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.409  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.409  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.409  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-06 19:03:48.409  1017  1129 D ConnectivityService: Adding iface wlan0 to network 504
,09-06 19:03:48.419  1017  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-06 19:03:48.419  1017  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:03:48.419  1017  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:03:48.419  1017  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-06 19:03:48.419  1017  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:03:48.419  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:48.419  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:48.419  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.419  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.419  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:03:48.419  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.419  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-06 19:03:48.429  1017  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
,09-06 19:03:48.429  1017  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-06 19:03:48.429  1017  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-06 19:03:48.429  1017  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:03:48.429  1017  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-06 19:03:48.429  1017  1129 D ConnectivityService: LTETest block dns file not exists
,09-06 19:03:48.439  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:03:48.439  1496  1496 D Launcher: onRestart, Launcher: 9427879
,09-06 19:03:48.449  1017  3357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:03:48.449  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:03:48.449  1017  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-06 19:03:48.459  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:48.459  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:48.459  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:03:48.499  1616  1616 I Hs20UtilService: Starting #22
,09-06 19:03:48.499  1616  1643 I Hs20UtilService: Message received 5007
,09-06 19:03:48.499  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:03:48.499  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 19:03:48.499  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-06 19:03:48.509  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 19:03:48.509  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 19:03:48.509  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-06 19:03:48.519  1868  1868 E SamsungIME: mOCRHelper is null
,09-06 19:03:48.519  2002  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:03:48.529  1496  1496 D Launcher: onStart, Launcher: 9427879
09-06 19:03:48.529  1496  1496 D Launcher.HomeView: onStart
,09-06 19:03:48.529  1496  1496 D Launcher: onResume, Launcher: 9427879
,09-06 19:03:48.529  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:03:48.529  1017  4970 D SettingsProvider: name = kids_home_mode
09-06 19:03:48.529  1017  4970 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:03:48.529  1017  4970 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:03:48.529  1017  4970 D SettingsProvider: selectionArgs: false
09-06 19:03:48.529  1017  4970 D SettingsProvider: selectionArgs: 10006
09-06 19:03:48.529  1017  4970 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:03:48.529  1017  4970 D SettingsProvider: ret = -1
,09-06 19:03:48.539  1496  1496 D Launcher.HomeView: onResume
,09-06 19:03:48.539  2633  2633 I art     : Explicit concurrent mark sweep GC freed 19545(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.133ms total 83.620ms
,09-06 19:03:48.549  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 19:03:48.549  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:03:48.549  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:48.549  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:03:48.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.549  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.559  3859  3859 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:03:48.559  3859  3859 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:03:48.569  1017  1129 V NetworkStats: updateIfacesLocked()
,09-06 19:03:48.569  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:03:48.579  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.579  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:48.579  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:48.579  4799  4799 I art     : Explicit concurrent mark sweep GC freed 22587(1369KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.282ms total 144.644ms
,09-06 19:03:48.589  1496  1496 D MenuAppsGridFragment: onResume
,09-06 19:03:48.589  1017  1129 V NetworkStats: performPollLocked() took 16ms
09-06 19:03:48.589  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.589  1496  1496 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:03:48.589  1496  1496 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:03:48.609  1450  1450 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:03:48.609  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 19:03:48.609  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-06 19:03:48.609  1017  1041 W TextServicesManagerService: no available spell checker services found
,09-06 19:03:48.619  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:48.619  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:03:48.619  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.619  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.619  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.619  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.629  1450  1450 D RegisteredServicesCache: empty dynamic service
09-06 19:03:48.629  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-06 19:03:48.629  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:48.629  1017  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:03:48.629  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:03:48.629  1017  1129 V NetworkStats: updateIfacesLocked()
09-06 19:03:48.629  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:03:48.629  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.629  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:03:48.629  1017  1492 D ActivityManager: handle home activity for 0
09-06 19:03:48.629  1017  1492 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-06 19:03:48.629  1017  1492 D KnoxTimeoutHandler: post home show event for user 0
09-06 19:03:48.629  1017  1492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:03:48.629  1017  1492 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:03:48.629  1017  1492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:03:48.629  1496  1496 D Launcher.HomeView: onPause
09-06 19:03:48.629  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:48.629  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.629  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 19:03:48.629  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.629  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.649  1017  1129 V NetworkStats: performPollLocked() took 19ms
,09-06 19:03:48.649  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.659  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.659  1017  7228 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:03:48.659  1017  7228 D SecContentProvider2: mCursor = null
,09-06 19:03:48.659  1017  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-06 19:03:48.659  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-06 19:03:48.659  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:48.659  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:03:48.659  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:03:48.659  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 19:03:48.659  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-06 19:03:48.659  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.659  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,09-06 19:03:48.669  1017  1129 D ConnectivityService:    accepting network in place of null
09-06 19:03:48.669  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:48.669  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:03:48.669  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-06 19:03:48.669  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:03:48.669  1464  1464 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:03:48.669  1464  1464 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:03:48.669  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.669  1017  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:03:48.669  1017  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-06 19:03:48.669  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:03:48.669  1017  1124 V NetworkStats: performPollLocked() took 6ms
09-06 19:03:48.669  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.669  1017  7602 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:03:48.669   279   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:03:48.669   279   999 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-06 19:03:48.669  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.679  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.679  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.679  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:03:48 GMT+02:00 2016
,09-06 19:03:48.689  1017  3357 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:03:48.689  1017  3357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-06 19:03:48.689   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-06 19:03:48.699  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:03:48.699  1017  3357 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:48.699  1017  3357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:48.699  1017  3357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:03:48.699  1450  1450 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:03:48.699  1017  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-06 19:03:48.699  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:03:48.709  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-06 19:03:48.709  1017  1511 D InputDispatcher: Focus entered window: 1496
09-06 19:03:48.709  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:03:48.709  1171  1710 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:03:48.709  4799  6805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:03:48.709  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.709  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.709  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:03:48.719  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:03:48.719  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:03:48.719  1496  1496 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:03:48.719  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:03:48.719  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:03:48.719  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:03:48.719  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-06 19:03:48.719  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:03:48.719  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:03:48.719  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.719  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.729  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.729  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:03:48.729  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 19:03:48.729  2912  2912 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:03:48.729  1017  4235 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-06 19:03:48.729  1017  4235 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-06 19:03:48.729  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-06 19:03:48.729  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 19:03:48.729  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-06 19:03:48.729  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:03:48.729  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 19:03:48.739  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.739  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.739  2912  2912 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-06 19:03:48.739  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.739  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.739  1017  4235 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:03:48.739  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:48.739  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.739  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.739  1017  4235 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:48.749  2912  2912 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:03:48.749  1017  7602 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:03:48.749  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:03:48.749  1017  1124 V NetworkStats: updateIfacesLocked()
09-06 19:03:48.749  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.749  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:03:48.749  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:03:48.749  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:03:48.749  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{11c6850 token=android.os.BinderProxy@23e77efb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-06 19:03:48.749  1496  1496 D Launcher.HomeView: onStop
,09-06 19:03:48.759  1017  1124 V NetworkStats: performPollLocked() took 6ms
,09-06 19:03:48.759  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.759  7655  7655 E Zygote  : MountEmulatedStorage(),
09-06 19:03:48.759  7655  7655 E Zygote  : v2
09-06 19:03:48.759  7655  7655 I libpersona: KNOX_SDCARD checking this for 10090
09-06 19:03:48.759  7655  7655 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:48.769  1017  1486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,09-06 19:03:48.769  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-06 19:03:48.769  1017  4235 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7655 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-06 19:03:48.769  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START,
,09-06 19:03:48.769  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-06 19:03:48.769  7655  7655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:48.779  1017  1486 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6743 uid 10171
09-06 19:03:48.779  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-06 19:03:48.779  7655  7655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:03:48.779  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.779  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:03:48.779  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.779  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:48.779  7655  7655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:03:48.789  1017  7661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:03:48.799  1017  1331 I TactileAssist: enable value -1
09-06 19:03:48.799  1017  1331 I TactileAssist: internal enable value -1
09-06 19:03:48.799  1017  1331 I TactileAssist: intensity value -1
09-06 19:03:48.799  1017  1331 I TactileAssist: saveAppList value true
,09-06 19:03:48.799  7672  7672 E Zygote  : MountEmulatedStorage()
09-06 19:03:48.799  7672  7672 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:03:48.799  7672  7672 E Zygote  : v2
09-06 19:03:48.799  7672  7672 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:48.799  7672  7672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:48.799  1868  1868 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-06 19:03:48.809  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7672 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-06 19:03:48.809  1017  1331 I TactileAssist: List of disabled apps :
09-06 19:03:48.809  1017  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
09-06 19:03:48.809  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:03:48 GMT], X-Android-Received-Millis=[1473181428828], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181428796]}
09-06 19:03:48.809  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 19:03:48.809  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 19:03:48.809  1017  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-06 19:03:48.809  1017  7602 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 19:03:48.809  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-06 19:03:48.809  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-06 19:03:48.819  1171  1710 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:03:48.819  7672  7672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:48.819  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:03:48.819  4799  6805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:03:48.819  7672  7672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:48.819  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.819  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.819  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:48.819  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:48.839  7655  7655 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:03:48.839  7655  7655 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:03:48.849  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:03:48.849  1017  1042 W ActivityManager: mDVFSHelper.release()
09-06 19:03:48.849  7682  7682 E Zygote  : MountEmulatedStorage()
09-06 19:03:48.849  7682  7682 E Zygote  : v2
09-06 19:03:48.849  7682  7682 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:03:48.849  7682  7682 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:48.849  7682  7682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:48.849  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 19:03:48.849  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:03:48.849  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 19:03:48.849  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.859  7682  7682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:48.859  7682  7682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicy: uID is 10171
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-06 19:03:48.879  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-06 19:03:48.879  1017  1143 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.internal.util.StateMachine$SmHandler) {13762fed}
09-06 19:03:48.879  1450  1450 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:03:48.879  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:03:48.889  7682  7682 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:03:48.889  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
09-06 19:03:48.889  7682  7682 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:48.889  7672  7672 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:48.889  7672  7672 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:48.889  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-06 19:03:48.899  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:03:48.899  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:03:48.899  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:03:48.929  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:03:48.929  2912  7653 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 19:03:48.929  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-06 19:03:48.929  2912  7653 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-06 19:03:48.939  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:03:48.939  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:03:48.939  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.939  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.939  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:03:48.939  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:03:48.959  2912  2912 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:03:48.959  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 19:03:48.959  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:03:48.959  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:03:48.959  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:03:48.959  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 19:03:48.959  1017  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-06 19:03:48.959  1017  1017 V EnterpriseBillingPolicy: uID is 10171
09-06 19:03:48.959  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:03:48.959  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:03:48.969  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:48.969  1017  3321 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-06 19:03:48.969  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:03:48.969  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:03:48.969  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:03:48.969  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:03:48.969  1017  1029 I ActivityManager: Killing 7056:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-06 19:03:48.969  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:03:48.969  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:03:48.969  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:03:48.969  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 19:03:48.969  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,09-06 19:03:48.969  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-06 19:03:48.969  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-06 19:03:48.969  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:03:48.969  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:03:48.969  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-06 19:03:48.979  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:03:48.979  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39dbfb6e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147871
,09-06 19:03:48.979  1171  1171 I StatusBar: Icon Only
,09-06 19:03:48.979  1171  1171 D PanelView: There is/are notification(s) 
,09-06 19:03:48.999  7672  7672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-06 19:03:49.009  1017  1511 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-06 19:03:49.009  1017  1511 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-06 19:03:49.009  1017  1511 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:49.009  1017  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:49.009  1017  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-06 19:03:49.009  7655  7655 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-06 19:03:49.009  1017  7228 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-06 19:03:49.009  7655  7655 D elm:15121: ELMEngine.ELMEngine( context ).
,09-06 19:03:49.009  7655  7655 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-06 19:03:49.019  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.019  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.019  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.019  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.039  7704  7704 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.039  7704  7704 E Zygote  : v2
09-06 19:03:49.039  7704  7704 I libpersona: KNOX_SDCARD checking this for 10048
09-06 19:03:49.039  7704  7704 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.039  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.039  7704  7704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.039  1017  1057 I art     : Explicit concurrent mark sweep GC freed 84672(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 25MB/37MB, paused 19.125ms total 398.470ms
,09-06 19:03:49.039  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.039  1017  7228 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7704 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-06 19:03:49.039  7704  7704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:49.039  7704  7704 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-06 19:03:49.049  7682  7682 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-06 19:03:49.049  1017  7228 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-06 19:03:49.049  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.049  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.049  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.049  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.059  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.059  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:03:49.059  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.059  7717  7717 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.059  7717  7717 E Zygote  : v2
,09-06 19:03:49.059  7717  7717 I libpersona: KNOX_SDCARD checking this for 1000,
,09-06 19:03:49.059  7717  7717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:49.059  7717  7717 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:49.069  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.069  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
09-06 19:03:49.069  1017  7228 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:03:49.069  7717  7717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:49.069  7717  7717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:03:49.069  1017  1057 D PackageManager: delete codoeFile: 
,09-06 19:03:49.079  7704  7704 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.079  1017  4234 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-06 19:03:49.079  1017  4234 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-06 19:03:49.079  7704  7704 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.079  1017  4234 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:49.079  1017  4234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:49.079  1017  4234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-06 19:03:49.089  7655  7655 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-06 19:03:49.089  1017  1029 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:03:49.089  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-06 19:03:49.089  1017  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-06 19:03:49.089  7655  7655 D elm:15121: ElmAgentService : onCreate()
09-06 19:03:49.089  1017  4234 D SecContentProvider2: uri = -1 selection = getSealedState
09-06 19:03:49.089  1017  4234 D SecContentProvider2: mCursor = null
,09-06 19:03:49.099  7682  7682 I PopupuiReceiver_KNOX: getSealedState : true
,09-06 19:03:49.099  7655  7728 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-06 19:03:49.099  7655  7728 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-06 19:03:49.099  7655  7728 D elm:15121: MDMBridge.getInstance()
09-06 19:03:49.099  7655  7728 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-06 19:03:49.099  1017  1057 D PackageManager: result of delete: 1{506055908}
,09-06 19:03:49.099  1017  1216 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
,09-06 19:03:49.099  1017  1216 D SecContentProvider2: mCursor = null
,09-06 19:03:49.099  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:03:49.099  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:03:49.099  7682  7682 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,09-06 19:03:49.109  1017  1463 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-06 19:03:49.109  1017  1463 D SecContentProvider2: mCursor = null
,09-06 19:03:49.109  7682  7682 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,09-06 19:03:49.109  7655  7728 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-06 19:03:49.109  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:03:49.109  7682  7682 D PopupuiReceiver: Action package removed
,09-06 19:03:49.109  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:03:49.109  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.109  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.109  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.109  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.119  7717  7717 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.119  7717  7717 D ActivityThread: Added TimaKeyStore provider,
09-06 19:03:49.119  7609  7609 D AndroidRuntime: Shutting down VM
,09-06 19:03:49.129  7735  7735 E Zygote  : MountEmulatedStorage()
,09-06 19:03:49.129  7735  7735 E Zygote  : v2
09-06 19:03:49.129  7735  7735 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:03:49.129  7735  7735 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:49.129  7735  7735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:03:49.129  7735  7735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:49.129  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7735 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:03:49.129  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-06 19:03:49.129  7735  7735 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.139  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-06 19:03:49.139  1017  7228 I ActivityManager: Killing 7071:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 19:03:49.139  1017  7228 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-06 19:03:49.139  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.139  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.139  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.139  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.149  7704  7704 D Compatibility: onReceive() it will make start service
,09-06 19:03:49.159   305   305 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 22.828ms
,09-06 19:03:49.159  7735  7735 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.159  7735  7735 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.159  7717  7717 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:03:49.169   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.527ms
,09-06 19:03:49.179  7717  7717 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-06 19:03:49.189   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.460ms
,09-06 19:03:49.199  1017  1486 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-06 19:03:49.199  1017  1486 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-06 19:03:49.199  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:49.209  7751  7751 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.209  7751  7751 E Zygote  : v2
09-06 19:03:49.209  7751  7751 I libpersona: KNOX_SDCARD checking this for 10145
09-06 19:03:49.209  7751  7751 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.209  7751  7751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.209  1017  1148 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,09-06 19:03:49.209  7751  7751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:49.209  7751  7751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.209  1017  7228 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7751 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:03:49.209  1017  7228 I ActivityManager: Killing 7102:com.sec.spp.push/u0a32 (adj 15): empty #21
09-06 19:03:49.219  1017  1492 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,09-06 19:03:49.219  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-06 19:03:49.219  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:49.219  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:03:49.219  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-06 19:03:49.229  7704  7762 D Compatibility: onHandleIntent()
,09-06 19:03:49.229  1017  7228 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-06 19:03:49.229  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.229  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.229  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.229  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.229  7704  7762 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
09-06 19:03:49.229  7751  7751 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.239  7751  7751 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.239  7704  7762 D Compatibility: found: 2
,09-06 19:03:49.249  7768  7768 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.249  7768  7768 I libpersona: KNOX_SDCARD checking this for 10087
09-06 19:03:49.249  7768  7768 E Zygote  : v2
09-06 19:03:49.249  7768  7768 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.249  7768  7768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.249  7768  7768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:49.249  1017  7228 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7768 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,09-06 19:03:49.249  7768  7768 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:03:49.249  1017  7228 I ActivityManager: Killing 7135:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:03:49.269  7704  7762 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-06 19:03:49.269  7704  7762 D Compatibility: skipping ResolveInfo{2c86e98e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-06 19:03:49.269  7704  7762 D Compatibility: considering ResolveInfo{26ee5af com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-06 19:03:49.269  7704  7762 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-06 19:03:49.269  7704  7762 D Compatibility: enabling receiver ResolveInfo{278d4dbc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-06 19:03:49.279  7655  7655 D elm:15121: ElmAgentService : onDestroy().
,09-06 19:03:49.279  7735  7735 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:03:49.279  7735  7735 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:03:49.279  7735  7735 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:03:49.279  1017  7228 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-06 19:03:49.279  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.279  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.289  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.289  1017  7228 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.289  7768  7768 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.289  7768  7768 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.289  7704  7762 D Compatibility: enabling receiver ResolveInfo{419145 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-06 19:03:49.299  7783  7783 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.299  7783  7783 I libpersona: KNOX_SDCARD checking this for 10052
09-06 19:03:49.299  7783  7783 E Zygote  : v2
09-06 19:03:49.299  7783  7783 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.299  7783  7783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.309  7704  7762 D Compatibility: enabling receiver ResolveInfo{368c109a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-06 19:03:49.309  7783  7783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:49.309  1017  7228 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7783 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-06 19:03:49.309  7783  7783 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.309  1017  7228 I ActivityManager: Killing 7084:com.android.chrome/u0a77 (adj 15): empty #21
,09-06 19:03:49.319  7735  7735 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-06 19:03:49.319  7735  7735 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:03:49.319  7735  7735 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:03:49.319  7735  7735 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-06 19:03:49.329  1017  1148 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,09-06 19:03:49.329  7704  7762 D Compatibility: enabling receiver ResolveInfo{17ce2dcb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-06 19:03:49.329  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-06 19:03:49.329  1017  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:03:49.329  1017  1029 D SecContentProvider2: mCursor = null
09-06 19:03:49.329  7609  7609 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:03:49.329  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.329  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.329  1017  1143 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135212 arg2=-1 target=com.android.internal.util.StateMachine$SmHandler } in state OnlineState
09-06 19:03:49.339  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.339  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.339  7491  7507 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:03:49.339  7704  7762 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-06 19:03:49.349  7798  7798 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.349  7798  7798 I libpersona: KNOX_SDCARD checking this for 10029
09-06 19:03:49.349  7798  7798 E Zygote  : v2
09-06 19:03:49.349  7798  7798 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.359  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:03:49.359  1017  1057 D PackageManager: userId{-1}
09-06 19:03:49.359  1017  1057 D PackageManager: andCode{true}
,09-06 19:03:49.359  7783  7783 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.359  7783  7783 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:49.359  1017  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7798 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-06 19:03:49.359  1017  1030 I ActivityManager: Killing 6932:com.google.android.talk/u0a102 (adj 15): empty #21
,09-06 19:03:49.369  7798  7798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.369  1017  1511 I ActivityManager: Killing 7153:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:03:49.369  7798  7798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:03:49.369  7798  7798 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.369  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:03:49.369  7751  7751 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-06 19:03:49.369  7751  7751 D ThemeInfoUtil: isCurrentFestival = false
,09-06 19:03:49.379  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.379  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.379  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.379  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.379  1017  1135 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:49.389  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:49.399  7808  7808 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.399  7808  7808 E Zygote  : v2
09-06 19:03:49.399  7808  7808 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:03:49.399  7808  7808 I libpersona: KNOX_SDCARD not a persona
,09-06 19:03:49.399  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7808 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 19:03:49.399  7808  7808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:03:49.409  7808  7808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:03:49.409  7808  7808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.409  7798  7798 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.409  7798  7798 D ActivityThread: Added TimaKeyStore provider
09-06 19:03:49.409  1017  3357 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-06 19:03:49.409  1017  3357 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.409  1017  3357 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.409  1017  3357 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:03:49.409  1017  3357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:03:49.429  7808  7808 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.429  7808  7808 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.439  1496  1496 I Choreographer: Skipped 38 frames!  The application may be doing too much work on its main thread.
,09-06 19:03:49.439  1496  1496 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23e77efb time:148335
,09-06 19:03:49.439  7830  7830 E Zygote  : MountEmulatedStorage()
09-06 19:03:49.439  7830  7830 E Zygote  : v2
09-06 19:03:49.439  7830  7830 I libpersona: KNOX_SDCARD checking this for 10148
09-06 19:03:49.439  7830  7830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:03:49.439  7830  7830 I libpersona: KNOX_SDCARD not a persona
09-06 19:03:49.439  1017  3357 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7830 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-06 19:03:49.439  1017  3357 I ActivityManager: Killing 7178:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
09-06 19:03:49.449  7830  7830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:03:49.449  7830  7830 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:03:49.469  1017  1463 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-06 19:03:49.479  7830  7830 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:03:49.479  7830  7830 D ActivityThread: Added TimaKeyStore provider
,09-06 19:03:49.519  7830  7830 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 19:03:49.519  1017  1511 I ActivityManager: Killing 7190:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-06 19:03:49.519  7830  7830 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:49.519  7830  7830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:49.519  7830  7830 D AndroidRuntime: Shutting down, VM
09-06 19:03:49.519  7830  7830 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:03:49.519  7830  7830 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7830
09-06 19:03:49.519  7830  7830 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-06 19:03:49.519  7830  7830 E AndroidRuntime: 	... 11 more
09-06 19:03:49.519  1017  4235 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-06 19:03:49.519  1017  4235 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-06 19:03:49.519  1017  4235 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:49.519  1017  4235 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:49.519  1017  4235 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-06 19:03:49.529  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-06 19:03:49.529  1017  1486 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
09-06 19:03:49.529  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-06 19:03:49.529  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:03:49.529  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:03:49.529  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox

```
