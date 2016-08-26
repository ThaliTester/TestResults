#### Test 82728424c383411_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-26 10:52:12.786  1018  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 10:52:12.786  1018  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 10:52:12.786  1018  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 10:52:12.786  1018  1498 D BatteryService: stay LED for fully charged
08-26 10:52:12.786  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-26 10:52:12.796  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 10:52:12.796  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 10:52:12.796  1018  1018 I MotionRecognitionService: Plugged
08-26 10:52:12.796  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 10:52:12.796  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 10:52:12.796  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 10:52:12.806  3170  3170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 10:52:12.806  3170  3299 D HeadsetStateMachine: Disconnected process message: 10
08-26 10:52:12.816  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:12.826  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:12.826  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:13.086  6836  6836 D AndroidRuntime: 
08-26 10:52:13.086  6836  6836 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 10:52:13.086  6836  6836 D AndroidRuntime: CheckJNI is OFF
08-26 10:52:13.086  6836  6836 D AndroidRuntime: readGMSProperty: start
08-26 10:52:13.086  6836  6836 D AndroidRuntime: readGMSProperty: already setted!!
08-26 10:52:13.086  6836  6836 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 10:52:13.086  6836  6836 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 10:52:13.086  6836  6836 D AndroidRuntime: readGMSProperty: end
08-26 10:52:13.086  6836  6836 D AndroidRuntime: addProductProperty: start
08-26 10:52:13.236  6836  6836 E AffinityControl: AffinityControl: registerfunction enter
08-26 10:52:13.266  6836  6836 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 10:52:13.276  1018  4342 E PersonaManagerService: inState():  stateMachine is null !!
08-26 10:52:13.276  1018  4342 I PersonaManagerService: PersonaId don't exist
08-26 10:52:13.276  1018  4342 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 10:52:13.286  1018  4342 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 10:52:13.296  1018  4342 W ActivityManager: mDVFSHelper.acquire()
08-26 10:52:13.306   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 10:52:13.316   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 10:52:13.326  1018  4342 D FocusedStackFrame: Set to : 0
08-26 10:52:13.326  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 10:52:13.326  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 10:52:13.336  1018  4342 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:13.336  1018  4342 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:13.336  1018  4342 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:13.336  1018  4342 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:13.336  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 10:52:13.346  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 10:52:13.346   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-26 10:52:13.346  6847  6847 E Zygote  : MountEmulatedStorage()
08-26 10:52:13.346  6847  6847 I libpersona: KNOX_SDCARD checking this for 10171
08-26 10:52:13.346  6847  6847 E Zygote  : v2
08-26 10:52:13.346  6847  6847 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:13.346  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:13.346  1018  4342 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6847 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 10:52:13.346  1018  4342 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 10:52:13.346  1018  4342 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 10:52:13.356  1018  4342 D InputDispatcher: Focused application set to: xxxx
08-26 10:52:13.356  1018  4342 D InputDispatcher: Focus left window: 1485
08-26 10:52:13.356  6836  6836 D AndroidRuntime: Shutting down VM
08-26 10:52:13.356  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:13.356  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 10:52:13.356  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 10:52:13.356  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 10:52:13.376  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:13.376  6847  6847 D ActivityThread: Added TimaKeyStore provider
08-26 10:52:13.376  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 10:52:13.376  1018  1018 V ActivityManager: Display changed displayId=0
08-26 10:52:13.386  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 10:52:13.406  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
08-26 10:52:13.406   288   288 E SMD     : DCD OFF
08-26 10:52:13.426  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 10:52:13.446   258   451 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-26 10:52:13.446   258   448 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-26 10:52:13.456  1485  1485 V ActivityThread: updateVisibility : ActivityRecord{235d941c token=android.os.BinderProxy@383db0f6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 10:52:13.456  1485  1485 D Launcher: onTrimMemory. Level: 20
08-26 10:52:13.526  6847  6847 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 10:52:13.536  6847  6847 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6926-6928)
08-26 10:52:13.536  6847  6847 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 10:52:13.566  6836  6836 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 10:52:13.576  6847  6847 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21257e1d}
,08-26 10:52:13.576  6847  6847 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 10:52:13.586  6847  6847 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 10:52:13.626  6847  6847 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 10:52:13.626  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:13.636  6847  6847 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 10:52:13.696  6847  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 10:52:13.696  6847  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 10:52:13.696  6847  6847 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 10:52:13.696  6847  6847 I Adreno-EGL: Local Branch: 
08-26 10:52:13.696  6847  6847 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 10:52:13.696  6847  6847 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 10:52:13.696  6847  6847 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 10:52:13.796  6847  6847 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 10:52:13.806  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 10:52:13.806  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 10:52:13.816  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 10:52:13.816  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 10:52:13.906  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{6e26581 u0 com.test.thalitest/.MainActivity t2}
,08-26 10:52:13.936  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:13.946  6847  6847 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 10:52:13.956  6847  6847 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 10:52:13.956  6847  6847 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 10:52:13.966  6847  6847 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 10:52:13.976  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:13.976  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:14.016  6847  6889 D OpenGLRenderer: Render dirty regions requested: true
,08-26 10:52:14.016  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 10:52:14.016  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 10:52:14.016  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 10:52:14.016  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 10:52:14.016  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 10:52:14.026  6847  6877 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 10:52:14.026  6847  6847 V ActivityThread: updateVisibility : ActivityRecord{2e204efd token=android.os.BinderProxy@2cf87b66 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 10:52:14.036  6847  6847 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 10:52:14.036  6847  6847 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 10:52:14.046   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 10:52:14.056  1018  1475 D InputDispatcher: Focus entered window: 6847
,08-26 10:52:14.056  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 10:52:14.056  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 10:52:14.056  6847  6847 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 10:52:14.056  6847  6889 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 10:52:14.066  6847  6889 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
08-26 10:52:14.066  6847  6889 D OpenGLRenderer: Enabling debug mode 0
,08-26 10:52:14.076  1018  1137 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,08-26 10:52:14.086  1172  1172 I StatusBar: Icon Only
,08-26 10:52:14.086  1172  1172 D PanelView: There is/are notification(s) 
,08-26 10:52:14.096  1018  1049 I ActivityManager: Displayed Component not be shown by security: +695ms (total +767ms)
,08-26 10:52:14.106  1018  1049 W ActivityManager: mDVFSHelper.release()
08-26 10:52:14.106  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6e26581 u0 com.test.thalitest/.MainActivity t2} time:107490
,08-26 10:52:14.106   258   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 10:52:14.106   258   448 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
08-26 10:52:14.106  6847  6847 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-26 10:52:14.106  6847  6847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cf87b66 time:107495
,08-26 10:52:14.156  1018  6894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 10:52:14.186  1875  1875 I SamsungIME: getCurrentCandidateView
,08-26 10:52:14.236  6847  6847 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6847
,08-26 10:52:14.296  1875  1875 D SamsungIME: Dismiss ExpandCandiate
,08-26 10:52:14.466  1875  1875 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 10:52:14.506  1875  1875 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 10:52:14.516  1875  1875 I SamsungIME: KeybaordView init() : load resources
,08-26 10:52:14.526  6847  6847 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 10:52:14.536  1018  1314 E Watchdog: !@Sync 3
,08-26 10:52:14.546  1875  1875 I SamsungIME: getCurrentKeyboard
08-26 10:52:14.546  1875  1875 I SamsungIME: getTextKeyboard
,08-26 10:52:14.576  1875  1875 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 10:52:14.616  6847  6896 D jxcore_app_log: JniHelper::setJavaVM(0xb79f82b0), pthread_self() = -1208462272
,08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 10:52:14.626  6847  6896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d1a2bb added. We now have 1 listener(s)
,08-26 10:52:14.626  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-26 10:52:14.626  6847  6896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 10:52:14.636  6847  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-26 10:52:14.636  6847  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 10:52:14.636  6847  6896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c8a16 added. We now have 1 listener(s)
08-26 10:52:14.636  6847  6896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 10:52:14.646  6847  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:14.656  6847  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 10:52:14.656  6847  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:14.656  6847  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:14.656  6847  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 10:52:14.656  6847  6896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:14.656  6847  6896 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 10:52:14.666  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:14.666  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:14.696  6847  6847 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 10:52:15.246  6847  6903 W jxcore-log: Initializing JXcore engine
08-26 10:52:15.246  6847  6903 W jxcore-log: JXcore engine is ready
,08-26 10:52:15.306  1958  1958 E audit   : type=1400 msg=audit(1472201535.296:205): avc:  denied  { ioctl } for  pid=6903 comm="Thread-1256" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 10:52:15.306  1958  1958 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:15.306  1958  1958 E audit   : type=1300 msg=audit(1472201535.296:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3638f8 items=0 ppid=323 ppcomm=main pid=6903 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1256" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 10:52:15.306  1958  1958 E audit   : type=1320 msg=audit(1472201535.296:205): 
,08-26 10:52:15.316  6847  6903 W jxcore-log: Starting JXcore engine
,08-26 10:52:15.416  6847  6903 W jxcore-log: Platform android
08-26 10:52:15.416  6847  6903 W jxcore-log: 
08-26 10:52:15.416  6847  6903 W jxcore-log: Process ARCH arm
08-26 10:52:15.416  6847  6903 W jxcore-log: 
,08-26 10:52:15.646  6847  6903 I jxcore-log: JXcore Cordova bridge is ready!
08-26 10:52:15.646  6847  6903 I jxcore-log: 
,08-26 10:52:15.646  6847  6903 W jxcore-log: JXcore engine is started
,08-26 10:52:15.656  6847  6896 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 10:52:15.656  6847  6847 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 10:52:16.066   351   351 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 10:52:16.066   351   351 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 10:52:16.406   288   288 E SMD     : DCD OFF
,08-26 10:52:16.536  1018  4352 I art     : Explicit concurrent mark sweep GC freed 31297(1696KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 2.484ms total 143.251ms
,08-26 10:52:19.406  1018  1051 I PowerManagerService: [PWL] Off : 50s ago,
,08-26 10:52:19.406   288   288 E SMD     : DCD OFF,
,08-26 10:52:19.476  1018  3370 D SSRM:n  : SIOP:: AP = 330
,08-26 10:52:21.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:22.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:22.206  5682  5682 D FactoryTest: Not factory mode
,08-26 10:52:22.206  5682  5682 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 10:52:22.206  5682  5682 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 10:52:22.206  5682  5682 D MTPRx   : still no open session command from host, so toast
,08-26 10:52:22.206  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 10:52:22.206  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 10:52:22.206  5682  5682 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115599
,08-26 10:52:22.216  1018  1031 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 10:52:22.216  1018  1031 I PersonaManagerService: PersonaId don't exist
08-26 10:52:22.216  1018  1031 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 10:52:22.216  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 10:52:22.216  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:22.216  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:22.216  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 10:52:22.226  1018  1031 W ActivityManager: mDVFSHelper.acquire()
,08-26 10:52:22.236  1018  1031 D PersonaManager: isKioskContainerExistOnDevice
,08-26 10:52:22.246  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 10:52:22.246  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 10:52:22.246  1018  1031 D InputDispatcher: Focused application set to: xxxx
,08-26 10:52:22.246  1018  1031 D InputDispatcher: Focus left window: 6847
,08-26 10:52:22.246  5682  5682 E MTPRx   : started activity for popup
,08-26 10:52:22.246  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 10:52:22.246  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 10:52:22.276  5682  5682 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:22.296  5682  5682 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 10:52:22.306  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 10:52:22.306  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 10:52:22.306  1018  1031 D InputDispatcher: Focused application set to: xxxx
,08-26 10:52:22.306  1018  1031 D InputDispatcher: Focus entered window: 6847
,08-26 10:52:22.306  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 10:52:22.306  1018  1475 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 10:52:22.316  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 10:52:22.316  1018  1475 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30795af8 attribute=null, token = android.os.BinderProxy@e666fc8
,08-26 10:52:22.356  5682  5682 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 10:52:22.366  5682  5682 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-26 10:52:22.366  5682  5682 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 10:52:22.386  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 10:52:22.386  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 10:52:22.386  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 10:52:22.386  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 10:52:22.386  1018  1266 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 10:52:22.386  1018  1266 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 10:52:22.386  1018  1266 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 10:52:22.386  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 10:52:22.386  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 10:52:22.406  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 10:52:22.406  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 10:52:22.406  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a356a42 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1c2b7edb, 16908290=android.view.AbsSavedState$1@1c2b7edb}, android:focusedViewId=100}]}]
,08-26 10:52:22.406  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 10:52:22.406   288   288 E SMD     : DCD OFF
08-26 10:52:22.406  6847  6847 V ActivityThread: updateVisibility : ActivityRecord{2e204efd token=android.os.BinderProxy@2cf87b66 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 10:52:22.406  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 10:52:22.406  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 10:52:22.406  6847  6847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cf87b66 time:115797
,08-26 10:52:22.416  1018  1498 D PersonaManager: isKioskContainerExistOnDevice
,08-26 10:52:22.846  1018  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 10:52:22.846  1018  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 10:52:22.846  1018  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 10:52:22.846  1018  1483 D BatteryService: stay LED for fully charged
,08-26 10:52:22.846  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 10:52:22.846  1018  1018 I MotionRecognitionService: Plugged
,08-26 10:52:22.846  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 10:52:22.856  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 10:52:22.856  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 10:52:22.856  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 10:52:22.856  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 10:52:22.866  3170  3170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 10:52:22.866  3170  3299 D HeadsetStateMachine: Disconnected process message: 10
,08-26 10:52:22.886  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:22.886  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:22.886  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:23.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:23.386  1018  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 10:52:24.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:25.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:25.226  1018  1044 W ActivityManager: mDVFSHelper.release(),
,08-26 10:52:25.406   288   288 E SMD     : DCD OFF
,08-26 10:52:26.066   351   351 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 10:52:26.616  1018  1097 V AlarmManager: waitForAlarm result :4
,08-26 10:52:26.626  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 10:52:26.636  1975  1975 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 10:52:26.676  1018  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:26.686  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 10:52:26.686  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:26.686  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:26.686  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:26.756  4835  4835 D ConnectivityManager: CallingUid : 10011, CallingPid : 4835
,08-26 10:52:26.756  1018  1031 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 10:52:26.756  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 10:52:26.756  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-26 10:52:26.756  1018  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 10:52:26.766  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 10:52:26.816  4835  6917 W DriveInitializer: Background init thread started
,08-26 10:52:26.846   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 10:52:26.846   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:26.846  4835  6917 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 10:52:26.896  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:26.896  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 10:52:26.896  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:26.896  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:26.896  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:26.926  1018  4342 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-26 10:52:26.926  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 10:52:26.936  1018  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:26.936  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 10:52:26.936  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:26.946  1018  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:26.946  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:26.946  4835  6917 W DriveInitializer: Background init thread ended
,08-26 10:52:26.956  4835  6925 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 10:52:26.956  4835  6925 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 10:52:26.986  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 10:52:27.016  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.016  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.016  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.136  1018  4342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:27.136  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 10:52:27.136  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.136  1018  4342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.136  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.166  1018  4352 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:27.166  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 10:52:27.166  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.166  1018  4352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.166  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.216  1018  1328 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.216  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.216  1018  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.216  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.226  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.236  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.236  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.236  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.286  1018  4352 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.286  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.286  1018  4352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.286  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.286  1018  4352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:27.286  1018  4352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:27.286  1018  4352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:27.286  1018  4352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:27.306  6930  6930 E Zygote  : MountEmulatedStorage(),
,08-26 10:52:27.306  6930  6930 E Zygote  : v2
,08-26 10:52:27.306  6930  6930 I libpersona: KNOX_SDCARD checking this for 10011
08-26 10:52:27.306  6930  6930 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:27.306  1018  4352 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6930 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 10:52:27.316  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:27.316  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:27.316  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 10:52:27.346  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:27.346  6930  6930 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:27.366  6930  6930 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 10:52:27.366  6930  6930 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 10:52:27.416  6930  6930 I MultiDex: VM with version 2.1.0 has multidex support
08-26 10:52:27.416  6930  6930 I MultiDex: install
08-26 10:52:27.416  6930  6930 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 10:52:27.446  6930  6930 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 10:52:27.516  6930  6930 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 10:52:27.516  6930  6930 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@73f3769: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 10:52:27.516  6930  6930 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 10:52:27.546  6930  6930 D ChimeraCfgMgr: Reading stored module config
,08-26 10:52:27.576  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 10:52:27.586  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 10:52:27.586  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.586  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.586  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 10:52:27.596  1018  1328 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 10:52:27.596  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.596  1018  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.596  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 10:52:27.616  6930  6944 I art     : Background sticky concurrent mark sweep GC freed 23006(1106KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 5.216ms total 57.774ms
,08-26 10:52:27.646  6930  6947 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 10:52:27.646  1975  1975 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=0281ecac-3379-439d-bd89-95cc0108aced
,08-26 10:52:27.656  1018  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 10:52:27.656  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 10:52:27.656  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:27.656  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.656  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.666  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 10:52:27.676  6930  6930 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 10:52:27.676  6930  6930 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 10:52:27.686  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 10:52:27.696  6930  6944 W art     : Suspending all threads took: 16.183ms
,08-26 10:52:27.696  6930  6944 I art     : Background partial concurrent mark sweep GC freed 1139(222KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 19.362ms total 77.654ms
,08-26 10:52:27.706  1018  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 10:52:27.716  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.716  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.716  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.786   283   701 D WVCdm   : Instantiating CDM.
,08-26 10:52:27.786   283   283 I WVCdm   : CdmEngine::OpenSession
08-26 10:52:27.786   283   283 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 10:52:27.816   283   283 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 10:52:27.836   283   283 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 10:52:27.856  4318  4327 I art     : Explicit concurrent mark sweep GC freed 1426(49KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 700us total 29.581ms,
,08-26 10:52:27.896  1975  2157 W GCoreFlp: No location to return for getLastLocation()
,08-26 10:52:27.896  6930  6938 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 10:52:27.896  6930  6938 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 10:52:27.896  6930  6938 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 10:52:27.896  6930  6938 I System.out: (HTTPLog)-Thread-1231-448481106: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 10:52:27.896  6930  6938 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:27.896   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 10:52:27.896   278   987 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 10:52:27.906  6930  6938 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 10:52:27.906  6930  6938 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6930, getuid(): 10011
,08-26 10:52:27.906   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 10:52:27.906   283  1016 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-26 10:52:27.906   283  1016 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,08-26 10:52:27.906   283  1016 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 10:52:27.926   283  1016 D WVCdm   : PrepareKeyRequest: nonce=629539571
,08-26 10:52:27.946  1018  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.946  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.946  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:27.946  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.956  4835  6926 D UdcContextInitService: registered all accounts: true
,08-26 10:52:27.956  1975  2161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 10:52:27.956  1018  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.966  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.966  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.966  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.966  1018  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:27.966  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:27.966  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:27.966  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:27.976  1975  2173 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 10:52:28.136  1018  4342 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 10:52:28.136  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 10:52:28.146  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:28.146  1018  4342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:28.146  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:28.186  1018  1483 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 10:52:28.186  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 10:52:28.186  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:28.186  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:28.186  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:28.196  1975  2173 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:28.196  6930  6938 I qtaguid : Untagging socket 30
,08-26 10:52:28.196   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 10:52:28.196   278   987 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 10:52:28.196  1975  2173 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 10:52:28.196  1975  2173 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1975, getuid(): 10011
,08-26 10:52:28.246  1975  2173 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1975, getuid(): 10011
,08-26 10:52:28.416   288   288 E SMD     : DCD OFF
,08-26 10:52:28.696  6961  6961 I dex2oat : ----------------------------------------------------,
08-26 10:52:28.696  6961  6961 I dex2oat : <SS>: S T A R T I N G . . .
08-26 10:52:28.696  6961  6961 I dex2oat : <SS>: Zip is absent. Canceled.
08-26 10:52:28.696  6961  6961 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 10:52:28.766  6961  6961 I dex2oat : dex2oat took 68.034ms (threads: 4)
,08-26 10:52:28.776  6930  6938 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 10:52:28.776  6930  6938 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 10:52:28.776  6930  6938 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 10:52:28.776  6930  6938 I Adreno-EGL: Local Branch: 
08-26 10:52:28.776  6930  6938 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 10:52:28.776  6930  6938 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 10:52:28.776  6930  6938 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 10:52:28.776  1018  3400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 10:52:28.846  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 10:52:28.846  6847  6903 I jxcore-log: 
,08-26 10:52:28.856  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 10:52:28.856  6847  6903 I jxcore-log: 
,08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:28.856  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:28.866  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:28.866  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-26 10:52:28.866  6847  6903 I jxcore-log: 
,08-26 10:52:28.866  6930  6938 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 10:52:28.866  6930  6938 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 10:52:28.866  6930  6938 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 10:52:28.866  6930  6938 I Adreno-EGL: Local Branch: 
08-26 10:52:28.866  6930  6938 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 10:52:28.866  6930  6938 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 10:52:28.866  6930  6938 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 10:52:28.866  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 10:52:28.866  6847  6903 I jxcore-log: 
,08-26 10:52:28.906  6930  6938 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-26 10:52:28.906  6930  6938 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 10:52:28.906  6930  6938 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 10:52:28.906  6930  6938 I Adreno-EGL: Local Branch: 
08-26 10:52:28.906  6930  6938 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 10:52:28.906  6930  6938 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 10:52:28.906  6930  6938 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 10:52:29.186  1975  6928 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:29.186  1975  6928 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 10:52:29.186  1975  6928 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1975, getuid(): 10011
,08-26 10:52:29.486  1018  3370 D SSRM:n  : SIOP:: AP = 350
,08-26 10:52:29.506  1975  6928 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1975, getuid(): 10011
,08-26 10:52:29.526   283   701 I WVCdm   : CdmEngine::CloseSession
,08-26 10:52:29.526   283   701 I WVCdm   : L3 Terminate.
,08-26 10:52:29.556  6847  6903 D executeNativeTests: Running unit tests
,08-26 10:52:29.636  6847  6861 I art     : Background sticky concurrent mark sweep GC freed 39809(1949KB) AllocSpace objects, 7(993KB) LOS objects, 19% free, 10MB/13MB, paused 5.071ms total 29.079ms
,08-26 10:52:29.646  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:29.646  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 added. We now have 2 listener(s)
,08-26 10:52:29.646  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:29.646  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:29.646  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:29.646  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:29.646  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 added. We now have 2 listener(s)
08-26 10:52:29.646  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:29.646  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:29.646  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:29.656  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:29.656  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:29.656  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:29.656  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.656  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.656  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 10:52:29.656  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:29.656  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 10:52:29.656  6847  6903 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 10:52:29.666  6847  6903 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:29.666  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:29.666  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 10:52:29.666  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:29.666  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:29.666  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:29.666  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:29.666  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 removed from the list
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.666  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 removed from the list
08-26 10:52:29.666  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.666  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.666  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
,08-26 10:52:29.666  6847  6903 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 10:52:29.666  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:29.666  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:29.666  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:29.666  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:29.666  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:29.666  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.666  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.666  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:29.666  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:29.666  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.666  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.676  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:29.676  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:29.676  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:29.676  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:29.676  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.676  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:29.676  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.676  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.676  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:29.676  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.676  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:29.676  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.676  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:29.676  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.676  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.686  6847  6903 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 10:52:29.686  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:29.686  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:29.686  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:29.686  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:29.686  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:29.686  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:29.686  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:29.686  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:29.686  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:29.686  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:29.696  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:52:29.696  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:29.696  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:52:29.706  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-26 10:52:29.706  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 10:52:29.706  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 10:52:29.706  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 10:52:29.706  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:29.706  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 10:52:29.726  3170  3179 D BtGatt.GattService: registerClient() - UUID=3a61efa3-13a7-4289-9251-0cd55268654b
,08-26 10:52:29.766  3170  3287 D BtGatt.GattService: onClientRegistered() - UUID=3a61efa3-13a7-4289-9251-0cd55268654b, clientIf=6
,08-26 10:52:29.776  6847  6858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:29.776  3170  5198 D BtGatt.GattService: start scan with filters
,08-26 10:52:29.776  3170  3297 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:29.776  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:29.776  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 10:52:29.776  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 10:52:29.776  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:29.786  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:29.786  3170  3297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:29.786  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:29.786  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:29.796  3170  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 10:52:29.796  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.796  3170  3297 D BtGatt.ScanManager: allow scan with filters
,08-26 10:52:29.796  3170  3297 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 10:52:29.796  3170  3297 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 10:52:29.796  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 10:52:29.796  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.796  3170  3297 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:29.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:29.806  3170  3297 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 10:52:29.806  3170  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 10:52:29.806  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.806  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 10:52:29.806  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:29.806  6847  6903 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:29.816  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:29.816  6847  6903 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:29.816  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:29.816  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 10:52:29.816  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:29.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:29.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:29.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:29.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:29.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:29.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:29.816  3170  3184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:29.816  3170  3179 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 10:52:29.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:29.826  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:29.826  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 10:52:29.826  3170  3297 D BtGatt.ScanManager: filter size is 1
,08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:29.826  3170  3297 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:29.826  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:29.826  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:29.826  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 10:52:29.826  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.826  3170  3297 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:29.826  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:29.826  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:29.826  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:29.836  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:29.836  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.836  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:29.836  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:29.836  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.836  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.836  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:29.836  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.836  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 10:52:29.836  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:29.836  6847  6903 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 10:52:29.836  3170  3297 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 10:52:29.836  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:29.836  3170  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 10:52:29.836  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:29.846  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:29.846  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:29.846  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:29.846  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.856  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:29.856  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:29.856  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:29.856  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:29.856  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:29.856  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.856  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:29.856  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:29.866  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:29.866  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:29.866  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 10:52:29.866  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:29.866  3170  3179 D BtGatt.GattService: registerClient() - UUID=e897833a-cec5-462d-98b7-aee09280a9c8
,08-26 10:52:29.916  3170  3287 D BtGatt.GattService: onClientRegistered() - UUID=e897833a-cec5-462d-98b7-aee09280a9c8, clientIf=6
,08-26 10:52:29.916  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:29.916  3170  5198 D BtGatt.GattService: start scan with filters
,08-26 10:52:29.916  3170  3297 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:29.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:29.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 10:52:29.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 10:52:29.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:29.926  3170  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 10:52:29.926  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:29.926  3170  3297 D BtGatt.ScanManager: allow scan with filters
08-26 10:52:29.926  3170  3297 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 10:52:29.926  3170  3297 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 10:52:29.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:29.926  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:29.926  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 10:52:29.926  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.926  3170  3297 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 10:52:29.926  3170  3297 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 10:52:29.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:29.936  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:29.936  6847  6903 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:29.936  3170  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 10:52:29.936  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.946  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:29.946  6847  6903 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:29.946  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:29.946  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 10:52:29.946  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:29.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:29.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:29.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:29.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:29.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:29.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:29.946  3170  3184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:29.946  3170  3179 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 10:52:29.946  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 10:52:29.946  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.956  3170  3297 D BtGatt.ScanManager: filter size is 1
,08-26 10:52:29.956  3170  3297 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:29.956  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:29.956  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 10:52:29.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 10:52:29.956  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:29.956  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 10:52:29.956  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.966  3170  3297 D BtGatt.ScanManager: stopping BLe Batch
08-26 10:52:29.966  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:29.966  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:29.966  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:29.966  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:29.966  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:29.966  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.966  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:29.966  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:29.966  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:29.966  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:29.966  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:29.966  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.966  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:29.966  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:29.966  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:29.966  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:29.966  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:29.966  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
,08-26 10:52:29.966  6847  6903 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 10:52:29.966  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 10:52:29.976  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:29.976  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:29.976  3170  3297 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:29.976  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:29.976  3170  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 10:52:29.976  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:29.976  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:29.986  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:29.986  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.986  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:29.986  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:29.986  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:29.986  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 10:52:29.986  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:29.986  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:29.996  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:29.996  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:29.996  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:30.006  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:30.006  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 10:52:30.006  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:30.006  3170  5198 D BtGatt.GattService: registerClient() - UUID=2cddd8e3-4b42-4762-bbf5-eaf2ac81e9fb
,08-26 10:52:30.046  3170  3287 D BtGatt.GattService: onClientRegistered() - UUID=2cddd8e3-4b42-4762-bbf5-eaf2ac81e9fb, clientIf=6
,08-26 10:52:30.046  6847  6862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:30.046  3170  3288 D BtGatt.GattService: start scan with filters
,08-26 10:52:30.056  3170  3297 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:30.056  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:30.056  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 10:52:30.056  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 10:52:30.056  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:30.056  3170  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 10:52:30.056  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:30.056  3170  3297 D BtGatt.ScanManager: allow scan with filters
,08-26 10:52:30.056  3170  3297 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 10:52:30.066  3170  3297 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 10:52:30.066  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:30.066  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:30.066  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:30.066  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 10:52:30.066  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:30.066  3170  3297 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 10:52:30.066  3170  3297 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 10:52:30.076  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:30.076  3170  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 10:52:30.076  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:30.076  6847  6903 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:30.086  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:30.086  6847  6903 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 10:52:30.086  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:30.086  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 10:52:30.086  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.086  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 10:52:30.086  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:30.086  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 10:52:30.086  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 10:52:30.086  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 10:52:30.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 10:52:30.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:30.096  3170  5198 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:30.096  3170  3297 D BtGatt.ScanManager: filter size is 1
,08-26 10:52:30.096  3170  3297 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 10:52:30.096  3170  3288 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:30.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:30.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 10:52:30.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 10:52:30.106  3170  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 10:52:30.106  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:30.106  3170  3297 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:30.106  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:30.106  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:30.106  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:30.106  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.106  6847  6903 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:30.106  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.106  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.106  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:30.106  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.106  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.106  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.106  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.106  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
,08-26 10:52:30.106  6847  6903 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 10:52:30.116  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
,08-26 10:52:30.116  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.116  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:30.116  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list,
08-26 10:52:30.116  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list,
08-26 10:52:30.116  3170  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 10:52:30.116  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:30.116  3170  3297 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 10:52:30.116  6847  6903 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
08-26 10:52:30.116  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
,08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list,
08-26 10:52:30.116  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list,
08-26 10:52:30.116  6847  6903 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 10:52:30.116  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 10:52:30.116  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.116  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
,08-26 10:52:30.116  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.116  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:30.116  3170  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 10:52:30.116  3170  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:30.126  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:30.126  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 10:52:30.126  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:30.126  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:30.126  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.126  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.126  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.126  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:30.126  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.126  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.126  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.126  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.126  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.126  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.126  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.126  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.126  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.126  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:30.126  6847  6903 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:30.126  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:30.126  6847  6903 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:30.126  68,47  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:30.126  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 10:52:30.136  6847  6903 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:30.136  6847  6903 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:30.136  6847  6903 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to i,s not amongst the discovered peers, but trying anyway...
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:30.136  6847  6903 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 10:52:30.136  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.136  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.136  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 10:52:30.136  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.136  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.136  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.136  6847  6971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1320)
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1320
08-26 10:52:30.146  6847  6903 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 10:52:30.146  6847  6903 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:30.146  6847  6903 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:30.146  6847  6903 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:30.146  6847  6903 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 10:52:30.146  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.146  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6971 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.146  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.146  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.146  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.146  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.146  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.156  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.156  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.156  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.156  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.156  6847  6971 D BluetoothSocket: connect(): myUserId = 0
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 10:52:30.156  6847  6971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 10:52:30.156  3170  3288 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:30.156  6847  6973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 10:52:30.156  6847  6973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:30.156  6847  6971 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.156  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.156  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.156  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:30.156  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.156  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.156  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.156  6847  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 10:52:30.156  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.156  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:30.156  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.156  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.166  6847  6903 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 10:52:30.166  6847  6903 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:30.166  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:30.166  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.166  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.166  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.166  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.166  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.166  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.166  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.166  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.166  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.166  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.166  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.166  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.176  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.176  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:30.176  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:30.176  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:30.176  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.176  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.176  6847  6903 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3513a4a8 not in the list
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.176  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:30.176  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.176  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.176  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:30.176  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:30.176  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:30.176  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17787bc1 not in the list
08-26 10:52:30.176  6847  6903 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:30.176  6847  6903 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:30.176  6847  6903 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 10:52:30.176  6847  6903 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:30.176  6847  6903 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:30.176  6847  6903 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 10:52:30.176  6847  6903 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 10:52:30.176  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:30.176  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@305986bb added. We now have 2 listener(s)
08-26 10:52:30.176  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:30.176  6847  6903 D BluetoothAdapter: enable()
08-26 10:52:30.186  6847  6903 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 10:52:30.206  1018  1137 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 10:52:30.206  1018  1137 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 10:52:30.206  1018  1137 D SecContentProvider2: mCursor = null
08-26 10:52:30.206  1018  1137 D WifiService: setWifiEnabled: true pid=6847, uid=10171
08-26 10:52:30.206  1018  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:30.216  1018  1137 W WifiService: Failed getting userId using ActivityManagerNative
08-26 10:52:30.216  1018  1137 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:30.216  1018  1137 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 10:52:30.216  1018  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 10:52:30.216  1018  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 10:52:30.216  1018  1137 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 10:52:30.216  1018  1137 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 10:52:30.216  1018  1137 D SettingsProvider: name = wifi_on
08-26 10:52:30.216  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:30.216  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ccd87d8 added. We now have 3 listener(s)
08-26 10:52:30.216  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:30.226  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:30.226  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bf6d731 added. We now have 4 listener(s)
08-26 10:52:30.226  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:30.226  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:30.226  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e90be16 added. We now have 5 listener(s)
08-26 10:52:30.226  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:30.226  1018  4342 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 10:52:30.226  1018  4342 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 10:52:30.226  1018  4342 D SecContentProvider2: mCursor = null
,08-26 10:52:30.226  1018  4342 D WifiService: setWifiEnabled: false pid=6847, uid=10171
,08-26 10:52:30.236  1018  4342 D SettingsProvider: name = wifi_on
,08-26 10:52:30.236  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 10:52:30.236  1387  1387 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 10:52:30.236  1387  1387 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 10:52:30.236  1387  1387 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 10:52:30.246  6847  6903 D BluetoothAdapter: disable()
,08-26 10:52:30.246  1387  1387 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 10:52:30.246  1018  1498 D SettingsProvider: name = bluetooth_on
08-26 10:52:30.246  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:30.256  3170  3280 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-26 10:52:30.256  3170  3280 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:30.256  3170  3280 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 10:52:30.256  3170  3280 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:30.256  3170  3280 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 10:52:30.256  1018  4352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:30.256  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 10:52:30.266  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.266  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.266  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:30.266  3170  3170 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 10:52:30.266  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e83ac87, channel: 19, state: LISTENING
08-26 10:52:30.266  3170  3280 D BluetoothAdapterService: Autoconnection is available 
,08-26 10:52:30.266  3170  3280 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 10:52:30.266  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 10:52:30.266  3170  3280 D BluetoothAdapterService: terminating service from this receiver
08-26 10:52:30.266  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e83ac87, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3690fa8f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@40bc7b4mSocket: android.net.LocalSocket@39150fdd impl:android.net.LocalSocketImpl@1abb4752 fd:FileDescriptor[74]
08-26 10:52:30.266  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:30.266  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39150fdd impl:android.net.LocalSocketImpl@1abb4752 fd:FileDescriptor[74]
08-26 10:52:30.266  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 10:52:30.266  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.266  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.266  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.266  3170  3280 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 10:52:30.266  3170  3280 D BluetoothAdapterProperties: mDiscovering is false
,08-26 10:52:30.276  1018  1467 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 10:52:30.276  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:30.276  3170  3280 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 10:52:30.276  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 10:52:30.276  1308  1308 D BluetoothPbap: Proxy object disconnected
08-26 10:52:30.276  1308  1308 D PbapServerProfile: Bluetooth service disconnected
,08-26 10:52:30.276  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:30.276  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:30.286  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:30.286  1172  1172 D BluetoothTile:  onBluetoothStateChange:
08-26 10:52:30.286  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:30.286  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-26 10:52:30.286  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 10:52:30.286  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:30.286  1172  1172 D BluetoothTile:  getBluetoothState : 13
08-26 10:52:30.286  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:30.286  1875  1875 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 10:52:30.286  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:30.286  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.286  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 10:52:30.296  1018  4352 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 10:52:30.296  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:30.296  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:30.296  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 10:52:30.296  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:30.296  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 10:52:30.296  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:30.296  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 10:52:30.296  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.296  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:30.296  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:30.306  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:30.306  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:30.306  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:30.306  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:30.306  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3977ab20, channel: 5, state: LISTENING
08-26 10:52:30.316  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3977ab20, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ac711c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28d7ccd9mSocket: android.net.LocalSocket@2d22869e impl:android.net.LocalSocketImpl@38eba57f fd:FileDescriptor[76]
08-26 10:52:30.316  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d22869e impl:android.net.LocalSocketImpl@38eba57f fd:FileDescriptor[76]
,08-26 10:52:30.316  3170  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 10:52:30.316  3170  3287 D BluetoothAdapterProperties: Scan Mode:20
,08-26 10:52:30.316  3170  3170 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:30.316  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7fc594c, channel: 12, state: LISTENING
,08-26 10:52:30.316  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7fc594c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@559a4c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@266f5d95mSocket: android.net.LocalSocket@22c6eaa impl:android.net.LocalSocketImpl@381f1a9b fd:FileDescriptor[79]
08-26 10:52:30.316  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22c6eaa impl:android.net.LocalSocketImpl@381f1a9b fd:FileDescriptor[79]
08-26 10:52:30.316  3170  5204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:30.316  3170  5204 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 10:52:30.316  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.316  3170  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 10:52:30.316  3170  3280 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 10:52:30.316  3170  3280 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 10:52:30.316  3170  3280 E bt-btif : cmd socket is not created
08-26 10:52:30.316  3170  3317 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 10:52:30.316  3170  3317 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 10:52:30.326  3170  3280 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 10:52:30.326  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 10:52:30.326  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 10:52:30.326  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 10:52:30.326  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:30.326  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:30.326  3170  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 10:52:30.326  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.326  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.326  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-26 10:52:30.326  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.326  3170  3170 V BluetoothOppManager: cleanUp...
,08-26 10:52:30.326  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.336  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:30.346  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:30.346  6847  6971 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@257f4984, channel: -1, state: INIT
08-26 10:52:30.346  6847  6971 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@257f4984, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fb0b56d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14d2a5a2mSocket: android.net.LocalSocket@9741233 impl:android.net.LocalSocketImpl@2a6979f0 fd:FileDescriptor[105]
08-26 10:52:30.346  6847  6971 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9741233 impl:android.net.LocalSocketImpl@2a6979f0 fd:FileDescriptor[105]
08-26 10:52:30.346  6847  6971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1320)
,08-26 10:52:30.346  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:30.346  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 10:52:30.346  1018  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 10:52:30.356  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.356  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:30.356  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.356  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.366  6979  6979 E Zygote  : MountEmulatedStorage()
,08-26 10:52:30.366  6979  6979 E Zygote  : v2
08-26 10:52:30.366  6979  6979 I libpersona: KNOX_SDCARD checking this for 10055
08-26 10:52:30.366  6979  6979 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:30.366  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:30.366  1018  1475 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6979 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 10:52:30.376  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:30.376  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 10:52:30.396  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:30.406  6979  6979 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:30.426  6979  6979 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 10:52:30.466  6979  6979 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-26 10:52:30.466  6979  6979 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 10:52:30.466  6979  6979 D UserAnalysis: Create SecureDbHelper
,08-26 10:52:30.476  6979  6979 D IntelligenceServiceApplication: onCreate()
,08-26 10:52:30.476  1018  1484 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 10:52:30.486  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.486  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:30.486  6979  6979 D IntelligenceServiceApplication: no applications having user consent for prediction
08-26 10:52:30.486  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.486  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.496  6994  6994 E Zygote  : MountEmulatedStorage(),
08-26 10:52:30.496  1018  1484 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6994 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
08-26 10:52:30.496  6994  6994 E Zygote  : v2
08-26 10:52:30.496  6994  6994 I libpersona: KNOX_SDCARD checking this for 10105,
08-26 10:52:30.496  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:30.496  6994  6994 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:30.496  6979  6979 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 10:52:30.496  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 10:52:30.506  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:30.506  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 10:52:30.506  1975  6976 I art     : Explicit concurrent mark sweep GC freed 62316(3MB) AllocSpace objects, 8(320KB) LOS objects, 40% free, 11MB/19MB, paused 1.504ms total 106.707ms
,08-26 10:52:30.516  6979  6979 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 10:52:30.516  3170  3317 W bt-l2cap: btif_mce_execute_se not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:30.516  3170  3317 W bt-btif : ag scb idx 1 not allocated
08-26 10:52:30.516  3170  3317 W bt-btif : ag scb idx 2 not allocated
08-26 10:52:30.516  3170  3317 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 10:52:30.516  3170  3364 I bt_userial_mct: exiting userial_read_thread
08-26 10:52:30.516  3170  3364 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 10:52:30.516  3170  3287 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 10:52:30.516  3170  3319 I bt_vendor: hw_epilog_process
,08-26 10:52:30.526  1018  1030 I ActivityManager: Killing 6408:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 10:52:30.526  3170  3287 D bt_userial_mct: userial_close
08-26 10:52:30.526  3170  3287 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 10:52:30.526  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:30.526  6994  6994 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:30.636   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 10:52:30.636   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:30.646  6994  7017 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 10:52:30.646   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 10:52:30.646   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:30.646  6994  7017 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 10:52:30.656  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 10:52:30.766  3170  3287 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 10:52:30.766  3170  3287 I bt_vendor: bluetooth satus is on
08-26 10:52:30.766  3170  3287 I bt_vendor: bt-vendor : resetting BT status
,08-26 10:52:30.766  3170  3287 I bt_vendor: Starting hciattach daemon
08-26 10:52:30.766  3170  3287 I bt_vendor: try to set false
,08-26 10:52:30.766  3170  3287 I bt_vendor: Starting hciattach daemon
08-26 10:52:30.766  3170  3287 I bt_vendor: try to set false
,08-26 10:52:30.766  3170  3287 I bt_vendor: cleanup
,08-26 10:52:30.766  3170  3317 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-26 10:52:30.766  3170  3287 I GKI_LINUX: GKI_exit_task 0 done
08-26 10:52:30.766  3170  3287 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 10:52:30.766  3170  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 10:52:30.766  3170  3280 D BtConfig.SecureMode: isSecureModeOn:false
08-26 10:52:30.766  3170  3280 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 10:52:30.766  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 10:52:30.766  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 10:52:30.766  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 10:52:30.766  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:30.766  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.776  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.776  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.776  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:30.776  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 10:52:30.776  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:30.776  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:30.776  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:30.776  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.776  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.776  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.776  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:30.776  3170  3170 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:30.776  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 10:52:30.776  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:30.776  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:30.776  3170  3170 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 10:52:30.776  3170  3170 D BtGatt.GattService: stop()
08-26 10:52:30.776  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:30.776  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.776  3170  3170 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 10:52:30.776  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.776  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.786  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.786  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 10:52:30.786  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 10:52:30.786  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:30.786  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 10:52:30.786  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:30.786  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.786  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.786  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.786  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.786  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 10:52:30.786  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 10:52:30.786  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 10:52:30.786  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:30.786  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 10:52:30.786  3170  3170 D HeadsetService: Received stop request...Stopping profile...
,08-26 10:52:30.786  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.796  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:30.796  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.796  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 10:52:30.796  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 10:52:30.796  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:30.796  1308  1308 D HeadsetProfile: Bluetooth service disconnected
,08-26 10:52:30.796  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 10:52:30.796  3170  3170 D A2dpService: Received stop request...Stopping profile...
08-26 10:52:30.796  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 10:52:30.796  1018  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:30.796  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.806  3170  3304 D A2dpStateMachine: Exit Disconnected: -1,
08-26 10:52:30.806  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.806  1018  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:30.806  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.806  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:30.806  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:30.806  3170  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.806  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:30.806  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-26 10:52:30.806  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:30.806  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.806  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.806  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.806  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 10:52:30.806  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  1308  1308 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:30.806  1308  1308 D A2dpProfile: Bluetooth service disconnected
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.816  1018  1030 I ActivityManager: Killing 6551:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-26 10:52:30.806  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 10:52:30.816  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:30.806  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:30.816  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.,apps.gmm.map.m.q.a(PG:8700)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  6994  6994 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:30.806  6994  6994 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:30.806  3170  3280 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 10:52:30.816  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:30.816  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.816  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:30.816  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:30.826  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:30.826  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 10:52:30.826  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 10:52:30.826  3170  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 10:52:30.826  3170  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 10:52:30.826  3170  3280 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 10:52:30.826  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 10:52:30.826  3170  3170 D HidService: Received stop request...Stopping profile...
08-26 10:52:30.826  3170  3170 D HidService: Stopping Bluetooth HidService
08-26 10:52:30.826  3170  3170 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:30.826  3170  3170 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 10:52:30.826  3170  3170 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 10:52:30.826  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:30.826  3170  3170 D HealthService: Received stop request...Stopping profile...
08-26 10:52:30.826  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:30.826  1308  1308 D BluetoothInputDevice: Proxy object disconnected
08-26 10:52:30.826  1308  1308 D HidProfile: Bluetooth service disconnected
08-26 10:52:30.826  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 10:52:30.826  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:30.826  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 10:52:30.826  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 10:52:30.836  3170  3170 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 10:52:30.836  3170  3170 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:30.836  3170  3170 D PanService: Received stop request...Stopping profile...
08-26 10:52:30.836  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:30.836  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 10:52:30.836  1308  1308 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 10:52:30.836  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 10:52:30.836  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:30.836  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 10:52:30.836  1308  1308 D PanProfile: Bluetooth service disconnected
08-26 10:52:30.836  3170  3170 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:30.836  3170  3170 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 10:52:30.836  3170  3305 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 10:52:30.836  3170  3170 I GKI_LINUX: GKI_exit_task 2 done
08-26 10:52:30.836  3170  3170 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 10:52:30.836  3170  3170 D BluetoothMapService: Received stop request...Stopping profile...
08-26 10:52:30.836  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:30.836  1308  1308 D BluetoothMap: Proxy object disconnected
08-26 10:52:30.836  3170  3170 D SapService: Received stop request...Stopping profile...
08-26 10:52:30.836  3170  3170 D SapService: Stopping Bluetooth SapService
08-26 10:52:30.836  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:30.846  1308  1308 D MapProfile: Bluetooth service disconnected
08-26 10:52:30.846  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 10:52:30.846  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 10:52:30.846  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 10:52:30.846  3170  3170 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 10:52:30.846  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 10:52:30.846  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:30.846  3170  3170 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:30.846  3170  3170 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 10:52:30.846  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 10:52:30.846  1308  1308 D SapProfile: Bluetooth service disconnected
08-26 10:52:30.846  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 10:52:30.846  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:30.846  3170  3170 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 10:52:30.846  3170  3170 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 10:52:30.846  3170  3170 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 10:52:30.846  3170  3170 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-26 10:52:30.846  3170  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 10:52:30.846  3170  3280 D BluetoothAdapterProperties: Setting state to 10
08-26 10:52:30.846  3170  3280 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 10:52:30.846  3170  3280 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:30.846  3170  3280 D BluetoothAdapterService: updateAdapterState state is 10
08-26 10:52:30.846  3170  3280 D BluetoothAdapterService: Autoconnection is available 
08-26 10:52:30.846  3170  3280 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 10:52:30.846  3170  3280 I BluetoothAdapterState: Entering OffState
08-26 10:52:30.846  1427  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.846  1427  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  1308  1318 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 10:52:30.856  1308  1318 D Bluetoothsap: Unbinding service...
08-26 10:52:30.856  1441  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.856  1441  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  1308  1317 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 10:52:30.856  3170  5198 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:30.856  1308  1318 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.856  1308  1318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  1975  2158 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.856  1975  2158 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  3170  3179 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.856  3170  3179 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.856  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.856  1308  1318 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 10:52:30.856  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:30.866  1455  1662 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.866  1455  1662 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.866  1308  1318 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:30.866  6847  6855 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.866  6847  6855 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.866  6847  6855 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 10:52:30.866  6847  6855 D BluetoothLeAdvertiser: Exit stop advertising
08-26 10:52:30.866  6847  6855 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 10:52:30.866  6847  6855 D BluetoothLeScanner: Exiting stopAllScan
08-26 10:52:30.866  1308  1317 D BluetoothMap: onBluetoothStateChange: up=false
08-26 10:52:30.866  1172  4673 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:30.866  1172  4673 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:30.876  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-26 10:52:30.876  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 10:52:30.876  6994  7018 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 10:52:30.886  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:30.886  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-26 10:52:30.886  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 10:52:30.886  3170  3287 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 10:52:30.886  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:30.886  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 10:52:30.886  1172  1726 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:30.886  3170  3170 I GKI_LINUX: GKI_exit_task 1 done
08-26 10:52:30.886  3170  3170 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 10:52:30.886  3170  3170 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 10:52:30.896  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:30.896  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-26 10:52:30.896  1172  1726 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:30.896  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:30.896  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:30.896  3170  3170 I art     : System.exit called, status: 0
08-26 10:52:30.896  3170  3170 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 10:52:30.896  1875  1875 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 10:52:30.896  1018  1328 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:30.896  1018  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:30.906  1975  2168 D BluetoothAdapter: 392272383: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:30.906  1975  2168 D BluetoothAdapter: 392272383: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:30.906  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:30.906  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:30.906  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.906  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:30.906  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:30.906  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:30.916  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.916  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:30.916  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 10:52:30.916  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:30.916  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.916  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.916  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:30.916  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:30.916  1018  1467 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 10:52:30.916  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 10:52:30.916  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:30.916  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:30.916  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 10:52:30.926  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:30.936  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:30.936  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:30.936  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 10:52:30.946  1018  1030 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 10:52:30.946  1018  1030 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 10:52:30.946  1018  1030 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 10:52:30.946  1018  1030 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 10:52:30.946  1018  1030 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 10:52:30.946  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 10:52:30.946  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:30.946  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:30.946  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:30.946  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:30.956  7036  7036 E Zygote  : MountEmulatedStorage()
,08-26 10:52:30.956  7036  7036 E Zygote  : v2
08-26 10:52:30.956  7036  7036 I libpersona: KNOX_SDCARD checking this for 1002
,08-26 10:52:30.956  7036  7036 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:30.966  7036  7036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:30.956  1018  1030 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7036 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 10:52:30.966  7036  7036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:30.966  7036  7036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:30.986  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:30.986  7036  7036 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:30.996  7036  7036 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 10:52:30.996  7036  7036 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:31.026  7036  7036 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 10:52:31.036  1387  1387 I wpa_supplicant: nl80211: Received scan results (11 BSSes),
08-26 10:52:31.036  1018  1126 D WifiP2pService: InactiveState{ what=147461 }
08-26 10:52:31.036  1018  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-26 10:52:31.036  1018  1126 D WifiP2pService: DefaultState{ what=147461 }
,08-26 10:52:31.036  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-26 10:52:31.036  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 10:52:31.046   278   991 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:31.046  1975  6928 V NativeCrypto: Read error: ssl=0xb802ff00: I/O error during system call, Connection timed out
08-26 10:52:31.046  1975  3021 V NativeCrypto: Read error: ssl=0xb7ef59b8: I/O error during system call, Connection timed out
,08-26 10:52:31.046  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 10:52:31.046  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:31.046  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:31.046  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-26 10:52:31.056  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 10:52:31.056  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 10:52:31.056  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.056  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.056  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.056  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.066  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-26 10:52:31.066  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 10:52:31.066  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:31.066  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-26 10:52:31.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.066  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 10:52:31.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
08-26 10:52:31.066  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 10:52:31.076  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 10:52:31.076  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 10:52:31.076  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-26 10:52:31.076  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:31.076  1975  6928 W GLSUser : [AppCertManager] IOException while requesting key: 
08-26 10:52:31.076  1975  6928 W GLSUser : javax.net.ssl.SSLException: Read error: ssl=0xb802ff00: I/O error during system call, Connection timed out
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_read(Native Method)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at sdu.read(:com.google.android.gms:714)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okio.Okio$2.read(Okio.java:116)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okio.RealBufferedSource.indexOf(RealBufferedSource.java:150)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:97)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:202)
,08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:119)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:796)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:405)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:349)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:517)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:797)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:762)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dja.a(:com.google.android.gms:233)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-26 10:52:31.076  1975  6928 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
,08-26 10:52:31.086  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 10:52:31.086  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 10:52:31.086  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:31.086  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 10:52:31.086  1018  1126 D WifiP2pService: P2pDisablingState
,08-26 10:52:31.086  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 10:52:31.096  1018  1127 E WifiNative-wlan0: do suspend true
08-26 10:52:31.096  1018  1126 D WifiP2pService: p2p socket connection lost
08-26 10:52:31.096  1018  1126 D WifiP2pService: P2pDisabledState
,08-26 10:52:31.106  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-26 10:52:31.106  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 10:52:31.106  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 10:52:31.106  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:31.106  1018  1049 D WifiDisplayController: disconnect
,08-26 10:52:31.106  1018  1049 D WifiDisplayController: updateConnection
08-26 10:52:31.106  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:31.106  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 10:52:31.106  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:31.106  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 10:52:31.106  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 10:52:31.106  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:31.106  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 10:52:31.106  1018  1137 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:31.116  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 10:52:31.116  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 10:52:31.116  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-26 10:52:31.116  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:31.116  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:31.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.146  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 10:52:31.146  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 10:52:31.146  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:31.146  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 10:52:31.146  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-26 10:52:31.146  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:31.146   278   991 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:31.146  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.146  1018  1129 V NetworkStats: performPollLocked() took 7ms
08-26 10:52:31.146  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.146  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 10:52:31.146  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.156  1172  1716 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 10:52:31.156  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 10:52:31.156  1387  1387 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 10:52:31.156  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 10:52:31.156  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 10:52:31.156  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-26 10:52:31.156  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-26 10:52:31.156  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 10:52:31.166  1018  1755 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 10:52:31.166  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:31.166  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 10:52:31.166  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:31.166  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:31.166  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.166  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.166  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.166  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.166  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 10:52:31.166  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:31.166  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:31.176  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:31.176  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:31.176  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.176  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.176  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.176  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.176  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:31.176  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 10:52:31.176  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:31.176  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 10:52:31.176  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:31.176  1172  1172 D HotspotTile: onReceive : 0, 0
,08-26 10:52:31.176  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:31.176  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:31.176  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:31.176  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:31.176  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:31.176  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:31.186  1018  1124 V NetworkStats: updateIfacesLocked(),
,08-26 10:52:31.176  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:31.186  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:31.186  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:31.186  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:31.186  1018  1124 V NetworkStats: performPollLocked() took 4ms
,08-26 10:52:31.186  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 10:52:31.186  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 10:52:31.186  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 10:52:31.196  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:31.196  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:31.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.196  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.236  1018  1475 I art     : Explicit concurrent mark sweep GC freed 42355(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/36MB, paused 2.705ms total 190.334ms
,08-26 10:52:31.236  1975  3021 V NativeCrypto: SSL shutdown failed: ssl=0xb7ef59b8: I/O error during system call, Broken pipe
,08-26 10:52:31.236  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 10:52:31.246  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 10:52:31.246  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 10:52:31.246  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 10:52:31.246  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:31.246  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:31.246  1975  3021 E GCM     : Wifi connection closed with errorCode 20
,08-26 10:52:31.246  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.246  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 10:52:31.246  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding GattService
,08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding A2dpService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding HidService
,08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding HealthService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding PanService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding SapService
,08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding SapClientService
08-26 10:52:31.256  7036  7036 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 10:52:31.256  7036  7036 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 10:52:31.256  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
08-26 10:52:31.256  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 10:52:31.256  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 10:52:31.256  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 10:52:31.256  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-26 10:52:31.266  1018  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-26 10:52:31.266  1018  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.266  1018  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.266  1018  1467 D SettingsProvider: selectionArgs: false
08-26 10:52:31.266  1018  1467 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.266  1018  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.266  1018  1467 D SettingsProvider: ret = -1
,08-26 10:52:31.266  1018  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 10:52:31.266  1018  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.266  1018  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.266  1018  1481 D SettingsProvider: selectionArgs: false
08-26 10:52:31.266  1018  1481 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.266  1018  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.266  1018  1481 D SettingsProvider: ret = -1
,08-26 10:52:31.266  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 10:52:31.266  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.266  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.266  1018  1030 D SettingsProvider: selectionArgs: false
08-26 10:52:31.266  1018  1030 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.266  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.266  1018  1030 D SettingsProvider: ret = -1
,08-26 10:52:31.266  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 10:52:31.266  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.266  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.266  1018  1031 D SettingsProvider: selectionArgs: false
08-26 10:52:31.266  1018  1031 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.266  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.266  1018  1031 D SettingsProvider: ret = -1
,08-26 10:52:31.266  1018  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 10:52:31.266  1018  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.266  1018  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.266  1018  1475 D SettingsProvider: selectionArgs: false
08-26 10:52:31.266  1018  1475 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.266  1018  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.266  1018  1475 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 10:52:31.276  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1137 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1137 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1137 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 10:52:31.276  1018  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1483 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1483 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1483 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1030 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 10:52:31.276  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1030 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1030 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1030 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:31.276  1018  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1328 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1328 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1328 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  4352 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:31.276  1018  4352 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  4352 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  4352 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  4352 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  4352 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  4352 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1266 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 10:52:31.276  1018  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:31.276  1018  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1266 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1266 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1266 D SettingsProvider: ret = -1
,08-26 10:52:31.276  1018  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-26 10:52:31.276  1018  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 10:52:31.276  1018  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:31.276  1018  1467 D SettingsProvider: selectionArgs: false
08-26 10:52:31.276  1018  1467 D SettingsProvider: selectionArgs: 1002
08-26 10:52:31.276  1018  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:31.276  1018  1467 D SettingsProvider: ret = -1
,08-26 10:52:31.306  1975  2173 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-26 10:52:31.306  1387  1387 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 10:52:31.306  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 10:52:31.306  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-26 10:52:31.306  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:31.316  1975  2173 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 10:52:31.316  1975  2173 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 10:52:28.080+0200, stopTime=2016-08-26 10:52:31.322+0200, duration=3242ms
,08-26 10:52:31.326  1975  7063 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:31.326   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 10:52:31.326   278   987 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 10:52:31.326  1387  1387 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 10:52:31.326  1387  1387 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 10:52:31.336  1387  1387 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 10:52:31.336  1387  1387 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 10:52:31.336  1387  1387 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 10:52:31.336  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:31.336  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:31.336  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:31.336  1018  1132 D Tethering: InitialState.processMessage what=4
,08-26 10:52:31.336  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 10:52:31.336  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:31.336  1018  1132 E Tethering: No numeric data
08-26 10:52:31.336  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:31.336  1018  1132 D Tethering: clearTetheredNotification()
,08-26 10:52:31.336  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:31.336  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:31.336  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 10:52:31.336  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:31.336  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:31.346  1018  1124 V NetworkStats: performPollLocked(flags=0x1),
08-26 10:52:31.346  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.346  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:31.346  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:31.346  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 10:52:31.346  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:31.346  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:31.346  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:31.346  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-26 10:52:31.346  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:31.346  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.346  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:31.346  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:31.356  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:31.356  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:31.366  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.366  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.366  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.366  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.366  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.366  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.376  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.376  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.376  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.376  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.376  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.386  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.386  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-26 10:52:31.386  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 10:52:31.386  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.386  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.386  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 10:52:31.386   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8c587c8
08-26 10:52:31.386   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-26 10:52:31.386   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 10:52:31.386   271   315 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1195014856),
,08-26 10:52:31.386  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 10:52:31.396  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.396  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.396  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.396  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 10:52:31.396  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.396  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 10:52:31.396  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 10:52:31.406  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.406  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.406  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 10:52:31.406  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 10:52:31.406  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 10:52:31.416   288   288 E SMD     : DCD OFF
,08-26 10:52:31.426  1975  1975 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
,08-26 10:52:31.426  1975  2173 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 10:52:31.426  1975  7081 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 10:52:31.426  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:31.436  1018  1137 I ActivityManager: Killing 6599:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 10:52:31.436  1018  1467 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:31.436   271   315 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-26 10:52:31.436   271   315 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 10:52:31.436   271   315 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1195014856) wakelock released: 1, error no: 0
08-26 10:52:31.436   271   315 I rmt_storage: 
,08-26 10:52:31.446   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8c587c8
,08-26 10:52:31.446  1018  1467 W ActivityManager: userId = 0, bbcId = -10000,
08-26 10:52:31.446  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:31.446  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:31.456  1018  1328 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:31.456  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:31.456  1018  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:31.456  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:31.456  1018  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 10:52:31.456  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 10:52:31.466  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:31.466  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:31.466  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 10:52:31.466  1618  1618 I Hs20UtilService: Starting #8
08-26 10:52:31.466  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:31.466  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 10:52:31.466  1975  7081 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 10:52:31.466  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:31.466  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:31.466  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:31.466  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:31.466  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:31.466  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:31.476  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 10:52:31.476  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:31.476  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:31.486  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 10:52:31.486  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:31.486  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 10:52:31.486  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:31.486  1018  1266 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 10:52:31.486  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:31.486  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:31.486  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:31.486  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:31.506  7083  7083 E Zygote  : MountEmulatedStorage()
,08-26 10:52:31.506  7083  7083 I libpersona: KNOX_SDCARD checking this for 10064
08-26 10:52:31.506  7083  7083 E Zygote  : v2
08-26 10:52:31.506  1018  1266 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7083 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:31.506  7083  7083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:31.506  7083  7083 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:31.516  7083  7083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 10:52:31.516  7083  7083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 10:52:31.526  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:31.536  7083  7083 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:31.546  7083  7083 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 10:52:31.556  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 10:52:31.566  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 10:52:31.566  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
,08-26 10:52:31.586  7083  7083 D FileShare-Client: Outbound.stopDelayTimer - ,
08-26 10:52:31.586  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 10:52:31.596  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:31.596  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:31.596  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:31.596  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:31.606  7098  7098 E Zygote  : MountEmulatedStorage(),
,08-26 10:52:31.606  7098  7098 E Zygote  : v2,
08-26 10:52:31.606  7098  7098 I libpersona: KNOX_SDCARD checking this for 10065
08-26 10:52:31.606  7098  7098 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:31.606  7098  7098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:31.606  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7098 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:31.616  7098  7098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 10:52:31.616  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:31.616  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:31.616  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-26 10:52:31.616  7098  7098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:31.616  1387  1387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 10:52:31.646  7098  7098 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:31.646  7098  7098 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:31.676  7098  7098 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:31.676  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:31.686  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-26 10:52:31.696  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:31.696  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:31.696  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:31.696  1018  1137 I ActivityManager: Killing 6580:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 10:52:31.706  1018  1328 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 10:52:31.706  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:31.706  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:31.706  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:31.706  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:31.706  1618  1618 I Hs20UtilService: Starting #9
08-26 10:52:31.706  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:31.706  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 10:52:31.706  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 10:52:31.706  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:31.716  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:31.716  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:31.716  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:31.716  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:31.726  1018  4352 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 10:52:31.726  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:31.726  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:31.726  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:31.726  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:31.726  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 10:52:31.726  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 10:52:31.726  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 10:52:31.726  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:31.726  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 10:52:31.736  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:31.736  1618  1618 I Hs20UtilService: Starting #10
,08-26 10:52:31.736  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:31.736  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:31.736  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.736  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.736  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:31.736  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:31.736  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:31.736  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:31.736  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 10:52:31.736  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:31.736  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 10:52:31.736  1172  1172 D HotspotTile: onReceive : 1, 0
,08-26 10:52:31.736  1975  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:31.736  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:31.746  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:31.746  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:31.756  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:31.756  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:31.756  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:32.106  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.106  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:32.106  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 10:52:32.106  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 10:52:32.106  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.106  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.106  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.106  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.116  1018  1018 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7113 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,08-26 10:52:32.116  7113  7113 E Zygote  : MountEmulatedStorage()
08-26 10:52:32.116  7113  7113 E Zygote  : v2
08-26 10:52:32.116  7113  7113 I libpersona: KNOX_SDCARD checking this for 10102
08-26 10:52:32.116  7113  7113 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.116  7113  7113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.126  7113  7113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 10:52:32.126  7113  7113 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 10:52:32.136  7113  7113 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:32.136  7113  7113 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.156  7113  7113 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 10:52:32.326  1018  1046 D Tethering: interfaceRemoved wlan0
,08-26 10:52:32.326  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 10:52:32.396  7113  7133 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 10:52:32.396  7113  7133 I Babel_SMS: MmsConfig.loadMmsSettings
08-26 10:52:32.396  7113  7133 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 10:52:32.396  7113  7133 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 10:52:32.436  7113  7133 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-26 10:52:32.436  7113  7133 I Babel_SMS: MmsConfig.loadFromResources
,08-26 10:52:32.446  7113  7133 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 10:52:32.446  7113  7133 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 10:52:32.456  1018  4342 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 10:52:32.456  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 10:52:32.456  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:32.456  1018  4342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:32.456  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 10:52:32.466  1018  1046 D Tethering: interfaceRemoved p2p0
08-26 10:52:32.466  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 10:52:32.476  7113  7113 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:32.486  7113  7113 I Babel_Crash: startup - clean
,08-26 10:52:32.506  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.506  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.506  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.516  1018  1018 W ActivityManager: userId = 0, bbcId = -10000,
08-26 10:52:32.516  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.516  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.516  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.516  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.516  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.526  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:32.526  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.526  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.526  7113  7113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 10:52:32.526  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:32.526  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.526  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.526  7113  7113 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 10:52:32.536  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.536  7113  7113 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 10:52:32.536  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.536  7113  7113 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 10:52:32.536  7113  7113 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 10:52:32.536  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.536  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.546  7113  7113 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 10:52:32.546  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.546  7113  7113 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 10:52:32.546  7113  7113 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 10:52:32.546  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.546  7113  7113 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 10:52:32.546  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.546  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.556  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.556  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.556  7113  7113 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 10:52:32.556  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:32.556  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 10:52:32.556  7113  7113 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 10:52:32.556  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 10:52:32.566  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.566  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.566  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.566  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.576  7113  7113 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
08-26 10:52:32.576  7136  7136 E Zygote  : MountEmulatedStorage()
08-26 10:52:32.576  7136  7136 I libpersona: KNOX_SDCARD checking this for 1000
08-26 10:52:32.576  7136  7136 E Zygote  : v2
08-26 10:52:32.576  7136  7136 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.576  7136  7136 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:32.576  7113  7113 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 10:52:32.576  7136  7136 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:32.576  7136  7136 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:32.576  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7136 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 10:52:32.586  7113  7113 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 10:52:32.586  7113  7113 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 10:52:32.596  7113  7113 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 10:52:32.596  7113  7113 W VideoCapabilities: Unsupported mime video/mp43
,08-26 10:52:32.596  7113  7113 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 10:52:32.606  7113  7113 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 10:52:32.606   323   323 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 28.144ms
,08-26 10:52:32.606  7136  7136 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:32.606  7136  7136 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.626  7113  7113 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 10:52:32.626   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.602ms
,08-26 10:52:32.646   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.452ms
,08-26 10:52:32.646  7136  7136 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 10:52:32.646  7136  7136 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 10:52:32.646  7136  7136 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 10:52:32.646  7113  7113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 10:52:32.656  7113  7113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 10:52:32.656  7113  7113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-26 10:52:32.656  7113  7113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 10:52:32.666  7136  7136 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 10:52:32.666  7136  7136 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 10:52:32.666  7136  7136 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 10:52:32.666  1018  4352 I ActivityManager: Killing 6649:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-26 10:52:32.666  7136  7136 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:32.666  7113  7113 I vclib   : onServiceConnected
,08-26 10:52:32.666  1018  1137 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-26 10:52:32.666  1018  1137 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 10:52:32.666  1018  1137 I ActivityManager: Killing 6666:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 10:52:32.676  7136  7153 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 10:52:32.676  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 10:52:32.676  1792  1792 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-26 10:52:32.676  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.676  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.676  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.676  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.686  7155  7155 E Zygote  : MountEmulatedStorage(),
08-26 10:52:32.686  7155  7155 E Zygote  : v2
08-26 10:52:32.686  7155  7155 I libpersona: KNOX_SDCARD checking this for 10121
,08-26 10:52:32.686  7155  7155 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.696  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.696  1018  1044 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7155 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-26 10:52:32.696  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:32.696  1018  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-26 10:52:32.696  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.696  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:32.696  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.696  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.696  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.716  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:32.716  7155  7155 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.716  7170  7170 E Zygote  : MountEmulatedStorage(),
08-26 10:52:32.716  7170  7170 E Zygote  : v2
08-26 10:52:32.716  7170  7170 I libpersona: KNOX_SDCARD checking this for 10031
,08-26 10:52:32.716  7170  7170 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.726  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.726  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:32.726  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:32.726  1018  1328 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7170 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,08-26 10:52:32.736  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 10:52:32.746  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.746  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.746  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.746  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.746  2604  6066 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-26 10:52:32.756  7155  7155 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:32.756  7155  7155 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 10:52:32.756  7155  7155 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:32.756  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 10:52:32.756  7170  7170 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.756  7185  7185 E Zygote  : MountEmulatedStorage(),
08-26 10:52:32.756  7185  7185 E Zygote  : v2
08-26 10:52:32.756  7185  7185 I libpersona: KNOX_SDCARD checking this for 10001,
08-26 10:52:32.756  7185  7185 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.766  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.766  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 10:52:32.766  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7185 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:32.766  1792  1792 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-26 10:52:32.766  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:32.766  1792  1792 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 10:52:32.766  1792  1792 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 10:52:32.766  1792  1792 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 10:52:32.776  7155  7155 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:32.786  1792  1792 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-26 10:52:32.786  7155  7155 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 10:52:32.786  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:32.786  7185  7185 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.786  1792  1792 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 10:52:32.786  7155  7155 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-26 10:52:32.786  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 10:52:32.786  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.786  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.786  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.786  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.796  7200  7200 E Zygote  : MountEmulatedStorage()
,08-26 10:52:32.796  7200  7200 E Zygote  : v2
08-26 10:52:32.796  7200  7200 I libpersona: KNOX_SDCARD checking this for 10077,
08-26 10:52:32.806  7200  7200 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.806  7200  7200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.806  1018  1137 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7200 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:32.806  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 10:52:32.806  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.806  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.806  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.806  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.806  7200  7200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:32.806  7200  7200 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 10:52:32.826  7210  7210 E Zygote  : MountEmulatedStorage()
,08-26 10:52:32.826  7210  7210 E Zygote  : v2
08-26 10:52:32.826  7210  7210 I libpersona: KNOX_SDCARD checking this for 10141
08-26 10:52:32.826  7210  7210 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.826  7210  7210 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.826  1018  1137 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7210 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-26 10:52:32.826  1018  1137 I ActivityManager: Killing 6678:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 10:52:32.826  7210  7210 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:32.836  7210  7210 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:32.836  7170  7170 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 10:52:32.846  1018  1266 I ActivityManager: Killing 6698:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 10:52:32.846  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:32.846  7200  7200 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.866  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:32.866  7210  7210 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:32.876  1018  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 10:52:32.876  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.876  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.876  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:32.876  1018  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:32.876  2779  7230 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 10:52:32.886  7210  7210 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 10:52:32.886  7210  7210 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:32.886  7210  7210 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 10:52:32.886  7210  7210 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 10:52:32.886  2779  7230 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 10:52:32.886  2779  7230 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 10:52:32.896  2779  7230 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 10:52:32.896  2779  7230 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 10:52:32.906  7232  7232 E Zygote  : MountEmulatedStorage(),
08-26 10:52:32.906  7232  7232 E Zygote  : v2
,08-26 10:52:32.906  7232  7232 I libpersona: KNOX_SDCARD checking this for 10032
08-26 10:52:32.906  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:32.906  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:32.906  1018  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 10:52:32.906  1018  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 10:52:32.906  1018  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 10:52:32.906  1018  1483 D BatteryService: stay LED for fully charged
08-26 10:52:32.906  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 10:52:32.906  1018  1484 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7232 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:32.906  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 10:52:32.916  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 10:52:32.916  1018  1018 I MotionRecognitionService: Plugged,
08-26 10:52:32.916  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 10:52:32.916  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 10:52:32.916  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 10:52:32.916  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 10:52:32.916  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 10:52:32.946  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 10:52:32.946  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:32.946  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:32.956  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:32.956  7232  7232 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.006  1018  4352 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.016  1018  1484 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.026  7232  7248 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 10:52:33.026  7232  7248 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 10:52:33.036  7232  7248 D SPPClientService: PushLog.txt file is not deleted.
08-26 10:52:33.036  7232  7248 D SPPClientService: PushLog.txt file is not deleted.
08-26 10:52:33.036  7232  7248 D SPPClientService: ============PushLog. stop!
,08-26 10:52:33.046  7232  7232 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 10:52:33.046  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 10:52:33.046  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.046  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.046  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.046  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.056  7252  7252 E Zygote  : MountEmulatedStorage()
,08-26 10:52:33.056  7252  7252 I libpersona: KNOX_SDCARD checking this for 10036
08-26 10:52:33.056  7252  7252 E Zygote  : v2
08-26 10:52:33.056  7252  7252 I libpersona: KNOX_SDCARD not a persona,
08-26 10:52:33.056  7252  7252 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:33.066  1018  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7252 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:33.066  1018  1030 I ActivityManager: Killing 6618:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-26 10:52:33.066  1018  1475 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 10:52:33.066  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.066  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:33.066  1018  1475 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 10:52:33.066  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-26 10:52:33.066  7252  7252 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:33.066  7252  7252 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 10:52:33.066  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
08-26 10:52:33.066   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:33.086  1018  1498 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.086  7252  7252 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:33.086  7252  7252 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.136  7252  7252 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@338cc765
,08-26 10:52:33.146  1018  1328 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 10:52:33.146  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.146  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.146  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.146  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.156  7252  7252 I SA      : [SSP] onCreated
,08-26 10:52:33.166  1018  1481 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.166  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.166  7274  7274 E Zygote  : MountEmulatedStorage()
,08-26 10:52:33.166  7274  7274 E Zygote  : v2
08-26 10:52:33.166  7274  7274 I libpersona: KNOX_SDCARD checking this for 10068
08-26 10:52:33.166  7274  7274 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:33.176  1018  1328 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7274 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 10:52:33.176  7274  7274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:33.176  7274  7274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:33.176  7274  7274 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 10:52:33.186  7252  7252 I SA      : [TPM] There is no property file
,08-26 10:52:33.196  7252  7252 I SA      : [SCU] isHaveSA() - false
,08-26 10:52:33.196  7274  7274 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:33.196  7252  7252 I SA      : [TPM] getModelProperty : null
08-26 10:52:33.196  7252  7252 I SA      : [TPM] getCSCProperty : null
08-26 10:52:33.196  7274  7274 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.196  7252  7252 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 10:52:33.196  7252  7252 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 10:52:33.196  7252  7252 I SA      : [DM] TFT FEATURE: false
,08-26 10:52:33.196  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 10:52:33.196  7232  7261 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 10:52:33.206  7252  7252 I SA      : [DM] init START
,08-26 10:52:33.216  7252  7252 I SA      : [DM] This device is not a Vodafone
,08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 10:52:33.216  7252  7252 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 10:52:33.226  7274  7274 D BadgeProvider: onCreate
,08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 10:52:33.226  7274  7274 D BadgeProvider: DatabaseHelper
,08-26 10:52:33.226  7252  7252 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:52:33.226  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-26 10:52:33.226  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-26 10:52:33.226  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-26 10:52:33.226  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-26 10:52:33.226  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 10:52:33.226  7252  7252 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75),
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 10:52:33.236  7252  7252 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 10:52:33.236  7295  7295 E Zygote  : MountEmulatedStorage()
08-26 10:52:33.236  7295  7295 I libpersona: KNOX_SDCARD checking this for 1000
08-26 10:52:33.236  7295  7295 E Zygote  : v2
08-26 10:52:33.236  7295  7295 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:33.236  7295  7295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:33.246  7252  7252 I SA      : [SCU] isHaveSA() - false
08-26 10:52:33.246  7252  7252 I SA      : support phone number id : false
08-26 10:52:33.246  7252  7252 I SA      : [DM] Supports Ref Jpn : true
08-26 10:52:33.246  7252  7252 I SA      : [DM] init END
08-26 10:52:33.246  7252  7252 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-26 10:52:33.246  7295  7295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:33.246  7295  7295 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:33.246  1018  1030 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7295 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 10:52:33.246  1018  1030 I ActivityManager: Killing 6112:com.android.mms/u0a41 (adj 15): empty #21
08-26 10:52:33.246  7252  7252 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 10:52:33.246  7252  7252 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 10:52:33.256  7252  7252 I SA      : [SLFUCHKMGR] constructor called
,08-26 10:52:33.266  7274  7288 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 10:52:33.276  7295  7295 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:33.276  7252  7252 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 10:52:33.276  7252  7252 I SA      : [OR] == isSIMCardReady false ==
,08-26 10:52:33.276  7295  7295 D ActivityThread: Added TimaKeyStore provider
08-26 10:52:33.276  7274  7288 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 10:52:33.276  7274  7288 D BadgeProvider: sendNotify, [notify] : null
08-26 10:52:33.276  7274  7288 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 10:52:33.276  7274  7288 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 10:52:33.276  7274  7288 D BadgeProvider: update, [UpdateCount] : 1
08-26 10:52:33.276  1485  1485 D Launcher.Model: reloadBadges entered.
,08-26 10:52:33.286  1018  1498 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 10:52:33.286  1018  1498 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 10:52:33.286  1018  1498 D SecContentProvider2: mCursor = null
,08-26 10:52:33.286  1018  1498 D WifiService: setWifiEnabled: true pid=6847, uid=10171
08-26 10:52:33.286  1018  1498 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 10:52:33.286  1018  1498 W WifiService: Failed getting userId using ActivityManagerNative
08-26 10:52:33.286  1018  1498 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:33.286  1018  1498 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 10:52:33.286  1018  1498 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 10:52:33.286  1018  1498 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 10:52:33.286  1018  1498 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 10:52:33.286  1018  1498 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:33.286  1018  1481 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.286  1018  1498 D SettingsProvider: name = wifi_on
,08-26 10:52:33.296  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:33.306  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 10:52:33.306  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.306  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.306  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.306  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.316  7313  7313 E Zygote  : MountEmulatedStorage()
08-26 10:52:33.316  7313  7313 I libpersona: KNOX_SDCARD checking this for 10009
,08-26 10:52:33.316  7313  7313 E Zygote  : v2
08-26 10:52:33.316  7313  7313 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:33.316  1018  1481 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7313 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 10:52:33.316  1018  1481 I ActivityManager: Killing 6743:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 10:52:33.316  1018  1481 I ActivityManager: Killing 6726:com.sec.esdk.elm/u0a90 (adj 15): empty #22
08-26 10:52:33.316  7313  7313 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:33.326  7313  7313 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 10:52:33.326  7313  7313 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 10:52:33.336  7252  7252 I SA      : [SCU] == networkStateCheck == false
08-26 10:52:33.336  7252  7252 I SA      : [OR] onReceive END
,08-26 10:52:33.336  1018  1137 I ActivityManager: Killing 6566:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 10:52:33.346  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:33.346  1018  1030 D CountryDetector: No listener is left
,08-26 10:52:33.356  7295  7295 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 10:52:33.356  7313  7313 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:33.356  7313  7313 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.376  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 10:52:33.376  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.376  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:33.376  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:33.376  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 10:52:33.376  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 10:52:33.396  1018  1467 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 10:52:33.396  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.396  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.396  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.396  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.416  1018  1467 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7330 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 10:52:33.416  7330  7330 E Zygote  : MountEmulatedStorage()
08-26 10:52:33.416  7330  7330 E Zygote  : v2
08-26 10:52:33.416  7330  7330 I libpersona: KNOX_SDCARD checking this for 10110
08-26 10:52:33.416  7330  7330 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:33.416  7330  7330 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:33.416  7330  7330 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:33.416  7330  7330 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 10:52:33.416  1018  1475 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 10:52:33.416  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.426  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:33.426  1018  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:33.426  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 10:52:33.436   323   323 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 23.974ms,
,08-26 10:52:33.446  7113  7329 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 10:52:33.456  7330  7330 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:33.456  7330  7330 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.456   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 696us total 18.999ms
,08-26 10:52:33.486   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 18.038ms
,08-26 10:52:33.516  1018  1475 I ActivityManager: Killing 6758:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-26 10:52:33.516  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:33.516  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.516  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:33.516  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:33.516  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:33.526  7295  7295 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 10:52:33.536  4835  7346 I iu.SyncManager: SYNC; picasa accounts
,08-26 10:52:33.546  4835  4835 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 10:52:33.546  7295  7295 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 10:52:33.546  7295  7295 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:33.546  7295  7295 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 10:52:33.546  7295  7295 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 10:52:33.546  7295  7295 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 10:52:33.556  1018  1483 I ActivityManager: Killing 6075:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 10:52:33.556  1975  2173 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-26 10:52:33.556  1975  2173 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-26 10:52:33.556  1018  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 10:52:33.556  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.556  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.556  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:33.556  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:33.566  7348  7348 E Zygote  : MountEmulatedStorage(),
08-26 10:52:33.566  7348  7348 E Zygote  : v2
08-26 10:52:33.576  7348  7348 I libpersona: KNOX_SDCARD checking this for 10008
08-26 10:52:33.576  7348  7348 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:33.576  7348  7348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:33.576  7348  7348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 10:52:33.576  7348  7348 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 10:52:33.576  1018  1328 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7348 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:33.586  1018  1328 I ActivityManager: Killing 6798:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-26 10:52:33.596  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 10:52:33.596  1018  4342 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 10:52:33.606  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.606  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.606  7348  7348 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:33.606  7348  7348 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:33.676  1018  1481 I ActivityManager: Killing 5874:com.android.vending/u0a26 (adj 15): empty #21
,08-26 10:52:33.686  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 10:52:33 GMT+02:00 2016
,08-26 10:52:33.686  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 10:52:33.686  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:33.686  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:33.686  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:33.686  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 10:52:33.696  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 10:52:33.696  2914  2914 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 10:52:33.696  2914  2914 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 10:52:33.706  2914  2914 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 10:52:33.706  2914  7363 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 10:52:33.706  2914  7363 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:33.716  2914  7363 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 10:52:33.716  1018  1097 V AlarmManager: waitForAlarm result :4
,08-26 10:52:33.716  2914  7363 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 10:52:33.716  2914  2914 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 10:52:33.746  1018  1484 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 10:52:33.856   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 10:52:33.856   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:33.856  1018  1046 D Tethering: interfaceAdded wlan0
,08-26 10:52:33.866  7330  7373 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 10:52:33.866  1018  1132 E Tethering: No numeric data
,08-26 10:52:33.866  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:52:33.866  1018  1132 D Tethering: clearTetheredNotification()
,08-26 10:52:33.866  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:33.866  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:33.866  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:33.866  1018  1132 D Tethering: InitialState.processMessage what=4
,08-26 10:52:33.876   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 10:52:33.876   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:33.876  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:33.876  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:33.876  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:33.876  7330  7373 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
08-26 10:52:33.876  1172  1172 D HotspotTile: updateTetherState():false, false
08-26 10:52:33.876  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:33.876  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:33.876  1018  1132 E Tethering: No numeric data
,08-26 10:52:33.876  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:33.876  1018  1132 D Tethering: clearTetheredNotification()
,08-26 10:52:33.876  1018  1046 D Tethering: interfaceAdded p2p0
,08-26 10:52:33.876  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 10:52:33.886  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-26 10:52:33.886  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.886  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 10:52:33.886  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:33.886  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:33.886  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.886  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 10:52:33.886  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-26 10:52:33.886  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:33.886  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:33.886  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 10:52:33.886  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:33.886  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.886   278   991 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 10:52:33.896   278   991 D SoftapController: Softap fwReload - Ok
08-26 10:52:33.896  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-26 10:52:33.896  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.896  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.896   278   991 D CommandListener: Setting iface cfg
08-26 10:52:33.896   278   991 D CommandListener: Trying to bring down wlan0
08-26 10:52:33.896  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:33.896   278   991 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:33.896   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 10:52:33.896   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:33.896  7330  7374 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 10:52:33.896  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 10:52:33.906  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 10:52:33.906  1018  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-26 10:52:33.906   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 10:52:33.906   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:33.916  7330  7374 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 10:52:33.916  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:33.916  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:33.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:33.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:33.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:33.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:33.916  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:33.916  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 10:52:33.916  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:33.916  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 10:52:33.916  7330  7330 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 10:52:33.916  7330  7330 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 10:52:33.916  7330  7330 I GAv4    :   adb logcat -s GAv4
,08-26 10:52:33.916  1172  1172 D HotspotTile: onReceive : 2, 0
,08-26 10:52:33.916  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:33.916  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:33.916  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:33.946  7330  7330 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:33.946  1018  1467 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 10:52:33.966  7330  7330 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:33.976  7376  7376 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 10:52:33.976  7376  7376 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 10:52:33.976  7376  7376 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 10:52:33.976  7330  7378 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:33.986  7376  7376 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 10:52:33.996   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7376
08-26 10:52:33.996   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 10:52:33.996  7376  7376 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 10:52:33.996  7376  7376 I wpa_supplicant: ssSupport state is = 1
08-26 10:52:33.996  7376  7376 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 10:52:33.996  7376  7376 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 10:52:33.996   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7376
08-26 10:52:33.996   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 10:52:34.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:34.186   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-26 10:52:34.186  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-26 10:52:34.226  1018  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:34.226  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:34.226  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:34.226  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 10:52:34.236  7376  7376 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 10:52:34.236  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 10:52:34.246  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 10:52:34.246   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7376
08-26 10:52:34.246   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 10:52:34.246  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 10:52:34.246  7376  7376 I wpa_supplicant: ssSupport state is = 1
,08-26 10:52:34.246  7330  7330 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 10:52:34.256  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 10:52:34.256  7376  7376 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:34.256  7376  7376 E wpa_supplicant: SIM READ ERROR
08-26 10:52:34.256  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:34.256  7376  7376 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:34.256  7376  7376 E wpa_supplicant: SIM READ ERROR
08-26 10:52:34.256  7376  7376 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 10:52:34.256  7376  7376 I wpa_supplicant: wpa_default_ap_write_once
08-26 10:52:34.256  7376  7376 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 10:52:34.256  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:34.256  7376  7376 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 10:52:34.256  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:34.256  7376  7376 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 10:52:34.256  7376  7376 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 10:52:34.256  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 10:52:34.256  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-26 10:52:34.256  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:34.276  7330  7330 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7657-7659)
,08-26 10:52:34.276  7330  7330 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 10:52:34.276  7330  7330 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {40bc7b4}
,08-26 10:52:34.276  7330  7330 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 10:52:34.276  7330  7330 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 10:52:34.296  7330  7330 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 10:52:34.296  7330  7330 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:34.306  7330  7330 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 10:52:34.316  7330  7330 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 10:52:34.316  7330  7330 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 10:52:34.316  7330  7330 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 10:52:34.316  7330  7330 I Adreno-EGL: Local Branch: 
08-26 10:52:34.316  7330  7330 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 10:52:34.316  7330  7330 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 10:52:34.316  7330  7330 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 10:52:34.346  7376  7376 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 10:52:34.386  7330  7408 W cr.media: Requires BLUETOOTH permission
,08-26 10:52:34.386  7330  7330 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 10:52:34.396  7330  7330 I NSApplication: Starting up...
,08-26 10:52:34.396  1018  1328 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 10:52:34.406  1018  1266 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 10:52:34.406  1018  1467 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 10:52:34.406  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:34.406  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:34.406  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:34.416  1018  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:34.416   288   288 E SMD     : DCD OFF
,08-26 10:52:34.426  1018  1467 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7413 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:34.426  7413  7413 E Zygote  : MountEmulatedStorage()
08-26 10:52:34.426  7413  7413 E Zygote  : v2
08-26 10:52:34.426  7413  7413 I libpersona: KNOX_SDCARD checking this for 10117
08-26 10:52:34.426  7413  7413 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:34.426  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:34.426  1018  1467 I ActivityManager: Killing 7036:com.android.bluetooth/1002 (adj 15): empty #21
,08-26 10:52:34.436  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:34.436  1018  1467 I ActivityManager: Killing 6979:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #22
,08-26 10:52:34.436  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 10:52:34.456  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:34.456  7413  7413 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:34.476  7413  7413 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 10:52:34.516  7376  7376 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 10:52:34.516  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 10:52:34.536  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 10:52:34.536   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7376
08-26 10:52:34.536   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 10:52:34.536  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 10:52:34.536  7376  7376 I wpa_supplicant: ssSupport state is = 1
,08-26 10:52:34.536  7376  7376 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 10:52:34.536  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 10:52:34.546  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 10:52:34.546   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7376
08-26 10:52:34.546   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 10:52:34.546  7376  7376 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 10:52:34.546  7376  7376 I wpa_supplicant: ssSupport state is = 1
08-26 10:52:34.546  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:34.546  7376  7376 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:34.546  7376  7376 E wpa_supplicant: SIM READ ERROR
08-26 10:52:34.546  7376  7376 I wpa_supplicant: wpa_default_ap_write_once
08-26 10:52:34.546  7376  7376 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 10:52:34.546  7376  7376 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 10:52:34.546  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 10:52:34.546  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:34.556  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:34.556  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 10:52:34.556  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-26 10:52:34.556  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:34.676  7376  7376 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 10:52:34.676  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 10:52:34.836  7376  7376 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 10:52:34.836  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-26 10:52:34.836  7376  7376 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 10:52:34.836  1018  1030 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 10:52:34.836  1018  1030 I ActivityManager: Killing 6994:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 10:52:34.846  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:34.846  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:34.846  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:34.846  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:34.846  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:34.846  1618  1618 I Hs20UtilService: Starting #11
,08-26 10:52:34.846  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:34.856  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
,08-26 10:52:34.856  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:34.856  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
08-26 10:52:34.856  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:34.866  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 10:52:34.866  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:34.866  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:34.866  1018  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 10:52:34.866  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:34.866  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-26 10:52:34.866  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:34.866  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 10:52:34.866  1618  1618 I Hs20UtilService: Starting #12
08-26 10:52:34.866  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:34.876  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 10:52:34.876  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:34.876  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
08-26 10:52:34.876  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:34.906  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 10:52:34.906  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 10:52:34.906  7376  7376 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 10:52:34.906  7376  7376 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:34.916  7376  7376 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:34.916  7376  7376 E wpa_supplicant: SIM READ ERROR
08-26 10:52:34.916  7376  7376 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 10:52:34.936  7376  7376 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 10:52:34.946  7376  7376 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 10:52:34.946  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:34.946  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:34.946  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:34.946  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:34.946  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:34.946  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 10:52:34.946  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 10:52:34.946  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:34.946  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:34.946  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 10:52:34.956  1172  1172 D HotspotTile: onReceive : 3, 0
,08-26 10:52:34.956  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 10:52:34.956  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:34.956  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:34.956  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:34.956  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:34.956  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:34.956  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:34.956  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:34.956  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:34.956  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:34.956  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:34.956  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 10:52:34.956  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:34.956  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:34.956  1618  1618 I Hs20UtilService: Starting #13
,08-26 10:52:34.966  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:34.966  1018  1127 E WifiConfigStore: Not a HS20
,08-26 10:52:34.966  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 10:52:34.966  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:34.966  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
08-26 10:52:34.966  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 10:52:34.966  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 10:52:34.966  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 10:52:34.976  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-26 10:52:34.976  7376  7376 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 10:52:34.976  7376  7376 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 10:52:34.976  7376  7376 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 10:52:34.976  7376  7376 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 10:52:34.976  7376  7376 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 10:52:34.976  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 10:52:34.976  7376  7376 I wpa_supplicant: First Scan Start
08-26 10:52:34.976  7376  7376 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 10:52:34.976  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-26 10:52:34.976  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:34.976  1018  1127 I WifiNative-HAL: startHal
08-26 10:52:34.976  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5b188c
08-26 10:52:34.976  1018  1127 I WifiNative-HAL: Could not start hal
,08-26 10:52:34.976  7113  7113 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:34.976  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 10:52:34.976  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 10:52:34.976  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 10:52:34.976  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:34.976  1018  1151 I WifiNative-HAL: startHal
08-26 10:52:34.976  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9ea6f9bc
08-26 10:52:34.976  1018  1151 I WifiNative-HAL: Could not start hal
08-26 10:52:34.976  1018  1151 E WifiScanningService: could not start HAL
08-26 10:52:34.976  1018  1018 D RttService: SCAN_AVAILABLE : 3
,08-26 10:52:34.986  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 10:52:34.986  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 10:52:34.986  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 10:52:34.986  1018  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 10:52:34.986  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 10:52:34.986  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 10:52:34.986  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 10:52:34.986  7376  7376 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-26 10:52:34.986   278   991 D CommandListener: Setting iface cfg,
,08-26 10:52:34.986  7376  7376 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2pEnablingState
08-26 10:52:34.986   278   991 D CommandListener: Trying to bring up p2p0
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2pEnablingState{ what=143376 }
08-26 10:52:34.986  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 10:52:34.986  1018  1126 D WifiP2pService: DefaultState{ what=143376 }
08-26 10:52:34.986  7376  7376 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 },
08-26 10:52:34.986  1018  1127 E WifiStateMachine: Failed to set frequency band 0
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2p socket connection successful
08-26 10:52:34.986  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:34.986  1018  1126 D WifiP2pService: P2pEnabledState
08-26 10:52:34.986  1018  1127 D SecContentProvider2: mCursor = null
08-26 10:52:34.986  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 10:52:34.986  1018  1129 E ConnectivityService: updateNetworkInfo(),
,08-26 10:52:34.986  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-26 10:52:34.986  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:34.986  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 10:52:34.986  1018  1127 D SecContentProvider2: mCursor = null
08-26 10:52:34.986  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:34.986  1018  1049 D WifiDisplayController: disconnect
,08-26 10:52:34.986  1018  1049 D WifiDisplayController: updateConnection
08-26 10:52:34.986  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:34.986  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:34.996  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:34.996  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:34.996  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 10:52:34.996  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 10:52:34.996  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 10:52:34.996  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 10:52:34.996  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 10:52:34.996  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:34.996  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 10:52:34.996  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 10:52:35.006  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 10:52:35.006  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  secondary type: null
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  wps: 0
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  grpcapab: 0
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  devcapab: 0
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  status: 3
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  wfdInfo: null
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-26 10:52:35.006  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-26 10:52:35.006  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:35.006  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:35.006  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:35.006  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:35.006  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 10:52:35.006  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:35.006  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-26 10:52:35.006  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 10:52:35.006  7083  7083 D FileShare-Client: Outbound.stopDelayTimer - ,
,08-26 10:52:35.016  7098  7098 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:35.026  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 10:52:35.026  1018  1126 D WifiP2pService: InactiveState
,08-26 10:52:35.026  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-26 10:52:35.026  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 10:52:35.026  7376  7376 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 10:52:35.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:36.076   351   351 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 10:52:36.206  7376  7376 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
08-26 10:52:36.206  7376  7376 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 10:52:36.206  7376  7376 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-26 10:52:36.206  7376  7376 I wpa_supplicant: Trying to associate with  'G700'
08-26 10:52:36.206  7376  7376 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 10:52:36.206  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 10:52:36.206  1018  7438 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 10:52:36.236  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:36.236  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.346  7376  7376 E wpa_supplicant: Cmd 35605 not handled
,08-26 10:52:36.346  7376  7376 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 10:52:36.346  7376  7376 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 10:52:36.346  7376  7376 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 10:52:36.346  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 10:52:36.346  7376  7376 I wpa_supplicant: Associated with F4.99.3E
08-26 10:52:36.346  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.346  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-26 10:52:36.346  7376  7376 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 10:52:36.346  7376  7376 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-26 10:52:36.346  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 10:52:36.346  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:36.346  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.346  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.346  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:36.356  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.356  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:36.356  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:36.356  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 10:52:36.356  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-26 10:52:36.356  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 10:52:36.356  7376  7376 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 10:52:36.356  7376  7376 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 10:52:36.356  1018  1132 E Tethering: No numeric data
,08-26 10:52:36.356  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:52:36.356  1018  1132 D Tethering: clearTetheredNotification()
08-26 10:52:36.356  7376  7376 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 10:52:36.356  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 10:52:36.366  7376  7376 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:52:36.366  7376  7376 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 10:52:36.366  7376  7376 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-26 10:52:36.366  7376  7376 I wpa_supplicant: Blacklist: Clear (temp) ,
,08-26 10:52:36.366  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 10:52:36.366  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 10:52:36.366  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-26 10:52:36.366  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 10:52:36.366  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:36.366  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:36.366  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 10:52:36.366  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:36.376  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 10:52:36.376  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:36.376  1018  1124 V NetworkStats: performPollLocked() took 10ms
08-26 10:52:36.376  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:36.376  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 10:52:36.376  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:36.376  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:36.386  1018  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 10:52:36.386  1018  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 10:52:36.386  1018  1475 D SecContentProvider2: mCursor = null
08-26 10:52:36.386  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 10:52:36.386  1018  1475 D WifiService: setWifiEnabled: false pid=6847, uid=10171
,08-26 10:52:36.386  1018  1475 D SettingsProvider: name = wifi_on
,08-26 10:52:36.386  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 10:52:36.386  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-26 10:52:36.386  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:36.386  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 10:52:36.396  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:36.396  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:36.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-26 10:52:36.406  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-26 10:52:36.406  1018  1266 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 10:52:36.406  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-26 10:52:36.406  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:36.406  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:36.406  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:36.406  1618  1618 I Hs20UtilService: Starting #14
,08-26 10:52:36.406  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:36.416  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:36.416  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 10:52:36.416  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:36.416  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:36.416  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:36.416  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 10:52:36.416  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:36.416  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:36.426   278   991 D CommandListener: Setting iface cfg
,08-26 10:52:36.436  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 10:52:36.436  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:36.436  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.446  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:36.446  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.446  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:36.446  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.456  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:36.456  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:36.456  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.456  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.456  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.456  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.466  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:36.466  1018  1475 I ActivityManager: Killing 7136:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 10:52:36.476  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 10:52:36.476  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 10:52:36.476   278   991 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:36.476  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 10:52:36.476  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 10:52:36.476  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:36.476  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:36.476  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 10:52:36.476  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.476  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-26 10:52:36.476  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 10:52:36.476  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.476  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.476  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 10:52:36.476  1018  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 10:52:36.476  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:36.476  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-26 10:52:36.476   278   991 E Netd    : no such netId 503
08-26 10:52:36.486  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 10:52:36.486  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:36.486  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-26 10:52:36.486  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 10:52:36.486  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:36.486  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:36.486  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.486  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.486  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.486  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.486  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:36.486  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-26 10:52:36.486  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 10:52:36.486  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 10:52:36.486  1018  1018 D RttService: SCAN_AVAILABLE : 1
,08-26 10:52:36.486  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:36.486  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:36.486  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 10:52:36.496  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:36.496  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.496  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:36.496  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:36.496  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 10:52:36.496  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 10:52:36.496  1018  1266 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:36.496  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 10:52:36.496  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:36.496  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:36.496  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:36.496  1018  1129 V NetworkStats: performPollLocked() took 13ms
08-26 10:52:36.496  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:36.496  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:36.496  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 10:52:36.496  1018  1126 D WifiP2pService: P2pDisablingState
08-26 10:52:36.496  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 10:52:36.496  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:36.496  1018  1049 D WifiDisplayController: disconnect
08-26 10:52:36.496  1018  1049 D WifiDisplayController: updateConnection
08-26 10:52:36.496  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 10:52:36.496  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 10:52:36.496  1618  1618 I Hs20UtilService: Starting #15
,08-26 10:52:36.496  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:36.496  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-26 10:52:36.496  1018  1126 D WifiP2pService: p2p socket connection lost
08-26 10:52:36.496  1018  1126 D WifiP2pService: P2pDisabledState
,08-26 10:52:36.506  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 10:52:36.506  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-26 10:52:36.506  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:36.506  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:36.506  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:36.506  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 10:52:36.506  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 10:52:36.506  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 10:52:36.506  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 10:52:36.506  1018  1127 E WifiNative-wlan0: do suspend true
08-26 10:52:36.506  1018  4352 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 10:52:36.506  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-26 10:52:36.506  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 10:52:36.506  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 10:52:36.506  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 10:52:36.506  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:36.506  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:36.506  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 10:52:36.506  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:36.506  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:36.506  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 10:52:36.506  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 10:52:36.506  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:36.506  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 10:52:36.506  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002,
08-26 10:52:36.506  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
08-26 10:52:36.506   278   991 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:36.516  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:36.516  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:36.516  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.516  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.516  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.516  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.516  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 10:52:36.516  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:36.516  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:36.516  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:36.516  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:36.526  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 10:52:36.526  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 10:52:36.526  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:36.526  7376  7376 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 10:52:36.526  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 10:52:36.526  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:36.526  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.526  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.526  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.526  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:36.536  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:36.536  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:36.536  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:36.536  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:36.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:36.536  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:36.536  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 10:52:36.536  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 10:52:36.536  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:36.536  1172  1172 D HotspotTile: onReceive : 0, 0
,08-26 10:52:36.536  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:36.536  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:36.536  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:36.536  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:36.536  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:36.536  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:36.536  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:36.536  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:36.556  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:36.556  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 10:52:36.556  7083  7083 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 10:52:36.556  7098  7098 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:36.566  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 10:52:36.566  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:36.566  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:36.566  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:36.566  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:36.576  1618  1618 I Hs20UtilService: Starting #16
,08-26 10:52:36.576  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:36.576  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:36.576  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 10:52:36.576  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:36.576  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 10:52:36.576  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:36.576  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:36.576  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:36.586  1018  4342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 10:52:36.586  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:36.586  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:36.586  1018  4342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:36.586  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:36.586  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 10:52:36.586  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:36.586  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 10:52:36.586  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:36.596  1618  1618 I Hs20UtilService: Starting #17
,08-26 10:52:36.596  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:36.766  7376  7376 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 10:52:36.956  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 10:52:36.956  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 10:52:36.956  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-26 10:52:36.956  7376  7376 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 10:52:36.986  7376  7376 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-26 10:52:36.986  7376  7376 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 10:52:36.986  7376  7376 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
,08-26 10:52:36.986  7376  7376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
08-26 10:52:36.986  7376  7376 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 10:52:36.996  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.996  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:36.996  1018  1132 D Tethering: InitialState.processMessage what=4
08-26 10:52:36.996  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:36.996  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:36.996  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:36.996  1018  1132 E Tethering: No numeric data
,08-26 10:52:36.996  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 10:52:36.996  1018  1132 D Tethering: clearTetheredNotification()
08-26 10:52:36.996  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:37.006  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 10:52:37.006  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:37.006  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:37.006  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:37.006  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 10:52:37.006  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:37.006  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:37.006  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:37.006  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:37.016  1018  1124 V NetworkStats: performPollLocked() took 8ms
,08-26 10:52:37.016  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:37.016  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:37.016  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:37.276  7376  7376 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 10:52:37.346  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 10:52:37.346  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:37.346  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:37.376  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 10:52:37.376  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:37.376  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:37.376  7376  7376 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-26 10:52:37.416   288   288 E SMD     : DCD OFF,
,08-26 10:52:37.486  7113  7113 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:37.486  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 10:52:37.486  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 10:52:37.496  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:37.496  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 10:52:37.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:37.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:37.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:37.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:37.506  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:37.506  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 10:52:37.506  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:37.506  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 10:52:37.506  1975  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:37.506  1172  1172 D HotspotTile: onReceive : 1, 0
,08-26 10:52:37.516  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:37.516  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:37.516  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:37.526  1018  4352 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:37.526  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:37.526  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:37.526  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:37.526  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:37.526  1618  1618 I Hs20UtilService: Starting #18
,08-26 10:52:37.526  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:37.526  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 10:52:37.526  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 10:52:37.526  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 10:52:37.536  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:38.216  1018  1046 D Tethering: interfaceRemoved wlan0
,08-26 10:52:38.216  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 10:52:38.426  1018  1046 D Tethering: interfaceRemoved p2p0,
08-26 10:52:38.426  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 10:52:39.236  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 10:52:39.406  6847  6903 D BluetoothAdapter: enable()
,08-26 10:52:39.416  1018  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 10:52:39.416  1018  1137 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256),
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 10:52:39.416  1018  1137 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:39.416  1018  1137 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-26 10:52:39.416  1018  1137 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:39.416  1018  1137 D SettingsProvider: name = bluetooth_on
,08-26 10:52:39.426  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-26 10:52:39.426  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:39.426  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-26 10:52:39.426  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 10:52:39.436  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:39.436  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:39.436  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:39.436  1018  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:39.446  1018  1048 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7448 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 10:52:39.446  7448  7448 E Zygote  : MountEmulatedStorage(),
08-26 10:52:39.446  7448  7448 E Zygote  : v2
08-26 10:52:39.446  7448  7448 I libpersona: KNOX_SDCARD checking this for 1002
08-26 10:52:39.446  7448  7448 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:39.456  7448  7448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 10:52:39.456  7448  7448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 10:52:39.466  7448  7448 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 10:52:39.486  7448  7448 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:39.486  7448  7448 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:39.506  7448  7448 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 10:52:39.516  7448  7448 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:39.516  1018  3370 D SSRM:n  : SIOP:: AP = 340
,08-26 10:52:39.536  7448  7448 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding GattService
,08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding HidService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding HealthService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding PanService
,08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding SapService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding SapClientService
08-26 10:52:39.566  7448  7448 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 10:52:39.566  7448  7448 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 10:52:39.576  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 10:52:39.576  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:39.576  1018  1030 D SettingsProvider: selectionArgs: false
08-26 10:52:39.576  1018  1030 D SettingsProvider: selectionArgs: 1002
,08-26 10:52:39.576  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.576  1018  1030 D SettingsProvider: ret = -1
,08-26 10:52:39.576  1018  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
08-26 10:52:39.576  1018  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.576  1018  1467 D SettingsProvider: selectionArgs: false
,08-26 10:52:39.576  1018  1467 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.576  1018  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.576  1018  1467 D SettingsProvider: ret = -1
,08-26 10:52:39.576  1018  4352 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 10:52:39.576  1018  4352 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  4352 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.576  1018  4352 D SettingsProvider: selectionArgs: false
08-26 10:52:39.576  1018  4352 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.576  1018  4352 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.576  1018  4352 D SettingsProvider: ret = -1
,08-26 10:52:39.576  1018  1266 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 10:52:39.576  1018  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.576  1018  1266 D SettingsProvider: selectionArgs: false
08-26 10:52:39.576  1018  1266 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.576  1018  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:39.576  1018  1266 D SettingsProvider: ret = -1
,08-26 10:52:39.576  1018  1484 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 10:52:39.576  1018  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.576  1018  1484 D SettingsProvider: selectionArgs: false
08-26 10:52:39.576  1018  1484 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.576  1018  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.576  1018  1484 D SettingsProvider: ret = -1
,08-26 10:52:39.576  1018  1498 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 10:52:39.576  1018  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.576  1018  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.576  1018  1498 D SettingsProvider: selectionArgs: false
08-26 10:52:39.576  1018  1498 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.576  1018  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 10:52:39.576  1018  1498 D SettingsProvider: ret = -1,
08-26 10:52:39.586  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-26 10:52:39.586  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-26 10:52:39.586  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.586  1018  1137 D SettingsProvider: selectionArgs: false,
08-26 10:52:39.586  1018  1137 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.586  1018  1137 D SettingsProvider: ret = -1
,08-26 10:52:39.586  1018  4342 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 10:52:39.586  1018  4342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.586  1018  4342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.586  1018  4342 D SettingsProvider: selectionArgs: false
08-26 10:52:39.586  1018  4342 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  4342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.586  1018  4342 D SettingsProvider: ret = -1
08-26 10:52:39.586  1018  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 10:52:39.586  1018  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.586  1018  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.586  1018  1483 D SettingsProvider: selectionArgs: false
08-26 10:52:39.586  1018  1483 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:39.586  1018  1483 D SettingsProvider: ret = -1
08-26 10:52:39.586  1018  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:39.586  1018  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.586  1018  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:39.586  1018  1475 D SettingsProvider: selectionArgs: false
08-26 10:52:39.586  1018  1475 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.586  1018  1475 D SettingsProvider: ret = -1
08-26 10:52:39.586  1018  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-26 10:52:39.586  1018  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.586  1018  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.586  1018  1328 D SettingsProvider: selectionArgs: false
08-26 10:52:39.586  1018  1328 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:39.586  1018  1328 D SettingsProvider: ret = -1
08-26 10:52:39.586  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 10:52:39.586  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.586  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:39.586  1018  1031 D SettingsProvider: selectionArgs: false
,08-26 10:52:39.586  1018  1031 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.586  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.586  1018  1031 D SettingsProvider: ret = -1
,08-26 10:52:39.606  7448  7448 D BluetoothAdapterState: make
,08-26 10:52:39.606  7448  7448 I bluedroid: init
,08-26 10:52:39.606  7448  7463 I BluetoothAdapterState: Entering OffState
,08-26 10:52:39.606  7448  7448 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 10:52:39.606  7448  7448 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 10:52:39.606  7448  7448 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 10:52:39.606  7448  7448 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 10:52:39.606  7448  7448 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 10:52:39.606  7448  7448 I bluedroid: get_profile_interface socket
08-26 10:52:39.606  7448  7448 I bluedroid: get_profile_interface map_client
08-26 10:52:39.606  7448  7466 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 10:52:39.616  7448  7448 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 10:52:39.616  7448  7466 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 10:52:39.616  7448  7466 E BluetoothServiceJni: populateRssiValuesNative
08-26 10:52:39.616  7448  7466 I bluedroid: getModelRssiValues
08-26 10:52:39.616  7448  7466 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 10:52:39.616  7448  7466 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 10:52:39.616  7448  7466 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 10:52:39.616  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 10:52:39.626  7448  7448 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:39.626  1018  1475 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 10:52:39.626  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.626  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:39.626  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.626  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.626  7448  7456 I bluedroid: config_hci_snoop_log
,08-26 10:52:39.626  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-26 10:52:39.636  1018  1048 D BluetoothManagerService: Ble is always on enable gatt
,08-26 10:52:39.636  1018  1048 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 10:52:39.636  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 10:52:39.636  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 10:52:39.636  7448  7448 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 10:52:39.646  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 10:52:39.646  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:39.646  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 10:52:39.646  7448  7463 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 10:52:39.646  7448  7463 D BluetoothAdapterProperties: Setting state to 11
,08-26 10:52:39.646  7448  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 10:52:39.656  7448  7463 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:39.656  7448  7463 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 10:52:39.656  7448  7463 D BluetoothAdapterService: Autoconnection is available 
,08-26 10:52:39.656  7448  7463 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 10:52:39.656  7448  7463 D BluetoothSecureManager: getInstant: null
,08-26 10:52:39.656  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 10:52:39.656  7448  7463 D BluetoothSecureManager: calling getMethod for getService
08-26 10:52:39.656  7448  7463 D BluetoothSecureManager: calling getService
,08-26 10:52:39.656  7448  7463 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@dd753d5
,08-26 10:52:39.656  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.656  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-26 10:52:39.666  1018  1266 D BluetoothSecureManagerService: isSecureModeEnabled
,08-26 10:52:39.666  1018  1266 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 10:52:39.666  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 10:52:39.666  7448  7463 D BtConfig.SecureMode: isSecureModeOn:false
08-26 10:52:39.666  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 10:52:39.666  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.666  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 10:52:39.676  1875  1875 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 10:52:39.676  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
08-26 10:52:39.676  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService,
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 10:52:39.676  7448  7463 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:39.676  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:39.676  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:39.686  1018  1467 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:39.686  7448  7463 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:39.686  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 10:52:39.696  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:39.696  1018  1483 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:39.696  7448  7463 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 10:52:39.696  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:39.696  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:39.696  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:39.706  7448  7463 D BluetoothBondStateMachine: make,
,08-26 10:52:39.706  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 10:52:39.706  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 10:52:39.706  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 10:52:39.706  7448  7468 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 10:52:39.836  1018  1266 I art     : Explicit concurrent mark sweep GC freed 82687(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.350ms total 156.059ms
,08-26 10:52:39.836  1018  4352 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:39.836  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.836  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.836  1018  4352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:39.836  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:39.846  1018  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:39.846  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
08-26 10:52:39.846  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.846  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.846  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.846  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.846  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 10:52:39.846  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 10:52:39.846  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:39.846  1018  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.846  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.856  7448  7448 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:39.856  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.856  1018  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.856  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.856  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:39.856  7448  7448 D BtGatt.GattService: Received start request. Starting profile...
,08-26 10:52:39.856  7448  7448 D BtGatt.GattService: start()
08-26 10:52:39.856  7448  7448 D BtGatt.GattService: start()
08-26 10:52:39.856  7448  7448 I bluedroid: get_profile_interface gatt
08-26 10:52:39.856  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:39.856  7448  7448 D BtGatt.AdvertiseManager: advertise manager created
,08-26 10:52:39.856  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 10:52:39.856  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 10:52:39.856  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:39.856  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.856  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.856  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 10:52:39.856  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:39.856  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:39.866  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.866  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-26 10:52:39.866  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 10:52:39.866  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 10:52:39.866  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 10:52:39.876  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:39.876  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:39.876  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:39.876  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:39.886  7472  7472 E Zygote  : MountEmulatedStorage()
,08-26 10:52:39.886  7472  7472 E Zygote  : v2
08-26 10:52:39.886  7472  7472 I libpersona: KNOX_SDCARD checking this for 10055
,08-26 10:52:39.886  7472  7472 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:39.886  7472  7472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 10:52:39.896  1018  1483 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7472 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 10:52:39.896  1018  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.896  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.896  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:39.896  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.896  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.896  7472  7472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:39.896  7472  7472 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:39.896  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 10:52:39.896  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 10:52:39.896  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 10:52:39.906  1018  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.906  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.906  7448  7448 D BtGatt.GattService: mStartError = false
08-26 10:52:39.906  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:39.906  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.906  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.906  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.906  7448  7448 D HeadsetService: Received start request. Starting profile...
08-26 10:52:39.906  7448  7448 D HeadsetService: start()
08-26 10:52:39.906  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 10:52:39.906  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 10:52:39.906  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 10:52:39.906  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.906  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 10:52:39.906  7448  7448 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:39.906  7448  7448 D HeadsetStateMachine: make
,08-26 10:52:39.906  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.906  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.906  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.916  7448  7448 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 10:52:39.916  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 10:52:39.916  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:39.916  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:39.916  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.916  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.916  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.916  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.916  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.916  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 10:52:39.916  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:39.916  7448  7463 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 10:52:39.916  1018  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:39.916  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.916  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:39.916  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.916  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:39.926  1018  1266 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:39.926  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-26 10:52:39.926  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-26 10:52:39.926  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 10:52:39.926  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:39.926  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.926  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 10:52:39.926  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 10:52:39.926  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 10:52:39.926  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 10:52:39.926  7448  7463 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 10:52:39.926  1018  1481 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 10:52:39.926  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 10:52:39.926  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:39.926  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:39.926  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 10:52:39.926  7448  7448 I bluedroid: get_profile_interface handsfree
,08-26 10:52:39.946  7472  7472 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:39.946  7448  7448 I DualScoManager: Instantiating Dual Sco Manager
08-26 10:52:39.946  7448  7448 I DualScoManager: Set HeadsetServiceHelper
,08-26 10:52:39.946  7472  7472 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:39.946  7448  7448 D BluetoothAtMessage: createCMTIContentObservers
,08-26 10:52:39.946  1018  1483 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 10:52:39.946  1018  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:39.946  1018  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:39.946  1018  1483 D SettingsProvider: selectionArgs: false
08-26 10:52:39.946  1018  1483 D SettingsProvider: selectionArgs: 1002
08-26 10:52:39.946  1018  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:39.946  1018  1483 D SettingsProvider: ret = -1
,08-26 10:52:39.956  7448  7481 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 10:52:39.956  7448  7448 D HeadsetService: mStartError = false
,08-26 10:52:39.956  7448  7481 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 10:52:39.956  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:39.956  7448  7481 D HeadsetStateMachine: map size, before remove : 0
08-26 10:52:39.956  7448  7481 D HeadsetStateMachine: map size, after remove: 0
,08-26 10:52:39.966  7448  7448 D A2dpService: Received start request. Starting profile...
,08-26 10:52:39.966  7448  7448 D A2dpService: start()
,08-26 10:52:39.966  7448  7448 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 10:52:39.966  7448  7448 I bluedroid: get_profile_interface avrcp
,08-26 10:52:39.976  7448  7448 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 10:52:39.976  7448  7448 D Avrcp   : Initialize Media Controller
08-26 10:52:39.976  7448  7448 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 10:52:39.976  7448  7448 E Avrcp   : getActiveSessions
,08-26 10:52:39.976  7448  7448 D Avrcp   : pick active media Controller
08-26 10:52:39.976  7448  7448 D Avrcp   : Get the active Media Controller 
,08-26 10:52:39.986  7472  7472 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 10:52:39.996  7448  7448 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 10:52:39.996  7448  7448 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 10:52:39.996  7448  7448 D A2dpStateMachine: make
08-26 10:52:39.996  7448  7492 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 10:52:40.006  7448  7448 I bluedroid: get_profile_interface a2dp
,08-26 10:52:40.006  7448  7494 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 10:52:40.006  7448  7448 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 10:52:40.006  7448  7448 D A2dpService: mStartError = false
08-26 10:52:40.006  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:40.006  7448  7448 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 10:52:40.006  7448  7448 D HidService: Received start request. Starting profile...
08-26 10:52:40.006  7448  7448 D HidService: start()
08-26 10:52:40.006  7448  7448 I bluedroid: get_profile_interface hidhost
08-26 10:52:40.006  7448  7448 D HidService: setHidService(): set to: null
08-26 10:52:40.006  7448  7448 D HidService: mStartError = false
08-26 10:52:40.006  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:40.006  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 10:52:40.016  7448  7448 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:40.016  7448  7493 D A2dpStateMachine: Enter Disconnected: -2
,08-26 10:52:40.016  7448  7448 D HealthService: Received start request. Starting profile...
08-26 10:52:40.016  7448  7448 D HealthService: start()
,08-26 10:52:40.016  7448  7448 I bluedroid: get_profile_interface health
08-26 10:52:40.016  7448  7448 D HealthService: mStartError = false
08-26 10:52:40.016  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:40.016  7448  7492 D BluetoothMediaBrowser: no now playing list
08-26 10:52:40.016  7448  7448 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 10:52:40.016  7448  7492 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 10:52:40.016  7448  7448 D PanService: Received start request. Starting profile...
08-26 10:52:40.016  7448  7448 D PanService: start()
08-26 10:52:40.016  7448  7448 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 10:52:40.016  7448  7448 I bluedroid: get_profile_interface pan
08-26 10:52:40.026  7448  7448 D PanService: mStartError = false
08-26 10:52:40.026  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:40.026  7448  7448 D BluetoothMapService: Received start request. Starting profile...
08-26 10:52:40.026  7448  7448 D BluetoothMapService: start()
,08-26 10:52:40.026  7448  7448 D BluetoothMapService: mStartError = false
08-26 10:52:40.026  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:40.026  7448  7448 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 10:52:40.026  7448  7448 D SapService: Received start request. Starting profile...
08-26 10:52:40.026  7448  7448 D SapService: start()
08-26 10:52:40.026  7448  7448 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 10:52:40.026  7448  7448 I bluedroid: get_profile_interface sap
08-26 10:52:40.026  7448  7448 D SapService: mStartError = false
08-26 10:52:40.026  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
08-26 10:52:40.026  7448  7448 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 10:52:40.036  1427  1448 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 10:52:40.036  7472  7472 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 10:52:40.036  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 10:52:40.036  7472  7472 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 10:52:40.036  7472  7472 D UserAnalysis: Create SecureDbHelper
,08-26 10:52:40.036  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 10:52:40.036  1427  1448 I Telecom : BluetoothPhoneService: Result of Message : true
08-26 10:52:40.036  7448  7448 D HeadsetStateMachine: Proxy object connected
,08-26 10:52:40.036  7448  7448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 10:52:40.036  7448  7448 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 10:52:40.036  7448  7481 D HeadsetStateMachine: Disconnected process message: 11
08-26 10:52:40.036  7448  7448 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 10:52:40.036  7448  7448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 10:52:40.036  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 10:52:40.036  7448  7448 D BluetoothA2dp: Proxy object connected
08-26 10:52:40.036  7448  7448 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 10:52:40.036  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 10:52:40.036  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 10:52:40.036  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 10:52:40.036  7448  7481 D HeadsetStateMachine: Disconnected process message: 18
08-26 10:52:40.036  7448  7481 D HeadsetStateMachine: Disconnected process message: 10
08-26 10:52:40.036  7448  7481 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 10:52:40.036  7448  7481 D HeadsetStateMachine: Disconnected process message: 11
,08-26 10:52:40.046  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 10:52:40.046  7472  7472 D IntelligenceServiceApplication: onCreate()
,08-26 10:52:40.046  1018  1481 I ActivityManager: Killing 7155:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-26 10:52:40.056  7472  7472 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 10:52:40.056  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 10:52:40.056  7472  7472 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 10:52:40.066  7472  7472 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 10:52:40.086  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 10:52:40.086  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 10:52:40.096  7448  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 10:52:40.096  1018  1328 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 10:52:40.096  7448  7463 I bluedroid: enable
,08-26 10:52:40.096  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:40.096  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:40.096  7448  7463 I bt_hci_bdroid: init
,08-26 10:52:40.096  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:40.096  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:40.096  7448  7499 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 10:52:40.106  7448  7463 I bt_vendor: bt-vendor : init
,08-26 10:52:40.106  7448  7463 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 10:52:40.106  7448  7463 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 10:52:40.106  7448  7463 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 10:52:40.106  7448  7463 D bt_userial_mct: userial_init
,08-26 10:52:40.106  7448  7463 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 10:52:40.106  7448  7463 I bt_vendor: Starting hciattach daemon
08-26 10:52:40.106  7448  7463 I bt_vendor: try to set false
08-26 10:52:40.106  7448  7463 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 10:52:40.106  7448  7463 I bt_vendor: Starting hciattach daemon
08-26 10:52:40.106  7448  7463 I bt_vendor: try to set true
,08-26 10:52:40.116  7503  7503 E Zygote  : MountEmulatedStorage(),
,08-26 10:52:40.116  7503  7503 E Zygote  : v2
08-26 10:52:40.116  7503  7503 I libpersona: KNOX_SDCARD checking this for 10105
08-26 10:52:40.116  7503  7503 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:40.116  7503  7503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:40.116  7503  7503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:40.116  7503  7503 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 10:52:40.126  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 10:52:40.126  1018  1328 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7503 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 10:52:40.156  7503  7503 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 10:52:40.156  7503  7503 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:40.176  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 10:52:40.186  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 10:52:40.206  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 10:52:40.216  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 10:52:40.226  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:40.236  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 10:52:40.346   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 10:52:40.346   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:40.346  7503  7536 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 10:52:40.356   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 10:52:40.356   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 10:52:40.356  7503  7536 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 10:52:40.416   288   288 E SMD     : DCD OFF,
,08-26 10:52:40.476  7547  7547 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-26 10:52:40.486  7548  7548 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:40.516  7448  7463 I bt_vendor: bluetooth satus is on
,08-26 10:52:40.516  7448  7501 D bt_userial_mct: userial_open(port:0)
08-26 10:52:40.516  7448  7501 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 10:52:40.516  7448  7501 I bt_vendor: Done intiailizing UART
,08-26 10:52:40.516  7448  7501 I bt_vendor: Done intiailizing UART
08-26 10:52:40.516  7448  7501 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 10:52:40.516  7448  7501 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 10:52:40.526  7448  7550 D bt_userial_mct: Entering userial_read_thread()
,08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_SDP,
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 10:52:40.526  7448  7499 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:40.536  1018  1266 I ActivityManager: Killing 7170:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at com.google.q.e.b(PG:15188)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	,at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253),
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
,08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 10:52:40.536  7503  7503 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:40.536  7503  7503 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 10:52:40.546  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:40.546  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:40.596  7503  7546 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 10:52:40.616  7448  7499 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 10:52:40.616  7448  7499 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41baed1 
,08-26 10:52:40.616  7448  7499 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41baed1 
,08-26 10:52:40.616  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:40.626  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.626  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:40.626  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 10:52:40.636  7448  7466 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 10:52:40.636  7448  7466 E bt-btif : Calling BTA_HhEnable
,08-26 10:52:40.636  7448  7466 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 10:52:40.636  7448  7466 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 10:52:40.636  7448  7466 E BluetoothServiceJni: populateRssiValuesNative
,08-26 10:52:40.636  7448  7466 I bluedroid: getModelRssiValues
08-26 10:52:40.636  7448  7466 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 10:52:40.636  7448  7466 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 10:52:40.646  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 10:52:40.646  7448  7466 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 10:52:40.646  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:40.646  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:40.656  7448  7466 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 10:52:40.656  7448  7466 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:40.656  7448  7466 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:40.656  7448  7466 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 10:52:40.656  7448  7466 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 10:52:40.656  7448  7466 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 10:52:40.656  7448  7466 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 10:52:40.656  7448  7466 E bt-btif : btif_sock_init: !vhci_init
,08-26 10:52:40.656  7448  7466 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 10:52:40.656  7448  7550 E bt_mct  : hci lib postload completed,
08-26 10:52:40.656  7448  7466 D IOP_DB_BT: db_open: db_open : handle 3028209680l, read 13894 bytes onto local cache
08-26 10:52:40.656  7448  7466 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1,
08-26 10:52:40.656  7448  7466 D IOP_DB_BT: db_query: result 1
,08-26 10:52:40.656  7448  7466 I         : iop_db_open: iop_db_open status 0
08-26 10:52:40.656  7448  7466 D bte_conf: Device ID record 1 : primary
08-26 10:52:40.656  7448  7466 D bte_conf:   vendorId            = 0075
08-26 10:52:40.656  7448  7466 D bte_conf:   vendorIdSource      = 0001
,08-26 10:52:40.656  7448  7466 D bte_conf:   product             = 0100
08-26 10:52:40.656  7448  7466 D bte_conf:   version             = 0200
08-26 10:52:40.656  7448  7466 D bte_conf:   clientExecutableURL = 
08-26 10:52:40.656  7448  7466 D bte_conf:   serviceDescription  = 
08-26 10:52:40.656  7448  7466 D bte_conf:   documentationURL    = 
08-26 10:52:40.656  7448  7466 D bte_conf: bte_load_did_conf no section named DID2.,
08-26 10:52:40.656  7448  7466 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 10:52:40.656  7448  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 10:52:40.656  7448  7463 D BluetoothAdapterProperties: ScanMode =  20
08-26 10:52:40.656  7448  7463 D BluetoothAdapterProperties: State =  11,
08-26 10:52:40.656  1018  1475 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 10:52:40.666  7448  7463 D BluetoothAdapterProperties: Setting state to 12
08-26 10:52:40.666  7448  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 10:52:40.666  7448  7466 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 10:52:40.666  7448  7466 D BluetoothAdapterProperties: Scan Mode:21
08-26 10:52:40.666  7448  7466 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:40.666  1018  1031 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 10:52:40.666  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:40.666  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:40.666  1018  1031 D SettingsProvider: selectionArgs: false
,08-26 10:52:40.666  1018  1031 D SettingsProvider: selectionArgs: 1002
,08-26 10:52:40.666  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:40.666  1018  1031 D SettingsProvider: ret = -1
,08-26 10:52:40.666  7448  7463 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 10:52:40.666  7448  7463 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 10:52:40.676  1018  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:40.676  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.676  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.676  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.676  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:40.676  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:40.676  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:40.686  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:40.686  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:40.686  7448  7463 D BluetoothAdapterService: Autoconnection is available 
08-26 10:52:40.686  7448  7463 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12,
08-26 10:52:40.686  7448  7463 D BluetoothAdapterService: starting service from this receiver
08-26 10:52:40.686  1018  4352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:40.686  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 10:52:40.686  1427  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.686  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.686  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.686  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:40.686  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:40.696  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:40.696  7448  7463 I BluetoothAdapterState: Entering On State from state = 11
,08-26 10:52:40.696  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.696  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.696  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.696  7448  7448 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 10:52:40.696  1427  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:40.696  1427  3298 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 10:52:40.696  1427  3298 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.696  1427  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.696  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 10:52:40.696  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:40.696  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.696  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.696  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.696  1427  1448 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 10:52:40.696  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.706  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:40.706  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 10:52:40.706  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:40.706  7503  7511 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.706  7503  7511 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.706  1308  1318 D Bluetoothsap: onBluetoothStateChange: up=true
,08-26 10:52:40.706  1308  1318 D Bluetoothsap: Binding service...
,08-26 10:52:40.706  7448  7448 I BluetoothPbapService: Handler(): got msg=1
,08-26 10:52:40.706  1018  4352 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 10:52:40.706  1308  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 10:52:40.716  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 10:52:40.716  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.716  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.716  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.716  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.716  7448  7556 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 10:52:40.716  1308  1318 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 10:52:40.716  7448  7467 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.716  7448  7467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.716  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-26 10:52:40.716  1308  1308 D SapProfile: Bluetooth service connected
08-26 10:52:40.716  1308  1308 D Bluetoothsap: getConnectedDevices()
,08-26 10:52:40.716  1441  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.716  1441  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.716  1308  7055 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 10:52:40.726  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 10:52:40.726  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.726  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.726  1308  1318 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.726  1308  1318 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.726  7448  7456 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 10:52:40.726  1308  1317 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.726  1308  1308 D BluetoothPbap: Proxy object connected
08-26 10:52:40.726  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:40.726  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:40.726  1308  1308 D PbapServerProfile: Bluetooth service connected
08-26 10:52:40.726  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 10:52:40.726  7448  7556 D BluetoothSocket: bindListen(): myUserId = 0
08-26 10:52:40.726  7448  7556 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:40.726  1308  1317 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:40.726  1975  1997 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.726  1308  1308 D HeadsetProfile: Bluetooth service connected
08-26 10:52:40.726  1975  1997 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:40.726  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.726  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:40.726  1308  7055 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 10:52:40.726  7448  7556 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-26 10:52:40.726  7448  7556 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 10:52:40.726  7448  7556 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:40.726  7448  7556 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d02c5ee
,08-26 10:52:40.726  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 10:52:40.726  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.726  7448  7556 D BluetoothSocket: channel: 19
08-26 10:52:40.726  7448  7556 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-26 10:52:40.726  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.726  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.726  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:40.736  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 10:52:40.736  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 10:52:40.736  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.736  1018  1018 D BluetoothA2dp: Proxy object connected
08-26 10:52:40.736  1308  1318 D BluetoothPan: Binding service...
,08-26 10:52:40.736  1308  1308 D BluetoothInputDevice: Proxy object connected
,08-26 10:52:40.736  1308  1308 D HidProfile: Bluetooth service connected
08-26 10:52:40.736  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 10:52:40.736  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.736  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.736  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.736  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.736  1308  1308 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:40.736  1308  1308 D PanProfile: Bluetooth service connected
08-26 10:52:40.736  1427  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.736  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:40.736  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:40.736  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.736  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.736  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.736  1427  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:40.736  1455  6310 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 10:52:40.736  1455  6310 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:40.746  1308  1318 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 10:52:40.746  1308  1318 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.746  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 10:52:40.746  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.746  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.746  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.746  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.746  1308  1308 D BluetoothA2dp: Proxy object connected
08-26 10:52:40.746  1308  1308 D A2dpProfile: Bluetooth service connected
,08-26 10:52:40.746  1018  1048 D BluetoothPan: Binding service...
,08-26 10:52:40.746  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 10:52:40.746  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.746  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:40.746  6847  6855 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.746  6847  6855 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.746  1455  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:40.746  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 10:52:40.746  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:40.756  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.756  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:40.756  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.756  1455  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:40.756  1308  7055 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 10:52:40.756  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 10:52:40.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.756  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.756  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.756  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.756  1308  1308 D BluetoothMap: Proxy object connected
,08-26 10:52:40.756  1308  1308 D MapProfile: Bluetooth service connected
08-26 10:52:40.756  1308  1308 D BluetoothMap: getConnectedDevices()
08-26 10:52:40.756  1172  1205 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:40.756  1172  1205 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:40.756  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 10:52:40.756  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 10:52:40.766  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:40.766  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-26 10:52:40.766  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 10:52:40.766  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-26 10:52:40.766  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@21b1834a, true
,08-26 10:52:40.766  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 10:52:40.776  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:40.776  1172  1172 D BluetoothTile:  getBluetoothState : 12
08-26 10:52:40.776  1875  1875 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 10:52:40.776  1427  1427 D BluetoothHeadset: registerMessageListener
,08-26 10:52:40.776  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:40.776  1018  1483 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:40.776  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 10:52:40.776  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:40.776  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:40.786  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:40.786  1018  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:40.786  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:40.786  7448  7557 D HeadsetService: registerMessageListener
,08-26 10:52:40.786  7448  7557 D HeadsetService: registerMessageListener
08-26 10:52:40.786  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.786  7448  7481 D HeadsetStateMachine: Disconnected process message: 70
08-26 10:52:40.786  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 10:52:40.786  7448  7481 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3690fa8f
08-26 10:52:40.786  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 10:52:40.786  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.786  1018  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:40.786  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:40.786  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:40.796  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:40.796  7448  7558 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 10:52:40.796  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 10:52:40.796  1308  1308 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 10:52:40.796  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 10:52:40.796  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 10:52:40.796  1308  1308 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-26 10:52:40.796  1308  1308 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 10:52:40.796  1308  1308 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 10:52:40.796  7448  7481 D HeadsetStateMachine: Disconnected process message: 9
08-26 10:52:40.796  7448  7558 D BluetoothSocket: bindListen(): myUserId = 0
08-26 10:52:40.796  7448  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:40.796  7448  7481 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 10:52:40.796  7448  7558 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 10:52:40.796  7448  7558 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 10:52:40.796  7448  7558 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:40.796  7448  7558 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ac711c
,08-26 10:52:40.796  7448  7558 D BluetoothSocket: channel: 5
,08-26 10:52:40.806   283   678 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 10:52:40.806   283   678 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 10:52:40.806   283   678 V voice   : voice_set_parameters: exit with code(-2)
08-26 10:52:40.806   283   678 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 10:52:40.806   283   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 10:52:40.806   283   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 10:52:40.806   283   678 V audio_hw_primary: adev_set_parameters: exit
08-26 10:52:40.806  7448  7481 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 10:52:40.806  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:40.816  1018  1137 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 10:52:40.816  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.816  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.816  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.816  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 10:52:40.816  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:40.826  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:40.826  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:40.826  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 10:52:40.836  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:40.836  7448  7448 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 10:52:40.836  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:40.836  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.836  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.836  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:40.836  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:40.846  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:40.846  1018  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:40.846  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:40.846  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.846  1018  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:40.846  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:40.856  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:40.856  1975  7563 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 10:52:40.866  1018  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:40.866  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-26 10:52:40.866  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:40.866  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:40.866  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:40.876  1018  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:40.886  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:40.886  1018  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:40.886  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:40.886  7448  7568 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 10:52:40.886  7448  7568 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:40.886  7448  7568 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 10:52:40.886  7448  7568 D BluetoothSocket: bindListen(), new LocalSocket 
,08-26 10:52:40.896  7448  7568 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:40.896  7448  7568 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@559a4c6
08-26 10:52:40.896  7448  7568 D BluetoothSocket: channel: 12
08-26 10:52:40.896  7448  7568 I BtOppRfcommListener: Accept thread started.
,08-26 10:52:40.896  1975  7563 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 10:52:42.426  6847  6903 D BluetoothAdapter: disable()
,08-26 10:52:42.436  1018  1475 D SettingsProvider: name = bluetooth_on
,08-26 10:52:42.446  7448  7463 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 10:52:42.446  7448  7463 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:42.446  7448  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 10:52:42.446  7448  7463 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:42.446  7448  7463 D BluetoothAdapterService: updateAdapterState state is 13
08-26 10:52:42.446  1018  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:42.446  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 10:52:42.446  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:42.446  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:42.446  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:42.446  7448  7448 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 10:52:42.456  7448  7463 D BluetoothAdapterService: Autoconnection is available ,
08-26 10:52:42.456  7448  7448 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e83ac87, channel: 19, state: LISTENING
,08-26 10:52:42.456  7448  7463 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 10:52:42.456  7448  7463 D BluetoothAdapterService: terminating service from this receiver
08-26 10:52:42.456  7448  7448 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e83ac87, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d02c5ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@40bc7b4mSocket: android.net.LocalSocket@39150fdd impl:android.net.LocalSocketImpl@1abb4752 fd:FileDescriptor[74],
08-26 10:52:42.456  7448  7448 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39150fdd impl:android.net.LocalSocketImpl@1abb4752 fd:FileDescriptor[74]
08-26 10:52:42.456  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 10:52:42.456  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:42.456  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:42.456  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:42.456  7448  7463 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 10:52:42.456  7448  7463 D BluetoothAdapterProperties: mDiscovering is false
,08-26 10:52:42.466  1018  1498 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 10:52:42.466  7448  7463 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 10:52:42.466  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:42.466  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 10:52:42.476  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-26 10:52:42.476  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 10:52:42.476  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:42.476  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-26 10:52:42.476  1172  1172 D BluetoothTile:  getBluetoothState : 13
08-26 10:52:42.476  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:42.486  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 10:52:42.486  1875  1875 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 10:52:42.486  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 10:52:42.486  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:42.486  1018  1328 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:42.496  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:42.496  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:42.496  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:42.496  1018  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:42.496  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:42.506  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:42.506  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:42.506  7448  7466 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-26 10:52:42.506  7448  7466 D BluetoothAdapterProperties: Scan Mode:20
,08-26 10:52:42.506  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:42.506  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:42.516  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:42.516  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:42.516  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:42.516  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:42.516  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:42.516  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:42.526  7448  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 10:52:42.526  7448  7463 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 10:52:42.526  1018  4352 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 10:52:42.526  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 10:52:42.526  7448  7463 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 10:52:42.526  7448  7568 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 10:52:42.526  7448  7463 E bt-btif : cmd socket is not created
,08-26 10:52:42.526  7448  7499 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 10:52:42.526  7448  7499 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 10:52:42.526  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:42.526  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:42.526  7448  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:42.526  7448  7463 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 10:52:42.526  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:42.536  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:42.536  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:42.536  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 10:52:42.536  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:42.536  1308  1308 D BluetoothPbap: Proxy object disconnected
08-26 10:52:42.536  1308  1308 D PbapServerProfile: Bluetooth service disconnected
,08-26 10:52:42.556  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:42.556  7448  7448 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ce48a23, channel: 5, state: LISTENING
08-26 10:52:42.556  7448  7448 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ce48a23, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ac711c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3977ab20mSocket: android.net.LocalSocket@28d7ccd9 impl:android.net.LocalSocketImpl@2d22869e fd:FileDescriptor[76]
08-26 10:52:42.556  7448  7448 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28d7ccd9 impl:android.net.LocalSocketImpl@2d22869e fd:FileDescriptor[76]
,08-26 10:52:42.556  7448  7448 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:42.556  7448  7448 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38eba57f, channel: 12, state: LISTENING
08-26 10:52:42.556  7448  7448 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38eba57f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@559a4c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7fc594cmSocket: android.net.LocalSocket@266f5d95 impl:android.net.LocalSocketImpl@22c6eaa fd:FileDescriptor[80]
08-26 10:52:42.556  7448  7448 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@266f5d95 impl:android.net.LocalSocketImpl@22c6eaa fd:FileDescriptor[80]
,08-26 10:52:42.556  7448  7568 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 10:52:42.556  7448  7448 V BluetoothOppManager: cleanUp...
,08-26 10:52:42.556  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:42.566  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:42.566  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 10:52:42.586  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:42.596  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:42.726  7448  7499 W bt-btif : ag scb idx 1 not allocated
08-26 10:52:42.726  7448  7499 W bt-btif : ag scb idx 2 not allocated
08-26 10:52:42.726  7448  7499 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 10:52:42.726  7448  7550 I bt_userial_mct: exiting userial_read_thread
08-26 10:52:42.726  7448  7550 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 10:52:42.726  7448  7466 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 10:52:42.726  7448  7501 I bt_vendor: hw_epilog_process
08-26 10:52:42.726  7448  7466 D bt_userial_mct: userial_close
08-26 10:52:42.726  7448  7466 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 10:52:42.976  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 10:52:42.976  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 10:52:42.976  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 10:52:42.976  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 10:52:42.976  1018  1030 D BatteryService: stay LED for fully charged
08-26 10:52:42.976  1018  1018 I MotionRecognitionService: Plugged
08-26 10:52:42.976  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-26 10:52:42.976  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 10:52:42.976  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 10:52:42.976  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 10:52:42.976  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 10:52:42.986  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:42.996  7448  7448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 10:52:42.996  7448  7481 D HeadsetStateMachine: Disconnected process message: 10
,08-26 10:52:42.996  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:43.006  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:43.206  7448  7466 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 10:52:43.206  7448  7466 I bt_vendor: bluetooth satus is on
08-26 10:52:43.206  7448  7466 I bt_vendor: bt-vendor : resetting BT status
08-26 10:52:43.206  7448  7466 I bt_vendor: Starting hciattach daemon
08-26 10:52:43.206  7448  7466 I bt_vendor: try to set false
,08-26 10:52:43.206  7448  7466 I bt_vendor: Starting hciattach daemon,
,08-26 10:52:43.206  7448  7466 I bt_vendor: try to set false
,08-26 10:52:43.216  7448  7466 I bt_vendor: cleanup
08-26 10:52:43.216  7448  7499 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 10:52:43.216  7448  7466 I GKI_LINUX: GKI_exit_task 0 done,
08-26 10:52:43.216  7448  7466 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 10:52:43.216  7448  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 10:52:43.216  7448  7463 D BtConfig.SecureMode: isSecureModeOn:false
08-26 10:52:43.216  7448  7463 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 10:52:43.216  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.216  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 10:52:43.216  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 10:52:43.216  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 10:52:43.216  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 10:52:43.226  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-26 10:52:43.226  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.226  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:43.226  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 10:52:43.226  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 10:52:43.226  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 10:52:43.226  7448  7448 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:43.226  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.226  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.226  7448  7448 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 10:52:43.226  7448  7448 D BtGatt.GattService: stop()
08-26 10:52:43.226  7448  7448 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 10:52:43.236  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.236  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.236  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.236  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 10:52:43.236  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:43.236  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 10:52:43.236  1018  4342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.236  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.236  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.236  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.236  1018  4342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.236  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.236  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 10:52:43.236  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:43.236  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 10:52:43.236  1018  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.236  7448  7448 D HeadsetService: Received stop request...Stopping profile...
08-26 10:52:43.236  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.236  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.236  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:43.236  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.246  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 10:52:43.246  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 10:52:43.246  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 10:52:43.246  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.246  1018  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:43.246  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.246  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.246  1018  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.246  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.246  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 10:52:43.246  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 10:52:43.246  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 10:52:43.246  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService,
,08-26 10:52:43.246  1018  4352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.246  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 10:52:43.256  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:43.256  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.256  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.256  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:43.256  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.256  7448  7463 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:43.256  1308  1308 D HeadsetProfile: Bluetooth service disconnected
08-26 10:52:43.256  1018  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.256  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.256  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:43.256  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.256  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.256  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 10:52:43.256  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:43.256  7448  7463 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 10:52:43.256  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:43.256  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.256  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.256  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.256  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:43.266  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:43.266  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 10:52:43.266  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 10:52:43.266  7448  7463 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 10:52:43.266  7448  7463 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 10:52:43.266  7448  7463 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 10:52:43.266  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-26 10:52:43.266  7448  7448 D A2dpService: Received stop request...Stopping profile...
08-26 10:52:43.266  7448  7493 D A2dpStateMachine: Exit Disconnected: -1
,08-26 10:52:43.266  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.266  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 10:52:43.266  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:43.266  7448  7448 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 10:52:43.266  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:43.266  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 10:52:43.266  1308  1308 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:43.266  7448  7448 D HidService: Received stop request...Stopping profile...
08-26 10:52:43.266  7448  7448 D HidService: Stopping Bluetooth HidService
08-26 10:52:43.266  7448  7448 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:43.266  7448  7448 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 10:52:43.266  7448  7448 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 10:52:43.266  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.266  1308  1308 D A2dpProfile: Bluetooth service disconnected
,08-26 10:52:43.276  7448  7448 D HealthService: Received stop request...Stopping profile...
,08-26 10:52:43.276  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.276  1308  1308 D BluetoothInputDevice: Proxy object disconnected
08-26 10:52:43.276  1308  1308 D HidProfile: Bluetooth service disconnected
,08-26 10:52:43.276  7448  7448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 10:52:43.276  7448  7448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 10:52:43.276  7448  7448 D PanService: Received stop request...Stopping profile...
,08-26 10:52:43.276  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.286  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 10:52:43.286  7448  7448 D BluetoothMapService: Received stop request...Stopping profile...
08-26 10:52:43.286  1308  1308 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 10:52:43.286  1308  1308 D PanProfile: Bluetooth service disconnected
,08-26 10:52:43.286  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.286  1308  1308 D BluetoothMap: Proxy object disconnected
08-26 10:52:43.286  1308  1308 D MapProfile: Bluetooth service disconnected
08-26 10:52:43.286  7448  7448 D SapService: Received stop request...Stopping profile...
08-26 10:52:43.286  7448  7448 D SapService: Stopping Bluetooth SapService
08-26 10:52:43.286  7448  7448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13fc06f4
,08-26 10:52:43.286  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
08-26 10:52:43.296  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:43.296  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 10:52:43.296  1308  1308 D SapProfile: Bluetooth service disconnected
,08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 10:52:43.296  7448  7448 D BluetoothA2dp: Proxy object disconnected
,08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 10:52:43.296  7448  7494 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 10:52:43.296  7448  7448 I GKI_LINUX: GKI_exit_task 2 done
,08-26 10:52:43.296  7448  7448 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 10:52:43.296  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 10:52:43.296  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.296  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 10:52:43.296  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.296  7448  7448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-26 10:52:43.296  7448  7448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:43.296  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 10:52:43.296  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:43.296  7448  7448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:43.296  7448  7448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 10:52:43.296  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-26 10:52:43.296  7448  7448 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
08-26 10:52:43.296  7448  7448 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 10:52:43.296  7448  7448 E BluetoothAdapterService(335283956): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 10:52:43.296  7448  7448 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 10:52:43.296  7448  7448 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 10:52:43.306  7448  7463 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 10:52:43.306  7448  7463 D BluetoothAdapterProperties: Setting state to 10
08-26 10:52:43.306  7448  7463 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 10:52:43.306  7448  7463 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:43.306  7448  7463 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 10:52:43.306  7448  7463 D BluetoothAdapterService: Autoconnection is available 
,08-26 10:52:43.306  7448  7463 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-26 10:52:43.306  7448  7463 I BluetoothAdapterState: Entering OffState
,08-26 10:52:43.306  1427  3298 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.306  1427  3298 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.306  7503  7513 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.306  7503  7513 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.306  1308  1317 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 10:52:43.306  1308  1317 D Bluetoothsap: Unbinding service...
,08-26 10:52:43.306  7448  7467 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.306  7448  7467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.316  1441  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:43.316  1441  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.316  1308  7055 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 10:52:43.316  1308  1318 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:43.316  1308  1318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.316  7448  7456 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 10:52:43.316  1975  1994 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:43.316  1975  1994 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:43.316  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 10:52:43.316  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:43.316  1308  7055 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 10:52:43.316  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 10:52:43.316  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.316  1455  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 10:52:43.316  1308  1317 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 10:52:43.316  6847  6858 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.316  6847  6858 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.316  6847  6858 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 10:52:43.316  6847  6858 D BluetoothLeAdvertiser: Exit stop advertising
,08-26 10:52:43.316  6847  6858 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 10:52:43.316  6847  6858 D BluetoothLeScanner: Exiting stopAllScan
,08-26 10:52:43.326  1308  7055 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 10:52:43.326  1172  1936 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 10:52:43.326  1172  1936 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 10:52:43.326  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 10:52:43.326  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 10:52:43.336  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:43.336  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-26 10:52:43.336  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 10:52:43.346  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.346  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 10:52:43.346  1172  1726 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.346  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:43.346  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-26 10:52:43.346  1172  1726 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.346  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.346  1172  1172 D BluetoothAdapter: 341685396: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.346  1018  1137 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:43.346  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:43.346  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:43.356  1975  2168 D BluetoothAdapter: 392272383: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.356  1975  2168 D BluetoothAdapter: 392272383: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:43.356  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:43.356  1875  1875 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 10:52:43.356  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:43.356  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:43.366  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:43.366  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.366  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:43.366  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:43.366  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:43.366  7448  7466 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 10:52:43.366  7448  7448 I GKI_LINUX: GKI_exit_task 1 done
08-26 10:52:43.366  7448  7448 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 10:52:43.366  7448  7448 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 10:52:43.366  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:43.366  7448  7448 I art     : System.exit called, status: 0
08-26 10:52:43.366  7448  7448 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 10:52:43.376  1018  1467 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 10:52:43.376  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.376  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:43.376  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:43.376  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 10:52:43.396  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:43.396  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:43.396  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:43.396  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 10:52:43.396  1018  1328 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 10:52:43.406  1018  1328 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 10:52:43.406  1018  1328 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 10:52:43.406  1018  1328 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 10:52:43.406  1018  1328 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:43.406  1018  1328 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 10:52:43.406  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:43.406  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:43.406  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:43.406  1018  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:43.416  7585  7585 E Zygote  : MountEmulatedStorage()
08-26 10:52:43.416  7585  7585 I libpersona: KNOX_SDCARD checking this for 1002
08-26 10:52:43.416  7585  7585 E Zygote  : v2
08-26 10:52:43.416  7585  7585 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:43.416  7585  7585 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:43.416   288   288 E SMD     : DCD OFF
,08-26 10:52:43.426  7585  7585 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 10:52:43.426  7585  7585 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:43.426  1018  1328 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7585 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 10:52:43.436  7585  7585 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:43.446  7585  7585 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:43.456  7585  7585 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 10:52:43.456  7585  7585 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:43.476  7585  7585 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding GattService
,08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding HidService
08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding HealthService
08-26 10:52:43.506  7585  7585 D BtSettings.ProfileConfig: Adding PanService
,08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding SapService
08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding SapClientService
08-26 10:52:43.516  7585  7585 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 10:52:43.516  7585  7585 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 10:52:43.516  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-26 10:52:43.516  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  1030 D SettingsProvider: selectionArgs: false
08-26 10:52:43.516  1018  1030 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  1030 D SettingsProvider: ret = -1
,08-26 10:52:43.516  1018  4352 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:43.516  1018  4352 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  4352 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  4352 D SettingsProvider: selectionArgs: false
08-26 10:52:43.516  1018  4352 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  4352 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  4352 D SettingsProvider: ret = -1
,08-26 10:52:43.516  1018  1266 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 10:52:43.516  1018  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  1266 D SettingsProvider: selectionArgs: false
08-26 10:52:43.516  1018  1266 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  1266 D SettingsProvider: ret = -1
,08-26 10:52:43.516  1018  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
08-26 10:52:43.516  1018  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  1481 D SettingsProvider: selectionArgs: false,
08-26 10:52:43.516  1018  1481 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  1481 D SettingsProvider: ret = -1
08-26 10:52:43.516  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-26 10:52:43.516  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  1031 D SettingsProvider: selectionArgs: false
,08-26 10:52:43.516  1018  1031 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  1031 D SettingsProvider: ret = -1
08-26 10:52:43.516  1018  1498 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 10:52:43.516  1018  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 10:52:43.516  1018  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.516  1018  1498 D SettingsProvider: selectionArgs: false
08-26 10:52:43.516  1018  1498 D SettingsProvider: selectionArgs: 1002
,08-26 10:52:43.516  1018  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.516  1018  1498 D SettingsProvider: ret = -1
08-26 10:52:43.516  1018  4342 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 10:52:43.516  1018  4342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.516  1018  4342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:43.516  1018  4342 D SettingsProvider: selectionArgs: false
08-26 10:52:43.516  1018  4342 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.516  1018  4342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.526  1018  4342 D SettingsProvider: ret = -1
,08-26 10:52:43.526  1018  1483 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 10:52:43.526  1018  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.526  1018  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.526  1018  1483 D SettingsProvider: selectionArgs: false
08-26 10:52:43.526  1018  1483 D SettingsProvider: selectionArgs: 1002,
08-26 10:52:43.526  1018  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.526  1018  1483 D SettingsProvider: ret = -1
08-26 10:52:43.526  1018  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:43.526  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 10:52:43.526  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.526  1018  1137 D SettingsProvider: selectionArgs: false
08-26 10:52:43.526  1018  1137 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.526  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:43.526  1018  1137 D SettingsProvider: ret = -1
08-26 10:52:43.526  1018  1484 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:43.526  1018  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.526  1018  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.526  1018  1484 D SettingsProvider: selectionArgs: false
,08-26 10:52:43.526  1018  1484 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.526  1018  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.526  1018  1484 D SettingsProvider: ret = -1
08-26 10:52:43.526  1018  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-26 10:52:43.526  1018  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.526  1018  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:43.526  1018  1467 D SettingsProvider: selectionArgs: false
,08-26 10:52:43.526  1018  1467 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.526  1018  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:43.526  1018  1467 D SettingsProvider: ret = -1
,08-26 10:52:43.526  1018  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 10:52:43.526  1018  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:43.526  1018  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 10:52:43.526  1018  1328 D SettingsProvider: selectionArgs: false
08-26 10:52:43.526  1018  1328 D SettingsProvider: selectionArgs: 1002
08-26 10:52:43.526  1018  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 10:52:43.526  1018  1328 D SettingsProvider: ret = -1
,08-26 10:52:43.546  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:43.546  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:43.546  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:43.546  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:43.546  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:43.546  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:43.556  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:43.556  1975  7601 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 10:52:43.556  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:43.566  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:43.566  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:43.566  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:43.576  1975  7601 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 10:52:44.406  1018  1051 I PowerManagerService: [PWL] Off : 75s ago
,08-26 10:52:44.406  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-26 10:52:44.406  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-26 10:52:44.406  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=13162)
,08-26 10:52:44.536  1018  1314 E Watchdog: !@Sync 4
,08-26 10:52:45.446  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 10:52:45.446  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:46.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:46.426   288   288 E SMD     : DCD OFF,
,08-26 10:52:47.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:48.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:48.446  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:48.446  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31b03b69 added. We now have 6 listener(s)
08-26 10:52:48.446  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:48.446  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:48.446  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@365979ee added. We now have 7 listener(s)
08-26 10:52:48.446  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:48.446  6847  6903 I System.out: IsBluetoothEnabled
08-26 10:52:48.446  6847  6903 D BluetoothAdapter: disable()
08-26 10:52:48.446  1018  1475 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 10:52:48.456  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:48.456  6847  6903 D BluetoothAdapter: enable()
,08-26 10:52:48.456  1018  1467 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 10:52:48.456  1018  1467 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 10:52:48.456  1018  1467 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:48.456  1018  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 10:52:48.456  1018  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:48.456  1018  1467 D SettingsProvider: name = bluetooth_on
,08-26 10:52:48.466  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 10:52:48.466  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:48.476  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 10:52:48.476  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 10:52:48.506  7585  7585 D BluetoothAdapterState: make
,08-26 10:52:48.516  7585  7585 I bluedroid: init
,08-26 10:52:48.516  7585  7585 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 10:52:48.516  7585  7585 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 10:52:48.516  7585  7585 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 10:52:48.516  7585  7585 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 10:52:48.516  7585  7585 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 10:52:48.516  7585  7585 I bluedroid: get_profile_interface socket
08-26 10:52:48.516  7585  7585 I bluedroid: get_profile_interface map_client
08-26 10:52:48.516  7585  7607 I BluetoothAdapterState: Entering OffState
,08-26 10:52:48.516  7585  7610 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
08-26 10:52:48.516  7585  7585 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 10:52:48.526  7585  7610 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 10:52:48.526  7585  7610 E BluetoothServiceJni: populateRssiValuesNative
,08-26 10:52:48.526  7585  7610 I bluedroid: getModelRssiValues
08-26 10:52:48.526  7585  7610 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 10:52:48.526  7585  7610 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 10:52:48.526  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 10:52:48.526  7585  7585 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:48.526  1018  1467 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 10:52:48.536  7585  7610 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-26 10:52:48.536  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.536  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.536  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.536  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.536  7585  7596 I bluedroid: config_hci_snoop_log
,08-26 10:52:48.536  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 10:52:48.546  1018  1048 D BluetoothManagerService: Ble is always on enable gatt
,08-26 10:52:48.546  1018  1048 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 10:52:48.546  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 10:52:48.546  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 10:52:48.546  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:48.546  7585  7585 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 10:52:48.546  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 10:52:48.546  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 10:52:48.556  7585  7607 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 10:52:48.556  7585  7607 D BluetoothAdapterProperties: Setting state to 11
,08-26 10:52:48.556  7585  7607 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 10:52:48.556  7585  7607 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:48.556  7585  7607 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 10:52:48.556  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:48.556  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
08-26 10:52:48.556  7585  7607 D BluetoothAdapterService: Autoconnection is available 
08-26 10:52:48.556  7585  7607 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 10:52:48.566  1875  1875 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-26 10:52:48.566  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:48.566  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:48.566  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 10:52:48.566  1172  1172 D BluetoothTile:  getBluetoothState : 11
08-26 10:52:48.566  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:48.566  1018  1328 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:48.566  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.566  1018  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 10:52:48.576  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.576  1018  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:48.576  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 10:52:48.576  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 10:52:48.576  1018  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 10:52:48.576  7585  7607 D BluetoothSecureManager: getInstant: null
08-26 10:52:48.576  7585  7607 D BluetoothSecureManager: calling getMethod for getService
08-26 10:52:48.576  7585  7607 D BluetoothSecureManager: calling getService
08-26 10:52:48.576  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 10:52:48.576  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
08-26 10:52:48.576  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 10:52:48.576  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:48.576  7585  7607 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@d3d978
,08-26 10:52:48.576  1018  1031 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 10:52:48.576  1018  1031 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 10:52:48.576  7585  7607 D BtConfig.SecureMode: isSecureModeOn:false
08-26 10:52:48.576  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 10:52:48.586  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:48.586  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 10:52:48.586  7585  7607 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:48.586  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 10:52:48.596  7585  7607 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-26 10:52:48.596  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 10:52:48.596  7585  7607 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 10:52:48.596  7585  7607 D BluetoothBondStateMachine: make,
,08-26 10:52:48.596  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 10:52:48.596  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 10:52:48.596  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 10:52:48.596  7585  7613 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 10:52:48.596  1018  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:48.596  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.606  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.606  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.606  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.606  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 10:52:48.606  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 10:52:48.606  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 10:52:48.606  7585  7585 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:48.606  7585  7585 D BtGatt.GattService: Received start request. Starting profile...
08-26 10:52:48.606  7585  7585 D BtGatt.GattService: start()
08-26 10:52:48.606  7585  7585 D BtGatt.GattService: start()
08-26 10:52:48.606  7585  7585 I bluedroid: get_profile_interface gatt
08-26 10:52:48.606  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
08-26 10:52:48.606  1018  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.606  7585  7585 D BtGatt.AdvertiseManager: advertise manager created
08-26 10:52:48.606  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.606  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.606  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:48.606  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.616  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 10:52:48.616  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 10:52:48.616  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 10:52:48.616  7585  7585 D BtGatt.GattService: mStartError = false
08-26 10:52:48.616  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892,
,08-26 10:52:48.616  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.616  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.616  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:48.616  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.616  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.626  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 10:52:48.626  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 10:52:48.626  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 10:52:48.626  7585  7585 D HeadsetService: Received start request. Starting profile...
08-26 10:52:48.626  7585  7585 D HeadsetService: start()
,08-26 10:52:48.626  1018  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.626  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.626  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.626  1018  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.626  7585  7585 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:48.626  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:48.626  7585  7585 D HeadsetStateMachine: make
,08-26 10:52:48.626  7585  7585 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 10:52:48.626  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 10:52:48.626  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 10:52:48.626  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 10:52:48.636  1018  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.636  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.636  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.636  1018  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.636  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.636  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 10:52:48.636  1018  4342 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 10:52:48.636  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.636  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:48.636  1018  4342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.636  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 10:52:48.636  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 10:52:48.636  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 10:52:48.636  1018  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.636  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.636  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:48.636  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.636  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.646  1018  1483 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 10:52:48.646  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.646  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.646  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.646  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 10:52:48.646  7585  7585 I bluedroid: get_profile_interface handsfree
08-26 10:52:48.646  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 10:52:48.646  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 10:52:48.646  7585  7607 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:48.646  1018  4352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.646  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.646  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:48.646  1018  4352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:48.646  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.646  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 10:52:48.646  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 10:52:48.646  7585  7607 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 10:52:48.646  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:48.646  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 10:52:48.656  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:48.656  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 10:52:48.656  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:48.656  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 10:52:48.666  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:48.666  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 10:52:48.666  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 10:52:48.666  7585  7607 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 10:52:48.666  7585  7607 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 10:52:48.666  7585  7607 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 10:52:48.666  7585  7585 I DualScoManager: Instantiating Dual Sco Manager
,08-26 10:52:48.666  7585  7585 I DualScoManager: Set HeadsetServiceHelper
,08-26 10:52:48.666  7585  7585 D BluetoothAtMessage: createCMTIContentObservers
,08-26 10:52:48.666  1018  1266 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 10:52:48.666  1018  1266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:48.666  1018  1266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:48.666  1018  1266 D SettingsProvider: selectionArgs: false
08-26 10:52:48.666  1018  1266 D SettingsProvider: selectionArgs: 1002
08-26 10:52:48.666  1018  1266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 10:52:48.666  1018  1266 D SettingsProvider: ret = -1
08-26 10:52:48.666  7585  7617 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 10:52:48.666  7585  7585 D HeadsetService: mStartError = false
08-26 10:52:48.666  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:48.666  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 10:52:48.676  7585  7617 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 10:52:48.676  7585  7617 D HeadsetStateMachine: map size, before remove : 0
,08-26 10:52:48.676  7585  7617 D HeadsetStateMachine: map size, after remove: 0
,08-26 10:52:48.676  7585  7585 D A2dpService: Received start request. Starting profile...
08-26 10:52:48.676  7585  7585 D A2dpService: start()
,08-26 10:52:48.676  7585  7585 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 10:52:48.676  7585  7585 I bluedroid: get_profile_interface avrcp
,08-26 10:52:48.686  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:48.686  7585  7585 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 10:52:48.686  7585  7585 D Avrcp   : Initialize Media Controller
08-26 10:52:48.686  7585  7585 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 10:52:48.686  7585  7585 E Avrcp   : getActiveSessions
08-26 10:52:48.686  7585  7585 D Avrcp   : pick active media Controller
08-26 10:52:48.686  7585  7585 D Avrcp   : Get the active Media Controller 
,08-26 10:52:48.686  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:48.706  7585  7585 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 10:52:48.706  7585  7620 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,08-26 10:52:48.706  7585  7585 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:48.706  7585  7585 D A2dpStateMachine: make
,08-26 10:52:48.706  7585  7585 I bluedroid: get_profile_interface a2dp
08-26 10:52:48.706  7585  7622 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 10:52:48.706  7585  7585 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 10:52:48.706  7585  7585 D A2dpService: mStartError = false
08-26 10:52:48.706  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:48.706  7585  7621 D A2dpStateMachine: Enter Disconnected: -2
,08-26 10:52:48.716  7585  7585 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 10:52:48.716  7585  7585 D HidService: Received start request. Starting profile...
08-26 10:52:48.716  7585  7585 D HidService: start()
08-26 10:52:48.716  7585  7585 I bluedroid: get_profile_interface hidhost
08-26 10:52:48.716  7585  7585 D HidService: setHidService(): set to: null
08-26 10:52:48.716  7585  7585 D HidService: mStartError = false
08-26 10:52:48.716  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:48.716  7585  7585 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 10:52:48.716  7585  7585 D HealthService: Received start request. Starting profile...
08-26 10:52:48.716  7585  7585 D HealthService: start()
,08-26 10:52:48.716  7585  7585 I bluedroid: get_profile_interface health
,08-26 10:52:48.716  7585  7585 D HealthService: mStartError = false
08-26 10:52:48.716  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
08-26 10:52:48.716  7585  7585 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 10:52:48.726  1427  1438 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 10:52:48.726  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 10:52:48.726  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 10:52:48.726  1427  1438 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 10:52:48.726  7585  7620 D BluetoothMediaBrowser: no now playing list
,08-26 10:52:48.726  7585  7620 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-26 10:52:48.726  7585  7585 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 10:52:48.726  7585  7585 D PanService: Received start request. Starting profile...
08-26 10:52:48.726  7585  7585 D PanService: start()
08-26 10:52:48.726  7585  7585 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 10:52:48.726  7585  7585 I bluedroid: get_profile_interface pan
,08-26 10:52:48.726  7585  7585 D PanService: mStartError = false
08-26 10:52:48.726  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:48.726  7585  7585 D BluetoothMapService: Received start request. Starting profile...
08-26 10:52:48.726  7585  7585 D BluetoothMapService: start()
,08-26 10:52:48.736  7585  7585 D BluetoothMapService: mStartError = false
08-26 10:52:48.736  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:48.736  7585  7585 D HeadsetStateMachine: Proxy object connected
08-26 10:52:48.736  7585  7585 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 10:52:48.736  7585  7617 D HeadsetStateMachine: Disconnected process message: 11
,08-26 10:52:48.736  7585  7585 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 10:52:48.736  7585  7585 D SapService: Received start request. Starting profile...
,08-26 10:52:48.736  7585  7585 D SapService: start()
08-26 10:52:48.736  7585  7585 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 10:52:48.736  7585  7585 I bluedroid: get_profile_interface sap
,08-26 10:52:48.736  7585  7585 D SapService: mStartError = false
08-26 10:52:48.736  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
08-26 10:52:48.736  7585  7585 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 10:52:48.736  7585  7617 D HeadsetStateMachine: Disconnected process message: 18
08-26 10:52:48.736  7585  7585 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 10:52:48.736  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 10:52:48.736  7585  7585 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 10:52:48.736  7585  7585 D BluetoothA2dp: Proxy object connected
08-26 10:52:48.736  7585  7585 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 10:52:48.736  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 10:52:48.736  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 10:52:48.736  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 10:52:48.736  7585  7617 D HeadsetStateMachine: Disconnected process message: 10
,08-26 10:52:48.736  7585  7617 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
08-26 10:52:48.736  7585  7617 D HeadsetStateMachine: Disconnected process message: 11
,08-26 10:52:48.746  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 10:52:48.756  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 10:52:48.756  7585  7585 E BluetoothAdapterService(819050642): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 10:52:48.766  7585  7607 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 10:52:48.766  7585  7607 I bluedroid: enable
,08-26 10:52:48.766  7585  7607 I bt_hci_bdroid: init
08-26 10:52:48.766  7585  7626 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 10:52:48.766  7585  7607 I bt_vendor: bt-vendor : init
08-26 10:52:48.766  7585  7607 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 10:52:48.766  7585  7607 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 10:52:48.766  7585  7607 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 10:52:48.766  7585  7607 D bt_userial_mct: userial_init
08-26 10:52:48.766  7585  7607 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 10:52:48.766  7585  7607 I bt_vendor: Starting hciattach daemon
08-26 10:52:48.766  7585  7607 I bt_vendor: try to set false
,08-26 10:52:48.766  7585  7607 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 10:52:48.766  7585  7607 I bt_vendor: Starting hciattach daemon
08-26 10:52:48.766  7585  7607 I bt_vendor: try to set true
,08-26 10:52:48.776  1018  2046 V SAMP_SPCM_test: CSC File load.. 
,08-26 10:52:48.786  1018  3400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 10:52:48.786  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction,
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 10:52:48.796  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn,
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,08-26 10:52:48.826  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize,
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering,
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-26 10:52:48.836  1018  2046 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-26 10:52:48.836  1018  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-26 10:52:48.836  1018  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:48.836  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-26 10:52:48.836  1018  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:48.836  1018  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:48.836  1018  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:48.846  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:48.856  7638  7638 E Zygote  : MountEmulatedStorage()
,08-26 10:52:48.856  7638  7638 E Zygote  : v2
08-26 10:52:48.856  7638  7638 I libpersona: KNOX_SDCARD checking this for 1000
08-26 10:52:48.856  7638  7638 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:48.856  7638  7638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:48.856  7638  7638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:48.856  7638  7638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 10:52:48.866  1018  2046 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7638 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 10:52:48.876  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:48.876  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 10:52:48.886  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 10:52:48.896  7638  7638 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 10:52:48.896  7638  7638 D ActivityThread: Added TimaKeyStore provider,
,08-26 10:52:48.896  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 10:52:48.916  7638  7638 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 10:52:48.956  1018  1018 I ActivityManager: Killing 7185:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 10:52:48.956  1018  2046 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 10:52:49.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 10:52:49.156  7661  7661 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-26 10:52:49.166  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 10:52:49.216  7585  7607 I bt_vendor: bluetooth satus is on
,08-26 10:52:49.216  7585  7628 D bt_userial_mct: userial_open(port:0),
08-26 10:52:49.216  7585  7628 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 10:52:49.226  7585  7628 I bt_vendor: Done intiailizing UART
,08-26 10:52:49.226  7585  7628 I bt_vendor: Done intiailizing UART
08-26 10:52:49.226  7585  7628 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 10:52:49.226  7585  7628 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 10:52:49.236  7585  7664 D bt_userial_mct: Entering userial_read_thread()
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 10:52:49.236  7585  7626 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 10:52:49.326  7585  7626 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 10:52:49.336  7585  7626 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41baed1 
,08-26 10:52:49.336  7585  7626 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41baed1 
,08-26 10:52:49.346  7585  7610 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 10:52:49.356  7585  7610 E bt-btif : Calling BTA_HhEnable
,08-26 10:52:49.356  7585  7610 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 10:52:49.356  7585  7610 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 10:52:49.356  7585  7610 E BluetoothServiceJni: populateRssiValuesNative
,08-26 10:52:49.356  7585  7610 I bluedroid: getModelRssiValues
08-26 10:52:49.356  7585  7610 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 10:52:49.356  7585  7610 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 10:52:49.356  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 10:52:49.356  7585  7610 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 10:52:49.366  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:49.366  7585  7610 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 10:52:49.366  7585  7610 D BluetoothAdapterProperties: Scan Mode:20
,08-26 10:52:49.376  7585  7610 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:49.376  7585  7610 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-26 10:52:49.376  7585  7610 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-26 10:52:49.376  7585  7610 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 10:52:49.376  7585  7610 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 10:52:49.376  7585  7610 E bt-btif : btif_sock_init: !vhci_init
,08-26 10:52:49.376  7585  7610 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 10:52:49.376  7585  7610 D IOP_DB_BT: db_open: db_open : handle 3028193296l, read 13894 bytes onto local cache
,08-26 10:52:49.376  7585  7610 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 10:52:49.376  7585  7610 D IOP_DB_BT: db_query: result 1
,08-26 10:52:49.376  7585  7610 I         : iop_db_open: iop_db_open status 0
,08-26 10:52:49.376  7585  7664 E bt_mct  : hci lib postload completed
,08-26 10:52:49.386  7585  7610 D bte_conf: Device ID record 1 : primary,
08-26 10:52:49.386  7585  7610 D bte_conf:   vendorId            = 0075
08-26 10:52:49.386  7585  7610 D bte_conf:   vendorIdSource      = 0001
08-26 10:52:49.386  7585  7610 D bte_conf:   product             = 0100
08-26 10:52:49.386  7585  7610 D bte_conf:   version             = 0200
08-26 10:52:49.386  7585  7610 D bte_conf:   clientExecutableURL = 
08-26 10:52:49.386  7585  7610 D bte_conf:   serviceDescription  = 
08-26 10:52:49.386  7585  7610 D bte_conf:   documentationURL    = 
08-26 10:52:49.386  7585  7610 D bte_conf: bte_load_did_conf no section named DID2.
08-26 10:52:49.386  7585  7610 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 10:52:49.386  7585  7607 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 10:52:49.386  7585  7607 D BluetoothAdapterProperties: ScanMode =  20
08-26 10:52:49.386  7585  7607 D BluetoothAdapterProperties: State =  11
,08-26 10:52:49.386  1018  4342 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 10:52:49.386  7585  7607 D BluetoothAdapterProperties: Setting state to 12
,08-26 10:52:49.386  7585  7607 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 10:52:49.386  7585  7610 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 10:52:49.396  7585  7610 D BluetoothAdapterProperties: Scan Mode:21
,08-26 10:52:49.396  7585  7610 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:49.396  1018  1137 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 10:52:49.396  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:49.396  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:49.396  1018  1137 D SettingsProvider: selectionArgs: false
08-26 10:52:49.396  1018  1137 D SettingsProvider: selectionArgs: 1002
08-26 10:52:49.396  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:49.396  1018  1137 D SettingsProvider: ret = -1
,08-26 10:52:49.396  7585  7607 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 10:52:49.396  7585  7607 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 10:52:49.396  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:49.396  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.396  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.396  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.396  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:49.416  7585  7607 D BluetoothAdapterService: Autoconnection is available 
08-26 10:52:49.416  7585  7607 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 10:52:49.416  7585  7607 D BluetoothAdapterService: starting service from this receiver
08-26 10:52:49.416  1018  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 10:52:49.416  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 10:52:49.416  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.416  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.416  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 10:52:49.426  7585  7607 I BluetoothAdapterState: Entering On State from state = 11
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:49.426  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:49.426   288   288 E SMD     : DCD OFF
08-26 10:52:49.426  1427  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 10:52:49.426  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:49.426  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 10:52:49.426  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:49.426  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.426  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.426  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 10:52:49.436  1427  1448 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 10:52:49.436  1427  3298 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.436  1427  3298 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:49.436  1427  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 10:52:49.436  7585  7585 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 10:52:49.436  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:49.436  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 10:52:49.436  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.436  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.436  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 10:52:49.446  1427  1438 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 10:52:49.446  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:49.446  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 10:52:49.446  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 10:52:49.446  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 10:52:49.446  7503  7513 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.446  7503  7513 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:49.446  1308  1317 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 10:52:49.446  1308  1317 D Bluetoothsap: Binding service...
08-26 10:52:49.446  1308  1317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:49.476  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:49.476  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:49.486  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:49.486  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23539e8f added. We now have 8 listener(s)
,08-26 10:52:49.486  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:49.486  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 10:52:49.486  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 10:52:49.486  1018  1030 D SecContentProvider2: mCursor = null
,08-26 10:52:49.486  1018  1030 D WifiService: setWifiEnabled: false pid=6847, uid=10171
,08-26 10:52:49.486  1018  1030 D SettingsProvider: name = wifi_on
,08-26 10:52:49.496  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:49.496  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 10:52:49.496  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 10:52:49.496  1018  1031 D SecContentProvider2: mCursor = null
,08-26 10:52:49.496  1018  1031 D WifiService: setWifiEnabled: true pid=6847, uid=10171
,08-26 10:52:49.496  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 10:52:49.496  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-26 10:52:49.496  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 10:52:49.496  1018  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 10:52:49.496  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 10:52:49.496  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 10:52:49.496  1018  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 10:52:49.496  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:49.496  1018  1031 D SettingsProvider: name = wifi_on
,08-26 10:52:49.506  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 10:52:49.546  1018  3370 D SSRM:n  : SIOP:: AP = 330
,08-26 10:52:49.606  1018  1048 I art     : Explicit concurrent mark sweep GC freed 31785(1833KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.621ms total 156.788ms
08-26 10:52:49.606  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 10:52:49.606  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.606  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.606  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.606  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.606  1308  1317 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 10:52:49.606  1441  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 10:52:49.606  1441  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:49.606  1308  1318 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 10:52:49.616  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 10:52:49.616  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.616  7585  7585 I BluetoothPbapService: Handler(): got msg=1
,08-26 10:52:49.616  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.616  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.616  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.616  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 10:52:49.616  1308  1317 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 10:52:49.616  1308  1317 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:49.616  1308  7055 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 10:52:49.616  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:49.616  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:49.616  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.616  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.616  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.626  1308  1308 D HeadsetProfile: Bluetooth service connected
08-26 10:52:49.626  1308  7055 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:49.626  1975  3033 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.626  1975  3033 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:49.626  7585  7671 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 10:52:49.626  7585  7598 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.626  7585  7598 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
08-26 10:52:49.626  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.626  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 10:52:49.626  1308  7055 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 10:52:49.626  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 10:52:49.626  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.626  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 10:52:49.626  1308  1308 D SapProfile: Bluetooth service connected
08-26 10:52:49.626  1308  1308 D Bluetoothsap: getConnectedDevices()
,08-26 10:52:49.626  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.626  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.626  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.626  7585  7671 D BluetoothSocket: bindListen(): myUserId = 0
08-26 10:52:49.626  7585  7671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:49.626  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:49.626  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:49.626  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 10:52:49.626  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 10:52:49.626  1018  1018 D BluetoothA2dp: Proxy object connected
,08-26 10:52:49.626  7585  7596 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 10:52:49.636  1308  1317 D BluetoothPan: Binding service...
,08-26 10:52:49.636  1308  1308 D BluetoothPbap: Proxy object connected
08-26 10:52:49.636  1308  1308 D PbapServerProfile: Bluetooth service connected
,08-26 10:52:49.636  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 10:52:49.636  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 10:52:49.636  1308  1308 D BluetoothInputDevice: Proxy object connected
08-26 10:52:49.636  1308  1308 D HidProfile: Bluetooth service connected
,08-26 10:52:49.636  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.636  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.636  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 10:52:49.636  7585  7671 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-26 10:52:49.636  7585  7671 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 10:52:49.636  7585  7671 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:49.636  7585  7671 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ac711c
,08-26 10:52:49.636  7585  7671 D BluetoothSocket: channel: 19
,08-26 10:52:49.636  7585  7671 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 10:52:49.636  1427  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:49.636  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 10:52:49.636  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:49.636  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.636  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.636  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.636  1427  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:49.636  1308  1308 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:49.636  1455  6310 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.636  1455  6310 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:49.636  1308  1318 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:49.636  1308  1308 D PanProfile: Bluetooth service connected
,08-26 10:52:49.646  1308  1318 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:49.646  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 10:52:49.646  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.646  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.646  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.646  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.646  1018  1048 D BluetoothPan: Binding service...
,08-26 10:52:49.646  1308  1308 D BluetoothA2dp: Proxy object connected
08-26 10:52:49.646  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 10:52:49.646  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 10:52:49.646  1308  1308 D A2dpProfile: Bluetooth service connected
,08-26 10:52:49.646  6847  6862 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 10:52:49.646  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:49.646  6847  6862 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:49.646  1455  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 10:52:49.646  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 10:52:49.646  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 10:52:49.646  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.646  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.646  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.656  1455  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 10:52:49.656  1308  7672 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 10:52:49.656  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 10:52:49.656  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.656  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.656  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.656  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.656  1308  1308 D BluetoothMap: Proxy object connected
,08-26 10:52:49.656  1308  1308 D MapProfile: Bluetooth service connected
,08-26 10:52:49.656  1172  1186 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 10:52:49.656  1172  1186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 10:52:49.656  1308  1308 D BluetoothMap: getConnectedDevices()
08-26 10:52:49.656  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 10:52:49.656  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 10:52:49.666  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.666  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-26 10:52:49.666  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 10:52:49.666  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3d1a2bb, true
08-26 10:52:49.666  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-26 10:52:49.666  1427  1427 D BluetoothHeadset: registerMessageListener
,08-26 10:52:49.676  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 10:52:49.676  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.676  1172  1172 D BluetoothTile:  getBluetoothState : 12
08-26 10:52:49.676  1875  1875 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 10:52:49.676  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:49.676  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:49.676  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:49.686  1018  1498 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-26 10:52:49.686  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 10:52:49.686  1018  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 10:52:49.686  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 10:52:49.686  1018  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 10:52:49.686  1018  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.686  7585  7596 D HeadsetService: registerMessageListener
,08-26 10:52:49.686  7585  7596 D HeadsetService: registerMessageListener
,08-26 10:52:49.686  7585  7617 D HeadsetStateMachine: Disconnected process message: 70
08-26 10:52:49.686  7585  7617 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@188ae125
08-26 10:52:49.696  1018  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.696  1172  1726 D BluetoothTile:  handleUpdatestate:false name:null
08-26 10:52:49.696  1018  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-26 10:52:49.696  1018  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:49.696  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 10:52:49.696  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 10:52:49.696  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 10:52:49.696  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 10:52:49.696  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 10:52:49.696  7585  7675 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 10:52:49.696  1308  1308 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 10:52:49.706  1308  1308 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 10:52:49.706  1308  1308 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-26 10:52:49.706  1308  1308 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 10:52:49.706  7585  7617 D HeadsetStateMachine: Disconnected process message: 9
,08-26 10:52:49.706  7585  7617 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 10:52:49.716  7585  7675 D BluetoothSocket: bindListen(): myUserId = 0
08-26 10:52:49.716  7585  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:49.716  7585  7675 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-26 10:52:49.716  7585  7675 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 10:52:49.716  7585  7675 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:49.716  7585  7675 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b5952fa
,08-26 10:52:49.716  7585  7675 D BluetoothSocket: channel: 5
,08-26 10:52:49.716   283   701 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 10:52:49.716   283   701 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 10:52:49.716   283   701 V voice   : voice_set_parameters: exit with code(-2)
,08-26 10:52:49.716   283   701 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-26 10:52:49.716  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:49.716  1018  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 10:52:49.716  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 10:52:49.726   283   701 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 10:52:49.726   283   701 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 10:52:49.726   283   701 V audio_hw_primary: adev_set_parameters: exit
,08-26 10:52:49.726  7585  7617 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 10:52:49.726  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.726  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.726  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 10:52:49.736  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:49.736  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 10:52:49.736  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.736  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 10:52:49.746  7585  7585 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:49.746  7585  7585 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 10:52:49.746  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 10:52:49.746  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.746  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.746  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.746  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 10:52:49.766  1975  1975 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:49.766  1018  4352 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 10:52:49.766  1018  4352 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:49.766  1018  4352 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.766  1018  4352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:49.766  1018  4352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:49.776  1975  7689 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 10:52:49.776  1975  1975 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 10:52:49.776  1018  4352 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 10:52:49.776  1018  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:49.786  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.786  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:49.786  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:49.796  7585  7691 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 10:52:49.796  7585  7691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:49.796  7585  7691 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-26 10:52:49.796  7585  7691 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 10:52:49.796  7585  7691 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 10:52:49.796  7585  7691 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@559a4c6
08-26 10:52:49.796  7585  7691 D BluetoothSocket: channel: 12
08-26 10:52:49.796  7585  7691 I BtOppRfcommListener: Accept thread started.
,08-26 10:52:49.796  1018  1467 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 10:52:49.796  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:49.796  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 10:52:49.796  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 10:52:49.806  1975  7689 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 10:52:49.836  1018  1046 D Tethering: interfaceAdded wlan0
08-26 10:52:49.836  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 10:52:49.836  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:49.846  1018  1132 E Tethering: No numeric data
08-26 10:52:49.846  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:49.846  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:52:49.846  1018  1132 D Tethering: clearTetheredNotification()
08-26 10:52:49.846  1018  1132 D Tethering: InitialState.processMessage what=4
08-26 10:52:49.856  1018  1046 D Tethering: interfaceAdded p2p0
,08-26 10:52:49.856  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:49.856  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:49.856  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:49.856  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:49.856  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:49.856  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-26 10:52:49.866   278   991 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 10:52:49.866   278   991 D SoftapController: Softap fwReload - Ok
,08-26 10:52:49.866  1018  1132 E Tethering: No numeric data
,08-26 10:52:49.866  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 10:52:49.866  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 10:52:49.866  1018  1132 D Tethering: clearTetheredNotification()
08-26 10:52:49.876  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 10:52:49.876  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:49.876  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:49.876   278   991 D CommandListener: Setting iface cfg
08-26 10:52:49.876  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:49.876   278   991 D CommandListener: Trying to bring down wlan0
08-26 10:52:49.876  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:49.876   278   991 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:49.876  1018  1124 V NetworkStats: performPollLocked() took 20ms
08-26 10:52:49.876  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:49.876  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:49.876  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 10:52:49.876  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:49.876  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:49.886  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:49.886  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:49.886  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 10:52:49.886  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:49.886  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-26 10:52:49.886  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:49.886  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:49.926  7694  7694 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-26 10:52:49.926  7694  7694 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 10:52:49.926  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 10:52:49.946  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-26 10:52:49.946   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7694
08-26 10:52:49.946   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 10:52:49.946  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 10:52:49.946  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-26 10:52:49.946  7694  7694 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 10:52:49.946  7694  7694 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 10:52:49.946   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7694
08-26 10:52:49.946   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 10:52:49.986  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 10:52:49.986  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:49.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 10:52:49.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:49.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:49.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:49.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:49.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:49.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 10:52:49.986  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 10:52:49.996  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:49.996  1172  1172 D HotspotTile: onReceive : 2, 0,
,08-26 10:52:49.996  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:49.996  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:49.996  1018  1328 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:49.996  1018  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:49.996  1018  1328 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:49.996  1018  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:49.996  1018  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:49.996  1618  1618 I Hs20UtilService: Starting #19
08-26 10:52:49.996  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:50.006  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 10:52:50.006  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:50.006  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
08-26 10:52:50.006  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:50.076   351   351 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 10:52:50.086   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-26 10:52:50.096  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-26 10:52:50.136  7694  7694 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 10:52:50.136  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 10:52:50.156  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 10:52:50.156   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694
08-26 10:52:50.156   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 10:52:50.156  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 10:52:50.156  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-26 10:52:50.156  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 10:52:50.156  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:50.156  7694  7694 E wpa_supplicant: SIM READ ERROR
,08-26 10:52:50.156  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 10:52:50.156  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:50.156  7694  7694 E wpa_supplicant: SIM READ ERROR,
08-26 10:52:50.156  7694  7694 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 10:52:50.156  7694  7694 I wpa_supplicant: wpa_default_ap_write_once,
08-26 10:52:50.156  7694  7694 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 10:52:50.156  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:50.156  7694  7694 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-26 10:52:50.156  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:50.156  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 10:52:50.166  7694  7694 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 10:52:50.166  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:50.166  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 10:52:50.166  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:50.296  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 10:52:50.456  7694  7694 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 10:52:50.456  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 10:52:50.466  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 10:52:50.466   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694
08-26 10:52:50.466   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 10:52:50.466  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-26 10:52:50.466  7694  7694 I wpa_supplicant: ssSupport state is = 1
08-26 10:52:50.466  7694  7694 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 10:52:50.476  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 10:52:50.486  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 10:52:50.486   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7694,
08-26 10:52:50.486   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 10:52:50.486  7694  7694 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 10:52:50.486  7694  7694 I wpa_supplicant: ssSupport state is = 1
,08-26 10:52:50.486  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 10:52:50.486  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 10:52:50.486  7694  7694 E wpa_supplicant: SIM READ ERROR
08-26 10:52:50.486  7694  7694 I wpa_supplicant: wpa_default_ap_write_once,
08-26 10:52:50.486  7694  7694 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 10:52:50.486  7694  7694 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 10:52:50.496  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 10:52:50.496  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 10:52:50.496  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:50.496  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 10:52:50.496  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:50.496  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:50.566  7694  7694 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 10:52:50.566  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 10:52:50.686  7694  7694 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 10:52:50.686  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 10:52:50.686  7694  7694 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 10:52:50.696  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 10:52:50.696  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-26 10:52:50.696  7694  7694 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-26 10:52:50.696  7694  7694 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 10:52:50.696  7694  7694 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 10:52:50.696  7694  7694 E wpa_supplicant: SIM READ ERROR
08-26 10:52:50.696  7694  7694 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 10:52:50.716  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 10:52:50.726  7694  7694 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 10:52:50.726  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-26 10:52:50.726  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:50.726  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:50.726  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:50.726  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:50.726  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:50.726  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 10:52:50.726  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:50.726  1172  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 10:52:50.726  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 10:52:50.726  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:50.726  1172  1172 D HotspotTile: onReceive : 3, 0
,08-26 10:52:50.736  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:50.746  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:50.746  1018  4342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:50.746  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:50.746  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:50.746  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:50.746  1018  4342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:50.746  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:50.746  1018  1127 E WifiConfigStore: Not a HS20
08-26 10:52:50.746  1618  1618 I Hs20UtilService: Starting #20
,08-26 10:52:50.746  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 10:52:50.746  1618  1689 I Hs20UtilService: Message received 5011
,08-26 10:52:50.756  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 10:52:50.756  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 10:52:50.756  6629  6629 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 10:52:50.756  6629  6629 D SecurityLogAgent: StateMachine : Current State = 1
08-26 10:52:50.756  6629  6629 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 10:52:50.756  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 10:52:50.756  7694  7694 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 10:52:50.756  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 10:52:50.756  7694  7694 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 10:52:50.756  7694  7694 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 10:52:50.756  7694  7694 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 10:52:50.756  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 10:52:50.756  7694  7694 I wpa_supplicant: First Scan Start
,08-26 10:52:50.756  7694  7694 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 10:52:50.756  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-26 10:52:50.756  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:50.756  1018  1127 I WifiNative-HAL: startHal
08-26 10:52:50.756  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d5b188c
08-26 10:52:50.756  1018  1127 I WifiNative-HAL: Could not start hal
,08-26 10:52:50.766  7113  7113 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:50.766  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 10:52:50.766  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 10:52:50.766  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 10:52:50.766  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 10:52:50.766   278   991 D CommandListener: Setting iface cfg
,08-26 10:52:50.766   278   991 D CommandListener: Trying to bring up p2p0
,08-26 10:52:50.766  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:50.766  1018  1151 I WifiNative-HAL: startHal
08-26 10:52:50.766  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9ea6f9bc
08-26 10:52:50.766  1018  1151 I WifiNative-HAL: Could not start hal
08-26 10:52:50.766  1018  1151 E WifiScanningService: could not start HAL
08-26 10:52:50.766  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-26 10:52:50.766  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 10:52:50.766  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 10:52:50.766  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 10:52:50.766  1018  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:50.766  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 10:52:50.766  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 10:52:50.766  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 10:52:50.766  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-26 10:52:50.766  1018  1126 D WifiP2pService: P2pEnablingState
08-26 10:52:50.766  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 10:52:50.766  1018  1126 D WifiP2pService: P2p socket connection successful
,08-26 10:52:50.766  1018  1126 D WifiP2pService: P2pEnabledState
,08-26 10:52:50.776  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 10:52:50.776  7694  7694 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 10:52:50.776  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:50.776  7694  7694 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 10:52:50.776  7694  7694 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 10:52:50.776  1018  1127 E WifiStateMachine: Failed to set frequency band 0
,08-26 10:52:50.776  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 10:52:50.776  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 10:52:50.776  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:50.776  1018  1049 D WifiDisplayController: disconnect
08-26 10:52:50.776  1018  1049 D WifiDisplayController: updateConnection
08-26 10:52:50.776  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 10:52:50.776  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:50.776  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:50.776  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:50.776  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 10:52:50.776  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 10:52:50.776  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 10:52:50.776  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-26 10:52:50.776  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 10:52:50.776  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 10:52:50.776  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 10:52:50.786  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:50.786  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 10:52:50.786  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:50.786  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:50.786  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 10:52:50.786  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 10:52:50.786  1018  1484 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 10:52:50.786  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 10:52:50.786  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  secondary type: null
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  wps: 0
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  grpcapab: 0
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  devcapab: 0
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  status: 3
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  wfdInfo: null
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-26 10:52:50.786  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-26 10:52:50.786  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 10:52:50.786  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:50.786  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 10:52:50.786  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:50.796  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:50.796  7083  7083 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 10:52:50.796  7083  7083 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 10:52:50.796  7098  7098 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 10:52:50.806  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 10:52:50.806  1018  1126 D WifiP2pService: InactiveState
08-26 10:52:50.806  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-26 10:52:50.806  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 10:52:50.806  7694  7694 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-26 10:52:50.806  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-26 10:52:50.806  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 10:52:50.836  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 10:52:50.836  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-26 10:52:50.836  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 10:52:51.076   351   351 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:51.516  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:51.516  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:51.526  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 10:52:51.526  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 10:52:51.526  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a356a42 Bundle[{}]
,08-26 10:52:51.526  6847  6903 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 10:52:51.526  6847  6903 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 10:52:51.526  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 10:52:51.536  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 10:52:51.536  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 10:52:51.536  6847  6903 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 10:52:51.536  6847  6903 I System.out: Running OutgoingSocketThread
,08-26 10:52:51.546  6847  7702 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,08-26 10:52:51.546  6847  7702 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60780
,08-26 10:52:51.546  6847  7702 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 10:52:51.906  7694  7694 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-26 10:52:51.906  7694  7694 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-26 10:52:51.906  1018  7699 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 10:52:51.906  7694  7694 I wpa_supplicant: Trying to associate with SSID '4E47373030',
,08-26 10:52:51.906  7694  7694 I wpa_supplicant: Trying to associate with  'G700'
08-26 10:52:51.906  7694  7694 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-26 10:52:51.916  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 10:52:51.936  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:51.936  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:52.026  7694  7694 E wpa_supplicant: Cmd 35605 not handled
,08-26 10:52:52.026  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 10:52:52.026  7694  7694 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 10:52:52.026  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 10:52:52.026  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-26 10:52:52.026  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:52.026  7694  7694 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-26 10:52:52.026  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 10:52:52.026  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-26 10:52:52.026  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 10:52:52.026  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
,08-26 10:52:52.026  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 10:52:52.026  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 10:52:52.026  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-26 10:52:52.036  7694  7694 I wpa_supplicant: Associated with F4.99.3E
08-26 10:52:52.036  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 10:52:52.036  7694  7694 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 10:52:52.036  1018  1132 E Tethering: No numeric data
08-26 10:52:52.036  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 10:52:52.036  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:52:52.036  1018  1132 D Tethering: clearTetheredNotification()
,08-26 10:52:52.036  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:52.036  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 10:52:52.036  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 10:52:52.036  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:52.036  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:52.036  1172  1172 D HotspotTile: updateTetherState():false, false
,08-26 10:52:52.046  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-26 10:52:52.046  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:52.046  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:52.046  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:52.046  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:52.046  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:52.046  7694  7694 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 10:52:52.046  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:52.046  1018  1127 D SecContentProvider2: mCursor = null
08-26 10:52:52.046  7694  7694 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 10:52:52.046  7694  7694 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 10:52:52.046  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 10:52:52.046  7694  7694 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-26 10:52:52.046  7694  7694 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 10:52:52.046  7694  7694 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 10:52:52.056  7694  7694 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 10:52:52.056  7694  7694 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030,
08-26 10:52:52.056  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 10:52:52.056  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-26 10:52:52.056  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 10:52:52.056  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 10:52:52.056  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 10:52:52.066  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 10:52:52.066  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 10:52:52.066  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:52.066  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 10:52:52.066  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:52.066  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:52.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.066  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.066  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-26 10:52:52.066  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:52.066  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:52.066  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:52.066  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:52.066  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 10:52:52.076  1618  1618 I Hs20UtilService: Starting #21
,08-26 10:52:52.076  1618  1689 I Hs20UtilService: Message received 5007
,08-26 10:52:52.076  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:52.076  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:52.076  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 10:52:52.076  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:52.086  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 10:52:52.086  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:52.086  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:52.086  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 10:52:52.096   278   991 D CommandListener: Setting iface cfg
,08-26 10:52:52.096  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 10:52:52.106  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 10:52:52.106  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:52.106  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:52.106  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 10:52:52.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.116  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.116  1018  1127 E WifiNative-wlan0: do suspend false
,08-26 10:52:52.116  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-26 10:52:52.116  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 10:52:52.126  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 10:52:52.126  1018  1127 D SecContentProvider2: mCursor = null
,08-26 10:52:52.336  7705  7705 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 10:52:52.346  7705  7705 I dhcpcd  : version 5.5.6 starting,
,08-26 10:52:52.346  7705  7705 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 10:52:52.406  7705  7705 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-26 10:52:52.406  7705  7705 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 10:52:52.406  7705  7705 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-26 10:52:52.406  7705  7705 I dhcpcd  : bssid match
,08-26 10:52:52.406  7705  7705 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127,
,08-26 10:52:52.426   288   288 E SMD     : DCD OFF,
,08-26 10:52:52.466  7705  7705 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-26 10:52:52.546  6847  6903 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351),
08-26 10:52:52.546  6847  6903 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
08-26 10:52:52.546  6847  6903 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356),
08-26 10:52:52.546  6847  6903 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 10:52:52.546  6847  6903 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357),
08-26 10:52:52.546  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.546  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3684451c added. We now have 2 listener(s)
,08-26 10:52:52.556  7705  7705 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 10:52:52.556  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 10:52:52.556  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.556  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.556  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:52.556  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13082525 added. We now have 9 listener(s)
08-26 10:52:52.556  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:52.566  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:52.566  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:52.576  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:52.576  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:52.576  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:52.576  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.576  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f594ab added. We now have 3 listener(s)
,08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.586  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.586  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a1e9708 added. We now have 10 listener(s)
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:52.586  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:52.586  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:52.586  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:52.586  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 10:52:52.586  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:52.586  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3684451c removed from the list
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.586  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13082525 removed from the list,
08-26 10:52:52.586  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:52.586  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.586  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:52.586  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-26 10:52:52.586  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13082525 not in the list
08-26 10:52:52.586  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 10:52:52.586  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:52.596  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:52.596  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.596  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.596  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a1e9708 removed from the list,
08-26 10:52:52.596  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:52.596  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.596  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.596  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:52.596  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f594ab removed from the list
08-26 10:52:52.596  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.596  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293aeea1 added. We now have 2 listener(s)
,08-26 10:52:52.606  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:52.606  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.606  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:52.606  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.606  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3452d8c6 added. We now have 9 listener(s)
08-26 10:52:52.606  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:52.606  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:52.606  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:52.616  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:52.616  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:52.626  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:52.626  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:52.626  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198a1bb4 added. We now have 3 listener(s)
,08-26 10:52:52.626  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:52.626  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.626  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.626  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.626  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1576d3dd added. We now have 10 listener(s)
08-26 10:52:52.626  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:52.626  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:52.626  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:52.626  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:52.626  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:52.626  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:52.636  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:52.636  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:52.636  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:52.646  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-26 10:52:52.646  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:52.656  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:52.656  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:52.656  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:52.666  7585  7674 D BtGatt.GattService: registerClient() - UUID=06fd1712-91a6-4be5-943f-dd540b0e4fbc
,08-26 10:52:52.706  7585  7610 D BtGatt.GattService: onClientRegistered() - UUID=06fd1712-91a6-4be5-943f-dd540b0e4fbc, clientIf=6,
08-26 10:52:52.706  6847  6858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:52.706  7585  7611 D BtGatt.GattService: start scan with filters
08-26 10:52:52.706  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:52.706  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:52.706  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:52.706  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:52.716  7585  7615 D BtGatt.ScanManager: handling starting scan,
,08-26 10:52:52.716  7585  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b892
,08-26 10:52:52.716  7585  7610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 10:52:52.716  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.716  7585  7615 D BtGatt.ScanManager: allow scan with filters
08-26 10:52:52.716  7585  7615 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 10:52:52.716  7585  7615 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 10:52:52.726  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 10:52:52.726  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.726  7585  7615 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:52.726  7585  7615 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 10:52:52.726  7585  7610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 10:52:52.726  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:52.726  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:52.726  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 10:52:52.726  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-26 10:52:52.736  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 10:52:52.736  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.736  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:52.746  6847  6903 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 10:52:52.746  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:52.746  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 10:52:52.746  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:52.746  7585  7596 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:52.746  7585  7673 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-26 10:52:52.746  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:52.746  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:52.746  7585  7615 D BtGatt.ScanManager: filter size is 1
08-26 10:52:52.746  7585  7615 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 10:52:52.756  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:52.756  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:52.756  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:52.756  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:52.756  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:52.756  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 10:52:52.756  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.756  7585  7615 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:52.756  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:52.756  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:52.756  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:52.756  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 10:52:52.756  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.756  7585  7615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 10:52:52.766  7585  7610 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 10:52:52.766  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:52.776  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 10:52:52.776  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:52.776  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:52.776  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:52.776  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.776  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:52.776  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-26 10:52:52.776  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293aeea1 removed from the list
08-26 10:52:52.776  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.776  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3452d8c6 removed from the list
,08-26 10:52:52.776  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:52.776  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:52.786  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 10:52:52.786  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.786  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.786  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 10:52:52.786  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.786  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3452d8c6 not in the list
08-26 10:52:52.786  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 10:52:52.786  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1576d3dd removed from the list,
08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:52.796  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.796  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@198a1bb4 removed from the list
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2391d0d9 added. We now have 2 listener(s)
,08-26 10:52:52.796  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:52.796  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.796  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.796  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338e3a9e added. We now have 9 listener(s)
08-26 10:52:52.796  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:52.796  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:52.806  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:52.816  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-26 10:52:52.816  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:52.816  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.816  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c712d4c added. We now have 3 listener(s)
08-26 10:52:52.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 10:52:52.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.816  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 10:52:52.816  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc5a195 added. We now have 10 listener(s)
08-26 10:52:52.816  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:52.816  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:52.816  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:52.816  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:52.816  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:52.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:52.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:52.816  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 10:52:52.816  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:52.826  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:52.826  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:52:52.826  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-26 10:52:52.836  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:52.836  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 10:52:52.836  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:52.836  7585  7674 D BtGatt.GattService: registerClient() - UUID=c7b01d97-fe4f-418e-9253-09b6537a8272
,08-26 10:52:52.876  7585  7610 D BtGatt.GattService: onClientRegistered() - UUID=c7b01d97-fe4f-418e-9253-09b6537a8272, clientIf=6
,08-26 10:52:52.876  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:52.876  7585  7611 D BtGatt.GattService: start scan with filters
,08-26 10:52:52.876  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:52.876  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:52.876  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:52.876  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:52.886  7585  7610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 10:52:52.886  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:52.886  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:52.886  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 10:52:52.886  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: allow scan with filters
,08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 10:52:52.886  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 10:52:52.886  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 10:52:52.886  7585  7615 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 10:52:52.896  7585  7610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 10:52:52.896  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:52.896  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:52.896  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 10:52:52.896  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:52.906  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:52.906  6847  6903 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 10:52:52.906  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:52.906  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:52.906  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:52.906  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:52.906  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2391d0d9 removed from the list
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.906  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338e3a9e removed from the list
08-26 10:52:52.906  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:52.906  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 10:52:52.906  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:52.906  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338e3a9e not in the list
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:52.906  7585  7674 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:52.906  7585  7611 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:52.906  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 10:52:52.906  7585  7615 D BtGatt.ScanManager: filter size is 1
,08-26 10:52:52.906  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:52.906  7585  7615 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 10:52:52.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:52.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:52.916  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 10:52:52.916  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.916  7585  7615 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:52.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:52.916  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:52.916  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:52.916  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:52.916  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc5a195 removed from the list
08-26 10:52:52.916  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:52.916  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:52.916  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:52.916  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:52.916  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c712d4c removed from the list
,08-26 10:52:52.916  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.916  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.916  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a2bc211 added. We now have 2 listener(s)
,08-26 10:52:52.916  7585  7615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 10:52:52.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:52.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.926  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.926  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e8ff76 added. We now have 9 listener(s)
08-26 10:52:52.926  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:52.926  7585  7610 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 10:52:52.926  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:52.926  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:52.926  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:52.926  1018  1127 E WifiNative-wlan0: do suspend true
,08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:52.936  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:52.936  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:52.936  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:52.936  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:52.936  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:52.946  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:52.946  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc5d9e4 added. We now have 3 listener(s)
,08-26 10:52:52.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 10:52:52.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:52.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:52.946  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:52.946  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f96e4d added. We now have 10 listener(s)
,08-26 10:52:52.946  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:52.946  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:52.946  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:52.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:52.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:52.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:52.946  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:52.946  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:52.956  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:52.956  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:52.956  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:52.956  6847  6903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:52.956  7585  7611 D BtGatt.GattService: registerClient() - UUID=98406cd0-5e98-4cb4-9b85-c408851bbeb8
,08-26 10:52:52.956  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-26 10:52:52.956  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 10:52:52.966  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 10:52:52.966  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,08-26 10:52:52.966  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 10:52:52.966  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:52.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.966  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.966  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-26 10:52:52.966  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-26 10:52:52.966  1018  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-26 10:52:52.976  1018  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-26 10:52:52.976  1018  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 10:52:52.976  1018  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 10:52:52.986  1018  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 10:52:52.986  1018  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 10:52:52.986  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:52.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:52.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:52.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:52.996  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 10:52:52.996  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 10:52:52.996  1018  1498 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:52.996  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 10:52:52.996  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:52.996  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:52.996  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 10:52:52.996  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:52.996  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-26 10:52:52.996  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 10:52:52.996  1018  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-26 10:52:52.996  1618  1618 I Hs20UtilService: Starting #22
08-26 10:52:52.996  1618  1689 I Hs20UtilService: Message received 5007
08-26 10:52:52.996  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:52.996  1308  1308 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 10:52:53.006  7585  7610 D BtGatt.GattService: onClientRegistered() - UUID=98406cd0-5e98-4cb4-9b85-c408851bbeb8, clientIf=6
08-26 10:52:53.006  6847  6862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 10:52:53.006  7585  7673 D BtGatt.GattService: start scan with filters
,08-26 10:52:53.006  1018  1129 D ConnectivityService: LTETest block dns file not exists
,08-26 10:52:53.006  7585  7615 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:53.006  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:53.006  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:53.006  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:53.006  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:53.006  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.006  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 10:52:53.006  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-26 10:52:53.016  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:53.016  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:53.016  7585  7610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 10:52:53.016  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.016  7585  7615 D BtGatt.ScanManager: allow scan with filters
,08-26 10:52:53.016  7585  7615 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 10:52:53.016  7585  7615 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 10:52:53.026  1018  1129 V NetworkStats: performPollLocked() took 13ms
08-26 10:52:53.026  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.026  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 10:52:53.026  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 10:52:53.026  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 10:52:53.026  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 10:52:53.036  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 10:52:53.036  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 10:52:53.036  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 10:52:53.036  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-26 10:52:53.036  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 10:52:53.036  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.036  7585  7615 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:53.036  7585  7615 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:53.036  1018  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 10:52:53.036  1018  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 10:52:53.036  1018  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 10:52:53.036  1018  1498 D BatteryService: stay LED for fully charged
08-26 10:52:53.036  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 10:52:53.036  7585  7610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 10:52:53.036  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:53.036  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 10:52:53.036  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:53.046  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.046  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.046  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 10:52:53.046  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:53.046  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:53.046  1018  1129 E ConnectivityService: updateNetworkInfo()
08-26 10:52:53.046  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 10:52:53.046  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.046  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:53.046  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:53.046  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:53.046  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 10:52:53.046  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.046  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:53.046  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.046  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:53.046  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.046  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 10:52:53.046  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:53.046  1018  1129 V NetworkStats: performPollLocked() took 6ms
,08-26 10:52:53.046  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.046  1018  1018 I MotionRecognitionService: Plugged
08-26 10:52:53.046  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 10:52:53.056  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 10:52:53.056  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 10:52:53.056  7585  7585 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 10:52:53.066  7585  7617 D HeadsetStateMachine: Disconnected process message: 10
08-26 10:52:53.066  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:53.066  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 10:52:53.066  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:53.066  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:53.066  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 10:52:53.066  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 10:52:53.066  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 10:52:53.066  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:53.066  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:53.066  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 10:52:53.066  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 10:52:53.066  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 10:52:53.066  1618  1618 I Hs20UtilService: Starting #23
08-26 10:52:53.066  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-26 10:52:53.066  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:53.066  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:53.066  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 10:52:53.066  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:53.066  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 10:52:53.066  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 10:52:53.066  1018  7703 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:53.076  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.076  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.076  1618  1689 I Hs20UtilService: Message received 5007
08-26 10:52:53.076   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 10:52:53.076   278   987 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-26 10:52:53.076  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 10:52:53.076  1018  1129 D ConnectivityService:    accepting network in place of null
,08-26 10:52:53.076  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 10:52:53.076  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 10:52:53.076  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-26 10:52:53.076  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 10:52:53.076  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 10:52:53.076  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:53.076  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 10:52:53.086  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 10:52:53.086  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-26 10:52:53.086  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-26 10:52:53.086  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 10:52:53.086  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 10:52:53.086  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 10:52:53.086  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 10:52:53.086  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 10:52:53.086  1018  1124 V NetworkStats: updateIfacesLocked(),
08-26 10:52:53.086  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 10:52:53.086  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-26 10:52:53.086  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:53.086  1172  1716 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:52:53.086  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 10:52:53.086  1308  2237 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 10:52:53.086  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.086  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:52:53.086  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.086  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.086  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.086  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 10:52:53.086  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:53.086  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:53.086  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:53.086  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:53.086  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.086  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:53.086  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:53.086  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a2bc211 removed from the list
08-26 10:52:53.086  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.086  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e8ff76 removed from the list
08-26 10:52:53.086  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:53.086  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:53.086  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-26 10:52:53.086  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 10:52:53.086  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 10:52:53.086  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-26 10:52:53.086  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.086  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-26 10:52:53.086  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 10:52:53.086  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 10:52:53.096  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 10:52:53.096  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.096  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e8ff76 not in the list
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 10:52:53.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.096  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:53.096  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.096  7585  7598 D BtGatt.GattService: stopScan() - queue size =1
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.096  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:53.096  7585  7615 D BtGatt.ScanManager: filter size is 1,
,08-26 10:52:53.096  7585  7611 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 10:52:53.096  7585  7615 D BtGatt.ScanManager: delete FilterIndex - 5
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:53.096  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:53.096  7585  7610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 10:52:53.096  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.096  7585  7615 D BtGatt.ScanManager: stopping BLe Batch
08-26 10:52:53.096  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:53.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:53.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:53.106  7585  7610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 10:52:53.106  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.106  7585  7615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 10:52:53.106  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 10:52:53.106  1018  1129 V NetworkStats: updateIfacesLocked()
08-26 10:52:53.106  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.106  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-26 10:52:53.106  7585  7610 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 10:52:53.106  7585  7610 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 10:52:53.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:53.106  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 10:52:53.106  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 10:52:53.106  1018  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 10:52:53.106  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 10:52:53.106  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:53.106  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:53.106  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.106  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:53.106  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f96e4d removed from the list
08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:53.106  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.106  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:53.106  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:53.106  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:53.106  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:53.106  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc5d9e4 removed from the list
08-26 10:52:53.106  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:53.106  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@227ba249 added. We now have 2 listener(s)
,08-26 10:52:53.106  1618  1618 I Hs20UtilService: Starting #24
08-26 10:52:53.106  1018  1129 V NetworkStats: performPollLocked() took 4ms
08-26 10:52:53.106  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.116  1618  1689 I Hs20UtilService: Message received 5007
08-26 10:52:53.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:53.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 10:52:53.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:53.116  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:53.116  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278c874e added. We now have 9 listener(s)
08-26 10:52:53.116  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:53.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:53.116  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 10:52:53.116  1308  1308 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 10:52:53.116  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:53.116  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 10:52:53.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.116  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.116  1172  1716 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 10:52:53.116  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 10:52:53.116  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 10:52:53.116  1172  1716 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 10:52:53.126  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 10:52:53.126  1018  1328 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:53.126  6847  6903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:53.126  1018  4352 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 10:52:53.126  1018  4352 D SecContentProvider2: mCursor = null
08-26 10:52:53.126  1018  1481 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 10:52:53.126  1018  1481 D SecContentProvider2: mCursor = null
,08-26 10:52:53.126  1018  1475 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 10:52:53.126  1018  1475 D SecContentProvider2: mCursor = null
08-26 10:52:53.126  6847  6903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:53.126  6847  6903 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:53.126  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1140817c added. We now have 3 listener(s)
08-26 10:52:53.136  1018  1266 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 10:52:53.136  1018  1266 D SecContentProvider2: mCursor = null
,08-26 10:52:53.136  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d31a05 added. We now have 10 listener(s)
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:53.136  6847  6903 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:53.136  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:53.136  6847  6903 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:53.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@227ba249 removed from the list,
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278c874e removed from the list
08-26 10:52:53.136  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:53.136  6847  6903 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:53.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:53.136  1018  1475 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 10:52:53.136  1018  1475 D SecContentProvider2: mCursor = null
,08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.136  6847  6903 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278c874e not in the list
08-26 10:52:53.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:53.136  1018  1266 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-26 10:52:53.136  1018  1266 D SecContentProvider2: mCursor = null,
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d31a05 removed from the list
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:53.136  6847  6903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:53.136  6847  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:53.136  6847  6903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:53.136  6847  6903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1140817c removed from the list
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 10:52:53.146  6847  6903 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:53.146  6847  7743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
08-26 10:52:53.146  6847  7743 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
08-26 10:52:53.146  6847  7743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 10:52:53.156  6847  7744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name)
,08-26 10:52:53.156  6847  7744 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
08-26 10:52:53.156  6847  7744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 10:52:53.156  6847  6903 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 10:52:53.156  6847  6903 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 10:52:53.156  6847  6903 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 10:52:53.156  6847  6903 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 10:52:53.156  6847  6903 D com.test.thalitest.ThaliTestRunner: Total duration: 23514 ms
,08-26 10:52:53.156  6847  6903 I jxcore-log: *Native tests were executed*,
08-26 10:52:53.156  6847  6903 I jxcore-log: 
08-26 10:52:53.156  6847  6903 I jxcore-log: Total number of executed tests:  80
08-26 10:52:53.156  6847  6903 I jxcore-log: 
08-26 10:52:53.156  6847  6903 I jxcore-log: Number of passed tests:  80
08-26 10:52:53.156  6847  6903 I jxcore-log: 
08-26 10:52:53.156  6847  6903 I jxcore-log: Number of failed tests:  0
08-26 10:52:53.156  6847  6903 I jxcore-log: 
,08-26 10:52:53.156  6847  6903 I jxcore-log: Number of ignored tests:  0
08-26 10:52:53.156  6847  6903 I jxcore-log: 
08-26 10:52:53.156  6847  6903 I jxcore-log: Total duration:  23514
,08-26 10:52:53.156  6847  6903 I jxcore-log: 
08-26 10:52:53.156  6847  6903 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 10:52:53.156  6847  6903 I jxcore-log: 
,08-26 10:52:53.166  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.166  6847  6903 I jxcore-log: 
08-26 10:52:53.166   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-26 10:52:53.166  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.166  6847  6903 I jxcore-log: 
08-26 10:52:53.166  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.166  6847  6903 I jxcore-log: 
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
,08-26 10:52:53.176  6847  6847 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
,08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
,08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
08-26 10:52:53.176  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.176  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
,08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  1018  4352 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
08-26 10:52:53.186  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:53.186  6847  6903 I jxcore-log: 
,08-26 10:52:53.196  1172  1172 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 10:52:53.256  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 10:52:53.266  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:53.266  6847  6903 I jxcore-log: 
,08-26 10:52:53.276  1018  7703 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-26 10:52:53.376  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:52:53 GMT], X-Android-Received-Millis=[1472201573387], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472201573317]}
,08-26 10:52:53.376  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 10:52:53.376  1018  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 10:52:53.386  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-26 10:52:53.386  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 10:52:53.386  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 10:52:53.386  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 10:52:53.386  1172  1716 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 10:52:53.386  4835  6916 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 10:52:53.386  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 10:52:53.386  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
,08-26 10:52:53.386  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 10:52:53.386  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 10:52:53.386  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-26 10:52:53.386  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 10:52:53.386  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 10:52:53.396  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 10:52:53.396  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 10:52:53.416  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 10:52:53.416  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:53.416  6847  6903 I jxcore-log: 
,08-26 10:52:53.436  7746  7746 D AndroidRuntime: ,
08-26 10:52:53.436  7746  7746 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 10:52:53.436  7746  7746 D AndroidRuntime: CheckJNI is OFF,
,08-26 10:52:53.446  7746  7746 D AndroidRuntime: readGMSProperty: start
08-26 10:52:53.446  7746  7746 D AndroidRuntime: readGMSProperty: already setted!!
08-26 10:52:53.446  7746  7746 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 10:52:53.446  7746  7746 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-26 10:52:53.446  7746  7746 D AndroidRuntime: readGMSProperty: end
08-26 10:52:53.446  7746  7746 D AndroidRuntime: addProductProperty: start
,08-26 10:52:53.566  7746  7746 E AffinityControl: AffinityControl: registerfunction enter
,08-26 10:52:53.576  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:53.596  7746  7746 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 10:52:53.606  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 10:52:53.606  6847  6903 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:53.606  6847  6903 I jxcore-log: 
,08-26 10:52:53.616  1018  1328 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 10:52:53.616  1018  1328 D PackageManager: START PACKAGE DELETE: observer{48039837}
08-26 10:52:53.616  1018  1328 D PackageManager: pkg{<packageName>}
08-26 10:52:53.616  1018  1328 D PackageManager: user{0},
08-26 10:52:53.616  1018  1328 D PackageManager: caller{2000}
08-26 10:52:53.616  1018  1328 D PackageManager: flags{2}
08-26 10:52:53.616  1018  1328 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 10:52:53.616  1018  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 10:52:53.616  1018  1328 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-26 10:52:53.616  1018  1328 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 10:52:53.616  1018  1328 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 10:52:53.616  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 10:52:53.616  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
08-26 10:52:53.616  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 10:52:53.616  1018  1059 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
08-26 10:52:53.616  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 10:52:53.716  1018  1059 W PackageSettings: Skipping PackageSetting{15104129 com.example.hello/10168} due to missing metadata
,08-26 10:52:53.756  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 10:52:53.756  6847  6847 D AndroidRuntime: Shutting down VM,
08-26 10:52:53.756  6847  6847 E AndroidRuntime: FATAL EXCEPTION: main
08-26 10:52:53.756  6847  6847 E AndroidRuntime: Process: com.test.thalitest, PID: 6847
08-26 10:52:53.756  6847  6847 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } in io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@16daf97
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:943)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: Caused by: java.lang.SecurityException: ConnectivityService: Neither user 10171 nor current process has android.permission.ACCESS_NETWORK_STATE.
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1540)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	,at android.net.IConnectivityManager$Stub$Proxy.getActiveNetworkInfo(IConnectivityManager.java:1297)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.net.ConnectivityManager.getActiveNetworkInfo(ConnectivityManager.java:748)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor.updateConnectivityInfo(ConnectivityMonitor.java:152)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver.onReceive(ConnectivityMonitor.java:225)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-26 10:52:53.756  6847  6847 E AndroidRuntime: 	... 8 more
,08-26 10:52:53.766  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:53.766  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:53.766  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:53.766  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:53.776  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:53.786  7756  7756 E Zygote  : MountEmulatedStorage()
08-26 10:52:53.786  7756  7756 E Zygote  : v2
08-26 10:52:53.786  7756  7756 I libpersona: KNOX_SDCARD checking this for 1000
08-26 10:52:53.786  7756  7756 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:53.786  7756  7756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 10:52:53.786  1018  1044 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 10:52:53.786  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 10:52:53.786  7756  7756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:53.796  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
08-26 10:52:53.796  1018  1044 I ActivityManager: Killing 6847:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 10:52:53.796  7756  7756 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:53.796  1018  1044 I ActivityManager:   Force finishing activity ActivityRecord{6e26581 u0 com.test.thalitest/.MainActivity t2}
,08-26 10:52:53.806  1018  1044 D InputDispatcher: Focus left window: 6847
08-26 10:52:53.806   258   451 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 10:52:53.816   258  1156 I SurfaceFlinger: id=13 Removed NainActivit (-2/9),
,08-26 10:52:53.826  1018  1044 D InputDispatcher: Focused application released
08-26 10:52:53.826  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 10:52:53.826  1018  1044 D FocusedStackFrame: Set to : 0
08-26 10:52:53.826  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 10:52:53.826  1018  1044 W ActivityManager: mDVFSHelper.acquire()
,08-26 10:52:53.836  1018  1498 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 10:52:53.836  1018  1498 D SecContentProvider2: mCursor = null
,08-26 10:52:53.836  1018  1044 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 10:52:53.846  1018  1059 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-26 10:52:53.846  7756  7756 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:53.846  7756  7756 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:53.856  1018  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 10:52:53.866  1485  1485 D Launcher: onRestart, Launcher: 860659296
,08-26 10:52:53.876  1018  1031 F ActivityManager: Activity Manager Crash
08-26 10:52:53.876  1018  1031 F ActivityManager: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.pm.Settings.getInstallerPackageNameLPr(Settings.java:3747)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.pm.PackageManagerService.getInstallerPackageName(PackageManagerService.java:17595)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at android.app.ApplicationPackageManager.getInstallerPackageName(ApplicationPackageManager.java:1741)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at android.app.ApplicationErrorReport.getErrorReportReceiver(ApplicationErrorReport.java:171)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.startAppProblemLocked(ActivityManagerService.java:15280)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:15101)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15868)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:15377)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:15359)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1455)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 10:52:53.876  1018  1031 F ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 10:52:53.876  1485  1485 D Launcher: onStart, Launcher: 860659296
08-26 10:52:53.876  1485  1485 D Launcher.HomeView: onStart
,08-26 10:52:53.876  1485  1485 D Launcher: onResume, Launcher: 860659296
,08-26 10:52:53.876  1018  1483 D SettingsProvider: name = kids_home_mode
08-26 10:52:53.876  1018  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 10:52:53.876  1018  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 10:52:53.876  1018  1483 D SettingsProvider: selectionArgs: false
08-26 10:52:53.876  1018  1483 D SettingsProvider: selectionArgs: 10006
08-26 10:52:53.876  1018  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 10:52:53.876  1018  1483 D SettingsProvider: ret = -1
08-26 10:52:53.876  1485  1485 D Launcher.HomeView: onResume
,08-26 10:52:53.896  1485  1485 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 10:52:53.906  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 10:52:53.906  2640  2640 I art     : Explicit concurrent mark sweep GC freed 19562(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 805us total 38.062ms
,08-26 10:52:53.916  1875  1875 E SamsungIME: mOCRHelper is null
,08-26 10:52:53.926  1975  2161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 10:52:53.936  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-26 10:52:53.946  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 10:52:53.946  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 10:52:53.946  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 10:52:53.946  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-26 10:52:53.946  4835  4835 I art     : Explicit concurrent mark sweep GC freed 24063(1423KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.757ms total 92.814ms
,08-26 10:52:53.956  7756  7756 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 10:52:53.956  7756  7756 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 10:52:53.956  7756  7756 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 10:52:53.956  1485  1485 D MenuAppsGridFragment: onResume
,08-26 10:52:53.956  1485  1485 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 10:52:53.956  1485  1485 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 10:52:53.976  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter,
,08-26 10:52:53.976  1441  1441 D PersonaManager: isKioskContainerExistOnDevice,
,08-26 10:52:53.976  1441  1441 D RegisteredServicesCache: empty dynamic service,
,08-26 10:52:53.976  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 10:52:53.986  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 10:52:53.986  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
08-26 10:52:53.986  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:53.986  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 10:52:53.996  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 10:52:53.996  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 10:52:53.996  1018  1124 V NetworkStats: performPollLocked() took 9ms
,08-26 10:52:53.996  1018  1475 D ActivityManager: handle home activity for 0
,08-26 10:52:53.996  1018  1475 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 10:52:54.006  1018  1475 D KnoxTimeoutHandler: post home show event for user 0
08-26 10:52:54.006  1018  1475 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 10:52:54.006  1018  1475 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 10:52:54.006  1018  1475 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 10:52:54.006  1485  1485 D Launcher.HomeView: onPause
,08-26 10:52:54.006  1485  1485 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 10:52:54.016  7756  7756 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 10:52:54.016  7756  7756 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 10:52:54.016  7756  7756 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 10:52:54.016  7756  7756 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:54.016  1018  1481 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-26 10:52:54.016  1018  1481 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 10:52:54.026   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-26 10:52:54.026  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 10:52:54.036  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 10:52:54.036  1018  4342 D InputDispatcher: Focus entered window: 1485
,08-26 10:52:54.036  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 10:52:54.036  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 10:52:54.046  1018  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 10:52:54.046  1792  1792 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 10:52:54.046  1485  1485 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 10:52:54.046  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.046  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.046  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.046  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:54.056  7777  7777 E Zygote  : MountEmulatedStorage()
08-26 10:52:54.056  7777  7777 E Zygote  : v2
08-26 10:52:54.056  7777  7777 I libpersona: KNOX_SDCARD checking this for 10031
08-26 10:52:54.056  7777  7777 I libpersona: KNOX_SDCARD not a persona
08-26 10:52:54.056  7777  7777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:54.066  7777  7777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:54.066  7777  7777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:54.076  1018  1498 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7777 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-26 10:52:54.076  1485  1485 V ActivityThread: updateVisibility : ActivityRecord{235d941c token=android.os.BinderProxy@383db0f6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-26 10:52:54.076  1485  1485 D Launcher.HomeView: onStop
,08-26 10:52:54.086  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 10:52:54.086  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.086  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.086  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.086  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.086  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 10:52:54.096  1018  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 10:52:54.096  1018  1030 D SecContentProvider2: mCursor = null
,08-26 10:52:54.106  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:54.106  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 10:52:54.106  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 10:52:54.106  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 10:52:54.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 10:52:54.116  7777  7777 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 10:52:54.116  7777  7777 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:54.116  7792  7792 E Zygote  : MountEmulatedStorage()
08-26 10:52:54.116  7792  7792 I libpersona: KNOX_SDCARD checking this for 10121
08-26 10:52:54.116  7792  7792 E Zygote  : v2
08-26 10:52:54.116  7792  7792 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:54.116  7792  7792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:54.116  1018  1044 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7792 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 10:52:54.126  1018  1483 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-26 10:52:54.126  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:54.126  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-26 10:52:54.126  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:54.126  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder,
08-26 10:52:54.126  7792  7792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 10:52:54.126  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 10:52:54.126  7792  7792 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 10:52:54.126  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 10:52:54.126  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-26 10:52:54.136  1018  1031 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6847 uid 10171
,08-26 10:52:54.136  1018  7798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 10:52:54.146  1875  1875 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 10:52:54.156  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 10:52:54.156  1018  3370 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-26 10:52:54.156  1018  1018 D CrashAnrDetector: processName: com.test.thalitest
08-26 10:52:54.156  1018  1018 D CrashAnrDetector: broadcastEvent : com.test.thalitest data_app_crash
08-26 10:52:54.156  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-26 10:52:54.156  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
08-26 10:52:54.156  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-26 10:52:54.166  2604  6066 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-26 10:52:54.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-26 10:52:54.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 10:52:54.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 10:52:54.166  1792  1792 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 10:52:54.176  7792  7792 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:54.176  7792  7792 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:54.196  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 10:52:54.196  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 10:52:54.206  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 10:52:54.206  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-26 10:52:54.206  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 10:52:54.206  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 10:52:54.206  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 10:52:54.216  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-26 10:52:54.216  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-26 10:52:54.216  1018  1043 W TextServicesManagerService: no available spell checker services found
,08-26 10:52:54.216  1792  1792 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 10:52:54.226  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:54.226  7792  7792 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 10:52:54.226  7792  7792 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:54.236  1172  1172 I StatusBar: Icon Only
,08-26 10:52:54.236  1172  1172 D PanelView: There is/are notification(s) 
,08-26 10:52:54.236  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 10:52:54.236  1018  1059 I art     : Explicit concurrent mark sweep GC freed 81606(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/37MB, paused 12.898ms total 279.676ms
,08-26 10:52:54.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:54.246  1792  1792 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 10:52:54.256  7809  7809 E Zygote  : MountEmulatedStorage()
08-26 10:52:54.256  7809  7809 E Zygote  : v2
08-26 10:52:54.256  7809  7809 I libpersona: KNOX_SDCARD checking this for 10001
08-26 10:52:54.256  7809  7809 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:54.256  7809  7809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 10:52:54.256  7809  7809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:54.256  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7809 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:54.256  7809  7809 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:54.266  7792  7792 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:54.276  1018  1059 D PackageManager: delete codoeFile: 
,08-26 10:52:54.276   323   323 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 21.650ms
,08-26 10:52:54.276  7809  7809 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:54.276  7809  7809 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:54.286  1018  1059 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-26 10:52:54.286  1018  1059 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-26 10:52:54.286  1018  1059 D PackageManager: result of delete: 1{48039837}
,08-26 10:52:54.296  1018  1049 W ActivityManager: mDVFSHelper.release()
,08-26 10:52:54.296  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b3bad3c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147683
08-26 10:52:54.296   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.715ms
,08-26 10:52:54.296  7792  7792 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 10:52:54.296  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.306  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.316  7792  7792 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 10:52:54.316   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 19.556ms
,08-26 10:52:54.326  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:54.326  1018  1498 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 10:52:54.326  7746  7746 D AndroidRuntime: Shutting down VM
,08-26 10:52:54.326  1018  1137 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-26 10:52:54.336  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.336  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:54.336  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:54.336  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
08-26 10:52:54.336  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.346  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.366  1018  4342 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 10:52:54.366  1018  4342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.366  1018  4342 W ActivityManager: userId = 0, bbcId = -10000
,08-26 10:52:54.366  1018  4342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 10:52:54.366  1018  4342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 10:52:54.376  7313  7313 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-26 10:52:54.386  7232  7232 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-26 10:52:54.396  2779  7828 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-26 10:52:54.396  2779  7828 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-26 10:52:54.396  2779  7828 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 10:52:54.396  7252  7252 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 10:52:54.406  7252  7252 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-26 10:52:54.406  7252  7252 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 10:52:54.416  7295  7295 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:54.416  7113  7830 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 10:52:54.416  7113  7830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 10:52:54.416  7113  7830 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 10:52:54.416  7113  7830 I System.out: (HTTPLog)-Thread-1275-23965591: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 10:52:54.416  7113  7830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 10:52:54.426  7295  7295 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 10:52:54.426  7295  7295 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-26 10:52:54.426  7295  7295 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-26 10:52:54.426  7252  7252 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 10:52:54.436  7252  7252 I SA      : [OR] == isSIMCardReady false ==
,08-26 10:52:54.436  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 10:52:54.436  7252  7252 I SA      : [SCU] == networkStateCheck == true
,08-26 10:52:54.436  7252  7252 I SA      : [DM] getCountryCodeFromCSC : PL
08-26 10:52:54.436  7252  7252 I SA      : isChinaCountryCode : false
08-26 10:52:54.436  7252  7252 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-26 10:52:54.436  7252  7252 I SA      : [OR] == networkStateCheck true ==
,08-26 10:52:54.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 10:52:54.436   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 10:52:54.436   278   987 D Netd    : getNetworkForDns: using netid 504 for uid 10102
08-26 10:52:54.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.446  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.446  2779  7828 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-26 10:52:54.456  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 10:52:54.456  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:54.456  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 10:52:54.456  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-26 10:52:54.456  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-26 10:52:54.456  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.456  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-26 10:52:54.456  7252  7252 I SA      : [OR] GetMyCountryZoneTask
08-26 10:52:54.456  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-26 10:52:54.456  7252  7252 I SA      : [OR] onReceive END
,08-26 10:52:54.456  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-26 10:52:54.466  2779  7828 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-26 10:52:54.466  2779  7828 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-26 10:52:54.466  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:54.476  7113  7830 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 10:52:54.476  1018  1467 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-26 10:52:54.476  1018  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.476  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:54.476  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:54.476  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-26 10:52:54.486  2779  7828 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-26 10:52:54.496  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.496  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.506  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 10:52:54.506  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 10:52:54.506  7252  7836 I SA      : [SRS] prepareGetMyCountryZone
,08-26 10:52:54.506  1018  1031 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-26 10:52:54.506  1018  1031 D SecContentProvider2: mCursor = null
,08-26 10:52:54.506  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.516  2779  7828 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-26 10:52:54.516  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 10:52:54.516  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 10:52:54.516  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.516  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 10:52:54.516  7252  7836 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 10:52:54.526  7252  7836 I SA      : [SSP] query invoked
,08-26 10:52:54.526  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 10:52:54.526  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 10:52:54.526  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 10:52:54.526  7113  7830 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 10:52:54.536  7252  7836 I SA      : [TPMU] GetMccFromDB : null
,08-26 10:52:54.536  7746  7746 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 10:52:54.546  1018  1475 I ActivityManager: Killing 7274:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-26 10:52:54.556  7252  7836 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-26 10:52:54.556  7252  7836 I SA      : [LBE] isSupportCheckDomainRegion : false
08-26 10:52:54.556  7252  7836 I SA      : [TPM] isNoProxy(default) : true
,08-26 10:52:54.556  1018  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 10:52:54.556  1018  1059 D PackageManager: userId{-1}
08-26 10:52:54.556  1018  1059 D PackageManager: andCode{true}
,08-26 10:52:54.566  1018  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.566  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.566  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.566  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 10:52:54.566  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 10:52:54.566  7252  7836 E File    : fail readDirectory() errno=2
,08-26 10:52:54.576  7839  7839 E Zygote  : MountEmulatedStorage()
08-26 10:52:54.576  7839  7839 E Zygote  : v2
08-26 10:52:54.576  7839  7839 I libpersona: KNOX_SDCARD checking this for 10003
08-26 10:52:54.576  7839  7839 I libpersona: KNOX_SDCARD not a persona
,08-26 10:52:54.576  7839  7839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 10:52:54.576  1018  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7839 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,08-26 10:52:54.576  7839  7839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 10:52:54.586  7839  7839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 10:52:54.606  7839  7839 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 10:52:54.606  7839  7839 D ActivityThread: Added TimaKeyStore provider
,08-26 10:52:54.616  1018  7774 D PersonaManager: isKioskContainerExistOnDevice
,08-26 10:52:54.686  7348  7348 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 10:52:54.696  1018  4352 I ActivityManager: Killing 6930:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-26 10:52:54.696  1485  1485 I Choreographer: Skipped 33 frames!  The application may be doing too much work on its main thread.
,08-26 10:52:54.706  7348  7348 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-26 10:52:54.706  1485  1485 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@383db0f6 time:148090
,08-26 10:52:54.706  7348  7348 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-26 10:52:54.716  7348  7348 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-26 10:52:54.716  1018  1481 I ActivityManager: Killing 7638:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 10:52:54.726  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 10:52:54 GMT+02:00 2016
,08-26 10:52:54.726  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 10:52:54.726  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.726  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:54.726  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 10:52:54.726  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 10:52:54.726  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 10:52:54.746  2914  2914 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 10:52:54.746  2914  2914 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 10:52:54.756  2914  2914 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 10:52:54.756  1018  1498 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-26 10:52:54.756  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-26 10:52:54.756  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
08-26 10:52:54.756  1018  1498 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 10:52:54.756  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps

```
